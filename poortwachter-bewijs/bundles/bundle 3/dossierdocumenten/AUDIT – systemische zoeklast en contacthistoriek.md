# AUDIT – Systemische zoeklast en contacthistoriek

**Bundel:** Bundel 3 – Contacthistoriek en zoeklast  
**Auditfocus:** de systeem- en procesmatige dimensie van de behandeling van het AVG-inzageverzoek, met bijzondere aandacht voor zoeklast, contacthistoriek, transparantie en controleerbaarheid.  
**Relatie tot andere documenten:** dit auditdocument staat naast het dossieroverzicht en het OSCARC-vaststellingsdocument. Het focust op systeemwerking, proceskwaliteit en beheersrisico, niet op herhaling van de volledige feitenreconstructie.

---

# 1. Executive Summary

## 1.1 Audit Background & Objectives

Deze audit vertrekt vanuit de vaststelling dat de betrokkene KBC inzage vroeg in contacthistoriek, telefoongesprekken, interactiedata, logs en dossierhistoriek, terwijl KBC hem vroeg zelf gesprekken en contactmomenten te specificeren. De auditvraag is of die behandeling systemisch voldoende controleerbaar, transparant en proportioneel was.

De doelstelling is niet om elke mail opnieuw te kwalificeren, maar om te beoordelen of de combinatie van processtappen, communicatie, privacyverklaring, historische ContactDB-context en later zichtbare contactkennis wijst op een robuust of juist fragiel rechtenfaciliteringsproces.

## 1.2 Scope of the Audit

De audit omvat:

* de behandeling van het AVG-inzageverzoek van 13 januari 2026;
* de daaropvolgende opzoeking van telefoongesprekken en contactmomenten;
* de betrokken communicatiekanalen `dataprotection`, `mypersonaldata`, klachtenmanagement en relevante security-/contactketens;
* de historische ContactDB-context uit de thesis;
* de publieke privacyverklaring van KBC;
* de mate waarin KBC eigen contacthistoriekbronnen, functies en gegevenscategorieën controleerbaar toelichtte.

De audit omvat niet:

* technische penetratietesten of systeemtoegang;
* een volledige broncode- of databasereview;
* een afzonderlijke beoordeling van telefonische authenticatie als zodanig;
* een volledige governance-audit van Bundel 6, behalve waar die relevant is voor procesarchitectuur.

## 1.3 Key OSCARC Findings

### Objectieve vaststelling

KBC vroeg de betrokkene zelf om telefoongesprekken te specificeren, beperkte inzage in relevante interne categorieën en gaf later wel kennis van eerdere contactmomenten en identificatieroute. De thesis wijst op historische ContactDB-capaciteit; de privacyverklaring erkent publiek gecommuniceerde verwerkingscategorieën.

### Standaard

Van een verwerkingsverantwoordelijke mag worden verwacht dat een inzageverzoek beknopt, transparant, begrijpelijk en controleerbaar wordt behandeld, met een functionele uitleg van de relevante gegevenscategorieën, zonder dat medewerkerprivacy of interne vertrouwelijkheid per definitie volledig opgeeft.

### Belangrijkste afwijking

De belangrijkste afwijking is dat KBC de reconstructielast in belangrijke mate bij de betrokkene legt zonder controleerbaar overzicht van haar eigen contacthistoriekbronnen, relevante functies of systematische raadplegingsstappen.

### Resultante of risico

De resultante is een systemisch controleerbaarheidsgat: het blijft onduidelijk welke bronnen zijn geraadpleegd, waarom de betrokkene zelf moest reconstrueren, en hoe historische en publiek gecommuniceerde datacapaciteit werd vertaald naar concrete rechtenfacilitatie.

### Auditconclusie

De audit wijst op een **gedeeltelijk conform maar systemisch kwetsbaar** proces. De behandeling lijkt niet willekeurig, maar de controleerbaarheid, taakduiding en proportionaliteit zijn onvoldoende aangetoond voor een robuuste audit opinion.

