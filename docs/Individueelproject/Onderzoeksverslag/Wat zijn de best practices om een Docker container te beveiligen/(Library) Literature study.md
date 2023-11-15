In de literatuur studie ga ik kijken naar verschillende bronnen om erachter te komen wat de meest voorkomende best practices zijn.

Vanuit [Container Security Best Practices (tigera.io)] heb ik een lijst opgesteld wat de best practices zijn voor Docker security:
- Avoid Root Permissions

Wat voor mij belangrijk is voor dit onderwerp is dat ik bezig ga met de tool opstellen en dat ik ga checken of de container is gestart als root. Daarnaast als 'Could have' ook functie die het probleem probeert op te lossen. 

- Use Secure Container Registries

Dit kan gecheckt worden, maar gaat wel buiten de scope vallen van mijn project. Aangezien ik een hele tool kan maken op basis van image scanning.

- Limit Resource Usage

Dit is goed om in te stellen, maar kan mogelijk ook juist performance problemen voorzaken als de container veel resources probeert te gebruiken maar niet krijgt. Ik zou de gebruiker wel adviseren om in ieder geval het geheugen gebruik limiet in te stellen. Daarnaast zou ik de CPU resources wel beperken, maar wel schalen op basis van het aantal gebruikers dat gebruik maakt van die container. Anders zou ik de gebruiker aanraden om Docker Swarm te gebruiken of Kubernetes.

- Scan Your Images

Dit onderwerp valt buiten de scope van het project, vanwege tijdsgebrek moet ik keuzes gaan maken wat wel en niet binnen het project gaat vallen.

- Build Your Networks and APIs for Security

Netwerk segmentatie is belangrijk, zodat je container niet de rest van het systeem zomaar kan. Soms wil je dat meerdere docker containers met elkaar gaan praten, dan kun je het beste die containers aan elkaar verbinden via een netwerk. Voor mijn tool wil ik gaan kijken of er überhaupt een ander netwerk gebruikt wordt dan de standaard. Daarnaast kan eventueel gecheckt worden of het netwerk meerdere containers bevat en of dat de bedoeling is.

- Docker Container Monitoring

Ik snap dat dit een essentieel onderdeel is van een security strategie, maar daar zijn al genoeg andere tools voor en valt daarom buiten de scope van dit project.

Wat ik nog aan deze lijst wil toevoegen is dat ik wil gaan kijken of de images die gebruikt zijn door de containers geüpdatet zijn. Als je een nieuwe container aanmaak dan gebruik je een image, maar als je deze container een jaar geleden aangemaakt hebt, dan krijg je uiteindelijk een verouderde image die mogelijk ook weer kwetsbaarheden bevat.

Ook heb ik bij OWASP [Docker Security Cheat Sheet (owasp.org)] gekeken wat de aanbevelingen zijn ten opzichte van Docker Security. 

- RULE #0 - Keep Host and Docker up to date
Om te zorgen dat bekende kwetsbaarheden gedicht worden is het erg belangrijk om te controleren dat Docker up-to-date is. Ik ga proberen om mijn applicatie te laten checken of Docker daadwerkelijk is geüpdatet naar de laatste versie. Dit is niet iets wat je per container kan checken, dus zal ik mijn tool daarvoor anders moeten gaan inrichten.

- RULE #1 - Do not expose the Docker daemon socket (even to the containers)
Dit is een goede regel om te checken per container. Momenteel heb ik wel geïmplementeerd dat wanneer je mijn image in een container draait waarbij je de Docker deamon socket onveilig koppelt de applicatie geen actie uitvoert en een foutmelding weergeeft.

- RULE #2 - Set a user
Dit is al geïmplementeerd en stond ook in de vorige bron. Op dit moment check ik of de root user gebruikt wordt. Als je root gebruikt kan dat ervoor zorgen dat je een kernel attack op de host kan doen.

- RULE #3 - Limit capabilities
Als je de vlag ‘--privileged’ gebruikt tijdens het draaien van de container, dan kan de container alle Linux kernel capabilities gebruiken. Het beste volgens OWASP is om de vlag ‘--cap-drop all’ te gebruiken, maar dan moet je zelf de benodigde capabilities toevoegen door bijvoorbeeld ‘--cap-add CHOWN’ te gebruiken. 

[Docker Security Cheat Sheet (owasp.org)]: https://cheatsheetseries.owasp.org/cheatsheets/Docker_Security_Cheat_Sheet.html
[Container Security Best Practices (tigera.io)]: https://www.tigera.io/learn/guides/container-security-best-practices/docker-security/#6-Docker-Container-Security-Best-Practices

[Snyk: Top 5 Docker Security Vulnerabilities]: https://snyk.io/learn/docker-security/top-5-vulnerabilities/


