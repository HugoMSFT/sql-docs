---
author: MikeRayMSFT
ms.author: mikeray
ms.reviewer: randolphwest
ms.date: 10/16/2023
ms.topic: include
---

The following table identifies features available by SQL Server edition:

|Feature | Enterprise | Standard | Web | Express | Developer | Evaluation |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| [Azure pay-as-you-go billing](../manage-configuration.md) | Yes | Yes | Not applicable | Not applicable | Not applicable | Not applicable |
| [Best practices assessment](../assess.md) | Yes | Yes | Yes | Yes | Yes | Yes |
| [Detailed database inventory](../view-databases.md#inventory-databases) | Yes | Yes | Yes | Yes | Yes | Yes |
| [Microsoft Entra ID authentication](../../../relational-databases/security/authentication-access/azure-ad-authentication-sql-server-overview.md) | Yes | Yes | Yes | Yes | Yes | Yes |
| [Microsoft Defender for Cloud](/azure/defender-for-cloud/defender-for-sql-usage) | Yes | Yes | Yes | Yes <sup>1</sup>| Yes | Yes |
| [Microsoft Purview: Govern using DevOps and data owner policies](/azure/purview/tutorial-register-scan-on-premises-sql-server) | Yes | Yes | Yes | Yes | Yes | Yes |
| [Automated backups](../point-in-time-restore.md) | Yes | Yes | Yes | Yes | Yes | Yes |
| [Automated patching](../patch.md) | Yes | Yes | Yes | Yes | Yes | Yes |
| [Failover cluster instances (preview)](../support-for-fci.md)| Yes | Yes | Not applicable | Not applicable | Yes | Not applicable |

<sup>1</sup> [Express LocalDB isn't supported.](/azure/purview/register-scan-on-premises-sql-server#supported-capabilities)