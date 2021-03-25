---
title: 適用於 Office 365 的 Microsoft Defender 服務描述
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender for Office 365 是一項雲端式電子郵件篩選服務，可協助您的組織抵禦未知的惡意程式碼和病毒，方法是提供強健的零日保護，並提供一些功能，以即時保護您的組織不受有害連結。
ms.openlocfilehash: c736ac7c107c91c720737c569a3e41fe5bb0c98f
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173008"
---
# <a name="microsoft-defender-for-office-365-service-description"></a><span data-ttu-id="f2641-103">適用於 Office 365 的 Microsoft Defender 服務描述</span><span class="sxs-lookup"><span data-stu-id="f2641-103">Microsoft Defender for Office 365 service description</span></span>

<span data-ttu-id="f2641-104">Microsoft Defender for Office 365 是一項雲端式電子郵件篩選服務，可協助您的組織抵禦未知的惡意程式碼和病毒，方法是提供強健的零日保護，並提供一些功能，以即時保護您的組織不受有害連結。</span><span class="sxs-lookup"><span data-stu-id="f2641-104">Microsoft Defender for Office 365 is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time.</span></span> <span data-ttu-id="f2641-105">Office 365 的 Defender 具備豐富的報告及 URL 追蹤功能，可讓系統管理員深入瞭解組織中發生的攻擊類型。</span><span class="sxs-lookup"><span data-stu-id="f2641-105">Defender for Office 365 has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>

<span data-ttu-id="f2641-106">以下是您可以使用 Office 365 的 Defender 進行郵件保護的主要方式：</span><span class="sxs-lookup"><span data-stu-id="f2641-106">The following are the primary ways you can use Defender for Office 365 for message protection:</span></span>

- <span data-ttu-id="f2641-107">在 Office 365 僅限篩選的案例中，Office 365 的 Defender 為您的內部部署 Exchange 伺服器環境或任何其他內部部署 SMTP 電子郵件解決方案，提供雲端式電子郵件保護。</span><span class="sxs-lookup"><span data-stu-id="f2641-107">In a Defender for Office 365 filtering-only scenario, Defender for Office 365 provides cloud-based email protection for your on-premises Exchange Server environment or any other on-premises SMTP email solution.</span></span>

- <span data-ttu-id="f2641-108">可以啟用 Office 365 的 Defender，以保護 Exchange Online 雲端託管信箱。</span><span class="sxs-lookup"><span data-stu-id="f2641-108">Defender for Office 365 can be enabled to protect Exchange Online cloud-hosted mailboxes.</span></span> <span data-ttu-id="f2641-109">若要深入瞭解 Exchange Online，請參閱 [Exchange online 服務說明](exchange-online-service-description/exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="f2641-109">To learn more about Exchange Online, see the [Exchange Online service description](exchange-online-service-description/exchange-online-service-description.md).</span></span>

- <span data-ttu-id="f2641-110">在混合式部署中，您可以設定 Office 365 的 Defender，以保護您的郵件環境，並在您混合使用 Exchange Online Protection 以進行輸入電子郵件篩選時，保護您的郵件環境和控制郵件路由。</span><span class="sxs-lookup"><span data-stu-id="f2641-110">In a hybrid deployment, Defender for Office 365 can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>

## <a name="microsoft-defender-for-office-365-availability"></a><span data-ttu-id="f2641-111">Microsoft Defender for Office 365 可用性</span><span class="sxs-lookup"><span data-stu-id="f2641-111">Microsoft Defender for Office 365 availability</span></span>

<span data-ttu-id="f2641-112">Microsoft Defender for Office 365 方案2隨附于 Office 365 E5、Office 365 A5、Microsoft 365 E5 安全性和 Microsoft 365 E5，如下所指定： [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) 。</span><span class="sxs-lookup"><span data-stu-id="f2641-112">Microsoft Defender for Office 365 Plan 2 is included in Office 365 E5, Office 365 A5, Microsoft 365 E5 Security, and Microsoft 365 E5 as specified here: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp).</span></span> <span data-ttu-id="f2641-113">Office 365 的 Defender （方案1）包含在 Microsoft 365 商務版 Premium 中。</span><span class="sxs-lookup"><span data-stu-id="f2641-113">Defender for Office 365 Plan 1 is included in Microsoft 365 Business Premium.</span></span>

<span data-ttu-id="f2641-114">您可以將 Office 365 的 Defender 新增至下列 Exchange 和 Microsoft 365 訂閱計畫：</span><span class="sxs-lookup"><span data-stu-id="f2641-114">You can add Defender for Office 365 to the following Exchange and Microsoft 365 subscription plans:</span></span>

