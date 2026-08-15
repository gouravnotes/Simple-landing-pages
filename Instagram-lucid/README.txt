Instagram PWA

Files:
- index.html
- manifest.webmanifest
- sw.js
- icons/

Install:
1. Serve this folder over HTTPS (localhost is also allowed for development).
2. Open index.html through that HTTPS site in Chrome on the phone.
3. Chrome should offer Install app / Add to Home screen.

Important:
A local file opened as file:///... cannot register a service worker.
