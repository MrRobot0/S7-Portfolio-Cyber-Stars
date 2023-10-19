Het doel van dit onderzoek is dat ik een goed beeld krijgt wat mijn tool zou moeten afchecken tijdens de security evaluatie. Op basis van de literatuurstudie maak ik testcases om de security maatregelen te kunnen verifiëren. 
#### Check for root container
Benodigdheden:
- Naam of id van de container die gecheckt moet worden (vervang "container_name" hiermee)

| Step | Action                                                         | Expected result                              |
| ---- | -------------------------------------------------------------- | -------------------------------------------- |
| 1    | docker inspect --format '{{.Config.User}}' "container_name"  | Mag niet "0:0" of "root" zijn                |
| 2    | docker inspect --format '{{.Config.Image}}' "container_name" | Naam van de gebruikte image ("image_naam") |
| 3    | docker inspect --format '{{.Config.User}}' "image_naam"      | Mag niet "0:0" of "root" zijn                |

#### Limit Resource Usage
Benodigdheden: 
- Naam of id van de container die gecheckt moet worden (vervang "container_name" hiermee)
- Aantal gigabyte ram die de container mag gebruiken (vervang "memory" hiermee)
- Aantal processor cores die gebruikt mag worden (vervang "cpu_cores" hiermee)

| Step | Action                                                                     | Expected result                           |
| ---- | -------------------------------------------------------------------------- | ----------------------------------------- |
| 1    | docker update --memory "memory" --cpuset-cpus "cpu_cores" "container_name" | Container is geüpdatet met nieuwe limieten |

#### Check for default network
Benodigdheden:
- Naam of id van de container die gecheckt moet worden (vervang "container_name" hiermee)

| Step | Action                                                                   | Expected result                    |
| ---- | ------------------------------------------------------------------------ | ---------------------------------- |
| 1    | docker inspect --format '{{.NetworkSettings.Networks}}' "container_name" | Should not return "bridge" network |
