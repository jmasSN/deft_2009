# DÉfi Fouille de Texte (DEFT) 2009 

Réalisation de la tâche 3 du [deft](https://deft.lisn.upsaclay.fr/2009/) : détermination du parti politique de chaque intervention dans un corpus parlementaire.

## Corpus 

Le corpus se compose de la retranscription de débats pour 313 séance parlementaire de 1999 à 2004. 
C'est un corpus parallèle disponible en anglais, français et italien.
L'entrainement comprend 60% des interventions soit : 19370/par langues et le test 40% soit : 12917/par langues.

Les données sont disponibles [ici](https://deft.lisn.upsaclay.fr/) 

## Modèles

Nous avons entrainé les modèles: NaïveBayes, SVM et RandomForest.
Le prétraitement des données et l'utilisation de ses modèles sont dans le notebook dans le dossier **codes**. 

Le rapport sous forme d'un article court dans le style ACL reprenant notre démarche se trouve [ici](https://github.com/jmasSN/deft_2009/Rapport.pdf). 

