# Auditrapport Bundel 6

## 1. Executive Summary

### 1.1 Audit Background & Objectives
Deze audit onderzoekt of KBC voor privacy- en AVG-signalen een voldoende duidelijke, onafhankelijke en controleerbare governance inrichtte. De aanleiding is de communicatiereeks rond het inzageverzoek, de DPO-vraag, de mailboxroutering tussen `dataprotection@kbc.be` en `mypersonaldata@kbc.be`, en de vraag of betwiste afhandeling voldoende aantoonbaar werd opgevolgd.

Het auditdoel is niet om de onderliggende juridische discussie definitief te beslechten, maar om systemisch vast te stellen of de organisatie de route van ontvangst, triage, inhoudelijke beoordeling, escalatie en afsluiting voldoende controleerbaar maakte.

### 1.2 Scope of the Audit
De audit omvat de bewijsstukken 6.1 tot en met 6.12 uit Bundel 6, aangevuld met de dossiercontext die deze stukken als governance- en boundarykader beschrijft. Binnen scope vallen:

- de ontvangst en doorverwijzing van het inzageverzoek;
- de operationele behandeling via `mypersonaldata@kbc.be`;
- de zichtbaarheid van de DPO-functie;
- de scheiding tussen ontvangst-, uitvoerings- en toezichtskanalen;
- de threadgrens tussen laatste KBC-reactie en betrokkene-follow-up.

Buiten scope vallen:

- de inhoudelijke juistheid van de onderliggende persoonsgegevensexport als zodanig;
- de telefonische authenticatie- en opnameproblematiek uit Bundel 4 en 5, behalve voor zover het dossier ernaar verwijst als context;
- de gemigreerde stukken 6.13 tot en met 6.17, tenzij de dossiercontext er expliciet naar verwijst.

### 1.3 Key OSCARC Findings

**Objectieve vaststelling**  
KBC organiseerde de afhandeling van het inzageverzoek via een combinatie van `dataprotection@kbc.be` en `mypersonaldata@kbc.be`, met latere explicitering dat privacymedewerker A verantwoordelijk is voor de `dataprotection@kbc.be`-mailbox. De betrokkene vroeg herhaaldelijk naar de DPO, maar kreeg geen controleerbare identificatie van de DPO in de thread zelf.

**Toepasselijke standaard**  
Relevante normen zijn de AVG-bepalingen over inzage, accountability en DPO-onafhankelijkheid, in het bijzonder artikelen 15, 24, 38 en 39 AVG, aangevuld met de eigen privacyverklaring en interne kanaalarchitectuur van KBC.

**Belangrijkste afwijking**  
De bewijsreeks toont routing en operationele opvolging, maar geen expliciet controleerbaar spoor dat de onafhankelijke DPO-toetsing boven de operationele mailboxlaag aantoonbaar maakt.

**Resultante of risico**  
Het concrete gevolg is een controleerbaarheidsprobleem: voor de betrokkene blijft onduidelijk wie inhoudelijk toetste, wie besliste, en hoe de onafhankelijke functie zich verhield tot de operationele afhandeling.

**Auditconclusie**  
De governance is gedeeltelijk traceerbaar op kanaalniveau, maar niet voldoende aantoonbaar op toezichtniveau. De organisatie toont een werkende route, maar niet overtuigend de onafhankelijke waarborg die daar bovenop hoort te staan.

### 1.4 Overall Audit Opinion or Rating
**Overall rating: Partially effective / needs improvement.**

Motivering:

- de routing is zichtbaar;
- de operationele behandeling is aantoonbaar;
- de DPO-vraag is herhaaldelijk gesteld;
- de onafhankelijke DPO-betrokkenheid blijft echter niet controleerbaar;
- de threadgrens tussen KBC-reactie en follow-up van de betrokkene is uiteindelijk wel te reconstrueren, maar had in de communicatie zelf explicieter gemarkeerd mogen worden.

### 1.5 Summary of Recommendations

1. Maak de routing tussen `dataprotection@kbc.be` en `mypersonaldata@kbc.be` formeel expliciet in een publiek of intern procesoverzicht.
2. Documenteer wanneer en hoe de DPO inhoudelijk wordt betrokken bij betwiste privacyverzoeken.
3. Scheid operationele uitvoering, klachtbehandeling en onafhankelijke toezichtstap in zichtbare stappen.
4. Label follow-up van de betrokkene duidelijk als follow-up, zodat threadgrenzen niet verwarren met nieuwe KBC-reacties.
5. Zorg voor een controleerbare escalatielijn voor meldingen die meer zijn dan louter een operationele vraag.

