---
id: RAPPORTENBOOM
type: index
naam: Rapportenboom
samenvatting: Van elk rapport dat we willen opstellen naar de thema's, de bevindingen, de feiten in de bundels en de bronnen eronder; wat nog niet uitgewerkt is, staat als placeholder met een vast id.
status: interpretatief
maturiteit: kiem
goedgekeurd_door: niet goedgekeurd (geen menselijke review vastgelegd)
laatst_bijgewerkt: 2026-11-23
vocabularium: poortwachter-bewijs/bundles/bundle 1/kennislaag/vocabularium.yaml
---

# Rapportenboom

Deze boom vertrekt bovenaan, bij de rapporten die we willen opstellen, en daalt af tot de bronnen. Zo is per rapport zichtbaar waarop het steunt, en per bundel welke rapporten erop wachten. De koppelingen zijn een interpretatie van de agent; ze moeten bij het herwerken van elke bundel worden nagekeken.

Wat nog geen eigen knoop heeft, staat hier als **placeholder**: een vast id met de afwezigheidswaarde `nog-niet-uitgewerkt`. Wie een bundel herwerkt zoals [bundel 1](poortwachter-bewijs/bundles/bundle%201/kennislaag/README.md), maakt van die id's echte knopen en zet hier de link. Er komen bewust geen lege bestanden: één placeholderrij is genoeg tot er inhoud is.

## Niveaus en id's

| Niveau | Wat | Id | Waar het staat |
|---|---|---|---|
| 0 | Uitgang: een rapport voor één publiek | `FSMA`, `NBB`, `FODE`, `OMB`, `GBA`, `MED`, `JUR` | [meldingen](meldingen/README.md), [GBA-klacht](poortwachter-bewijs/perspectieven/3-klacht-gba.md), [media](media/README.md), [juridisch](juridisch/README.md) |
| 1 | Thema binnen een uitgang | `NBB-07`, `MED-01`, `JUR-02` … | in het rapport zelf |
| 2 | Bevinding | `B1.2` … `B7.3` (audit), `F-01` … `F-20` (persoonlijke casus) | [audit](poortwachter-bewijs/perspectieven/1-audit.md), [persoonlijk register](persoonlijk/ontward/register.md) |
| 3 | Feit in een bundel | `B1-F00` … `B1-F10` (uitgewerkt); `B2-F01` … `B7-F09` (placeholder) | [kruistabel bundel 1](poortwachter-bewijs/bundles/bundle%201/kennislaag/kruistabel.md); voor bundels 2–7: het dossieroverzicht van de bundel |
| 4 | Bron | `B1-S01` … (uitgewerkt); `B2-S01` … (placeholder); `BRON-01` … (persoonlijk) | [bronregister bundel 1](poortwachter-bewijs/bundles/bundle%201/kennislaag/bronregister.md), [persoonlijke bronnen](persoonlijk/ontward/bronnen.md) |

**Let op drie gelijkende notaties.** `B1` is bundel 1. `B1.2` is bevinding 2 van de audit over bundel 1. `B1-F02` is feit F2 uit het dossieroverzicht van bundel 1. De placeholders `Bn-Fxx` volgen de F-nummering van het dossieroverzicht van bundel n, met twee cijfers (`F4A` wordt `B7-F04A`).

---

## Deel 1 · Van rapport naar bron

Per uitgang: thema → bevinding → feit in een bundel → bron. "Geen bundel" betekent dat het thema niet uit de privacybundels komt maar uit de persoonlijke casus, waarvan de meeste bronnen nog niet in de repository zitten.

### Meldingen

#### FSMA ([fsma.md](meldingen/fsma.md))

