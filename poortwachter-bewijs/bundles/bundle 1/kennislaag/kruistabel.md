---
id: B1-KRUISTABEL
type: kruistabel
naam: Kruistabel bundel 1
samenvatting: Legt de zes nummeringen van de dossierdocumenten van bundel 1 naast elkaar, met vaste id's voor feiten en bronnen en een betrouwbaarheid per koppeling.
status: interpretatief
maturiteit: ontwerp
goedgekeurd_door: niet goedgekeurd (geen menselijke review vastgelegd)
laatst_bijgewerkt: 2026-11-23
relaties:
  - document/behandelt: bronregister.md
vocabularium: vocabularium.yaml
---

# Kruistabel bundel 1

Dezelfde feiten komen in bundel 1 terug onder zes nummeringen. Deze tabel herschrijft niets; ze wijst alleen aan waar hetzelfde onderwerp staat. De koppelingen zijn een interpretatie van de agent: elke koppeling draagt een betrouwbaarheid uit [vocabularium.yaml](vocabularium.yaml). Zonder markering is de koppeling **zeker** (zelfde datum en zelfde stuk, of letterlijk dezelfde titel); *(w)* betekent **waarschijnlijk** (zelfde onderwerp en stuk, andere titel); *(o)* betekent **onzeker** (alleen thematisch).

## De documenten en hun nummering

