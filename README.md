# Application de traitment automatique des valeurs manquantes
L'application est un script Python utilisant la bibliothèque Tkinter pour créer une interface graphique (GUI) simple qui effectuer les tâches suivant:

- le nettoyage des données

- le prétraitement (la normalisation, le traitment des valeurs aberantes par la supprition ou les remplaces par NAN)

- l'évaluation de modèles d'apprentissage automatique si le target est de type numirique on utilisant les models suivant: -RandomForestRegressor -LinearRegression -KNeighborsRegressor si le target est de type qualitatife on utilisant les models suivant: -RandomForestClassifier -LogisticRegression -KNeighborsClassifier

- affichage des données apres la prédiction
