# Package Install Notes

## Warnings

- hexo > warehouse > cuid@2.1.8: Cuid and other k-sortable and non-cryptographic ids (Ulid, ObjectId, KSUID, all UUIDs) are all insecure. Use @paralleldrive/cuid2 instead.
- hexo-renderer-marked > jsdom > abab@2.0.6: Use your platform's native atob() and btoa() methods instead
- hexo-renderer-marked > jsdom > domexception@4.0.0: Use your platform's native DOMException instead
- hexo-renderer-marked > jsdom > data-urls > abab@2.0.6: Use your platform's native atob() and btoa() methods instead
- hexo-renderer-stylus > stylus > glob@7.2.3: Glob versions prior to v9 are no longer supported
- hexo-renderer-stylus > stylus > glob > inflight@1.0.6: This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
