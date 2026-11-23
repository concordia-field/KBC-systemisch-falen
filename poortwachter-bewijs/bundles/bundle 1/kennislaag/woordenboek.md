---
id: B1-WOORDENBOEK
type: woordenboek
naam: Woordenboek bundel 1
samenvatting: Eén zin per term die in de documenten van bundel 1 terugkomt, zodat mens en AI dezelfde betekenis lezen.
status: gedefinieerd
maturiteit: ontwerp
goedgekeurd_door: niet goedgekeurd (geen menselijke review vastgelegd)
laatst_bijgewerkt: 2026-11-23
---

# Woordenboek bundel 1

De toegelaten waarden voor status, maturiteit, epistemische basis, afwezigheid, datumsoort, bronrol, relatie en betrouwbaarheid staan alleen in [vocabularium.yaml](vocabularium.yaml). Dit woordenboek herhaalt die lijsten niet; het legt de termen uit die de dossierdocumenten gebruiken.

## Datums

| Term | Betekenis |
|---|---|
| **datumsoort** | Elke datum hoort bij een soort (documentdatum, versiedatum, vastleggingsdatum, …); twee verschillende datums van een andere soort zijn geen tegenstrijdigheid. Voorbeeld: de privacyverklaring heeft versiedatum 22 mei 2026 en werd door de betrokkene vastgelegd op 14 juni 2026; dat zijn twee waarheden over hetzelfde stuk. |
| **bestandsnaamdatum** | De datum in een genormaliseerde bestandsnaam (`bewijsstuk_05_2026-01-30_…`) volgt telkens één datumsoort; welke, staat per stuk in het [bronregister](bronregister.md). |
| **tijdzone** | KBC-mails dragen hun Date-header in UTC (`+0000`); omgerekend naar Belgische tijd is dat +1 uur in de winter en +2 uur in de zomer, wat de dag kan doen verspringen. |

## Stukken en bronnen

| Term | Betekenis |
|---|---|
| **stuk** | Een genummerd bewijsstuk zoals de dossierdocumenten het noemen ("Stuk 5"); in de kennislaag heet het `B1-S05`. |
| **B1-S…** | Vaste id van een bron in bundel 1; de deel-dossiernotatie `B1-S5` en de notatie "Stuk 5" verwijzen naar dezelfde bron. |
| **Bijlage JT-01** | De juridische toetssteen (`B1-JT01`); tot 2026-11-23 heette ze "Stuk 10", een nummer dat nu de KBC-mail van eind juni draagt, zoals in de GBA-klacht. |
| **ingebed bericht** | Een eerder bericht dat geciteerd staat in een latere e-mail; het bewijst wat er toen geschreven werd, voor zover het citaat niet werd gewijzigd. |
| **topbericht** | Het bovenste, meest recente bericht van een bewaarde `.eml`; zijn datum is de exportdatum van die keten, niet de datum van de ingebedde berichten. |
| **legacy** | De map `bewijsstukken/legacy/` met bronbestanden van vóór de normalisatie van de bestandsnamen; zie het bronregister voor wat ze wel en niet zijn. |
| **bewijsstukken (lokaal)** | De map met bronbestanden; ze bevat persoonsgegevens en wordt door Git genegeerd, zodat links ernaar alleen lokaal werken. |
| **dossierdocument** | Een analyse die uit de bronnen werd opgesteld (dossieroverzicht, juridische nota, audit, register, validatie); het is uitvoer, nooit zelf een bron. |

## Nummeringen in de dossierdocumenten

| Term | Betekenis |
|---|---|
| **F0–F10** | Feitennummers in het dossieroverzicht; de kennislaag neemt ze over als `B1-F00`–`B1-F10`. |
| **M1–M4, R1–R2** | Meldingen van de betrokkene (M) en reacties van KBC (R) in het dossieroverzicht, hoofdstuk 5. |
| **[1]–[17]** | Bouwstenen in het OSCARC dossier- en bewijsregister. |
| **OSCARC 1–8** | Genummerde vaststellingen in de juridische nota. |
| **Finding 1–6** | Auditbevindingen in het auditrapport. |
| **A1–A7, B1–B7** | Onderdelen van Spoor A en Spoor B in het deel-dossier; het dossieroverzicht gebruikt eigen, andere A- en B-nummers. |
| **OSCARC** | Vaststellingstechniek per bevinding: objectieve vaststelling, standaard of norm, chronologie en context, acties of nalatigheden, resultante, conformiteitsoordeel. |

## Onderwerpen

| Term | Betekenis |
|---|---|
| **Spoor A** | Het individuele dossier: hoe KBC dit ene inzageverzoek behandelde. |
| **Spoor B** | Het systeem: wat die behandeling zegt over de privacyprocessen van KBC. |
| **standaardoverzicht** | Het overzicht "Recht van inzage" dat KBC als brief met bijlage verstrekte (`B1-S05`). |
| **aanvullend verzoek** | Een vraag naar gegevens die volgens KBC niet in het standaardoverzicht zitten en afzonderlijk opvraagbaar zijn. |
| **zoeklast** | De inspanning om persoonsgegevens te lokaliseren, en de vraag wie die draagt: de verwerkingsverantwoordelijke of de betrokkene. |
| **access scope shift** | Term uit de validatienota voor het verschil tussen een eerdere levering van een gesprek (`B1-S13`) en latere niet-levering; een interpretatie, geen vaststelling. |
| **mypersonaldata@kbc.be** | De mailbox die KBC aanduidt als eerstelijnsdienst voor privacyrechten. |
| **dataprotection@kbc.be** | De mailbox die de privacyverklaring vermeldt als contact voor de Data Protection Officer. |
| **Doccle** | Externe documentenomgeving waarin KBC-documenten zichtbaar worden; de datum die Doccle toont, is niet noodzakelijk de documentdatum. |
| **GBA** | Gegevensbeschermingsautoriteit, de Belgische toezichthouder bij wie het klachtformulier `B1-S15` werd ingediend. |
| **COM-2026-00932** | Kenmerk in de bestandsnaam van dat klachtformulier; wat het kenmerk aanduidt, staat niet in het formulier zelf (afwezigheid: niet-in-bron). |
