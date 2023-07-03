# get-next-line

<div align="center">
  <img src="https://media1.giphy.com/media/KsBC8HSDKs3MC03Xf2/giphy.gif?cid=6c09b952uqzyfm5rji12l8qjs8umi6rcfrnua5kvrscdecjx&ep=v1_stickers_related&rid=giphy.gif&ct=s" alt="GIF d'introduction" width="200px">
</div>

Le projet Get Next Line (GNL) consiste à créer une fonction qui permet de lire une ligne à partir d'un fichier ou d'un descripteur de fichier (file descriptor) en C.

# Objectif

L'objectif du projet GNL est de développer une fonction qui permet de lire une ligne de texte à partir d'un fichier, peu importe sa taille, en gérant les différentes occurrences de fin de ligne. Cette fonction est particulièrement utile pour la lecture de fichiers texte ligne par ligne.
# Fonctionnement

La fonction GNL lit le fichier ouvert et renvoie une ligne de texte à chaque appel successif. Elle gère automatiquement les caractères de fin de ligne, tels que '\n', et retourne une ligne complète jusqu'à cette occurrence.
# Utilisation

Pour utiliser la fonction GNL, il suffit de l'appeler avec le descripteur de fichier approprié. La fonction renverra une ligne à chaque appel jusqu'à ce que la fin du fichier soit atteinte.
# Gestion de la mémoire

La fonction GNL alloue dynamiquement de la mémoire pour stocker les lignes lues. Il est important de libérer cette mémoire correctement après utilisation pour éviter les fuites de mémoire.
# Exemple d'utilisation

Dans mon projet graphique "so_long" j'utilise le code de gnl pour me permettre de lire une map et de récupérer les informations nécessaires pour rendre mon jeu jouable: positions des murs, nombres d'items à récupérer, position de la sortie, etc...
