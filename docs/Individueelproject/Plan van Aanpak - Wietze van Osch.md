## Context
Mijn achtergrond ligt in de software en ook ben ik veel bezig geweest DevSecOps. In dit semester bij Cyber Stars zou ik graag mijn kennis over DevSecOps willen uitbreiden. Voor mijn persoonlijk project pak ik graag een probleem aan die zowel security raakt als operations. Voor dit project is de scope bepaling heel belangrijk aangezien deze tool die ik ga bouwen heel uitgebreid kan gaan worden.
## Probleemstelling
Bij het gebruik van Docker sta je niet zo snel stil bij wat er op de achtergrond gebeurt. Daarnaast gebruik je images van bijvoorbeeld Dockerhub zonder te kijken wat voor pakketten er gebruikt worden in die specifieke image. Deze pakketten kunnen kwetsbaarheden bevatten die al wel bekend zijn, maar de uitgever van de image heeft het nog niet geüpdatet.
## Doelstelling
Mijn doel is om het beveiligen van Docker toegankelijk te maken voor iedereen die Docker wilt gebruiken. Daarnaast wil ik ook de security van de Docker containers zelf verbeteren. Er zijn wel wat best practises beschikbaar hiervoor, maar er is geen makkelijke manier om te checken of al je draaiende containers hier aan voldoen.
## Kennisgebieden
De volgende kennisgebieden worden geraakt met deze opdracht:
- Informatiebeveiliging
Ten eerste verbetert dit product de beveiliging van je Docker-systeem.
- Compliance
Dit product checkt of je voldoet aan de best practises. Daarnaast kan dit product bijdragen aan het aantonen van de eisen van een bepaalde ISO/NEN certificering.
- Software
Dit product wordt zelf ontwikkeld. Software taal wordt nog bepaald. Maar dit zal niet de primaire leerdoel zijn.
## Hoofdvraag
Hoe zorg je ervoor dat je docker systeem veilig is door middel van een zelf geschreven self hosted tool?
## Deelvragen

### Wat zijn de best practices om een Docker container te beveiligen?
- (Showroom) Guideline conformity analysis
- (Library) Literature study
### Hoe maak ik een prototype om de best practices aan te tonen?
- (Workshop) Prototyping
### Is het mogelijk om ISO/NEN eisen te koppelen aan de Docker security best practices?
- (Library) Literature study
### Hoe maak ik een prototype om een image op kwetsbaarheden te controleren?
- (Workshop) Prototyping
## Scope
Deze tool wil ik beperken tot security best practices toepassen op de Docker containers. Hieronder maak ik een Moscow model om aan te geven wat er binnen de scope gaat vallen van dit project.

| Requirement                                                   | MoSCoW |
| ------------------------------------------------------------- | ------ |
|Use best practices to secure a docker container| M      |
| Use ISO/NEN certification and combine with the best practises | S      |
| Deploy container using compose and check for security errors  | C      |
| Root user container one click fix                             | C      |
## Planning

| Lesweek | Onderdeel                                                                                |
| ------- | ---------------------------------------------------------------------------------------- |
| 4       | [[#Wanneer is een Docker image veilig?]]                                                 |
| 5       | [[#Hoe maak ik een prototype om de image kwetsbaarheden te laten zien?]]                 |
| 6       | [[#Hoe maak ik een prototype om de image kwetsbaarheden te laten zien?]]                 |
| 7       | [[#Wat zijn de best practises om een Docker container te beveiligen?]]                   |
| 8       | [[#Is het mogelijk om ISO/NEN eisen te koppelen aan de Docker security best practises?]] |
| 9       | [[#Hoe maak ik een prototype om de best practises aan te tonen?]]                        |
| 10        |[[#Hoe maak ik een prototype om de best practises aan te tonen?]]|


## Vervallen deelvragen
### Wanneer is een Docker image veilig?
- (Lab) Security test
- (Showroom) Guideline conformity analysis
- (Library) Literature study
### Hoe maak ik een prototype om de image kwetsbaarheden te laten zien?
- (Workshop) Prototyping