## 1.4 Overall Audit Opinion or Rating

**Audit opinion: gedeeltelijk conform met verhoogd systeemrisico.**

Motivering:

* de communicatie toont enige inhoudelijke behandeling;
* de betrokkene werd echter substantieel belast met reconstructie;
* KBC gaf geen controleerbare functionele matrix van toegang, doel en logging;
* de thesis en privacyverklaring verhogen de verwachting dat KBC haar eigen datacapaciteit explicieter had moeten inzetten of toelichten;
* de latere kennis van contacthistoriek wijst erop dat contactcontext intern niet afwezig was.

## 1.5 Summary of Recommendations

Aanbevolen wordt om:

* een functioneel overzicht te maken van contacthistoriekbronnen, gegevenscategorieën, functies en doelen;
* het rechtenproces te voorzien van een controleerbaar retrieval-log of beslislog;
* de scheiding tussen operationele afhandeling, klachtenbehandeling en privacy-governance expliciet te documenteren;
* de publieke privacyverklaring en de feitelijke rechtenafhandeling op elkaar af te stemmen;
* een minimale audit trail te bewaren van hoe contactmomenten en telefoongesprekken worden opgespoord bij inzageverzoeken.

---

# 2. Introduction & Methodology

## 2.1 Audit Objectives

De audit moet vaststellen:

* of KBC haar contacthistoriek en interactiedata systemisch controleerbaar inzet bij AVG-rechtenuitoefening;
* of de zoeklast proportioneel is verdeeld tussen KBC en de betrokkene;
* of de communicatie rond contacthistoriek aansluit bij de publieke privacyverklaring en de historische systeemcontext;
* of het proces een voldoende audit trail en functionele onderbouwing bevat.

## 2.2 Audit Scope and Boundaries

Binnen scope:

* de mails en bewijsstukken in Bundel 3;
* de thesis over ContactDB;
* de privacyverklaring van KBC;
* de matrix en het dossieroverzicht als analysekader.

Buiten scope:

* technische systeeminspectie;
* interne broncode, database-schema’s of toegangsrechten;
* interviews met KBC-medewerkers;
* een formele compliance-opinion over alle AVG-onderdelen van KBC.

## 2.3 Audit Methodology and Approach

Gebruikte methode:

* documentreview van de bewijsstukken;
* chronologische reconstructie van de mailketen;
* vergelijking van KBC’s vraagstelling met de historische ContactDB-context;
* vergelijking van KBC’s privacyverklaring met de feitelijke behandeling van het inzageverzoek;
* analyse van terugkerende patronen in toegangsbeperking, zoeklastverschuiving en kennis van contacthistoriek.

Er werden geen interviews of systeemtests uitgevoerd. Dit betekent dat de audit vooral documentaire bewijskracht heeft en geen technische penetratie- of configuratieaudit is.

## 2.4 Criteria and Standards Used

Het toetsingskader bestaat uit:

* artikel 12 AVG;
* artikel 15 AVG;
* de beperking van artikel 15, lid 4 AVG;
* de publieke privacyverklaring van KBC;
* de historische ContactDB-context uit de thesis;
* de interne logica van een controleerbaar rechtenproces: wie zoekt, welke bron, welk doel, welke logging.

## 2.5 Evidence and Reliability Basis

De audit steunt op:

* formele e-mails van 13 januari, 23 januari, 11 februari, 13 februari, 3 maart, 4 maart en 7 mei 2026;
* de thesis over customer journey predictors for consumer loans;
* de KBC-privacyverklaring;
* het dossieroverzicht en de contradictiematrix als analytisch kader.

De betrouwbaarheid van de bronmails is hoog als primaire bewijsbron, omdat zij directe communicatie tussen de betrokken partijen vastleggen. De thesis en de privacyverklaring zijn contextueel sterk, maar hebben een andere aard: de thesis toont historische capaciteit, de privacyverklaring publiek gecommuniceerde verwerkingscategorieën.

