---
title: 規劃 Microsoft 365 合規性 - GCC
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本指南適用于在美國聯邦、state、local、部落或 territorial 政府機構或其他實體中，處理政府法規和需求之相關資料的 IT 專業365人員，其使用 Microsoft 365 政府-GCC，以符合這些需求。
ms.openlocfilehash: cf5a5caa5cf0793141e7498006aff1224fbcc659
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652627"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>規劃 Microsoft 365 合規性– GCC

本指南適用于在美國聯邦、state、local、部落或 territorial 政府機構或其他實體中，處理政府法規和需求之相關資料的 IT 專業365人員，其使用 Microsoft 365 政府-GCC，以符合這些需求。

> [!NOTE]
> 如果您的組織已符合 Microsoft 365 政府-GCC 和 the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>步驟 1. 判斷您的組織是否需要 Microsoft 365 政府-GCC 和符合資格的需求

Microsoft 365 政府版的環境符合美國政府對雲端服務的需求，包括 FedRAMP 適中，以及刑事審判和聯邦稅收資訊系統的需求 (CJI 及 FTI 資料類型) 。

除了享有 Office 365 的功能之外，組織還受益于 Microsoft 365 政府版-GCC 所獨有的下列功能：

- 您組織的客戶內容與 Microsoft 的商業 Office 365 服務中的客戶內容有邏輯隔離。

- 組織的客戶內容儲存於美國境內。

- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。

- Microsoft 365 政府版-GCC 遵循美國公開部門客戶所需的認證和資格鑒定。

