## Inleiding
Graag neem ik je mee in mijn Cyber Stars semester. Wat heb ik gedaan om de leeruitkomsten te bewijzen. Ik leg in het kopje "Wat is Docker" uit wat je moet weten om mijn onderzoek te begrijpen mocht je Docker nog niet kennen. 
## Wat is Docker
We beginnen met het uitleggen wat überhaupt virtualisatie is. Een server representeert een grote kubus. In deze kubus zitten mini servers die representeren een mini kubus in de grote kubus. In het volgende diagram kun je zien hoe dat eruit ziet:

![[KubusUitleg.png]]

Het begint allemaal met virtualisatie, eerst hadden we een fysieke server per doeleinde. Omdat de hardware nu geen probleem meer is gebruiken we een fysieke servers waarop we mini servers draaien. Om het zelf in beheer te houden veel onderhoud kost, zijn we over naar Infrastructure as a Service. Zelf een server beheren koste veel geld als het fout ging. Het is nu leuk om een kleine server te draaien voor thuisgebruik of voor de MKB markt. Door IaaS te gebruiken leggen we het risico van de hoofdserver te draaien bij de hosting partij.

Docker is een softwarepakket om applicaties gecontaineriseerd te maken. Een container is een mini server die geïsoleerd zou moeten draaien van de hoofdserver. Dit is dus niet altijd het geval en hier gaat mijn onderzoek over. Hoe kun je daadwerkelijk een container veilig draaien op de hoofdserver. Zonder dat de hoofdserver gecompromitteerd raakt.
## **_Leeruitkomst 1: Security awareness_**
Het is belang dat iedereen op de hoogte is van cybercriminaliteit, wat de risico's zijn en hoe voorkom je een cyberaanval. 

Mijn individuele project gaat over het beveiliging van de infrastructuur, dus meer gericht richting de MKB markt. Het is een technisch onderwerp, die uitdaging bied om een tool te maken die met veel gebruiksgemak ervoor zorgt dat iemand ervoor kan zorgen dat een container veilig kan draaien. Als een bepaalde container wordt blootgesteld aan een virus dan kan dat op een makkelijke manier opgelost worden. Zonder goede beveiliging van de container kan de virus ook de hoofdserver besmetten. Mijn kennis gebied zit op software gebied en ook op de cybersecurity. Door deze domein specifieke kennis te delen, hoop ik dat ik digitale weerbaarheid kan creëren bij het MKB en particulieren. 

Graag verwijs ik je naar mijn onderzoeksverslag over Docker container security. Hier heb ik tooling gemaakt om een container veilig te stellen, en ik heb onderzoek gedaan wat de best practices zijn om een container te beveiligen.

Het groesproject gaat over security awareness te creëren bij particulieren. Wij hebben van Interpolis deze opdracht gekregen om hun te helpen bij security awareness. Op dit moment weet iedereen wel dat het bestaat, maar er worden weinig acties gedaan om preventief een cyberaanval te voorkomen. De fysieke inbraken die beginnen af te nemen volgens Interpolis. De aanvallen via internet nemen juist weer toe. De stijgende lijn van cyberaanvallen komt overeen met de daling van fysieke inbraken.

Graag verwijs ik je naar het adviesrapport dat we hebben gemaakt voor Interpolis. Om een te begrijpen wat het proces was van dit adviesrapport verwijs ik je naar ons onderzoeksverslag die we gedaan te hebben om tot dit eindproduct te komen.
## **_Leeruitkomst 2: Risico's en kansen_**
Container management is een groeiende trend. Deze technologie is vrij nieuw in het bedrijfsleven. Het is een beter aanpak als je werkt met microservices bijvoorbeeld. Dit houdt in dat je een grote applicatie opsplitst in allemaal kleine componenten. Als je bijvoorbeeld een grote nieuwssite zoals Tweakers.net pakt dan zou je "Nieuws" en "Reviews" een eigen component kunnen maken. Je ziet nog steeds alle component bij elkaar komen visueel, maar op de achtergrond worden ze gesplitst in meerdere containers. Dit zorgt ervoor als er bijvoorbeeld veel verkeer is op het nieuws gedeelte van Tweakers.net dat je die apart zou kunnen opschalen.

Mijn plan is om een risicoanalyse te maken voor het beveiligen van een Docker container. Hierin ga ik in op wat de mogelijke risico's zijn, als je bepaalde maatregelen niet neemt tijdens het aanmaken van een Docker container. 
## **_Leeruitkomst 3: Professionaliteit_**
Ik maak gebruik van het DOT framework. Dit om mijn onderzoek te doen, in deze methode gebruik ik verschillende methodieken zoals "Guideline conformity analysis" en "Prototyping". Deze methodes helpen mij om mijn hoofdvraag te kunnen beantwoorden.

Mijn domein voor dit semester is container management, het softwarepakket waarbij ik mijn uitzoek in ga uitvoeren is Docker. Hiervoor ga ik een web applicatie maken waarbij het mogelijk is om de security level van je Docker omgeving in te zien.

Ik wil wekelijks feedback/ feedforward krijgen van de docenten, zodat mijn belanghebbende op de hoogte zijn waar ik mee bezig ben. Daarnaast zorgt de feedback/ feedforward ervoor dat ik tijdens mijn onderzoek op het goede pad blijf zitten en zodat ik voldoe aan de wensen van de docenten.