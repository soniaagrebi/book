# Adressage
## Les noms de domaine
Le nom *champignons.ch* est ce qu'on appelle un *nom de domaine*.
Les noms de domaines sont gérés par l'ICANN, une organisation non gouvernementale à but non lucratif
basée aux Etats-Unis dont la fonction principale est la gestions de l'adressage sur Internet.
Les noms de domaines sont gérés de manière hierarchique, selon le
*nom de domaine de premier niveau*, c'est à dire la "terminaison" de l'adresse (*.ch*, *.org*, *.fr*, etc.)Ainsi la gestion des adresses en *.ch* est confiée à Switch, une fondation suisse dont c'est le rôle principal.La personne qui a créé le site *champignons.ch* a donc
réservé ce nom de domaine auprès de Switch (en passant par un intermédiaire) et peut le conserver moyennant un paiement d'environ CHF 15.- par an.     
[Faire un encadré sur l'internationalisation des noms de domaines, et les controverses (.sucks)? ]

Si les noms de domaines sont pratiques pour désigner des adresses sur internet, les machines, elles, utilisent des nombres pour référencer les machines
connectées à Internet, c'est ce qu'on appelles les *adresses IP*. Ainsi, la personne qui a enregistré le site *champignons.ch* a également reçu une (ou plusieurs)
adresses IP de la part de Switch ou d'un intermédiaire. 

[Ajouter une illustration de la gestion des nom de domaines? ]
    
Exercice: déterminer à l'aide du site web https://www.nic.ch/whois/ qui a enregistré le nom de domaine champignons.ch. 

## Les adresses IP
### IPv4
Afin de pouvoir identifier chacune des machines connectées à Internet, il a été décidé de leur attribuer à chacune un nombre de 32 bits, c'est-à-dire entre 0 et 2^32-1=4'294'967'295 (4 millards 294 millons 967 mille 295). On pensait alors (c'était en 1982) que ce serait amplement suffisant pour pouvoir accomoder toutes les machines et qu'Internet ne dépasserait pas les 4 millards de machines connectées. [dire combien il y en avait à l'époque].
Afin de rendre ces adresses plus lisibles pour les humains, on décompose d'habitude une adresse IP de 32 bits en quatre groupes de 8 bits séparés par un point. Chaque groupe de 8 bits peut alors être représenté comme un nombre entre 0 et 2^8-1 = 255. 

Exemple:

L'adresse 010100101010... sera décrite comme 128.233.53.23. 

Question:
Lesquelles des adresses suivantes sont des adresses IP valides:

### Blocs et masques ?

### Gouvernance
Comme les noms de domaine, les adresses IP sont gérée hiérarchiquement. Ainsi, les adresses de la forme 
46.x.x.x (c'est-à-dire celles qui commencent par 46 = 00101110) sont assignées au Centre de Coordination Européeen qui les répartis entre différents *Registres Internet locaux* tels que Switch qui va pouvoir louer une partie de ces adresses IP à des organisations, des entreprises ou des particuliers qui en feraient la demande. 

Certains blocs d'adresses IP sont réservés à des usages particuliers. Par exemple les adresses 10.x.x.x sont réservées aux réseaux privés, c'est-à-dire des machines qui ne communiquent pas directement avec le reste d'internet. 

Exercices:
- Parmi les adresses suivantes, indiquer lesquelles sont au format IPv4, lesquelles sont IPv6 et lesquelles ne sont pas valides. 
- 

### IPv6




- IP statique vs dynamique
- DNS