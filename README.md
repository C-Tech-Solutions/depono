# Depono

Depono helps legal teams prepare case documents and upload productions to Clio. It includes production preparation, copy-only Bates preparation, and a resumable upload queue.

Formerly **Clio Companion**, Depono is proprietary Windows software from C-Tech Solutions LLC. This repository hosts customer downloads and public release information; it does not contain the application's source code.

## Downloads

**Depono v0.4.2 is a public pilot for coordinated installation and update testing. General customer rollout is on hold.** See the [v0.4.2 release](https://github.com/C-Tech-Solutions/depono/releases/tag/v0.4.2) for downloads and [release information](RELEASE-NOTES.md) for scope.

Depono targets Windows x64 and installs for the current Windows user. Normal installation and updates do not require administrator credentials; organizational policies may restrict installation or downloads.

Existing Clio Companion v0.4.0 users will need to install the first public Depono release manually. The private Depono v0.4.1 pilot already uses this update repository. The upgrade retains existing settings, activation and saved work. Removing an older shared installation is a separate administrator-assisted step.

## Updates and verification

Releases contain a signed setup executable, its SHA-256 checksum, update metadata and a signed Windows catalog authenticating that metadata. Depono verifies the catalog and installer publisher before applying updates. Download installers only from this repository's Releases page and verify the publisher is **C-Tech Solutions LLC**.

The pilot uses the stable update channel so existing Depono v0.4.1 installations can discover it. It is publicly downloadable; the pilot label does not restrict access. Automatic checks normally run about once a day when the application is running. **Check now** starts an earlier check.

Automatic updates can be disabled in **Help → Updates**. Manual checks remain available. A staged update applies after a permitted normal exit, or through **Restart to update**; minimizing to the tray does not install it.

## License and third-party components

Depono is proprietary software. See [the proprietary notice](LICENSE.txt). Customer software use is governed by the terms supplied with the applicable release or purchase. Manual activation uses a signed license file for one Windows-user installation; the current license model is perpetual and does not require a recurring online license check. Clio operations require network access. Third-party components remain subject to their own licenses and notices included with the software.

Do not put client documents, matter details, credentials, license files or diagnostic records in public repository discussions or issues.

Depono is an independent product. References to Clio describe the integration and do not imply endorsement by Clio.
