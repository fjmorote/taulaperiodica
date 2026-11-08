# Taula periòdica · Joc

App web (un sol fitxer, sense dependències) per practicar la taula periòdica dels
estats d'oxidació / càrregues dels ions (47 elements, els de la taula del full).

L'app il·lumina una casella a l'atzar i has d'omplir:

- **Símbol**
- **Nom** en català (normativa de l'IEC; accepta sense accents ni punt volat)
- **+/−**: com a la taula del full, cada casella té una columna **esquerra** i una **dreta**, i els valors s'han de posar **en el mateix ordre** de dalt a baix (p. ex. N: esquerra −3, dreta +1 +3 +5 +2; Mn: esquerra +6 +7, dreta +2 +3 +4). Negatius en blau, positius en vermell
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

## Protons (check de la capçalera)

El check **Protons** decideix si es demanen els protons. Cada nivell el deixa en un valor per defecte (Bàsic i Mitjà: no; Avançat i Expert: sí) i el pots canviar.
«Avançat» és «Mitjà + protons», així que marcar-lo a Mitjà passa a Avançat i desmarcar-lo a Avançat torna a Mitjà.
El rànquing separa les variants: Bàsic, Bàsic + protons, Mitjà, Avançat, Expert sense protons i Expert.

## Ordre

Aleatori, **per files** (període a període, d'esquerra a dreta) o **per columnes** (grup a grup, de dalt a baix).
El nivell, l'ordre i l'abast es recorden al navegador.

## Rànquing

En acabar la **primera ronda** (totes les caselles resoltes una vegada) apareix el resultat i pots desar-lo amb el teu nom.
Hi ha un rànquing **per nivell** (i per abast, perquè 47 caselles i 20 no són comparables). S'ordena per encerts al primer intent
i, en cas d'empat, per temps. Les caselles saltades o revelades no compten com a encert; després pots repassar els errors.
El rànquing es guarda al navegador del dispositiu (no hi ha servidor): el mòbil i l'ordinador tenen rànquings separats.
Es pot consultar en qualsevol moment amb el botó 🏆 Rànquing.

## Canviar de fila o columna

Amb l'ordre **per files** o **per columnes**, a la pregunta hi ha un selector «Canvia de fila…» (o columna) amb les que encara tenen caselles pendents.
Pots començar per la que vulguis: continua en ordre fins al final i torna a l'inici per les que s'havien saltat.

## Desplegament

Es publica amb GitHub Pages directament des de `main` (carpeta arrel): cada `git push` a `main` es desplega sol.
Només cal activar-ho un cop a *Settings → Pages → Source: Deploy from a branch → `main` / `(root)`*.

## Ús

Obre `index.html` al navegador.
