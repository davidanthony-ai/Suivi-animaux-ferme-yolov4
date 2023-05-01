# Suivi d'animaux dans une ferme (moutons et poulets)

Ce projet contient 3 fichiers scripts permettant de détecter sur une image des moutons et les poulets. Ces fichiers permettent aussi de les suivre et de les compter sur une video ou une camera live. Ce projet utilise Yolov4, OpenCV et un centroidtracker.

## Demo 

## Détection sur une image
Detection de poulets sur une image d'une ferme

<img src="https://user-images.githubusercontent.com/125910035/235456953-fa06e2bc-25f0-465f-8ea6-774c324698a3.jpg" width="700" height="700">


Detection avec des figurines


<img src="https://user-images.githubusercontent.com/125910035/235456840-45f25691-6631-4264-830f-17ee9a5006be.jpg" width="700" height="700">

Detection de moutons


<img src="https://user-images.githubusercontent.com/125910035/235457739-2985db6f-754c-4cb4-99ea-9d717be2d3d8.jpg" width="700" height="700">


## Détection sur une video

https://www.dropbox.com/s/t5ke8t541qa43mm/video-mouton.mp4?dl=0

https://www.dropbox.com/s/t5ke8t541qa43mm/video-mouton.mp4?dl=0


## Requirements
```bash
pandas
numpy
scipy
urllib3
tqdm
opencv-python==3.4.13.47
```

## Installation 

* Cloner mon répertoire

* Télécharger les fichiers lourds qui se trouvent sur mon répertoire dropbox:
https://www.dropbox.com/scl/fo/r9h3i1r20dsmxc1m676o5/h?dl=0&rlkey=hxz6b57dl7h0aumcav1svem6w

* Gestion des fichiers :

- Les poids d'entrainement :
Placer le fichier de poids (.weights) dans le dossier 'yolo-pou_mou-data' 
- Les fichiers de test : 
Créer un dossier 'images' et y placer les images ainsi qu'un dossier 'videos' pour les videos

Attention à changer les noms des fichiers test dans le code si vous utiliser vos propres images ou videos

* Ouvrir le répertoire sur votre IDE 

* Créer un nouvel environnement (.venv par exemple ) et l'activer : 

- Sur le terminal de l'IDE, se placer dans le répertoire du projet à l'aide de la commande 'cd'
- Exécuter cette commande :
```bash 
python -m venv .venv
```

Activer ensuite l'environnement virtuel


* Installation des packages:les packages nécessaires sur le nouvel environnement
```bash
pip install -r requirements.txt
```

* Exécution fichiers scripts :

 Il y'a 3 fichiers .py
- yolov4-camera.py pour détecter les animaux à l'aide d'une caméra si vous avez des figurines pour tester
- yolov4-image.py pour détecter les animaux sur une image
- yolov4-video.py pour détecter les animaux sur une video (en fonction de la taille de la video test, l'exécution peut prendre du temps)

## Contribution

Les "Pull requests" sont les bienvenues. Pour les changements majeurs, veuillez d'abord ouvrir une question pour discuter de ce que vous aimeriez changer.
Veillez à mettre à jour les tests le cas échéant.

## License

[MIT](https://choosealicense.com/licenses/mit/)
