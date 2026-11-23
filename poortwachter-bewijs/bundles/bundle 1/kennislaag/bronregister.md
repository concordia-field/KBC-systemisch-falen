---
id: B1-BRONREGISTER
type: bronregister
naam: Bronregister bundel 1
samenvatting: Elke bron in de map bewijsstukken van bundel 1 met vaste id, datums per datumsoort, rol, ingebedde berichten en wat er wel en niet werd nagekeken.
status: vastgesteld
maturiteit: ontwerp
goedgekeurd_door: niet goedgekeurd (geen menselijke review vastgelegd)
laatst_bijgewerkt: 2026-11-23
relaties:
  - document/behandelt: kruistabel.md
vocabularium: vocabularium.yaml
---

# Bronregister bundel 1

Bundel 1 wordt hier als een afgesloten geheel behandeld: kopieën van dezelfde stukken in andere bundels tellen niet mee. De waarden voor datumsoort, bronrol en afwezigheid komen uit [vocabularium.yaml](vocabularium.yaml); de termen staan in het [woordenboek](woordenboek.md).

**Zo lees je een datum.** Elke datum staat bij zijn datumsoort. Een versiedatum en een vastleggingsdatum die verschillen, spreken elkaar niet tegen. Tijden in KBC-headers staan in UTC; de Belgische tijd is telkens tussen haakjes afgeleid (+1 uur in de winter, +2 uur in de zomer).

**Status van dit register.** Wat in een veld staat, is waargenomen in de bron, tenzij er uitdrukkelijk *gerapporteerd* (alleen uit een dossierdocument) of *afgeleid* bij staat.

## Overzicht

| Id | Notatie in dossierdocumenten | Bron | Bestandsnaamdatum volgt | Rol | In dossierdocumenten verwerkt |
|---|---|---|---|---|---|
| B1-S01 | Stuk 1 · B1-S1 | E-mailketen inzageverzoek | ingebedde verzenddatum origineel verzoek | feitelijk-bewijs | ja |
| B1-S02 | Stuk 2 · B1-S2 | E-mailketen verduidelijking scope | verzenddatum topbericht | feitelijk-bewijs | ja |
| B1-S03 | Stuk 3 · B1-S3 | E-mailketen betwisting uitsluiting e-mail | verzenddatum topbericht | feitelijk-bewijs | ja |
| B1-S04 | Stuk 4 · B1-S4 | Schermafbeelding Doccle | beschikbaarstellingsdatum zoals Doccle toont | procedureel-bewijs | ja |
| B1-S05 | Stuk 5 · B1-S5 | KBC-brief "Recht van inzage" met bijlage | beschikbaarstellingsdatum (niet de documentdatum) | feitelijk-bewijs | ja |
| B1-S06 | Stuk 6 · B1-S6 | E-mailketen formele reactie 11 februari | verzenddatum topbericht | feitelijk-bewijs | ja |
| B1-S07 | Stuk 7 · B1-S7 | E-mailketen derde aanvraag en doorverwijzing | verzenddatum ingebed bericht betrokkene | feitelijk-bewijs | ja |
| B1-S08 | Stuk 8 · B1-S8 | KBC-mail aangetekende brief | verzenddatum topbericht | procedureel-bewijs | ja |
| B1-S09 | Stuk 9 · B1-S9 | KBC-ontvangstbevestiging | verzenddatum topbericht | procedureel-bewijs | ja |
| B1-JT01 | Bijlage JT-01 (vroeger "Stuk 10" en B1-S10) | Juridische toetssteen (twee versies) | niet-van-toepassing: geen datum in bestandsnaam | juridische-context | ja |
| B1-S11 | Stuk 11 · B1-S11 | KBC-privacyverklaring | niet-van-toepassing: geen datum in bestandsnaam | contextbron | ja |
| B1-S12 | Stuk 12 · B1-S12 | Thesis customer journeys | niet-van-toepassing: geen datum in bestandsnaam | contextbron | ja |
| B1-S13 | Stuk 13 · B1-S13 | KBC-mail met geleverde gespreksopname | verzenddatum | feitelijk-bewijs | ja |
| B1-S14 | `Bewijsstuk_14_…` | E-mailketen juli 2026, voorstel beluisteren | verzenddatum topbericht | feitelijk-bewijs | **nee** |
| B1-S15 | — | Klachtformulier GBA (`COM-2026-00932`) | niet-van-toepassing: geen datum in bestandsnaam | uitvoer-betrokkene | **nee** |
| B1-S10 | `bewijsstuk_10_2026-06-26_…` · "Bewijsstuk 10" in B1-S15 | KBC-mail eind juni 2026 | **onbekend** | feitelijk-bewijs | **nee** |
| B1-L1 – B1-L6 | map `legacy/` | Oorspronkelijke bronbestanden | — | oorspronkelijk-bestand | nee |

