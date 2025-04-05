# 🗂️ TBYD License Classification Table

This table defines the classification of all publicly available TBYD systems for licensing purposes.

Each system is assigned to a license class (A, B, or C), which determines:
- the required structural protection fee
- the applicable rights under the full license (`LICENSE.md`)
- the constraints under preview-only access (`LICENSE-Addendum-A.md`)
- the verifiability via public cryptographic hash (`HASHES.md`)

---

## 🧾 License Classes Overview

| Class | Description                                              | Protection Fee (EUR) | Ethereum Transfer Required | Example Systems                |
|-------|----------------------------------------------------------|-----------------------|-----------------------------|--------------------------------|
| A     | Critical infrastructure systems (core platforms, OS)     | €2,500                | Yes (per user key)          | MaxOneCloud, MaxOneOpen        |
| B     | Auditing, security, certification & validation systems   | €1,500                | Yes (per user key)          | MaxAudit                       |
| C     | Lightweight tools, helpers, visualisations               | €750 (optional)       | Case-by-case                | MaxOps Preview Layer (planned) |

> All payments must be executed **via user-specific ETH address**, requested through [license@take-back-your-data.com](mailto:license@take-back-your-data.com).  
> For more details, refer to the [Full License Terms](./LICENSE.md#structural-activation-fee).

---

## 📄 Active System Classifications

| System Name       | License Class | Current Version | Protection Fee | Hash Reference | Documentation |
|-------------------|---------------|------------------|----------------|----------------|----------------|
| **MaxOneOpen**    | A             | `v1.0.0`         | €2,500         | `0x83b1...d7f9` | [Whitepaper](./whitepaper-maxoneopen.md) |
| **MaxOneCloud**   | A             | `v1.0.0`         | €2,500         | `0x5ae9...82e1` | [CTO Summary](./MaxOneOpen_Structural_CTOSummary.md) |
| **MaxAudit**      | B             | `v1.0.0`         | €1,500         | `0xe13c...4a72` | [Tech Strategy](./MaxOneAudit_Technological_Strategy.md) |

> All hashes are fully listed and verified in [`HASHES.md`](./HASHES.md)  
> Licensing is only valid if the declared version hash matches the distributed audit version.

---

## 🛠️ Governance & Extension Notes

- New systems will be classified and listed here with a versioned hash.
- The classification table is referenced from:
  - [`LICENSE.md`](./LICENSE.md) – Full operational license
  - [`LICENSE-Addendum-A.md`](./LICENSE-Addendum-A.md) – Preview-only license
- No system may be deployed without a matching entry in this table and confirmed activation hash.

---

_Last updated: 2025-04-05_  
_Take Back Your Data (TBYD) – Digital Souveränität durch Struktur, nicht durch Zustimmung._
