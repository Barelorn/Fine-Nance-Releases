# Fine Nance releases

This public repository contains checksum-verified update packages for **Fine Nance — Your Money, Finally Making Cents.**

It intentionally contains no financial records, bank credentials, Plaid tokens, email credentials, MFA secrets, or personal documents.

The server edition checks `manifest.json`. The self-contained Windows edition checks `manifest-standalone.json`. Fine Nance verifies each package's SHA-256 checksum before installation. User data, documents, MFA settings, and connected-account tokens remain local and are preserved during updates.

Current Windows release: **1.3.2**

Current server release: **1.3.3**

The Windows installer is not yet code-signed, so Windows SmartScreen may show an **Unknown publisher** warning. Verify the checksum from the standalone manifest before running it.

The application source is maintained separately in a private repository.
