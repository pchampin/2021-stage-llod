# Stage: Base de Connaissances cartographique pour les linguistes

## Contexte

On recouvre sous le terme *Linked Data* un ensemble de [principes][ld] énoncés par Tim Berners-Lee (l'inventeur du Web), et de standards du W3C pour représenter et échanger des données de manière interopérable et décentralisée. Ces principes ont été adoptés par un certain nombres de projets et bases de données ouvertes, en particulier [Wikidata] (un projet de Wikipedia) et [Geonames] (un référentiel géographique).

Ces principes ont également été largement appliqués dans le domaine de la linguistique; on parle alors de *Linguistic Linked Open Data* ou [LLOD].

Les linguistes qui souhaitent publier des données liées se heurtent à un problème récurrent: les zones géographiques dans lesquelles différentes langues sont parlées ne correspondent que rarement à des découpages géographiques « administratifs », comme un (groupe de) pays, une région ou un département. Or, ce sont ces découpages qui sont munis d'identifiants dans un référentiel comme [Geonames]. Il n'y a donc pas de moyen simple et uniforme d'indiquer, sur le [LLOD], dans quelle région du monde une certaine langue est parlée.

## Objectif du stage

L'objectif de ce stage est double. Il consiste à mettre en place :

* une base de données ouverte et accessible en ligne, respectant les [principes du Web de données][ld], visant à héberger un référentiel géographique dédié à la linguistique, et complémentaire de [Geonames];

* une application Web permettant d'alimenter cette base de manière collaborative. Une attention particulière devra être portée à l'ergonomie de cette application, puisque les utilisateurs ciblés sont des linguistes, en général peu familiers des techniques de modélisation de données.

[ld]: https://www.w3.org/DesignIssues/LinkedData.html
[Wikidata]: http://wikidata.org/
[Geonames]: https://www.geonames.org/
[LLOD]: http://www.linguistic-lod.org/