# 1_7-Conduite-Projet-2018
Projet de Conduite de projet 2018 (groupe 1_7)

## Tâches du Sprint 1
ID d'une tâche : T#[Numéro Sprint].[NuméroTâche][D|I|F] avec :
* D : tâche de définition
* I : tâche d'implémentation
* F : tâche d'infrastructure

Signification des symboles :
* \* &nbsp;: Tout, tous
* \- &nbsp;: Rien, aucun

|ID|Description|Durée|Dépendances|US associées|État|
|--|-----------|-----|-----------|------------|----|
|T#1.0F|Implémenter un Dockerfile permettant d'exécuter l'application.|1|-|-|DONE|
|T#1.1D|Définir les attributs d'un "Projet".|0.25|-|-|DONE|
|T#1.2D|Définir les attributs d'une "User Story".|0.25|-|-|TODO|
|T#1.14D|Définir les attributs d'un "Développeur".|0.25|-|-|DONE|
|T#1.3I|Impélmenter le fichier "creerProjet.ejs"|0.5|T#1.1D|US#3|DONE|
|T#1.4I|Impélmenter le fichier "listeProjets.ejs"|0.5|T#1.1D|US#5|DONE|
|T#1.5I|Impélmenter le fichier "modifierProjet.ejs"|0.5|T#1.1D|US#4|TODO|
|T#1.7I|Impélmenter le fichier "supprUS.ejs"|0.5|T#1.2D|US#8|TODO|
|T#1.6I|Impélmenter le fichier "creerUS.ejs"|0.5|T#1.2D|US#8|TODO|
|T#1.8I|Impélmenter le fichier "backlog.ejs"|0.5|T#1.2D|US#9|TODO|
|T#1.9I|Impélmenter le fichier "modifierUS.ejs"|0.5|T#1.2D|US#10|TODO|
|T#1.10I|Impélmenter le fichier "projet.js" comportant les requètes CRUD à la base de données concernant un Projet.|1|T#1.1D T#1.2D|-|DOING|
|T#1.16I|Implémenter le fichier "login.ejs" permettant de se connecter.|1|T#1.14D|US#2|DOING|
|T#1.17I|Implémenter le fichier "SignUp.ejs" permettant de créer un compte de développeur.|1|T#1.14D|US#1|DOING|
|T#1.11I|Impélmenter le fichier "server.js" gérant les routes de l'application.|1.5|T#1.12F|-|DOING|
|T#1.12F|Mettre en place une architecture client/server NodeJS.|0.5|-|-|DONE|
|T#1.15F|Mettre en place la base de données et sa fonction de connexion.|0.5|-|-|DONE|
|T#1.13F|Construire la release|0.5|*|-|DONE||


Lien vers la release : https://github.com/LoannGio/1_7-Conduite-Projet-2018/releases/tag/0.1.0
