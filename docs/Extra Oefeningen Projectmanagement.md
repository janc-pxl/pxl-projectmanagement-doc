---
share: true
---
# Extra oefeningen Projectmanagement

![Image|600](https://i.imgur.com/hxGs2TC.jpg)


#### Hogeschool PXL
##### **PXL-Digital** Professionele bachelor in de toegepaste informatica

##### **42TIN1250 Projectmanagement**

##### **Lectoren**
##### Dhr. Lowie Vangaal, Dhr. Jan Castermans

<div style="page-break-after: always;"></div>

## Proloog

![](https://i.imgur.com/KFSuBRb.png)

> [!quote] 
> “Maar deze keer gaan we het ècht goed aanpakken.” 
> -- John Hammond

*John Hammond (CEO InGen) zit in de Mc Donalds te genieten van een lekker menu, samen met Dr. Alan Grant (paleontoloog) , Ian Malcolm (consultant), Dennis Nedry (programmeur) en Ray Arnold (hoofd ingenieur). Ze plannen om opnieuw een park te openen om nieuwe dino’s te kweken en aan een groot publiek te tonen. Met de juiste campagne èn veiligheidsvoorschriften zijn ze er zeker van dat er geen drama’s kunnen voorvallen op het eiland.*

Om de opening van het park goed te organiseren, werken ze eerst een planning uit op een dienblad in de Mc Donalds. 

> [!quote] 
> “Wat kan er fout gaan?” 
> -- Dennis Nedry

## Chapter 1: A new PERT-o-saurus

Terwijl Alan en Ian nog nagenieten van een McFlurry werken Dennis, Ray en John alvast aan een PERT-planning om de doorlooptijd en het kritische pad te berekenen van het nieuwe park.

Alle drie schatten ze per taak in hoelang een taak zal duren. John droomt van snel succes en schat de volledige ontwikkeling zeer optimistisch in (T<sub>o</sub>). Dennis heeft al slechte ervaringen uit zijn eerste Jurassic Park en maakt eerder pessimistische inschattingen (T<sub>p</sub>). Ray is de meest ervaren persoon in het team en schat alle activiteiten in als een goede gemiddelde inschatting (T<sub>l</sub>).

Gebruik de formule uit de cursus voor de T<sub>e</sub> (expected time) te berekenen per taak, behalve bij taak I.

| activiteit | beschrijving               | voorafgaand | John | Ray | Dennis |
| ---------- | -------------------------- | ----------- | ---- | --- | ------ |
| A          | Analyse van het park       | /           | 3    | 5   | 7      |
| B          | Onderzoek naar dino’s      | A           | 3    | 9   | 15     |
| C          | CRISPR DNA                 | A           | 3    | 12  | 18     |
| D          | Ontwikkel website          | A           | 8    | 16  | 24     |
| E          | Incubeer dino’s            | B,C         | 10   | 16  | 22     |
| F          | Bouw infrastructuur eiland | B           | 10   | 20  | 30     |
| G          | Release dino’s in het park | E           | 3    | 4   | 5      |
| H          | Verkoop tickets            | D,F         | 5    | 5   | 5      |
| I          | Veiligheid park testen     |             |      |     |        |

> [!REMARK] Opmerkingen
>  - ingeschatte duur in **weken**
>  - De totale inschatte duur van **activiteit I** bedraagt: 2 weken. Je dient de formule in deze activiteit niet toe te passen.

### Opdracht

- Bereken de T<sub>e</sub> per taak door de formule toe te passen uit de cursus.
- Teken het netwerk en duidt het kritieke pad aan.
- Vermeld in het netwerk de nummers van de activiteiten T<sub>E</sub> en T<sub>L</sub> bij elk knooppunt.

## Chapter 2: The T-rex strikes back

Eénmaal terug aangekomen op Isla Sorna kan John aan de echte planning beginnen van zijn nieuwe eiland. De overige teamleden verkennen ondertussen het eiland en gaan op zoek naar opportuniteiten.  
John opent zijn MS Project Professional 2019 en voert nu de gegevens uit de bespreking in detail op.

### Projectgegevens

Hij noemt het project *“Digisaurus”* en wijzigt de startdatum van het project naar maandag 7 februari 2022. Op deze dag starten de activiteiten.

### Resources & kalender

In het resourceblad neemt hij enkel zijn eigen team in rekening. Materiaal en andere kosten pakt hij niet op in deze fase van de planning.

John Hammond werkt aan een standaard tarief van **€100/uur**. Ian Malcolm aan **€80/uur**, Dennis Nedry aan **€60/u**, Ray Arnold aan **€80/uur** en Alan Grant aan **€50/uur**.

Aan elk van deze resources koppelt hij een nieuwe basis/base kalender= “**Dinosaur power**”.  
De werkdagen starten om **08:00** en eindigen om **17:30**, met dagelijks 90 minuten pauze tussen **12:00** en **13:30**.

De maand **juli** is vakantie voor iedereen. Deze vakantie plan je in onder de kalender ‘Dinosaur power’.  
- Dennis neemt bijkomend verlof op **04 augustus 2022**.  
- Ray neemt bijkomend verlof op **9 augustus 2022**.  

Als overzichtstaak start hij met de concrete uitwerking van de <u>Analysefase</u>:

De eerste taak in deze fase is *"het plan van aanpak"* uitwerken. Deze taak van het type <u>vaste duur</u>, duurt **10 dagen** en alle 5 de teamleden zullen hier aan deelnemen. Zodra het PvA klaar is, start Ray aan de *"risicoanalyse"*, een taak van **10 dagen**. Hij zal John Hammond vragen om hem te helpen bij deze taak zodat deze in de helft van de tijd klaar is. Dennis start op hetzelfde moment al met de *"technische analyse van het park"*. Een taak die hij inschat met een duur van **15 dagen**.

Na de analysefase, volgt de <u>Dinofase</u>:

Ray zal **45 dagen** spenderen aan het *"onderzoek naar dino’s in het park"*. Zodra Ray klaar is met dit onderzoek, kunnen John en Alan samen **100 dagen** werken aan de *"bouw infrastructuur eiland"*. Dennis wacht niet op Ray, John en Alan. Zodra de dinofase start, zal hij *"Crisperen DNA"* van de dino’s. Een taak van **60 dagen** in totaal die hij alleen uitvoert. Zodra Ray klaar is met het onderzoek van de dino’s in het park <u>en</u> Dennis klaar is met het *"Crisperen DNA"*, start Ray met het *"incuberen van dino eitjes"*. Een taak van **80 dagen**. Vervolgens op deze taak, kunnen Dennis en Ray de komende **20 dagen** *"Dino’s releasen op het eiland"*.

In de laatste fase: <u>ontwikkeling website fase</u> voert Ian 3 taken opeenvolgend uit:

Als eerste start hij de *"analyse van de nieuwe website"*. Een taak van **20 dagen**, onmiddellijk na de volledige analysefase. Vervolgens zal hij nog **45 dagen** *"Coderen aan de website"* en *" Testen van de website"*, nog een laatste taak van **15 dagen**.

Twee taken dienen nog uitgevoerd te worden:

- John zal over een periode van **25 dagen** *"Tickets verkopen".* Deze taak kan pas beginnen zodra de <u>dinofase</u> en <u>ontwikkeling website fase</u> zijn afgesloten.
- Dennis en Ray zullen samen **2 dagen** de *"Veiligheid park testen".*

### De opdracht
- Teken de Gantt-chart in MS-Project.
- Voorzie duidelijk de taken, subtaken, milestones met hun duur en volgorde
- Duid het kritieke pad aan
- Ken de taken toe
- Stel de baseline in over het hele project
-   Update het project als op 1 januari 2023
-   Maak een notitie bij de laatste mijlpaal met volgende gegevens:

> [!QUOTE] 
> “Te weinig tijd en zekerheid of er voldoende stroom staat op de schrikdraad. We bekijken dit volgend jaar wel!”

### Extra stappen

Wijzig de duur van *‘Tickets verkopen’* van 25 dagen naar **50 dagen**.  
Wijzig de duur van *‘Veiligheid park testen’* van 2 dagen naar **27 dagen**.

- Open de vergelijkende Gantt diagram
	- Voeg volgende kolommen toe:
		- Afwijking van einddatum *(finish date variance)*
		- % voltooid *(% complete)*
		- Vlag 10
	- Hernoem kolom Vlag 10 naar ‘High Priority task’
        -   Indien het % voltooid werk kleiner of gelijk aan 20% bedraagt, dien je in deze kolom een rode vlag te tonen.
	- Stel een voortgangslijn in op de projectstatus datum.

## Chapter 3: Return of the velociraptor 
![](https://i.imgur.com/iPRUn6W.png)

(Enkel mogelijk na de leerstof kosten-batenanalyse)

Ian twijfelt aan de veiligheid van het park. Maar wie heeft nu tijd voor kwaliteit en veiligheid? Dennis en Ray willen toch liever snel beginnen, want eens het park bezoekers aantrekt, dan komt het geld pas binnen. Dinosaurussen kweken kost nu éénmaal veel geld. Eens er voldoende geld in het laadje binnenstroomt, kunnen zij nog upgrades uitvoeren van het park en de verbetering van het stroomnet.

Voor John het geld gaat besteden aan dit glorieuze project, stelt hij dus een kosten-batenanalyse op. Hij wil graag binnen een periode van 5 jaren uit de kosten zijn.

De huidige **<u>marktrente</u>** bedraagt ‘2,2%’.

Hij schat enkele kosten in als volgende:

### De éénmalige kosten bedragen: 

**Ontwikkelingskosten**: de totale som die je kan aflezen uit je eigen MS Project statistieken:  
![](https://i.imgur.com/m3nU4Bm.png)

### Jaarlijkse kosten van het oude systeem:

- **/** *(Niet van toepassing. Dit project is geheel nieuw en de kosten van het oude systeem bestaan in dit geval niet.)*

### Jaarlijkse kosten van het nieuwe systeem:
- **Onderhoud van het park:** €200.000
- **Onkosten CRISPR onderzoek:** €150.000
- **Medicatie dinosaurussen:** €125.000
- **Transportkosten:** €75.000
- **Reclame en marketingkosten:** €25.000

### Gemiddelde jaarlijks verwachte omzet: 
- **Inkomsten bezoekers:**
	- In het eerste jaar: €1.100.250
	- Vanaf het tweede jaar telkens een stijging van 10% t.o.v. het vorige jaar.

- **Inkomsten subsidies:**
	- In het eerste en tweede jaar: €100.000
	- In het derde en vierde jaar: €85.000
	- In het vijfde jaar: €75.000

### Een alternatieve analyse door Ian Malcolm
Ian laat een kosten- en batenanalyse uitvoeren via outsourcing. Hij vertrouwt het boeltje niet zo.  
Samen met een team van auditeurs stelt hij volgende kosten op.

- **De ontwikkelingskosten:** Deze stijgen met factor 3 en werden zwaar onderschat in de ontwikkeling van het park.
- **Onderhoud van het park:** Deze stijgen met de helft t.o.v.de inschattingen van John.
- **Onkosten CRISPR:** Deze kosten worden 6x hoger ingeschat dan John verwacht.
- De overige inschattingen lijken te kloppen, behalve in het vijfde jaar krijgt het park geen subsidies meer.
- De rente voor deze lening stijgt naar 4,65%.

### De opdracht
Werk de analyses uit in Excel-blad voor de kosten-batenanalyse.

Bereken de terugverdientijd (TVT) en de interne rentabiliteit van het project (IR) voor de analyse van John en Ian.

Motiveer het resultaat van je uitwerking in een lege cel onder je uitwerking:

Is het raadzaam om het project van de bouw van een park uit te voeren. Wanneer ben je uit de kosten? Wat is de rentabiliteit van het project volgens John, en Ian? Of kan je beter je geld beleggen in een ander project, vergeleken met de huidige rentevoet op de bank?

## Chapter 4: The Diplodocus Menace 
![](https://i.imgur.com/IspZZp2.png)

Ian heeft enkele mock-up’s ontworpen voor de nieuwe website. Voordat hij deze website kan ontwikkelen, zal hij een product backlog moeten opstellen. Deze backlog kan hij later gebruiken om de website op een Agile wijze te ontwikkelen.

### De opdracht
- Werk op basis van de screenshot in de opgave <u>5 user stories</u> uit die je in een product backlog kan verwerken. Je mag ook naar de website surfen indien je meer detail wil hebben en inspiratie wil opdoen.
- Let er op dat de 5 user stories <u>SMART</u> gedefinieerd zijn.

*Je hoeft geen storypoints of prioriteiten toe te kennen aan de stories.  
Fit criteria en extra informatie is niet nodig. Enkel de beschrijving van de stories zijn voldoende.*

- De opdracht mag je uitwerking in een Word-document of een ander tekstbestand.
