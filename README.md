# Szmötty

A zenekar statikus weboldala a `Weblap terv.pdf` alapján. A nyitókép és a logó a főoldalon szerepel, az öt menüpont önálló HTML-oldalra vezet.

## Helyi előnézet

A projekt mappájában futtasd:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Nyisd meg a böngészőben a `http://127.0.0.1:8000` címet. A YouTube-lejátszókhoz internetkapcsolat szükséges.

## Forrásfájlok

- `index.html` – a főoldal nyitóképe és logója
- `rolunk.html`, `galeria.html`, `live.html`, `linktree.html`, `kapcsolat.html` – az öt menüpont oldala
- `style.css` – a látványtervhez igazodó, reszponzív megjelenés
- `assets/images/` – a látványtervből és a mellékelt zenekari fotókból származó webes képek
- `assets/fonts/` – az Elegant Typewriter Light betűtípus és Lukas Krakora licencszövege. A betűtípus nem kereskedelmi célra használható ingyenesen.
