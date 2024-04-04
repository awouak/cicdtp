# Répertoire du TP2 CI/CD

## Elements requis :

- Un répertoire Github en Public
- Un compte Microsoft Azure avec de l'argent

## Repertoire Github :

Pour utiliser le projet, la 1ère étape est de mettre les fichiers : app.py, requirements.txt et test_app.py dans votre répertoire Github en mode "Public"

## Azure :

Pour que Azure puisse deployer automatiquement l'application flask (sous forme d'un site web), il est nécéssaire de créer une App Web Service dans Azure.

Pour ce faire se rendre sur "App Services" puis sur "Create" et "App Web App"

Paramétrer de la facon suivante : 

Groupe de ressource : Celui que vous voulez
Nom : Le nom que vous voulez
Publier : Code
Pile d'éxécution : Python 3.12

Ensuite, dans l'onglet "Déploiement" dans "Parametre des actions Github" sélectionner "Permettre" pour "Déploiement Continue", et connecter votre compte Github à Azure dans l'encart qui va apparaitre en dessous. Sélectionner le répertoire où il y a votre projet python.

Enfin lancer la création

## Voir la page web :

Pour voir la page web, rendez vous sur https://nom.azurewebsites.net

Vous devriez voir normalement votre application Flask (Cela peux prendre 10min à s'afficher il faut etre patient)

Vous pouvez voir le status du déploiement dans "Service d'applications' et dans 'Overview' pour voir si le déploiement est toujours en cours ou terminé.
Vous pouvez aussi consulté cela dans "Actions" sur votre répertoire Github.
