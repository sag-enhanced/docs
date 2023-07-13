---
order: 10
---

# SAGE Extension

SAGE needs a Browser Extension to properly function.

SAGE needs to:

- get and modify Steam session cookies
- send arbitrary requests to Steam (to bypass CORS)
- intercept the CAPTCHA

Which just isn't possible without an extension.

## Installing

+++ Firefox

1. Go to the [Releases][1] page
2. Download the `sage-firefox.xpi` file and install it
3. Done!

[!ref Video Guide](https://youtu.be/kINmrXz9pB4) TOOD: UPDATE VIDEO

+++ Chrome

1. Go to the [Releases][1] page
2. Download the `sage-chromium.zip` file
3. Extract it to a persistent location (eg your desktop)
4. Go to `chrome://extensions/` and click on `Enable developer mode`
5. Click on `Load unpacked` and select the directory from step 3
6. Done!

[!ref Video Guide](https://youtu.be/Iau50gDdhM8) TOOD: UPDATE VIDEO

+++ Other

Other browsers such as _Internet Explorer_, _Safari_, _Opera (GX)_, _Brave_ etc.
are **not supported**.

If they work, that's purely coincidental. We will not offer any help or support
for these browsers.

+++

[1]: https://github.com/sag-enhanced/browser-extension/releases

## Source Code

The extension is open-source. You can inspect the code. If you don't trust our
builds, you can also pack it yourself.

[!ref Extension Source](https://github.com/sag-enhanced/browser-extension)
