# Depono v0.4.2

**Public pilot for coordinated installation and update testing. General customer rollout is on hold.**

Depono is the new name for Clio Companion. It brings case-document preparation, copy-only Bates preparation and queued Clio uploads together in a Windows application.

This pilot includes:

- Installation for the current Windows user, with subsequent updates applied without administrator credentials where Windows policies permit.
- Signed automatic updates from this repository, applied after a safe normal exit, plus **Restart to update**.
- Update status and controls under **Help → Updates**, including an option to disable automatic updates.
- Manual activation with a signed license file, immediate feature availability after successful activation, and offline license verification.
- Preservation of the existing installation identity, perpetual license, Clio connection, settings and saved work across the rename and upgrade.
- Startup window placement that keeps the title bar and menus inside the usable desktop at increased Windows scaling.

The v0.4.1 pilot already includes manual activation and offline licensing. This update retains those features and existing activation; it does not introduce subscriptions or online activation.

## Upgrading

Clio Companion v0.4.0 requires a manual Depono installation. The Depono v0.4.1 pilot discovers v0.4.2 through its existing update feed when its next check is due. **Help → Updates → Check now** checks sooner. Older shared installations require a separate administrator-assisted migration/removal step.

The installation directory and internal executable names retain the former Clio Companion name for compatibility. The visible app, shortcuts and installed-app entry use Depono.

## Release files

The release provides these four files:

- `DeponoSetup-v0.4.2-win-x64.exe`
- `DeponoSetup-v0.4.2-win-x64.exe.sha256.txt`
- `update-manifest.json`
- `update-manifest.cat`

The installer must show **C-Tech Solutions LLC** as its verified publisher. Checksums accompany the installer; the application additionally verifies signed metadata and installer trust. Do not disable Windows trust checks to install an unverified download.

The release is listed as stable to exercise the existing updater. It remains a pilot, with general rollout held until release acceptance is complete. The proprietary notice and existing customer license rights remain applicable. This pilot publishes no new EULA or privacy terms.
