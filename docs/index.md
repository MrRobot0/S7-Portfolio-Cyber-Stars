## Inleiding
Graag neem ik je mee in mijn Cyber Stars semester. Wat heb ik gedaan om de leeruitkomsten te bewijzen. Op deze pagina leg ik [[Wat is Docker]] uit en wat je moet weten om mijn onderzoek te begrijpen mocht je Docker nog niet kennen. 
## Individuele project
Mijn individuele project gaat over het beveiliging van de infrastructuur, dus meer gericht richting de MKB markt, maar ook juist voor hobbyisten die het leuk vinden om een eigen server te hebben zoals mijzelf. Je denk altijd dat jezelf nooit gehackt gaat worden, maar in tegendeel wordt juist vaak mensen gehackt die niet bewust zijn van hun situatie. Het is een technisch onderwerp, die uitdaging bied om een tool te maken die met veel gebruiksgemak ervoor zorgt dat iemand ervoor kan zorgen dat een container veilig kan draaien. Als een bepaalde container wordt blootgesteld aan een virus dan kan dat op een makkelijke manier opgelost worden. Zonder goede beveiliging van de container kan de virus ook de hoofdserver besmetten. 

Graag verwijs ik je naar mijn onderzoeksverslag over Docker container security. Hier heb ik tooling gemaakt om een container veilig te stellen, en ik heb onderzoek gedaan wat de best practices zijn om een container te beveiligen.
## **_Leeruitkomst 1: Security awareness_**
### Inhoudelijk gesprekspartner
Het is belang dat iedereen op de hoogte is van cybercriminaliteit, wat de risico's zijn en hoe je een cyberaanval voorkomt. 

Het PVO-symposium was een uitstekende gelegenheid voor mij om niet alleen mijn kennis te delen, maar ook om met mensen van diverse achtergronden te praten. Ik nam deel aan gesprekken met professionals uit verschillende vakgebieden, waaronder ICT en beveiliging. Tijdens deze interacties kon ik niet alleen mijn expertise delen, maar ook mijn vermogen tonen om complexe onderwerpen op een begrijpelijke manier uit te leggen aan iedereen in de groep. Bovendien bood het evenement een waardevolle kans om te netwerken en contact te leggen met andere professionals. Ook al waren de meeste mensen ZZP'ers waarbij je niet bijvoorbeeld een stage kan doen, maar mogelijk hebben hun wel connecties om een stage adres te vinden.
### Security awareness
Het groesproject gaat over security awareness te creëren bij particulieren. Wij hebben van Interpolis deze opdracht gekregen om hun te helpen bij security awareness. Op dit moment weet iedereen wel dat het bestaat, maar er worden weinig acties gedaan om preventief een cyberaanval te voorkomen. De fysieke inbraken die beginnen af te nemen volgens Interpolis. De aanvallen via internet nemen juist weer toe. De stijgende lijn van cyberaanvallen komt overeen met de daling van fysieke inbraken.

Ik heb meerdere sessies bijgewoond over cybersecurity. Bij de Symposium samen veilig en weerbaar ondernemen heb ik een sessie bijgewoond over een hack aanval op Xander Koppelmans. Ik had wel een idee wat voor impact een cyberaanval kon hebben, maar dat dit na de hack nog 2 jaar lang gevolgen had voor Xander had ik niet verwacht. De schade na de aanval hadden ze nog kunnen hebben, ook al waren ze veel projecten kwijt, maar het langdurige gevolgen en reputatieschade was de ondergang voor Xander. Hij had een erg goede presentatie over de persoonlijke gevolgen en was zeer transparant in het delen van zijn emotionele en financiele schade. 

Daarnaast heb ik ook een sessie gehad over brandveiligheid, lijkt niet veel te maken te hebben met Cybersecurity, maar in tegendeel kan dit ook erg veel impact hebben op iemand zijn persoonlijke leven en om te zorgen dat je digitale leven op order is door bijvoorbeeld een goed back-up plan te hebben. Fysieke beveiliging gaat soms ten koste van digitale beveiliging. Ik denk dat het een goed leerpunt is om ervoor te zorgen dat je in beide situatie een goed verdediging hebt.

### Kennis en vaardigheden op cybergebied
### Domein specifieke kennis
Mijn domein voor dit semester is container management, het softwarepakket waarbij ik mijn uitzoek in ga uitvoeren is Docker. Hiervoor ga ik een web applicatie maken waarbij het mogelijk is om de security level van je Docker omgeving in te zien. Ik heb wel veel met Docker gewerkt, maar heb nog niet voldoende de security controls toegepast. 

Mijn kennis gebied zit op software gebied en ook op de cybersecurity. Door deze domein specifieke kennis te delen, hoop ik dat ik digitale weerbaarheid kan creëren bij andere. Voor mijn individueel project gebruik ik een combinatie van mijn software kennis met cybersecurity kennis.

Voor mijn individuele project maak ik een tool die ervoor zorgt dat een Docker omgeving goed getest wordt op basis van verschillende best practices. Ik maak bijvoorbeeld gebruik van OWASP best practises op docker gebied om tot een goed advies te komen. De tool kan automatische testen uitvoeren, hierdoor zorg je ervoor dat je zelf fouten kan maken tijdens het draaien van de testen. 

