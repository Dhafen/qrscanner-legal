# QR Premium — GitHub Pages (samma upplägg som `fampro-legal`)

Källfiler för **Dhafen/qrscanner-legal** på GitHub — samma upplägg som Fampro ([fampro-legal](https://github.com/Dhafen/fampro-legal)): statiska HTML-sidor + GitHub Pages från `main` / root.

## Live (GitHub Pages)

| Sida | URL |
|------|-----|
| Startsida | https://dhafen.github.io/qrscanner-legal/ |
| Support (ASC) | https://dhafen.github.io/qrscanner-legal/support.html |
| Integritet (ASC) | https://dhafen.github.io/qrscanner-legal/privacy.html |

Verifierat HTTP **200** efter första deploy.

## Uppdatera sidorna

Ändra HTML här, committa och pusha till `main`:

```bash
cd /Users/elon/MacStudioAI/apps/qrscanner/docs/qrscanner-legal
git add -A && git commit -m "Uppdatera legal-sidor" && git push
```

GitHub Pages bygger om inom ca 1 minut.

## Kontakt-e-post

`support.html` och `privacy.html` använder samma inkorg som Fampro (`fampro.app@outlook.com`). Byt i båda filerna om QR Premium ska ha en egen adress.

## Juridik

Detta är en **mall** för webbsidor, inte juridisk rådgivning. Justera integritetstexten så den stämmer exakt med faktisk datainsamling i appen innan release.
