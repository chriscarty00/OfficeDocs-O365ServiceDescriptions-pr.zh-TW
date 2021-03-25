---
title: 高可用性和業務連續性
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online 提供組織的電子郵件基礎結構的廣泛保留和復原支援。 其中包括在資料中心複寫信箱，以及還原已刪除信箱和已刪除郵件的能力。
ms.openlocfilehash: e205f26bfa611e388cc22557db98eeb84505ef9c
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173678"
---
# <a name="high-availability-and-business-continuity"></a><span data-ttu-id="9574d-104">高可用性和業務連續性</span><span class="sxs-lookup"><span data-stu-id="9574d-104">High availability and business continuity</span></span>

<span data-ttu-id="9574d-105">Microsoft Exchange Online 提供組織的電子郵件基礎結構的廣泛保留和復原支援。</span><span class="sxs-lookup"><span data-stu-id="9574d-105">Microsoft Exchange Online offers extensive retention and recovery support for an organization's email infrastructure.</span></span> <span data-ttu-id="9574d-106">其中包括在資料中心複寫信箱，以及還原已刪除信箱和已刪除郵件的能力。</span><span class="sxs-lookup"><span data-stu-id="9574d-106">This includes mailbox replication at data centers and the ability to restore deleted mailboxes and deleted items.</span></span>
  
## <a name="mailbox-replication-at-data-centers"></a><span data-ttu-id="9574d-107">在資料中心複寫信箱</span><span class="sxs-lookup"><span data-stu-id="9574d-107">Mailbox replication at data centers</span></span>

<span data-ttu-id="9574d-p103">Exchange Online 信箱在各 Microsoft 資料中心內持續複寫至多重資料庫複本，藉此在本機訊息基礎結構故障時提供資料還原功能。若是大規模的失敗，則會啟動服務連續性管理程序。</span><span class="sxs-lookup"><span data-stu-id="9574d-p103">Exchange Online mailboxes are continuously replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a local messaging infrastructure failure. For large-scale failures, service continuity management procedures are initiated.</span></span>
  
