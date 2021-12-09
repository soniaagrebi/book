# Conception d'images dans un éditeur hexadécimal

## Introduction

Cette activité, prévue pour deux périodes de 45 minutes en salle d'informatique, tourne autour de la conception d'images au format `BMP`.
La manipulation des images se fait au travers d'un éditeur hexadécimal et ne demande pas de connaissances en programmation.

## Contexte disciplinaire

Cette activité s'inscrit dans le cadre de la thématique "représentation de l'information".
L'activité a peu de prérequis:
- La notion de bit et d'octet.
- Les fichiers en tant que séquences d'octets.

Il est à noter que l'activité n'implique pas de programmation de la part des élèves et peut donc être entreprise par des classes qui n'auraient pas encore abordé cette thématique.

## Objectifs pédagogiques

L'objectif général de la leçon est que les élèves soient capables de concevoir des fichiers au travers d'un éditeur hexadécimal et en suivant un format de données spécifié.

Les objectifs spécifiques sont les suivants:
- Les élèves sont capables d'expliquer que les fichiers, peu importe leur type, sont constitués de séquences de bits regroupés en octets.
- Les élèves sont capables de lire et d'écrire des octets en notation hexadécimale.
- Les élèves sont capables de concevoir des images au format `BMP` étant donné un fichier modèle.
- Les élèves sont capables de déchiffrer des couleurs exprimées au format `BGR` / `RGB`.
- Les élèves sont capables d'expliquer les principes généraux de la compression de données sans pertes.
- Les élèves sont capables de concevoir des images au format `BMP` utilisant une palette de couleur étant donné un fichier modèle. 

## Matériel

### Éditeur

Cette activité nécessite l'usage par les élèves d'un éditeur hexadécimal.
D'expérience, nous conseillons l'éditeur [Hexed.it](https://hexed.it), une application web qui ne nécessite aucune installation.

Il existe d'autres solutions, notamment l'éditeur [Hex Fiend](https://hexfiend.com/) sur Mac OS X, qui offre une interface minimaliste suffisante pour le travail des élèves.

### Fichiers

- Fichier modèle 4 pixels par 4 pixels: [files.modulo-info.ch/petit.bmp](https://files.modulo-info.ch/petit.bmp)
- Fichier modèle 8 pixels par 8 pixels: [files.modulo-info.ch/grand.bmp](https://files.modulo-info.ch/grand.bmp)
- Fichier modèle 8 pixels par 8 pixels, avec palette de couleurs: [files.modulo-info.ch/palette.bmp](https://files.modulo-info.ch/palette.bmp)

### Resources

- Sélectionneur de couleurs BGR: [files.modulo-info.ch/couleurs.html](https://files.modulo-info.ch/couleurs.html)

## Références théoriques pour l'enseignant

L'activité nécessite l'utilisation d'un éditeur hexadécimal par les élèves, ce qui suppose une introduction à la notation hexadécimale. L'[article Wikipédia](https://fr.wikipedia.org/wiki/Syst%C3%A8me_hexad%C3%A9cimal) sur le sujet est très complet.

Le format d'image utilisé dans le cadre de cette activité est le format `BMP`.
Une bonne introduction au format est [disponible sur Wikipédia](https://fr.wikipedia.org/wiki/Windows_bitmap).
Au besoin, la [version anglaise de l'article](https://en.wikipedia.org/wiki/BMP_file_format) entre dans plus de détails du format au travers d'exemples.

## Déroulement

### Étape 1 : Double lecture des fichiers [5 minutes]

L'enseignant invite les élèves à télécharger le premier fichier utilisé à l'adresse:
[files.modulo-info.ch/petit.bmp](https://files.modulo-info.ch/petit.bmp).

Puis, il invite les élèves à ouvrir le fichier à l'aide d'une visionneuse d'image (par exemple `Aperçu` sur Mac OS X).
Il est à noter qu'il faut bien zoomer pour voir l'image étant donné sa petite taille.

L'enseignant montre qu'il s'agit d'une image de 4 par 4 pixels, tous de couleur blanche.
Il en profite pour donner une définition du terme "pixel".

> Le pixel est plus petit élément qui compose une image.
> Chaque pixel d'une image est un carré de couleur qui occupe une place dans la grille de l'image.
> Le terme provient de l'anglais ***pic**ture **el**ement*.

Après cela, l'enseignant invite les élèves à ouvrir l'image dans un éditeur hexadécimal (par exemple [Hexed.it](https://hexed.it)).
L'enseignant explique aux élèves ce qu'ils ont sous les yeux: la séquence d'octets qui représente l'image.
L'enseignant souligne les deux façons de visualiser le même fichier:
- Son interprétation en tant qu'image dans la visionneuse d'image, et
- Son interprétation en tant que séquence d'octets dans l'éditeur hexadécimal.

S'il est possible de le faire dans l'éditeur, l'enseignant montre les bits qui se cachent sous la notation hexadécimale des octets. Dans [Hexed.it](https://hexed.it), les bits d'un octet sont affichés dans la colonne de gauche de l'éditeur.

### Étape 2 : Introduction à la notation hexadécimale [10 minutes]

### Étape 3 : Prise en main de l'éditeur et découverte du format BMP [10 minutes]

### Étape 4 : Représentation des couleurs [5 minutes]

### Étape 5 : Reproduction d'une image [20 minutes]

### Étape 6 : Utilisation d'une palette de couleurs [10 minutes]

### Étape 7 : Conception libre d'une image avec palette de couleur [30 minutes]

## Pistes pour aller plus loin

Stéganographie: Utiliser les bits de poids faible des canaux de couleurs pixels pour y cacher un message.

Compression avec codage par plage, qui est aussi supportée au format BMP.

Compression avec pertes et le format JPEG.

Images vectorielles.