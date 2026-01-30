# VideoAnalyse

## 📌 Description du projet

Ce projet a pour objectif de développer un programme Python capable d’analyser une vidéo embarquée de Formule 1, filmée depuis la caméra halo, afin d’extraire et d’afficher automatiquement plusieurs informations clés :

- 📈 Estimation de la vitesse du véhicule  
- 🚦 Détection des phases de freinage  
- 🔁 Identification des dépassements  
- 🚗 Reconnaissance des voitures lors des dépassements  

Le projet s’appuie sur des techniques de vision par ordinateur, de traitement vidéo et de machine learning appliquées au sport automobile.

---

## 🎯 Objectifs

- Exploiter une vidéo embarquée (onboard halo)
- Extraire des informations dynamiques à partir d’images
- Concevoir une architecture modulaire et évolutive
- Approfondir les compétences en :
  - Vision par ordinateur
  - Analyse vidéo
  - Data science appliquée au sport

---

## 🧠 Fonctionnalités

### Fonctionnalités actuelles / prévues

- [ ] Chargement et lecture d’une vidéo onboard F1
- [ ] Détection de la piste et des repères visuels
- [ ] Estimation de la vitesse à partir du déplacement image par image
- [ ] Détection des phases de freinage (décélération + indices visuels)
- [ ] Détection des dépassements
- [ ] Identification de la voiture dépassée (couleur, numéro, livrée)
- [ ] Affichage des informations en surimpression sur la vidéo

---

## 🛠️ Technologies utilisées

- Python 3
- OpenCV
- NumPy
- YOLO / CNN pour la détection d’objets

---

## 🗂️ Structure du projet



---

## 🚀 Installation

1. Cloner le dépôt :

git clone https://github.com/Adrn3/VideoAnalyse.git

cd f1-halo-video-analysis


2. Installer les dépendances :

pip install -r requirements.txt


---

## ▶️ Utilisation

Lancer l’analyse sur une vidéo :

python src/main.py --video data/videos/onboard.mp4


Les résultats sont :
- affichés en temps réel sur la vidéo
- sauvegardés dans le dossier `outputs/`

---

## ⚠️ Limitations

- La vitesse est une estimation basée sur la perspective vidéo
- Les performances dépendent fortement de la qualité de la vidéo
- Les vidéos compressées peuvent réduire la précision
- Aucune donnée télémétrique officielle n’est utilisée

---

## 🔮 Améliorations futures

- Calibration précise avec dimensions réelles de la piste
- Utilisation de données GPS ou télémétriques simulées
- Interface graphique (GUI)
- Analyse en temps réel
- Support multi-caméras

---

## 👤 Auteur

Projet personnel développé par **Adrien Ponchard**

N’hésitez pas à me contacter pour toute question ou suggestion.