- <span data-ttu-id="f2641-115">Exchange Online Plan 1</span><span class="sxs-lookup"><span data-stu-id="f2641-115">Exchange Online Plan 1</span></span>

- <span data-ttu-id="f2641-116">Exchange Online Plan 2</span><span class="sxs-lookup"><span data-stu-id="f2641-116">Exchange Online Plan 2</span></span>

- <span data-ttu-id="f2641-117">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="f2641-117">Exchange Online Kiosk</span></span>

- <span data-ttu-id="f2641-118">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="f2641-118">Exchange Online Protection</span></span>

- <span data-ttu-id="f2641-119">Microsoft 365 商務基本版</span><span class="sxs-lookup"><span data-stu-id="f2641-119">Microsoft 365 Business Basic</span></span>

- <span data-ttu-id="f2641-120">Microsoft 365 商務標準版</span><span class="sxs-lookup"><span data-stu-id="f2641-120">Microsoft 365 Business Standard</span></span>

- <span data-ttu-id="f2641-121">Office 365 企業版 E1</span><span class="sxs-lookup"><span data-stu-id="f2641-121">Office 365 Enterprise E1</span></span>

- <span data-ttu-id="f2641-122">Office 365 企業版 E3</span><span class="sxs-lookup"><span data-stu-id="f2641-122">Office 365 Enterprise E3</span></span>

- <span data-ttu-id="f2641-123">Office 365 企業版 F3</span><span class="sxs-lookup"><span data-stu-id="f2641-123">Office 365 Enterprise F3</span></span>

- <span data-ttu-id="f2641-124">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="f2641-124">Office 365 A1</span></span>

- <span data-ttu-id="f2641-125">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="f2641-125">Office 365 A3</span></span>

