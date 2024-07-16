# Application de traitment automatique des valeurs manquantes
L'application est un script Python utilisant la bibliothèque Tkinter pour créer une interface graphique (GUI) simple qui effectuer les tâches suivant:

- Le nettoyage des données

- Le prétraitement (la normalisation, le traitment des valeurs aberantes par la supprition ou les remplaces par NAN)

- L'évaluation de modèles d'apprentissage automatique si le target est de type numérique on utilisant les models suivant: -RandomForestRegressor -LinearRegression -KNeighborsRegressor si le target est de type qualitatife on utilisant les models suivant: -RandomForestClassifier -LogisticRegression -KNeighborsClassifier

- Affichage des données après la prédiction
