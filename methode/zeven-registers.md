# Methode: van bron tot beslissing in zeven registers

Elk rapport in deze repository, of het nu naar een toezichthouder, een journalist of een advocaat gaat, wordt opgebouwd uit dezelfde zeven registers. Ze lopen van wat er ligt naar wat we ermee doen. Elke stap mag alleen steunen op de stappen ervoor.

| Register | Vraag die het beantwoordt | Voorbeeld |
|---|---|---|
| **Bron** | Welk materiaal hebben we, en waar komt het vandaan? | Een gearchiveerde e-mail met headers en bijlagen. |
| **Waarneming** | Wat kan iemand rechtstreeks in die bron nagaan? | De e-mail van 14 mei zegt dat de beslissing al genomen is. |
| **Interpretatie** | Wat kan de waarneming in haar context betekenen? | "Beslissing" kan een interne aanbeveling zijn, of een formele goedkeuring. |
| **Hypothese** | Welke verklaring kunnen we toetsen? | De formele goedkeuring ging mogelijk vooraf aan de consultatie. Het goedkeuringsstuk en de tijdlijn van de consultatie kunnen dat toetsen. |
| **Bewering** | Welke stelling zijn we bereid te beoordelen of uit te spreken? | Een ambtenaar beschreef de beslissing als genomen nog vóór de consultatie afliep. |
| **Beoordeling** | Hoe houdt de bewering stand tegen een uitgesproken maatstaf? | Of de procedure werd nageleefd, hangt af van de toepasselijke regel en van het tijdstip van de formele goedkeuring. |
| **Beslissing** | Wat doen we met die beoordeling, en waarom? | Het ondertekende goedkeuringsstuk opvragen, om een reactie vragen, of de engere bewering melden met bronvermelding. |

## Waarom zeven registers

Het oorspronkelijke materiaal liet zien wat er gebeurt als die stappen in elkaar schuiven: een waarneming ("KBC beperkte de inzage") en een hypothese ("KBC deed dat met opzet") deelden één woord, *bewust*, en de hypothese leende de zekerheid van de waarneming. Zie [ontwarring](../poortwachter-bewijs/ontwarring/README.md).

De zeven registers houden die stappen uit elkaar:

- **Waarneming tegenover interpretatie.** Een waarneming is wat een derde in de bron kan nalezen, zonder voorkennis. Al het andere is interpretatie, ook als het voor de hand ligt.
- **Interpretatie tegenover hypothese.** Een interpretatie zegt wat iets *kan* betekenen; er zijn er doorgaans meerdere. Een hypothese kiest één verklaring en zegt *welk stuk haar zou bevestigen of weerleggen*. Zonder toetsmiddel is het geen hypothese maar een vermoeden.
- **Bewering tegenover beoordeling.** Een bewering is de formulering die we verdedigen. De beoordeling zet haar naast een maatstaf met exacte bepaling en versie. Zonder maatstaf blijft de beoordeling open.
- **Beslissing.** Elke beoordeling eindigt in een handeling: melden, opvragen, wederhoor vragen, versmallen, uitstellen of weglaten. De beslissing benoemt ook *waarom* en *door wie*.

## Verhouding tot wat er al ligt

| Bestaand instrument | Plaats in de zeven registers |
|---|---|
| Bronnenregisters (`BRON-xx` in [persoonlijk](../persoonlijk/ontward/bronnen.md), `S01–S24` in de [audit](../poortwachter-bewijs/perspectieven/1-audit.md#3-bronnen)) | Bron |
| OSCARC **O** (objectieve vaststelling) | Waarneming |
| OSCARC **C** en **A** (context, handeling of nalaten) | Waarneming en interpretatie, gescheiden |
| Aannameregisters (`ASM-xx`) | Hypothese: elke open aanname is een hypothese met een toetsmiddel |
| Open vragen (`Q-xx`) en bewijsvragen (`V1–V8`) | Het toetsmiddel van een hypothese |
| OSCARC **S** en het conformiteitsoordeel | Beoordeling |
| [PIA](../Publicatie-impactanalyse%20%28PIA%29.md), stap F | Beslissing |

OSCARC blijft de vorm voor één bevinding. De zeven registers zijn de ruggengraat waaraan bevindingen, aannames en beslissingen hangen.

## Regels

1. **Eén gemeenschappelijke basis, meerdere uitgangen.** Bronnen en waarnemingen worden één keer vastgelegd en door alle rapporten gedeeld. Interpretaties, hypotheses en beweringen mogen per forum verschillen; de feiten niet. Een journalist, een advocaat en de FSMA lezen dezelfde waarneming in dezelfde woorden.
2. **Niets springt een register over.** Een bewering verwijst naar minstens één waarneming. Een beoordeling verwijst naar een bewering én een maatstaf. Een beslissing verwijst naar een beoordeling.
3. **Een bewering is nooit sterker dan haar zwakste schakel.** Rust ze op een open hypothese, dan is ze voorwaardelijk en wordt ze zo geformuleerd ("indien", "voor zover", "dit vraagt verificatie van").
4. **"Na" is geen "door".** Een volgorde in de tijd is een waarneming. Een oorzakelijk verband is een hypothese tot het getoetst is.
5. **Wat ontbreekt, krijgt een rij.** Een thema zonder bron staat in het rapport met de status `geen bron`. Het verdwijnt niet en wordt niet ingevuld met een vermoeden.
6. **Niets wordt verwijderd.** Een verworpen hypothese of een ingetrokken bewering blijft staan, met de reden.
7. **Elke beslissing die iets naar buiten brengt, is een beslissing van de betrokkene.** Geen melding, klacht, wederhoorverzoek of publicatie vertrekt zonder zijn uitdrukkelijke akkoord.

## Codes en status

Elk rapport nummert zijn thema's met een eigen voorvoegsel (`FSMA-01`, `NBB-03`, `FODE-02`, `OMB-05`, `MED-01`, `JUR-01`). Binnen een thema worden de zeven registers ingevuld met verwijzingen naar bestaande codes, niet met kopieën van de tekst.

| Status van een thema | Betekenis |
|---|---|
| `geen bron` | Het thema is benoemd, maar er ligt nog geen materiaal in de repository. |
| `bron aanwezig` | Er is materiaal; waarnemingen zijn nog niet vastgelegd. |
| `waargenomen` | Waarnemingen staan vast; interpretatie en hypotheses lopen. |
| `bewering klaar` | De formulering is vastgelegd en steunt op de registers eronder. |
| `beoordeeld` | De bewering is getoetst aan een maatstaf met exacte bepaling en versie. |
| `beslist` | Er is een beslissing genomen over wat ermee gebeurt. |

## Sjabloon per thema

```markdown
### <CODE> · <thema>

**Status:** geen bron

| Register | Inhoud |
|---|---|
| Bron | |
| Waarneming | |
| Interpretatie | |
| Hypothese | Toetsmiddel: |
| Bewering | |
| Beoordeling | Maatstaf: |
| Beslissing | |
```
