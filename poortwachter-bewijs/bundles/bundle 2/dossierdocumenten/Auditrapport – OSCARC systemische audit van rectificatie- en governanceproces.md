# Auditrapport – OSCARC systemische audit van rectificatie- en governanceproces

**Dossier:** Bundel 2 – Recht op rectificatie / correctie persoonsgegevens  
**Auditfocus:** systemische werking van rectificatie, privacy governance, kanaalarchitectuur en controleerbaarheid  
**Status:** conceptauditdocument  

---

# 1. Executive Summary

## 1.1 Audit Background & Objectives

Deze audit onderzoekt of KBC in het concrete dossier een systemisch werkend, controleerbaar en reproduceerbaar proces heeft voor het uitoefenen van het recht op rectificatie, de doorverwijzing van privacyvragen, de rol van `dataprotection@kbc.be` en `mypersonaldata@kbc.be`, en de zichtbaarheid van de DPO-functie als onafhankelijke governance-waarborg.

De auditvraag is niet enkel of KBC ooit reageerde, maar of de organisatie, de kanalen, de normen en de bewijsvoering samen een robuust proces vormen. Daarbij wordt expliciet gekeken naar structurele patronen: herhaalde doorverwijzing, gebrek aan controleerbare correctiebevestiging, normatieve spanning tussen privacyverklaring en uitvoering, en onduidelijkheid over onafhankelijk toezicht.

## 1.2 Scope of the Audit

De audit omvat:
- de rectificatie- en opvolgingscommunicatie in Bundel 2;
- de privacyverklaring van KBC als door KBC gecommuniceerde procesnorm;
- de kanaalarchitectuur rond `dataprotection@kbc.be` en `mypersonaldata@kbc.be`;
- de vraag naar DPO-bereikbaarheid en onafhankelijke betrokkenheid;
- de latere gegevensset van 28 mei 2026 en de vraag of dezelfde foutieve gegevens zichtbaar bleven.

De audit omvat niet:
- een technische forensische vergelijking van alle bronbestanden;
- een volledige juridische kwalificatie van mogelijke AVG-schendingen;
- een audit van andere bundels buiten hun directe verwijzingswaarde.

## 1.3 Key OSCARC Findings

### Finding 1 – Structureel herhaald verduidelijkingspatroon
- **Objectieve vaststelling:** KBC vroeg op 4 maart 2026 opnieuw welke gegevens onjuist waren, hoewel op 3 februari 2026 reeds een concrete lijst werd bezorgd en op 26 februari 2026 een formeel rectificatieverzoek volgde. Zie [bewijsstuk_01](../bewijsstukken/bewijsstuk_01_2026-02-03_onjuiste-gegevens-lijst.eml), [bewijsstuk_02](../bewijsstukken/bewijsstuk_02_2026-02-26_rectificatie-en-deadline.eml) en [bewijsstuk_03](../bewijsstukken/bewijsstuk_03_2026-03-04_kbc-vraagt-welke-gegevens-onjuist-zijn.eml).
- **Standaard:** een rectificatieproces hoort invoer, registratie, opvolging en terugkoppeling controleerbaar te verbinden.
- **Belangrijkste afwijking:** hernieuwde verduidelijking suggereert dat de eerdere melding niet zichtbaar werd geïnternaliseerd in de procesketen.
- **Resultante/risico:** vertraging, procesonzekerheid en risico op onvolledige rechtenuitoefening.
- **Auditconclusie:** gedeeltelijk conform op communicatievlak, maar structureel zwak op procescontinuïteit.

### Finding 2 – Normatieve belofte van controle en inzage overstijgt de feitelijke uitvoeringssporen
- **Objectieve vaststelling:** op de coverpagina van KBC’s privacyverklaring staan expliciet de titel `Jouw privacy is belangrijk voor ons`, de tussenkop `Je behoudt altijd de controle over je gegevens` en de FAQ `Toon mij welke gegevens jullie van mij hebben`. Zie [bewijsstuk_11](../bewijsstukken/bewijsstuk_11_KBC_Bank_privacy_NL.pdf).
- **Standaard:** publieke privacycommunicatie moet aansluiten op de concrete verwerking en kanaalwerking.
- **Belangrijkste afwijking:** de praktijk toont geen expliciete, controleerbare correctiebevestiging of audit trail; de logica van tijdelijke beperking van verwerking bij betwiste juistheid wordt evenmin zichtbaar gemaakt in de stukken.
- **Resultante/risico:** normatieve mismatches tussen belofte en uitvoering verhogen het risico op audit finding en reputatie-/compliance-impact.
- **Auditconclusie:** niet-conforme of minstens onvoldoende aantoonbare procesimplementatie.

