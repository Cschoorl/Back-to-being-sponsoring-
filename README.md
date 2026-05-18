# Back to Being — sponsoring (zonder betaalpagina)

Statische **sponsor-deck** (7 slides): zelfde verhaal als [met-bedragen op de hoofdsite](https://cschoorl.github.io/Back-to-Being/met-bedragen.html), maar **zonder bunq/checkout** en **zonder** de tussenpagina met drie sponsoringskaarten. Op de laatste slide staan nog wel snelle **mailto**-knoppen per bedrag (€1k / €5k / €10k).

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
