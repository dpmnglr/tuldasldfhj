# Tulu Lipi downloads
Static site. Host on GitHub Pages: upload everything, then Settings > Pages > Deploy from branch (main, / root).
Files for users are in downloads/: Tulu-Keyboard.apk, Tulu-Lipi-Lens.apk, Tulu-Lipi-Mallige-Firefox.xpi, Tulu-Lipi-Mallige-Chrome.zip.
Icons in assets/img/: keyboard.png, lens.png, firefox.png, chrome.png (shown on the home cards and each page).
Step screenshots: put images in assets/img/ named keyboard-1.png, lens-1.png, firefox-1.png, chrome-1.png ... (step order).
Edit step text directly in each page's HTML.

## Redesign notes
- Mandara font: assets/fonts/mandara.ttf, registered in assets/css/style.css (font-display: swap). It is the Tulu-Tigalari display/script face; tulu.ttf is kept as a fallback.
- Pages are plain HTML + one stylesheet (assets/css/style.css) + a tiny menu script (assets/js/main.js). No external requests.
- Step screenshots: add assets/img/keyboard-1.png etc. and they appear automatically; missing ones are hidden.
