# Back to Being — sponsoring (zonder betaalpagina)

Statische **sponsor-deck**: dezelfde opzet als [met-bedragen op de hoofdsite](https://cschoorl.github.io/Back-to-Being/met-bedragen.html), maar **zonder bunq/checkout**. De drie niveaus (€1k / €5k / €10k) openen **mailto** naar hetzelfde adres als in de deck.

## Live bekijken

- **Repository:** https://github.com/Cschoorl/Back-to-being-sponsoring-
- **GitHub Pages** (als ingeschakeld onder *Settings → Pages*, branch `main`, map `/ (root)`):  
  https://cschoorl.github.io/Back-to-being-sponsoring-/

Open `index.html` in de root van de repo voor de volledige ervaring (preloader, logo’s, slides).

## Lokaal openen

Clone de repo en open `index.html` in je browser, of gebruik een eenvoudige server:

```bash
git clone https://github.com/Cschoorl/Back-to-being-sponsoring-.git
cd Back-to-being-sponsoring-
python3 -m http.server 8080
```

Ga naar http://localhost:8080

## Structuur

| Pad | Inhoud |
|-----|--------|
| `index.html` | Volledige deck (NL/EN, inline CSS & JS) |
| `assets/brand/` | Logo voor de topbar |
| `assets/lottie/` | Preloader-animatie |
| `assets/partners/` | Partnerlogo’s op de slides |

## Aanpassen

- **Contactmail:** staat in `index.html` (zoek op `Caesar.schoorl@gmail.com` in het `<script>`-blok en in de contactslide).
- **Teksten / slides:** alles in `index.html`.
