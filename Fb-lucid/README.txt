# thefacebook PWA

This package contains the original page with only the PWA installation pieces added:
- Web App Manifest
- 192x192 and 512x512 app icons
- Service worker
- PWA/service-worker registration

## Install on Android with Chrome

1. Upload/host this folder on an HTTPS website.
2. Open the hosted `index.html` in Chrome on Android.
3. Use Chrome's menu and choose **Install app** or **Add to Home screen**.
4. Launch it from the Android home screen. It opens in standalone app mode.

Important: opening `index.html` directly from `file://` is not sufficient for normal PWA installation. Chrome requires a secure origin (HTTPS; localhost is also valid for development).
