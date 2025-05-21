# Régression Linéaire Multiple en Python (from scratch)

Ce projet implémente un modèle de régression linéaire multiple à partir de zéro, sans utiliser de bibliothèques de machine learning comme `scikit-learn`. L'algorithme utilise la descente de gradient pour ajuster les paramètres.

## 📌 Fonctionnalités

- Implémentation de la régression linéaire multiple
- Optimisation avec descente de gradient
- Affichage du coût (MSE) à chaque étape
- Prédictions sur de nouvelles données
- Écrit en pur Python avec NumPy

## 🧠 Formule mathématique

La prédiction est donnée par :

ŷ = w₁·x₁ + w₂·x₂ + ... + wₙ·xₙ + b

La fonction de coût (erreur quadratique moyenne) est :

J(w, b) = (1/m) ∑ (ŷᵢ - yᵢ)²