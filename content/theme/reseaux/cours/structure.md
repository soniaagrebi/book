# Introduction
## Origine d'Internet
Les réseaux de communications existaient déja avant (poste, télégraphe, téléphone), mais ils étaient centralisés. 

Après la 2e guerre mondiale, qui avait vu le nivellement de villes entières par des bombardements aériens (comme à Dresde)
et la bombe atomique, l'armée américaine a décidé de financer le développement d'un réseau de communication décentralisé, qui serait moins vulnérable à une attaque. 

Les universitaires américains ont été associés à la conception de ce réseau et l'ont utilisé pour partager des informations et des ressources entre universités. 

Ainsi est né Internet, par une association entre universitaires attachés surtout à la libre circulation de l'information et des militaires aux visées plutôt sécuritaires. 


## Un réseau décentralisé
Cette section présente une vue d'ensemble de ce qui sera abordé dans ce chapitre.
### Routage
Dans un réseau centralisé comme le téléphone traditionnel, un opérateur central (le standard dans le cas du
téléphone?) relie tous les appareils branchés au réseau. Lorsque deux personnes veulent entrer en 
communication, l'opérateur central les met en relation, c'est-à-dire relie leurs appareils. C'était d'abord 
fait à la main (peut-être montrer un extrait de film dans lequel l'appelant parle à l'opératrice), puis 
automatiquement (avec le téléphone à cadran rotatif). Dans un réseau décentralisé, la mise en lien doit se 
faire de manière décentralisée. C'est ce qu'on appelle le *routage*. (Ajouter une illustration graphique)

### Commutation par paquets
Dans un réseau centralisé comme le téléphone, lorsque deux personne sont en communication, elles "occupent la ligne": ces deux personnes ne sont pas joignables par d'autres personnes (c'est ce qu'indique le signal "occupé"), mais cela n'implique pas d'autres personnes qui veulent communiquer entre elles (sauf si le standard et surchargé). C'est ce qu'on appelle la *commutation de circuits* car un circuit électrique est créé entre les deux appareils qui communiquent. 

Imaginons maintenant qu'une relation soit établie entre deux appareils d'un réseau décentralisé (montrer une
image). Si l'on avait une commutation de circuits, toutes les connexions utilisées pour acheminer
l'information entre deux appareils seraient inutilisables pour les autres personnes utilisatrices du réseaux.
Cela pourrait conduire rapidement à une saturation du réseau. Pour éviter ce problème, il a été décidé de
"découper" la communication en petits morceaux (appelé les paquets) et d'envoyer chaque morceaux
individuellement. C'est ce qu'on appelle la *commutation par paquets*. C'est un peu comme si au téléphone on
raccrochait et on se rappelait entre chaque mot. Cela ne monopolise pas la ligne et permet de mener plusieurs
conversations en même temps sur la même ligne. En plus, cela ne sollicite la ligne que lorsqu'une information
est transmise et par, par exemple, pendant les moments de silence, ou lorsqu'on est en train de rédiger sa
réponse sur une messagerie. 

### Les protocoles
Lorsque deux personnes entrent en communication, elle se mettent d'accord (souvent implicitement) sur la
manière dont elles communiquent, par exemple la langue qu'elles vont utiliser, la manière dont on signifie
la début et la fin d'une conversation (les salutations), etc. Pour les machines, ces règles doivent être
précisées beaucoup plus précisément car les machines n'ont pas la faculté d'interprétation et d'adaptation
des humains. Dans un réseau décentralisé, il faut spécifier quels sont exactement les signaux que doit
envoyer une machine qui veut se connecter au réseau et établir une communication avec une autre machine.
C'est ce qu'on appelle le *protocole de communication*, par exemple comment la machine indique qu'elle veut
établir ou fermer une communication, comment elle indique avec qui elle veut établir une communication, etc.
Il y a pleins de protocoles différents, par exemple le protocole qui régit comment une machine veux se
connecter par wifi à un routeur, le protocole qui régit comment demander le contenu d'une page web à un
serveur, le protocole qui régit comment envoyer un email sur le réseau, ou se connecter à distance sur une
autre machine (mettre les noms?).

(Parler des protocoles ouverts et fermés?)
## Organisation du chapitre
Dans le reste de ce chapitre nous allons aborder plus concrètement les notions décrites ci-dessus et en approfondire certains aspects. Pour illustrer notre propos,
considérons la situation suivante


# Exemple: l'application aux champignons
Imaginons qu'Alice est partie à la cueillette aux champignons dans la forêt.
Elle pense avoir trouvé un beau bolet, mais pour plus de sécurité, consulte
avec son téléphone portable un site web spécialisé dans les champigons de notre région,
*www.champignons.ch*.
 Que se passe-t-il réellement entre derrière l'écran de son téléphone?
 C'est ce que nous allons découvrir dans ce chapitre. 

# Etablir une communication (adressage et routage)
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
- IPv4
- IPv6
- IP statique vs dynamique
- DNS
## La tables de routage
### Routage dynamique

# Envoyer de l'information (paquets et protocoles)
## Le protocole TCP
## Le protocole IP

# Le world wide web
## Le protocole HTTP
## L'URL
## Le langage HTML

# Le modèle en couches
## Introduction
## Exemples







