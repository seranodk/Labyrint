# Labyrint

Et labyrintspil til browser og mobil med klassisk jagt-gameplay: spis alle prikker, undgå de fire jægere, og spis dem, når du har taget en kraftpille.

**Version 0.2.2**

## Spil som app (fuld skærm)

Åbn spillet på GitHub Pages på mobilen og vælg **Føj til hjemmeskærm** (Safari: Del-knappen, Chrome: menuen ⋮). Så starter det i fuld skærm uden browserlinje, med eget ikon, og kan spilles offline. På Android går spillet også i fuld skærm, når du trykker Start, og der er en fuldskærmsknap øverst.

GitHub Pages slås til under Settings → Pages → branch `main`, mappe `/ (root)`.

## Spil

- **Browser:** piletaster eller WASD, P for pause
- **Mobil:** fire retningsknapper nederst på skærmen

## Indhold

- 5 temaer: Neon, Have, Hav, Rummet, Vinter
- 5 banestørrelser: Lille (19×21), Mellem (23×25), Klassisk (27×31), Stor (31×35), Kæmpe (35×41)
- Tilfældige, symmetriske baner uden blindgyder, valgfrit ny bane på hvert level
- Rekord gemmes lokalt i browseren pr. banestørrelse

## Filer

- `index.html` – spillet til GitHub Pages (med app-installation)
- `game.html` – samme spil i artifakt-udgaven til Claude
- `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` – det, der får spillet til at opføre sig som en app

## Versioner

Versionsnavne følger 0.x.x: en større ændring hæver det første x, en mindre ændring det andet.

- **0.2.2** – Retningsknapperne vises kun under spillet, ikke i menuen. Menuen passer på skærmen uden scroll, også på små telefoner.
- **0.2.1** – Joysticket er erstattet af fire firkantede retningsknapper, så retningen altid er entydig.
- **0.2.0** – Kan installeres som app: fuld skærm, ikon og offline-spil. Fuldskærmsknap, automatisk fuld skærm ved start på telefoner, og skærmen slukker ikke midt i et spil.
- **0.1.4** – Rettet: spilleren kunne sidde fast i kryds med fire veje. Navnet ændret til Labyrint.
- **0.1.3** – Joysticket læner sig mod tommelfingerens retning og undgår at køre fast mod mure.
- **0.1.2** – Swipe og klassisk styring fjernet; større drejevindue og rundt joystick.
- **0.1.1** – Blødere styring med forhåndsdrej; pauseknap flyttet til toppen.
- **0.1.0** – Første version.
