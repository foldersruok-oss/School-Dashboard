# Schulplaner 26/27 auf den iPhone-Home-Bildschirm

Dateien (alle im selben Ordner, Struktur beibehalten):
index.html, manifest.json, service-worker.js, icons/ (apple-touch-icon.png, icon-192.png, icon-512.png, icon-maskable-512.png, favicon-32.png)

1. Hosten: Den Ordner auf einen HTTPS-Webspace legen (GitHub Pages, Netlify Drop, Cloudflare Pages). Service Worker funktionieren nur über HTTPS, nicht über file://.
2. In Safari (nicht Chrome) die Adresse öffnen.
3. Teilen-Symbol, dann "Zum Home-Bildschirm", dann "Hinzufügen".
4. Über das neue Symbol starten. Die App läuft dann im Vollbild und offline.

Daten liegen nur im Browser-Speicher dieses Geräts/dieser Adresse. Regelmäßig unter Mehr > Backup erstellen.
Nach Änderungen an Dateien VERSION in service-worker.js erhöhen.
