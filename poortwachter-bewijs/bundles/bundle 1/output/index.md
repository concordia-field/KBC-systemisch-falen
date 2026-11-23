---
id: B1-OUTPUT-INDEX
type: index
naam: Output bundel 1
samenvatting: Statusoverzicht van wat vanuit bundel 1 naar buiten ging of gaat, zoals klachten bij de GBA.
status: vastgesteld
maturiteit: kiem
goedgekeurd_door: niet goedgekeurd (geen menselijke review vastgelegd)
laatst_bijgewerkt: 2026-11-23
vocabularium: ../kennislaag/vocabularium.yaml
---

# Output bundel 1

[Bundel 1](../README.md) · [Kennislaag](../kennislaag/README.md) · [Dossierdocumenten](../dossierdocumenten/)

Deze map bevat de stukken die vanuit bundel 1 extern werden ingediend of worden voorbereid. Alleen dit `index.md` staat in Git. De stukken zelf bevatten persoonsgegevens en blijven lokaal, net als de bewijsstukken (zie de [PIA](../../../../Publicatie-impactanalyse%20%28PIA%29.md)).

**Hoe dit overzicht werkt.** Elke rij is één ingediend of voorbereid stuk. De status komt uit `uitvoerstatus` in het [vocabularium](../kennislaag/vocabularium.yaml). Een datum staat altijd bij zijn soort. Wat niet bekend is, krijgt een afwezigheidswaarde en blijft niet leeg.

## Overzicht

| Id | Stuk | Indiener | Bij | Kanaal | Status | Datum (soort) | Kenmerk | Bestand in `output/` |
|---|---|---|---|---|---|---|---|---|
| B1-O1 | Klacht recht van inzage, eigen formulier | betrokkene | GBA | online formulier | ingediend | onbekend (het formulier draagt geen datum) | `COM-2026-00932` (in bestandsnaam; betekenis niet-in-bron) | nog-niet-toegevoegd · nu als `B1-S15` in `bewijsstukken/` |
| B1-O2 | Klacht opgesteld door advocaat | advocaat, namens betrokkene | GBA | onbekend | ingediend | onbekend | onbekend | nog-niet-toegevoegd |

## Per stuk

### B1-O1 · Klacht via het online formulier van de GBA

| Veld | Waarde |
|---|---|
| Status | ingediend (beweerd door de betrokkene, 2026-11-23) |
| Indieningsdatum | onbekend: het formulier draagt geen datum; het lokale bestand werd op 2026-07-17 gewijzigd, maar dat is geen indieningsdatum |
| Meegestuurde bewijsstukken | negen bestanden volgens de bijlagenlijst: bewijsstukken 01, 02, 03, 05, 06, 07, 08, 09 en `bewijsstuk_10_2026-06-26_…eml` (`B1-S10`). Bewijsstuk 04 zat er niet bij. |
| Nummering | "Bewijsstuk 10" in deze klacht = `B1-S10`, de KBC-mail van eind juni 2026 |
| Volgende stap | de betrokkene voegt het formulier toe aan `output/`; ontvangstbevestiging en kenmerk van de GBA nog vastleggen |

### B1-O2 · Klacht opgesteld door een advocaat

| Veld | Waarde |
|---|---|
| Status | ingediend (beweerd door de betrokkene, 2026-11-23) |
| Indieningsdatum | onbekend |
| Kenmerk | onbekend |
| Meegestuurde bewijsstukken | onbekend; nakijken of de nummering dezelfde is als in B1-O1, in het bijzonder "bewijsstuk 10" |
| Verhouding tot B1-O1 | onbekend: aanvulling, vervanging of afzonderlijk dossier |
| Volgende stap | de betrokkene voegt de klacht toe aan `output/` |

## Logboek

| Datum | Wijziging | Door |
|---|---|---|
| 2026-11-23 | Map aangemaakt; B1-O1 en B1-O2 geregistreerd op basis van de mededeling van de betrokkene | agent |
