# Hackathon StatUp x Capgemini & Too Good To Go 

Bon hackathon :) 

La présentation de nos résultats est un disponible [ici](https://github.com/Noureddineidir/Hackathon-StatUp-x-Capgemini/blob/019a569e427f6aa8887557d809be0cb3202d5942/4_presentation/PPT_EQUIPE_3_TGTG.pdf).

## A. Contexte

L’un de nos principaux enjeux est de maintenir nos commerçants actifs sur notre
plateforme afin qu’ils sauvent un maximum de panier-repas de la poubelle. Un
commerçant est considéré actif lorsqu’il propose des repas à la vente sur l’application.

## B. Objectif
L'objectif est ici de construire un modèle qui permettrait de déterminer la probabilité
qu’un store devienne inactif, c'est-à-dire qu’il arrête de mettre en vente des paniers sur
notre plateforme.
Les différents facteurs de corrélation peuvent être cherchés dans le comportement des
commerçants sur notre plateforme (last meal saved date, average rating, store
cancellation, ...) mais aussi ailleurs (saisonnalité, emplacement, vacances, ...).
In fine, nous souhaiterions être capable, à partir des données dont nous disposons, de
générer chaque jour ou chaque semaine une liste de magasins avec une forte probabilité
de churn afin de mener des actions préventives.
Par “churn” nous entendons ici : un magasin qui avait l’habitude de mettre des paniers en
ligne sur l’application (au moins 1 par semaine) et qui cesse de le faire pendant plus de 30
jours consécutifs. La limite de 30 jours a été fixée de façon empirique et peut tout à fait
être remise en question, l’enjeu réel étant de conserver les magasins actifs sur
l’application.
Pour information, les magasins suivent en général un rythme hebdomadaire assez marqué
et vont avoir des comportements similaires d’une semaine sur l’autre. La limite des 30
jours permet de prendre une marge de 4 périodes et d’éviter de s’intéresser aux magasins
qui seraient simplement fermés en période de vacances (été, noël, pâques)


## Accès aux données 

https://fts.capgemini.com/pubpwd/33504211085251/SujetMachineLearning-TGTG.zip 
 
Avec les identifiants (à demander) : 



username: ********
Password: ********



## Nécessite une màj/need for update.
