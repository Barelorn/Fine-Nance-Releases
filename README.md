# Fine Nance releases

This public repository contains signed update packages for **Fine Nance — Your Money, Finally Making Cents.**

It intentionally contains no financial records, bank credentials, Plaid tokens, email credentials, MFA secrets, or personal documents.

Fine Nance checks `manifest.json`, downloads the named package, verifies its SHA-256 checksum, creates a local backup, and only then installs the update. User data, documents, MFA settings, and connected-account tokens remain local and are preserved during updates.

Current release: **1.1.1**

The application source is maintained separately in a private repository.
