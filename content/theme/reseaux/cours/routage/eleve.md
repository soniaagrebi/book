# Le routage ou comment acheminer l'information
Nous avons vu précédemment, comment il est possible d'identifier sur internet
une machine avec laquelle on souhaite communiquer, en ayant recours à son
adresse IP ou un nom de domaine. Contrairement à un système centralisé comme
le téléphone, où un opérateur va mettre directement en relation les deux
machines qui communiquent, sur internet l'acheminement de l'information d'une
machine à une autre se fait de manière décentralisée. C'est le problème du
*routage*, c'est-à-dire quel chemin (ou quelle route) l'information va emprunter pour
aller d'un point à l'autre du réseau. [ajouter une illustration]

## Les routeurs    
Les *routeurs* sont des ordinateurs spécialisés dont le rôle est de relayer
et d'orienter correctement les informations qui circulent sur internet. Si
internet est représenté par un graphe dont les arêtes représentent les canaux
de communication, alors les routeurs sont situé aux noeuds du graphes et
décident dans quelle direction faire suivre une information afin qu'elle atteigne
son destinataire. Les routeurs sont donc comme des facteurs
disposés aux intersections du réseau internet qui vont lire la destination des
messages qui leur arrivent et les rediriger vers la prochaine intersection
de manière à les rapprocher de leur distination. [ajouter une illustration]
Pour ceci, les routeurs s'aident de *tables de routage* qui leur indique la
direction à suivre pour chaque destination. 
        
## Les tables de routage
Une table de routage est un tableau qui indique dans quelle direction orienter
un message en fonction de son destinataire. Ainsi la première colonne contient
l'adresse IP de destinatation, la seconde l'interface à laquelle il faut envoyer
les message destiné à cette adresse. [donner le détail du format des tables de routage ?]
Afin de ne pas avoir à conserver en
mémoire une ligne par destinataire possible, elle utilise les masques de
Dans des petits réseaux locaux, cette table de routage peut être construite
manuellement
    
## Le routage dynamique
Dans la pratique, le réseau de connections qui constitute Internet change et
évolue constamment: des nouvelles machines se connectent au réseau, changent
d'adresse IP, des
routeurs tombent en panne, certaines
connexion s'ajoutent ou disparaissen, par exemple en cas de dommages aux
cables. Cela ne serait pas gérable pour des humains de constamment mettre à
jour les tables de routage pour les adapter à la configuration du réseau.
C'est pourquoi un système automatisé de mise à jour des tables de routage
est utilisé. C'est ce qu'on appelle le *routage dyamique*.
    [ qui permet non
seulement de gérer les changement configuration du réseau, mais également les
phénomènes de congestion?]   
