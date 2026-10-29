# Traitement d'images avec NumPy

Trois exercices pour manipuler des images comme des tableaux de pixels avec NumPy.

## Contenu

1. **Comprendre les pixels** : chargement d'une image, lecture de la forme du tableau (hauteur, largeur, canaux), lecture d'une valeur RGB, modification d'une zone.
2. **Niveaux de gris** : conversion d'une partie de l'image avec la pondération 0,299 R + 0,587 V + 0,114 B.
3. **Luminosité** : augmentation et diminution de la luminosité avec `np.clip` pour rester dans la plage 0-255.

## Ce que j'ai appris

- Une image couleur est un tableau 3D (hauteur × largeur × 3 canaux).
- Le slicing NumPy permet de modifier une zone sans boucle.
- Il faut convertir en `int16` avant d'ajouter une constante à des `uint8`, sinon les valeurs dépassent 255 et repartent de 0.

## Lancer le notebook

    pip install -r requirements.txt
    jupyter notebook exo_numpy_images.ipynb

## Outils

Python · NumPy · Matplotlib · Pillow · Jupyter

## Auteur

Yan AKOUEDENOUDJE — [Portfolio](https://yanakouedenoudje.github.io) · [GitHub](https://github.com/yanakouedenoudje)