## 2. Introduction & Methodology

### 2.1 Audit Objectives
De audit moest vaststellen:

- hoe privacy- en AVG-signalen binnen KBC worden ontvangen;
- wie de operationele uitvoering van een rechtenverzoek behandelt;
- of de DPO-functie voldoende zichtbaar en onafhankelijk bereikbaar is;
- of governance en operationele uitvoering van elkaar gescheiden zijn;
- of de communicatie controleerbaar laat zien wat KBC deed, wanneer en via welk kanaal.

### 2.2 Audit Scope and Boundaries
Binnen scope:

- bundel 6 kernstukken 6.1 tot en met 6.12;
- dossiercontext over privacygovernance, routing en accountability;
- de kanaalarchitectuur rond `dataprotection@kbc.be`, `mypersonaldata@kbc.be` en klachtenmanagement.

Buiten scope:

- de feitelijke inhoud van alle onderliggende persoonsgegevens;
- de inhoudelijke onderbouwing van de onderliggende claim over telefoongesprekken, opnames of logging buiten zover deze in bundel 6 wordt gebruikt als governancecontext;
- de buitenbundelse gemigreerde stukken 6.13 tot en met 6.17, behalve als contextuele verwijzing.

### 2.3 Audit Methodology and Approach
Gebruikte methoden:

- documentreview van bundel 6 en de bijhorende dossiertekst;
- chronologische reconstructie van mailketens;
- kanaalanalyse van ontvangst-, uitvoerings- en doorverwijslijnen;
- controle van threadgrenzen en labelcorrectheid;
- contextuele beoordeling van systemische patronen.

Geen interviews, systeemtoegang of technische loggingreview was in deze bundel beschikbaar. De audit steunt dus op documentaire bewijsvoering en threadanalyse.

### 2.4 Criteria and Standards Used
Toetsingskader:

- artikel 15 AVG voor inzage en reactie op rechtenverzoeken;
- artikel 24 AVG voor verantwoordelijkheid en aantoonbare naleving;
- artikelen 38 en 39 AVG voor de onafhankelijke rol van de DPO;
- de privacyverklaring en gecommuniceerde kanaalarchitectuur van KBC;
- de intern en extern zichtbare scheiding tussen governance, operationele uitvoering en klachtenafhandeling.

### 2.5 Evidence and Reliability Basis
Betrouwbare kernbronnen:

- primaire e-mails in bundel 6;
- chronologie en labels in het dossier;
- de expliciete threadmarkeringen van KBC en de betrokkene.

Beperkingen:

- geen directe systeemlogs;
- geen interviewtranscripten;
- geen formele management response op deze audit;
- geen technische verificatie van mailbox- of DPO-routing buiten de documentketen.

## 3. Detailed Audit Findings using OSCARC

### 3.1 Finding 1: Gescheiden ontvangst- en uitvoeringskanalen

#### 3.1.1 O – Objectieve vaststelling
Op 13 januari 2026 werd het inzageverzoek gericht aan `dataprotection@kbc.be`. Op 19 januari 2026 volgde doorverwijzing naar `mypersonaldata@kbc.be`. Op 27 maart 2026 en 24 april 2026 werd de scheiding tussen `dataprotection@kbc.be` en `mypersonaldata@kbc.be` verder expliciet gemaakt. Deze vaststelling steunt op [bewijsstuk 6.1](../bewijsstukken/bewijsstuk_01_2026-01-13_formeel-verzoek-inzage-kopie-persoonsgegevens.eml), [bewijsstuk 6.2](../bewijsstukken/bewijsstuk_02_2026-01-19_privacymedewerker-a-dataprotection-doorverwijzing-mypersonaldata.eml), [bewijsstuk 6.9](../bewijsstukken/bewijsstuk_09_2026-03-27_privacymedewerker-a-dataprotection-mypersonaldata.eml) en [bewijsstuk 6.10](../bewijsstukken/bewijsstuk_10_2026-04-24_dataprotection-eerstelijnsdienst.eml).