- **FSMA-01 tot FSMA-04 · Bolero**
  - bevinding: F-19
  - feit: geen bundel
  - bron: BRON-09 (verwezen, niet in de map) · `nog-niet-uitgewerkt`
  - publiek signaal: Bolero en keuzedividenden, De Tijd ca. 2026-06 ([register](publieke-signalen/media.md#4-bolero))
- **FSMA-05 · Druk door de bankdirecteur**
  - bevinding: F-04, F-07
  - feit: B5-F01 tot B5-F04 (het gesprek met clusterdirecteur A); B6-F11, B6-F12 (de Teams-meeting en Secure4U)
  - bron: BRON-01 (transcriptie), de audio in bundel 5 (`B5-S01`, placeholder)
  - open: de datum van het gesprek, zie [knoop 1](#1-de-datum-van-het-gesprek-met-de-directeur)
- **FSMA-06 · Klachtbehandeling**
  - bevinding: F-16, B6.2
  - feit: B6-F13 tot B6-F15 (security- en privacymelding via klachtenmanagement); B2-F07 (vraag naar de DPO)
  - bron: `B6-S…`, `B2-S…` (placeholders); BRON-14, BRON-16 (verwezen)
- **FSMA-07 · Structurele tekortkomingen**
  - bevinding: ASM-004 (open)
  - feit: geen bundel
  - bron: [publieke signalen](publieke-signalen/media.md)

#### NBB ([nbb.md](meldingen/nbb.md))

- **NBB-01 · Versnippering van kredietdossiers**
  - bevinding: F-10
  - feit: B7-F04A (herhaalde vraag naar private banking); de assetmail van juli 2025 (`B7-S11`, placeholder)
- **NBB-02 · Coördinatie tussen diensten**
  - bevinding: B1.5, F-02
  - feit: B6-F02, B6-F08, B6-F09 (routering tussen mailboxen); B5-F03 (intern overleg met CIO A en commercieel directeur)
- **NBB-03 · Geen dossierverantwoordelijke**
  - bevinding: F-10
  - feit: B7-F04A
  - bron: BRON-07 (verwezen) · `nog-niet-uitgewerkt`
- **NBB-04 · Governance**
  - bevinding: B6.1, B6.2, B2.3
  - feit: B6-F01 tot B6-F10; B2-F07
- **NBB-05 · Interne controle**
  - bevinding: B4.1 tot B4.3, B3.2
  - feit: B4-F01 tot B4-F04, B4-F06, B4-F08; B3-F03
- **NBB-06 · Tegenstrijdige verwerking in systemen**
  - bevinding: B7.1, F-17
  - feit: B7-F04 (classificatie "hoofdbankier")
  - bron: B1-S05 (het overzicht "Recht van inzage")
- **NBB-07 · De-risking en beëindiging**
  - bevinding: F-13, ASM-005 (open)
  - feit: geen bundel
  - bron: BRON-12, BRON-19 (verwezen) · `nog-niet-uitgewerkt`
- **NBB-08 · Operationele tekortkomingen (overkoepelend)**
  - steunt op NBB-01 tot NBB-07 en NBB-09 tot NBB-12 samen
- **NBB-09 · Operationele risico's**
  - bevinding: B5.1, B5.2
  - feit: B5-F02, B5-F04 (opnamebandje, herbeluisteren); B6-F11 (mogelijke externe toegang tot een Teams-vergadering)
- **NBB-10 · Beleid tegenover praktijk**
  - bevinding: B1.3, B2.2
  - feit: B2-F09, B3-F08, B4-F06, B4-F07, B7-F09 (telkens de privacyverklaring als norm)
  - bron: B1-S11; de publieke privacyverklaring in [publieke-bronnen](poortwachter-bewijs/bronnen/publieke-bronnen/)
  - open: welke versie gold op welk moment, zie [knoop 2](#2-kopieën-en-versies-tussen-de-bundels)
- **NBB-11 · Klachtenbeheer**
  - bevinding: F-16
  - feit: B6-F13 tot B6-F15
- **NBB-12 · Digitale dienstverlening**
  - bevinding: F-18, F-19
  - feit: geen bundel · `nog-niet-uitgewerkt`

#### FOD Economie ([fod-economie.md](meldingen/fod-economie.md))

- **FODE-01 tot FODE-04**
  - bevinding: geen; FODE-04 raakt F-04
  - feit: geen bundel
  - bron: rekeninguittreksels, beëindigingsbrief, tarievenlijst · `nog-niet-uitgewerkt`

#### Ombudsfin ([ombudsfin.md](meldingen/ombudsfin.md))

- **OMB-01 tot OMB-06 · Krediet, structuur, opzegging, Bolero**
  - bevinding: F-01 tot F-04, F-09, F-12, F-13, F-19
  - feit: geen bundel
  - bron: BRON-01; BRON-03 tot BRON-12 (verwezen) · `nog-niet-uitgewerkt`
- **OMB-07 · Dienstverlening**
  - bevinding: F-10, F-14, F-18
  - feit: B7-F04A
- **OMB-08 · Kosten**
  - feit: geen bundel · `nog-niet-uitgewerkt`

### GBA

Bij de GBA ligt al iets: volgens de [output-index van bundel 1](poortwachter-bewijs/bundles/bundle%201/output/index.md) werden twee klachten ingediend (`B1-O1`, `B1-O2`). Het concept [3-klacht-gba.md](poortwachter-bewijs/perspectieven/3-klacht-gba.md) zou daarom een aanvulling worden, geen nieuwe klacht; zie [knoop 3](#3-wat-al-bij-de-gba-ligt).

- **Feit 1 · Standaardoverzicht** → B1.1, B1.3, B1.4 → B1-F00 tot B1-F10 (uitgewerkt)
- **Feit 2 · Categorieën geweigerd** → B1.2 → bundel 1; B3-F04, B3-F10
- **Feit 3 · Zoeklast** → B3.1, B5.3 → B3-F02, B3-F05, B3-F06; B1-S13 (geleverde opname)
- **Feit 4 · Rectificatie** → B2.1, B2.4 → B2-F02, B2-F05, B2-F06, B2-F08
- **Feit 5 · Opnamemelding** → B5.1, B5.2 → B5-F02, B5-F04; open: [knoop 1](#1-de-datum-van-het-gesprek-met-de-directeur)
- **Feit 6 · Interne toegang** → B4.2, B4.3 → B4-F01 tot B4-F04
- **Feit 7 · Classificatie** → B7.1, B7.2 → B7-F03, B7-F04, B7-F07, B7-F09
- **Feit 8 · DPO** → B6.2 → B6-F04 tot B6-F09

### Media ([media](media/README.md))

- **MED-01 · Welk bewijs de klant te zien krijgt** → B1.1 tot B1.3, B3.1, B5.1 tot B5.3 → bundels 1, 3, 5
- **MED-02 · Fouten en een classificatie zonder bron** → B2.1, B2.4, B7.1 → bundels 2, 7
- **MED-03 · Andere klanten** → ASM-004 → [publieke signalen](publieke-signalen/media.md) · `nog-niet-uitgewerkt`
- **MED-04 · Het krediet** → F-01 tot F-13 → geen bundel · `nog-niet-uitgewerkt`

### Juridisch ([juridisch](juridisch/README.md))

- **JUR-01 · AVG** → B1 tot B7 → alle zeven bundels
- **JUR-02, JUR-03 · Krediet en bouwgrond** → F-01 tot F-09, F-03 → geen bundel
- **JUR-04 · Beëindiging** → F-12, F-13 → geen bundel
- **JUR-05 · Bolero** → F-19 → geen bundel
- **JUR-06 · Bewijsmaatregelen** → V1 tot V8 → alle bundels; per bewijsvraag de open bewijsvragen in §7 van elk dossieroverzicht

---

## Deel 2 · Van bundel naar rapport

Per bundel: de kernvraag, de feiten als placeholder-id's en welke uitgangen erop steunen. De onderwerpen zijn kort samengevat uit het dossieroverzicht van de bundel (epistemische basis: *gerapporteerd*, niet in de bronnen nagekeken).

| Bundel | Kennislaag | Kernvraag (kort) | Audit | Voedt |
|---|---|---|---|---|
| [1 · Inzage](poortwachter-bewijs/bundles/bundle%201/README.md) | [ontwerp](poortwachter-bewijs/bundles/bundle%201/kennislaag/README.md) | Verstrekte KBC wat gevraagd werd, en verantwoordde ze wat ze wegliet? | B1.1–B1.6 | GBA, NBB-02, NBB-10, MED-01, JUR-01 |
| [2 · Rectificatie](poortwachter-bewijs/bundles/bundle%202/README.md) | `nog-niet-uitgewerkt` | Werd rectificatie gefaciliteerd, uitgevoerd en verantwoord? | B2.1–B2.4 | GBA, NBB-04, NBB-10, MED-02, JUR-01 |
| [3 · Zoeklast](poortwachter-bewijs/bundles/bundle%203/README.md) | `nog-niet-uitgewerkt` | Zette KBC haar eigen contacthistoriek in, of verschoof ze het zoeken naar de klant? | B3.1–B3.3 | GBA, NBB-05, NBB-10, MED-01, JUR-01 |
| [4 · Telefonische toegang](poortwachter-bewijs/bundles/bundle%204/README.md) | `nog-niet-uitgewerkt` | Kan KBC aantonen wie op 26 en 28 februari welke gegevens raadpleegde, waarom en onder welke logging? | B4.1–B4.3 | GBA, NBB-05, NBB-10, JUR-01 |
| [5 · Gespreksopnames](poortwachter-bewijs/bundles/bundle%205/README.md) | `nog-niet-uitgewerkt` | Werd de klant correct geïnformeerd over opname, herbeluistering en doel? | B5.1–B5.3 | GBA, FSMA-05, NBB-02, NBB-09, MED-01, JUR-01 |
| [6 · Governance en DPO](poortwachter-bewijs/bundles/bundle%206/README.md) | `nog-niet-uitgewerkt` | Hoe ontvangt, routeert en beoordeelt KBC privacy- en securitysignalen? | B6.1–B6.2 | GBA, FSMA-05, FSMA-06, NBB-02, NBB-04, NBB-09, NBB-11, JUR-01 |
| [7 · Profilering](poortwachter-bewijs/bundles/bundle%207/README.md) | `nog-niet-uitgewerkt` | Waar komt "hoofdbankier" vandaan, en welke profielen bleven onzichtbaar? | B7.1–B7.3 | GBA, NBB-01, NBB-03, NBB-06, NBB-10, OMB-07, MED-02, JUR-01 |

### Feiten per bundel (placeholders)

Elke rij wordt een knoop zodra de bundel een kennislaag krijgt. Tot dan verwijst het id naar het feit met hetzelfde nummer in het dossieroverzicht.

**Bundel 2 · Rectificatie** (`B2-KENNISLAAG`: `nog-niet-uitgewerkt`)

| Id | Onderwerp | Voedt |
|---|---|---|
| B2-F01 | 2026-01-30 · eerste aanlevering van persoonsgegevens | GBA feit 4 |
| B2-F02 | 2026-02-03 · melding van onjuiste gegevens | GBA feit 4, MED-02 |
| B2-F03 | 2026-02-11 · KBC verwijst naar kantoor of app | B2.1 |
| B2-F04 | 2026-02-13 · eigen logging van de betrokkene | B3.1 |
| B2-F05 | 2026-02-26 · formeel rectificatieverzoek | GBA feit 4 |
| B2-F06 | 2026-03-04 · KBC vraagt opnieuw welke gegevens fout zijn | GBA feit 4, MED-02 |
| B2-F07 | 2026-02-11 en 2026-03-11 · vraag naar DPO en aanspreekpunt | FSMA-06, NBB-04, GBA feit 8 |
| B2-F08 | 2026-05-28 · gelijkaardige gegevensset, fouten blijven | GBA feit 4, MED-02 |
| B2-F09 | privacyverklaring als publieke procesnorm | NBB-10 |

**Bundel 3 · Zoeklast** (`B3-KENNISLAAG`: `nog-niet-uitgewerkt`)

| Id | Onderwerp | Voedt |
|---|---|---|
| B3-F01 | 2026-01-13 · breed inzageverzoek | GBA feit 1 |
| B3-F02 | 2026-01-23 · KBC vraagt de klant gesprekken te specificeren | GBA feit 3, MED-01 |
| B3-F03 | 2026-01-23 · algemene toelichting over functiegebonden toegang | NBB-05 |
| B3-F04 | 2026-02-11 · interne categorieën geweigerd of beperkt | GBA feit 2 |
| B3-F05 | 2026-02-11 · eigen logging is slechts ondersteunend | GBA feit 3 |
| B3-F06 | 2026-02-13 · eigen contactlog bezorgd | GBA feit 3 |
| B3-F07 | thesis: historische ContactDB-capaciteit (vertrouwelijk) | B3.3, ASM-003 |
| B3-F08 | privacyverklaring: contactmomenten en opnames | NBB-10 |
| B3-F09 | 2026-03-03 · KBC kent eerdere Live- en kantoorcontacten | NBB-05 |
| B3-F10 | 2026-05-07 · KBC handhaaft de beperking | GBA feit 2 |
| B3-F11 | contradictiematrix | analyse, geen feit |

**Bundel 4 · Telefonische toegang** (`B4-KENNISLAAG`: `nog-niet-uitgewerkt`)

| Id | Onderwerp | Voedt |
|---|---|---|
| B4-F01 | 2026-02-26 · gesprek over de concrete financiële situatie | NBB-05, GBA feit 6 |
| B4-F02 | 2026-02-28 · opvolggesprek waarin dossiercontext lijkt te worden gelezen | NBB-05, GBA feit 6 |
| B4-F03 | 2026-03-03 · identificatie via mobiel nummer bevestigd | NBB-05 |
| B4-F04 | 2026-03-04 · reactie over eerdere contacten en gespreksduur | NBB-05, GBA feit 6 |
| B4-F05 | datum onbekend · contact over kindrekening of volmacht | `nog-niet-uitgewerkt`: datum en bron ontbreken in de bundel |
| B4-F06 | privacyverklaring: alleen gemachtigden, enkel indien relevant | NBB-10 |
| B4-F07 | privacyverklaring: contactmomenten, verslagen, opnames | NBB-10 |
| B4-F08 | KBC-communicatie over rol- en taakgebonden toegang | NBB-05 |

**Bundel 5 · Gespreksopnames** (`B5-KENNISLAAG`: `nog-niet-uitgewerkt`)

| Id | Onderwerp | Voedt |
|---|---|---|
| B5-F01 | 2026-01-23 · telefoongesprek met clusterdirecteur A | FSMA-05 |
| B5-F02 | 2026-01-23 · geen opnamebandje bij aanvang | NBB-09, GBA feit 5 |
| B5-F03 | 2026-01-23 · verwijzing naar intern overleg met CIO A en commercieel directeur | NBB-02, FSMA-05 |
| B5-F04 | 2026-01-23 · verwijzing naar herbeluisteren | NBB-09, GBA feit 5 |
| B5-F05 | gebruikelijke opname-informatie bij andere gesprekken | B5.3 |
| B5-F06 | mogelijk intern gebruik van gespreksinhoud | open vraag, geen feit |
| B5-M02, B5-R02 | latere vraag aan KBC over opname en doelbinding, en antwoord | `nog-niet-uitgewerkt`: in de bundel als "[datum in te vullen]" |

**Bundel 6 · Governance en DPO** (`B6-KENNISLAAG`: `nog-niet-uitgewerkt`)

| Id | Onderwerp | Voedt |
|---|---|---|
| B6-F01 | 2026-01-13 · inzageverzoek aan dataprotection | NBB-04 |
| B6-F02 | 2026-01-19 · doorverwijzing naar mypersonaldata | NBB-02, NBB-04 |
| B6-F03 | jan.–feb. 2026 · operationele mypersonaldata-keten | NBB-04 |
| B6-F04 | 2026-03-10 · vraag naar DPO-contactgegevens | GBA feit 8 |
| B6-F05 | 2026-03-11 · verwijzing naar de privacyverklaring | GBA feit 8 |
| B6-F06 | 2026-03-11 · vraag naar rol en onafhankelijkheid | GBA feit 8 |
| B6-F07 | 2026-03-17 · herinnering, uitnodiging aan de DPO | GBA feit 8 |
| B6-F08 | 2026-03-27 · rolverduidelijking mailboxen | NBB-02, NBB-04 |
| B6-F09 | 2026-04-24 · herhaalde doorverwijzing | NBB-02, NBB-04 |
| B6-F10 | 2026-05-28 · laatste mypersonaldata-reactie | NBB-04 |
| B6-F11 | 2026-01-23 · mogelijke externe toegang tot een Teams-vergadering | NBB-09, FSMA-05; zelfde gebeurtenis als F-06 (persoonlijk)? |
| B6-F12 | 2026-01-23 · voorgestelde melding aan Secure4U | FSMA-05 |
| B6-F13 | 2026-02-26 · formele security- en privacymelding | FSMA-06, NBB-11 |
| B6-F14 | 2026-03-03 · routering naar klachtenmanagement | FSMA-06, NBB-11 |
| B6-F15 | 2026-03-04 · geen aantoonbare afzonderlijke incidenttriage | FSMA-06, NBB-11 |

**Bundel 7 · Profilering** (`B7-KENNISLAAG`: `nog-niet-uitgewerkt`)

| Id | Onderwerp | Voedt |
|---|---|---|
| B7-F01 | 2026-01-13 · vraag naar profilering en geautomatiseerde besluitvorming | GBA feit 7 |
| B7-F02 | 2026-01-23 · algemene verwijzing naar automatische besluitvorming | GBA feit 7 |
| B7-F03 | 2026-01-30 · standaardoverzicht met beperkte afgeleide gegevens | GBA feit 7 |
| B7-F04 | 2025-10-17 en 2025-10-20 · classificatie "hoofdbankier" | NBB-06, GBA feit 7, MED-02 |
| B7-F04A | herhaalde vraag naar private banking (17 mei, 2 december; jaar te bevestigen) | NBB-01, NBB-03, OMB-07 |
| B7-F05 | 2026-02-28 · menselijke raadpleging van dossierinformatie | NBB-05 |
| B7-F06 | 2026-03-03 en 2026-03-04 · persoonsgebonden context bevestigd, geen profielinformatie | GBA feit 7 |
| B7-F07 | 2026-03-04 · "alle beschikbare informatie bezorgd" | GBA feit 7 |
| B7-F08 | historische capaciteit voor voorspellende analyse (thesis) | ASM-003 |
| B7-F09 | privacyverklaring van 2026-05-22: profiel- en afleidingscategorieën | NBB-10, GBA feit 7 |

---

## Deel 3 · Knopen die de boom zichtbaar maakt

Deze punten worden hier vastgelegd, niet opgelost.

### 1. De datum van het gesprek met de directeur

Vier bronnen spreken elkaar tegen of vullen elkaar aan:

- de transcriptie (BRON-01) draagt in haar bestandsnaam 12 februari 2026;
- in het gesprek zegt de betrokkene "we zijn nu bijna eind januari" (ASM-002 in de persoonlijke casus);
- bundel 5 dateert het gesprek met clusterdirecteur A op 23 januari 2026, met dezelfde inhoud (opnamebandje, CIO A, commercieel directeur), en de audio in die bundel duurt 26:05, tegenover een laatste tijdcode van 25:43 in de transcriptie;
- bundel 6 plaatst de Teams-meeting met een derde en het Secure4U-punt op 23 januari 2026 (B6-F11, B6-F12), wat overeenkomt met de geannuleerde meeting van 8u30 in de transcriptie (F-06).

De audit ([1-audit.md](poortwachter-bewijs/perspectieven/1-audit.md#8-vóór-gebruik-te-verifiëren), §8 punt 2) verplaatste het gesprek naar 12 februari. Alles wijst eerder op 23 januari. **Dit raakt FSMA-05, NBB-09, GBA feit 5 en de persoonlijke chronologie**, en moet beslecht zijn voordat een van die uitgangen vertrekt. Toets: de audio naast de transcriptie leggen.

### 2. Kopieën en versies tussen de bundels

Bundel 7 bevat naast eigen stukken ook kopieën uit bundels 1, 3 en 4. De thesis zit in bundels 1, 3 en 7; de privacyverklaring in bundels 1, 2, 3, 4 en 7, met bestandsdatums van 30 januari 2026 en een versie van 22 mei 2026. Volgens de regel van bundel 1 telt een kopie niet als bevestiging. Wanneer de bundels herwerkt worden, is één bronregister over alle bundels nodig, zodat hetzelfde stuk overal hetzelfde id draagt, en vastligt welke versie van de privacyverklaring op welk moment gold.

### 3. Wat al bij de GBA ligt

Twee klachten zijn volgens de betrokkene ingediend (`B1-O1` via het formulier, `B1-O2` via een advocaat), met onbekende onderlinge verhouding. Het concept in [3-klacht-gba.md](poortwachter-bewijs/perspectieven/3-klacht-gba.md) dekt alle zeven bundels. Of het een aanvulling wordt op wat al ligt, en onder welk kenmerk, is een beslissing van de betrokkene en de advocaat.

### 4. Gaten in de bundels zelf

- B4-F05 en B4-M03 (kindrekening of volmacht) hebben geen datum en geen bron.
- B5-M02 en B5-R02 (latere vraag over opname en doelbinding) staan als "[datum in te vullen]".
- B7-F04A noemt 17 mei en 2 december zonder jaar.

### 5. Thema's zonder bundel

De Ombudsfin- en FOD Economie-rapporten, NBB-07, NBB-12 en de Bolero-thema's van de FSMA steunen niet op de privacybundels, maar op de persoonlijke casus. Daarvan zitten de meeste bronnen (BRON-03 tot BRON-20) nog niet in de repository. Een tak "kredietdossier" naast de zeven privacybundels zou die bronnen een plaats geven.

### 6. Eén vocabularium

Het vocabularium staat nu in bundel 1. Zodra een tweede bundel een kennislaag krijgt, hoort het op één gedeelde plaats, zodat er geen twee lijsten van dezelfde waarden ontstaan.
