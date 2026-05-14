# QR Premium — källfiler för GitHub Pages

**Gemensam standard** för GitHub Pages-URL:er över flera appar: filen `docs/GITHUB_LEGAL_PAGES.md` i **QRScanner**-huvudrepot (lokal klon). Där finns formeln `https://<github-användare>.github.io/<app-slug>-legal/…` och tabell över appar.

Den här katalogen (`docs/qrscanner-legal/`) motsvarar GitHub-repot [`Dhafen/qrscanner-legal`](https://github.com/Dhafen/qrscanner-legal) (egen `.git` här — `git push` dit). Samma filstruktur som **fampro-legal**: `index.html`, `support.html`, `privacy.html` + Pages från `main` / root.

## Färdiga länkar (QR Premium)

| Sida | URL |
|------|-----|
| Startsida | https://dhafen.github.io/qrscanner-legal/ |
| Support (ASC) | https://dhafen.github.io/qrscanner-legal/support.html |
| Integritet (ASC) | https://dhafen.github.io/qrscanner-legal/privacy.html |

*(Uppdatera tabellen i `GITHUB_LEGAL_PAGES.md` om du byter användarnamn eller repo-namn.)*

## Uppdatera sidorna

```bash
cd /Users/elon/MacStudioAI/apps/qrscanner/docs/qrscanner-legal
git add -A && git commit -m "Uppdatera legal-sidor" && git push
```

GitHub Pages bygger om inom ca en minut.

## Kontakt-e-post

`support.html` och `privacy.html` — justera vid behov (t.ex. egen inkorg för QR jämfört med Fampro).

## Juridik

Malltexter, inte juridisk rådgivning. Justera mot faktisk datainsamling innan release.
