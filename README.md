
## 🎯 Objectif
Détecter automatiquement la présence ou l'absence de maladie cardiaque à partir de données cliniques.

## 🧰 Technologies utilisées
- Python
- Pandas
- NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📊 Description des données (heart.csv)
- `age` : âge du patient  
- `sex` : sexe (1 = homme ; 0 = femme)  
- `cp` : type de douleur thoracique (0 à 3)  
- `trestbps` : pression artérielle au repos  
- `chol` : taux de cholestérol  
- `fbs` : glycémie à jeun > 120 mg/dl (1 = oui ; 0 = non)  
- `restecg` : résultats électrocardiographiques au repos  
- `thalach` : fréquence cardiaque maximale atteinte  
- `exang` : angine induite par l’exercice (1 = oui ; 0 = non)  
- `oldpeak` : dépression ST  
- `slope` : pente du segment ST  
- `ca` : nombre de vaisseaux colorés par fluoroscopie (0 à 3)  
- `thal` : 1 = normal, 2 = défaut fixe, 3 = défaut réversible  
- `target` : 0 = pas de maladie ; 1 = maladie cardiaque présente  

## ⚙️ Étapes du projet
1. Chargement et exploration du dataset  
2. Nettoyage des données  
3. Visualisation des corrélations  
4. Prétraitement : standardisation et encodage  
5. Séparation en données d'entraînement et de test  
6. Entraînement du modèle de régression logistique  
7. Évaluation du modèle (accuracy, matrice de confusion, courbe ROC)
