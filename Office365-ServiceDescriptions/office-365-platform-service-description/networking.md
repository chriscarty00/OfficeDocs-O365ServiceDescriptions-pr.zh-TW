---
title: 網路功能
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft 支援下列網路功能。
ms.openlocfilehash: df2fb9343529a7722fc434a79bf74621b78b787e
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652537"
---
# <a name="networking"></a><span data-ttu-id="d0dd7-103">網路功能</span><span class="sxs-lookup"><span data-stu-id="d0dd7-103">Networking</span></span>

<span data-ttu-id="d0dd7-104">Microsoft 支援下列網路功能。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-104">Microsoft supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="d0dd7-105">連接埠、通訊協定和 IP 位址</span><span class="sxs-lookup"><span data-stu-id="d0dd7-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="d0dd7-106">Microsoft 使用 IPv4 和 IPv6 位址。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-106">Microsoft uses IPv4 and IPv6 addresses.</span></span> <span data-ttu-id="d0dd7-107">IPv6 位址指定的使用是選用的，且不是連線 Office 365 的必要條件。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-107">Use of IPv6 addressing is optional and not required for connectivity with Office 365.</span></span> <span data-ttu-id="d0dd7-108">使用 IPv6 並不會完全啟用所有的 Microsoft 365 功能。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-108">Not all Microsoft 365 features are fully enabled using IPv6.</span></span> <span data-ttu-id="d0dd7-109">如需 Ipv6 支援的詳細資訊，請參閱[Microsoft 服務中的 IPv6 支援](/office365/enterprise/ipv6-support)。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-109">For more information about Ipv6 support, see [IPv6 support in Microsoft services](/office365/enterprise/ipv6-support).</span></span>
  
<span data-ttu-id="d0dd7-110">Microsoft 會在 Microsoft 協助中維護允許的 IP 位址清單。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-110">Microsoft maintains a list of allowed IP addresses in the Microsoft help.</span></span> <span data-ttu-id="d0dd7-111">如需詳細資訊，請參閱 [URLs 和 IP 位址範圍](/office365/enterprise/urls-and-ip-address-ranges)。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-111">For more information, see [URLs and IP address ranges](/office365/enterprise/urls-and-ip-address-ranges).</span></span> <span data-ttu-id="d0dd7-112">對於 21Vianet 運作的 Office 365，請參閱〈[21Vianet 運作的 Office 365 的 URL 及 IP 位址](/office365/enterprise/managing-office-365-endpoints)〉。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-112">For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](/office365/enterprise/managing-office-365-endpoints).</span></span> <span data-ttu-id="d0dd7-113">如需了解 Office 365 Germany，請參閱〈[Office 365 Germany 端點](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)〉。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-113">For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="d0dd7-p103">我們強烈建議您啟用上述文章中所列之根網域名稱的路由 (例如：\*.Outlook.com、\*.MicrosoftOnline.com 和 \*.SharePoint.com)，而非特定 IP 位址子網路的路由。仰賴 IP 位址子網路會讓您的使用者在進行變更時遇到中斷問題。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="d0dd7-116">頻寬需求</span><span class="sxs-lookup"><span data-stu-id="d0dd7-116">Bandwidth requirements</span></span>

<span data-ttu-id="d0dd7-117">如需頻寬需求的相關資訊，請參閱〈[網際網路頻寬規劃](/office365/enterprise/network-planning-and-performance)〉。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-117">For information on bandwidth requirements, see [Internet bandwidth planning](/office365/enterprise/network-planning-and-performance).</span></span>
  
## <a name="connecting-to-microsoft"></a><span data-ttu-id="d0dd7-118">連接至 Microsoft</span><span class="sxs-lookup"><span data-stu-id="d0dd7-118">Connecting to Microsoft</span></span>

