---
"@ariakit/utils": patch
---

Fixed global event listeners infinitely recursing when a library overwrites `window.frames`.
