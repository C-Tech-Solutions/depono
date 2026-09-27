# Depono v0.4.2

**In preparation — downloads are not yet available.**

Depono is the new name for Clio Companion. It brings case-document preparation, copy-only Bates preparation and queued Clio uploads together in a Windows application.

The first public release is planned to include:

- Installation for the current Windows user, with subsequent updates applied without administrator credentials where Windows policies permit.
- Signed automatic updates from this repository, applied after a safe normal exit, plus **Restart to update**.
- Update status and controls under **Help → Updates**, including an option to disable automatic updates.
- Manual activation with a signed license file, immediate feature availability after successful activation, and offline license verification.
- Preservation of the existing installation identity, perpetual license, Clio connection, settings and saved work across the rename and upgrade.

## Upgrading

Clio Companion v0.4.0 requires a manual installation of the first public Depono release. The private Depono v0.4.1 pilot can discover the public release through its existing update feed once a stable release is published. Older shared installations require a separate administrator-assisted migration/removal step.

The installation directory and internal executable names retain the former Clio Companion name for compatibility. The visible app, shortcuts and installed-app entry use Depono.

## Release files

The approved release will provide these four files:

- `DeponoSetup-v0.4.2-win-x64.exe`
- `DeponoSetup-v0.4.2-win-x64.exe.sha256.txt`
- `update-manifest.json`
- `update-manifest.cat`

The installer must show **C-Tech Solutions LLC** as its verified publisher. Checksums accompany the installer; the application additionally verifies signed metadata and installer trust. Do not disable Windows trust checks to install an unverified download.

Final availability, release details and approved customer terms will accompany the published release.