Container management is een groeiende trend. Deze technologie is vrij nieuw in het bedrijfsleven. Het is een beter aanpak als je werkt met microservices bijvoorbeeld. Dit houdt in dat je een grote applicatie opsplitst in allemaal kleine componenten. Als je bijvoorbeeld een grote nieuwssite zoals Tweakers.net pakt dan zou je "Nieuws" en "Reviews" een eigen component kunnen maken. Je ziet nog steeds alle component bij elkaar komen visueel, maar op de achtergrond worden ze gesplitst in meerdere containers. Dit zorgt ervoor als er bijvoorbeeld veel verkeer is op het nieuws gedeelte van Tweakers.net dat je die apart zou kunnen opschalen.
## **_Leeruitkomst 2: Risico's en kansen_**
### Technologie en trends
Tijdens mijn onderzoek over Docker kom je veel nieuwe trends tegen, maar vaak is de beveiliging nog niet goed op orde. Ik wil erop inspelen dat het voor iedereen toegankelijk is om Docker bijvoorbeeld uit te proberen zonder grote risico's te hoef nemen. Door middel van de geautomatiseerde testen kun je ervoor zorgen dat er geen mogelijk beveilgingslekken binnen een omgeving komen. 

Daarnaast heb ik gekeken naar andere trends binnen de containerisation landschap. Je hebt bijvoorbeeld Kubernetes die ongeveer hetzelfde als Docker doet, maar dan is alles meer dynamisch ingesteld. In mijn onderzoek ben ik vaak tegengekomen dat best practises die voor Docker zijn ook toegepast kunnen worden op Kubernetes.

Ik hou me op de hoogte van alle technologieën en trends door nieuwssites te volgen. Hierin kom ik vaak nieuwe trends tegen, die ook effect hebben op de Cyber security tak of Software ontwikkelaar tak.

### Inschatten en voorzien van maatregelen
Mijn plan is om een risicoanalyse te maken voor het beveiligen van een Docker container. Hierin ga ik in op wat de mogelijke risico's zijn, als je bepaalde maatregelen niet neemt tijdens het aanmaken van een Docker container. 

Vervolgens zal ik mijn kennis van veelvoorkomende tools op het gebied van cybersecurity inzetten om de identificeerde risico's in mijn Docker-containeromgeving nauwkeurig te analyseren. Hierbij zal ik gebruikmaken van zowel proactieve als reactieve benaderingen om potentiële bedreigingen te detecteren en te neutraliseren. Een cruciaal onderdeel van mijn aanpak is het regelmatig monitoren van de Docker-container, waarbij ik alert ben op ongebruikelijke activiteiten en verdachte patronen.

Door deze uitgebreide risicoanalyse en de implementatie van passende maatregelen streef ik ernaar een robuuste beveiligingsinfrastructuur te creëren voor mijn Docker-container, waardoor de integriteit, vertrouwelijkheid en beschikbaarheid van de daarin opgeslagen gegevens worden gewaarborgd.
## **_Leeruitkomst 3: Professionaliteit_**
### Responsieve professional
Ik wil wekelijks feedback/ feedforward krijgen van de docenten, zodat mijn belanghebbende op de hoogte zijn waar ik mee bezig ben. Daarnaast zorgt de feedback/ feedforward ervoor dat ik tijdens mijn onderzoek op het goede pad blijf zitten en zodat ik voldoe aan de wensen van de docenten.

Bovendien ben ik proactief in het delen van mijn voortgang en bevindingen, zelfs als er geen specifieke feedbackmomenten zijn gepland. Mijn doel is om een cultuur van transparantie en open communicatie te bevorderen, waardoor alle belanghebbenden op de hoogte blijven van de laatste ontwikkelingen binnen mijn onderzoek. Door regelmatig te checken of mijn doelstellingen nog steeds in lijn zijn met de verwachtingen van de docenten, waarborg ik niet alleen de kwaliteit van mijn werk maar ook een voortdurende afstemming op hun behoeften en prioriteiten
### Ethisch weloverwogen handelen
Binnen mijn werk in cybersecurity is het cruciaal dat ik niet alleen technisch onderlegd ben, maar ook bewust handel met verantwoordelijkheid en ethiek in het achterhoofd. Het gaat niet alleen om het begrijpen van de technische aspecten van digitale veiligheid, maar ook om het besef van de ethische overwegingen bij het beheren van digitale informatie. Ik vind het essentieel om proactief te anticiperen op en te voldoen aan wet- en regelgeving. Het waarborgen van privacygrenzen en het respecteren van geldende juridische kaders zijn voor mij geen alleen ethische plichten, maar vormen ook integrale aspecten van het cybersecurityproces.

Bij het ontdekken van kwetsbaarheden of beveiligingslekken ga ik ethisch te werk door deze informatie te delen met de betrokken partijen voordat ik het publiek informeer. Dit geeft hen de gelegenheid om de problemen op te lossen zonder onnodige blootstelling van kwetsbaarheden.

Ik hou de wet- en regelgeving op het gebied van cybersecurity in de gaten en zorg ervoor dat mijn beveiligingsmaatregelen in overeenstemming zijn met deze voorschriften. Dit omvat bijvoorbeeld naleving van de Algemene Verordening Gegevensbescherming (AVG) of andere relevante wetgeving, afhankelijk van de locatie en het werkterrein.
### Methodisch onderzoek
Ik maak gebruik van het DOT framework. Dit om mijn onderzoek te doen, in deze methode gebruik ik verschillende methodieken zoals "Guideline conformity analysis" en "Prototyping". Deze methodes helpen mij om mijn hoofdvraag te kunnen beantwoorden. Daarnaast zorg ik ervoor dat alle deelvragen nooit afgesloten zijn, maar altijd een aanvulling kunnen krijgen binnen het semester. Op deze manier werkt ik iteratief aan mijn project en kan ik twee wekelijks een demo gegeven van mijn applicatie.

