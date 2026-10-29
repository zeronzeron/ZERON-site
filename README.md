# ZERON-site

The public front door of **ZERON — Zero Carbon Emissions Calculator**: one page (`index.html`) that shows the ZERON web app full-screen at
**https://zeronzeron.github.io/ZERON-site/**.

The program itself is in `zeronzeron/zeron` and runs as a Google Apps Script web app.

- **Turn the page on:** Settings ▸ Pages ▸ Build and deployment ▸ *Deploy from a branch* ▸ `main` / `(root)` ▸ Save.
- **Connect it to the web app:** in `index.html`, replace the line marked **APP URL** with the web app link (Apps Script ▸ Deploy ▸ Manage deployments ▸ Web app URL, ending in `/exec`). Until then the page says ZERON is not connected yet.
- Code updates through the ZERON updater keep the same link. Only a **new** deployment needs a new APP URL line.