---

# 3. Detailed Audit Findings using OSCARC

## 3.1 Finding 1: Zoeklastverschuiving zonder controleerbare retrieval-log

### 3.1.1 O – Objectieve vaststelling

Op 23 januari 2026 vroeg KBC de betrokkene om telefoongesprekken te specificeren via kanaal, datum, tijdstip, medewerker en telefoonnummer. Op 11 februari 2026 en nadien bleef KBC interne notities, logs, metadata, CRM-velden en interne communicatie beperken of weigeren. Deze vaststelling steunt op [bewijsstuk_01_2026-01-23_kbc-vraagt-overzicht-telefoongesprekken.eml](../bewijsstukken/bewijsstuk_01_2026-01-23_kbc-vraagt-overzicht-telefoongesprekken.eml), [bewijsstuk_05_2026-03-04_kbc-alles-wat-we-kunnen-geven-is-bezorgd.eml](../bewijsstukken/bewijsstuk_05_2026-03-04_kbc-alles-wat-we-kunnen-geven-is-bezorgd.eml) en de relevante stukken in het dossieroverzicht.

### 3.1.2 S – Standaard of norm

Volgens artikel 12 en 15 AVG moet het inzageproces begrijpelijk, controleerbaar en voldoende specifiek zijn. De betrokkene hoeft niet de primaire zoek- of reconstructielast te dragen wanneer de verwerkingsverantwoordelijke zelf over relevante bronnen of systeemcategorieën kan beschikken.

### 3.1.3 C – Chronologie en context

De chronologie toont dat eerst de betrokkene breed inzage vroeg, daarna KBC gedetailleerde zoekparameters vroeg, en vervolgens een algemene beperking op meerdere categorieën gaf. De context wordt verzwaard door het feit dat de thesis historische ContactDB-capaciteit toont en de privacyverklaring contactmomenten en opnames publiek als verwerkbare persoonsgegevens erkent.

### 3.1.4 A – Acties of nalatigheden

KBC vroeg reconstructie, maar gaf geen controleerbaar retrieval-log of functioneel zoekoverzicht van welke eigen bronnen zij effectief raadpleegde. Dat is een nalatigheid voor zover de behandelingsketen daardoor niet controleerbaar wordt.

### 3.1.5 R – Resultante, effect of risico

De resultante is een verhoogd risico op zoeklastverschuiving en een gebrek aan audit trail. Het blijft onduidelijk of KBC intern eerst eigen contacthistoriekbronnen heeft geraadpleegd of vooral de betrokkene liet reconstrueren.

### 3.1.6 C – Conformiteitsbeoordeling en auditconclusie

De situatie is **gedeeltelijk conform** in die zin dat KBC wel reageerde, maar **niet conform in auditzin** voor zover controleerbaarheid, bronduiding en interne zoekvolgorde niet aantoonbaar zijn. Ernst: **middel-hoog**.

### 3.1.7 Recommendation and Management Action Plan

Aanbevolen wordt om een standaard retrieval-log te hanteren voor inzageverzoeken, met vermelding van broncategorie, zoekanker, verantwoordelijke functie, datum van raadpleging en uitkomst.

## 3.2 Finding 2: Functie-, bron- en doelmatrix ontbreekt als systemische controlelaag

### 3.2.1 O – Objectieve vaststelling

KBC gaf algemene uitleg over taakgebonden toegang tot klantgegevens, maar geen concreet functioneel overzicht van functiecategorieën, gegevenscategorieën, doeleinden en logging. Deze vaststelling steunt op [bewijsstuk_01_2026-01-23_kbc-vraagt-overzicht-telefoongesprekken.eml](../bewijsstukken/bewijsstuk_01_2026-01-23_kbc-vraagt-overzicht-telefoongesprekken.eml), [bewijsstuk_03_2026-03-03_klachtenbehandelaar-a-security-incident-earlier-branch.eml](../bewijsstukken/bewijsstuk_03_2026-03-03_klachtenbehandelaar-a-security-incident-earlier-branch.eml) en de matrix in [CONTRADICTIEMATRIX.md](CONTRADICTIEMATRIX.md).

