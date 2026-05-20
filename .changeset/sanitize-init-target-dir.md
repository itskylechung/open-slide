---
'@open-slide/cli': patch
---

Sanitize the target directory name during `init` so the printed `cd` command always works — names with spaces or other shell-unfriendly characters are now suggested as a safe equivalent (e.g. `future of open slide` → `future-of-open-slide`).
