LEDGER — INSTALLABLE PHONE APP

This package turns the original Ledger HTML into a standalone Progressive Web App.

WHAT CHANGED
- Replaced the original window.storage dependency with browser localStorage.
- Added an app manifest and phone icons.
- Added a service worker so the app can work offline after its first load.
- Kept the original Ledger UI, categories, tabs, notes, totals, filters and delete behavior.

IMPORTANT
A PWA can only be installed as a full offline app when served from HTTPS (or localhost).
Opening index.html directly as a file will let you use the ledger, but the browser may not offer full PWA installation.

ANDROID / CHROME
1. Put the LedgerApp folder on any HTTPS static host you control.
2. Open the resulting URL in Chrome on your phone.
3. Choose the browser menu -> Install app (or Add to Home screen).
4. Open Ledger from the new home-screen icon.
5. Your expenses are stored locally on that phone/browser.

IPHONE / SAFARI
1. Open the HTTPS URL in Safari.
2. Tap Share -> Add to Home Screen.
3. Open Ledger from the new icon.
4. Expenses are stored locally on the device/browser.

NO ACCOUNT IS REQUIRED. NO SERVER DATABASE IS USED.