## Aandachtspunten die het register zichtbaar maakt

Deze punten worden hier vastgelegd, niet opgelost.

1. **"Bewijsstuk 10" is sinds 2026-11-23 eenduidig.** Het GBA-klachtformulier `B1-S15` noemt de KBC-mail van eind juni "Bewijsstuk 10"; die nummering ligt extern vast. Daarom draagt die mail in bundel 1 nu `B1-S10`. De juridische toetssteen, die in de dossierdocumenten "Stuk 10" heette, heet voortaan **Bijlage JT-01** (`B1-JT01`); haar herziene versie werd hernoemd naar `BIJLAGE JURIDISCHE TOETSSTEEN 01 - herzien.md`, en de dossierdocumenten vermelden "vroeger stuk 10". De pdf-versies van de dossierdocumenten dragen nog de oude nummering.
2. **Bronnen die geen dossierdocument verwerkt.** `B1-S14`, `B1-S15` en `B1-S10` dateren van na de laatste herziening van de dossierdocumenten (18 juni 2026) en komen in geen ervan voor. Ook de KBC-berichten van 20 februari en 7 mei 2026, die in de legacy-bestanden en als ingebed bericht voorkomen, hebben geen eigen feit in het dossieroverzicht.
3. **Versie van de privacyverklaring.** De versie in de bundel geldt vanaf 22 mei 2026, na de feiten van januari en februari 2026. Welke versie in januari 2026 gold, zit niet in de bundel (afwezigheid: niet-in-bundel).
4. **Datum in de ontvangstbevestiging.** De ingebedde Data Protection-reactie in `B1-S01` vermeldt ontvangst op "13/01/2025" en doorsturen op "14/01/2025"; het ingebedde verzoek zelf draagt 13 januari 2026. Dat is een afwijking binnen de bron.
5. **Legacy is geen hernoemde kopie.** Volgens de bundel-README bevat `legacy/` de oorspronkelijke bestandsnamen. Alleen `Je vraag over een telefoongesprek.eml` is byte-identiek aan een genormaliseerd stuk (`B1-S13`); de andere legacy-bestanden zijn andere exports of andere berichten.

---

## B1-S01 · E-mailketen formeel inzageverzoek

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_01_2026-01-13_formeel-verzoek-inzage-kopie-persoonsgegevens.eml` |
| Andere notaties | Stuk 1 (dossieroverzicht, juridische nota, register) · B1-S1 (deel-dossier) |
| Exportdatum | 2026-01-19 19:12 (+0100), topbericht van de betrokkene |
| Ingebedde berichten | Data Protection-reactie 2026-01-19 17:06 · origineel verzoek betrokkene 2026-01-13 23:20 |
| Bestandsnaamdatum volgt | verzenddatum van het ingebedde originele verzoek (13 januari) |
| Bijlagen | een pdf met een eerdere Gmail-conversatie, een afbeelding |
| Rol | feitelijk-bewijs: inhoud en omvang van het verzoek |
| Afwijking in bron | De ingebedde reactie noemt "13/01/2025" en "14/01/2025" (zie aandachtspunt 4). |
| Nagekeken | headers, berichtgrenzen en de datumpassage; de volledige tekst van het verzoek niet regel per regel |

## B1-S02 · E-mailketen verduidelijking scope en anonimisering

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_02_2026-01-23_verduidelijking-scope-communicatie-anonimisering.eml` |
| Andere notaties | Stuk 2 · B1-S2 |
| Verzenddatum topbericht | 2026-01-23 15:53 (+0100), betrokkene |
| Ingebedde berichten | KBC (mypersonaldata) 2026-01-23 13:32 |
| Bestandsnaamdatum volgt | verzenddatum topbericht |
| Rol | feitelijk-bewijs: eerste KBC-reactie met beperkingen en de verduidelijking door de betrokkene, in één keten |
| Nagekeken | headers en berichtgrenzen |