<span data-ttu-id="9574d-p104">如需有關 Microsoft 如何保護資料的詳細資訊，請參閱 [Office 365 信任中心r](https://go.microsoft.com/fwlink/p/?LinkId=299135)。如果您使用 21Vianet 運作的 Office 365，請參閱 [21Vianet 信任中心](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl)。</span><span class="sxs-lookup"><span data-stu-id="9574d-p104">For more information about how Microsoft protects your data, see [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). If you are using Office 365 operated by 21Vianet, see the [21Vianet Trust Center](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).</span></span>
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="9574d-112">復原已刪除的信箱</span><span class="sxs-lookup"><span data-stu-id="9574d-112">Deleted mailbox recovery</span></span>

<span data-ttu-id="9574d-113">管理員可以使用 Microsoft 365 系統管理中心刪除 Exchange Online 信箱，以刪除對應的使用者帳戶或移除 Exchange Online 授權，或是使用遠端 Windows PowerShell 中的 **Remove-Mailbox** Cmdlet 來刪除。</span><span class="sxs-lookup"><span data-stu-id="9574d-113">Administrators can delete Exchange Online mailboxes by using the Microsoft 365 admin center to delete the corresponding user account or remove the Exchange Online license, or by using the **Remove-Mailbox** cmdlet in remote Windows PowerShell.</span></span> <span data-ttu-id="9574d-114">信箱刪除之後，Exchange Online 預設會保留該信箱及其內容 30 天。</span><span class="sxs-lookup"><span data-stu-id="9574d-114">When a mailbox is deleted, Exchange Online retains the mailbox and its contents for 30 days by default.</span></span> <span data-ttu-id="9574d-115">30 天後，信箱將無法復原。</span><span class="sxs-lookup"><span data-stu-id="9574d-115">After 30 days, the mailbox is not recoverable.</span></span> <span data-ttu-id="9574d-116">復原的信箱包含所有儲存在信箱內遭到刪除的資料。</span><span class="sxs-lookup"><span data-stu-id="9574d-116">A recovered mailbox contains all of the data stored in it at the time it was deleted.</span></span> <span data-ttu-id="9574d-117">系統管理員可以使用 Microsoft 365 系統管理中心，在保留期間內復原已刪除的信箱。</span><span class="sxs-lookup"><span data-stu-id="9574d-117">Administrators can recover a deleted mailbox within the retention period by using the Microsoft 365 admin center.</span></span> <span data-ttu-id="9574d-118">若要復原已刪除的信箱，系統管理員必須還原對應的使用者帳戶，或將 Exchange Online 授權重新指派給使用者帳戶。</span><span class="sxs-lookup"><span data-stu-id="9574d-118">To recover a deleted mailbox, administrators have to restore the corresponding user account or reassign an Exchange Online license to the user account.</span></span> <span data-ttu-id="9574d-119">如需詳細資訊，請參閱 [刪除或還原 Exchange Online 中的使用者信箱](/exchange/recipients-in-exchange-online/delete-or-restore-mailboxes).</span><span class="sxs-lookup"><span data-stu-id="9574d-119">For more information, see [Delete or Restore User Mailboxes in Exchange Online](/exchange/recipients-in-exchange-online/delete-or-restore-mailboxes).</span></span>
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="9574d-120">復原已刪除的項目</span><span class="sxs-lookup"><span data-stu-id="9574d-120">Deleted item recovery</span></span>

<span data-ttu-id="9574d-121">Exchange Online 可讓使用者還原已從任何電子郵件資料夾中刪除的專案，包括「刪除的郵件」資料夾。</span><span class="sxs-lookup"><span data-stu-id="9574d-121">Exchange Online lets users restore items they have deleted from any email folder, including the Deleted Items folder.</span></span> <span data-ttu-id="9574d-122">郵件被刪除後，會保留在使用者的 [刪除的郵件] 資料夾中。</span><span class="sxs-lookup"><span data-stu-id="9574d-122">When an item is deleted, it's kept in a user's Deleted Items folder.</span></span> <span data-ttu-id="9574d-123">在使用者將它手動移除或保留原則將它自動移除之前，它會一直保留在該處。</span><span class="sxs-lookup"><span data-stu-id="9574d-123">It remains there until it's either manually removed by the user or automatically removed by retention policies.</span></span> <span data-ttu-id="9574d-124">系統管理員可以在 EAC 中或使用遠端 Windows PowerShell 自訂保留原則。</span><span class="sxs-lookup"><span data-stu-id="9574d-124">Administrators can customize retention policies in the EAC or by using remote Windows PowerShell.</span></span>
  
<span data-ttu-id="9574d-125">郵件從 [刪除的郵件] 資料夾中被移除後，會在 [可復原的項目] 資料夾中額外保留 14 天，然後才會永久移除，但是系統管理員可使用遠端 Windows PowerShell 將此天數增加，最多可達 30 天。</span><span class="sxs-lookup"><span data-stu-id="9574d-125">After an item has been removed from the Deleted Items folder, it's kept in a Recoverable Items folder for an additional 14 days before being permanently removed, but administrators can increase this to a maximum of 30 days by using remote Windows PowerShell.</span></span> <span data-ttu-id="9574d-126">在此期間內，使用者可以使用 Outlook 網頁版或 Outlook 中的 [復原刪除的郵件] 功能來復原專案。</span><span class="sxs-lookup"><span data-stu-id="9574d-126">Users can recover the item during this time period by using the Recover Deleted Items feature in Outlook on the web or Outlook.</span></span> <span data-ttu-id="9574d-127">了解如何[變更已刪除郵件的保留期間](/exchange/recipients-in-exchange-online/manage-user-mailboxes/change-deleted-item-retention)。</span><span class="sxs-lookup"><span data-stu-id="9574d-127">Learn how to [change the deleted item retention period](/exchange/recipients-in-exchange-online/manage-user-mailboxes/change-deleted-item-retention).</span></span>
  
<span data-ttu-id="9574d-p108">如果使用者已從 [可復原的項目] 資料夾中手動清除郵件，則系統管理員可以透過遠端 Windows PowerShell 使用「單一項目復原」功能，在一樣的保留期間內復原郵件。建立信箱時，預設會啟用「單一項目復原」。若要深入了解，請參閱[啟用或停用信箱的單一項目復原](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-single-item-recovery)。</span><span class="sxs-lookup"><span data-stu-id="9574d-p108">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same time period by using the Single Item Recovery feature with remote Windows PowerShell. By default, Single Item Recovery is enabled when a mailbox is created. To learn more, see [Enable or disable single item recovery for a mailbox](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-single-item-recovery).</span></span>
  
<span data-ttu-id="9574d-p109">若要將郵件保留在 [可復原的項目] 資料夾 30 天以上，組織可以實作更長期的電子郵件保留或以時間為基礎的就地保留功能。深入了解如何[將信箱設為就地保留](/exchange/security-and-compliance/in-place-and-litigation-holds)。</span><span class="sxs-lookup"><span data-stu-id="9574d-p109">To preserve messages for longer than 30 days in the Recoverable Items folder, organizations can implement longer-term email preservation or time-based In-Place Holds. Learn more about [placing a mailbox on In-Place Hold](/exchange/security-and-compliance/in-place-and-litigation-holds).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="9574d-133">功能可用性</span><span class="sxs-lookup"><span data-stu-id="9574d-133">Feature availability</span></span>

<span data-ttu-id="9574d-134">若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="9574d-134">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