### Finding 3 – DPO-governance blijft onvoldoende onderscheidbaar van operationele afhandeling
- **Objectieve vaststelling:** de betrokkene vroeg expliciet naar DPO-contact, rol van privacymedewerker A en onafhankelijkheid. Zie [bewijsstuk_06](../bewijsstukken/bewijsstuk_06_2026-02-11_dpo-contactvraag-en-privacyverklaring.eml) en [bewijsstuk_07](../bewijsstukken/bewijsstuk_07_2026-03-11_antwoord-op-klachtenbehandelaar-a-dpo-contactbranch.eml).
- **Standaard:** een controleerbare governanceomgeving onderscheidt operationele mailboxen van onafhankelijke toezichtslijnen.
- **Belangrijkste afwijking:** de stukken tonen vooral doorverwijzing en mailboxrol, niet de onafhankelijke DPO-toetsing zelf.
- **Resultante/risico:** onduidelijkheid over accountability, escalatie en governance.
- **Auditconclusie:** procesmatig zwak; governance-waarborg onvoldoende aantoonbaar.

### Finding 4 – Latere gegevensset bevestigt mogelijk systeemmatig voortbestaan van foutieve data
- **Objectieve vaststelling:** op 28 mei 2026 werd opnieuw een gegevensset ontvangen waarvan de betrokkene stelt dat die inhoudelijk gelijk was aan de eerdere aanlevering. Zie [bewijsstuk_08](../bewijsstukken/bewijsstuk_08_2026-05-28_meest-recente-mail-telefoongesprekken.eml) en [bewijsstuk_08B](../bewijsstukken/bewijsstuk_08B_2026-05-28_pdf-bijlage-recht-van-inzage.pdf).
- **Standaard:** gecorrigeerde gegevens horen niet opnieuw als foutieve set zichtbaar te worden in een latere levering.
- **Belangrijkste afwijking:** ontbrekende zichtbaar gemaakte correctie of vergelijkingstabel.
- **Resultante/risico:** mogelijk voortbestaan van incorrecte data in het systeemlandschap.
- **Auditconclusie:** hoog risico op structurele datakwaliteits- of synchronisatieproblemen.

## 1.4 Overall Audit Opinion or Rating

**Audit opinion:** gedeeltelijk conform tot niet-conform, met verhoogd systemisch risico.

Motivering:
- de communicatie laat zien dat KBC reageerde;
- de procesarchitectuur blijft echter onvoldoende controleerbaar;
- de privacyverklaring legt een hogere norm vast dan wat in de concrete uitvoering aantoonbaar werd gemaakt;
- de latere gegevensset en herhaalde verduidelijkingen wijzen op een proces dat niet robuust of niet transparant genoeg is.

## 1.5 Summary of Recommendations

1. Formaliseer een zichtbaar rectificatiepad met ontvangst, triage, correctie, terugkoppeling en audit trail.
2. Scheid operationele uitvoering expliciet van onafhankelijke DPO-toetsing.
3. Maak mailboxrollen en bevoegdheden transparant in de privacyverklaring en in interne procedures.
4. Voeg een controleerbare correctiebevestiging toe per gemelde fout, met datum, systeem en verantwoordelijke.
5. Voorzie bij latere gegevensleveringen een vergelijkingsoverzicht tussen eerdere en gecorrigeerde datasets.

---

# 2. Introduction & Methodology

## 2.1 Audit Objectives

De audit moest vaststellen:
- of KBC’s rectificatieproces systemisch werkt;
- of de kanaalarchitectuur controleerbaar is;
- of de privacyverklaring en de feitelijke uitvoering op elkaar aansluiten;
- of de DPO-functie onderscheidbaar en onafhankelijk is gepositioneerd;
- of er een aantoonbare audit trail bestaat voor rectificatieopvolging.

## 2.2 Audit Scope and Boundaries

Binnen scope:
- Bundel 2 als hoofdbron;
- de privacyverklaring als normatief referentiekader;
- de mailketen rond rectificatie, opvolging en DPO-contact.

Buiten scope:
- volledige technische audit van KBC-systemen;
- alle overige bundels behalve voor contextuele verwijzing;
- juridische eindkwalificaties die aanvullend feitenonderzoek zouden vereisen.

