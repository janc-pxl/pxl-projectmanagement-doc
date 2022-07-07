---
share: True
---
# Risicomanagement

![Image|600](https://i.imgur.com/hxGs2TC.jpg)


#### Hogeschool PXL
##### **PXL-Digital** Professionele bachelor in de toegepaste informatica

##### **42TIN1250 Projectmanagement**

##### **Lectoren**
##### Dhr. Lowie Vangaal, Dhr. Jan Castermans

<div style="page-break-after: always;"></div>

## Inleiding
![](https://i.imgur.com/0yXSNzo.png)

Een risicoanalyse is een methode waarbij nader benoemde risico's worden gekwantificeerd door het bepalen van de kans dat een dreiging zich voordoet en de gevolgen daarvan: 

> Risico = Kans x Gevolg. 

De risicoanalyse is de eerste stap binnen het risicomanagementproces.

![](https://i.imgur.com/PT4MpTl.png)

## Doel
![](https://i.imgur.com/LBxBZZz.png)

Bij een risicoanalyse worden bedreigingen benoemd en in kaart gebracht. Per bedreiging wordt de kans van het optreden ervan bepaald en wordt vervolgens berekend wat als gevolg de schade is die op zou kunnen optreden als een bedreiging zich daadwerkelijk voor doet.

Op grond van een risicoanalyse kunnen de volgende maatregelen worden genomen:

- **preventie**: het voorkomen dat iets gebeurt of het verminderen van de kans dat het gebeurt;
- **repressie**: het beperken van de schade wanneer een bedreiging optreedt;
- **correctie**: het instellen van maatregelen die worden geactiveerd zodra iets is gebeurd om het effect hiervan (deels) terug te draaien
- **acceptatie**: geen maatregelen, men accepteert de kans en het mogelijke gevolg van een bedreiging;
- **manipulatie**: het wijzigen van parameters in de berekening om tot een gewenst resultaat te komen.

De bedoeling van een risicoanalyse is dat er na de analyse wordt vastgesteld op welke wijze de risico's beheerst kunnen worden, of teruggebracht tot een aanvaardbaar niveau. Daarbij wordt naast een risicoanalyse ook een kosten en baten analyse uitgevoerd. Op voorhand hoeft niet ieder risico te worden afgedekt: wanneer de kosten van de maatregelen om een risico te beperken hoger zijn dan de mogelijke schade, dan kan besloten worden het risico te accepteren. Het permanent uitvoeren van risicoanalyses wordt Risico Management (ook wel Risk Management of Risk Control) genoemd.

## Risicoanalyse technieken
![](https://i.imgur.com/oyirpjD.png)
### Inleiding

Een risicoanalyse kan uitgevoerd worden op 2 manieren:

| Kwalitatieve methode | Kwantitatieve methode                                                                 |
| -------------------- | ------------------------------------------------------------------------------------- |
| Schattingen maken    | Risico’s kwantificeren in meetbare criteria,meestal uitgedrukt in financiële gevolgen |

### Fault tree analyse

De foutenboomanalyse (Fault Tree Analysis, FTA) is een methode om diepgaand, maar niet kwantitatief, te onderzoeken wat er fout kan gaan met de dienstverlening, het proces of het product.

Bij elke faalvorm wordt de vraag gesteld: wat is de oorzaak? Zo ontstaan er, naar beneden toe, grondoorzaken van de faalvormen van het proces of product. De foutenboomanalyse is handig uit te voeren aan de hand van de functiestructuur.

#### Doel en belang

De foutenboom brengt visueel in kaart wat kan fout gaan met het product, en dit door bij elke faalvorm de vraag te stellen: “Hoe komt dit, wat is de oorzaak hiervan?”. Zo wordt een (omgekeerde) boom bekomen, die naar beneden toe de (achterliggende) grondoorzaken van het product toont.

Een opgestelde functiestructuur is handig als basis voor de foutenboomanalyse: bij elk onderdeel of elke functie kan de vraag gesteld worden: “Wat kan hiermee fout gaan?”.

#### Voorbeeld: Een stuk foutenboomanalyse voor een fiets. 
![](https://i.imgur.com/8Oh1Eb2.png)

Hoe een foutenboom opstellen?

- Plaats bovenaan de boom een mogelijk defect.
- Geef alle mogelijke oorzaken van het defect aan de hand van logische structuren (EN, OF,…) aan.
- Diep dit uit tot op een niveau dat het probleem duidelijk zichtbaar is. In de volgende stappen wordt bekeken wat het gevolg en de ernst van het probleem is, en worden naar oplossingen gezocht.

#### Gebruikte symbolen
![](https://i.imgur.com/SNWdQUF.png)

#### Uitgewerkt voorbeeld
![](https://i.imgur.com/qJDgS9z.png)

#### Kansberekening met Booleaanse algebra
![](https://i.imgur.com/TRSpZTP.png)

![](https://i.imgur.com/bd3HWM0.png)

### Risicoanalyse techniek : SPRINT

Voor de risico analyse is gebruik gemaakt van de SPRINT-methodiek van het ISF. In interviews met het verantwoordelijke management zijn de risico’s per afdeling geïnventariseerd. Deze risico analyse is de samenvatting van de uitkomsten op basis waarvan het basisbeveiligingsniveau is vastgesteld, aangevuld met veelal afdeling gebonden aandachtspunten, waarvoor additionele maatregelen reeds bestaan dan wel moeten worden gedefinieerd.

In het kort een toelichting op deze methode:

#### Risico analyse checklist

1. **Identificeer kritieke onderdelen van de afdeling**

In een tabel zijn de kritieke onderdelen van \<PPPP\> opgenomen, met een motivatie waarom deze onderdelen kritiek zijn. Onder ‘kritiek’ wordt hier verstaan een veiligheidsrisico lopend.

2. **Vul de B, I en V tabellen in**

In een tabel wordt weergegeven wat het risico is van een gebeurtenis, rekening houdend met de volgende variabelen:

• de impact van een gebeurtenis;
• de kans dat de gebeurtenis optreedt;
• de schade bij het optreden van de gebeurtenis.

Aan de impact van een gebeurtenis wordt een ‘rating’ toegekend tussen A (verwaarloosbaar risico) en E (hoog risico). De rating is in deze risico analyse al gecorrigeerd voor de reeds genomen maatregelen, waardoor het risico gereduceerd dan wel ondervangen is.

Schematisch kunnen we dit als volgt weergeven:

| Rating | Ernst                          | Schade (in € * 1000) |
| ------ | ------------------------------ | -------------------- |
| E      | Bedrijfscontinuïteit in gevaar | >1000                |
| D      | Zware schade                   | >100                 |
| C      | Aanzienlijke schade            | >10                  |
| B      | Lichte schade                  | >1                   |
| A      | Verwaarloosbaar                | <1                   |


#### Vertrouwelijkheid

| Gevolgen van inbreuk op vertrouwelijkheid | Rating  |       |     |     |     | Opmerkingen                                                                                                                                                                                                                 |
|-------------------------------------------|---------|-------|-----|-----|-----|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Concurrentieverlies                       | **A**   | B     | C   | D   | E   | Niet echt van toepassing, want \<PPPP\> is uniek binnen de branche. Wel zijn er vergelijkbare organisaties, maar met een andere scope dan \<PPPP\>. Deze worden niet gezien als concurrenten.                               |
| Direct verlies van business               | **A**   | B     | C   | D   | E   | Dit is nauwelijks van toepassing. Vrijwel alle informatie is openbaar of opvraagbaar ihkv de WOB. De wel gevoelige informatie (JZ, PZ, ICT) is goed beveiligd.                                                              |
| Extern imago                              | A       | **B** | C   | D   | E   | Als \<PPPP\> erin slaagt de voorpagina van de Telegraaf of van de vakbladen te halen, dan kan dit gebruikt worden in de stemmingsvorming rondom \<PPPP\>. De kans hierop is echter zeer klein.                              |
| Extra kosten                              | ***A*** | B     | C   | D   | E   | Uit een inbreuk op de vertrouwelijkheid is de directe schade gezien de situatie en de maatregelen nihil.                                                                                                                    |
| Aansprakelijkheid                         | **A**   | B     | C   | D   | E   | Gezien de positie van \<PPPP\> is een claim voorvloeiend uit een incident m.b.t. de vertrouwelijkheid zeer klein. In feite vormt alleen PZ hierop een uitzondering. Voorts vormen hardkopies en laptops een beperkt risico. |
| Interne moraal                            | **A**   | B     | C   | D   | E   | Behalve incidenten bij PZ zal de interne moraal niet aangetast worden bij een inbreuk op de vertrouwelijkheid.                                                                                                              |
| Fraude                                    | **A**   | B     | C   | D   | E   | Gezien de hiërarchische opbouw van \<PPPP\> lopen de bedrijfsprocessen van klant tot klant over meerdere afdelingen, zodat de pakkans bij fraude zeer groot is, als het gaat om vertrouwelijkheid.                          |
| Overall Rating                            | A       | **B** | C   | D   | E   |                                                                                                                                                                                                                             |

De risico’s met betrekking tot vertrouwelijkheid zijn zeer gering. Indien de bestaande procedures worden nageleefd, valt in feite iedere inbreuk op de vertrouwelijkheid uit te leggen. Kwetsbaarheden die periodiek gemonitord moeten worden, opdat het beveiligingsniveau wordt gehandhaafd, liggen op de afdelingen:

1. PZ,
2. JZ,
3. ICT
4. Directiesecretariaat.

#### Integriteit

| Gevolgen van inbreuk op de integriteit          | Rating |       |       |     |     | Opmerkingen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|-------------------------------------------------|--------|-------|-------|-----|-----|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Management beslissingen                         | **A**  | B     | C     | D   | E   | Als de uitkomsten van onderzoeken onjuist gecommuniceerd worden, kan dit de juistheid van de beslissingen van klanten beïnvloeden. Intern zijn fiatteringsprocedures aanwezig, waardoor functiescheiding wordt geborgd.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Direct verlies van business                     | **A**  | B     | C     | D   | E   | Niet van toepassing (zie volgende punten)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Fraude                                          | A      | B     | **C** | D   | E   | Het frauderisico is aanzienlijk op afdeling \<QQQQ\>. Dit betreft met name interne medewerkers en kan via functiescheiding geregeld worden, maar het is nog niet volledig duidelijk of deze systematiek ook in bijzondere situaties op de afdeling waterdicht is. Gezien hun bevoegdheden vormen vooral FAB’ers een mogelijk risico. Voorts zijn bestanden op de centrale server benaderbaar via programma’s als Excel. Omdat er een diepgaande kennis aanwezig moet zijn van bestandsstructuren, om deze daadwerkelijk voor dit doel te manipuleren, is het risico beperkt, zeker omdat de pakkans relatief hoog is. Indien het vermoeden toeneemt, dat de continuïteit van \<PPPP\>niet geborgd kan worden, neemt het risico op fraude aanzienlijk toe i.v.m. afnemende loyaliteit. |
| Imago                                           | A      | B     | **C** | D   | E   | Hoewel onderzoeken niet door \<PPPP\> zelf worden uitgevoerd, loopt het als opdrachtgever wel het risico op imagoschade, als het resultaat niet adequaat blijkt te zijn. Persoonlijke deskundigheid van opdrachtgevers dekt dit risico momenteel af, maar dat is geen duurzame oplossing.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Extra kosten                                    | A      | **B** | C     | D   | E   | Kosten kunnen verhaald worden op de toeleveranciers van informatie. Er moet nog gecheckt worden of dit contractueel waterdicht geregeld is. Voorts kan een interpretatiefout bij \<QQQQ\> leiden tot herstelacties.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Aansprakelijkheid                               | A      | B     | **C** | D   | E   | Zie ook vorige punt. Indien echter \<PPPP\> uitgebreid aansprakelijk gesteld wordt voor een incident en \<PPPP\> communiceert niet adequaat, dan kan dat imagoschade opleveren, die de bedrijfscontinuïteit in gevaar brengt. Hiervoor bestaat geen communicatieplan.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Interne moraal                                  | **A**  | B     | C     | D   | E   | De impact van de integriteit op de interne moraal is verwaarloosbaar, gezien andere en veel sterkere prikkels.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Verstoring bedrijfsproces                       | A      | B     | **C** | D   | E   | Dit impact van dit risico is beperkt. In de meeste gevallen zal dit slechts tot dubbel werk leiden. Afdeling \<QQQQ\> is kwetsbaar, als door \<QQQQ\> zelf ontwikkelde programmatuur niet integer blijkt te zijn. Hier is de functiescheiding onvoldoende om dit te borgen, hetgeen nu gecompenseerd wordt door voldoende deskundigheid van de betrokkenen.                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Overall Rating(is gelijk aan de hoogste rating) | A      | B     | **C** | D   | E   | Voor MB moet er een plan komen hoe in de toekomst de functiescheiding geregeld gaat worden. Er moet een communicatieplan komen om escalaties bij incidenten en calamiteiten te voorkomen.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

De risico’s met betrekking tot de integriteit liggen niet zozeer binnen \<PPPP\> zelf, maar omdat het in de keten manager is van het klantorder ontkoppelpunt (KOOP), zal \<PPPP\> bijna per definitie aangewezen worden als de schuldige bij incidenten, zelfs al is \<PPPP\> onschuldig. Zeker in het huidige krachtenveld is dit voor \<PPPP\> een feit, waarmee het moet leren leven. Voorkomen van imagoschade in de vorm van goede procedures in combinatie met een adequaat communicatieplan is cruciaal, want de kosten van het aftimmeren van op zich kleine risico’s bedragen een veelvoud van de eventuele kosten van imagoschade. Bovendien zou dit een investering vergen, waardoor de positie van \<PPPP\> naar de klanten verder wordt verzwakt.

#### Beschikbaarheid

| Gevolgen van inbreuk op beschikbaarheid | Bus. Impact Rating |     |     |     |     | Opmerkingen                                                                                                                                                           |
|-----------------------------------------|--------------------|-----|-----|-----|-----|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                         | 1u                 | 1dg | 3dg | 1wk | 1m  |                                                                                                                                                                       |
| Management beslissingen                 |                    |     |     | X   |     | Managementbeslissingen zijn meestal niet tijd kritisch. Gezien de maximale uitvaltijd van de ICT en thuiswerkplekken is er een verwaarloosbaar risico.                |
| Direct verlies van business             |                    |     |     |     |     | Niet van toepassing als er een BCP is.                                                                                                                                |
| Extern imago                            |                    |     |     | X   |     | Mits er een BCP met een communicatieplan bestaat, is er een verwaarloosbaar risico.                                                                                   |
| Extra kosten                            |                    | X   |     |     |     | Dit betreft alleen het niet productief zijn van het personeel en mogelijk renteverlies bij \<RRRR\>.                                                                  |
| Aansprakelijkheid                       |                    |     |     |     |     | Niet van toepassing. \<PPPP\> sluit geen contracten met harde deadlines.                                                                                              |
| Herstelwerkzaamheden                    |                    |     |     | X   |     | Alleen in geval van calamiteiten (zie BCP).                                                                                                                           |
| Verstoring bedrijfsproces               |                    |     |     | X   |     | De belangrijkste bedrijfsprocessen kunnen vanaf een externe werkplek gecontinueerd worden. Na een week wordt het ontbreken van dossiers en communicatie een probleem. |
| Interne moraal                          |                    |     |     | X   |     | Zie vorige punt                                                                                                                                                       |
| Fraude                                  |                    |     | X   |     |     | Omdat transacties handmatig afgehandeld worden, is controle minder goed mogelijk. Dit mag maximaal 3 dagen stil liggen.                                               |

Gezien het uitwijkplan is het niet beschikbaar zijn van de ICT geen ernstige dreiging. Wel dient er een BCP te komen om te borgen, dat \<PPPP\> snel kan communiceren en binnen een week weer kan functioneren.

#### Conclusies

- Gelet op de uitgangspunten gedefinieerd in het informatiebeveiligingsbeleid, de gegevensclassificatie en de genomen maatregelen doen we de volgende aanbevelingen:
- Een baseline voor informatiebeveiliging geldend voor alle afdelingen, die voldoet aan ISO 17799 en waardoor het nu adequate beveiligingsniveau eenvoudig bewaakt kan worden.
- Vastlegging aanvullende maatregelen voor afdeling \<QQQQ\> om te voldoen aan de normen van externe toezichthouders. Op zich zijn deze (grotendeels) beschikbaar.
- Een tweejaarlijkse toetsing op de handhaving van de maatregelen met betrekking tot de vertrouwelijkheid op de afdelingen PZ, JZ, ICT en het Directiesecretariaat.
- Het onder beheer brengen van de laptops en USB-sticks van de buitendienst. Dit betreft zowel de apparatuur als de data.
- Functiescheiding bij \<QQQQ\> met betrekking tot ontwikkelen en onderhouden van applicaties.
- Auditing van testresultaten op binnen \<PPPP\> ontwikkelde of gewijzigde programmatuur. Dit geldt met name voor applicaties, die buiten de afdeling Automatisering ontwikkeld of onderhouden worden.
- Heldere communicatie over de rol van \<PPPP\> naar klanten, zodat het niet onterecht slachtoffer wordt van incidenten, die buiten zijn invloedssfeer liggen.
- Het uitwijkplan dient tweejaarlijks getest te worden.
- Het BCP dient voltooid te worden inclusief bijlagen (communicatieplan).
- Jaarlijks moet beoordeeld worden of het uitwijkplan en het BCP aanpassingen behoeven vanwege investerings- of wijzigingsvoorstellen.
- Acceptatie van het beperkte risico dat bestanden op de centrale server benaderbaar zijn via Excel.
- Gezien de dreiging voor de bedrijfscontinuïteit is het niet onaannemelijk, dat veel expertise \<PPPP\> in de komende jaren gaat verlaten, waardoor een negatieve spiraal ontstaat en de integriteit van de informatievoorziening onder druk komt te staan. We gaan op dit issue als beveiligingsissue niet verder in.
- Acceptatie van de genoemde risico’s in deze analyse door de directie.

Het spreekt vanzelf, dat niet ieder risico is afgedekt en iedere schade kan worden voorkomen. Ingeschat wordt echter dat met deze aanbevelingen bedrijfseconomisch een optimum bereikt wordt op een niveau dat minimaal marktconform is en waarmee ook voldaan wordt aan ISO 17799.

# Bibliografie

```dataview 
list  "_'" + title + "'_ -  **" + authors  + "(" + year + ")** "  + url + "<br/><br/>"
from "500 Reading notes" AND (outgoing([](Risicomanagement%5D))) sort authors 
```