## B1-S03 · E-mailketen betwisting uitsluiting e-mail en interne nota's

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_03_2026-01-28_betwisting-uitsluiting-email-interne-notas.eml` |
| Andere notaties | Stuk 3 · B1-S3 |
| Verzenddatum topbericht | 2026-01-28 20:48 (+0100), betrokkene |
| Ingebedde berichten | KBC 2026-01-28 16:21 · KBC 2026-01-23 13:32 |
| Bestandsnaamdatum volgt | verzenddatum topbericht |
| Rol | feitelijk-bewijs; bevat ook de KBC-reactie van 23 januari, vóór de eerste levering |
| Nagekeken | headers en berichtgrenzen |

## B1-S04 · Schermafbeelding Doccle-archief

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_04_2026-01-30_doccle-kbc-document-recht-van-inzage.png` |
| Andere notaties | Stuk 4 · B1-S4 |
| Vastleggingsdatum | 2026-06-13 14:38 (klok in de schermafbeelding; bestand aangemaakt 2026-06-13 12:38 UTC) |
| Beschikbaarstellingsdatum | 30/01/2026, zoals Doccle die in de kolom "datum" toont |
| Inhoud | Doccle-archief, zoekopdracht "recht van inzage", één resultaat: partner KBC, naam "Recht van inzage", type "Informatie" |
| Bestandsnaamdatum volgt | de Doccle-datum |
| Rol | procedureel-bewijs: welk document op 13 juni in Doccle zichtbaar was |
| Open | Wat de Doccle-kolom "datum" precies registreert (ontvangst in Doccle, documentmetadata of iets anders): onbekend. Ze verschilt van de documentdatum in de brief (29 januari, zie `B1-S05`). |
| Nagekeken | volledig bekeken |

## B1-S05 · KBC-brief "Recht van inzage" met bijlage

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_05_2026-01-30_kbc-overzicht-recht-van-inzage.pdf` |
| Andere notaties | Stuk 5 · B1-S5 |
| Documentdatum | 29 januari 2026 (in de brief) |
| Beschikbaarstellingsdatum | 30 januari 2026 (Doccle, zie `B1-S04`) |
| Omvang | 21 pagina's: brief (p. 1–2) en bijlage met persoonsgegevens (p. 3–21) |
| Inhoud brief | Verwijst voor Bolero naar een aparte brief; noemt als afzonderlijk opvraagbaar via mypersonaldata: opgenomen gesprekken met medewerkers, chatgesprekken met Kate, gegevens als vertegenwoordiger bij Corporate Banking, vastgoedwaardering, gezondheidsgegevens, en een laatste punt dat alleen uit puntjes bestaat ("……….") |
| Inhoud bijlage | Rubrieken: persoonsgegevens, adres, relaties, contactgegevens, privacy-instellingen, fiscale kenmerken, beleggingsgegevens, bankproducten, kredietwaarborgen, kredietaanvragen, overeenkomsten, kredieten, aanvraag- en risicogegevens met situatiedatums, verzekeringen, schadedossiers, SEPA-domiciliëring, andere gegevens |
| Situatiedatums in bijlage | o.a. 15/08/2019, 10/07/2025, 23/08/2025, 17/10/2025, 20/10/2025, 06/11/2025, 08/01/2026 |
| Bestandsnaamdatum volgt | beschikbaarstellingsdatum, **niet** de documentdatum |
| Rol | feitelijk-bewijs: wat KBC als standaardoverzicht verstrekte |
| Nagekeken | volledig gelezen |

## B1-S06 · E-mailketen formele reactie 11 februari

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_06_2026-02-11_formele-reactie-op-weigering-redactie-pseudonimisering.eml` |
| Andere notaties | Stuk 6 · B1-S6 |
| Verzenddatum topbericht | 2026-02-11 17:47 (+0100), betrokkene |
| Ingebedde berichten | KBC 2026-02-11 10:37 · KBC 2026-01-23 13:32 |
| Bijlage | een eerder bewaarde `.eml` van 28 januari 2026 |
| Bestandsnaamdatum volgt | verzenddatum topbericht |
| Rol | feitelijk-bewijs: KBC-beperkingsstandpunt na herbekijken en de reactie van de betrokkene |
| Nagekeken | headers en berichtgrenzen |

