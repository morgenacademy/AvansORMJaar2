# Medior Semester — Doorontwikkeling jaar 2

Dit is de werkrepository voor het herontwerp van het medior semester (jaar 2) binnen de ORM-opleiding. Collega's vinden hier de gepubliceerde praatplaat én de onderbouwing van de keuzes die eraan ten grondslag liggen.

**Gepubliceerde praatplaat:** zie de `docs/`-map of de Netlify-deploylink.

---

## Wat stuurt dit ontwerp?

Jaar 2 wordt scherper gepositioneerd: van kennismaken (jaar 1) naar verdiepen en toepassen. Drie bewuste keuzes bepalen de structuur:

1. **Beide kennislagen, niet kiezen.** De discussie over "meer kennis" wordt niet opgelost door te kiezen tussen aanpakvaardigheden óf vakinhoud — het ontwerp doet bewust beide. Groeien bouwt projectmanagementkennis op; Rendabel maken voegt vakinhoudelijke verdieping toe.

2. **Kennis direct toepassen.** Elk kennismoment is gekoppeld aan een werksessie diezelfde week. Geen losse workshops, maar echte tracks met voortgang.

3. **Tussentijdse toetsing.** Bewust ingebouwd na Groeien en binnen Skills of the Future, zodat studenten eerder feedback krijgen en herkansbare blokken kleiner worden.

---

## Kernlogica per onderdeel

### Groeien (Projectkennis, 3 ECTS)
- Strak, gezamenlijk blok gericht op het leren aanpakken van een challenge of project — bewust gelabeld als projectmanagement.
- In jaar 1 zit projectmanagement nog verborgen onder onderzoek; in jaar 2 maken we dit expliciet.
- Projectkennis is ingebouwd in het maandagritme: kennis + uitleg (11:30–12:00), direct toepassen in de challenge (12:00–14:00). Die 0,5 uur wordt niet dubbel geteld in de urenbegroting.
- Afgesloten met een kennistoets; inzage in week 9, herkansing in week 10.

### Business Challenge I (7 ECTS)
- Start standaard met een zo echt mogelijke casus in groepjes van vier.
- Uitzondering week 1: studenten met een sterk eigen bedrijf of externe organisatie kunnen dit pitchen aan hun coach.
- Werksessies: maandag 12:00–14:00 en woensdag 09:00–11:00.
- Afgesloten met een eindpitch.

### Business Challenge II (7 ECTS)
- Eigen bedrijf of externe organisatie — de student regelt de plek zelf.
- Voorbereiding via Routekeuze CH2 vanaf week 6 (blok 1).
- Opbouw via zes korte BMC-gerichte vakcolleges (maandag 11:30–12:00 in week 12–17): Marketing, Sales, Proces, Inkoop & cost structure, Verdienmodel & finance, Legal.
- Studenten vullen op basis van die colleges het BMC verder uit en bouwen tegelijk aan hun portfolio voor CH2.
- Week 18 = kennistoets, week 19 = inzage, week 20 = herkansing.

### Rendabel maken (Vakkennis, 3 ECTS)
- De zes vakcolleges borgen de kennislijn (3 ECTS) apart van de challenge.
- Een AI-vrije kennistoets bewaakt de vakinhoudelijke rode draad: van projectmanagement naar vakinhoudelijke verdieping, en van oefenen naar onderbouwd toepassen.

### Skills of the Future I & II (5 ECTS per blok)
- Oude inhoudelijke keuzetracks verdwijnen; studenten volgen per blok beide praktijktracks.
- **MDT Missie** en **AI Lab** wisselen wekelijks af op donderdag 09:00–13:00.
- Week 1 (blok 1) en week 11 (blok 2): skill-test → doelen stellen → skill-paspoort.
- Docentbelasting: AI Lab = 2 docenten in het eerste uur + 4 in het werkdeel; MDT Missie = 2 docenten voor het hele blok.
- Coachlijn (Janne, Tom, Rosemarijn, Harmen) loopt parallel en wordt apart begroot.

---

## Urenbegroting

Werkhypothese: budget = ECTS × 28 uur × 75%. Toetstijd is inclusief 50% herkansing.

### Blok 1 — Groeien

| Module | ECTS | Contacttijd | Toetstijd | Zelfstudie | Totaal |
|---|---|---|---|---|---|
| Projectkennis | 3 | 5,0 uur | 1,5 uur | 56,5 uur | 63 uur |
| Business Challenge I | 7 | 26,0 uur | 0,75 uur | 120,25 uur | 147 uur |
| Skills of the Future I | 5 | 27,0 uur | 0,75 uur | 77,25 uur | 105 uur |
| **Totaal** | **15** | **58,0 uur** | **3,0 uur** | **254,0 uur** | **315 uur** |

### Blok 2 — Rendabel maken

| Module | ECTS | Contacttijd | Toetstijd | Zelfstudie | Totaal |
|---|---|---|---|---|---|
| Vakkennis | 3 | 4,0 uur | 1,5 uur | 57,5 uur | 63 uur |
| Business Challenge II | 7 | 32,0 uur | 0,75 uur | 114,25 uur | 147 uur |
| Skills of the Future II | 5 | 29,25 uur | 0,75 uur | 75,0 uur | 105 uur |
| **Totaal** | **15** | **65,25 uur** | **3,0 uur** | **246,75 uur** | **315 uur** |

**Let op:** het geïntegreerde maandagmoment (11:30–14:00) wordt niet dubbel geteld. De 0,5 uur valt op de kennislijn, de 2 uur op de challenge.

---

## Wat zit er in deze repo?

```
docs/               → gepubliceerde HTML-pagina's (Netlify deploy)
  index.html        → overzichtspagina / praatplaat
  weekplanning/     → weekplanning-weergave
  roostering/       → roostering-weergave
  taaklast/         → docenttaaklast-weergave
  besluiten/        → besluitenpagina met onderbouwing
README.md           → dit bestand
```

De werkbestanden (Word-documenten, Excel-sheets, HTML-archiefversies) staan lokaal maar worden niet bijgehouden in git — alleen `docs/` wordt gepubliceerd.
