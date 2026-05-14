# QR Premium — GitHub Pages (samma upplägg som `fampro-legal`)

Källfiler för en **publik** GitHub Pages-repo, parallellt med  
[github.com/Dhafen/fampro-legal](https://github.com/Dhafen/fampro-legal) ( `index.html`, `support.html`, `privacy.html` ).

## Publika URL:er (efter att repot finns och Pages är påslaget)

Anta repo-namnet **`qrscanner-legal`** under användaren **`Dhafen`** och att GitHub Pages publiceras från **`main`** / **root**:

| Sida | URL |
|------|-----|
| Startsida | `https://dhafen.github.io/qrscanner-legal/` |
| **Support (App Store Connect)** | `https://dhafen.github.io/qrscanner-legal/support.html` |
| **Integritet (ASC / App Privacy)** | `https://dhafen.github.io/qrscanner-legal/privacy.html` |

Byt `dhafen` / `qrscanner-legal` om du använder annat användarnamn eller repo-namn.

## Skapa repot och publicera

1. På GitHub: **New repository** → namn t.ex. `qrscanner-legal` → **Public** → skapa (utan README om du pushar denna mapp).
2. Lokalt från denna katalog:

   ```bash
   cd /Users/elon/MacStudioAI/apps/qrscanner/docs/qrscanner-legal
   git init
   git add index.html support.html privacy.html README.md
   git commit -m "Add GitHub Pages for QR Premium"
   git branch -M main
   git remote add origin https://github.com/Dhafen/qrscanner-legal.git
   git push -u origin main
   ```

3. I repot på GitHub: **Settings → Pages** → **Build and deployment**: *Deploy from a branch* → Branch **main**, folder **/ (root)** → Save.
4. Vänta en minut och öppna support-URL i webbläsare. Klistra in **Support URL** och **Privacy Policy URL** i App Store Connect och uppdatera `docs/APPSTORE_METADATA.md`.

## Kontakt-e-post

`support.html` och `privacy.html` använder samma inkorg som Fampro (`fampro.app@outlook.com`). Byt i båda filerna om QR Premium ska ha en egen adress.

## Juridik

Detta är en **mall** för webbsidor, inte juridisk rådgivning. Justera integritetstexten så den stämmer exakt med faktisk datainsamling i appen innan release.
