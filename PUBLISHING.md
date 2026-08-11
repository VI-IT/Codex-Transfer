# Publishing a new Codex Transfer by VI-IT version

Codex Transfer by VI-IT checks the latest public release of:

`https://github.com/VI-IT/Codex-Transfer`

Version `1.0.0` is the first public GitHub release. For every later update:

1. Increase product, assembly and file version.
2. Build and run the complete self-test.
3. Create a semantic version tag such as `v1.1.0`.
4. Attach the portable binary with this exact filename: `Codex-Transfer-by-VI-IT.exe`.
5. Attach `SHA256.txt` and add bilingual release notes.
6. Publish the release and mark it as the latest release.

Portable copies check GitHub at startup. When the release tag is newer, the application displays a localized update notice and opens the matching official download when requested.

The public repository contains release documentation and binaries only. Do not upload the private application source, private screenshots, test archives, user profiles, projects, credentials or signing material.

