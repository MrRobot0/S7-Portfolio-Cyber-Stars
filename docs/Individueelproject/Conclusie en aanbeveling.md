## Conclusie
Mijn hoofdvraag 'Hoe zorg je ervoor dat je docker containers veilig zijn door het gebruik middel van tool?' is succesvol beantwoord, aangezien er maatregelen genomen zijn om de Docker-omgeving veilig te maken, door de OWASP en Tigera Docker beveiligingsrichtlijnen toe te passen. 

Het prototype dat ik heb ontwikkeld, is effectief in het testen van deze beveiligingsmaatregelen. Hierdoor is het mogelijk om consistent alle beveiligingsrichtlijnen te controleren.

Hoewel ik ISO/NEN normen heb gekoppeld, moet ik opmerken dat deze normen algemeen zijn en niet specifiek gericht zijn op de beveiliging van Docker containers. Voor de toekomst is het belangrijk om te overwegen specifieke normen voor containerbeveiliging te implementeren, mochten die er komen.

Ik kreeg positieve feedback van SUE, wat aangeeft dat er potentieel is voor verdere ontwikkeling en implementatie van het project. Door het project open source te maken, wil ik anderen de kans geven om bij te dragen en te profiteren van de ontwikkelingen. Hierdoor is het ook mogelijk dat andere mijn code kunnen bekijken om te zien of er mogelijk een beveiligingslek in de applicatie voorkomt. Daarnaast zal er actief gehandeld gaan worden om de applicatie zoveel mogelijk up-to-date te houden met de laatste pakketten die gebruikt worden in de applicatie.

Mijn presentatie aan de klas verliep soepel, waarbij ik vragen goed kon beantwoorden. Mijn project heeft niet alleen de Docker-omgeving veilig gemaakt, maar heeft het ook erkenning gekregen van SUE en een basis gelegd voor samenwerking met anderen door het open source te maken.
## Aanbeveling
### Mogelijke nieuwe functies
- Verder uitbreiden van de testen, er zijn nu 4 testsoort geïmplementeerd, dit zou in de toekomst een stuk meer kunnen zijn.
- Ondersteuning voor Kubernetes en andere container engines
- Koppeling met monitoring systeem
- API koppeling om data uit te lezen
- Rapport genereren
- Testen automatisch laten draaien op basis van een schema
### Toelichting van nieuwe functies
- Het plan is om de testen verder uit te breiden. Momenteel zijn er 4 soorten testen geïmplementeerd, maar er wordt overwogen om dit aantal in de toekomst aanzienlijk te verhogen, zodat er meer beveiligingsrichtlijnen gecontroleerd kunnen worden.
- Er kan ook nog worden gewerkt aan de ondersteuning voor Kubernetes en andere container engines. Dit stelt het systeem in staat om ook te werken in andere containeromgevingen, wat de flexibiliteit en schaalbaarheid ten goede zal komen.
- Een belangrijk nieuwe functie is de koppeling met een monitoring systeem. Hierdoor kan er real-time inzicht krijgen in de status van de systemen door het uitvoeren van testen, waardoor eventuele nieuwe problemen snel kunnen worden geïdentificeerd en aangepakt.
- Om de verzamelde gegevens toegankelijk te maken, kan er gewerkt worden aan een API koppeling. Hiermee kunnen gebruikers eenvoudig relevante data uitlezen en integreren met andere systemen of tools.
- Een functionaliteit waar ook gewerkt aan kan worden is het genereren van rapporten. Hiermee kunnen gebruikers overzichtelijke rapporten ontvangen over de uitgevoerde testen, inclusief gedetailleerde resultaten en analyses.
- Om het proces verder te automatiseren, kan er gewerkt worden aan een schema gebaseerde testen uitvoering. Dit stelt gebruikers in staat om tests op een vooraf bepaald schema te laten draaien, waardoor regelmatige en geplande testuitvoeringen mogelijk zijn zonder handmatige tussenkomst. Waarbij er ook weer een rapport kan worden gegeneerd met de verschillen van de vorige keer dat de test gedraaid heeft.

Zo zijn er nog talloze functies te bedenken, maar dit zal afhangen van wat de gebruikers echt missen in de applicatie en of er genoeg mensen zijn die hiervoor tijd willen vrijmaken om hieraan te werken. Als er meerdere mensen kunnen bijdragen aan de applicatie zullen de meeste functies al snel geïmplementeerd kunnen zijn. 