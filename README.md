# Koordinata Street — sajt za GitHub Pages

Sve je već kompajlirano. Svaki HTML fajl je potpuno samostalan: slike, fontovi i JavaScript su ugrađeni. Nema build koraka i nema foldera za otpremanje.

## Fajlovi
- `index.html` — sajt
- `blueprint.html` — dizajn sistem i arhitektura
- `pregled.html` — desktop + mobilni pregled jedan pored drugog
- `.nojekyll` — isključuje Jekyll obradu na GitHubu

## Objavljivanje na https://<korisnik>.github.io/koordinatastreet/
1. Napravi repozitorijum sa imenom **koordinatastreet**.
2. Obriši sve stare fajlove iz repozitorijuma.
3. Add file → Upload files → prevuci `index.html`, `blueprint.html`, `pregled.html` i `.nojekyll` → Commit.
4. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
5. Sačekaj 1–2 minuta i otvori `https://<korisnik>.github.io/koordinatastreet/`.

Napomena: sajt otvaraj preko **github.io** adrese, ne preko github.com prikaza fajla — tamo GitHub uvek prikazuje kod.
