# IAM evidence

The three screenshots below were captured in the Azure Portal and are awaiting upload to this folder. Public versions should have personal and subscription identifiers removed.

| File | Verified observation |
|---|---|
| `IAM-001-Role-Assignment.png` | `id-iam-reader-lab`, Reader, scope: This resource |
| `IAM-002-Reader-Permissions.png` | Reader JSON: `actions: ["*/read"]` |
| `IAM-003-Contributor-Permissions.png` | Contributor JSON: `actions: ["*"]` and management exclusions |

### Publication precautions

- Redact Azure subscription IDs and any student email or tenant identifiers.
- Do not publish access tokens, credentials, or internal tenant information.
- Preserve authentic evidence; never recreate a portal screenshot to imply an event occurred.
- The screenshots verify **role assignment and definitions**, not runtime authorization enforcement.
