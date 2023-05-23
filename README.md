# Portfolio Stage Timo Maas
Vencomatic Group Eersel

## Inhoud
1. [Versiebeheer en Verspreiding](#versiebeheer--verspreiding)
1. [Introductie](#introductie)
2. [Project Beschrijving](#projectbeschrijving)
3. [Processen](#processen)
    - [Analyse](#analyse)
    - [Ontwerp](#ontwerp)
    - [Realisatie](#relalisatie)
4. [Onderzoek](#onderzoek)
5. [Conclusie](#conclusie)
6. [Bijlagen](#bijlagen)

## Versiebeheer & Verspreiding

| Versie | Datum     | Auteur            | Wijzigingen               |
| ------ | --------- | ----------------- | --------------------------|
| 0.1    | 16-5-2023 | Timo Maas         | Opzet document            |
| 1.0    | 19-5-2023 | Timo Maas         | Aanvullen ontwerpdocument |
| 1.1    | 22-5-2023 | Timo Maas         | Aanvullen analysedocument |
| 1.2    | 23-5-2023 | Timo Maas         | Aanvullen realisatie      |
*Versiebeheer*

| Versie | Datum     | Aan                              | Notities                       |
| ------ | --------- | -------------------------------- | ------------------------------ |
| 1.2    | 24-5-2023 | Onno Marsman                     | Exclusief Onderzoek            |
*Verspreiding*

---
## Introductie
Dit verslag is geschreven naar aanleiding van mijn stage bij de Vencomatic Group, een wereldwijde speler in de pluimveesector. Vencomatic Group staat bekend om de vertegenwoordiging van vier grote merken binnen de sector, namelijk Vencomatic, Prinzen, Agro Supply en Van Gent. Door het combineren van deze merken kan Vencomatic Group een volledig assortiment aan innovatieve systemen aanbieden voor de inrichting van moderne pluimveebedrijven wereldwijd.

Met een toegewijd team van ruim 450 medewerkers, lokale vestigingen en een netwerk van meer dan 100 dealers, heeft Vencomatic Group de capaciteit om aan de wensen van duizenden klanten over de hele wereld te voldoen. De organisatie bestaat uit vijf afzonderlijke bedrijven, elk met hun eigen specialiteit: Vencomatic en Van Gent voor duurzame en pluimveevriendelijke huisvestingssystemen, Agro Supply voor klimaatoplossingen, Prinzen voor complete oplossingen voor eierverwerkingsmachines, Rondeel voor duurzame productie van consumptie-eieren en Vencosteel voor productie van eigen staalproducten.

Buiten de hoofdvestiging in Nederland, heeft Vencomatic Group ook vestigingen in Brazilië, China, Spanje en Maleisië. Recentelijk is het bedrijf bezig met een transformatie van haar dienstverlening, na de aankoop van Vencomatic-apparatuur zal er ondersteuning beschikbaar zijn van Vencomatic-medewerkers. Dit verschilt van de eerdere werkwjize, waarbij Vencomatic enkel de machines installeerde zonder extra service te bieden. Om deze dienstverleningsverandering te realiseren, zijn er aanpassingen nodig binnen de online omgeving van Vencomatic.

Tijdens mijn stageperiode was ik actief binnen het R&D Control Technology team, dat verantwoordelijk is voor de ontwikkeling van IT- en OT-producten binnen de Vencomatic Group. Dit verslag biedt een diepgaand overzicht van mijn leerervaringen en bijdragen aan dit team en de organisatie als geheel.

<!-- ![Venco Campus](/Media/venco_campus.jpg) -->

---
## Projectbeschrijving
Op dit moment ervaren Vencomatic medewerkers moeilijkheden bij het verstrekken van advies aan klanten over het verbeteren van hun stal schema's. Het ontbreekt momenteel aan een gebruiksvriendelijke tool om deze schema's duidelijk weer te geven. Bovendien ondervinden boeren problemen bij het controleren van alle computers in hun stal, omdat dit momenteel gebeurt via verschillende computers en met verschillende interfaces. Het is noodzakelijk om een oplossing te ontwikkelen waarmee deze computers via een enkel dashboard kunnen worden beheerd.

Het doel is om een flexibel schema bord te ontwikkelen binnen de webomgeving van Vencomatic. Dit bord moet verschillende schema's kunnen weergeven, zoals lichtschema's en voerschema's in de stallen. Het moet mogelijk zijn om de schema's volledig aan te passen, inclusief de lengtes, tijdstippen en hoeveelheden. Bovendien moeten klanten in staat zijn om schema's in- en uit te kunnen voeren.

De implementatie van dit schema bord biedt een praktische en geïntegreerde oplossing om klanten te ondersteunen bij het optimaliseren van hun stal schema's. Het bevordert communicatie tussen de Vencomatic medewerkers en de klanten, waardoor er verbeteringen kunnen worden doorgevoerd in de pluimveebedrijven.

---
## Processen
### Analyse
Om het project succesvol te starten, is het van belang dat de student een grondige analyse uitvoert om een duidelijk beeld te krijgen van de verwachtingen en vereisten. In dit kader heeft de student waardevolle inzichten verkregen door met beide stakeholders te overleggen en functionele requirements op te stellen. Dit proces stelde hem in staat om de specifieke behoeften en doelstellingen van het project te identificeren.

Daarnaast heeft de student een klein onderzoek uitgevoerd naar de bestaande systemen binnen Vencomatic en de systemen waarmee hij zal werken. Dat onderzoek heeft hem geholpen om een goed begrip te krijgen van de context waarin hij zal opereren en heeft hem in staat gesteld om gerichte oplosingen te ontwikkelen die passen binnen het bestaande systeemlandschap van Vencomatic.

Door deze analyse en het onderzoek naar de bestaande systemen kan de student een stevig fundament leggen voor het project, waarbij hij zowel rekening houd de verwachtingen van de stakeholders als rekening houdt met de bestaande systemen en infrastructuur van Vencomatic. Dit zal bijdragen aan een efficiënte uitvoering van het project.

Voor meer informatie en een lijst met requirements klik [hier](/Analyse/README.md).

### Ontwerp

Een ontwerpdocument is een gestructureerd document dat de blauwdruk vormt voor het ontwikkelen van een ICT-project. Het document bevat gedetailleerde informatie over de architectuur, functionalitei en technische specificaties. Het ontwerpdocument bevat verschillende elementen, waaronder schermschetsen, een database model en een dataflow model. Elk model of heeft een toelichting waarin wordt beschreven hoe de student tot deze uitkomst is gekomen en welke overwegingen hebben geleid tot bepaalde keuzes.

Voor meer informatie over het ontwerp klik [hier](/Ontwerp/README.md).

### Realisatie

#### Uitdagingen

Een van de technische uitdagingen binnen dit project was het dynamisch maken van de volledige pagina. Alles diende aanpasbaar te zijn zonder hardcoded marges of posities. Dit leverde enige complexiteit op vanwege de tijdlijnen. Uiteindelijk zijn er wel oplossingen voor gevonden, waarvan een hieronder word gepresenteerd. Specifiek betreft het hier de achtergrondlijnen in de dagtijdlijn. Deze lopen van 00:00 tot 00:00 de volgende dag, waarbij elk uur een achtergrondlijn moet worden weergegeven. Om dit te bereiken, wordt er 25 keer een berekening uitgevoerd met behulp van een formule in het typescript-bestand om de positie van de achtergrondlijn te bepalen. Deze wordt vervolgens toegepast door een string naar de style property te returnen.

```
<ng-container *ngFor="let index of createRange(25)">
    <div class="backgroundlines">
        <div class="backgroundline" [style]="calculateBackgroundLineLocation(index-1)">
            <span class="time" [innerHTML]="getTimeString(index-1)"></span>
        </div>
    </div>
</ng-container>
```
*schema.component.html*

```
calculateBackgroundLineLocation(rangeNumber): string {
    let percentage = 0;
    percentage += (4.165*rangeNumber);
    return `margin-left: ${percentage}%;`
}

getTimeString(rangeNumber): string {
    return `${this.timeArray24h[rangeNumber]}`
}
```
*schema.component.ts*

Een andere uitdaging binnen het project was het beheer van de verwachtingen van de twee verschillende stakeholders. Deze stakeholders, hoewel zij overeenstemming konden bereiken over de hoofdlijnen van het project, hadden elk hun eigen unieke prioriteiten. Dit resulteerde in een dynamiek waarbij elke stakeholder streefde naar verschillende doelen en prioriteiten.Het balanceren van de uiteenlopende eisen en verwachtingen om beide stakeholders tevreden te houden, vormde een aanzienlijke uitdaging. echter, door open communicatie en strategische planningwerd deze uitdaging aangepakt.

Een bijkomende uitdaging in dit project waren de sprintvergaderingen. In eerste instantie bleek het voor de student een uitdaging om een sprint effectief vooruit te plannen. Het resultaat was dat de ene sprint te weinig taken bevate op het sprintbord, terwijl de andere sprint overvol leek. Deze problematiek kwam voornamelijk door het gebrek aan ervaring van de student met het werken in de gegeven omgeving en met sprintplanning.

Na verloop van tijd verbeterde het echter. Dit was grotendeels te danken aan het toekennen van geschatte uren of punten aan de taken op het sprintbord. Dit hielp de student bij het maken van betere planningen en zorgde voor een meer gebalanceerde verdeling van taken over de sprints. De latere sprints verliepen aanzienlijk beter. De student werd beter in het organiseren en beheren van de taken binnen de sprints, wat resulteerde in efficiëntere en effectievere sprintvergaderingen. De student leerde ook beter inschatten hoeveel tijd of punten aan elke taak moesten worden toegewezen, wat verder bijdroeg aan de verbeterde planning en organisatie.

Hieronder wordt een vergelijking gemaakt tussen het sprintbord van sprint 2 en dat van een latere sprint.

![Sprint 2](/Media/sprint1.PNG)*Sprint 2*
![Sprint 8](/Media/sprint7.PNG)*Sprint 8*

---
## Conclusie



---
## Persoonlijke Reflectie
Voorafgaand aan de stageperiode stelde ik mezelf als doel om veel te leren over werken in een bedrijfsomgeving, omdat dit zo anders is dan op school. Het plannen van meetings, bijhouden van taken en het vragen van hulp aan collega's waren allemaal belangrijke aspecten. In het begin was het zeker wennen. 

Ik merkte ook dat ik moeite had met de achtergrondgeluiden van mensen die aan het praten of typen waren. Na de Covid-periode was ik gewend geraakt aan het werken in mijn eentje, vanuit huis, of op school met oortjes in.  Daarom vond ik het aanpassen aan de nieuwe werkomgeving moeilijk en werd ik snel afgeleid door geluiden, wat resulteerde in het vaak dragen van oortjes. Ik realiseer me nu dat dit moet veranderen wanneer je in een team werkt, niet alleen.

Ik had ook vooraf een persoonlijk doel gesteld: het verbeteren van mijn presentatievaardigheden. Na een feedbacksessie met mijn stagecoördinator, waarbij ik tips kreeg na het geven van mijn eerste stagekring presentatie, heb ik me voorbereid op de volgende stagekring presentatie. Ik heb deze presentatie van tevoren geoefend met een medestudent die veel ervaring heeft met presenteren. Hij heeft me waardevolle tips en suggesties gegeven. Het effect hiervan was direct merkbaar tijdens de stagekring. Iedereen begreep duidelijk wat ik probeerde over te brengen, in tegenstelling tot de eerste keer.

Op dit moment, terwijl ik deze tekst schrijf, heb ik nog niet de presentatie voor de gehele R&D afdeling gehad, wat de presentatie is waar ik het meest tegenop zag. Echter, na het oefenen en het geven van meerdere stagekring presentaties voel ik me veel zelfverzekerder dat ik deze presentatie goed zal gaan.

---
## Bijlagen

[Pluimveeweb - Over Vencomatic](https://www.pluimveeweb.nl/kennispartner/vencomatic/over/)