#### 3.1.2 S – Standaard of norm
Volgens de AVG-accountability en de eigen proceslogica van KBC moet duidelijk zijn welk kanaal ontvangt, welk kanaal uitvoert en welk kanaal toeziet.

#### 3.1.3 C – Chronologie en context
De communicatie wijst op een vaste routering: ontvangst via `dataprotection@kbc.be`, uitvoering via `mypersonaldata@kbc.be`, en later herbevestiging van die tweedeling.

#### 3.1.4 A – Acties of nalatigheden
KBC splitste ontvangst en uitvoering operationeel, maar documenteerde in dezelfde lijn geen expliciet, controleerbaar toezichtstraject erboven.

#### 3.1.5 R – Resultante, effect of risico
De resultante is een zichtbaar werkende kanaalstructuur, maar ook een risico op onduidelijkheid over waar onafhankelijke toetsing precies plaatsvindt.

#### 3.1.6 C – Conformiteitsbeoordeling en auditconclusie
Gedeeltelijk conform: kanaalroutering is aantoonbaar, maar toezichtscheiding is niet aantoonbaar genoeg.

#### 3.1.7 Recommendation and Management Action Plan
Formeel vastleggen welke mailboxen ontvangst, uitvoering en toezicht vertegenwoordigen, inclusief escalatieregels en verantwoordelijke functies.

### 3.2 Finding 2: DPO-onafhankelijkheid blijft niet controleerbaar

#### 3.2.1 O – Objectieve vaststelling
De betrokkene vroeg op 10 maart, 11 maart en 17 maart 2026 expliciet naar de DPO, de identiteit van privacymedewerker A en haar onafhankelijkheid. KBC verwees naar de privacyverklaring en later naar mailboxverantwoordelijkheid, zonder de DPO in de thread zelf expliciet en controleerbaar te identificeren. Deze vaststelling steunt op [bewijsstuk 6.5](../bewijsstukken/bewijsstuk_05_2026-03-10_vraag-dpo-contactgegevens.eml), [bewijsstuk 6.6](../bewijsstukken/bewijsstuk_06_2026-03-11_antwoord-klachtenmanagement-dpo-contact.eml), [bewijsstuk 6.7](../bewijsstukken/bewijsstuk_07_2026-03-11_vraag-privacymedewerker-a-dpo-onafhankelijkheid.eml), [bewijsstuk 6.8](../bewijsstukken/bewijsstuk_08_2026-03-17_herinnering-dpo-onafhankelijke-mening.eml) en [bewijsstuk 6.9](../bewijsstukken/bewijsstuk_09_2026-03-27_privacymedewerker-a-dataprotection-mypersonaldata.eml).

#### 3.2.2 S – Standaard of norm
De DPO moet onafhankelijk, tijdig bereikbaar en inhoudelijk herkenbaar zijn binnen de AVG-governance.

#### 3.2.3 C – Chronologie en context
De vraag ontstond na betwisting van de afhandeling en werd herhaald voordat KBC later via mailboxbeheer antwoordde.

#### 3.2.4 A – Acties of nalatigheden
De betrokkene probeerde de DPO-functie te activeren; KBC gaf wel een privacyroute en mailboxinformatie, maar geen expliciete, controleerbare DPO-identificatie in de thread.

#### 3.2.5 R – Resultante, effect of risico
Het gevolg is een audit- en accountabilitygat: bereikbaarheid van het kanaal is aantoonbaar, maar onafhankelijk toezicht niet.

#### 3.2.6 C – Conformiteitsbeoordeling en auditconclusie
Gedeeltelijk conform: de organisatie reageert, maar maakt de onafhankelijke DPO-laag onvoldoende zichtbaar.

#### 3.2.7 Recommendation and Management Action Plan
Introduceren van een expliciete DPO-contact- en escalatieprocedure in de communicatie met betrokkenen.

### 3.3 Finding 3: Threadgrens en bewijslabeling zijn uiteindelijk correct, maar niet vanzelfsprekend

