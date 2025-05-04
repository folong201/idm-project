# projet SimplePDLV2
## Description
Le langage Simple PDL (Process Description Language) est un langage définit pour 
modéliser et représenter les processus métiers ou techniques sous une forme structurée, facilement 
analysable et transformable. Il permet notamment de décrire l’enchaînement d’activités dans un 
processus. 

## Objectif du projet
L’objectif de ce projet est de :
- Créer un metamodele pour le langage SimplePDLV2(voir dossier SimplePDL2)
- ajouter des contraintes OCL pour le metamodele (voir dossier SimplePDL2)
- decrire deux processus métiers en utilisant le langage SimplePDL2 (voir dossier SimplePDL2) plus de details dans le rapport.
    - processus d'incription academic
    - processus de preparation d'un repas
- modeliser les deux processus en utilisant le metamodele SimplePDL2 (voir dossier SimplePDL2)
- valider les deux modeles en utilisant le metamodele SimplePDL2 (voir dossier SimplePDL2)
- realiser une transformation de modeles SimplePDL2 vers un du texte:
    - en html (voir dossier simple2html)
    - en dot (voir dossier simple2graph)

- proposer une syntaxe concrete graphique pour le langage SimplePDL2 (voir my.ptoject.design)
- proposer une syntaxe concrete textuelle pour le langage SimplePDL2 (voir my.ptoject.design)

## Prerequis
- Java 17 ou superieur
- Eclipse IDE 2023-03 ou superieur
- EMF (Eclipse Modeling Framework) 2.28.0 ou superieur
- Sirius 3.2.0 ou superieur
- Papyrus 5.0.0 ou superieur
- OCL 1.10.0 ou superieur

## Description de chaque dossier du projet

### dossier SimplePDL2
ce dossier contient le metamodele SimplePDL2, les contraintes OCL, les modeles SimplePDL2 et les modeles valides(.xmi) SimplePDL2.

### dossier simple2html
ce dossier contient le projet acceleo de transformation de modeles SimplePDL2 vers du texte en html. 

le resultat de la transformation est un fichier html qui contient le model SimplePDL2 sous forme de section html ave un design minimaliste.

ce resultat se trouve dans le dossier simple2html/task.

### dossier simple2graph
ce dossier contient le projet acceleo  de transformation de modeles SimplePDL2 vers du texte en dot.

le resultat de la transformation est un fichier dot qui contient le model SimplePDL2 sous forme de graphe.
ce resultat se trouve dans le dossier simple2graph/task.


### dossier my.project.design
ce dossier contient le projet de design de la syntaxe concrete graphique et textuelle pour le langage SimplePDL2.