### 3.2.2 S – Standaard of norm

Vanuit control perspective moet een rechtenproces minstens aangeven welke functies welke gegevenscategorieën mogen raadplegen en met welk doel. Dat is niet hetzelfde als volledige openbaarheid van interne systemen, maar wel een noodzakelijke functionele verantwoordingslaag.

### 3.2.3 C – Chronologie en context

De vereiste aan een functioneel overzicht wordt sterker door de latere kennis van contacthistoriek in de security-/klachtenketen en door de privacyverklaring waarin KBC zelf contactverwerking publiek benoemt. De historicale thesiscontext versterkt die verwachting.

### 3.2.4 A – Acties of nalatigheden

KBC gaf algemene taal over toegang, maar geen expliciete matrix van functie versus gegevens versus doel versus logging. Daarmee bleef de controlelaag impliciet.

### 3.2.5 R – Resultante, effect of risico

De resultante is een governance-gap: het dossier laat zien dat toegang bestaat of wordt verondersteld, maar niet hoe die toegang in het concrete rechtenproces functioneel wordt verantwoord.

### 3.2.6 C – Conformiteitsbeoordeling en auditconclusie

De situatie is **niet volledig conform** aan een auditverwachting van controleerbare procesverantwoordingslaag. Ernst: **middel**.

### 3.2.7 Recommendation and Management Action Plan

Aanbevolen wordt een functie-/gegevens-/doelmatrix op te stellen voor contacthistoriek, inclusief logging- en escalatieverantwoordelijkheden.

## 3.3 Finding 3: Publieke privacyverklaring en historische ContactDB-capaciteit sluiten niet naadloos aan op de feitelijke behandeling

### 3.3.1 O – Objectieve vaststelling

KBC’s privacyverklaring erkent contactmomenten, contactoverzichten, korte verslagen, klachten, feedback en opnames van telefoongesprekken als persoonsgegevens. De thesis wijst historisch op ContactDB als contacthistoriek- en analysecapaciteit. Deze vaststelling steunt op [bewijsstuk_06_Thesis_YL_CustomerJournePredictorsForConsumerLoans_final_confid.pdf](../bewijsstukken/bewijsstuk_06_Thesis_YL_CustomerJournePredictorsForConsumerLoans_final_confid.pdf), [bewijsstuk_07_KBC_Bank_privacy_NL.pdf](../bewijsstukken/bewijsstuk_07_KBC_Bank_privacy_NL.pdf) en de relevante passages in het dossieroverzicht.

### 3.3.2 S – Standaard of norm

Wanneer een organisatie publiek communiceert dat contactmomenten en opnames verwerkbare persoonsgegevens zijn, en historisch reeds contacthistoriek systematisch kon structureren, mag van een controleerbaar rechtenproces worden verwacht dat dit in de behandeling van inzageverzoeken zichtbaar terugkomt.

### 3.3.3 C – Chronologie en context

De thesis verwijst naar een historische systemische capaciteit. De privacyverklaring toont dat KBC ook publiek een actuele verwerkingscontext schetst. De contextuele spanning ontstaat omdat die twee bronnen niet vanzelf weerspiegeld worden in de feitelijke zoek- en ontsluitingspraktijk.

### 3.3.4 A – Acties of nalatigheden

KBC maakte niet zichtbaar hoe de historische of publiek gecommuniceerde capaciteit werd omgezet in concrete rechtenfacilitatie. Dat is een systemische nalatigheid in de procesverantwoording.

### 3.3.5 R – Resultante, effect of risico

