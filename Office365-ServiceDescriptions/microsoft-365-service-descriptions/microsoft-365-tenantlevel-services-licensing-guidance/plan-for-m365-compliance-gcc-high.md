---
title: 規劃 Microsoft 365 合規性 - GCC High
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本指南適用于促進美國聯邦政府機構中的 Office 365 部署的 IT 專業人員，或是處理政府規定和需求之資料的其他實體，其使用 Microsoft 365 政府– GCC 高的方式，都適用于符合這些需求。
ms.openlocfilehash: 357cf30350ff2a3b21d7d9326e91c2c01d119b21
ms.sourcegitcommit: f7874215059c1e5a9d383da0539f87b6f85a57e6
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/25/2021
ms.locfileid: "52001909"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>規劃 Microsoft 365 合規性– GCC 高

本指南適用于促進美國聯邦政府機構中的 Office 365 部署的 IT 專業人員，或是處理政府規定和需求之資料的其他實體，其使用 Microsoft 365 政府– GCC 高的方式，都適用于符合這些需求。

> [!NOTE]
>如果您的組織已符合 Microsoft 365 政府– GCC 的高資格需求，且已套用至程式並被公認，您可以略過步驟1和2，直接移至步驟3。
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>步驟 1. 判斷您的組織是否需要 Microsoft 365 政府– GCC 高並符合資格需求

Microsoft 365 政府版高環境符合美國政府對雲端服務的需求。 除了享受 Office 365 的功能之外，組織還會受益于 Microsoft 365 政府（GCC 高）特有的下列功能：

- 您組織的客戶內容與 Microsoft 的商業 Office 365 服務中的客戶內容有邏輯隔離。
- 組織的客戶內容儲存於美國境內。
- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。
- Microsoft 365 政府– GCC 高遵循美國公開部門客戶所需的認證和資格鑒定。