您可以在 [Office 365 政府版方案](https://products.office.com/government/compare-office-365-government-plans)（包括資格要求）中，找到有關適用于美國政府客戶的 Microsoft 365 政府版服務的詳細資訊。

[Office 365 US 政府服務描述](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)說明平臺的優點，其位於美國的符合規範需求。

> [!TIP]
> 您可能想要將服務描述中的資訊表格傳輸到 Excel 活頁簿中，並新增兩欄： **適用于我的組織，y/n** 及 **符合我的組織的需求**。 然後您可以與同事一起查看此清單，以確認此服務符合您組織的需求。

> [!NOTE]
> Microsoft 365 政府版-GCC 僅適用于美國。 非美國政府客戶可以選擇許多 [Office 365 政府方案](https://products.office.com/government/compare-office-365-government-plans)。

**決策點**： <br/>
- *決定 Microsoft 365 政府版-GCC 是否適用于您的組織。*
- *確認您的組織符合資格的需求。*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>步驟 2. 適用于 Microsoft 365 政府-GCC

確定此服務對您的組織而言是正確的，請啟動 [此服務的應用程式](https://products.office.com/government/eligibility-validation)。

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>步驟 3. 瞭解 Microsoft 365 政府-GCC 預設安全性設定

建議您在修改系統管理員和安全性設定之前，請先仔細檢查您的系統管理員和安全性設定，並考慮對規範的影響，再變更預設安全性設定。

**決策點**： *決定是否要修改任何預設的 Microsoft 365 政府-GCC 安全性設定，以先瞭解可能進行的任何變更的影響。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>步驟 4. 瞭解 Microsoft 365 政府中目前哪些功能目前無法使用或已停用（GCC<sup>1</sup> ）

為了符合政府雲端客戶的需求，Microsoft 365 政府版與企業版方案中有一些差異。 請參閱下表，以查看哪些功能可供使用。 請參閱 [這兒](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) ，以取得 Microsoft 365 藍圖上發行的最新規範產品更新。<br><br>

| 範圍 | 功能 | GCC 狀態 |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **資訊保護**              | 統一的標籤用戶端和掃描器         | 可以使用              |
|                                         | 完全相符的資料          | 可以使用              |
|                                         | 自動分類及標籤，供 Exchange Online、SharePoint 線上及 OneDrive                      | 推出中              |
|                                         | 自動分類及標籤 for Office app (Word、Excel、PowerPoint、Outlook) 跨平臺 (網頁、Android、iOS、Windows 及 Mac)  |  在開發              |
|                                         | 自動分類及標記 Office 用戶端 (行動)                                        | 在工程處理積壓工作              |
|                                         | 小組的自動分類和標籤                            | 在工程處理積壓工作 |
|                                         | 資料分類分析：綜述和內容瀏覽器                            | 在工程處理積壓工作 |
|                                         | 分析：在服務端使用自動標記的機器學習分類器                           | 在工程處理積壓工作  |
|                                         | 分析：在 Office app/用戶端使用自動標籤的機器學習分類器                           | 在工程處理積壓工作  |
|                                         | 基本 Office 365 郵件加密 (E3)                             | 可以使用              |
|                                         | Advanced Office 365 郵件加密 (E5)   | 可以使用              |
|                                         | Office 365 的客戶金鑰    | 可以使用 |
|                                         | 為客戶管理的金鑰布建生命週期提供您自己的金鑰 (BYOK)                             | 可以使用 |
|                                         | 存放您自己的金鑰 (HYOK) ，以跨越 Azure 資訊保護和 Active Directory () 高管制案例的 AD 版權管理 (預覽)                          | 可以使用 |
|                                         | 雙重金鑰加密                           | 可以使用 |
|                                         | 加密：在使用 WXP web 應用程式的加密檔上共同撰寫                           | 在工程處理積壓工作 |
|                                         | 資料遺失防護 (檔和電子郵件的 DLP)          | 可以使用 |
|                                         | DLP 用於小組聊天及通道交談         | 在開發 |
|                                         | DLP 端點 | 在工程處理積壓工作 |
| **資訊控管** | 資訊管理：電子郵件封存                                       | 可以使用              |
|                                         | 資訊管理：保留鎖定          | 可以使用              |
|                                         | 資訊管理：匯入 PST                      | 可以使用              |
|                                         | 資訊管理：手動非記錄保留標籤            | 可以使用 |
|                                         | 資訊管理： SharePoint 的預設保留標籤、商務文件庫、資料夾及檔集的 OneDrive;Exchange 收件匣;和 Office 365 群組 | 可以使用              |
|                                         | 資訊管理：整個組織的保留原則;特定位置或使用者。根據特定條件自動根據 (例如，關鍵字或機密資訊) ;根據事件                                       | 可以使用              |
|                                         | 資訊管理：小組的保留原則                            | 可以使用 |
|                                         | 資訊管理：使用 SharePoint Syntex 分類的保留標籤                            | 在工程處理積壓工作 |
|                                         | 資訊管理：具有 trainable 分類器的保留原則                            | 在工程處理積壓工作 |
|                                         | 資訊管理：小組會議錄製的保留原則                            | 在工程處理積壓工作 |
|                                         | 資訊管理： Yammer 的保留原則                            | 在工程處理積壓工作 |
|                                         | 記錄管理：手動分類的記錄標籤                           | 可以使用              |
|                                         | 記錄管理： SharePoint 的預設記錄標籤、商務文件庫、資料夾及檔組的 OneDrive和 Office 365 群組                              | 可以使用              |
|                                         | 記錄管理：根據特定條件自動記錄原則 (例如關鍵字或機密資訊) ;根據事件                            | 可以使用              |
|                                         | 記錄管理：處置評審  | 可以使用              |
|                                         | 記錄管理：檔案計畫管理員    | 可以使用 |
|                                         | 記錄管理：處置證明                            | 可以使用 |
|                                         | 記錄管理：記錄版本設定                            | 可以使用 |
|                                         | 記錄管理：規章記錄 (公開預覽)                          | 在開發 |
|                                         | 記錄管理：多階段處置評審 | 在工程處理積壓工作 |
|                                         | 記錄管理：使用 SharePoint Syntex 分類套用記錄標籤 | 在工程處理積壓工作 |
| **內部風險管理**             | 客戶加密箱                                | 可以使用            |
|                                         | 有問必答風險管理：小組、SharePoint 網站、電子郵件訊息的 Office 指示器                         | 在開發 |
|                                         | 內部使用者風險管理：透過使用者竊取資料                        | 在開發 |
|                                         | 有問必答風險管理：一般資料洩漏                                | 在開發              |
|                                         | 有問必答風險管理：調查有問必答風險管理提醒                                   | 在開發              |
|                                         | 內部人員風險管理：案例儀表板、內容瀏覽器和通知範本 | 在開發 |
|                                         | 有問必答風險管理：逐步進行調查以取得高級電子檔探索 | 在開發|
|                                         | 內部人員風險管理： Windows 10 組建1809和更高版本上的活動裝置指示器 | 在工程處理積壓工作|
|                                         | 有問必答風險管理：違反安全性原則的指示器 (預覽)  | 在工程處理積壓工作|
|                                         | 有問必答風險管理： Microsoft Defender for Endpoint 警示 (預覽的指示器)  | 在工程處理積壓工作|
|                                         | 有問必答風險管理：優先順序使用者 (預覽中的資料洩漏原則範本)  | 在工程處理積壓工作 |
|                                         | 有問必答風險管理：不滿使用者 (預覽的資料洩漏原則範本)  | 在工程處理積壓工作 |
|                                         | 有問必答風險管理：一般安全性原則違規原則範本 (預覽)  | 在工程處理積壓工作 |
|                                         | 有問必答風險管理：原則範本因優先順序使用者、去聲使用者、不滿使用者 (預覽的安全性原則違規)  | 在工程處理積壓工作 |
|                                         | 有問必答風險管理：原則自訂 (預覽)  | 在工程處理積壓工作 |
|                                         | 有問必答風險管理： (預覽中匯出提醒)  | 在工程處理積壓工作 |
|                                         | 有問必答風險管理：優先順序使用者群組 (預覽)  | 在工程處理積壓工作 |
|                                         | 通訊相容性 (包括。監察原則) ：建立客戶原則，3預先設定  | 推出中 |
|                                         | 通訊相容性 (包括。監察原則) ：對團隊、Exchange 及移除小組郵件的支援 | 推出中 |
|                                         | 通訊相容性 (包括。監察原則) ：存取警示;通知範本;通訊原則儀表板 | 推出中  |
|                                         | 通訊相容性 (包括。監察原則) ：提升以進行調查以取得高級電子檔探索 | 推出中 |
|                                         | 通訊相容性 (包括。監察原則) ：偵測成人內容 | 推出中 |
|                                         | 通訊相容性：偵測一段時間的重複行為違規代碼 | 推出中 |
|                                         | 通訊相容性：支援更細微的許可權 | 推出中 |
|                                         | 通訊相容性：分析小組使用部署信箱的使用者聊天資料 | 推出中 |
|                                         | 通訊相容性：利益範本衝突 | 在工程處理積壓工作 |
|                                         | 通訊相容性：能夠忽略電子郵件簽名或免責聲明 | 在工程處理積壓工作 |
|                                         | 通訊法規遵從性：「內幕風險管理」手持 | 在工程處理積壓工作 |
|                                         | 通訊相容性：原則狀況檢查和暫停原則的功能 | 在工程處理積壓工作 |
|                                         | 通訊相容性：在調查期間翻譯健康情況內容 | 在工程處理積壓工作 |
|                                         | 通訊相容性： Burnout 和 suicide 偵測 | 在工程處理積壓工作 |
|                                         | 資訊屏障 | 在工程處理積壓工作 |
|                                         | 特殊權限存取管理                    | 在工程處理積壓工作 |
| **探索 & 回應**                  | 核心 eDiscovery：就地保留                            | 可以使用              |
|                                         | 核心電子檔探索：審計                                 | 可以使用              |
|                                         | 核心 eDiscovery：案例管理                                 | 可以使用              |
|                                         | 核心 eDiscovery：匯出                                          | 可以使用              |
|                                         | 核心 eDiscovery：原生匯出                                  | 可以使用              |
|                                         | 核心 eDiscovery： RMS 解密                                   | 可以使用              |
|                                         | 核心 eDiscovery： Microsoft 規範中心擴充支援，可在 SharePoint 和 OneDrive 商務用回收站中搜尋及匯出專案                                        | 在開發              |
|                                         | Advanced eDiscovery：高級處理                             | 可以使用 |
|                                         | Advanced eDiscovery：儀表板                                 | 可以使用 |
|                                         | Advanced eDiscovery：電子郵件執行緒                   | 可以使用 |
|                                         | Advanced eDiscovery： Export (下載、匯出、新增至另一個 view set)                                           | 可以使用 |
|                                         | Advanced eDiscovery：篩選                               | 可以使用 |
|                                         | Advanced eDiscovery：小組私人通道訊息的法律封存                 | 可以使用 |
|                                         | Advanced eDiscovery：接近重複識別                                         | 可以使用 |
|                                         | Advanced eDiscovery：非 custodial 資料來源                                         | 可以使用 |
|                                         | Advanced eDiscovery：非 Office 365 攝取                                      | 可以使用 |
|                                         | Advanced eDiscovery：預測編碼                                       | 可以使用 |
|                                         | Advanced eDiscovery：已使用載入檔案處理匯出                   | 可以使用 |
|                                         | Advanced eDiscovery：密文                        | 可以使用 |
|                                         | Advanced eDiscovery：複查集                                     | 可以使用 |
|                                         | Advanced eDiscovery：審閱資料 (查詢資料、智慧標籤、儀表板) 及批註 (密文)                              | 可以使用 |
|                                         | Advanced eDiscovery：搜尋字詞報告                        | 可以使用 |
|                                         | Advanced eDiscovery：單一專案錯誤修正                              | 可以使用 |
|                                         | Advanced eDiscovery：支援 PST 匯出                              | 可以使用 |
|                                         | Advanced eDiscovery：從 OneDrive 和 SharePoint 線上 (新式附件支援連結內容)                               | 可以使用 |
|                                         | Advanced eDiscovery：標記                              | 可以使用 |
|                                         | Advanced eDiscovery：承租人報告                              | 可以使用 |
|                                         | Advanced eDiscovery：主題                              | 可以使用 |
|                                         | Advanced eDiscovery： Viewer                              | 可以使用 |
|                                         | Advanced eDiscovery： Microsoft 規範中心的 Yammer 高級 eDiscovery                              | 可以使用 |
|                                         | Advanced eDiscovery： Microsoft 規範中心擴充支援，可在 SharePoint 和 OneDrive 進行商務用回收站中搜尋及匯出專案                              | 在開發 |
|                                         | Advanced eDiscovery：小組反應支援                              | 在開發 |
|                                         | 基本審核                              | 可以使用 |
|                                         | 高級審核：對重要事件的存取 (例如，mailitemsaccessed)                               | 可以使用 |
|                                         | 高級審核：增加管理活動 API 的頻寬                              | 可以使用 |
|                                         | 高級審計：小組私人通道郵件的法律封存                               | 可以使用 |
|                                         | 高級審核：記錄保留 (1 年)                                | 推出中 |
|                                         | 高級審核：安全性與合規性中心                               | 可以使用 |
|                                         | 高級審核：審核記錄的字詞保留時間 (10 年)                                | 在工程處理積壓工作 |
|                                         | 高級審計：郵件轉寄和郵件傳送事件                               | 在工程處理積壓工作 |
|                                         | 高級審核：已處理的審計深入資訊                               | 在工程處理積壓工作 |
|                                         | 高級審計：在 Exchange Online 中和 SharePoint Online 中搜尋字詞事件                              | 在工程處理積壓工作 |
|    **規範管理**            | Microsoft 365 安全性與合規性中心                              | 可以使用 |
|                                         | 合規性管理員                              | 可以使用 |
|                                         | Microsoft 雲端 App 安全性                              | 在工程處理積壓工作 |
|                                         | 雙位元組字元支援                              | 在工程處理積壓工作 |
|    **生態**            | 適用于 Advanced eDiscovery 的圖形 APIs                              | 在開發 |
|                                         | 第一方資料連線器                              | 在工程處理積壓工作 |
|                                         | 協力廠商資料連接器                              | 在工程處理積壓工作 |
|                                         | 小組的圖形 APIs 匯出資料                              | 在工程處理積壓工作 |




<sup>1</sup> 識別的狀態視專案方案和優先順序重新評估而變更。<br/>

**決策點**： *決定相容性功能是否符合貴組織的需求。*