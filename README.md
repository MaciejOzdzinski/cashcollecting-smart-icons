# cashcollecting-smart-icons

Public copies of the Cash Collecting Smart Outlook add-in icons, served by GitHub Pages.

The manifests reference them in `IconUrl` (64 px) and `HighResolutionIconUrl` (128 px). The Outlook add-ins
dialog is a public Microsoft page and the browser's Local Network Access rule blocks it from loading images
from the internal add-in host, so these two icons must be on a public HTTPS address.

| Stage | 64 px | 128 px |
|---|---|---|
| QC | `qc/icon-64.png` | `qc/icon-128.png` |
| Production | `production/icon-64.png` | `production/icon-128.png` |

Menu (ribbon) icons stay on the add-in host. Source of truth: `addins/<stage>/dispute/public/assets/` in the
add-ins repository — update both places together.
