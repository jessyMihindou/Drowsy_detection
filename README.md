# Détection de Fatigue avec YOLO et UAnalytics


![Exemple de Détection de Fatigue](https://files.ia.ca/-/media/files/ia/zoneconseilsv2/auto/2023/images-couleur/quoi-faire-pour-eviter-la-fatigue-au-volant.jpg)


## Présentation

Ce projet vise à développer un système de détection de fatigue pour les conducteurs en utilisant des techniques avancées de reconnaissance d'images avec YOLO (You Only Look Once) et une analyse de données avec UAnalytics. Le système détecte les signes de fatigue dans les vidéos de conduite en temps réel et fournit des alertes pour améliorer la sécurité routière.

## Fonctionnalités

- Détection en temps réel de la fatigue du conducteur.
- Utilisation du modèle YOLO pour la détection des visages et des expressions.
- Analyse des données et des alertes avec UAnalytics.
- Interface utilisateur pour visualiser les alertes de fatigue.

## Prérequis

Avant de commencer, assurez-vous que vous avez installé les éléments suivants :

- Python 3.7 ou version ultérieure
- YOLOv5 (ou YOLOv4 selon votre choix)
- UAnalytics
- OpenCV
- NumPy
- Matplotlib (pour les visualisations)
- Bibliothèques supplémentaires selon les besoins (voir `requirements.txt`)

## Installation

1. **Clonez le dépôt**

   ```bash
   git clone https://github.com/jessyMihindou/Drowsy_detection.git
   cd Drowsy_detection