## 2.3 Audit Methodology and Approach

Gebruikte benadering:
- documentreview van de bewijsstukken;
- chronologische reconstructie;
- normatieve toetsing aan artikel 16 AVG en KBC’s eigen privacyverklaring;
- patroonanalyse van doorverwijzing, opvolging en controleerbaarheid;
- systemische duiding van rol- en kanaalarchitectuur.

## 2.4 Criteria and Standards Used

Toetsingskader:
- artikel 16 AVG;
- artikel 18 AVG als aanvullende beheerslogica bij betwiste juistheid van persoonsgegevens;
- accountability- en transparantieverwachtingen uit de AVG;
- KBC’s privacyverklaring als publiek gecommuniceerde procesnorm;
- interne proceslogica zoals zichtbaar uit de mails;
- auditprincipes van controleerbaarheid, herhaalbaarheid en traceerbaarheid.

## 2.5 Evidence and Reliability Basis

Primaire bewijsbronnen:
- de mails in Bundel 2;
- de pdf-bijlage van 28 mei 2026;
- de privacyverklaring van KBC.

Betrouwbaarheid:
- hoog voor het bestaan van de communicatie en de kanaalroutes;
- middelmatig voor de inhoudelijke interpretatie van de latere dataset zonder technische vergelijkingstabel;
- hoog voor het bestaan van de privacyverklaring als normatief document;
- hoog voor de chronologie van de mailsporen.

Aanvullende juridische logica:
- wanneer juistheid van gegevens wordt betwist, hoort het proces niet enkel op rectificatie te sturen maar ook op beheersing van verdere verwerking totdat de betwisting controleerbaar is behandeld.

---

# 3. Detailed Audit Findings using OSCARC

## 3.1 Finding 1: Procesmatige herhaling zonder zichtbare interne koppeling

### 3.1.1 O – Objectieve vaststelling

Op 3 februari 2026 bezorgde de betrokkene een concrete lijst van foutieve of onduidelijke persoonsgegevens. Op 26 februari 2026 volgde een formeel rectificatieverzoek. Op 4 maart 2026 vroeg KBC opnieuw welke gegevens onjuist waren. Deze vaststelling steunt op [bewijsstuk_01](../bewijsstukken/bewijsstuk_01_2026-02-03_onjuiste-gegevens-lijst.eml), [bewijsstuk_02](../bewijsstukken/bewijsstuk_02_2026-02-26_rectificatie-en-deadline.eml) en [bewijsstuk_03](../bewijsstukken/bewijsstuk_03_2026-03-04_kbc-vraagt-welke-gegevens-onjuist-zijn.eml).

### 3.1.2 S – Standaard of norm

Volgens artikel 16 AVG en een basisnorm van goede procesbeheersing had de eerdere concrete lijst intern herkend en gekoppeld moeten worden aan het formele rectificatieverzoek.

### 3.1.3 C – Chronologie en context

De chronologie toont een eerste foutmelding, een formeel verzoek en daarna opnieuw een verduidelijkingsvraag. Contextueel kan worden aangevoerd dat sommige onderdelen van de eerste mail verduidelijking vroegen, maar de kern bleef een gespecificeerd rectificatiegeschil.

### 3.1.4 A – Acties of nalatigheden

KBC stelde opnieuw de vraag welke gegevens onjuist waren. De stukken tonen niet dat KBC tegelijk een zichtbare correctiebevestiging of audit trail aanleverde.

### 3.1.5 R – Resultante, effect of risico

De resultante is een voortzetting van de onzekerheid over de behandeling van de melding, met risico op procesvertraging en niet-controleerbare opvolging.

### 3.1.6 C – Conformiteitsbeoordeling en auditconclusie

De situatie is slechts gedeeltelijk conform. Communicatie gebeurde wel, maar de systemische proceskoppeling blijft zwak. Ernst: middel tot hoog.

### 3.1.7 Recommendation and Management Action Plan

Aanbevolen wordt om een standaard triage- en linkingsmechanisme te implementeren voor alle rectificatieverzoeken. Management dient een controleerbare case owner en een registratiepad te voorzien.

## 3.2 Finding 2: Privacyverklaring als norm, uitvoering als afwijking

### 3.2.1 O – Objectieve vaststelling

