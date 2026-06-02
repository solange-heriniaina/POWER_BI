A- DESCRIPTION DU PROJET - ADIDAS REVENUE INSIGHT (US)
Ce projet Power BI a pour objectif d’analyser les performances commerciales d’Adidas aux États-Unis à travers différents indicateurs financiers et opérationnels. Le tableau de bord permet d'explorer l'évolution du chiffre d'affaires, de la rentabilité, des ventes par produit, des canaux de distribution et des performances régionales afin d'identifier les principaux leviers de croissance.

 Objectifs des analyses

Les analyses réalisées dans ce dashboard couvrent plusieurs axes :

1. Analyse des indicateurs clés (KPIs)

Suivi des principaux indicateurs de performance :
Revenue (Chiffre d'affaires total)
Nombre de produits vendus
Profit opérationnel
Nombre de détaillants (Retailers)
Nombre de villes couvertes

Chaque KPI est comparé à la période précédente afin de mesurer l'évolution en pourcentage (Year-over-Year).

2. Analyse temporelle des performances

Visualisation de l'évolution mensuelle : Chiffre d'affaires cumulé, Profit opérationnel cumulé

Cette analyse permet d'identifier :
Les tendances de croissance au cours de l'année
Les périodes de forte activité commerciale
La corrélation entre les ventes et la rentabilité

3. Analyse des méthodes de vente

Répartition du chiffre d'affaires selon les canaux de distribution :
In-store, Online, Outlet

Objectifs :
Identifier le canal le plus performant
Mesurer la contribution de chaque canal aux revenus globaux
Comprendre les habitudes d'achat des clients

4. Analyse géographique

Analyse du chiffre d'affaires par région :
West, Northeast, Southeast, Midwest, South

Cette vue permet :
D'identifier les régions les plus rentables
De comparer les performances selon les canaux de vente
D'orienter les stratégies commerciales régionales

5. Analyse des produits

Classement des catégories de produits selon leur chiffre d'affaires :
Men's Street Footwear
Women's Apparel
Men's Athletic Footwear
Women's Street Footwear
Men's Apparel
Women's Athletic Footwear

Cette analyse aide à :
Identifier les produits les plus performants
Comprendre les préférences des consommateurs
Optimiser les décisions marketing et d'approvisionnement

B- DESCRIPTION DU DATASET

Le projet s'appuie sur le fichier Adidas US Sales Dataset, contenant les ventes réalisées par Adidas auprès de différents distributeurs aux États-Unis.

Caractéristiques du dataset
Nombre de lignes : 9 648 transactions
Nombre de colonnes : 14 variables
Période couverte : du 1er janvier 2020 au 31 décembre 2021
Zone géographique : États-Unis
Niveau de granularité : une ligne correspond à une transaction de vente associée à un produit, un détaillant, une localisation et un canal de vente.

L'année 2020 est utilisée comme année de référence (N-1) afin de mesurer l'évolution des performances en 2021. Cette comparaison permet de calculer les indicateurs de croissance (Year-over-Year)

C- MODELISATION
Afin d'optimiser les analyses temporelles et les calculs DAX, une table de dates (Calendar Table) a été créée dans Power BI.
Une relation de type One-to-Many (1:*) a été créée entre : la colonne Invoice_date et la colonne Date de Calendar_table
Cette modélisation permet d'effectuer des analyses temporelles fiables.

RESULTAT:
Le dashboard fournit une vue consolidée des performances commerciales d'Adidas aux États-Unis et facilite la prise de décision grâce à des analyses interactives sur les ventes, la rentabilité, les produits, les régions et les canaux de distribution.