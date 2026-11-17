# ME/CFS Connect – Website

Statische Website für GitHub Pages.

## Veröffentlichung
1. Dateien aus diesem ZIP ins Root des öffentlichen Repositories `mecfs-connect-website` hochladen.
2. Unter **Settings → Pages**: **Deploy from a branch**, Branch `main`, Folder `/(root)` wählen.
3. Custom domain: `mecfs-connect.org` (CNAME-Datei ist enthalten).
4. Beim Domainanbieter die DNS-Einträge für GitHub Pages setzen und danach **Enforce HTTPS** aktivieren.

## Vor der öffentlichen Freigabe prüfen
- Rechtliche und technische Endprüfung der Datenschutzerklärung (der App-Quelltext bezeichnet sie ausdrücklich als Entwurf).
- Exakte Liste der Dienstleister (z. B. Supabase, RevenueCat, Apple/Google, SMTP), Drittlandtransfers und Aufbewahrungsfristen.
- Angaben im Impressum mit den aktuellen offiziellen Daten abgleichen.
- Abo-Bedingungen mit den tatsächlich angebotenen Store-Abonnements abgleichen.
- Community-Melde- und Prüfverfahren konkretisieren.

**Quelle:** `src/settings-menu.js` und Bilder aus dem bereitgestellten MECFS-Projekt. Keine geheimen Projektdateien enthalten.
