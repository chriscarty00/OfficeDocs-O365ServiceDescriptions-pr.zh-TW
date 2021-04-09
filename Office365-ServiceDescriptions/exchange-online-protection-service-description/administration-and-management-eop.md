---
title: Exchange Online Protection 中的管理與管理
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- administration-and-management-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9448f39-5e8a-48a4-80bc-b12b6fb72544
description: 本文說明 Microsoft Exchange Online Protection (EOP) 系統管理員可用的管理介面。
ms.openlocfilehash: f4b1aa1e9345740528763ff45a3fc99858fbd71a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653065"
---
# <a name="administration-and-management-in-exchange-online-protection"></a><span data-ttu-id="02c1f-103">Exchange Online Protection 中的管理與管理</span><span class="sxs-lookup"><span data-stu-id="02c1f-103">Administration and management in Exchange Online Protection</span></span>

<span data-ttu-id="02c1f-104">本文說明 Microsoft Exchange Online Protection (EOP) 系統管理員可用的管理介面。</span><span class="sxs-lookup"><span data-stu-id="02c1f-104">This article describes management interfaces that are available to Microsoft Exchange Online Protection (EOP) administrators.</span></span>
  
<span data-ttu-id="02c1f-105">尋找所有 EOP 功能的相關資訊嗎？</span><span class="sxs-lookup"><span data-stu-id="02c1f-105">Looking for information about all EOP features?</span></span> <span data-ttu-id="02c1f-106">請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="02c1f-106">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="access-to-the-microsoft-365-admin-center"></a><span data-ttu-id="02c1f-107">存取 Microsoft 365 系統管理中心</span><span class="sxs-lookup"><span data-stu-id="02c1f-107">Access to the Microsoft 365 admin center</span></span>

<span data-ttu-id="02c1f-108">Microsoft 365 系統管理中心是一個網頁入口網站，每個公司的服務管理員可以從該入口網站管理每個訂閱的 Microsoft 服務的使用者帳戶和設定。</span><span class="sxs-lookup"><span data-stu-id="02c1f-108">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Microsoft services to which they subscribe.</span></span> <span data-ttu-id="02c1f-109">在 Microsoft 365 系統管理中心內，管理員可以追蹤 EAC 的連結，以供他們管理 EOP 特有的設定。</span><span class="sxs-lookup"><span data-stu-id="02c1f-109">From within the Microsoft 365 admin center, administrators can follow links to the EAC, where they can manage settings specific to EOP.</span></span>
  
## <a name="access-to-the-exchange-admin-center"></a><span data-ttu-id="02c1f-110">存取 Exchange 系統管理中心</span><span class="sxs-lookup"><span data-stu-id="02c1f-110">Access to the Exchange admin center</span></span>

<span data-ttu-id="02c1f-111">Exchange 系統管理中心 (EAC) 是單一整合的管理主控台，不但易於使用，還可針對所有部署類型最佳化。</span><span class="sxs-lookup"><span data-stu-id="02c1f-111">The Exchange admin center (EAC) is a single unified management console that allows for ease of use and is optimized for all types of deployments.</span></span> <span data-ttu-id="02c1f-112">新的及改善的 EAC 會取代 Forefront Online Protection for Exchange 系統管理中心。</span><span class="sxs-lookup"><span data-stu-id="02c1f-112">The new and improved EAC replaces the Forefront Online Protection for Exchange Administration Center.</span></span> <span data-ttu-id="02c1f-113">EAC 可透過 Exchange 產品 (Microsoft Exchange Online 和 Microsoft Exchange Server 2013) ，提供與 Microsoft 365 更緊密的整合，以及跨 Exchange 產品的一致、流暢的 UI 體驗。</span><span class="sxs-lookup"><span data-stu-id="02c1f-113">EAC provides a tighter integration with Microsoft 365 and a consistent, seamless UI experience across Exchange products (Microsoft Exchange Online and Microsoft Exchange Server 2013).</span></span> <span data-ttu-id="02c1f-114">如需 EAC 的詳細資訊，請參閱＜[Exchange Online Protection 中的 Exchange 系統管理中心](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)＞。</span><span class="sxs-lookup"><span data-stu-id="02c1f-114">For more information about the EAC, see [Exchange Admin Center in Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).</span></span>
  
## <a name="remote-windows-powershell-access"></a><span data-ttu-id="02c1f-115">遠端 Windows PowerShell 存取</span><span class="sxs-lookup"><span data-stu-id="02c1f-115">Remote Windows PowerShell access</span></span>

 <span data-ttu-id="02c1f-p104">系統管理員可以使用遠端 Windows PowerShell，從命令列執行管理工作。如需如何使用 Windows PowerShell 的詳細資訊，包括建立命令介面工作階段的資訊和每個 Cmdlet 的相關文件，請參閱＜[Exchange Online PowerShell](/powershell/exchange/exchange-online-powershell)＞。</span><span class="sxs-lookup"><span data-stu-id="02c1f-p104">Administrators can use Remote Windows PowerShell to perform management tasks from the command line. For more information about how to use Windows PowerShell, including information about creating a remote Shell session and documentation about each cmdlet, see [Exchange Online PowerShell](/powershell/exchange/exchange-online-powershell).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="02c1f-118">功能可用性</span><span class="sxs-lookup"><span data-stu-id="02c1f-118">Feature availability</span></span>

<span data-ttu-id="02c1f-119">若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱 [Exchange Online Protection 服務說明](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="02c1f-119">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
