# Changelog

## 1.8.5

This release includes the changes made in 1.8.1 through 1.8.4. Android 7.0 is now the minimum supported version.

- Minimum SDK is now API 24, with target SDK 36 and version code 26.
- The APK uses the same signing certificate as the previous official GitHub release.
- The requested permission set remains within the published 1.7.0 APK's set.

## 1.8.4

- Moved Back and Forward beside the eye control in the title bar.
- Added a search-engine picker to the address-bar site icon, using the same choices as Settings.
- Opened the selected engine's home page after a change and kept new tabs aligned with that choice. Custom home pages and incoming links are preserved.
- Fixed saved floating-cookie positions moving off-screen after rotation or resizing.
- Restored the native cookie icon after fullscreen video and picture-in-picture. Cookie controls work with page JavaScript disabled.
- Added a marked search-engine step to the tutorial.

## 1.8.3

- Reduced dialog heading, footer and form spacing while keeping rounded surfaces and accessible button targets.
- Replaced UA text with an eye icon and added cookie icons to the toolbar and floating control.
- Put Go beside the address field and moved common browsing actions ahead of advanced tools.
- Showed address-editing tools while the address is focused and swapped Reload for Stop while a page loads.
- Improved history opening and scrolling with recycled rows, background search and ordered background saves.
- Kept the newest 5,000 entries when restoring an oversized history record.
- Put cookie snapshot and clear-data actions on one row and adjusted the list height to its content.
- Improved floating-cookie tap, drag and cancellation handling.

## 1.8.2

- Added a tour that marks the actual controls, scrolls hidden tools into view and places its cards clear of the target in portrait and landscape.
- Added a first-use hint for holding the page title to edit text locally.
- Removed preset location coordinates. The override starts Off, validates both coordinates and can be blocked per site.
- Updated website location watches, permission queries and live changes. The override runs at document start where WebView supports it.
- Preserved tab previews and favicons during suspension and app restarts. Recently closed normal tabs also retain previews when session restoration is enabled.
- Honoured the session-restoration setting and kept private thumbnails out of persistent storage.
- Kept the current page attached if another tab could not be restored, with a reload fallback for damaged saved WebView state.
- Removed device camera, microphone, GPS, foreground-service, reboot and wake-lock permissions to stay within the published GitHub APK's requested permission set.
- Photo uploads use an installed camera app. Downloads use the visible app and ordinary Android jobs.

## 1.8.1

- Added tutorial navigation, completion and replay from About.
- Kept desktop mode active across redirects without an explicit site override, preserved custom user agents and added On/Off labels.
- Made reading mode confirm that an article view opened and restore the original page when closed.
- Connected page previews and favicons to the tab switcher and added the address-bar favicon.
- Improved cookie search, forms and save feedback while preserving available scope and attributes.
- Grouped settings and site permissions, added permission reset and improved account-profile validation.
- Applied a shared Material theme and rounded dialog surfaces.
- Kept offline pages inside system-bar insets and added a back toolbar.
- Updated the moved default domain blocklist URL without replacing custom sources.
- Corrected canvas noise sampling for solid-colour canvas exports.

For earlier releases, see [GitHub Releases](https://github.com/savaskarofficial/UltraBrowser/releases).
