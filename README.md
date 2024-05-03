# Default_Detection
Développement d’une application intelligente pour le traitement d’images en vue de la détection et de la localisation de défauts dans une image.
## 2.4 Les librairies utilisées

### 2.4.1 Modules de détection
OpenCV (Open Source Computer Vision Library) est utilisé pour la détection d'objets et de motifs dans les images et les vidéos.

### 2.4.2 Modules de seuillage
Pour la détection de contours dans des images en couleur, un prétraitement basé sur le seuillage est nécessaire pour produire une image binaire à canal unique. Les étapes incluent :
- Conversion de l'image en niveaux de gris à l'aide de `cv2.cvtColor()`.
- Inversion des valeurs des pixels dans une image binaire avec `cv2.bitwisenot()`.
- Création d'une image seuillée binaire avec `cv2.threshold()`.

### 2.4.3 Modules de localisation
Numpy est une bibliothèque fondamentale pour les opérations numériques en Python. Elle est largement utilisée pour la manipulation de tableaux, de matrices et les opérations mathématiques. Dans ce projet, Numpy est employé pour la création et la manipulation de tableaux pour diverses opérations de localisation.

### 2.4.4 Modules de visualisation
Matplotlib est une bibliothèque polyvalente pour la création de visualisations en Python. Elle est couramment utilisée pour afficher des images, tracer la progression de l'apprentissage, ou visualiser des statistiques de données de manière graphique.
