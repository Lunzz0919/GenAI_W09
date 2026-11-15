---
title: 藍牙音訊編碼
type: concept
aliases: [Codec, 轉碼器, 編解碼器, SBC, AAC, LC3, 藍牙編碼]
tags: [藍牙, 編碼, 通用概念]
sources: [sony-wh-1000xm6-help-guide, bose-qc-ultra-headphones-2nd-gen-owners-guide, sennheiser-momentum-5-manual]
created: 2026-11-15
updated: 2026-11-15
---

# 藍牙音訊編碼（Bluetooth Audio Codec）

## 定義

透過藍牙無線傳輸聲音時使用的音訊編碼演算法；Sony 的說明書稱為「轉碼器」（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.101）。

## 各編碼

| 編碼 | 擁有者 | 說明 | 出處 |
|---|---|---|---|
| SBC | 藍牙標準 | Subband Codec；所有藍牙裝置都支援的標準編碼。Sennheiser 稱為「一般音質」 | S p.101／M p.17 |
| AAC | — | Advanced Audio Coding；主要用於 iPhone 等 Apple 產品，音質高於 SBC | S p.101 |
| [[ldac\|LDAC]] | Sony | 可傳輸 High-Resolution Audio 內容 | S p.101 |
| LC3 | 藍牙標準 | Low Complexity Communication Codec；[[le-audio\|LE Audio]] 的編碼，低延遲 | S p.101 |
| [[aptx\|aptX／aptX HD／aptX Lossless／aptX Adaptive]] | Qualcomm | Sennheiser 列為高解析音訊編碼方式；aptX Adaptive 另由 [[snapdragon-sound\|Snapdragon Sound]] 裝置自動啟用 | M p.17／B p.32 |

> 表格中的 S、B、M 分別指 [[sony-wh-1000xm6-help-guide|XM6 說明指南]]、[[bose-qc-ultra-headphones-2nd-gen-owners-guide|QC Ultra 2 使用手冊]]、[[sennheiser-momentum-5-manual|MOMENTUM 5 說明書]]，數字為 PDF 頁數。「未載」表示該說明書沒有提到，不代表沒有這項功能。

## 三款對照

| 編碼 | Sony WH-1000XM6 | Bose QC Ultra 2 | Sennheiser MOMENTUM 5 |
|---|---|---|---|
| SBC | 支援 | 未載 | 支援 |
| AAC | 支援 | 未載 | 支援 |
| LDAC | 支援 | 未載 | 未列 |
| LC3（LE Audio） | 支援 | 未載 | 未列 |
| aptX | 未列 | 未載 | 支援 |
| aptX HD | 未列 | 未載 | 支援 |
| aptX Lossless | 未列 | 未載 | 支援 |
| aptX Adaptive | 未列 | 支援 | 支援 |
| 出處 | S p.141 | B p.32 | M p.43 |

「未列」表示該型號有完整的編碼清單而其中沒有這一項；「未載」表示手冊根本沒有編碼清單。Bose 的手冊只提到 aptX Adaptive。

## 運作方式

- 三款都會依播放裝置自動選擇編碼，不需在耳機上手動切換（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.101）（[[bose-qc-ultra-headphones-2nd-gen-owners-guide|QC Ultra 2 使用手冊]]，p.32）（[[sennheiser-momentum-5-manual|MOMENTUM 5 說明書]]，p.17）。
- Sony：裝置若支援比 SBC 更好的編碼，可能要先在裝置上設定；以 LE Audio 連線時一律用 LC3（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.101）。
- Sennheiser：來源支援任一種 aptX 或 AAC 時自動用最高品質，否則用 SBC（[[sennheiser-momentum-5-manual|MOMENTUM 5 說明書]]，p.17）。

## 各款獨有的特點

### Sony WH-1000XM6 獨有

- **LDAC**：三款中唯一支援，且完全不列 aptX（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.141）。
- **LC3／LE Audio**：三款中唯一明列（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.141）。
- **依編碼公布續航**：LDAC 開降噪 26 小時，其餘 30 小時（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.29）。
- 應用程式會顯示目前使用的編碼（[[sony-wh-1000xm6-help-guide|XM6 說明指南]]，p.121）。

### Bose QC Ultra Headphones (2nd Gen) 獨有

- 以 **Snapdragon Sound** 品牌呈現，而不是列出編碼清單；需要認證裝置（[[bose-qc-ultra-headphones-2nd-gen-owners-guide|QC Ultra 2 使用手冊]]，p.32）。

### Sennheiser MOMENTUM 5 獨有

- **aptX 全系列**，包含 aptX HD 與 aptX Lossless（[[sennheiser-momentum-5-manual|MOMENTUM 5 說明書]]，p.43）。
- 規格表列出的編碼種類最多（6 種）（[[sennheiser-momentum-5-manual|MOMENTUM 5 說明書]]，p.43）。

## 觀察

進階編碼分成兩個陣營：Sony 的 LDAC，與 Qualcomm 的 aptX（Bose、Sennheiser 採用）。對只支援 AAC 的 iPhone 來說，這項差異不存在——Sennheiser 的續航測試條件就是 iPhone（[[sennheiser-momentum-5-manual|MOMENTUM 5 說明書]]，p.43）。

## 採用的型號

- [[sony-wh-1000xm6|Sony WH-1000XM6]]
- [[bose-qc-ultra-headphones-2nd-gen|Bose QC Ultra Headphones (2nd Gen)]]
- [[sennheiser-momentum-5|Sennheiser MOMENTUM 5]]

## 相關概念

- [[ldac|LDAC]]、[[aptx|aptX]]、[[le-audio|LE Audio]]、[[snapdragon-sound|Snapdragon Sound]]、[[dsee-extreme|DSEE Extreme]]

## 待查問題

- Bose 是否支援 SBC、AAC 以外的其他編碼（LC3、aptX Lossless）
- 各編碼的位元率與延遲（目前只有 LDAC 有數字）