| Id | Document | Nummering | Opmaakdatum | Herzieningsdatum | Laag |
|---|---|---|---|---|---|
| D1 | [DOSSIEROVERZICHT-Recht van inzage](../dossierdocumenten/DOSSIEROVERZICHT-Recht%20van%20inzage.md) | F0–F10, M1–M4, R1–R2, A1–A5, B0–B8 | 3 juni 2026 | 15 juni 2026 | feitenlaag (voorstel: canoniek) |
| D2 | [Deel-dossier Bundel 1](../dossierdocumenten/Deel-dossier%20Bundel%201.md) | §3.1–3.6, A1–A7, B1–B7, B1-S1–B1-S13 | onbekend | onbekend | uitvoer |
| D3 | [JURIDISCHE-NOTA-OSCARC](../dossierdocumenten/JURIDISCHE-NOTA-OSCARC-Recht%20van%20inzage.md) | OSCARC 1–8 | 16 juni 2026 | niet-in-bron | uitvoer |
| D4 | [AUDITRAPPORT-OSCARC](../dossierdocumenten/AUDITRAPPORT-OSCARC-AVG-recht-van-inzage-systemische-governance.md) | Finding 1–6, E-B1-01–E-B1-13 | 16 juni 2026 | niet-in-bron | uitvoer |
| D5 | [OSCARC-DOSSIER-EN-BEWIJSREGISTER](../dossierdocumenten/OSCARC-DOSSIER-EN-BEWIJSREGISTER-BUNDLE-1.md) | [1]–[17] | 18 juni 2026 | niet-in-bron | uitvoer |
| D6 | [INHOUDELIJKE-VALIDATIE-BUNDLE-1](../dossierdocumenten/INHOUDELIJKE-VALIDATIE-BUNDLE-1.md) | §1–11 | 16 juni 2026 | niet-in-bron | validatie |
| D7 | Juridische toetssteen, twee versies | §1–20 | 13 juni 2026 | zie [bronregister](bronregister.md#b1-jt01--juridische-toetssteen-twee-versies) | bron `B1-JT01` |
| — | Vijf pdf-versies van D1, D4, D5, D6 en D7 (versie A) | — | — | — | uitvoer, afgeleid van de md-versie |

Let op: **"A1" en "B1" betekenen in D1 en D2 iets anders.** D1 A1 is "Recht van inzage", D2 A1 is "Recht van inzage: omvang van het verzoek"; D1 B1 is "Datamapping", D2 B1 is "Datamapping en ontsluiting". Die nummers zijn daarom hier telkens voorafgegaan door het document (`D1-A1`, `D2-B1`).

## Tabel 1 · Feiten

Het dossieroverzicht (D1) is het enige document dat feiten met datum en stuk telt. Daarom krijgen de feiten hier zijn nummering: `B1-F00` = F0.

| Feit | Datum en datumsoort | Kort | Bron | D1 melding/reactie | D2 | D3 OSCARC | D4 Finding | D5 register |
|---|---|---|---|---|---|---|---|---|
| B1-F00 | 2025-11-19, verzenddatum (gesprek: 2025-10-28) | KBC levert een opgenomen gesprek per e-mail | B1-S13 | — | B1-S13 in matrix; D2-A4 *(o)* | 6 | 4 | [13] |
| B1-F01 | 2026-01-13, verzenddatum | Formeel inzageverzoek | B1-S01 | M1 | §3.1; D2-A1 *(w)* | 1 | 1 | [1] |
| B1-F02 | 2026-01-23, verzenddatum KBC-bericht | KBC vraagt zoekgegevens voor gesprekken en noemt beperkingen | B1-S02 (ook ingebed in B1-S03, B1-S06) | R1 | §3.2 *(w)* | 2 *(w)* | 2 | [2], [4] *(w)*, [10] *(w)* |
| B1-F03 | 2026-01-23, verzenddatum bericht betrokkene | Betrokkene verduidelijkt scope, aanvaardt anonimisering | B1-S02 | M2 | §3.4; D2-A6 *(w)* | 3 *(w)* | — | [3], [9] *(w)* |
| B1-F04 | 2026-01-28, verzenddatum | Betrokkene betwist uitsluiting e-mail en interne nota's | B1-S03 | M3 | §3.5; D2-A5 *(w)* | 2 *(w)* | 2 *(w)* | [5] |
| B1-F05 | 2026-01-30, beschikbaarstellingsdatum (documentdatum brief: 2026-01-29) | Eerste overzicht via de digitale documentenomgeving | B1-S04, B1-S05 | — | §3.3; D2-A2, D2-A3 *(w)* | 4 *(w)*, 8 *(w)* | 1 | [6], [7] *(w)* |
| B1-F06 | 2026-02-11, verzenddatum KBC-bericht | KBC bevestigt brede beperkingen | B1-S06 | R2 | §3.6 *(w)* | 2 *(o)* | 2 *(o)* | [8] *(w)* |
| B1-F07 | 2026-02-11, verzenddatum bericht betrokkene | Betrokkene vraagt categoriegewijze motivering, stelt redactie voor | B1-S06 | M4 | D2-A6 *(w)* | 3 *(w)* | — | [9] *(w)* |
| B1-F08 | 2026-04-24, verzenddatum KBC-bericht (verzoek betrokkene: 2026-04-23) | Derde aanvraag en doorverwijzing | B1-S07 | — | D2-A7, D2-B7 *(w)* | — | 6; 5 *(w)* | [15]; [14] *(w)* |
| B1-F09 | 2026-05-22, verzenddatum | KBC meldt verzending per aangetekende brief | B1-S08 | — | D2-B3 *(o)* | 8 *(w)* | 5 *(w)* | [16]; [14] *(w)* |
| B1-F10 | 2026-06-04, verzenddatum | KBC bevestigt ontvangst van vervolgcommunicatie | B1-S09 | — | — | 8 *(w)* | 5 *(w)* | [17]; [14] *(w)* |

## Tabel 2 · Bevindingen die niet op één feit rusten

Sommige onderdelen gaan niet over een gebeurtenis maar over context of over een patroon. Ze rusten op contextbronnen of op meerdere feiten.

| Onderwerp | Rust op | D1 | D3 OSCARC | D4 Finding | D5 register |
|---|---|---|---|---|---|
| Standaardoverzicht tegenover aanvullend opvraagbare gegevens volgens de privacyverklaring | B1-S05, B1-S11 | Synthese §9 | 4, 5 | 3 | [7], [11] |
| Verwerking breder dan basisidentificatie | B1-S05, B1-S11, B1-S12 | D1-B1 | 7 | 4 | [12] |
| Telefoongesprekken zijn lokaliseerbaar en leverbaar | B1-F00, B1-S11 | — | 6 | 4 | [13] |
| Bewaartermijn- en modelcontext | B1-F02, B1-S11 | — | — | 4 *(o)* | [10] |
| Kanaalkeuze en vorm van aanlevering | B1-F02, B1-F05, B1-F08, B1-F09, B1-F10 | D1-B3 *(w)* | 8 | 5 | [14] |
| Data Protection- en DPO-zichtbaarheid | B1-F08 | D1-B7 | — | 6 | [15] |
| Minder ingrijpende alternatieven | B1-F03, B1-F07 | D1-A4 *(w)* | 3 | 2 *(o)* | [9] |
| Juridisch kader | B1-JT01 | §3 | alle (rubriek S) | §2.4 | rubriek S |

## Tabel 3 · Bronnen zonder plaats in de dossierdocumenten

Deze bronnen staan in de bundel maar worden door geen enkel dossierdocument behandeld (afwezigheid: nog-niet-uitgewerkt). Ze zijn vastgelegd, niet geïnterpreteerd.

| Bron | Datum en datumsoort | Waarom ze hier staat |
|---|---|---|
| B1-L3 | 2026-02-20, verzenddatum | KBC-bericht na de herinnering van 13 februari; geen eigen feit in D1 |
| B1-L4 (ook ingebed in B1-S08) | 2026-05-07, verzenddatum | KBC-reactie van 7 mei; geen eigen feit in D1 |
| B1-S10 | 2026-06-28, verzenddatum | KBC meldt geen bijkomende inhoudelijke toelichting meer te geven |
| B1-S14 | 2026-07-06 en 2026-07-17, verzenddatums | KBC stelt beluisteren in een kantoor voor; de betrokkene gaat in op het voorstel |
| B1-S15 | niet-in-bron | Klachtformulier GBA; zijn "Bewijsstuk 10" is B1-S10 |

## Wat deze tabel niet doet

- Ze beslist niet welk document gelijk heeft wanneer twee documenten een feit anders formuleren.
- Ze maakt D1 niet canoniek; dat is een voorstel dat een menselijke beslissing vraagt.
- Ze vult geen ontbrekende feiten aan voor de bronnen in tabel 3.
