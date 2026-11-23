---
id: B1-KENNISLAAG
type: index
naam: Kennislaag bundel 1
samenvatting: Ingang voor mens en AI tot bundel 1, met vaste id's voor bronnen en feiten, gedeclareerde datumsoorten en een kruistabel over de bestaande dossierdocumenten.
status: vastgesteld
maturiteit: ontwerp
goedgekeurd_door: niet goedgekeurd (geen menselijke review vastgelegd)
laatst_bijgewerkt: 2026-11-23
---

# Kennislaag bundel 1

[Bundel 1](../README.md) · [Dossierdocumenten](../dossierdocumenten/) · Bewijsstukken (lokaal)

De dossierdocumenten van bundel 1 blijven ongewijzigd. Deze map legt er een dunne laag naast, zodat een lezer of een tool snel kan nagaan **welke bron wat zegt, op welke datum, en waar dat in de analyses terugkomt**. Ze volgt de [kennisengineering-skill](../../../../.claude/skills/kennisengineering/SKILL.md).

| Bestand | Waarvoor |
|---|---|
| [bronregister.md](bronregister.md) | Elke bron met vaste id (`B1-S01` …), datums per datumsoort, rol en wat werd nagekeken. Begin hier. |
| [kruistabel.md](kruistabel.md) | Waar elk feit (`B1-F00` …) terugkomt in de zes nummeringen van de dossierdocumenten. |
| [woordenboek.md](woordenboek.md) | Eén zin per term, van "datumsoort" tot "Spoor B". |
| [vocabularium.yaml](vocabularium.yaml) | De enige lijst van toegelaten waarden (status, datumsoort, bronrol, relatie …), machineleesbaar. |

## Lagen

| Laag | Wat | Waar |
|---|---|---|
| Bron | Mails, brieven, pdf's, schermafbeelding | `bewijsstukken/` (lokaal, niet in Git) en de toetssteen in `dossierdocumenten/` |
| Intake | Registratie van elke bron met datums en rol | [bronregister.md](bronregister.md) |
| Feiten | F0–F10 uit het dossieroverzicht | voorlopig in het dossieroverzicht; id's in [kruistabel.md](kruistabel.md) |
| Uitvoer | Juridische nota, audit, register, deel-dossier, pdf's | `dossierdocumenten/` |
| Extern ingediend | Klachten en andere stukken die naar buiten gingen | [`output/`](../output/index.md) (alleen de index in Git) |

## Twee regels voor wie verder bouwt

1. **Een datum zonder datumsoort is onvolledig.** Versiedatum, vastleggingsdatum, documentdatum en verzenddatum zijn vier verschillende dingen; zie het [woordenboek](woordenboek.md#datums).
2. **Bundel 1 is een afgesloten geheel.** Kopieën van dezelfde stukken in andere bundels tellen hier niet als bron en niet als bevestiging.

## Stand

- Opgesteld door een agent op 23 november 2026; nog door geen mens nagekeken.
- Wat de agent wel en niet heeft nagekeken, staat onderaan het [bronregister](bronregister.md#ontvangstbewijs-van-deze-intake).
- Open punten die het register zichtbaar maakt (o.a. de hernummering van "bewijsstuk 10", bronnen van na 18 juni 2026 die nog niet verwerkt zijn) staan bovenaan het [bronregister](bronregister.md#aandachtspunten-die-het-register-zichtbaar-maakt).
