Le projet Dictionary scrap a pour ambition de scraper des dictionaires français afin de collecter les différentes définitions. Ceci dans le but de pouvoir utiliser ces définitions dans d'autres projets de Natural Langage Processing en français.

L'autre objectif de ce projet est de se familiariser avec git, github, le scrapper open source scrapy et la base de donnée Neo4j.

Pour commencer : 
1/ installation de anaconda
# note :  anaconda est une distribution opensource python qui va faciliter les développements Python pour les applications de machine learning et data science
- télécharger et installer anaconda ( https://www.anaconda.com/distribution/)
- lancer anaconda cloud
- aller sur l'onglet environnement et créer un nouvel environnement virtuel (ie : DictionaryScraper)
# note : un environnement permet de gérer l'ensemble des dépendances ( ex : librairies et leur versions) d'un projet sans interférer avec les dépendances des autres projets. pour en savoir plus : https://openclassrooms.com/fr/courses/4425111-perfectionnez-vous-en-python/4463278-travaillez-dans-un-environnement-virtuel
# note : VS code un editeur (python) fournit est fournit avec anaconda

2/ instalation et configuration de git et github
#note: pour débuter avec Git le tutorial : https://www.christopheducamp.com/2013/12/15/github-pour-nuls-partie-1/
Les étapes à suivre sont : 
- télécharger le logiciel git
- créer un compte sur github
- créer un répertoire du nom de votre projet sur Github
- créer un répertoire en local du nom de votre projet
- indiquer que ce répertoire est suivi par git via git init
- connecter le répertoire local au répertoire distant ( github) via git remote add origin https://github.com/nomutilisateur/MonProjet.git
3/ créer un répertoire en local et le pousser vers github
- sous votre répertoire local, ajouter un fichier via git add NomDuFichier
- figer le code (photo) de votre répertoire via git git commit -m "description de votre photo)
- ajouter le répertoire distant de github via git remote add origin https://github.com/SebastienJuras/DictionaryScrap.git
- pousser le code "comité" sur le répertoire distant via git push --set-upstream origin master

3/ créer un fichier sur Github et le récupérer en local
- utiliser la commade : git pull https://github.com/SebastienJuras/DictionaryScrap master ( recupère le fichier et le merge avec la branche master)
# note : pull = fetch + merge

