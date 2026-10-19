# Hry s tátou

Jednoduchá offline hra v prohlížeči pro tříletou dceru — hraje **společně s tátou**, ne sama.

## Jak otevřít

### Varianta A — dvojklik (nejjednodušší)

1. Otevři složku `hry-pro-dceru`.
2. Dvojklikni na soubor `index.html`.
3. Otevře se v prohlížeči (Chrome, Firefox, Edge, Safari).

### Varianta B — malý lokální server

Pokud by v prohlížeči něco nefungovalo přes `file://`, spusť v této složce:

```bash
cd /cesta/k/hry-pro-dceru
python3 -m http.server 8080
```

Pak v prohlížeči otevři: <http://localhost:8080>

## Co je uvnitř

Čtyři krátké aktivity (každá cca 5–10 minut, jasný konec „Hotovo, končíme“):

1. **Třídění** — barvy a tvary do košíků (ťukni na obrázek, pak na košík)
2. **Zvířátka** — „Kdo dělá bú?“ (kráva, pejsek, kočička, slepice, prasátko, koník)
3. **Pexeso** — 4 nebo 6 dvojic
4. **Počítání** — spočítej 1–5 a ťukni na číslo

Ovládání jen myší / prstem, velké cíle, žádné tažení ani klávesnice.

## Mluvené pokyny (čeština)

Hra umí číst pokyny nahlas přes Web Speech API (`speechSynthesis`, `cs-CZ`).

- Funguje jen pokud má prohlížeč nainstalovaný **český hlas**.
- V Chrome / Edge: Nastavení → Jazyky / Přístupnost → Textová řeč → zkontroluj češtinu.
- Tlačítko 🔊 vpravo nahoře pokyn zopakuje.
- Bez českého hlasu jde hra stejně hrát — jen bez namluvení.

## Soukromí

- Žádná data se neukládají (žádné cookies, žádný účet).
- Žádné reklamy, nákupy ani odkazy ven.
- Hraje se **offline** — po otevření stránky internet nepotřebuješ.
- Všechno je v jednom souboru `index.html`.

## Poznámka od Elišky

Věk 2–5 let: max. ~1 hodina obrazovky denně, ideálně společně. Hra je záměrně krátká, bez bodů, žebříčků a časového tlaku.
