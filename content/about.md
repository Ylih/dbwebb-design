---
Title: ABOUT
Description: Page about techniques
---

Tekniker
===========

PICO
----
Pico är det content management system (CMS) som har använts vid skapandet av denna sida.

TWIG
----
Twig är en så kallad template engine. Kortfattat används en template engine för att kombinera en mall (template) med en datamodell för att leverera ett resultat. I bilden nedan kan man se filen index.twig. Det index.twig gör är att den inkluderar header, nav och footer på varje sida. Där det står {{ content }} på bilden hamnar vår data. I detta fall är datan allt som är mellan nav och footer på hemsidan.

[![Twig index](%base_url%/assets/img/template.jpg "Bild på index twig")](%base_url%/assets/img/template.jpg)

SASS
----
SASS är en så kallad pre-processor till CSS. SASS ger möjligheten att använda saker som CSS inte har. Några exempel på detta är: variabler, nested rules, mixins och inbyggda funktioner. Genom att använda en pre-processor så minskas repetition av kod vilket i sin tur gör att det blir mer organiserat.