<span data-ttu-id="f2641-126">若要購買 Microsoft Defender for Office 365，請參閱 [Microsoft defender For office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。</span><span class="sxs-lookup"><span data-stu-id="f2641-126">To buy Microsoft Defender for Office 365, see [Microsoft Defender for Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).</span></span>

<span data-ttu-id="f2641-127">如需可讓使用者使用 Microsoft Defender for Office 365 之訂閱的詳細資訊，請參閱 [完整訂閱比較表](https://go.microsoft.com/fwlink/?linkid=2139145)。</span><span class="sxs-lookup"><span data-stu-id="f2641-127">For detailed plan information on subscriptions that enable users for Microsoft Defender for Office 365, see the [full subscription comparison table](https://go.microsoft.com/fwlink/?linkid=2139145).</span></span>

## <a name="whats-new-in-microsoft-defender-for-office-365"></a><span data-ttu-id="f2641-128">Microsoft Defender for Office 365 的新功能</span><span class="sxs-lookup"><span data-stu-id="f2641-128">What's new in Microsoft Defender for Office 365</span></span>

<span data-ttu-id="f2641-129">我們正在繼續將新功能新增至 Office 365 的 Defender。</span><span class="sxs-lookup"><span data-stu-id="f2641-129">We are continuing to add new features to Defender for Office 365.</span></span> <span data-ttu-id="f2641-130">若要深入瞭解即將 Defender for Office 365 (或 Microsoft 365 的新功能) ，請參閱下列資源：</span><span class="sxs-lookup"><span data-stu-id="f2641-130">To learn more about new features coming to Defender for Office 365 (or Microsoft 365 in general), see the following resources:</span></span>

- [<span data-ttu-id="f2641-131">Microsoft 365 藍圖</span><span class="sxs-lookup"><span data-stu-id="f2641-131">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [<span data-ttu-id="f2641-132">Microsoft Defender for Office 365 的新功能</span><span class="sxs-lookup"><span data-stu-id="f2641-132">What's new in Microsoft Defender for Office 365</span></span>](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a><span data-ttu-id="f2641-133">Microsoft Defender for Office 365 的需求</span><span class="sxs-lookup"><span data-stu-id="f2641-133">Requirements for Microsoft Defender for Office 365</span></span>

<span data-ttu-id="f2641-134">Office 365 的 Defender 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server。</span><span class="sxs-lookup"><span data-stu-id="f2641-134">Defender for Office 365 can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server.</span></span> <span data-ttu-id="f2641-135">如需適用于 Office 365 的作業系統、網頁瀏覽器及語言支援的相關資訊，請參閱 [Exchange Online Protection 中](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)的「支援的瀏覽器」和「支援的語言」一節。</span><span class="sxs-lookup"><span data-stu-id="f2641-135">For information about the operating systems, web browsers, and languages that are supported by Defender for Office 365, see the "Supported browsers" and "Supported languages" sections in [Exchange admin center in Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).</span></span>

## <a name="feature-availability-across-defender-for-office-365-plans"></a><span data-ttu-id="f2641-136">各版 Office 365 方案中可用的功能</span><span class="sxs-lookup"><span data-stu-id="f2641-136">Feature availability across Defender for Office 365 plans</span></span>

<span data-ttu-id="f2641-137">每項功能如下所列。</span><span class="sxs-lookup"><span data-stu-id="f2641-137">Each feature is listed below.</span></span> <span data-ttu-id="f2641-138">提到 Exchange Online 時，通常是指 Office 365 企業版服務系列。</span><span class="sxs-lookup"><span data-stu-id="f2641-138">When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span><br><br>

| <span data-ttu-id="f2641-139">功能</span><span class="sxs-lookup"><span data-stu-id="f2641-139">Feature</span></span> | <span data-ttu-id="f2641-140">適用於 Office 365 的 Defender 方案 1</span><span class="sxs-lookup"><span data-stu-id="f2641-140">Defender for Office 365 Plan 1</span></span> | <span data-ttu-id="f2641-141">適用於 Office 365 的 Defender 方案 2</span><span class="sxs-lookup"><span data-stu-id="f2641-141">Defender for Office 365 Plan 2</span></span> | <span data-ttu-id="f2641-142">Microsoft 365 E5/A5 安全性</span><span class="sxs-lookup"><span data-stu-id="f2641-142">Microsoft 365 E5 / A5 Security</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="f2641-143">*設定、保護及偵測*</span><span class="sxs-lookup"><span data-stu-id="f2641-143">*Configuration, protection, and detection*</span></span>|
|[<span data-ttu-id="f2641-144">安全附件</span><span class="sxs-lookup"><span data-stu-id="f2641-144">Safe Attachments</span></span>](#safe-attachments)|<span data-ttu-id="f2641-145">是</span><span class="sxs-lookup"><span data-stu-id="f2641-145">Yes</span></span>|<span data-ttu-id="f2641-146">是</span><span class="sxs-lookup"><span data-stu-id="f2641-146">Yes</span></span>|<span data-ttu-id="f2641-147">是</span><span class="sxs-lookup"><span data-stu-id="f2641-147">Yes</span></span>|
|<span data-ttu-id="f2641-148">小組中的安全附件</span><span class="sxs-lookup"><span data-stu-id="f2641-148">Safe Attachments in Teams</span></span>|<span data-ttu-id="f2641-149">是</span><span class="sxs-lookup"><span data-stu-id="f2641-149">Yes</span></span>|<span data-ttu-id="f2641-150">是</span><span class="sxs-lookup"><span data-stu-id="f2641-150">Yes</span></span>|<span data-ttu-id="f2641-151">是</span><span class="sxs-lookup"><span data-stu-id="f2641-151">Yes</span></span>|
|[<span data-ttu-id="f2641-152">安全連結</span><span class="sxs-lookup"><span data-stu-id="f2641-152">Safe Links</span></span>](#safe-links)|<span data-ttu-id="f2641-153">是</span><span class="sxs-lookup"><span data-stu-id="f2641-153">Yes</span></span>|<span data-ttu-id="f2641-154">是</span><span class="sxs-lookup"><span data-stu-id="f2641-154">Yes</span></span>|<span data-ttu-id="f2641-155">是</span><span class="sxs-lookup"><span data-stu-id="f2641-155">Yes</span></span>|
|[<span data-ttu-id="f2641-156">安全文件</span><span class="sxs-lookup"><span data-stu-id="f2641-156">Safe Documents</span></span>](#safe-documents)|<span data-ttu-id="f2641-157">否</span><span class="sxs-lookup"><span data-stu-id="f2641-157">No</span></span>|<span data-ttu-id="f2641-158">否</span><span class="sxs-lookup"><span data-stu-id="f2641-158">No</span></span>|<span data-ttu-id="f2641-159">是</span><span class="sxs-lookup"><span data-stu-id="f2641-159">Yes</span></span>|
|<span data-ttu-id="f2641-160">Teams 中的安全連結</span><span class="sxs-lookup"><span data-stu-id="f2641-160">Safe Links in Teams</span></span>|<span data-ttu-id="f2641-161">是</span><span class="sxs-lookup"><span data-stu-id="f2641-161">Yes</span></span>|<span data-ttu-id="f2641-162">是</span><span class="sxs-lookup"><span data-stu-id="f2641-162">Yes</span></span>|<span data-ttu-id="f2641-163">是</span><span class="sxs-lookup"><span data-stu-id="f2641-163">Yes</span></span>|
|[<span data-ttu-id="f2641-164">適用於 SharePoint、OneDrive 及 Microsoft Teams 的 ATP</span><span class="sxs-lookup"><span data-stu-id="f2641-164">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>](#atp-for-sharepoint-onedrive-and-microsoft-teams)|<span data-ttu-id="f2641-165">是</span><span class="sxs-lookup"><span data-stu-id="f2641-165">Yes</span></span>|<span data-ttu-id="f2641-166">是</span><span class="sxs-lookup"><span data-stu-id="f2641-166">Yes</span></span>|<span data-ttu-id="f2641-167">是</span><span class="sxs-lookup"><span data-stu-id="f2641-167">Yes</span></span>|
|[<span data-ttu-id="f2641-168">防網路釣魚原則</span><span class="sxs-lookup"><span data-stu-id="f2641-168">Anti-phishing policies</span></span>](#anti-phishing-policies)|<span data-ttu-id="f2641-169">是</span><span class="sxs-lookup"><span data-stu-id="f2641-169">Yes</span></span>|<span data-ttu-id="f2641-170">是</span><span class="sxs-lookup"><span data-stu-id="f2641-170">Yes</span></span>|<span data-ttu-id="f2641-171">是</span><span class="sxs-lookup"><span data-stu-id="f2641-171">Yes</span></span>|
|[<span data-ttu-id="f2641-172">即時報告</span><span class="sxs-lookup"><span data-stu-id="f2641-172">Real-time reports</span></span>](#real-time-reports)|<span data-ttu-id="f2641-173">是</span><span class="sxs-lookup"><span data-stu-id="f2641-173">Yes</span></span>|<span data-ttu-id="f2641-174">是</span><span class="sxs-lookup"><span data-stu-id="f2641-174">Yes</span></span>|<span data-ttu-id="f2641-175">是</span><span class="sxs-lookup"><span data-stu-id="f2641-175">Yes</span></span>|
|<span data-ttu-id="f2641-176">*自動化、調查、修正及教育*</span><span class="sxs-lookup"><span data-stu-id="f2641-176">*Automation, investigation, remediation, and education*</span></span>|
|[<span data-ttu-id="f2641-177">威脅追蹤工具</span><span class="sxs-lookup"><span data-stu-id="f2641-177">Threat Trackers</span></span>](#threat-trackers)|<span data-ttu-id="f2641-178">否</span><span class="sxs-lookup"><span data-stu-id="f2641-178">No</span></span>|<span data-ttu-id="f2641-179">是</span><span class="sxs-lookup"><span data-stu-id="f2641-179">Yes</span></span>|<span data-ttu-id="f2641-180">是</span><span class="sxs-lookup"><span data-stu-id="f2641-180">Yes</span></span>|
|<span data-ttu-id="f2641-181">威脅調查 (高級威脅調查) </span><span class="sxs-lookup"><span data-stu-id="f2641-181">Threat investigation  (advanced threat investigation)</span></span>|[<span data-ttu-id="f2641-182">即時偵測</span><span class="sxs-lookup"><span data-stu-id="f2641-182">Real-time detections</span></span>](#real-time-detections)|[<span data-ttu-id="f2641-183">總管</span><span class="sxs-lookup"><span data-stu-id="f2641-183">Explorer</span></span>](#explorer)|[<span data-ttu-id="f2641-184">總管</span><span class="sxs-lookup"><span data-stu-id="f2641-184">Explorer</span></span>](#explorer)|
|[<span data-ttu-id="f2641-185">自動化的事件回應</span><span class="sxs-lookup"><span data-stu-id="f2641-185">Automated incident response</span></span>](#automated-incident-response)|<span data-ttu-id="f2641-186">否</span><span class="sxs-lookup"><span data-stu-id="f2641-186">No</span></span>|<span data-ttu-id="f2641-187">是</span><span class="sxs-lookup"><span data-stu-id="f2641-187">Yes</span></span>|<span data-ttu-id="f2641-188">是</span><span class="sxs-lookup"><span data-stu-id="f2641-188">Yes</span></span>|
|[<span data-ttu-id="f2641-189">攻擊模擬器</span><span class="sxs-lookup"><span data-stu-id="f2641-189">Attack Simulator</span></span>](#attack-simulator)|<span data-ttu-id="f2641-190">否</span><span class="sxs-lookup"><span data-stu-id="f2641-190">No</span></span>|<span data-ttu-id="f2641-191">是</span><span class="sxs-lookup"><span data-stu-id="f2641-191">Yes</span></span>|<span data-ttu-id="f2641-192">是</span><span class="sxs-lookup"><span data-stu-id="f2641-192">Yes</span></span>|
|<span data-ttu-id="f2641-193">*與 [Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)整合*</span><span class="sxs-lookup"><span data-stu-id="f2641-193">*Integration with [Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*</span></span>|<span data-ttu-id="f2641-194">否</span><span class="sxs-lookup"><span data-stu-id="f2641-194">No</span></span>|<span data-ttu-id="f2641-195">是</span><span class="sxs-lookup"><span data-stu-id="f2641-195">Yes</span></span>|<span data-ttu-id="f2641-196">是</span><span class="sxs-lookup"><span data-stu-id="f2641-196">Yes</span></span>|

> [!NOTE]
> <span data-ttu-id="f2641-197">如果您的租使用者只有 Microsoft Defender for Office Plan P2 試用版授權或 Office 365 E5 試用版授權，但沒有其他適用于 Microsoft 365 Defender 的合格授權，您將無法存取 Microsoft 365 Defender。</span><span class="sxs-lookup"><span data-stu-id="f2641-197">If your tenant only has Microsoft Defender for Office Plan P2 trial license or Office 365 E5 trial license, with no other eligible license for Microsoft 365 Defender, you will not be able to access Microsoft 365 Defender.</span></span> <span data-ttu-id="f2641-198">若要深入瞭解 MTP 授權，請參閱 [Microsoft 365 Defender 需求](/microsoft-365/security/mtp/prerequisites)。</span><span class="sxs-lookup"><span data-stu-id="f2641-198">To learn more about MTP license, see [Microsoft 365 Defender requirements](/microsoft-365/security/mtp/prerequisites).</span></span>

## <a name="defender-for-office-365-capabilities"></a><span data-ttu-id="f2641-199">Office 365 的 Defender 功能</span><span class="sxs-lookup"><span data-stu-id="f2641-199">Defender for Office 365 capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="f2641-200">安全附件</span><span class="sxs-lookup"><span data-stu-id="f2641-200">Safe Attachments</span></span>

<span data-ttu-id="f2641-201">[安全附件](/microsoft-365/security/office-365-security/atp-safe-attachments) 可防止未知的惡意程式碼和病毒，並提供零天的保護來保護郵件系統。</span><span class="sxs-lookup"><span data-stu-id="f2641-201">[Safe Attachments](/microsoft-365/security/office-365-security/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="f2641-202">所有沒有已知病毒/惡意程式碼簽章的郵件和附件都會路由至特殊的環境，其中 Office 365 的 Defender 會使用各種機器學習和分析技術來偵測惡意目的。</span><span class="sxs-lookup"><span data-stu-id="f2641-202">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where Defender for Office 365 uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="f2641-203">如果未偵測到可疑活動，即會釋出訊息傳遞到信箱。</span><span class="sxs-lookup"><span data-stu-id="f2641-203">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="f2641-204">安全附件掃描會在 Office 365 資料所在的相同區域中進行。</span><span class="sxs-lookup"><span data-stu-id="f2641-204">Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="f2641-205">如需資料中心地理位置的詳細資訊，請參閱[您的資料位於何處？](https://products.office.com/where-is-your-data-located?geo=All)</span><span class="sxs-lookup"><span data-stu-id="f2641-205">For more information about data center geography, see [Where is your data located?](https://products.office.com/where-is-your-data-located?geo=All)</span></span>

### <a name="safe-links"></a><span data-ttu-id="f2641-206">安全連結</span><span class="sxs-lookup"><span data-stu-id="f2641-206">Safe Links</span></span>

<span data-ttu-id="f2641-207">[安全連結](/microsoft-365/security/office-365-security/atp-safe-links)功能會在郵件中或 Office 檔中主動保護您的使用者免受惡意 URLs。</span><span class="sxs-lookup"><span data-stu-id="f2641-207">The [Safe Links](/microsoft-365/security/office-365-security/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="f2641-208">因為可動態封鎖惡意連結，允許存取無害連結，所以每次使用者選取連結時都能受到持續保護。</span><span class="sxs-lookup"><span data-stu-id="f2641-208">The protection remains every time they select the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="f2641-209">下列應用程式的 URL 可使用安全連結：</span><span class="sxs-lookup"><span data-stu-id="f2641-209">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="f2641-210">Microsoft 365 Windows 或 Mac 版企業版應用程式</span><span class="sxs-lookup"><span data-stu-id="f2641-210">Microsoft 365 Apps for enterprise on Windows or Mac</span></span>

- <span data-ttu-id="f2641-211">Office 網頁版 (Word 網頁版、Excel 網頁版、PowerPoint 網頁版和 OneNote 網頁版)</span><span class="sxs-lookup"><span data-stu-id="f2641-211">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web)</span></span>

- <span data-ttu-id="f2641-212">Windows 上的 Word、Excel 及 PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2641-212">Word, Excel, and PowerPoint on Windows</span></span>

- <span data-ttu-id="f2641-213">Microsoft Teams 頻道與聊天</span><span class="sxs-lookup"><span data-stu-id="f2641-213">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="f2641-214">使用者必須已取得 Office 365 版的授權 <sup>\*</sup> ，必須包含在安全連結原則中，而且必須登入裝置上，才可進行保護。</span><span class="sxs-lookup"><span data-stu-id="f2641-214">Users must be licensed for Defender for Office 365<sup>\*</sup>, must be included in Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="f2641-215"><sup>\*</sup> 若為全組織的 Office 365 授權 (例如，ATP_ENTERPRISE_FACULTY) ，您不需要將 Defender for Office 365 授權指派給個別使用者。</span><span class="sxs-lookup"><span data-stu-id="f2641-215"><sup>\*</sup> For organization-wide Defender for Office 365 licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign Defender for Office 365 licenses to individual users.</span></span>
>
> <span data-ttu-id="f2641-216">如需安全連結保護的詳細資訊，請參閱 [Microsoft Defender For Office 365 中的安全連結](/microsoft-365/security/office-365-security/atp-safe-links)。</span><span class="sxs-lookup"><span data-stu-id="f2641-216">For more information about Safe Links protection, see [Safe Links in Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/atp-safe-links).</span></span>

### <a name="safe-documents"></a><span data-ttu-id="f2641-217">安全文件</span><span class="sxs-lookup"><span data-stu-id="f2641-217">Safe Documents</span></span>

<span data-ttu-id="f2641-218">[ [安全檔](/microsoft-365/security/office-365-security/safe-docs) ] 功能使用 [Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 來掃描在 [受保護的檢視](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)中開啟的檔和檔案。</span><span class="sxs-lookup"><span data-stu-id="f2641-218">The [Safe Documents](/microsoft-365/security/office-365-security/safe-docs) feature uses [Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) to scan documents and files that are opened in [Protected View](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).</span></span>

<span data-ttu-id="f2641-219">開始之前有哪些須知？</span><span class="sxs-lookup"><span data-stu-id="f2641-219">What do you need to know before you begin?</span></span>

- <span data-ttu-id="f2641-220">12730 Office 版本2004的使用者通常可使用安全檔， () 或更高！</span><span class="sxs-lookup"><span data-stu-id="f2641-220">Safe Documents is now generally available to users with Office Version 2004 (12730.x) or greater!</span></span> <span data-ttu-id="f2641-221">此功能預設為關閉，必須由安全性管理員啟用。</span><span class="sxs-lookup"><span data-stu-id="f2641-221">This feature is off by default and will need to be enabled by the Security Administrator.</span></span>

- <span data-ttu-id="f2641-222">此功能僅適用于使用 Microsoft 365 E5 或 Microsoft 365 E5 安全性授權 (未包含在 Office 365 方案) 中的使用者。</span><span class="sxs-lookup"><span data-stu-id="f2641-222">This feature is only available to users with the Microsoft 365 E5 or Microsoft 365 E5 Security license (not included in Defender for Office 365 plans).</span></span>

- <span data-ttu-id="f2641-223">Windows 上的 Word、Excel 及 PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2641-223">Word, Excel, and PowerPoint on Windows</span></span>

- <span data-ttu-id="f2641-224">Microsoft Teams 頻道與聊天</span><span class="sxs-lookup"><span data-stu-id="f2641-224">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="f2641-225">使用者必須是 Microsoft 365 E5 或 Microsoft 365 E5 Security 的授權 <sup>\*</sup> ，必須包含在安全檔原則中，且必須登入裝置，以進行保護。</span><span class="sxs-lookup"><span data-stu-id="f2641-225">Users must be licensed for Microsoft 365 E5 or Microsoft 365 E5 Security<sup>\*</sup>, must be included in Safe Documents policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="f2641-226">如需安全檔案保護的詳細資訊，請參閱 [Microsoft 365 E5 中的安全檔](/microsoft-365/security/office-365-security/safe-docs)。</span><span class="sxs-lookup"><span data-stu-id="f2641-226">For more information about Safe Documents protection, see [Safe Documents in Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).</span></span>

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="f2641-227">適用於 SharePoint、OneDrive 及 Microsoft Teams 的 ATP</span><span class="sxs-lookup"><span data-stu-id="f2641-227">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="f2641-228">[SharePoint、OneDrive 和 Microsoft 團隊的 ATP](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  可協助偵測和封鎖在小組網站和文件庫中識別為惡意的檔案。</span><span class="sxs-lookup"><span data-stu-id="f2641-228">[ATP for SharePoint, OneDrive, and Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  helps detect and block files that are identified as malicious in team sites and document libraries.</span></span> <span data-ttu-id="f2641-229">此外，Microsoft 小組通道和聊天現在提供安全連結保護。</span><span class="sxs-lookup"><span data-stu-id="f2641-229">In addition, Safe Links protection is now available in Microsoft Teams channels and chats.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="f2641-230">防網路釣魚原則</span><span class="sxs-lookup"><span data-stu-id="f2641-230">Anti-phishing policies</span></span>

<span data-ttu-id="f2641-231">[反網路釣魚](/microsoft-365/security/office-365-security/atp-anti-phishing) 檢查內送郵件中是否有郵件可能是網路釣魚企圖。</span><span class="sxs-lookup"><span data-stu-id="f2641-231">[Anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="f2641-232">當使用者在 Office 365 原則中涵蓋時 (安全附件、安全連結或反網路釣魚) 時，會透過多部機器教學模型評估內送郵件，以分析郵件，並根據設定的原則採取適當的動作。</span><span class="sxs-lookup"><span data-stu-id="f2641-232">When users are covered by Defender for Office 365 policies (Safe Attachments, Safe Links, or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="f2641-233">即時報告</span><span class="sxs-lookup"><span data-stu-id="f2641-233">Real-time reports</span></span>

<span data-ttu-id="f2641-234">「安全性 & 合規性中心」 () 中提供的監控功能 [https://protection.office.com](https://protection.office.com) 包括 [即時報告和洞察力](/microsoft-365/security/office-365-security/view-reports-for-atp) ，可讓您的安全性和合規性問題著重于高優先順序問題，例如安全性攻擊或增加的可疑活動。</span><span class="sxs-lookup"><span data-stu-id="f2641-234">Monitoring capabilities available in the Security & Compliance Center ([https://protection.office.com](https://protection.office.com)) include [real-time reports and insights](/microsoft-365/security/office-365-security/view-reports-for-atp) that let your security and compliance administrators focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="f2641-235">除了醒目提示問題之外，智慧報告和洞察力也包含建議和連結，以查看及流覽資料，也會快速採取動作。</span><span class="sxs-lookup"><span data-stu-id="f2641-235">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="explorer"></a><span data-ttu-id="f2641-236">總管</span><span class="sxs-lookup"><span data-stu-id="f2641-236">Explorer</span></span>

<span data-ttu-id="f2641-237">總管 (也稱為威脅總管) 是即時的報告，可讓授權的使用者識別並分析最近的威脅。</span><span class="sxs-lookup"><span data-stu-id="f2641-237">Explorer (also referred to as Threat Explorer) is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="f2641-238">根據預設，此報告會顯示過去7天的資料;不過，您可以修改視圖，以顯示過去30天的資料。</span><span class="sxs-lookup"><span data-stu-id="f2641-238">By default, this report shows data for the past seven days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="f2641-239">Explorer 包含一些視圖，例如電子郵件和內容) 、提交、網路釣魚和所有電子郵件的惡意程式碼 (。</span><span class="sxs-lookup"><span data-stu-id="f2641-239">Explorer contains views, such as Malware (for email and content), Submissions, Phish, and All Email.</span></span> <span data-ttu-id="f2641-240">若要查看 Explorer 如何與即時偵測相比較，請 [下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="f2641-240">To see how Explorer compares with real-time detections, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="f2641-241">如需 microsoft defender for Office 365 Plan 2) 和即時偵測 (在 Microsoft Defender for Office 365 方案 1) 中的 Explorer (的詳細資訊，請參閱 [威脅瀏覽器和即時](/microsoft-365/security/office-365-security/threat-explorer)偵測。</span><span class="sxs-lookup"><span data-stu-id="f2641-241">For more information about Explorer (in Microsoft Defender for Office 365 Plan 2) and real-time detections (in Microsoft Defender for Office 365 Plan 1), see [Threat Explorer and real-time detections](/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="real-time-detections"></a><span data-ttu-id="f2641-242">即時偵測</span><span class="sxs-lookup"><span data-stu-id="f2641-242">Real-time detections</span></span>

<span data-ttu-id="f2641-243">即時偵測是即時的報告，可讓授權的使用者識別並分析最近的威脅。</span><span class="sxs-lookup"><span data-stu-id="f2641-243">Real-time detections is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="f2641-244">類似 Explorer，依預設，此報告會顯示過去7天的資料。</span><span class="sxs-lookup"><span data-stu-id="f2641-244">Similar to Explorer, by default, this report shows data for the past seven days.</span></span>

<span data-ttu-id="f2641-245">即時偵測包含諸如電子郵件和內容) 、報送和網路釣魚的惡意程式碼 (的視圖。</span><span class="sxs-lookup"><span data-stu-id="f2641-245">Real-time detections contain views, such as Malware (for email and content), Submissions, and Phish.</span></span> <span data-ttu-id="f2641-246">若要查看即時檢測與瀏覽器的比較方式，請 [下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="f2641-246">To see how real-time detections compare with Explorer, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="f2641-247">如需 microsoft defender for Office 365 Plan 2) 和即時偵測 (在 Microsoft Defender for Office 365 方案 1) 中的 Explorer (的詳細資訊，請參閱 [威脅 Explorer (和即時偵測) ](/microsoft-365/security/office-365-security/threat-explorer)。</span><span class="sxs-lookup"><span data-stu-id="f2641-247">For more information about Explorer (in Microsoft Defender for Office 365 Plan 2) and real-time detections (in Microsoft Defender for Office 365 Plan 1), see [Threat Explorer (and real-time detections)](/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="f2641-248">威脅追蹤工具</span><span class="sxs-lookup"><span data-stu-id="f2641-248">Threat Trackers</span></span>

<span data-ttu-id="f2641-249">[威脅](/microsoft-365/security/office-365-security/threat-trackers) 追蹤器是資訊性的小元件和視圖，可讓授權的使用者在可能影響組織的 cybersecurity 問題上使用情報。</span><span class="sxs-lookup"><span data-stu-id="f2641-249">[Threat Trackers](/microsoft-365/security/office-365-security/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="automated-incident-response"></a><span data-ttu-id="f2641-250">自動化的事件回應</span><span class="sxs-lookup"><span data-stu-id="f2641-250">Automated incident response</span></span>

<span data-ttu-id="f2641-251">[自動化的事件回應](/microsoft-365/security/office-365-security/office-365-air) (適用于 Office 365 的 AIR) 功能。方案2讓您執行自動調查程式，以回應目前存在的已知威脅。</span><span class="sxs-lookup"><span data-stu-id="f2641-251">[Automated incident response](/microsoft-365/security/office-365-security/office-365-air) (AIR) capabilities available in Defender for Office 365 Plan 2 let you run automated investigation processes in response to well-known threats that exist today.</span></span> <span data-ttu-id="f2641-252">透過自動化某些調查任務，您的安全性運作小組可以更有效率地運作。</span><span class="sxs-lookup"><span data-stu-id="f2641-252">By automated certain investigation tasks, your security operations team can operate more efficiently and effectively.</span></span> <span data-ttu-id="f2641-253">修正動作（如刪除惡意電子郵件訊息）是由您的安全性運作小組核准。</span><span class="sxs-lookup"><span data-stu-id="f2641-253">Remediation actions, such as deleting malicious email messages, are taken upon approval by your security operations team.</span></span> <span data-ttu-id="f2641-254">若要深入瞭解，請參閱 [Office 365 中的 AIR 運作方式](/microsoft-365/security/office-365-security/automated-investigation-response-office)。</span><span class="sxs-lookup"><span data-stu-id="f2641-254">To learn more, see [How AIR works in Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).</span></span>

### <a name="attack-simulator"></a><span data-ttu-id="f2641-255">攻擊模擬器</span><span class="sxs-lookup"><span data-stu-id="f2641-255">Attack Simulator</span></span>

<span data-ttu-id="f2641-256">[攻擊模擬器](/microsoft-365/security/office-365-security/attack-simulator) 可讓授權使用者在您的組織中執行現實的攻擊案例。</span><span class="sxs-lookup"><span data-stu-id="f2641-256">[Attack Simulator](/microsoft-365/security/office-365-security/attack-simulator) lets authorized users run realistic attack scenarios in your organization.</span></span> <span data-ttu-id="f2641-257">有幾種不同的攻擊可供使用，包括顯示名稱 spear 網路釣魚攻擊、密碼噴塗攻擊和強力密碼攻擊。</span><span class="sxs-lookup"><span data-stu-id="f2641-257">Several different kinds of attacks are available, including a display name spear-phishing attack, a password-spray attack, and a brute-force password attack.</span></span>