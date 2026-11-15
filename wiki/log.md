---
title: 紀錄
type: log
---

# 操作紀錄

只增不改。格式：`## [YYYY-MM-DD] 類型 | 標題`，類型為 ingest、query、lint、schema。

## [2026-11-15] schema | 建立 wiki
- 新增：AGENTS.md、wiki/index.md、wiki/log.md、wiki/overview.md
- 建立目錄：raw/（manuals、specs、assets）、wiki/（sources、models、brands、concepts、comparisons）
- 備註：範圍為耳機全領域；主要來源為官方說明書與規格 PDF；ingest 採逐篇討論

## [2026-11-15] schema | 新增附屬速查頁與品牌專屬功能規則
- 更新：AGENTS.md——新增 `reference` 頁面類型（型號的 operations／connection 附屬頁）、品牌專屬功能一律獨立成 concepts 頁、查表型內容完整收錄、表格內 wikilink 與頁碼的寫法
- 備註：依使用者在第一次 ingest 討論中的決定

## [2026-11-15] ingest | Sony WH-1000XM6 說明指南（繁體中文）
- 來源：raw/manuals/sony-wh-1000xm6-help-guide-zh-tw.pdf（142 頁）
- 新增：sources/sony-wh-1000xm6-help-guide
- 新增：models/sony-wh-1000xm6、models/sony-wh-1000xm6-operations、models/sony-wh-1000xm6-connection
- 新增：brands/sony
- 新增（通用概念）：concepts/active-noise-cancellation、ambient-sound-mode、bluetooth-codecs、le-audio、multipoint
- 新增（Sony 專屬）：concepts/ldac、auto-nc-optimizer、quick-attention-mode、speak-to-chat、dsee-extreme、360-reality-audio、quick-access、sony-sound-connect、auto-switch、sony-voice-control、head-gesture
- 更新：index.md、overview.md
- 備註：說明指南未載驅動單體、降噪晶片、上市日期、價格；LDAC／LE Audio 與多點連線能否並用待查；Sound Connect 中「適應聲音控制」「BGM 效果」「Auto Play」「安全聆聽」「頭部追蹤」只有名稱沒有說明

## [2026-11-15] ingest | Bose QuietComfort Ultra Headphones (2nd Gen) 使用手冊（英文）
- 來源：raw/manuals/bose-qc-ultra-headphones-2nd-gen-owners-guide-en.pdf（50 頁）
- 新增：sources/bose-qc-ultra-headphones-2nd-gen-owners-guide
- 新增：models/bose-qc-ultra-headphones-2nd-gen、models/bose-qc-ultra-headphones-2nd-gen-operations、models/bose-qc-ultra-headphones-2nd-gen-connection
- 新增：brands/bose
- 新增（Bose 專屬）：concepts/bose-immersive-audio、bose-listening-modes、activesense、simplesync、bose-app、bose-shortcut
- 新增（第三方技術）：concepts/snapdragon-sound
- 新增（通用概念）：concepts/wear-detection、spatial-audio
- 更新：concepts/active-noise-cancellation、ambient-sound-mode、bluetooth-codecs、multipoint（補上 Bose 的做法與對照表）
- 更新：concepts/auto-switch、360-reality-audio、quick-access、sony-sound-connect、speak-to-chat、models/sony-wh-1000xm6（加上與 Bose 對應功能的連結）
- 更新：index.md、overview.md
- 備註：手冊內部有兩處不一致，已標註來源矛盾——快充 3 小時對 2.5 小時（p.36），連線燈號 10 秒對 5 秒（p.28 對 p.37）。手冊沒有規格表

## [2026-11-15] query | 建立 Sony WH-1000XM6 與 Bose QC Ultra Headphones (2nd Gen) 的比較頁
- 新增：comparisons/sony-wh-1000xm6-vs-bose-qc-ultra-2nd-gen
- 備註：只比較說明書能確認的功能有無與宣稱數字；降噪強度與音質沒有來源，不下判斷

## [2026-11-15] schema | 釐清概念頁與比較頁的分工
- 更新：AGENTS.md——概念頁依技術組織、長期累積各廠做法；比較頁依問題組織、針對特定型號下結論。新增第三方技術的歸類方式

## [2026-11-15] ingest | Sennheiser MOMENTUM 5 說明書（英文）
- 來源：raw/manuals/sennheiser-momentum-5-manual-en.pdf（47 頁）
- 新增：sources/sennheiser-momentum-5-manual
- 新增：models/sennheiser-momentum-5、models/sennheiser-momentum-5-operations、models/sennheiser-momentum-5-connection
- 新增：brands/sennheiser
- 新增（Sennheiser 專屬）：concepts/sennheiser-smart-control-plus、smart-pause
- 新增（第三方技術）：concepts/dolby-atmos、aptx
- 新增（通用概念）：concepts/battery-and-charging、wired-and-usb-audio、sidetone、wind-noise-reduction
- 重寫（改為三款對照，並加上「各款獨有的特點」）：concepts/wear-detection、spatial-audio、bluetooth-codecs
- 更新（加入 Sennheiser、三款對照表、「各款獨有的特點」）：concepts/active-noise-cancellation、ambient-sound-mode、multipoint、le-audio、snapdragon-sound
- 更新（加上「三款中的定位」）：17 個品牌專屬功能頁
- 更新：models/sony-wh-1000xm6、models/bose-qc-ultra-headphones-2nd-gen（相關型號）、index.md、overview.md
- 備註：說明書內部有四處不一致，已標註來源矛盾——重設秒數（p.41 對 p.42）、LED 時數（p.9–10 對 p.15）、斷線語音提示（p.11 對 p.41）、保固期（p.45）。Auracast、Fast Pair、Qi 只出現在商標頁，不記為已支援

## [2026-11-15] query | 把比較頁改為三款合一
- 新增：comparisons/flagship-anc-headphones-comparison（Sony、Bose、Sennheiser 三款，含「各款獨有的功能」）
- 移除：comparisons/sony-wh-1000xm6-vs-bose-qc-ultra-2nd-gen（內容併入新頁，檔案改名）
- 更新：所有指向舊比較頁的連結

## [2026-11-15] schema | 官方說明書為主、通用概念頁標註各款獨有的特點、比較頁合一
- 更新：AGENTS.md——(1) 以官方文件為主要來源，不主動建議第三方評測；(2) 通用概念頁固定包含對照表與「各款獨有的特點」；(3) 同類型號共用一個比較頁，新增型號時加欄而不另開新頁；(4) 品牌專屬功能頁加上「三款中的定位」段落

## [2026-11-15] schema | 新增 Present 工作流程
- 更新：AGENTS.md——新增「筆記 → 簡報逐頁內容 → HTML 簡報」三步流程、簡報的風格與技術規格；新增 log 類型 `present`
- 建立目錄：notes/、slides-outline/、presentations/
- 備註：筆記完全依 wiki 撰寫，wiki 沒有的明講；網路搜尋結果只列入建議參考文獻，分官方與第三方；簡報為深色底的簡潔清新風格，不放產品照片或商標