#### 3.3.1 O – Objectieve vaststelling
Op 28 mei 2026 kwam een laatste inhoudelijke reactie van KBC via `mypersonaldata@kbc.be`. Op 4 juni 2026 volgde een vervolgmail van de betrokkene zelf. Deze vaststelling steunt op [bewijsstuk 6.11](../bewijsstukken/bewijsstuk_11_2026-05-28_laatste-mypersonaldata-communicatie.eml) en [bewijsstuk 6.12](../bewijsstukken/bewijsstuk_12_2026-06-04_vervolgcommunicatie-mypersonaldata.eml).

#### 3.3.2 S – Standaard of norm
Audit- en bewijsstandaarden vereisen correcte labeling van primaire respons en follow-up, zodat bewijswaarde niet wordt verschoven.

#### 3.3.3 C – Chronologie en context
De thread toont eerst een KBC-reactie en daarna een follow-up van de betrokkene, maar de latere documentatie moest expliciet verduidelijken dat 6.12 geen nieuwe KBC-reactie is.

#### 3.3.4 A – Acties of nalatigheden
De bundel is achteraf gecorrigeerd om de threadgrens duidelijk te maken.

#### 3.3.5 R – Resultante, effect of risico
Het risico is beperkt maar reëel: zonder expliciete labeling zou follow-up als nieuwe response kunnen worden gelezen.

#### 3.3.6 C – Conformiteitsbeoordeling en auditconclusie
Conform mits expliciete documentatie; dit is nu voldoende gecorrigeerd.

#### 3.3.7 Recommendation and Management Action Plan
Behoud de expliciete onderscheidslijn tussen KBC-reacties en follow-up van de betrokkene in alle bundel- en dossierdocumenten.

## 4. Auditobject and domain-specific substantiation

Het primaire auditobject is de governance van privacy- en AVG-signalen binnen KBC, zoals zichtbaar in de communicatieketen rond `dataprotection@kbc.be`, `mypersonaldata@kbc.be`, klachtenmanagement en de DPO-vraag.

De audit laat zien dat dit object niet louter individueel is. Het bevat een systemisch patroon:

- ontvangst wordt gecentraliseerd;
- uitvoering wordt gemandateerd aan een operationeel kanaal;
- toezicht blijft conceptueel aanwezig, maar documentair ondoorzichtig;
- follow-up en reactie moeten zorgvuldig worden onderscheiden.

## 5. Verfijningen ter versterking van betrouwbaarheid en bewijskracht

Om de auditbasis te versterken, zouden de volgende stappen de bewijskracht verhogen:

- een formele kanaalkaart met ontvangst-, uitvoering- en toezichtrollen;
- een expliciete DPO-escalatieprocedure voor betwiste rechtenverzoeken;
- een logging- of registratieoverzicht van routingbesluiten;
- een aparte management response op de governancevraag;
- een vast format om follow-up van de betrokkene van KBC-reacties te onderscheiden;
- eventueel aanvullende bewijsstukken over de buitenbundelse gemigreerde context, als die voor de audit relevant worden geacht.

Deze verfijningen corrigeren niet noodzakelijk een bevinding, maar verhogen de herhaalbaarheid en controleerbaarheid.

## 6. Appendices

### 6.1 List of Interviewees and Stakeholders
- Yves Langeraert
- KBC `dataprotection@kbc.be`
- KBC `mypersonaldata@kbc.be`
- Privacymedewerker A
- KBC klachtenmanagement

### 6.2 Documents, Data, and Systems Reviewed
- Bundel 6 bewijsstukken 6.1 tot en met 6.12
- Bundel 6 dossieroverzicht
- Bundel 6 OSCARC-vaststellingsnota

### 6.3 Risk Matrix and Rating Definitions
- Laag: beperkte impact en duidelijke beheersing
- Middel: beperkte maar relevante onduidelijkheid of afwijking
- Hoog: structurele onduidelijkheid of terugkerend governanceprobleem
- Kritiek: ernstig controleverlies of substantiële auditbreuk

### 6.4 Evidence Register
- Zie de bewijsmatrix in het bundeldossier voor de primaire stukken

### 6.5 Management Response Letter
- Niet beschikbaar in de huidige bundel

### 6.6 OSCARC Finding Register
- Finding 1: Gescheiden ontvangst- en uitvoeringskanalen
- Finding 2: DPO-onafhankelijkheid blijft niet controleerbaar
- Finding 3: Threadgrens en bewijslabeling zijn uiteindelijk correct, maar niet vanzelfsprekend