您可以在 [Office 365 政府版方案](https://products.office.com/government/compare-office-365-government-plans)（包括資格要求）中找到有關 Microsoft 365 政府– GCC 優質產品的詳細資訊。

[Office 365 US 政府服務描述](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)說明平臺的優點，其位於美國的符合規範需求。

> [!TIP]
> 您可能想要將服務描述中的資訊表格傳輸到 Excel 活頁簿中，並新增兩欄： **適用于我的組織，y/n** 及 **符合我的組織的需求**。 然後您可以與同事一起查看此清單，以確認此服務符合您組織的需求。

**決策點**：<br/>
- *決定 Microsoft 365 政府– GCC-High 是否適用于您的組織。*
- *確認您的組織符合資格的需求。*

> [!NOTE]
> Microsoft 365 政府-GCC High 僅限美國境內。 非美國政府客戶可以選擇許多 [Office 365 政府方案](https://products.office.com/government/compare-office-365-government-plans)。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>步驟 2. 適用于 Microsoft 365 政府– GCC-High

確定此服務對您的組織而言是正確的，請啟動 [此服務的應用程式](https://products.office.com/government/eligibility-validation)。
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>步驟 3. 瞭解 Microsoft 365 政府– GCC-High 預設安全性設定

建議您在修改系統管理員和安全性設定之前，請先仔細檢查您的系統管理員和安全性設定，並考慮對規範的影響，再變更預設安全性設定。

**決策點**： *決定是否要修改任何預設的 Microsoft 365 政府– GCC-High 安全性設定，並解決以先瞭解可能進行的任何變更的影響。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>步驟 4. 瞭解 Microsoft 365 政府中目前可使用或已停用的功能為何功能-GCC-高<sup>1</sup>

為了符合我們政府雲端客戶的需求，Microsoft 365 政府– GCC-High 和企業方案之間有一些差異。 請參閱下表，以查看哪些功能可供使用。 請參閱 [這裡](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) ，以取得 Microsoft 365 藍圖發佈的最新規範產品更新。<br><br>

| 區域 | 功能 | GCC 高狀態 |
|------|---------|-----------------|
| **資訊保護** | 統一的標籤用戶端和掃描器 | 可以使用 |
| | 完全相符的資料 | 可以使用 |
| 敏感度標籤 | 自動分類及標籤，供 Exchange Online、SharePoint 線上及 OneDrive | 可以使用 |
| 敏感度標籤 | 自動分類及標籤 for Office app (Word、Excel、PowerPoint、Outlook) 跨 web、Android、iOS、Windows 及 Mac | 可以使用 |
| 敏感度標籤 | 自動分類及標記 Office 用戶端 (行動)  | 在工程處理積壓工作 |
| 敏感度標籤 | 針對團隊、Microsoft 365 群組和 SharePoint 網站的自動分類和標籤 | 可以使用 |
| 分析 | 資料分類分析：綜述和內容瀏覽器 | 可以使用 |
| 分析 | 分析：在服務端使用自動標記的機器學習分類器 | 在工程處理積壓工作 |
| 分析 | 分析：在 Office app/用戶端使用自動標籤的機器學習分類器 | 推出中 |
| 加密 | 基本 Office 365 郵件加密 (E3)  | 可以使用 |
| 加密 | Advanced Office 365 郵件加密 (E5)  | 可以使用 |
| 加密 | Office 365 的客戶金鑰 | 可以使用 |
| 加密 | 客戶金鑰： Microsoft 365 的靜態資料加密 | 推出中 |
| 加密 | 為客戶管理的金鑰布建生命週期提供您自己的金鑰 (BYOK)  | 可以使用 |
| 加密 | 雙重金鑰加密 | 可以使用 |
| 加密 | 使用 Microsoft 受管理金鑰的 Exchange Online 服務加密 | 可以使用 |
| 資料外洩防護 | 資料遺失防護 (檔和電子郵件的 DLP)  | 可以使用 |
| 資料外洩防護 | DLP 用於小組聊天及通道交談 | 可以使用 |
| 資料外洩防護 | DLP 端點 | 在開發 |
| 資料外洩防護 | 警示儀表板 | 在開發 |
| 資料外洩防護 | 概觀頁面 | 在開發 |
| **資訊控管** | 保留及標記原則的自我調整範圍 | 在工程處理積壓工作 |
| | 資訊管理：電子郵件封存 | 可以使用 |
| | 資訊管理：商務文件庫、資料夾及檔組的 SharePoint/OneDrive 的預設保留標籤。Exchange 收件匣;和 Office 365 群組 | 可以使用 |
| | 資訊管理：匯入 PST | 可以使用 |
| | 資訊管理：手動非記錄保留標籤 | 可以使用 |
| | 資訊管理：保留鎖定 | 可以使用 |
| | 資訊管理：整個組織的保留原則;特定位置或使用者。根據特定條件自動根據 (例如，關鍵字或機密資訊) ;根據事件 | 可以使用 |
| | 資訊管理：小組的保留原則 | 推出中 |
| | 資訊管理：小組會議錄製的保留原則 | 在開發 |
| | 資訊管理：小組專用通道的保留原則 | 在工程處理積壓工作 |
| | 資訊管理：小組共用通道的保留原則 | 在工程處理積壓工作 |
| | 資訊管理：具有 trainable 分類器的保留原則 | 在開發 |
| | 資訊管理： Yammer 的保留原則 | 在工程處理積壓工作 |
| 記錄管理 | 刪除記錄標籤的能力 | 在開發 |
| 記錄管理 | 手動套用記錄標籤 | 可以使用 |
| 記錄管理 | 套用 SharePoint 的預設記錄標籤、商務文件庫、資料夾及檔組的 OneDrive;和 Office 365 群組 | 可以使用 |
| 記錄管理 | 根據特定條件自動套用記錄原則 (例如關鍵字或機密資訊) ;根據事件 | 可以使用 |
| 記錄管理 | 使用 trainable 的分類器自動套用記錄原則 | 在開發 |
| 記錄管理 | 處置檢閱 | 可以使用 |
| 記錄管理 | 檔案計劃管理員 | 可以使用 |
| 記錄管理 | 多階段處置評審 | 在工程處理積壓工作 |
| 記錄管理 | 處置證明 | 可以使用 |
| 記錄管理 | 在保留期間結束時，電源自動化流程 | 在工程處理積壓工作 |
| 記錄管理 | 保留和自動標記雲端附件 | 在工程處理積壓工作 |
| 記錄管理 | 記錄版本設定 | 可以使用 |
| 記錄管理 | 法規記錄 | 可以使用 |
| 記錄管理 | 使用 SharePoint Syntex 分類套用記錄標籤 | 在工程處理積壓工作 |
| **內部風險管理** | 客戶加密箱 | 可以使用 |
| 通訊合規性 | 能夠忽略電子郵件簽章或免責聲明 | 在開發 |
| 通訊合規性 | 能夠設定通訊相容性原則的保留期間 | 在開發 |
| 通訊合規性 | 存取警示;通知範本;通訊原則儀表板 | 可以使用 |
| 通訊合規性 | 使用部署信箱分析小組聊天的使用者資料 | 可以使用 |
| 通訊合規性 | 利益衝突範本 | 可以使用 |
| 通訊合規性 | 建立客戶原則，3預先設定 | 可以使用 |
| 通訊合規性 | 偵測成人內容 | 在工程處理積壓工作 |
| 通訊合規性 | 偵測一段時間的重複行為違規代碼 | 可以使用 |
| 通訊合規性 | 針對高級電子檔探索進行升級以進行調查 | 可以使用 |
| 通訊合規性 | 有問必答風險管理手持 | 在工程處理積壓工作 |
| 通訊合規性 | 利用光學字元辨識提取和評估郵件 | 在開發 |
| 通訊合規性 | 非常小的企業新簡化的視圖 | 在開發 |
| 通訊合規性 | 原則狀況檢查和暫停原則的功能 | 在工程處理積壓工作 |
| 通訊合規性 | Power 自動化整合 | 在工程處理積壓工作 |
| 通訊合規性 | 支援適用于威脅、目標騷擾和 profanities 分類符的七種語言 | 在工程處理積壓工作 |
| 通訊合規性 | 支援更細微的許可權 | 可以使用 |
| 通訊合規性 | 支援小組、Exchange 及移除小組訊息的能力 | 可以使用 |
| 通訊合規性 | Microsoft 小組整合 | 在工程處理積壓工作 |
| 通訊合規性 | 小組交談內容 | 在工程處理積壓工作 |
| 通訊合規性 | 在調查期間翻譯內容 | 在工程處理積壓工作 |
| 客戶加密箱 | 客戶加密箱 | 可以使用 |
| 資訊屏障 | 資訊屏障 | 在開發 |
| 測試人員風險管理 | 案例儀表板 | 可以使用 |
| 測試人員風險管理 | 由去聲使用者竊取資料 | 可以使用 |
| 測試人員風險管理 | Windows 10 組建1809及更高版本上活動的裝置指示器 | 在工程處理積壓工作 |
| 測試人員風險管理 | 針對高級電子檔探索進行升級以進行調查 | 可以使用 |
| 測試人員風險管理 | 匯出提醒 | 在工程處理積壓工作 |
| 測試人員風險管理 | 一般資料洩漏 | 可以使用 |
| 測試人員風險管理 | 違反安全性原則的標記 | 在工程處理積壓工作 |
| 測試人員風險管理 | Microsoft Defender for Endpoint 警示的標記 | 在工程處理積壓工作 |
| 測試人員風險管理 | 有問必答風險管理活動瀏覽器 | 在開發 |
| 測試人員風險管理 | 有問必答風險管理內容瀏覽器 | 在開發 |
| 測試人員風險管理 | 調查有問必答風險管理提醒 | 可以使用 |
| 測試人員風險管理 | 通知範本 | 可以使用 |
| 測試人員風險管理 | 用於小組、SharePoint 網站、電子郵件訊息的 Office 指示器 | 可以使用 |
| 測試人員風險管理 | 依優先使用者的資料洩漏原則範本 | 在工程處理積壓工作 |
| 測試人員風險管理 | 不滿使用者的資料洩漏原則範本 | 在工程處理積壓工作 |
| 測試人員風險管理 | 一般安全性原則違規的原則範本 | 在工程處理積壓工作 |
| 測試人員風險管理 | 原則範本因優先順序使用者、去聲使用者、不滿使用者以外的安全性原則違規 | 在工程處理積壓工作 |
| 測試人員風險管理 | 原則自訂 | 在工程處理積壓工作 |
| 測試人員風險管理 | 優先順序使用者群組 | 在工程處理積壓工作 |
| 測試人員風險管理 | Power 自動化整合 | 在開發 |
| 測試人員風險管理 | Microsoft 小組整合 | 在工程處理積壓工作 |
| 特殊權限存取管理 | 特殊權限存取管理 | 在工程處理積壓工作 |
| **探索 &amp; 回應** | 核心電子檔探索：審計 | 可以使用 |
| 電子文件探索 | 核心 eDiscovery：案例管理 | 可以使用 |
| 電子文件探索 | 核心 eDiscovery：匯出 | 可以使用 |
| 電子文件探索 | 核心 eDiscovery：就地保留 | 可以使用 |
| 電子文件探索 | 核心 eDiscovery：原生匯出 | 可以使用 |
| 電子文件探索 | 核心 eDiscovery： RMS 解密 | 可以使用 |
| 電子文件探索 | 核心電子檔探索：搜尋 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：高級處理 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：保管人 to 工作負載對應 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：保管人通訊 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：儀表板 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：中文、日文和韓文的雙位元組支援 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：電子郵件執行緒 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery： Export (下載、匯出、新增至另一個評審集)  | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：篩選 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：保留優化 | 在開發 |
| 電子文件探索 | Advanced eDiscovery：小組私人通道訊息的法律封存 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery： Microsoft 規範中心擴充支援，可在 SharePoint 和 OneDrive 進行商務用回收站中搜尋及匯出專案 | 在開發 |
| 電子文件探索 | Advanced eDiscovery：接近重複識別 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：全新的預測編碼模組 | 在工程處理積壓工作 |
| 電子文件探索 | Advanced eDiscovery：非 custodial 資料來源 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：非 Office 365 攝取 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：預測編碼 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：已使用載入檔案處理匯出 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：密文 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：複查集 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：審閱資料 (查詢資料、智慧標籤、儀表板) 及批註 (密文)  | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：搜尋字詞報告 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：單一專案錯誤修正 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：支援 PST 匯出 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：從 OneDrive 和 SharePoint 線上 (新式附件支援連結內容)  | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：支援小組反應 | 在工程處理積壓工作 |
| 電子文件探索 | Advanced eDiscovery：標記 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：承租人報告 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery：主題 | 可以使用 |
| 電子文件探索 | Advanced eDiscovery： Viewer | 可以使用 |
| 電子文件探索 | Advanced eDiscovery： Microsoft 規範中心的 Yammer 高級 eDiscovery | 可以使用 |
| 稽核 | 基本審核 | 可以使用 |
| 稽核 | 高級審核：對重要事件的存取 (例如， *MailItemsAccessed*)  | 可以使用 |
| 稽核 | 高級審核：增加管理活動 API 的頻寬 | 可以使用 |
| 稽核 | 高級審計：小組私人通道郵件的法律封存 | 可以使用 |
| 稽核 | 高級審核：記錄保留 (1 年)  | 可以使用 |
| 稽核 | 高級審核：審核記錄的字詞保留時間 (10 年)  | 在開發 |
| 稽核 | 高級審計：郵件轉寄和郵件傳送事件 | 可以使用 |
| 稽核 | 高級審計： Microsoft 365 安全性與合規性中心可用性 | 可以使用 |
| 稽核 | 高級審計：在 Exchange Online 中和 SharePoint Online 中搜尋字詞事件 | 在工程處理積壓工作 |
| **規範管理** | Microsoft 365 安全性與合規性中心 | 可以使用 |
| | 合規性管理員 | 可以使用 |
| | 雙位元組字元支援 | 可以使用 |
| | Microsoft Cloud App Security | 可以使用 |
| **生態** | 適用于 Advanced eDiscovery 的圖形 APIs | 在開發 |
| | 小組的圖形 APIs 匯出資料 | 在工程處理積壓工作 |
| | 第一方資料連線器 | 在工程處理積壓工作 |
| | 協力廠商資料連接器 | 在開發 |

<sup>1</sup> 識別的狀態視專案方案和優先順序重新評估而變更。<br/>

**決策點**： *決定相容性功能是否符合貴組織的需求。*