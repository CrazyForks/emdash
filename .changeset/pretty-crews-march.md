---
"emdash": patch
---

Fixes WXR import not preserving original post dates or publish status. Imported content now uses `wp:post_date_gmt` for `created_at` and sets `published_at` for published posts, rather than defaulting to the import time.
