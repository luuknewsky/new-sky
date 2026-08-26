# Skills

Elke skill krijgt hier een eigen map. De mapnaam is de naam van de skill: kleine letters, woorden gescheiden door een streepje.

## Mapindeling

```
.claude/skills/
  naam-van-de-skill/
    SKILL.md        verplicht
    references/     optioneel, achtergrondinfo die Claude erbij pakt
    assets/         optioneel, templates, sheets en afbeeldingen
    scripts/        optioneel, scripts die de skill uitvoert
```

## Format van SKILL.md

Het bestand begint met frontmatter tussen twee regels met drie streepjes:

```
---
name: naam-van-de-skill
description: Wat de skill doet en wanneer Claude hem gebruikt. Noem concrete triggerzinnen, daar wordt de skill op herkend.
---
```

Daaronder staan de instructies zelf, stap voor stap in de volgorde waarin ze uitgevoerd worden.

Regels voor de naam:

- gelijk aan de mapnaam
- alleen kleine letters, cijfers en streepjes
- maximaal 64 tekens

## Install-URL

Wijs naar de map van de skill, niet naar de repo.

Goed:
https://github.com/luuknewsky/new-sky/tree/main/.claude/skills/naam-van-de-skill

Fout:
https://github.com/luuknewsky/new-sky
