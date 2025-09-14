# 🔬 Optimisation de la Distillation Eau/Acide Acrylique

## 📋 Description

Ce projet présente une étude comparative de la distillation d'un mélange industriel eau/acide acrylique en présence de gaz incondensables. L'objectif est d'évaluer l'impact du prétraitement par séparation des gaz sur l'efficacité globale du procédé.

### 🎯 Objectifs
- Atteindre **99% de pureté** d'acide acrylique dans le résidu
- Analyser l'influence des gaz incondensables (CO₂, O₂, N₂, propylène)
- Comparer les performances avec/sans prétraitement
- Optimiser la qualité du co-produit eau

## 🧪 Méthodologie

### Composition d'alimentation
- **Eau** : 65.54% molaire
- **Acide acrylique** : 32.33% molaire
- **Gaz incondensables** : 3.97% molaire
  - CO₂ : 0.53%
  - O₂ : 0.73%
  - N₂ : 1.52%
  - Propylène : 1.19%

### Configurations testées

#### 🔴 Expérience 1 - Sans Prétraitement

Alimentation → Colonne de Distillation (20 étages) → Produits
- Débit : 100 kmol/h
- Tous composés inclus
- Alimentation plateau 10


#### 🟢 Expérience 2 - Avec Prétraitement

Alimentation → CompoundSplitter → Colonne (20 étages) → Produits
- Débit purifié : 95.57 kmol/h
- Gaz éliminés : 4.43 kmol/h
- Eau + Acide acrylique uniquement


## 📊 Résultats Principaux

### Performance du Distillat (Fraction Eau)

|        Paramètre        | Sans Prétraitement | Avec Prétraitement | Amélioration |
|-------------------------|--------------------|--------------------|--------------|
| **Pureté H₂O**          |       70.95%       |       96.28%       |   +25.33%    |
| **Contamination Acide** |       11.03%       |        3.72%       |    -7.31%    |
| **Contamination Gaz**   |       18.01%       |           0%       |   -18.01%    |
| **Débit**               |        7.92 kmol/h |        5.83 kmol/h |   -26.4%     |

### Performance du Résidu (Acide Acrylique)
- **🎯 Objectif atteint** : 99% de pureté dans les deux configurations
- **Contamination eau** : 1% (stable)
- **Température** : 137.55°C (identique)

## 🔍 Analyses Techniques

### Impact des Gaz Incondensables
- **Température distillation** : 101.74°C → 100.61°C (avec prétraitement)
- **Modification équilibres** liquide-vapeur
- **Entraînement mécanique** d'acide acrylique vers le distillat
- **Pollution du co-produit** eau (18% de gaz)

### Efficacité de Séparation
- **Nombre d'étages** : 20 (identique dans les deux cas)
- **Position alimentation** : Plateau 10
- **Pression opératoire** : 101 325 Pa (1 atm)

## 🛠️ Outils Utilisés

### Logiciels de Simulation
- **COCO (COFE)** : Interface de simulation de procédés
- **ChemSep** : Calculs rigoureux d'équilibres de phases
- **Modèles thermodynamiques** : Équations d'état précises

### Équipements Modélisés
- **CompoundSplitter** : Séparation gaz/liquide
- **Colonne de distillation** : 19 plateaux théoriques + rebouilleur
- **Condenseur total** en tête
- **Rebouilleur** en fond


## 📈 Résultats Économiques

### ROI du Prétraitement
- **ROI Qualité** : +25.33% pureté eau (co-produit valorisable)
- **ROI Énergétique** : Réduction coûts retraitement distillat contaminé
- **ROI Environnemental** : Valorisation flux gazeux séparés

### Applications Industrielles
- **Industrie pétrochimique** : Purification monomères acryliques
- **Procédés verts** : Optimisation énergétique
- **Contrôle qualité** : Spécifications strictes
- **Économie circulaire** : Valorisation sous-produits

## 🎯 Conclusions

### Principales Découvertes
1. **Objectif technique atteint** : 99% acide acrylique dans les deux cas
2. **Impact critique des gaz** : Dégradation qualité distillat (-25.33%)
3. **Prétraitement rentable** : Amélioration significative co-produit
4. **Optimisation globale** : Même équipement, meilleures performances

### Recommandations
- **Prétraitement recommandé** pour applications haute qualité
- **Valorisation gaz** séparés (combustible, matière première)
- **Post-traitement évité** du distillat contaminé
- **Flexibilité procédé** selon spécifications produits

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 🙏 Remerciements

- **COCO Software** pour l'interface de simulation intuitive
- **ChemSep** pour les calculs thermodynamiques rigoureux
- **Communauté Process Engineering** pour le partage de connaissances
