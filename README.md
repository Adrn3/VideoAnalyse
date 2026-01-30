# VideoAnalyse

🏎️ Analyse Vidéo de Formule 1 depuis une caméra Halo
📌 Description du projet

Ce projet a pour objectif de développer un programme Python capable d’analyser une vidéo embarquée de Formule 1, filmée depuis la caméra halo, afin d’extraire et d’afficher automatiquement plusieurs informations clés :

📈 Estimation de la vitesse du véhicule

🚦 Détection des phases de freinage

🔁 Identification des dépassements

🚗 Reconnaissance des voitures lors des dépassements

Le projet combine des techniques de vision par ordinateur, de traitement vidéo et de machine learning, appliquées à un contexte réel et complexe : la course automobile.

🎯 Objectifs

Exploiter une vidéo embarquée (onboard halo)

Extraire des informations dynamiques à partir d’images

Mettre en place une architecture modulaire et évolutive

Approfondir les compétences en :

Computer Vision

Analyse vidéo

Data science appliquée au sport automobile

🧠 Fonctionnalités
✔️ Fonctionnalités actuelles / prévues

 Chargement et lecture d’une vidéo onboard F1

 Détection de la piste et des lignes de référence

 Estimation de la vitesse à partir du déplacement image → image

 Détection des zones de freinage (décélération + indices visuels)

 Détection des dépassements

 Identification de la voiture dépassée (numéro, couleur, livrée)

 Affichage des données en surimpression sur la vidéo

 Export des données (CSV / JSON)

🛠️ Technologies utilisées

Python 3

OpenCV – traitement d’image et analyse vidéo

NumPy – calculs numériques

PyTorch / TensorFlow (optionnel) – détection et classification

YOLO / CNN (optionnel) – reconnaissance des voitures

Matplotlib – visualisation des données

🗂️ Structure du projet
├── data/
│   └── videos/          # Vidéos onboard F1
├── src/
│   ├── video_loader.py
│   ├── speed_estimation.py
│   ├── braking_detection.py
│   ├── overtake_detection.py
│   ├── car_identification.py
│   └── main.py
├── models/              # Modèles ML entraînés
├── outputs/
│   ├── videos/
│   └── data/
├── requirements.txt
└── README.md

🚀 Installation

Cloner le dépôt :

git clone https://github.com/
cd f1-halo-video-analysis


Installer les dépendances :

pip install -r requirements.txt

▶️ Utilisation

Lancer l’analyse sur une vidéo :

python src/main.py --video data/videos/onboard.mp4


Les résultats sont :

affichés en temps réel sur la vidéo

sauvegardés dans le dossier outputs/

⚠️ Limitations connues

La vitesse est une estimation, dépendante de la perspective et du calibrage

La reconnaissance des voitures dépend fortement de la qualité vidéo

Les vidéos TV compressées peuvent réduire la précision

Le projet n’utilise pas de données télémétriques officielles

🔮 Améliorations futures

Calibration précise avec dimensions réelles de la piste

Utilisation de données GPS simulées

Interface graphique (GUI)

Analyse multi-caméras

Support temps réel

📚 Sources & inspirations

Vision par ordinateur appliquée au sport

Analyse vidéo embarquée

Projets open-source d’object detection

Projet personnel développé par Adrien Ponchard
