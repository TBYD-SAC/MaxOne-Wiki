# 🔒 TBYD License Classification Table

This table defines the classification of all publicly available TBYD systems for licensing purposes.

Each system is assigned to a license class (A, B, or C), which determines:

- the required structural protection fee
- the applicable rights under the full license ([LICENSE.md](./LICENSE.md))
- the constraints under preview-only access ([LICENSE-Addendum-A.md](./LICENSE-Addendum-A.md))
- the verifiability via public cryptographic hash ([HASHES.md](./HASHES.md))

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

| System Name | License Class | Current Version | Protection Fee | Hash Reference |
|-------------|---------------|-----------------|----------------|----------------|
| MaxOneOpen  | A             | 1.0             | €2,500         | [HASHES_MaxOneOpen-final.md](./HASHES_MaxOneOpen-final.md) |
| MaxOneCloud | A             | 1.0             | €2,500         | [HASHES_MaxOneCloud-final.md](./HASHES_MaxOneCloud-final.md) |
| MaxAudit    | B             | 1.0             | €1,500         | [HASHES_MaxAudit-final.md](./HASHES_MaxAudit-final.md) |
| MaxReg      | B             | 1.0             | €1,500         | [HASHES_MaxReg-final.md](./HASHES_MaxReg-final.md) |
| MaxTune-SD  | B             | 1.0             | €1,500         | [HASHES_MaxTune-final.md](./HASHES_MaxTune-final.md) |
| SDG         | B             | 1.0             | €1,500         | [HASHES_SDG-final.md](./HASHES_SDG-final.md) |

---

## Notes

- All systems listed above are available under the TBYD Structural License v2.2.
- For preview-only access, refer to the [LICENSE-Addendum-A.md](./LICENSE-Addendum-A.md).
- Hash references ensure integrity and authenticity of each system release.
