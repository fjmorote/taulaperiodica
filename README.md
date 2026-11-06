# Taula periòdica · Joc

App web (un sol fitxer, sense dependències) per practicar la taula periòdica dels
estats d'oxidació / càrregues dels ions (47 elements, els de la taula del full).

L'app il·lumina una casella a l'atzar i has d'omplir:

- **Símbol**
- **+/−**: com a la taula del full, cada casella té una columna **esquerra** i una **dreta**, i els valors s'han de posar **en el mateix ordre** de dalt a baix (p. ex. N: esquerra −3, dreta +1 +3 +5 +2; Mn: esquerra +6 +7, dreta +2 +3 +4). Negatius en blau, positius en vermell
- **Nom** en català (normativa de l'IEC; accepta sense accents ni punt volat)
- **Protons** (nombre atòmic)

Les caselles s'acoloreixen segons el resultat (al primer intent / amb errors / solució)
i les que falles tornen a sortir al final. Es pot limitar l'abast (períodes 1–3, 1–4,
grups principals, metalls de transició).

## Nivells

| Nivell | Què veus | Què demana |
|---|---|---|
| Bàsic | el símbol a la casella | nom |
| Mitjà | res (casella amb «?») | símbol + nom |
| Avançat | res | símbol + nom + protons |
| Expert | res | tot: símbol + nom + protons + +/− (esquerra/dreta i ordre) |

## Ordre

Aleatori, **per files** (període a període, d'esquerra a dreta) o **per columnes** (grup a grup, de dalt a baix).
El nivell, l'ordre i l'abast es recorden al navegador.

## Rànquing

En acabar la **primera ronda** (totes les caselles resoltes una vegada) apareix el resultat i pots desar-lo amb el teu nom.
Hi ha un rànquing **per nivell** (i per abast, perquè 47 caselles i 20 no són comparables). S'ordena per encerts al primer intent
i, en cas d'empat, per temps. Les caselles saltades o revelades no compten com a encert; després pots repassar els errors.
El rànquing es guarda al navegador del dispositiu (no hi ha servidor): el mòbil i l'ordinador tenen rànquings separats.
Es pot consultar en qualsevol moment amb el botó 🏆 Rànquing.

## Ús

Obre `index.html` al navegador.