KBC verklaart in haar privacyverklaring dat persoonsgegevens kunnen worden verbeterd, dat dit via kantoor, KBC Live of KBC Mobile kan, en dat rechten via `mypersonaldata@kbc.be` kunnen worden uitgeoefend. Deze vaststelling steunt op [bewijsstuk_11](../bewijsstukken/bewijsstuk_11_KBC_Bank_privacy_NL.pdf).

### 3.2.2 S – Standaard of norm

De eigen privacyverklaring van KBC fungeert als publiek gecommuniceerde procesnorm. Die norm vereist dat de beloofde kanalen en rechtenuitoefening in de praktijk herkenbaar en controleerbaar zijn.

### 3.2.3 C – Chronologie en context

De privacyverklaring krijgt betekenis in samenhang met de latere rectificatiegeschiedenis. De betrokkene meldt fouten, vraagt rectificatie en treft later opnieuw dezelfde gegevens aan.

### 3.2.4 A – Acties of nalatigheden

Er werd geen duidelijke correctiebevestiging of vergelijkingsmatrix aangetroffen waaruit bleek dat de foutieve gegevens daadwerkelijk uit de latere dataset verdwenen waren.

### 3.2.5 R – Resultante, effect of risico

De resultante is een mogelijke mismatch tussen normatieve belofte en feitelijke uitvoering, met risico op compliance gap en reputatierisico.

### 3.2.6 C – Conformiteitsbeoordeling en auditconclusie

Niet conform of minstens onvoldoende aantoonbaar conform. Ernst: hoog.

### 3.2.7 Recommendation and Management Action Plan

Aanbevolen wordt om de privacyverklaring operationeel te vertalen naar een meetbare procesflow met bewijs van correctie, ontvangst en afsluiting.

## 3.3 Finding 3: DPO-governance en mailboxarchitectuur zijn niet audit-proof onderscheidbaar

### 3.3.1 O – Objectieve vaststelling

De betrokkene vroeg naar DPO-contact, de rol van privacymedewerker A en haar onafhankelijkheid. KBC verwees naar de privacyverklaring en later naar mailboxrollen. Deze vaststelling steunt op [bewijsstuk_06](../bewijsstukken/bewijsstuk_06_2026-02-11_dpo-contactvraag-en-privacyverklaring.eml) en [bewijsstuk_07](../bewijsstukken/bewijsstuk_07_2026-03-11_antwoord-op-klachtenbehandelaar-a-dpo-contactbranch.eml), in samenhang met [bewijsstuk_06](../bewijsstukken/bewijsstuk_06_2026-02-11_dpo-contactvraag-en-privacyverklaring.eml) en [bewijsstuk_09](../bewijsstukken/bewijsstuk_09_2026-03-04_klachtenbehandelaar-a-security-incident-schending-privacy.eml).

### 3.3.2 S – Standaard of norm

Een audit-proof governanceomgeving vereist duidelijke rolafbakening tussen operationele verwerking, mailboxbeheer en onafhankelijke toezichtslijnen.

### 3.3.3 C – Chronologie en context

De DPO-vraag volgt na de inhoudelijke rechtenuitoefening. De context is dus een escalatiefase waarin de betrokkene niet langer enkel data vraagt, maar ook controle over het governancekanaal zoekt.

### 3.3.4 A – Acties of nalatigheden

KBC bevestigde mailboxrollen, maar gaf geen expliciete, controleerbare verklaring over onafhankelijke DPO-toetsing in het concrete dossier.

### 3.3.5 R – Resultante, effect of risico

De resultante is onzekerheid over waar toezicht eindigt en uitvoering begint. Dat verhoogt het risico op onduidelijke verantwoordelijkheid en niet-auditbare afhandeling.

### 3.3.6 C – Conformiteitsbeoordeling en auditconclusie

Gedeeltelijk conform op toegankelijkheidsvlak, maar onvoldoende conform op controleerbaarheid van governance. Ernst: middel tot hoog.

### 3.3.7 Recommendation and Management Action Plan

Aanbevolen wordt om DPO-contact, mailboxbeheer en uitvoeringsdienst expliciet in een governancekaart te documenteren en publiek of intern controleerbaar te maken.

## 3.4 Finding 4: Latere dataset wijst op mogelijk structurele datakwaliteits- of synchronisatieproblemen

### 3.4.1 O – Objectieve vaststelling

