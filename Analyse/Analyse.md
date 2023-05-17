# Analyse
## Requirements

Het opstellen van requirements is een cruciale stap bij het starten van alle ICT-projecten. Het helpt bij het duidelijk definiëren van de doelen en verwachtingen van het project, en zorgt ervoor dat alle teamleden en stakeholders een gedeeld begrip hebben van wat er moet worden berijkt. Requirements stellen ons in staat om de projectomvang te bepalen, de taken te plannen en de voortgang te meten.

Bovendien helpt het opstellen van requirements bij het managen van de verwachtingen van stakeholders en zorgt het voor transparantie en verantwoording. Het proces zorgt ervoor dat de behoeften en wensen van alle betrokkenen worden meegenomen en dat deze worden afgestemd op de technische mogelijkheden en beperkingen.

In mijn ervaring met het opstellen van requirements heb ik te maken gehad met verschillende stakeholders, elk met hun eigen perspectieven, prioriteiten en verwachtingen. Het was mijn taak om deze verschillende meningen samen te brengen tot een enkele lijst van requirements. Dit proces was een balans tussen het respecteren van de inbreng van elke stakeholder. Door dit te doen, kon ik helpen bij het creëren van een duidelijke, gedeelde visie voor het project, wat cruciaal is voor het uiteindelijke succes ervan.

| ID    | Description                                                                  | Quality & Constraint                                                                           | Priority |
| ----- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | -------- |
| FR.01 | User is able to view schema.                                                 | Q.01.01 User is able to collapse certain lines for more info.                                  | MUST     |
|       |                                                                              | Q.01.02 User is able to hover mouse over lines for more info.                                  |          |
|       |                                                                              | Q.01.03 Time is shown at the bottom.                                                           |          |
| FR.02 | User is able to create new schema manually.                                  | Q.02.01 User can choose which lines to add.                                                    | MUST     |
|       |                                                                              | Q.02.02 User can adjust all lines.                                                             |          |
|       |                                                                              | Q.02.03 User is able to configurate all lines.                                                 |          |
|       |                                                                              | Q.02.04 User is asked to confirm when leaving without saving.                                  |          |
|       |                                                                              | Q.02.05 User is able to add note with schema.                                                  |          |
|       |                                                                              | C.02.01 User must set a name for the schema.                                                   |          |
|       |                                                                              | C.02.02 Maximum name lenght is 50 characters.                                                  |          |
|       |                                                                              | C.02.03 User must add one ore more lines.                                                      |          |
|       |                                                                              | C.02.04 Maximum note lenght is 500 characters.                                                 |          |
| FR.03 | User is able to change existing schema manually.                             | Q.03.01 User is able to add lines.                                                             | MUST     |
|       |                                                                              | Q.03.02 User is able to adjust all lines.                                                      |          |
|       |                                                                              | Q.03.03 User is able to remove lines.                                                          |          |
|       |                                                                              | Q.03.04 User is able to configurate all lines.                                                 |          |
|       |                                                                              | Q.03.05 User is asked to confirm when leaving without saving.                                  |          |
|       |                                                                              | Q.03.06 User is able to edit note with schema.                                                 |          |
|       |                                                                              | C.03.01 User must leave at least one line.                                                     |          |
|       |                                                                              | C.03.02 User is only able to change manually created schemas.                                  |          |
|       |                                                                              | C.03.03 Maximum note lenght is 500 characters                                                  |          |
| FR.04 | User is able to view and compare multiple schema's.                          | Q.04.01 User is able to change the added schema's                                              | MUST     |
|       |                                                                              | C.04.01 User can only add up to 4 schema's.                                                    |          |
|       |                                                                              | C.04.02 User must select at least 2 schema's.                                                  |          |
| FR.05 | Schema's are automatically generated from real data.                         | Q.05.01 Using an API data is automatically imported.                                           | SHOULD   |
|       |                                                                              | Q.05.02 Schema's are saved automatically with good naming.                                     |          |
|       |                                                                              | Q.05.03 A note explaining that it was automatically generated is added to the schema           |          |
|       |                                                                              | C.05.01 A maximum of 1 schema per day is generated.                                            |          |
|       |                                                                              | C.05.02 The import data function currently only works with the Meggsius Inspect Machine.       |          |
| FR.06 | Schema's can be exported to machine computers.                               | Q.06.01 The machine's behavior changes after exporting the schema.                             | SHOULD   |
|       |                                                                              | Q.06.02 User is asked to confirm when pressing button to export the schema.                    |          |
|       |                                                                              | C.06.01 The export only continues when user confirms.                                          |          |
|       |                                                                              | C.06.02 The export function currently only works on the Meggsius Inspect Machine.              |          |
| FR.07 | User is able to navigate all schema's.                                       | Q.07.01 The difference between automatically generated schema's and manual ones is made clear. | SHOULD   |
|       |                                                                              | Q.07.02 Time of creation of schema's is made clear.                                            |          |
|       |                                                                              | C.07.01 User is only view his schema's and schema's shared to him.                             |          |
|       |                                                                              | C.07.02 Admin is able to view all schema's.                                                    |          |
| FR.08 | Schema's can be exported to a PNG format.                                    | Q.08.01 User is asked to choose between exporting all lines or only the collapsed schema.      | COULD    |
|       |                                                                              | C.08.01 Schema's note is not printed with the PNG.                                             |          |
| FR.09 | Admin is able to delete schema's                                             | Q.09.01 User is asked to confirm his decision to delete schema's.                              | COULD    |
|       |                                                                              | Q.09.02 Deleted schema is moved to deleted folder.                                             |          |
|       |                                                                              | C.09.01 Schema is only deleted when the user confirms.                                         |          |
|       |                                                                              | C.09.02 Automatically generated schema's can not be manually deleted.                          |          |
| FR.10 | Admin is able to restore deleted schema's.                                   | Q.10.01 Admin is asked to confirm his decision to restore schema.                              | COULD    |
|       |                                                                              | C.10.01 Schema is only restored when the admin confirms.                                       |          |
| FR.11 | Deleted schema's are automatically removed.                                  | Q.11.01 Schema is only deleted after one week of being deleted.                                | COULD    |
| FR.12 | User is able to scroll through a timeline with all the schema's for a flock. |                                                                                                | SHOULD   |
| FR.13 | User is able to add schema's to a timeline.                                  |                                                                                                | SHOULD   |
| FR.14 | User is able to remove schema's from a timeline.                             |                                                                                                | SHOULD   |
|       |                                                                              |                                                                                                |          |
|       | FR = Functional Requirement                                                  |                                                                                                |          |
|       | Q = Quality                                                                  |                                                                                                |          |
|       | C = Contraint                                                                |                                                                                                |          |


## User Stories
