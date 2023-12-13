## Root Permissions in Docker
### 1. Privilege Escalation
#### Beschrijving
Containers met root-toegang hebben het potentieel voor privilege-escalatie, waarbij een aanvaller via kwetsbaarheden in de container probeert toegang te krijgen tot het host-systeem.
#### Impact
Volledige controle over het host-systeem kan leiden tot gegevensdiefstal, systeemmanipulatie en andere kwaadaardige activiteiten.
### 2. Verhoogd Aanvalsoppervlak
#### Beschrijving
Root-permissies vergroten het aanvalsoppervlak door aanvallers meer mogelijkheden te geven om kwetsbaarheden te benutten en ongeoorloofde acties uit te voeren.
#### Impact
Toegenomen kans op succesvolle aanvallen, inclusief het omzeilen van beveiligingsmaatregelen.
### 3. Beperkte Isolatie
#### Beschrijving
Containers met root-toegang hebben mogelijk beperkte isolatie van andere containers en het host-systeem, waardoor de impact van potentiële inbreuken kan worden vergroot.
#### Impact
Minder effectieve containerisolatie kan resulteren in grotere schade bij een beveiligingsincident.

## Limit Resource Usage in Docker
### 1. Onvoldoende Resource Controle
#### Beschrijving
Het ontbreken van beperkingen op resourcegebruik binnen Docker-containers kan leiden tot ongewenste situaties waarin een container meer middelen verbruikt dan nodig is.
#### Impact
Overmatig resourcegebruik kan leiden tot verminderde prestaties van andere containers en het host-systeem, wat resulteert in een verminderde algehele systeemstabiliteit.
### 2. Ongeautoriseerde Resource Overname
#### Beschrijving
Zonder adequate beperkingen kan een kwaadaardige container proberen ongeautoriseerd excessief CPU-, geheugen- of opslaggebruik te benutten, wat de beschikbaarheid van resources voor andere containers in gevaar brengt.
#### Impact
Ongeautoriseerde resourceovername kan leiden tot een verstoord operationeel systeem, verminderde prestaties en mogelijke uitval van andere containers.

## Exposing the Docker Daemon Socket

### 1. Ongeautoriseerde Toegang tot Docker Daemon
#### Beschrijving
Het blootstellen van de Docker daemon-socket aan de buitenwereld kan ongeautoriseerde toegang mogelijk maken, waardoor externe gebruikers of kwaadwillende actoren controle kunnen krijgen over Docker-functionaliteiten.
#### Impact
Ongeautoriseerde toegang tot de Docker daemon kan leiden tot het maken, starten en manipuleren van containers, waardoor een potentiële bedreiging ontstaat voor de integriteit van het systeem.

### 2. Mogelijkheid tot Container escaping
#### Beschrijving
Een  Docker daemon-socket die open staat kan fungeren als een potentiële aanvalsvector voor container escaping, waarbij een aanvaller probeert te ontsnappen uit de beperkingen van een container om toegang te krijgen tot het host-systeem.
#### Impact
Containerontsnapping kan leiden tot ongeautoriseerde toegang tot het host-systeem, wat de beveiliging van andere containers en gegevens in gevaar brengt.