De resultante is een auditrisico op mismatch tussen communicatie, capaciteit en uitvoering. Dit kan de geloofwaardigheid van de rechtenafhandeling verlagen en herhaalbaarheid bemoeilijken.

### 3.3.6 C – Conformiteitsbeoordeling en auditconclusie

De situatie is **gedeeltelijk conform**, maar met een duidelijke **systemische kwetsbaarheid**. Ernst: **middel-hoog**.

### 3.3.7 Recommendation and Management Action Plan

Aanbevolen wordt om privacyverklaring, interne procesbeschrijving en retrievalpraktijk op elkaar af te stemmen en deze afstemming periodiek te toetsen.

---

# 4. Auditobject en domeinspecifieke onderbouwing

Het primaire auditobject is de behandeling van het AVG-inzageverzoek in relatie tot contacthistoriek, interactiedata en zoeklast.

Relevante domeinonderbouwing bestaat uit:

* de communicatieketen rond het inzageverzoek;
* de thesis over ContactDB;
* de publieke privacyverklaring;
* de procesmatige en inhoudelijke documentatie in Bundel 3;
* de vaststellingen over latere kennis van contacthistoriek.

De audit leest deze elementen niet als losse incidenten, maar als onderdelen van één systemische keten: vraag, zoekvolgorde, beperking, context, resultaat en verantwoording.

---

# 5. Verfijningen ter versterking van betrouwbaarheid en bewijskracht

De auditbasis kan verder worden versterkt door:

* een formeel retrieval-log toe te voegen voor elk inzageverzoek;
* een functionele matrix van toegang, doel en logging te formaliseren;
* de privacyverklaring te laten aansluiten op de feitelijke rechtenafhandeling;
* bijkomende bronstukken toe te voegen over de interne handling van contacthistoriek;
* een duidelijke eigenaarschapstabel te maken voor contacthistoriek, security, klachtenmanagement en privacy-governance;
* steekproefsgewijze verificatie van brondata en zoekresultaten uit te voeren;
* eventuele management responses apart te documenteren.

Deze verfijningen zijn niet noodzakelijk corrigerende acties op een individuele bevinding, maar verhogen de betrouwbaarheid, herhaalbaarheid en bewijskracht van de audit als geheel.

---

# 6. Appendices

## 6.1 List of Interviewees and Stakeholders

Niet van toepassing voor deze documentaudit. Er werden geen interviews afgenomen.

## 6.2 Documents, Data, and Systems Reviewed

* Formeel verzoek tot inzage en kopie persoonsgegevens
* KBC-vraag naar overzicht van telefoongesprekken
* Logging van contacten door betrokkene
* Klachtenbehandelaar A-security-incident-mails
* KBC-mail over volledige bezorging van beschikbare informatie
* Thesis over customer journey predictors for consumer loans
* KBC privacyverklaring `KBC_Bank_privacy_NL.pdf`
* Dossieroverzicht `DOSSIEROVERZICHT – verschuiving van zoeklast.md`
* Contradictiematrix `CONTRADICTIEMATRIX.md`

## 6.3 Risk Matrix and Rating Definitions

* Laag: beperkte impact, beperkte herhaalbaarheid, beperkte auditrelevantie
* Middel: inhoudelijk relevant, maar beperkt in structurele impact
* Middel-hoog: duidelijke proces- of governancekwetsbaarheid
* Hoog: substantiële impact op controleerbaarheid, betrouwbaarheid of rechtenfacilitatie
* Kritiek: structureel falen van proces of governance met brede impact

## 6.4 Evidence Register

Zie de bewijsstukken in Bundel 3 en de hoofdverwijzingen in de andere documenten.

## 6.5 Management Response Letter

Niet beschikbaar in de huidige corpusreeks.

## 6.6 OSCARC Finding Register

De detailed findings in sectie 3 fungeren als OSCARC finding register.