## B1-S07 · E-mailketen derde aanvraag en doorverwijzing

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_07_2026-04-23_derde-aanvraag-doorverwijzing-dataprotection-mypersonaldata.eml` |
| Andere notaties | Stuk 7 · B1-S7 |
| Verzenddatum topbericht | 2026-04-24 05:57 UTC (afgeleid: 07:57 Belgische tijd), Data Protection |
| Ingebedde berichten | betrokkene 2026-04-23 17:50 |
| Bestandsnaamdatum volgt | verzenddatum van het ingebedde bericht van de betrokkene (23 april) |
| Bijlage | een identiteitsdocument (pdf) |
| Rol | feitelijk-bewijs: doorverwijzing van Data Protection naar mypersonaldata |
| Opmerking | 23 april (verzoek) en 24 april (doorverwijzing) zijn twee verzenddatums van twee berichten; het dossieroverzicht dateert het feit F8 op 24 april. |
| Nagekeken | headers en topbericht |

## B1-S08 · KBC-mail over aangetekende brief

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_08_2026-05-22_kbc-brief-aangetekend-verzonden.eml` |
| Andere notaties | Stuk 8 · B1-S8 |
| Verzenddatum topbericht | 2026-05-22 08:09 UTC (afgeleid: 10:09 Belgische tijd), mypersonaldata |
| Ingebedde berichten | betrokkene 2026-05-22 10:01 · betrokkene 2026-05-07 15:17 · KBC 2026-05-07 14:01 · 2026-04-30 07:56 · Data Protection 2026-04-24 07:58 · betrokkene 2026-04-23 17:50 |
| Bestandsnaamdatum volgt | verzenddatum topbericht |
| Rol | procedureel-bewijs: verzending per aangetekende post |
| Nagekeken | headers en berichtgrenzen |

