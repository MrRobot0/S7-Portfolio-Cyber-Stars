Ik kan het onderzoek [[(Showroom) Guideline conformity analysis]] gebruiken om een prototype te maken die de testcases van die deelvraag verifieerd. Deze prototype wordt een proof of principle. Graag wil ik ervoor zorgen dat de testcases allemaal geverifieerd kunnen worden in mijn applicatie.

Dit is de eerste prototype van mijn app. Ik gebruik hierin al live data die rechtstreeks van docker komt. Daarnaast heb ik ook al werkende filters gemaakt, die zie je bovenaan de pagina, elke knop die naast "Refresh" staat is een filter optie. Hiermee kun je bijvoorbeeld alleen de "Failed" en "Exited" testen zien.

![[Pasted image 20231024222430.png]]

Ik heb feedback gevraagd aan een collega die gaf aan dat "Exited" geen goede term is om te gebruiken om aan te geven dat er een fout is ontstaan in de test. Ik ga hier een andere term voor zoeken.

Uiteindelijk besloten om "Invalid" te gebruik als term om aan te geven wanneer een test niet valide is uitgevoerd. Daarnaast zal ik nog in de UI een soort help pagina moeten maken. Daar zal dan uitleg komen over de verschillende termen die gebruikt worden in de app. Hieronder zie je de implementatie hiervan.

![[Pasted image 20231026110434.png]]


