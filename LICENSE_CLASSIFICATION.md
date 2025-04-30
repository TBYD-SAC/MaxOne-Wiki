# 🔒 TBYD License Classification Table

This table defines the classification of all publicly available TBYD systems for licensing purposes.

Each system is assigned to a license class (A, B, or C), which determines:

- the required structural protection fee
- the applicable rights under the full license ([LICENSE.md](./LICENSE.md))
- the constraints under preview-only access ([LICENSE-Addendum-A.md](./LICENSE-Addendum-A.md))
- the verifiability via public cryptographic hash

---

## License Classes Overview

| Class | Description                                         | Protection Fee (EUR) | Ethereum Transfer Required | Example Systems                     |
|-------|-----------------------------------------------------|----------------------|----------------------------|-------------------------------------|
| A     | Critical infrastructure systems (core platforms, OS) | €2,500               | Yes (per user key)         | MaxOneCloud, MaxOneOpen             |
| B     | Auditing, security, certification & validation systems | €1,500               | Yes (per user key)         | MaxAudit, MaxReg, MaxTune-SD, SDG   |
| C     | Lightweight tools, helpers, visualisations          | €750 (optional)      | Case-by-case               | MaxOps Preview Layer (planned)      |

> All payments must be executed via user-specific ETH address, requested through license@take-back-your-data.com.  
> For more details, refer to the [Full License Terms](./LICENSE.md).

---

## Active System Classifications

| System Name | License Class | Current Version | Protection Fee | SHA256 Hash |
|-------------|---------------|-----------------|----------------|-------------|
| MaxOneOpen  | A             | 1.0             | €2,500         | `8c0cb67b8ddff8961b1e89679d81d6f3086867d606a23b77c4bf69a3a44c5500` |
| MaxOneCloud | A             | 1.0             | €2,500         | `e46ac04242be4103bbe5ca1402e325d981c3a2d5ebda0abe3d3fe5eb0b83e258` |
| MaxAudit    | B             | 1.0             | €1,500         | `f5a0debafcbd301aff2e5ef65f76f9a482697ab8f281b950c0e634fabfed9fac` |
| MaxReg      | B             | 1.0             | €1,500         | `9a846a2ba34c1761c748d6293074581ef0c1648fb2d3ba17d671c3df75bd996a` |
| MaxTune-SD  | B             | 1.0             | €1,500         | `efa5979861216bfee36d2593cef65fca74df09a4a5a25d2cd691831be8c23598` |
| SDG         | B             | 1.0             | €1,500         | `df1b1febfd3faf109549daa57456686053fc1812630790a022e10e9b3efee8c9` |

---

## Notes

- All systems listed above are available under the TBYD Structural License v2.2.
- For preview-only access, refer to the [LICENSE-Addendum-A.md](./LICENSE-Addendum-A.md).
- Hash references ensure integrity and authenticity of each system release.
