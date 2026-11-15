---
title: LE Audio
type: concept
aliases: [Bluetooth LE Audio, 低功耗音訊, Auracast, GMAP, LC3, Classic Audio]
tags: [藍牙, 通用概念, 低延遲]
sources: [sony-wh-1000xm6-help-guide, sennheiser-momentum-5-manual]
created: 2026-11-15
updated: 2026-11-15
---

# LE Audio

## 定義

Bluetooth 技術的聲音通訊標準，使用 LC3 編碼，特點是低延遲（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.40）。說明書把傳統的藍牙音訊連線稱為 **Classic Audio**（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.40）。

## 特性

- **編碼**：LC3（見[[bluetooth-codecs|藍牙音訊編碼]]）（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.101）。
- **低延遲、較不穩定**：優先維持低延遲，連線穩定性低於 Classic Audio；聲音斷續時改回 Classic Audio（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.40）。
- **GMAP（Gaming Audio Profile）**：LE Audio 的設定檔之一，提供超低延遲。以 LE Audio 連線時啟動支援 GMAP 的遊戲，會自動切換；手機也須相容（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.41）。
- **Auracast 廣播音訊**：LE Audio 的功能，讓一支手機的音樂同時在多副耳機上播放；連線裝置須支援（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.80）。

## 在 WH-1000XM6 上

- 支援的 LE Audio 相關模式：TMAP、GMAP、PBP（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.141）。
- 只能在聲音品質模式設為 **[Low latency]** 時使用；預設的 [Prioritize Sound Quality] 下不能用（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.100–101）。
- 手機與耳機都要支援 LE Audio，耳機軟體與應用程式須為最新版（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.40）。
- 使用不支援 LE Audio 的裝置或 Xperia 1 IV／5 IV 時，應用程式不顯示 [Low latency]（這兩款改用 [LE Audio Priority] 選項）（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.40）（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.100）。
- 設定步驟見 [[sony-wh-1000xm6-connection|XM6 配對與連線]]。
- LC3 續航：開降噪 30 小時，關閉 40 小時（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.29）。

### LE Audio 連線期間不能用的功能

依 [[sony-sound-connect|Sony Sound Connect]] 功能清單的標註（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.121）：

- 設定語音助理（操作時會聽到語音提示告知無法使用（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.8））
- [[quick-access|Quick Access]]
- 服務連結
- 設定聲音品質模式
- 簡易配對
- [[auto-switch|Auto Switch]]

## 三款的支援情況

| 型號 | LE Audio | 依據 |
|---|---|---|
| [[sony-wh-1000xm6\|Sony WH-1000XM6]] | 支援（LC3、GMAP、Auracast） | 說明指南有專章與設定步驟 |
| [[bose-qc-ultra-headphones-2nd-gen\|Bose QC Ultra 2]] | 未載 | 手冊完全沒有提到 |
| [[sennheiser-momentum-5\|Sennheiser MOMENTUM 5]] | 正文未載 | 編碼清單沒有 LC3；商標頁提到 Auracast，但沒有功能說明 |

Sony 出自（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.40）（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.141）；Sennheiser 出自（[[sennheiser-momentum-5-manual|MOMENTUM 5 說明書]]，p.43）（[[sennheiser-momentum-5-manual|MOMENTUM 5 說明書]]，p.46）。Sennheiser 另有一個「LE-MOMENTUM 5」的裝置名稱，說明書註明只用於藍牙低功耗（應用程式與耳機之間的通訊），不是 LE Audio（[[sennheiser-momentum-5-manual|MOMENTUM 5 說明書]]，p.19）（[[sennheiser-momentum-5-manual|MOMENTUM 5 說明書]]，p.43）。

## 各款獨有的特點

### Sony WH-1000XM6 獨有

- 三款中**唯一有 LE Audio 完整說明**的型號，包含 LC3、GMAP 遊戲低延遲與 Auracast 廣播音訊。
- 代價也只有 Sony 寫明：LE Audio 連線時多項應用程式功能停用，穩定性較低。

## 採用的型號

- [[sony-wh-1000xm6|Sony WH-1000XM6]]

## 相關概念

- [[bluetooth-codecs|藍牙音訊編碼]]、[[multipoint|多點連線]]

## 待查問題

- LE Audio 連線時能否使用多點連線（說明指南未說明）
- TMAP、PBP 各自的用途（說明指南只列名稱）
