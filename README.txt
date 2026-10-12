PATHOLOGY MCQ EXAM PREP
=======================

Files
- 2015-images.html: standalone quiz based on the four provided images (30 items).
- 2016.html: standalone quiz based on MSIS Pathology 2016 batch.pdf (22 items). Note: the PDF's internal title says “MSIS Pathology 2018”.
- 2017.html: standalone quiz based on Patho MSSI 2017 .pdf (41 items).
- index.html: launch page for all three sets.
- manifest.webmanifest + sw.js + icon.svg: Progressive Web App (PWA) install/offline support.

WEB DEPLOYMENT
1. Upload the entire contents of this folder to a static host that serves HTTPS (for example GitHub Pages, Netlify, or your own HTTPS web server).
2. Visit the hosted index.html URL. The service worker caches the quiz pages for subsequent offline use.
3. Do not test PWA installation by opening index.html as a file:// URL; service workers and installation generally require HTTPS or localhost.

ANDROID INSTALL
- Easiest installable app experience: deploy over HTTPS, open the site in Chrome on Android, open the browser menu, and choose “Install app” or “Add to Home screen”. Exact wording depends on browser/device.
- A distributable APK is not included. To publish a Play Store APK/AAB, wrap the deployed PWA with Android Trusted Web Activity tooling (Bubblewrap/PWABuilder), configure Digital Asset Links for a domain you control, and sign the release build. See Android's Trusted Web Activity documentation: https://developer.android.com/develop/ui/views/layout/webapps/guide-trusted-web-activities-version2

FEATURES
- Immediate answer reveal and explanations in practice mode.
- Exam mode hides explanations until finish.
- Flag/unflag, question navigator, filters, progress, timer, shuffle, restart, results summary, JSON export.
- Saves answers and flags locally in browser storage.

CONTENT QUALITY NOTE
Question text is transcribed from the supplied materials. Several source items have ambiguous/incomplete wording or questionable single-best-answer options; these are identified where possible. Distractor explanations are provided as per-option feedback, but generic distractor notes should not be treated as authoritative clinical teaching where the source question is ambiguous. Review those items against your course's official key.
