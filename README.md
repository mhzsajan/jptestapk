# jptestapk — retired

**This repository is retired. Do not download anything from here.**

The Android app that lived in this repository was a 7 MB Flutter application that
had been configured to load:

```
https://mhzsajan.github.io/jpmb
```

That URL has never existed. Anyone who installed the app and tapped the icon got
a 404 page, so the app was non-functional from the day it was published.

This repository also contained **no source code**. Its entire contents were a
single 9-byte placeholder file, `apk/test.txt`, plus a compiled release asset.
When the app broke there was nothing to edit and nothing to rebuild from, which
is why it could not simply be fixed.

## Where things are now

| | |
|---|---|
| **The platform** | <https://mhzsajan.github.io/jptest/> |
| **The app (current)** | <https://github.com/mhzsajan/jptest/releases/tag/v2.0.0> |
| **App source** | <https://github.com/mhzsajan/jptest/tree/main/android> |
| **Build notes** | <https://github.com/mhzsajan/jptest/blob/main/docs/ANDROID_APP.md> |

The current app is **v2.0.0**: a 669 KB native WebView wrapper, roughly a tenth
of the size, with its source committed to the main repository and its URL pointing
at the platform's real address.

### If you already have the old app installed

Uninstall it before installing v2.0.0. The old build was signed with an Android
debug key that no longer exists, and Android will not accept an update signed
with a different key — even though the package name is the same.

**Settings → Apps → JFT Mock Test → Uninstall**

Then install v2.0.0 from the link above. From v2.0.0 onward, updates install
normally without an uninstall.

### About the release still attached below

The `jptestapk` release with the old `jptest.1.0.0.apk` asset is deliberately
left in place so that any link already shared keeps resolving to *something*
rather than a 404. **It is retained only as a historical artifact and does not
work.** Please do not install it.