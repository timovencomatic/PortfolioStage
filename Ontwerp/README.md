# Ontwerpdocument
## Inhoud
1. [Introductie](#introductie)
2. [Schermschets](#schermschets)
3. [Database Model](#database-model)
4. [Dataflow](#dataflow)
5. [Conclusie](#conclusie)

---
## Introductie
Een ontwerpdocument is een gestructureerd document dat de blauwdruk vormt voor het ontwikkelen van een ICT-project. Het document bevat gedetailleerde informatie over de architectuur, functionalitei en technische specificaties. Het ontwerpdocument bevat verschillende elementen, waaronder schermschetsen, een database model en een dataflow model. Elk model of heeft een toelichting waarin wordt beschreven hoe de student tot deze uitkomst is gekomen en welke overwegingen hebben geleid tot bepaalde keuzes.

---
## Schermschets
De student heeft een gedetailleerde schermschets gemaakt, die tijdens de realisatiefase diende als waardevolle inspiratiebron. Deze schermschets is ontwikkeld op basis van de [requirments](/Analyse/README.md/#requirements) die in samenwerking met de stakeholders zijn opgesteld. Door middel van samenwerking en verschillende iteraties, kon de student de schermschets aanpassen om zo aan alle eisen te voldoen die door de stakeholders waren opgesteld.

Uiteindelijk resulteerde dat proces in een schermschets die alle gewenste functionaliteiten en ontwerpelementen bevat, zoals overeengekomen met de stakeholders. Deze schermschets diende al seen leidraad tijdens de realisatiefase van het project, waarbij het de student streefde om een appllicatie te creëren die nauwkeurig overeenkwam met de initiële visie en vereisten.

Voor het maken van de schermschets heeft de student [Figma](www.figma.com) gebruikt. [Figma](www.figma.com) is een handige tool die er voor zorgt dat de schermschets er proffesioneel uitziet, hierdoor komt de schets zo dicht mogelijk bij het gewenste resultaat.

![Schermschets](/Media/scherm_schets_edit.png)*[SchemaEditView.fig](/Ontwerp/SchemaEditView.fig)*

### Schermschets Stakeholder

Voorafgaand aan het starten van de schermschets, had een van de stakeholders al een conceptuele schets gemaakt van hoe hij zich het scherm van de applicatie voorstelde. Deze schets werd later een waardevolle bron van inspiratie te zijn bij het creëren van de student's eigen schermschets.

De schets van de stakeholder bood inzicht in de gewenste lay-out, functionaliteiten en visuele elementen van het scherm. Door voort te bouwen op het concept van de stakeholder kon de student een schermschets ontwikkelen die trouw bleef aan de ideeën van de stakeholder, terwijl er ook ruimte was voor eigen creatieve input en expertise. Hierdoor werd een evenwicht bereikt tussen de verwachtingen van de stakeholder en de inzichten van de student.

![Schermschets Stakeholder](/Media/scherm_schets_analyse.png)

---
## Database Model
"Een datamodel laat de logische structuur van een database zien, inclusief de relaties en beperkingen die bepalen hoe gegevens opgeslagen en toegankelijk gemaakt kunnen worden. Een individuele database model wordt ontworpen op basis van de regels en concepten van een meer uitgebreid datamodel dat een ontwerper uitkiest om mee te werken." ([lucidchart.com](#bronnen))


Een voorbeeld hiervan is het gebruik van language keys. Aangezien de applicatie die word ontwikkeld beschikbaar moet zijn in verschillende talen word er een language key opgeslagen in de database. Door de samenwerking met collega's is dat meteen vanaf het begin toegevoegd, hierdoor was het toevoegen van vertalingen later gemakkelijk.

![Database Model](/Media/database_model.png)*[DatabaseDiagram.drawio](/Ontwerp/DatabaseDiagram.drawio)*

---
## Dataflow
"Een gegevensstroomdiagram (DFD) brengt de gegevensstroom van een proces of systeem in beeld. Het is de meest gebruikte vorm om duidelijk te maken hoe de processen binnen een systeem zich afspelen."([ictportal.nl](#bronnen))

In het onderstaande dataflow model is vastgesteld waar de data die door de applicatie gaat vandaan komt en waar deze naartoe gaat. Het project heeft de naam "Timetable" gekregen. Hoewel het model verschillende elementen bevat die buiten de scope van het project vallen, zoals het automatisch importeren en exporteren van data uit verschillende klimaatcomputers, is het voornamelijk ontwikkeld met het oog op de toekomst. Het doel is namelijk dat na de stageperiode iemand anders doorgaat met de ontwikkeling van deze applicatie.

![Dataflow](/Media/dataflow.png)*[DataFlow.drawio](/Ontwerp/DataFlow.drawio)*

---
## Conclusie

## Bronnen
[ZuciSystems - Een Softwareontwerpdocument Maken](https://www.zucisystems.com/nl/blog/een-softwareontwerpdocument-maken/)

[Lucidchart - Wat is een datamodel?](https://www.lucidchart.com/pages/nl/wat-is-een-datamodel)

[ICTPortal - Wat is een gegevensstroomdiagram?](https://www.ictportal.nl/ict-lexicon/data-flow-diagram-dfd)

