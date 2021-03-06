# NT-ordonnances (NTO)

[![Join the chat at https://gitter.im/NT-ordonnances/community](https://badges.gitter.im/NT-ordonnances/community.svg)](https://gitter.im/NT-ordonnances/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

*Read this in : [English](README.en.md)*

### Objectif:
### Avoir des ressources (simples listes) de l'ensemble des ordonnances données à des chrétiens, quel qu'ils soient, dans le nouveau testament, classées par :

#### - LIVRE :
  - évangiles :
    - Matthieu
    - Marc
    - …
  - épîtres :
    - Romains
    -  …
  - autres :
    - Actes des apôtres
    - Apocalypse

#### - ASSEMBLÉE (ou type de personne) à qui l'ordonnance est donnée :
  - Toute personnes pouvant être apparenté à des croyants dans les évangiles :
    - Aux "douze"
    - Aux "soixante-dix" disciples
    - Aux disciples-croyants hors des douzes et des soixantes-dix
    - Aux foules (parmi lesquels se trouvent peut être des croyants)
  - À L'assemblée de Corinthe
  - À L'assemblée des Thessaloniciens
  - Aux chrétiens romains (équivalent normalement au fichier sur l'épître aux Romains)
  - Au type de chair :
     - Aux hommes
     - Aux femmes
     - Aux enfants
   - Au statut maritale :
     - Aux couples
     - Aux célibataires
   - À l'état spirituel :
     - Aux anciens
     - Aux pécheurs (Jacques, …)
     - Aux nouveaux nés spirituel
  …

#### - la PERSONNE par laquelle l'ordonnance est donnée :
  - La Tête du Corps de Christ, le Chef
    - J.ésus lui-même
  - Un apôtre :
    - Simon Pierre, fils de Jonas
    - Jean, fils de Zébédée
    - Paul, de Tarse, appelé précédemment Saul. (1 Cor 11:2)
  - Autres

#### - PÉRIODE :
  - avant la crucifixion
  - après la crucifixion
  - avant la pentecôte
  - après la pentecôte

#### - ÉTAT :
  - "positif" ("do")
  - "négatif" ("don't")

#### - TYPE
  - commandement (*ἐντολή, …? - strong n°1785, …?*)
  - demande-prière (*ἐρωτάω - strong n°2065*)
  - "indirecte" (Actes 13:47, 1 Thess 4:3-4, …)
  - exorthation (*παρακαλέω - strong n°3870*)
  - question (Rm 3:7, …)
  - conseil (*γνώμη, …? - strong n°1106, …?*)
  - ( voir si c'est pertinent: ordres, instructions (*δικαίωμα, ἐπιταγή, … - strong n°1345, 2003, …*) ? voir "LOI" page 891 de "Le Pentatqueque" de la Bible d'Alexandrie les éditions du cerf 2001 )

#### - THÉMATIQUE 
(voir https://github.com/kylak/greekNTO-classificationProgram)
#### - possiblement d'autres critères



## Pour ajouter une ordonnance dans un fichier :

##### Les branches autres que master ne sont que des branches de développement. Si vous voulez consulter la dernière version du Readme soyez sur la branche master.

- Afin d'éviter toute erreur, l'emploi d'au moins une traduction littérale est vivement conseillé, le mieux étant d'utiliser (ou de vérifier dans) les textes grec directement.

- Citer la référence du verset dans ce format classique: ``Livre chapitre:verset``

Attention, il peut se trouver plusieurs ordonnances dans un seul et même verset, dans un tel cas, dupliquer la référence de ce verset autant de fois qu'il contient d'ordonnance.  
Aussi, une ordonnance peut "s'étaler" sur plusieurs versets contigus, dans ce cas, il faut utiliser un tiret "-" comme pour une référence classique : ``Livre chapitre:verset_début-verset_fin``

- Après chaque référence ajoutée, ajouter une virgule, et faire un retour à la ligne.

 **Exemple :**
 - pour un verset:  `Lc 10:5,`
 - pour deux versets:
```
Lc 10:5,
Lc 13:43,
```

- Classez vos ordonnances dans le ou les fichiers adaptés en enregistrant toute modification dans la ou les branche(s) concerncée(s).

 **Exemple :**
 - Si je veux ajouter toutes les ordonnances qui sont dans l'épitre aux hébreux, je me place sur la branche "livre" et ajoute les références des versets concerncés dans le fichier hébreux.csv et all.csv, puis 'commit' et 'push'.
 - Si je veux classer des ordonnances, je peux classer celles qui ont été ajoutées dans la branche livre et qui n'ont pas été encore classées ou sinon ajouter des ordonnances dans la branche livre (qui n'y ont pas encore été ajoutées) et les classer en même temps. Concrètement, si je veux classer des ordonnances par thématique, ou période ou autres, je me place sur la branche concernée, je classe dans les fichiers puis 'commit' et 'push'.


##### Condition pour ajouter les ordonnances d'un livre sur la branche master:
 - que les ordonnances du livre aient été classées dans toutes les catégories possibles (c'est-à-dire dans toutes les branches du repository (master exclue)). Une fois cette condition validée, il faut merger toutes les branches excepté master sur livre puis ensuite merger livre sur master.

##### Si quelqu'un souhaite modifier le Readme:
  - ne le modifier que sur la branche master.


### Tout le monde peut participer et est invité à le faire !
#### Si vous ne connaissiez pas Github avant, vous pouvez aussi m'envoyer par email votre aide pour que je l'ajoute au projet: gustavberloty2@gmail.com .
