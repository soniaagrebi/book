# Paquets et protocoles
(ou comment envoyer de l'information)
## Les paquets
Dès leur origine, les systèmes de communication se sont développés selon deux stratégies distinctes selon les supports utilisés. Soit on maintient un "canal de communication" ouvert par exemple avec le téléphone, la radio ou la télévision traditionnelle. Dans ce cas, le récepteur et l'émetteur entrent en communication et l'information est
envoyées de manière continue de l'émetteur au récepteur. Le récepteur ne peut pas être en communication avec plusieurs émetteurs à la fois. 

Dans les sections ci-dessus, on a évoqué des messages qui étaient envoyés et circulaient dans le réseau.
Cette analogie est pertinente dans le sens que toute information envoyée par internet est découpée en petits
*paquets* qui sont envoyés indépendamment les uns des autres. Ainsi, lorsque le serveur hébergeant le
site www.champignons.ch va envoyer
une image de champignon à Alice, cette image sera découpé en petits paquets qui seront chacuns envoyés séparément à
Alice. Cela a l'avantage qui si, pour une raison ou une autre, une partie de l'image se perd en route, il n'y a pas besoin de renvoyer toute l'image mais uniquement les parties qui se sont perdues. Cela permet aussi à une machine de maintenir plusieurs canaux de communications ouverts simultanément. C'est ce qu'on appelle la *commutation par paquets* parce que ce sont les paquets qui sont adressés individuellement à leur destinataire. A l'inverse, dans le cas du téléphone traditionnel, lorsqu'on appelle quelqu'un, un circuit électrique est établi entre les deux téléphones pour leur permettre de communiquer (à l'exclusion des autres téléphones), c'est ce qu'on appelle la *commutation de circuit*.

Les protocoles IP (Internet Protocol) et TCP (Transmission Control Protocol) décrivent le format ainsi que la gestion
possible de ces paquets. 



## Le protocole IP
L'envoi d'un paquet par la poste suit certaines règles, telles que la position et le format de l'adresse de destination, la position et le format de l'adresse d'expédition, la position du timbre et son montant en fonction du poids et de la destination.. Sans ces règles, l'acheminement du paquet ne peut pas être assuré. De manière analogue l'envoi d'un paquet sur internet doit suivre certaines règles pour être acheminé. C'est le protocole IP qui définit ces règles.

Selon ce protocole un paquet est constitué d'une suite de 0 et de 1 que l'on peut séparer en deux parties. 
1. L'entête qui donne des informations sur le paquet (son émetteur, sa destination, sa taille, etc.)
1. Les données qui forment le contenu du paquet, c'est-à-dire les informations que l'on veut transmettre. 




## Le protocole TCP