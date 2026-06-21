# AGENTS.md

Instruccions per a agents que treballen en aquest repositori.

## Projecte

Aquest repositori conté el manuscrit i la documentació de treball de la novel·la **Al Jimmy Bar**.

El tema central de l'obra és la família escollida. Abans de proposar canvis narratius importants, consulta sempre:

- `notes/biblia-novella.md`: font principal de personatges, temes, conflictes i normes del món.
- `manuscrit/00-index.md`: ordre actual dels capítols.
- `docs/guia-estil.md`: criteris d'estil, si el canvi afecta la veu o la correcció del text.

## Estructura

- `manuscrit/`: capítols en Markdown, un fitxer per capítol.
- `notes/`: bíblia, sinopsi, escaleta, personatges i idees narratives.
- `recursos/originals/`: documents font originals, com `.docx`, que s'han de conservar intactes.
- `docs/`: guies, criteris i materials de suport.

## Convencions de manuscrit

- Els capítols viuen en `manuscrit/` amb format `NN-capitol-N.md`.
- Cada capítol ha de començar amb un títol H1:
  `# Capítol N: Títol del capítol`
- Mantín `manuscrit/00-index.md` actualitzat quan s'afegisquen, eliminen o reordenen capítols.
- No canvies noms, relacions o fets de continuïtat sense contrastar-los amb `notes/biblia-novella.md`.
- Si detectes contradiccions entre el manuscrit i la bíblia, assenyala-les abans de reescriure-les.

## Originals i conversions

- No edites directament els fitxers de `recursos/originals/`.
- Els `.docx` originals serveixen com a arxiu font.
- Les versions treballables han d'estar en Markdown dins de `manuscrit/`.
- Si converteixes documents, conserva accents, diàlegs i separació de paràgrafs.

## Estil de treball

- Escriu i respon en valencià/català quan el context del projecte ho permeta.
- Mantín la veu emocional i realista de drama juvenil.
- Prioritza coherència de personatges, conseqüències emocionals i evolució lenta de les relacions.
- Evita convertir els conflictes en resolucions ràpides: les reconciliacions han de costar.
- La música i el Jimy Bar són elements simbòlics recurrents; preserva'ls quan siguen rellevants.

## Git

- Abans de tocar fitxers, revisa l'estat amb `git status --short`.
- No revertisques canvis que no siguen teus.
- Fes commits menuts i descriptius quan l'usuari ho demane.
- Si afegeixes capítols, inclou també l'actualització de l'índex en el mateix commit.
