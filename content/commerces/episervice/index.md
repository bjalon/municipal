+++
fragment = "content"
weight = 100

title = "DELTA SUITE – AERO"
# [asset]
#  image = "image1.png"
  
summary = """
Epicerie ouverte
"""

+++

## Présentation


La version AERO est la déclinaison C3ISR du logiciel DELTA SUITE, édité par la société IMPACT. Cette version est utilisée en opération par le Commandement des Opérations spéciales Français.

La DELTA SUITE AERO est composée d’un système d’information géographique, combiné à des capacités avancées de communication et de gestion des capteurs embarqués. Plusieurs applicatifs métiers, détaillés ci-dessous, sont disponibles dans cette version.

En plus de la fonctionnalité de base « Moving Map » (permettant d’afficher dans le fond cartographique les données nécessaires au suivi efficace de la mission), la DELTA SUITE AERO offre un ensemble d’outils avancés permettant d’optimiser l’exploitation des capteurs ISR (vidéo augmentée, mode blanchiment, mode SLEW, etc.).

En termes de communications, sous réserve d’utiliser des moyens compatibles (PRC152 et 117, Inmarsat, Saturn, SRX Motorola, etc.), l’échange de données entre différents postes équipés de la DELTA SUITE est possible. La situation tactique globale peut ainsi être partagée avec un centre de commandement, un autre aéronef ou des éléments au sol.

Enfin, le respect de standards et protocoles militaires (VMF, COT, etc.) et civils permet une interopérabilité accrue de la solution avec des systèmes tiers.

## Fonctionnalités de base

Afin de permettre une synthèse rapide des informations primordiales, l’utilisateur a en permanence, sur son affichage principal, accès aux fonctionnalités suivantes :

* Coordonnées (MGRS, Long/Lat) et altitude (m & ft) ;
* Échelle graphique et numérique (m & Nm) ;
* Heure locale / universelle ;
* Outil de recherche (requête) ;
* Mode basique / avancé ;
* Outils de navigation dans la carte ;  
* Outils « aller à », géosignets, etc. ; 
* Outil de gestion temporelle ;
* Mesure (distance et azimut) ;
* Basculement vue 2D/3D.

##  Applicatif métier « Cartographie » : intégration de données et analyse de terrain

Cet applicatif métier apporte les fonctions suivantes :

* Import par glisser-déposer de différents formats de données géographiques : GeoTIFF, JPEG 2000, ECW, DTED/DMED, Shapefile, KML/KMZ, NITF, S57, USRP, ASRP, Mr Sid
* Chargement et gestion en 3D des messages ACO (Air Coordination Order) ;
* Dessin d’objets vectoriels (points, lignes, polygones, cercles, araignées, etc.) ;
* Calcul de Profils de pentes ;
* Calcul d’intervisibilité en 2D ou 3D, pouvant être asservis à des objets en mouvement.

## Applicatif métier « Moving map »

Il s’agit d’un applicatif métier dédié à l’exploitation de caméras (matériel compatible STANAG 4609, Wescam MX Series). Il propose de nombreuses fonctionnalités :

![Image 2](image2.png)

* Choix du type d’orientation de la vue (caméra, nord fixe, libre...) ;
* Saisie de commentaires (main courante) ;
* Affichage d’informations relatives à la cible (Target) ;
* Affichage de l’orientation de la caméra en azimut et élévation ;
* Gestion de multiples capteurs simultanément ;
* Mode SLEW (selon capteur) = ralliement à la caméra ;
* Affichage de la position de l’avion, de sa trace, de la target, du
footprint et du segment camera-target ;
* Rejeu de mission ;
* Mode blanchiment permettant de visualiser les zones déjà observées (code couleur en fonction du
nombre de passages et de la durée d’observation) ;
*   La vidéo augmentée avec affichage en surimpression des données vectorielles dans la fenêtre vidéo.

![Image 3](image3.png)


# Options

Des modules optionnels peuvent être ajoutés afin d’enrichir les fonctionnalités offertes par la DELTA SUITE :
* Connexion au système CSI de l’OTAN afin de pouvoir échanger des informations au travers de la Liaison 16 (position ami, ennemi, position avion, situation tactique air, etc.) ;
* Intégration des outils KESTREL de la société SENTIENT afin d’assurer une détection et un suivi automatique de cibles mobiles (sous conditions) ;
* Intégration des algorithmes de la société MAGELLIUM permettant de recaler automatiquement la vidéo sur des images de référence (sous conditions) ;
* Outil de messagerie instantanée, point à point ou en mode serveur (norme XMPP).

[Version PDF](./2019-03-28%20IMP_FP_DS_AERO.pdf)