## B1-S09 · KBC-ontvangstbevestiging vervolgmail

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_09_2026-06-04_kbc-ontvangstbevestiging-vervolgmail.eml` |
| Andere notaties | Stuk 9 · B1-S9 |
| Verzenddatum topbericht | 2026-06-04 14:05 UTC (afgeleid: 16:05 Belgische tijd), mypersonaldata |
| Ingebedde berichten | betrokkene 2026-06-04 07:29 · betrokkene 2026-05-28 11:18 · KBC 2026-05-22 10:09 · en de oudere keten tot 2026-01-13 |
| Bestandsnaamdatum volgt | verzenddatum topbericht |
| Rol | procedureel-bewijs |
| Nagekeken | headers en berichtgrenzen |

## B1-JT01 · Juridische toetssteen (twee versies)

| Veld | Waarde |
|---|---|
| Bestanden | `dossierdocumenten/BIJLAGE JURIDISCHE TOETSSTEEN 01 - herzien.md` (versie B; tot 2026-11-23 `bewijsstuk_10_gdpr-research-juridische-toetssteen.md`) · `dossierdocumenten/BIJLAGE JURIDISCHE TOETSSTEEN 01.md` (versie A) |
| Andere notaties | Bijlage JT-01 · tot 2026-11-23: Stuk 10 (dossieroverzicht, juridische nota, register, audit E-B1-10) en B1-S10 (deel-dossier) |
| Opmaakdatum | 13 juni 2026 (beide versies) |
| Herzieningsdatum | versie B: 15 juni 2026 · versie A: niet-in-bron |
| Verschil tussen de versies | Versie B voegt een paragraaf over de EDPB-richtsnoeren 01/2022 toe; vervangt het precedent "CJEU C-312/23 Addiko Bank" door "EDPB en CJEU C-307/22"; formuleert het machineleesbaar formaat voorzichtiger (gekoppeld aan artikel 20 in plaats van artikel 15). Waarom Addiko werd vervangen, staat nergens (afwezigheid: niet-in-bron). |
| Rol | juridische-context: geen zelfstandig feitelijk bewijs (zo vermeld in de bundel-README) |
| Oorspronkelijke bron | Beide versies verwijzen naar een onderzoeksnota van de betrokkene (`GDPR_research.txt`); die zit niet in de bundel (afwezigheid: niet-in-bundel). |
| Opmerking | Dit stuk is zelf een dossierdocument; het staat daarom in `dossierdocumenten/`, niet in `bewijsstukken/`. Waar versie A naar de onderzoeksnota `GDPR_research.txt` verwijst, noemt versie B (§2.5) haar eigen bestandsnaam; die zin werd bij de hernoeming alleen mechanisch aangepast. |
| Nagekeken | de twee versies tegen elkaar vergeleken (diff); de rechtspraak zelf niet |

## B1-S11 · KBC-privacyverklaring

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_11_kbc-bank-privacyverklaring-nl.pdf` |
| Andere notaties | Stuk 11 · B1-S11 |
| Versiedatum | 22-05-2026 (voettekst elke pagina) |
| Ingangsdatum | 22 mei 2026 ("Deze privacyverklaring gaat in op 22 mei 2026") |
| Vastleggingsdatum | 2026-06-14 (bestand aangemaakt 07:46 UTC; herkomst volgens bestandsmetadata: `multimediafiles.kbcgroup.eu/…/KBC_Bank_privacy_NL.pdf`) |
| Omvang | 32 pagina's |
| Passages die de dossierdocumenten gebruiken | §1.3 categorieën (o.a. afgeleide gegevens, commerciële profielen, contactmomenten, opnames) · §2.1.7 en §2.5.2 contactregistratie, opname van telefoongesprekken voor opleiding en bewijsvoering · §3.1 inzage: "zo volledig mogelijk overzicht", log-, historiek-, archief- of back-upbestanden aanvullend opvraagbaar · §3.10 aanspreekpunten · §3.11 DPO via dataprotection · §4.9 bewaartermijnen (vijf jaar voor registraties in kantoor, bij de agent of in KBC Live; tot tien jaar langer voor studies en modellen) |
| Rol | contextbron: wat KBC publiek over haar verwerking zegt, in de versie van 22 mei 2026 |
| Grens | De versie die gold tijdens de feiten van januari tot april 2026 zit niet in de bundel (afwezigheid: niet-in-bundel). |
| Nagekeken | volledig gelezen |

