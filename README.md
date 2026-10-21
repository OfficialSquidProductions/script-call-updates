# Script Call downloads and signed updates

Script Call is **A Squid Productions Software**. This public repository contains reviewed application releases, update metadata, checksums and release notes.

- [Public MIT source and fictional demos](https://github.com/OfficialSquidProductions/script-call)
- Website entry point being coordinated: https://scriptcall.squidproductions.org/
- [Release downloads](https://github.com/OfficialSquidProductions/script-call-updates/releases)

Stable backend paths are `releases/latest/download/stable-darwin-arm64.json` for signed metadata and `releases/latest/download/Script-Call-Mac.zip` for the byte-identical notarized Mac download alias. Immutable update ZIPs use `releases/download/vVERSION/Script-Call-VERSION-darwin-arm64.zip`.

The first update-enabled Mac version requires one manual installation. Then use Script Call → Check for Updates. Signing keys and credentials remain on the publisher's Mac; client apps contain only a public verification key. Never upload production data, issued PDFs, keys, credentials, private samples or build caches here. The Last Light and legacy fictional demos remain included inside the app and source.

Windows distribution is not yet signed/tested. A source commit or tag alone does not ship an update. Check release notes for current validation and any remaining limitations.
