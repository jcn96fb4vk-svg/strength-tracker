# Strength Tracker – iPhone PWA

## Inhoud
- `index.html`: de app
- `manifest.json`: installatiegegevens
- `sw.js`: offline cache
- `icon-192.png` en `icon-512.png`: app-iconen

## Publiceren
Een PWA moet via HTTPS worden aangeboden. De eenvoudigste gratis route:
1. Maak een GitHub-account op https://github.com als je dat nog niet hebt.
2. Maak een nieuwe repository, bijvoorbeeld `strength-tracker`.
3. Upload alle bestanden uit deze map naar de hoofdmap van de repository.
4. Ga naar **Settings → Pages**.
5. Kies **Deploy from a branch**, branch `main`, folder `/ (root)`, en klik Save.
6. Wacht tot GitHub Pages de site publiceert. Je krijgt een HTTPS-adres, bijvoorbeeld `https://gebruikersnaam.github.io/strength-tracker/`.

## Installeren op iPhone
1. Open het HTTPS-adres in Safari (niet in een in-app browser).
2. Tik op het deel-icoon.
3. Kies **Zet op beginscherm** / **Add to Home Screen**.
4. Geef de app eventueel de naam Strength en tik op **Voeg toe**.
5. Open de app vanaf het nieuwe beginschermicoon.

## Gegevens en privacy
- Sets worden meteen opgeslagen in de lokale opslag van Safari op dit toestel.
- Er is geen account, cloudsync of serverdatabase.
- Exporteer regelmatig een JSON-back-up via Records → Exporteer back-up.
- Wis websitegegevens van Safari niet als je de trainingshistorie wilt behouden.
- De app is een eerste persoonlijke MVP; data wordt niet automatisch gesynchroniseerd naar andere apparaten.