## B1-S12 · Thesis customer journeys

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_12_Thesis_YL_CustomerJournePredictorsForConsumerLoans_final_confid.pdf` |
| Andere notaties | Stuk 12 · B1-S12 |
| Documentdatum | academiejaar 2015–2016 (gerapporteerd in de bundel-README; niet in de bron nagekeken) |
| Rol | contextbron: historische verwerking bij KBC; systeemnamen en architectuur zijn historisch (zo vermeld in de bundel-README) |
| Nagekeken | niet-nagekeken: de pdf werd voor dit register niet geopend |

## B1-S13 · KBC-mail met geleverde gespreksopname

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_13_2025-11-19_kbc-levering-opgenomen-telefoongesprek.eml` |
| Andere notaties | Stuk 13 · B1-S13 |
| Verzenddatum | 2025-11-19 16:07 UTC (afgeleid: 17:07 Belgische tijd), mypersonaldata |
| Gebeurtenisdatum | 28/10/2025: het gesprek waarover de mail gaat |
| Bijlage | `ZIP_Call_28102025.zip` (versleuteld) met volgens de bundel-README `Call_28102025.m4a` |
| Bestandsnaamdatum volgt | verzenddatum |
| Relatie | bron/identiek-aan `legacy/Je vraag over een telefoongesprek.eml` (zelfde md5) |
| Rol | feitelijk-bewijs: eerdere levering van een opgenomen gesprek per e-mail |
| Nagekeken | headers, tekst en bijlagenaam; de inhoud van de zip niet |

## B1-S14 · E-mailketen juli 2026: voorstel tot beluisteren in kantoor

| Veld | Waarde |
|---|---|
| Bestand | `Bewijsstuk_14_2026-07-17_Formeel verzoek tot inzage en kopie persoonsgegevens.eml` |
| Andere notaties | geen; niet vermeld in de dossierdocumenten of de bundel-README |
| Verzenddatum topbericht | 2026-07-17 09:02 (+0200), betrokkene |
| Ingebedde berichten | KBC 2026-07-17 08:48 · betrokkene 2026-07-06 16:20 · KBC 2026-07-06 15:57 · KBC 2026-06-28 21:44 · en de oudere keten |
| Inhoud (waargenomen) | KBC verwijst naar artikel 15, lid 3 AVG en het arrest C-487/21, wijst op rechten van andere betrokkenen, en stelt voor dat de betrokkene de gesprekken in een KBC-kantoor komt beluisteren. De betrokkene antwoordt dat hij op dat voorstel ingaat. |
| Rol | feitelijk-bewijs |
| Status in bundel | nog-niet-uitgewerkt: geen feit, register-item of bevinding verwijst ernaar |
| Nagekeken | headers, berichtgrenzen en de twee bovenste berichten |

## B1-S15 · Klachtformulier GBA

| Veld | Waarde |
|---|---|
| Bestand | `COM-2026-00932 - Dossier ELD.pdf` |
| Andere notaties | geen |
| Documentdatum | niet-in-bron: het formulier draagt geen datum |
| Bestandssysteemdatum | 2026-07-17 (wijzigingsdatum van het bestand; zwak als datumsoort, daarom niet als indieningsdatum gebruikt) |
| Inhoud | Formulier "Klacht indienen" van de Gegevensbeschermingsautoriteit, ingediend in eigen naam, tegen KBC Bank NV; periode van de feiten "tussen november 2025 en nu"; bijlagenlijst met negen bestanden: de bewijsstukken 01, 02, 03, 05, 06, 07, 08 en 09, plus `bewijsstuk_10_2026-06-26_…eml`. Bewijsstuk 04 (de Doccle-schermafbeelding) staat niet in de lijst. |
| Rol | uitvoer-betrokkene: een extern ingediend stuk, geen bewijs van een KBC-handeling |
| Relatie | verwijzing/genummerd-als: "Bewijsstuk 10" in dit formulier = `B1-S10` |
| Status in bundel | nog-niet-uitgewerkt |
| Nagekeken | volledig gelezen |

## B1-S10 · KBC-mail eind juni 2026

