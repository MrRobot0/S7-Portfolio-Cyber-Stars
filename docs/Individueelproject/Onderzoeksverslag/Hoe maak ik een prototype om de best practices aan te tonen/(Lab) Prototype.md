Ik kan het onderzoek [[(Showroom) Guideline conformity analysis]] gebruiken om een prototype te maken die de testcases van die deelvraag verifieerd. Deze prototype wordt een proof of principle. Graag wil ik ervoor zorgen dat de testcases allemaal geverifieerd kunnen worden in mijn applicatie.

## Voortgang
Ik ben begonnen met dit project in lesweek 6, hiervoor heb ik mijn onderzoek naar de best practices op het gebied van Docker security afgerond
### Lesweek 6
Dit is de eerste prototype van mijn app. Hier wordt je gegroet met een inlog scherm. Hier geef je de Docker host URL op. 

![[Pasted image 20231026111147.png]]

Er wordt live data gebruikt die rechtstreeks van docker komt. Daarnaast heb ik ook al werkende filters gemaakt, die zie je bovenaan de pagina, elke knop die naast "Refresh" staat is een filter optie. Hiermee kun je bijvoorbeeld alleen de "Failed" en "Exited" testen zien.

![[Pasted image 20231024222430.png]]

Ik heb feedback gevraagd aan een collega die gaf aan dat "Exited" geen goede term is om te gebruiken om aan te geven dat er een fout is ontstaan in de test. Ik ga hier een andere term voor zoeken.

Uiteindelijk besloten om "Invalid" te gebruik als term om aan te geven wanneer een test niet valide is uitgevoerd. Daarnaast zal ik nog in de UI een soort help pagina moeten maken. Daar zal dan uitleg komen over de verschillende termen die gebruikt worden in de app. Hieronder zie je de implementatie hiervan.

![[Pasted image 20231026110434.png]]

### Lesweek 7
Ik streef erna om steeds iteratief de applicatie gebruiksvriendelijker te maken. Het doel is om een professioneel ogende applicatie te ontwikkelen. Deze iteratie heb ik ervoor gezorgd dat de landingspagina gelijk het dashboard is met de testen. Links kun je een nieuwe connectie maken met een andere Docker instantie. En in de sidebar kun je ook filters toepassen. je kan zoeken naar een container en de bestaande filters zijn nu verplaatst naar een logischere locatie volgens mij. Daarnaast heeft de refresh knop een nieuwe locatie rechtsboven gekregen, waar je ook ziet hoeveel containers er totaal getest zijn. Daarnaast kun je ook bij de filters zien hoeveel van die containers een test hebben gehaald, gefaald of niet gelukt zijn om te testen. 

![[Pasted image 20231026115831.png]]

Bij de volgende iteratie wil ik nieuwe testen toevoegen aan de applicatie. Het project kan wat groter worden nu aangezien de planning van dit semester is aangepast dat we nu het hele semester hebben dus nog 10 leswerken ongeveer. Dit was eerst tot en met lesweek 10.
### Lesweek 8
In het begin van deze lesweek ben ik bezig geweest om de user experience te verbeteren. Ik heb een student met domein kennis over docker gevraagd wat die ervan vond en de feedback van hem verwerkt in een Kanban board die ik deze week heb aangemaakt. 

![[Pasted image 20231031230014.png]]

Ook heb ik mijn project op github openbaar gezet. Op deze manier kan iedereen bugs rapporteren. Deze week heeft een vriend van mij al een issue aangemaakt die hij is tegengekomen:

![[Pasted image 20231102143204.png]]
### Lesweek 9
Deze lesweek ben ik terug naar de tekentafel gegaan om meer testen te vinden, ik heb nu twee testen en een volwassen user interface. Maar nu moet ik nog focussen op testen zodat ik de security nog beter kan testen.