Op 28 mei 2026 ontving de betrokkene opnieuw een pdf-bijlage waarvan hij stelt dat die dezelfde of inhoudelijk gelijkaardige gegevensset bevat als eerdere aanlevering. Deze vaststelling steunt op [bewijsstuk_08](../bewijsstukken/bewijsstuk_08_2026-05-28_meest-recente-mail-telefoongesprekken.eml) en [bewijsstuk_08B](../bewijsstukken/bewijsstuk_08B_2026-05-28_pdf-bijlage-recht-van-inzage.pdf).

### 3.4.2 S – Standaard of norm

Gecorrigeerde persoonsgegevens dienen niet opnieuw zichtbaar te blijven als foutieve dataset. Een auditvriendelijk proces vergt traceerbare correctie en versienummering.

### 3.4.3 C – Chronologie en context

De latere aanlevering moet worden gelezen tegen de achtergrond van de eerste foutmelding, het rectificatieverzoek en de daaropvolgende verduidelijkingsvraag. Contextueel is relevant dat de betrokkene zelf stelt dat hij opnieuw dezelfde gegevens zag.

### 3.4.4 A – Acties of nalatigheden

De beschikbare stukken tonen geen expliciete, controleerbare correctiecomparatie die laat zien welke gegevens in de tussenliggende periode werden aangepast.

### 3.4.5 R – Resultante, effect of risico

De resultante is een reëel risico op herhaalde verspreiding van onjuiste data binnen het systeemlandschap.

### 3.4.6 C – Conformiteitsbeoordeling en auditconclusie

Niet conform of hoogstens onvoldoende aantoonbaar conform. Ernst: hoog.

### 3.4.7 Recommendation and Management Action Plan

Aanbevolen wordt om een dataset-diff of correctiehistoriek verplicht te maken bij herlevering van persoonsgegevens.

---

# 4. Auditobject en domeinspecifieke onderbouwing

Het primaire auditobject is het rectificatie- en privacy-governanceproces binnen KBC zoals zichtbaar in Bundel 2.

De audit onderbouwt zich domeinspecifiek op:
- rights handling;
- mailbox governance;
- privacy compliance;
- datakwaliteit;
- control trail / audit trail;
- governance- en escalatiebeheersing.

De audit leest de bundel systemisch: niet enkel als reeks losse mails, maar als procesketen waarin dezelfde fout, dezelfde norm en dezelfde onduidelijkheid meerdere keren terugkeren.

---

# 5. Verfijningen ter versterking van betrouwbaarheid en bewijskracht

Voor verdere versterking van deze audit worden aanbevolen:
- een vergelijkingstabel tussen de datasets van 30 januari en 28 mei 2026;
- een interne log of case history van de behandeling van het rectificatieverzoek;
- een governance-overzicht van de rollen `dataprotection@kbc.be`, `mypersonaldata@kbc.be` en DPO;
- een expliciete bevestiging van welke fouten werden gecorrigeerd, wanneer en in welk systeem;
- een geverifieerde verwijzing naar de privacyverklaring met de exacte passages die relevant zijn.

Deze verfijningen zijn niet noodzakelijk corrigerende maatregelen op zich, maar verhogen de auditrobustheid, de reproduceerbaarheid en de bewijskracht.

---

# 6. Appendices

## 6.1 List of Interviewees and Stakeholders

- Yves Langeraert
- KBC / `mypersonaldata@kbc.be`
- KBC / `dataprotection@kbc.be`
- Klachtenbehandelaar A
- Privacymedewerker A

## 6.2 Documents, Data, and Systems Reviewed

- Bundel 2-e-mails
- KBC privacyverklaring
- Pdf-bijlage van 28 mei 2026

## 6.3 Risk Matrix and Rating Definitions

- Laag: beperkte impact, goed herstelbaar
- Middel: merkbare procesafwijking met beperkte structurele impact
- Hoog: relevante governance- of compliance-afwijking met herhalingsrisico
- Kritiek: structurele afwijking met ernstige impact of systemische ondermijning van rechtenuitoefening

## 6.4 Evidence Register

- Zie de bewijsstukken in Bundel 2 en de verwijzingen in de OSCARC-vaststellingen.

## 6.5 Management Response Letter

- Niet beschikbaar in de huidige bundel.

## 6.6 OSCARC Finding Register

- Finding 1: procesmatige herhaling zonder zichtbare interne koppeling
- Finding 2: privacyverklaring als norm, uitvoering als afwijking
- Finding 3: DPO-governance en mailboxarchitectuur zijn niet audit-proof onderscheidbaar
- Finding 4: latere dataset wijst op mogelijk structurele datakwaliteits- of synchronisatieproblemen
