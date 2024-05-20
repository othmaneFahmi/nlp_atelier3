# nlp_atelier3
## Analyse de données textuelles et modèles prédictifs
Ce dépôt contient deux parties distinctes visant à analyser des données textuelles et à construire des modèles prédictifs pour des tâches de classification et de régression.

## Partie 1 : Analyse de données textuelles
Cette partie se concentre sur le traitement et l'analyse de données textuelles à l'aide de différentes techniques telles que la transformation TF-IDF, le sac de mots (Bag of Words) et le plongement de mots (Word Embedding). Voici un aperçu des étapes principales :

- Prétraitement des données : Les données textuelles sont prétraitées pour enlever les caractères spéciaux, les liens URL, les mots-clés (#, @), et sont ensuite normalisées en minuscules.
- Transformation TF-IDF et Bag of Words : Les textes prétraités sont convertis en représentations numériques à l'aide de TF-IDF et du sac de mots.
- Plongement de mots (Word Embedding) : Les mots sont convertis en vecteurs de nombres réels en utilisant Word2Vec.
- Modèles de régression : Trois modèles de régression sont entraînés et évalués sur des données textuelles, à savoir la régression linéaire, la régression par arbre de décision et la régression à vecteurs de support (SVR).

## Partie 2 : Modèles prédictifs pour la classification
Cette partie se concentre sur la construction et l'évaluation de modèles prédictifs pour la classification de données. Voici un aperçu des principales étapes :

- Prétraitement des données : Les données textuelles sont prétraitées de la même manière que dans la partie précédente.
- Transformation TF-IDF et Bag of Words : Les textes prétraités sont convertis en représentations numériques à l'aide de TF-IDF et du sac de mots.
- Plongement de mots (Word Embedding) : Les mots sont convertis en vecteurs de nombres réels en utilisant Word2Vec, similairement à la partie précédente.
- Modèles de classification : Trois modèles de classification sont entraînés et évalués sur les données textuelles, à savoir la régression logistique, la machine à vecteurs de support (SVM) et la forêt aléatoire.
Chaque partie est accompagnée de scripts Python détaillés et commentés, ainsi que d'une interprétation des résultats obtenus.
