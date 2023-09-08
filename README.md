# Projet 2: Analysez des données de systèmes éducatifs 
## Présentation:
Je suis Data Scientist dans une start-up de la EdTech, nommée academy, qui propose des contenus de formation en ligne
pour un public de niveau lycée et université.
Mark, mon manager, m'a convié à une réunion pour me présenter le projet d’expansion à l’international de
l’entreprise. Il me confie une première mission d’analyse exploratoire, pour déterminer si les données sur l’éducation
de la banque mondiale permettent d’informer le projet d’expansion.

Voici les différentes questions que Mark aimerait explorer, que j'ai notées durant la réunion :

- Quels sont les pays avec un fort potentiel de clients pour nos services ?
- Pour chacun de ces pays, quelle sera l’évolution de ce potentiel de clients ?
- Dans quels pays l'entreprise doit-elle opérer en priorité ?
## Mission:
Réaliser une analyse pré-exploratoire du jeu de données. 
Pour la pré-analyse, il faut:
- Valider la qualité de ce jeu de données (comporte-t-il beaucoup de données manquantes, dupliquées ?)
- Décrire les informations contenues dans le jeu de données (nombre de colonnes ? nombre de lignes ?)
- Sélectionner les informations qui semblent pertinentes pour répondre à la problématique (quelles sont les colonnes contenant des informations qui peuvent être utiles pour répondre à la problématique de l’entreprise ?)
- Déterminer des ordres de grandeurs des indicateurs statistiques classiques pour les différentes zones géographiques et pays du monde (moyenne/médiane/écart-type par pays et par continent ou bloc géographique)

Ce travail va permettre de déterminer si ce jeu de données peut informer les décisions d'ouverture vers de 
nouveaux pays. L'analyse sera partagée avec le board, il faut donc soigner la présentation et l'illustrer avec des graphiques pertinents et lisibles !
## Données:
Les données de la Banque mondiale sont disponibles à l’adresse suivante :
https://datacatalog.worldbank.org/dataset/education-statistics

Ou en téléchargement direct à ce lien :https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Donn%C3%A9es+%C3%A9ducatives/Projet+Python_Dataset_Edstats_csv.zip

En résumé, l’organisme “EdStats All Indicator Query” de la Banque mondiale répertorie 4000 indicateurs internationaux 
décrivant l’accès à l’éducation, l’obtention de diplômes et des informations relatives aux professeurs, aux dépenses 
liées à l’éducation... Plus d'informations sur ce site : http://datatopics.worldbank.org/education/
## Construction:
Dans ce dépôt, vous trouverez plusieurs fichiers:

- "notebook.ipynb" : notebook  comportant les analyses pré-exploratoires réalisées.


## Packages:
Différents packages Python ont été utilisés:

- pandas 1.4.4
- matplotlib 3.5.2

## Compétences:
- Mettre en place un environnement Python
- Effectuer une représentation graphique à l'aide d'une librairie Python adaptée
- Manipuler des données avec des librairies Python spécialisées
- Maîtriser les opérations fondamentales du langage Python pour la Data Science
- Utiliser un notebook Jupyter pour faciliter la rédaction du code et la collaboration