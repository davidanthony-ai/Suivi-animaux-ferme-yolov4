# Detection et decompte d'animaux (moutons et poulets)

## Exécution du code 

### 1) Télécharger et extraire le dossier dans un répertoire local ou cloner le répertoire

### 2) Télécharger les fichiers lourds de mon répertoire dropbox:
https://www.dropbox.com/scl/fo/r9h3i1r20dsmxc1m676o5/h?dl=0&rlkey=hxz6b57dl7h0aumcav1svem6w

- les poids d'entrainement
Placer le fichier de poids dans le dossier 'yolo-pou_mou-data' 
- les fichiers de test 
Placer les images dans le dossier images et les videos dans le dossier videos

Attention à changer les noms des fichiers test dans le code si vous utiliser vos propres images ou videos

### 3) Ouvrir le répertoire sur votre IDE 

### 4) Créer un nouvel environnement (venv par exemple ) et l'activer
### 5) Installation des packages:
pip install -r requirements.txt pour installer les packages nécessaires sur le nouvel environnement
### 6) Exécution fichiers scripts
 Il y'a 3 fichiers .py
- yolov4-camera.py pour détecter les animaux à l'aide d'une caméra si vous avez des figurines pour tester
- yolov4-image.py pour détecter les animaux sur une image
- yolov4-video.py pour détecter les animaux sur une video (en fonction de la taille de la video test, l'exécution peut prendre du temps)
