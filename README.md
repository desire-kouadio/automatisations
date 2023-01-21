## Automatisations 

GitHub actions est un outil qui vous permet d'automatiser vos flux de travail de développement
de logiciels. GitHub actions est l'outil le plus utilisé pour construire des pipelines CI/CD.

##  workflows 1
test simple avec des commandes bash, etc....

## workflows 2
nous allons créer une action qui exécute des tests avec pytest et contrôle la qualité de votre code 
avec Flake8 lorsque vous chargez sur votre dépôt.

- Le framework pytest permet de créer facilement des tests simples et lisibles, et peut s'adapter à des tests fonctionnels complexes pour des applications et des bibliothèques.

- Flake8 est une bibliothèque Python qui englobe PyFlakes, pycodestyle et le script McCabe de Ned Batchelder. Il s'agit d'une excellente boîte à outils pour vérifier votre base de code par rapport au style de codage (PEP8), aux erreurs de programmation (comme "library imported but unused - bibliothèque importée mais inutilisée" et "Undefined name - nom non défini").

- Tout d'abord, vous devez créer un script python qui contient des fonctions avec des assertions à tester. 
Pytest analysera toutes les fonctions de vos scripts mais il y a une condition : le nom de vos fonctions doit commencer par test_.
