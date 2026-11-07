# detox-launcher.com

Webseite für den [Detox Launcher](https://play.google.com/store/apps/details?id=com.kevinnovation.detoxlauncher).
Statisches HTML ohne Build-Schritt, ausgeliefert über GitHub Pages (Branch `main`, Domain über `CNAME`, DNS bei IONOS).

- `index.html`: Startseite inkl. interaktiver Handy-Vorschau (CSS/JS inline)
- `impressum.html`, `datenschutz.html`
- `en/`: englische Version (`en/index.html`, `en/privacy.html`), Screenshots in `img/en/`
- `img/`: Screenshots (WebP), `og.png` für Link-Vorschauen
- `fonts/`: Roboto und Roboto Flex, selbst gehostet (keine Google-Fonts-Anfragen)
- `app-ads.txt`: Altlast aus der AdMob-Zeit (seit App 0.9.10 keine Werbung mehr)