| Veld | Waarde |
|---|---|
| Bestand | `bewijsstuk_10_2026-06-26_Formeel verzoek tot inzage en kopie persoonsgegevens.eml` |
| Andere notaties | "Bewijsstuk 10" in `B1-S15` |
| Verzenddatum topbericht | 2026-06-28 19:43 UTC (afgeleid: 21:43 Belgische tijd), mypersonaldata; in `B1-S14` als ingebed bericht vermeld als 28 juni 21:44 |
| Ingebedde berichten | betrokkene 2026-05-28 11:18 · KBC 2026-05-22 10:09 · en de oudere keten tot 2026-04-23 |
| Bestandsnaamdatum volgt | onbekend: in het bestand staat geen bericht van 26 juni 2026 |
| Inhoud (waargenomen) | KBC verwijst naar eerdere communicatie en meldt dat het geen bijkomende inhoudelijke toelichting meer geeft voor berichten met hetzelfde voorwerp. |
| Rol | feitelijk-bewijs |
| Status in bundel | nog-niet-uitgewerkt |
| Nagekeken | headers, berichtgrenzen en het topbericht |

## B1-L1 – B1-L6 · Map `legacy/`

| Id | Bestand | Verzenddatum topbericht | Afzender topbericht | Relatie |
|---|---|---|---|---|
| B1-L1 | `Formeel verzoek tot inzage en kopie persoonsgegevens (12).eml` | 2026-01-13 23:20 (+0100) | betrokkene | het originele verzoek als los bericht; ook ingebed in `B1-S01` |
| B1-L2 | `Formeel verzoek tot inzage en kopie persoonsgegevens (18).eml` | 2026-01-19 16:06 UTC | Data Protection | ook ingebed in `B1-S01`; bevat de datumafwijking "13/01/2025" |
| B1-L3 | `Formeel verzoek tot inzage en kopie persoonsgegevens (14).eml` | 2026-02-20 13:32 UTC | mypersonaldata | KBC verwijst naar eerdere communicatie; dit bericht van 20 februari heeft geen eigen feit in de dossierdocumenten |
| B1-L4 | `FW_ Formeel verzoek tot inzage en kopie persoonsgegevens (5).eml` | 2026-05-07 12:00 UTC | mypersonaldata | KBC-reactie van 7 mei; ook ingebed in `B1-S08` |
| B1-L5 | `FW_ Formeel verzoek tot inzage en kopie persoonsgegevens.eml` | 2026-05-28 11:18 (+0200) | betrokkene | bijlagen o.a. een pdf "Recht van inzage kbc" en een schermafbeelding; ook ingebed in `B1-S09` |
| B1-L6 | `Je vraag over een telefoongesprek.eml` | 2025-11-19 16:07 UTC | mypersonaldata | bron/identiek-aan `B1-S13` |

Rol van alle legacy-bestanden: oorspronkelijk-bestand. Behalve B1-L6 zijn ze niet byte-identiek aan een genormaliseerd stuk; welk legacy-bestand bij welk genormaliseerd stuk hoort, is daarom niet zeker (betrouwbaarheid: waarschijnlijk, op basis van datums en ingebedde berichten).

---

## Ontvangstbewijs van deze intake

| Wat | Hoe | Resultaat |
|---|---|---|
| E-mails (`.eml`) | Headers (Date, Subject, From, bijlagenamen) en tekst uitgelezen; berichtgrenzen in de keten opgelijst | Datums per bericht vastgesteld; de berichten zelf niet volledig regel per regel gelezen, behalve waar vermeld |
| `B1-S05`, `B1-S11`, `B1-S15` | Volledig gelezen als pdf | Inhoud en datums vastgesteld |
| `B1-S04` | Afbeelding bekeken | Doccle-datum en vastleggingsmoment vastgesteld |
| `B1-S12` | Niet geopend | Alleen gerapporteerde gegevens |
| `B1-JT01` | Twee versies vergeleken | Verschillen vastgesteld; rechtspraak niet getoetst |
| Kopieën in andere bundels | Bewust niet bekeken | Bundel 1 als afgesloten geheel |
| Wat kan de AI verkeerd begrepen hebben? | — | De koppeling legacy ↔ genormaliseerd stuk; de betekenis van de Doccle-datum; of `B1-S10` dezelfde rol heeft als de stukken 1–9. Dit vraagt een menselijke controle. |