<span data-ttu-id="d0dd7-119">所有對 Microsoft 的連線都是透過公用網際網路或私人 Azure ExpressRoute 連線進行，並視需要受到 SSL 保護。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-119">All Connections to Microsoft are done over the public internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate.</span></span> <span data-ttu-id="d0dd7-120">Azure ExpressRoute 允許直接連線至全域 Microsoft 網路，而不會略過網際網路。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-120">Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the internet.</span></span> <span data-ttu-id="d0dd7-121">Microsoft 網路合作夥伴提供全球 Microsoft 網路的連線。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-121">A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="d0dd7-122">如需 Azure ExpressRoute 的詳細資訊，請參閱 [Azure ExpressRoute Office 365](/microsoft-365/enterprise/azure-expressroute)。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](/microsoft-365/enterprise/azure-expressroute)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="d0dd7-123">WAN 加速器</span><span class="sxs-lookup"><span data-stu-id="d0dd7-123">WAN accelerators</span></span>

<span data-ttu-id="d0dd7-p105">Microsoft 不支援客戶自有的 WAN 加速器和 Office 365 的快取裝置。如果您決定採用 WAN 的最佳化控制器，以改善高延遲與低頻寬情況下的效能，則您必須在向 Microsoft 提出疑難排解服務要求時，停用此裝置並洽詢裝置廠商以取得裝置支援。如需相關資訊，請參閱〈[WAN 加速器和 Office 365 的快取裝置](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365)〉。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="d0dd7-127">Microsoft 全球網路</span><span class="sxs-lookup"><span data-stu-id="d0dd7-127">The global Microsoft network</span></span>

<span data-ttu-id="d0dd7-128">Microsoft 網路基礎結構由大量的資料中心、伺服器、內容發佈網路、edge 計算節點及光纖網路組成，以提供服務的全球發佈。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-128">The Microsoft networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services.</span></span> <span data-ttu-id="d0dd7-129">將精密的服務檢測和監控功能徹底整合至所有元件中，讓您輕鬆檢視資料中心、網路骨幹、網際網路交換等元件，以便找出、診斷和管理出現的中斷原因。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-129">Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise.</span></span> <span data-ttu-id="d0dd7-130">此網路可在大規模網路中斷情況時，在不影響效能的情況下提供充足的儲存容量。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-130">The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance.</span></span> <span data-ttu-id="d0dd7-131">如需詳細資訊，請參閱 [Microsoft 全球網路](/azure/networking/microsoft-global-network)。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-131">For more information, see [Microsoft Global Network](/azure/networking/microsoft-global-network).</span></span> 
  
<span data-ttu-id="d0dd7-132">為了維護客戶資料的機密性和完整性，Microsoft 保留獨立于 Microsoft 網路的消費者服務網路。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-132">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Microsoft networks.</span></span> <span data-ttu-id="d0dd7-133">Microsoft 技術用於控制資料流，包括但不限於：</span><span class="sxs-lookup"><span data-stu-id="d0dd7-133">Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="d0dd7-p108">實體分隔。網路區段是由路由 (設定為防止特定的通訊模式) 進行實體分隔。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="d0dd7-p109">邏輯分隔。虛擬 LAN (VLAN) 技術用於進一步分隔通訊。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="d0dd7-138">防火牆。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-138">Firewalls.</span></span> <span data-ttu-id="d0dd7-139">防火牆和其他網路安全性強制端點可用於限制對網際網路公開之系統的資料交換，以及與 Microsoft 所管理的後端系統隔離系統。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-139">Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="d0dd7-140">通訊協定限制。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="d0dd7-141">如需詳細資訊，請參閱〈[Office 365 信任中心](https://www.microsoft.com/trust-center)〉。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-141">For more information, see the [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="d0dd7-142">功能可用性</span><span class="sxs-lookup"><span data-stu-id="d0dd7-142">Feature availability</span></span>

<span data-ttu-id="d0dd7-143">若要查看不同方案中的功能可用性，請參閱[Microsoft 365 和 Office 365 platform service description](office-365-platform-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="d0dd7-143">To view feature availability across plans, see [Microsoft 365 and Office 365 platform service description](office-365-platform-service-description.md).</span></span>
