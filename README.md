# La Réunion DataCup Challenge 2024 - Eaupen Atlas

La [Réunion DataCup Challenge](https://data.regionreunion.com/p/page-reunion-datacup-challenge) est un événement unique où toutes les compétences en manipulation de données sont mises à l’honneur : extraction, traitement, modélisation… Porté par la Région Réunion, *La Réunion DataCup Challenge* s'inscrit dans un cadre de coopération avec les producteurs de données du territoire souhaitant ouvrir, mutualiser et valoriser leurs données. Les thématiques des partenaires sont variées : de la préservation des ressources à l’économie, ou encore des préoccupations des collectivités territoriales et de leurs habitants.

L’objectif de cette seconde édition est de continuer à fédérer une communauté autour des données ouvertes du territoire ainsi qu'initier des projets pérennisables et utiles au plus grand nombre.


## Nom de l'équipe

Notre équipe a choisi de répondre au défi Catch Water If You Can porté par l'Office de l'eau.
Ce défi s'inscrit dans le contexte suivant :

L’eau est une ressource précieuse qu’il faut préserver. Face aux besoins croissants et à la raréfaction de la ressource en eau, notamment en saison sèche, il est primordial de repenser nos usages et d’imaginer des solutions pérennes pour économiser l’eau. La récupération de l’eau de pluie constitue un levier important pour viser la sobriété des usages.

Il est aujourd’hui réglementairement possible de récupérer les eaux issues des toitures pour différents usages, principalement l’arrosage extérieur et l’alimentation des WC.

Dans le but de faciliter l’installation de récupérateurs d’eau de pluie, l’Office de l’eau Réunion souhaite moderniser son outil de calcul en ligne à destination des citoyens et des partenaires techniques. Le calcul constitue une aide au dimensionnement de volumes de cuves en fonction de la localisation, de la surface de toiture et des usages du bénéficiaire (particulier, ERP,…).

Il a pour objectif de disposer d’un outil ergonomique et innovant permettant :

1) d’évaluer :
 * le volume d’eau de pluie récupérable en fonction de la localisation géographique et de la surface de toiture,
 * les besoins liés aux usages du bénéficiaire,
2) de calculer
 * le volume optimal d’une cuve de récupération d’eau de pluie,
 * les économies réalisées que ce soit au niveau de la ressource en eau, de la facture d’eau.

Visualiser les résultats sous forme ludique et exploratoire (résultats sous forme de graphique, données d’entrée ajustables par l’utilisateur, données et objets graphiques cliquables, ...)

Ces éléments permettront de mieux sensibiliser les bénéficiaires aux besoins de sobriété des usages et sur le potentiel d’eau de pluie récupérable.


## **Documentation**

Notre solution répond au problème de cacluler dynamiquement au travers d'un site web, la quantité d'eau recupérable sur une toiture. Elle consiste à ... . Cette solution s'adresse aux particuliers voulant savoir s'il peut économiser, et quelle est capacité de cuve optimale pour son usage.

Notre solution est basé sur des outils open source d'open atlas, et une connexion à la base de Météo France pour la pluiviométrie, et la BD ortho pour l'affichage de tous les batiments et le calcul de surface des toitures.


### **Installation**
La base des outils se trouvent sur le gitlab de la plate-forme FusionForge ADULLACT.

https://gitlab.adullact.net/pixelhumain

[Guide d'installation](/INSTALL.md)

### **Utilisation**

**documentation d'utilisation de la solution**

La page permet donne des informations concernant la récupération d'eau, et l'usage. 
Nous avons un calculateur de surface de toit.

#### **ROD MON KAZ**
Une carte qui permet à la personne d'obtenir la surface de la toiture calculé à partir des données géo ( TODO : apporter une précision ici ).
On entre l'adresse et on voit la maison. Ensuite, le résultat de la surface s'affiche.


#### **Ouverture offertes**
 Dans l'optique d'économiser des ressources, de l'énergie et des euros € : on ne se limite pas qu'au potentiel d'eau récupérable. 
 Un lien vers l'outil cadastre solaire est présent. 
 
  **Votre potentiel d'énergie solaire**
 
  **Votre potentiel d'énergie éolienne**

  
### **POC : TRAP LO LA PLI**
Vous pouvez tester notre solution ici :
[Trap lo la pli](https://qa.communecter.org/costum/co/index/slug/reunionEau/#welcome)

### **Contributions**

Si vous souhaitez contribuer à ce projet, merci de suivre les [recommendations](/CONTRIBUTING.md).

### **Licence**

Le code est publié sous licence [MIT](/licence.MIT).

Les données référencés dans ce README et dans le guide d'installation sont publiés sous [Etalab Licence Ouverte 2.0](/licence.etalab-2.0).
