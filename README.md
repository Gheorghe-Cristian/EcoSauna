# Sauna ECO — site de prezentare

Landing page pentru **Sauna ECO**, saună pe lemne din Chișinău (str. Calea Orheiului 88/5).

## Structură

```
index.html            pagina site-ului (HTML + CSS + JS, fără dependențe)
assets/img/           logo original, favicon și fotografii reale (Google Maps)
assets/fonts/         Fraunces și Manrope, găzduite local
design/               exportul inițial al designului (cu text placeholder)
preview/              tot site-ul într-un singur fișier HTML, pentru previzualizare
```

## Rulare

Se deschide `index.html` direct în browser. Pentru publicare se încarcă `index.html` și `assets/` pe orice hosting static (de exemplu GitHub Pages din ramura `main`, din rădăcină).

## De confirmat cu Sauna ECO înainte de publicare

- **Prețurile** pachetelor și ale serviciilor suplimentare (secțiunea `#preturi` din `index.html`). Sunt estimate, nu sunt publice.
- **Capacitatea** (6 persoane pentru Relax și Ritual ECO, 10 pentru Companie). Apare în pachete și în secțiunea de întrebări frecvente.
- După publicare: `og:image` din `<head>` trebuie trecut ca URL absolut cu domeniul final.

## Note

- Formularul de rezervare nu are server: deschide aplicația de e-mail cu cererea completată către office.ecosauna@gmail.com.
- Harta este un embed Google Maps și se încarcă doar online.
- Sursa datelor: Google Maps (nota 4,5 din 48 de recenzii, fotografii, recenzii), Facebook (logo), Instagram @sauna_eco, lista.md (program, facilități).
