# Segmentation sémantique avec TransUNet sur le dataset Arcade

Ce projet applique un modèle TransUNet pour segmenter les images du dataset Arcade.

##  Objectif
- Générer des masques à partir des annotations
- Effectuer un split aléatoire en train/test
- Entraîner (fine-tuning) un modèle TransUNet
- Évaluer les performances sur le jeu de test

##  Pipeline
1. Génération des masques à partir des annotations
2. Mélange et split aléatoire en train/test
3. Entraînement du modèle
4. Évaluation

##  Résultats
- F1-score sur le test set : **0.6951**

##  Dépendances (optionnel)

- torch
- numpy
- opencv-python
- matplotlib
- pillow
- tqdm
- albumentations
- scikit-learn
