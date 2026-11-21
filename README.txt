KP AI CRYPTO TRADER — MOBILE WEB APP STARTER
================================================

This is a front-end prototype. It uses sample/demo values only.
It does NOT connect to an exchange, fetch live prices, or place orders.

FILES
- index.html: app UI and navigation
- manifest.webmanifest: installable PWA metadata
- sw.js: basic offline cache
- icon.svg, icon-192.png, icon-512.png: app icons

HOW TO TEST ON A PHONE
1. Extract this ZIP.
2. Open index.html in a browser if your file manager supports it.
   Some browsers restrict service workers for local files; that is normal.
3. For PWA installation, host the folder on an HTTPS static host (for example,
   GitHub Pages). Then open the HTTPS URL in Chrome and use "Add to Home screen"
   or "Install app" if offered.

ANDROID APK
After the app is hosted at a public HTTPS URL, a PWA packaging service such as
PWABuilder can be used to explore Android packaging. APK signing/build options
and current service requirements may change. Review the generated package before
installing or distributing it.

IMPORTANT SECURITY
- Do not put exchange API keys, secrets, passwords, or private keys in HTML/JS.
- Do not enable real orders in this prototype.
- A production trading app needs a secure backend, server-side secret storage,
  authentication, audit logs, exchange permission controls, and extensive testing.
- Crypto futures can cause rapid losses. This prototype is not trading advice.
