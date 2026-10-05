# Depono v0.4.5 — Windows maintenance public pilot

**Public pilot for coordinated installation and update testing. General customer rollout remains on hold.**

This is a maintenance update for Windows x64:

- License clock messages now refer to "System time" and "the date and time".
- Production Prep ZIP selection and partial-result confirmation run asynchronously, using the same dialogs.

Windows Help text and license entitlements are unchanged. The macOS app is not part of this public release.

## Test the update flow

In your existing Depono installation, choose **Help → Updates → Check now**. Once v0.4.5 is downloaded and verified, use **Restart to update** or close the app normally when no protected work is running. Minimizing to the tray does not install the update. If automatic updates are disabled, use the signed installer below for the manual path.

Existing settings, credentials, installation identity, activation and saved work are retained. Keep your current license in place during the update. Automatic checks continue every four hours while running, with a startup check unless a recent attempt was made. GitHub retry delays and your automatic-update setting are respected.

## Release files

- `DeponoSetup-v0.4.5-win-x64.exe`
- `DeponoSetup-v0.4.5-win-x64.exe.sha256.txt`
- `update-manifest.json`
- `update-manifest.cat`

Verify the installer publisher is **C-Tech Solutions LLC**. This pilot uses the stable channel so existing Depono installations can discover it. It is publicly downloadable; the pilot label does not restrict access. This release publishes no new EULA or privacy terms and does not change existing customer license rights.

# Depono v0.4.4 — annual licensing public pilot

**Public pilot for coordinated installation, update and annual-license testing. General customer rollout remains on hold.**

This release adds annual license files with yearly renewal:

- Each annual license covers one calendar year. Each renewal requires a newly issued file; no three-year entitlement is granted upfront.
- Upgrade to v0.4.4 before importing an annual license. The annual period is fixed when the license is issued, and importing it later does not restart the year.
- Existing perpetual licenses remain valid and are preserved by the update. Annual imports cannot replace an existing perpetual entitlement.
- License status shows the annual expiration, with a warning during the final 30 days.
- At expiration, new production work stops while work already running can finish. Activation, help, updates, existing outputs and reports remain available. A valid renewal restores access without automatically restarting the queue.
- Verification works offline. Keep Windows date and time correct; if a clock-error message appears, correct the clock and contact the issuer for assistance. No subscription billing or online activation is added.

This release also includes automatic update checks every four hours while running, a startup check unless a recent attempt was made, and **Last checked** / **Next check** under **Help → Updates**. GitHub retry delays and your automatic-update setting are respected.

## Test the update flow

In your existing Depono installation, choose **Help → Updates → Check now**. Once v0.4.4 is downloaded and verified, use **Restart to update** or close the app normally when no protected work is running. Minimizing to the tray does not install the update. If automatic updates are disabled, use the signed installer below for the manual path.

Existing settings, credentials, installation identity, activation and saved work are retained. Keep your current license in place during the update. Annual activation or renewal is a separate step after the supporting version is installed.

## Release files

- `DeponoSetup-v0.4.4-win-x64.exe`
- `DeponoSetup-v0.4.4-win-x64.exe.sha256.txt`
- `update-manifest.json`
- `update-manifest.cat`

Verify the installer publisher is **C-Tech Solutions LLC**. This pilot uses the stable channel so existing Depono installations can discover it. It is publicly downloadable; the pilot label does not restrict access. This release publishes no new EULA or privacy terms and does not change existing customer license rights.

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
