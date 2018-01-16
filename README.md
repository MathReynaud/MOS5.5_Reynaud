# Interactive Data Visualization - Rendu n°1 

# Bar Chart

## Définition générale

Les bar chart, ou encore diagramme en bâtons sont des représentations très classiques de données. Les caractères sont soit qualitatifs, soit quantitatif discrets. Les diagrammes en bâtons se distinguent donc des histogrammes qui permettent de traiter le cas des caractères quantitatifs continus. 

Le principal but des diagrammes en bâtons est de comparer des groupes de données entre elles.

Il existe principalement deux types de diagrammes en bâtons :
* les diagrammes en bâtons vertical. On reprédente pour chaque modalité d'une variable discrète un rectangle dont la hauteur représente la valeur d'une variable continue et dont la largeur n'a pas d'importance. Ci-dessous se trouve un exemple très simple. 

<image src="http://www.itse.be/statistique2010/res/Fig_org_04.jpg" alt="Histogramme Simple" width="400" align="center">

* Les diagrammes en bâtons horizontal. Cette fois-ci c'est la largeur du rectangle qui réprésente la valeur de la variable continue et la hauteur de ce rectangle qui n'a pas d'importance statistique. Ci dessous se trouve un exemple très simple.

<image src="https://sites.google.com/site/rgraphiques/_/rsrc/1495529900208/realiser-des-graphiques-avec-le-logiciel-r/diagrammes-en-barres/diagramme-en-batons-a-barres-horizontales/Rplot001.jpg" alt="Diagramme horizontal" width="400" align="center">

## Historique 

William Playfar est un écossais qui a lui seul a développé un grand nombre de graphiques que nous utilisons encore aujourd'hui. C'est en 1786, dans son livre <I>Commercial and Political Atlas</I> qu'il a crée le premier diagramme en bâtons. 

<image src="http://jplusplus.github.io/guide-du-datajournalisme/figs/incoming/06-TT-01.gif" alt="Premier diagramme bâton" width="400" align="center">

Ce diagramme illustre les différentes importations et exportations de l'Ecosse. 

Cependant, le Français Nicole Oresme, avait déjà utilisé déjà 20 ans plus tôt une forme moins conventionnelle de diagramme en bâtons. C'est pourquoi certaines personnes lui attribu l'invention de ce diagramme. Grâce à ces diagrammes il avait représenté la vitesse d'un object en accélération constante en fonction du temps. 

<image src="http://www.jpowered.com/graphs-and-charts/images/nicole-oresme-bar-charts-420x615.png" width="400" align="center">

Par la suite, cette répresentation sera de nouveau utilisée par exemple par André-Michel Guerry en 1883 dans l'<I>Essai sur la statistiques morale de la France</I>.

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/Essai_sur_la_statistique_morale_de_la_France%2C_Plate_VII%2C_1833.jpg/468px-Essai_sur_la_statistique_morale_de_la_France%2C_Plate_VII%2C_1833.jpg" width="400" align="center">

## Variantes

Il existe plusieurs variantes des diragrammes en bâtons.

* ### Diagrammes en bâtons empilés

Le but des diagrammes en bâtons empilés est des comparer les totaux et d'identifier rapidement les variations au seins des catégories pour comprendre ce qui peut avoir affecté la variation globale. 

<image src="https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/948c895a-e1b1-4c8f-b7f3-e0555a4ae589/5-stacked-bar-chart-800w-opt.png" width="500" align="center">

Par exemple pour l'exemple ci-dessous, on remariqe facielemnt que la stratégie 5 a été bien moins efficace que toutes les autres stratégies, et ceci est dû au fait que très peu de produit D on été vendus. 

* ### Diagrammes combinés

Le diagramme combiné est une visualisation qui regroupe un diagramme en bâton et un graphique linéaire. On peut par exemple reprendre l'exemple précédent pour obtenir les mêmes informations mais sous une forme différente. 

<image src="https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/9cdfe396-4155-4e7f-9c70-6fb2e290b71d/7-combined-multi-series-bar-and-line-chart-800w-opt.png" width="500" align="center">

Cette fois-ci le total est représenté par un graphique linéaire. De manière générale, ce genre de diagramme est souvent moins clair et des diagrammes en bâtons empilés permettent d'obtenir les mêmes informations avec une lecture plus facile. 


Définition Générale
https://fr.wikipedia.org/wiki/Représentation_graphique_de_données_statistiques

Examples historiques
http://jplusplus.github.io/guide-du-datajournalisme/pages/0706.html

Diagramme en bâton du Français 20 ans plus tôt
http://www.jpowered.com/graphs-and-charts/bar-chart-history.htm

Différences entre diagrammes en batons et histogrammes
http://mathematiques.ac-bordeaux.fr/profplus/docmaths/statistiques/artigues/chapitre2.pdf

Diagrammes empilés
https://www.smashingmagazine.com/2017/03/understanding-stacked-bar-charts/
