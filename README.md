# Keijo — Portfolio

Henkilökohtainen portfolio, joka esittelee osaamiseni, projektit ja tarjoaa keinot ottaa yhteyttä. Tämä harjoitusprojekti on tehty HTML:llä, CSS:llä ja JavaScriptillä.

## Sisältö

- Etusivu: esittely ja projektien yhteenveto
- Projektit: projektikortit ja linkit (GitHub / Live)
- Palvelut: tarjoamani palvelut ja hinnasto (esimerkki)
- Taidot: osaamisprofiili ja osaamistasot
- Yhteystiedot: lomake ja yhteystiedot

## Ominaisuudet

- Responsiivinen layout ja yksinkertainen mobiilivalikko
- Saavutettavuusparannuksia (skip-link, ARIA-attribuutit)
- Popup-yhteydenottolomake (asiakaspuolen validointi)
- Animaatiot osaamisprofiilille (asteikkopalkit)

## Paikallinen esikatselu

1. Kloonaa tai lataa repo:

```bash
git clone https://github.com/pentinmaki/portfolio.git
cd portfolio
```

2. Avaa `index.html` selaimessa: kaksoisklikkaus tai vedä tiedosto selaimeen.

Vaihtoehtoisesti voit käyttää yksinkertaista paikallista serveriä (esim. Python):

```bash
# Python 3
python -m http.server 8000
# Selaa http://localhost:8000
```

## Julkaisu

- Suosittelen GitHub Pages -julkaisua: aseta branch `main` tai `gh-pages` GitHubin Pages-asetuksista.

## Muokkaus & laajennus

- Projektin rakenne on yksinkertainen — lisää uusia HTML-sivuja ja päivitä `style.css`.
- Voit siirtää projektit JSON-tiedostoon ja renderöidä ne JavaScriptillä helpompaa ylläpitoa varten.

## Lomake (yhteystiedot)

- Nykyinen popup-lomake toimii paikallisella validoinnilla. Jos haluat toimivan sähköposti lähetyksen ilman omaa backendia, käytä esim. Formspree tai EmailJS ja päivitä `form action` tai JavaScript.

## Saavutettavuus

- Lisäsin skip-linkin ja ARIA-attribuutteja valikolle. Testaa sivustoa näppäimistöllä ja ruudunlukuohjelmalla.

## Kehitysaskelia / To-do

- Lisää projektille kuvat ja yksityiskohtaiset case-esimerkit
- Lisää kommit- ja deploy-työkalut (GitHub Actions)
- Lisää dark-mode-teema ja teemanvaihtaja

## Yhteystiedot

- Sähköposti: keijo@example.com
- GitHub: https://github.com/pentinmaki

## Lisenssi

Tämä projekti on MIT-lisenssillä.

---

Päivitetty: 2026-02-16 — parannuksia saavutettavuuteen ja README-dokumentaatioon.