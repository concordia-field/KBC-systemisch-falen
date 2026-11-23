---
id: VERZEKERING-BA
type: waarborg
naam: Verzekering beroepsaansprakelijkheid
samenvatting: Het onderzoekswerk in deze repository valt onder de beschreven activiteiten van een polis beroepsaansprakelijkheid met rechtsbijstand; of die polis een concrete vordering dekt, beslist de verzekeraar per schadegeval.
status: voorwaardelijk
maturiteit: ontwerp
goedgekeurd_door: niet goedgekeurd (geen menselijke review vastgelegd)
laatst_bijgewerkt: 2026-11-23
vocabularium: poortwachter-bewijs/bundles/bundle 1/kennislaag/vocabularium.yaml
bronnen:
  - VERZ-01: behoefteanalyse, documentdatum 2026-05-08 (lokaal, juridisch/bewijsstukken/)
  - VERZ-02: bijzondere voorwaarden, bijvoegsel 1, documentdatum 2026-05-08, ingangsdatum 2026-05-04 (lokaal, juridisch/bewijsstukken/)
relaties:
  - document/behandelt: Publicatie-impactanalyse (PIA).md
---

# Verzekering beroepsaansprakelijkheid

Naast de [publicatie-impactanalyse](Publicatie-impactanalyse%20%28PIA%29.md), die bepaalt wát naar buiten mag, is er een tweede waarborg: het onderzoekswerk gebeurt binnen een beroepsactiviteit waarvoor een verzekering beroepsaansprakelijkheid loopt. De PIA verkleint de kans op een terechte klacht; de verzekering gaat over de gevolgen als er toch een vordering komt.

Status: **voorwaardelijk.** Dat de polis bestaat en wat ze beschrijft, staat vast. Of ze een concrete vordering dekt, hangt af van de algemene voorwaarden en van de beoordeling door de verzekeraar.

## Context

Een analyse die zwaktes in de processen van een bank blootlegt, kan tot een vordering leiden, ook als ze zorgvuldig is. Dat risico wordt niet weggeschreven maar gedragen: door de PIA en wederhoor vóór publicatie, en door een verzekering voor het geval een vordering volgt.

## Beschrijving

- **Verzekeraar:** KBC Verzekeringen NV, een dochter van KBC Groep NV.
- **Verzekeringnemer:** de vennootschap waarlangs de beroepsactiviteit van de betrokkene loopt.
- **Verzekeringen:** aansprakelijkheid en rechtsbijstand.
- **Geldig:** het huidige bijvoegsel geldt vanaf 4 mei 2026, met jaarlijkse vervaldag op 1 januari en stilzwijgende verlenging.

## Eigenschappen

**Verzekerde activiteiten**, in eigen woorden: consultancy en onderzoek over dataverwerking, digitale systemen en AI-toepassingen, uitdrukkelijk met inbegrip van:

1. kwetsbaarheden in ICT-systemen, datastromen en digitale processen identificeren, analyseren en valideren;
2. exploiteerbare zwaktes in businesslogica, procesontwerp en geautomatiseerde besluitvorming testen en aantonen;
3. risico's evalueren van data-accumulatie, algoritmisch gedrag en systeeminteracties;
4. responsible disclosure en vulnerability research, conform de toepasselijke regelgeving.

Het werk in deze repository (procesontwerp, geautomatiseerde besluitvorming en informatiebeheer bij een bank onderzoeken en de zwaktes documenteren) sluit aan bij punten 2 en 3. Dat is de lezing van de betrokkene; de verzekeraar beoordeelt het per schadegeval.

## Gedrag

| Wat | Stand |
|---|---|
| Polis en verzekerde activiteiten | vastgesteld, in de bijzondere voorwaarden |
| Dekking van een concrete vordering van KBC Bank | open; beoordeling door de verzekeraar |
| Verdediging door de verzekeraar en de reikwijdte van de rechtsbijstand | niet-in-bron; staat in de algemene voorwaarden (versie 14 maart 2015), die niet in de repository zitten |
| Uitsluitingen (zoals opzet) | niet-in-bron, op één gewijzigde paragraaf na |
| Verzekeraar en mogelijke eiser in dezelfde groep | vastgesteld; hoe het belangenconflictenbeleid van de verzekeraar dan speelt, is onbekend |

## Relaties

- **Vult aan:** [Publicatie-impactanalyse (PIA)](Publicatie-impactanalyse%20%28PIA%29.md), stap 6 van de aanpak in de [README](README.md#de-aanpak).
- **Juridisch:** de open vragen staan bij de [vragen aan de advocaat](juridisch/README.md#vragen-aan-de-advocaat).
- **Bronnen:** de polisdocumenten bevatten bedrijfs- en polisgegevens. Ze worden lokaal bewaard in `juridisch/bewijsstukken/` en door Git genegeerd.
