# panorama-opencv
Application de fusion d’images pour générer un panorama à l’aide d’OpenCV

# MTI805 Lab 02

Voici l'enoncé : [Énoncé](https://cours.etsmtl.ca/mti805/private/labos/laboratoire2.pdf)

Pour faire l'application de base, le tutoriel suivant a été suivi: [Tutoriel](https://pyimagesearch.com/2018/12/17/image-stitching-with-opencv-and-python/).

Voici les étapes importantes à savoir pour démarrer le code.

Un premier code simple a été fait sous `image_stitching_simple.py`. Par contre, ce code ne fait que faire le stitching des images, pour faire le crop après on utilise le code `image_stitching.py`. Dans ce code il y a fallu faire des petits tours de passe passe pour faire le cropping adéquatement.

### Start Scripts

Pour lancer les scripts, simplement créer un nouveau dossier avec les images comme suit `images/TestX`. C'est ces images qui seront utilisés par le Stitcher.

Ensuite faire la commande suivante : `python image_stitching.py --images images/TestX --output resultats/TestX/output_final.png --crop 1`

*ATTENTION*: Le code peut prendre un certain temps a finir de runner. Les images en output ne seront pas visibles avant la fin.

Le parametre crop permets de choisir si on veut crop l'image après avoir fait le stitching ou non.
- crop 1 : le croping est fait
- crop 0 : le croping n'est pas fait