# Tió de Nadal! · El joc de l'Ada de Som Mainada

Joc musical de navegador per a infants de 1r a 3r de primària, al ritme de la cançó **«Tió de Nadal»** de l'Ada de Som Mainada.

**Juga:** https://tio-de-nadal.pages.dev/

## Com es juga
- El bastó màgic pica el Tió al ritme de la música, i el Tió caga torrons, regals i caganers per 3 carrils.
- L'Ada els recull amb la cistella. Les arengades pudents resten un punt: per esquivar-les, canvia de carril o toca **la banda** per amagar-t'hi.
- Toca l'**estació** d'un carril per moure l'Ada.
- Cada 10 regals es desbloqueja un vers tradicional del Tió (n'hi ha 4). Surt uns segons sense aturar el joc, i al final de la partida es poden llegir tots.
- Una cançó, una partida: el joc s'acaba quan s'acaba la cançó, amb el missatge «Ara ves a donar menjar al teu Tió!».
- Teclat (pissarra digital): fletxes ← →, números 1–3, espai o ↓ per anar amb la banda, P per fer pausa.

## Fitxers
| Fitxer | Què és |
|---|---|
| `index.html` | El joc sencer (gràfics, lògica i so) |
| `tio-de-nadal.mp3` | La cançó |
| `portada.png` | Imatge de vista prèvia quan es comparteix l'enllaç (1200×630) |

## Sincronia amb la cançó
110 BPM (temps 0 a 0,014 s). La lletra es canta dues vegades (temps 24–47 i 48–71), pausa de bateria als temps 72–79 i melodia final fins al temps 93 (50,7 s). Els valors són a l'inici del codi (`BEAT0`, `BEAT`, `REP_STARTS`, `LINE_OFF`).

Opció: `BARRETINA_TOTHOM = true` posa barretina a tota la banda (ara només la porta l'Ada).

## Estadístiques
GoatCounter (tiodenadal.goatcounter.com, site propi separat dels altres jocs) compta les visites i aquests esdeveniments: `partida-iniciada`, `partida-acabada` i `vers-1` … `vers-4` (quants infants arriben a cada vers).

## Mode de prova
`index.html?test&t=20` comença al segon 20, sense so. Afegeix `&auto` perquè jugui sol, o `&barretines` per veure tota la banda amb barretina.

---
Cançó: «Tió de Nadal» © l'Ada de Som Mainada · Joc: Europe Multimedia Service
