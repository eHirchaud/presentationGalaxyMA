% Formation guide Galaxy : Micro-Array
% Edouard Hirchaud, Audrey Bihouée, Raluca Teusan
% 25 Septembre, 2014


[https://github.com/eHirchaud/presentationGalaxyMA](https://github.com/eHirchaud/presentationGalaxyMA)

Créer un compte galaxy
======================

Aller sur [http://cardioserve.nantes.inserm.fr/galaxy](http://cardioserve.nantes.inserm.fr/galaxy)

Dans la barre de navigation aller sur **User** puis **Register**

Créer un compte. L' **user** doit être un email. 

Attention au public name Galaxy n'accepte que les minuscules et le symbole  _


Description de l'interface
=========================

Panneau à gauche : Les outils
-----------------

Comporte tous les outils (tools) classés par catégorie.

Les outils disponibles dépendent de l'instance de Galaxy.

On trouve un mini moteur de recherche en haut de ce panneau.

Panneau à droite : Historique
-----------------------------

Contient tous les datasets, les input et les outputs.

Couleurs des dataset :

* Vert : Ok tout va bien
* Jaune : Patience ça tourne
* Gris : En attente, dépend d'un autre **job** (généralement pas long)
* Bleu : En upload
* Rouge : Probléme probablement un mauvais fichier d'entrée ou un bug dans l'outil

Il est conseillé de renommer son historique en cliquant sur Unnamed history.
On peut également créer un nouvel historique.

Panneau central : Paramétrage et lancement des outils
-----------------------------
Une fois un outil sélectionné, les paramètres s'affichent dans un formulaire dans le panneau central.
C'est de là que sont exécutés les outils.


Barre de navigation
-------------------

* Analyze Data : pour revenir à la page principale (Analyse)
* Workflow : créer et modifier des workflows.
* Shared Data : 

  1. Données partagées
  2. Publication d'historique,workflows, Pages, visualisations

* Visualisation : créer des visualisations
* Aide
* User : paramétre du compte, déconnection

Importation des data
====================

* Via l'outil d'upload de galaxy : choisir les fichiers se trouvant en local
* Via les library : importer des données déjà sur le serveur

    1. Shared Data -
    2. Data Libraries 
    3. formation_agilent_files
    4. Sélectionner tous les fichiers (Cocher la boite à coté de Name)
    5. puis en bas For selected datasets : import to current history. Cliquer sur Go


Glossaire /jargon
=================


* Instance de Galaxy : Application web propre à un labo. Chaque instance est personalisée, dans le choix des outils, les quotas de stockages etc.. Il n'y a pas d'interpolarité entre les instances.
* Tool : Un formulaire permettant de rentrer les paramétres pour un script et qui décrit la façon de l'exécuter.
* Job : Lorsque l'on execute un outil la machine va lancé un job
* Dataset : C'est la donnée d'entré ou de sortie. Il ne s'agit pas seulement d'un fichier car elle contient des métadonnées (type de données, base de données liée, comment elle à été générée etc...)
* Script : Le programme en question décrit par un outil et exécuté en arrière-plan.
* Workflow : Enchainement d'outils dont les inputs (entrées) d'outils sont les outputs (sortie) d'autres
* Toolshed : Application web différente de Galaxy qui contient des outils rangés en catégories. (Une sorte d'AppStore)
* Library : Ensemble de datasets (spécifique à une instance)



Liens 
============

* [http://www.pf-bird.univ-nantes.fr/](http://www.pf-bird.univ-nantes.fr/) BiRD (Nantes)

* [http://abims.sb-roscoff.fr/](http://abims.sb-roscoff.fr/) ABiMS (Roscoff)

* [http://www.genouest.org/](http://www.genouest.org/) GenOuest (Rennes)

* [http://www.biogenouest.org/](http://www.biogenouest.org/) BioGenOuest (Grand Ouest)


![Figure 1-1. Fenetre principale de galaxy.](images/screenGalaxy.png)

![Workflow](images/gen_image2.png)
