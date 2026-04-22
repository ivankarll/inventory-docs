# Overview

The Inventory System uses **Role-Based Access Control (RBAC)** with three built-in roles.

## Roles at a Glance

| Capability | Super Admin | Admin | Employee |
|---|:---:|:---:|:---:|
| View inventory | ✅ | ✅ | ✅ |
| Create requests | ✅ | ✅ | ✅ |
| Add / edit SKUs | ✅ | ✅ | ⛔ |
| Adjust stock | ✅ | ✅ | ⛔ |
| Manage users | ✅ | ⚠️ (Limited) | ⛔ |
| View reports | ✅ | ✅ | ⛔ |
| Configure system | ✅ | ⛔ | ⛔ |
| Restore backups | ✅ | ⛔ | ⛔ |

## Choosing the Right Role

<div class="grid cards" markdown>

-   :material-shield-crown: **Super Admin**

    Full system control. Reserved for IT leads and system owners. Handles configuration and data recovery.

    [→ Super Admin Role](super-admin.md)

-   :material-account-tie: **Admin**

    Operational management. Use for team leads who manage equipment and approve staff requests.

    [→ Admin Role](admin.md)

-   :material-account: **Employee**

    Standard access. Day-to-day users who need to view inventory and request equipment.

    [→ Employee Role](employee.md)

</div>
