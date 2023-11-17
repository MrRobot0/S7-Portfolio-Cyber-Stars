We beginnen met het uitleggen wat überhaupt virtualisatie is. Een hoofdserver representeert een grote kubus. In deze kubus zitten mini servers die representeren een mini kubus in de grote kubus. In het volgende diagram kun je zien hoe dat eruit ziet:

![[KubusUitleg.png]]

Het begint allemaal met virtualisatie, eerst hadden we een fysieke server per doeleinde. Omdat de hardware nu geen probleem meer is gebruiken we een fysieke servers waarop we mini servers draaien. Om het zelf in beheer te houden veel onderhoud kost, zijn we over naar Infrastructure as a Service. Zelf een server beheren koste veel geld als het fout ging. Het is nu leuk om een kleine server te draaien voor thuisgebruik of voor de MKB markt. Door IaaS te gebruiken leggen we het risico van de hoofdserver te draaien bij de hosting partij.

Docker is een softwarepakket om applicaties gecontaineriseerd te maken. Een container is een mini server die geïsoleerd zou moeten draaien van de hoofdserver. Dit is dus niet altijd het geval en hier gaat mijn onderzoek over. Hoe kun je daadwerkelijk een container veilig draaien op de hoofdserver. Zonder dat de hoofdserver gecompromitteerd raakt.