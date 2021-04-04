# Todo - condition d'utilisation
> Cerbère version `1.8.0` ou supérieur

En utilisant la commande `[prefix]todo [parametre]` vous affirmez avoir lus et aprouvé l'ensemble de ces conditions d'utilisations.

***
### Sommaire :
  - [1. Conservation des données](#1-conservation-des-données)
  - [2. Utilisation](#2-utilisation)
  - [3. "Droit"](#3-droit)
  - [4. Important](#4-important)
***

## 1. Conservation des données

- Vos informations sont stockées dans le serveur qui exécute le script du bot où sont contenus ces informations.
- Vos données sont conservés dans un fichier `.json` avec l'ensemble des données des autres utilisateurs.
- Cependant il est possible que le contenu de votre todo soit enregistré dans le fichier de façon "encoder" de cette façon le contenu de votre todo ne sera pas lisible depuis le fichier (attention cette action est irréversible et peut engendrer un temps de charge plus long pour les commandes todo de plus l'encodage ne sera appliqué que sur les commandes ajout ou modification qui suivront l'activation de l'encodage).
    >__Exemple :__
    >
    >*En entrée :*
    >```fix
    >Farmer 1000xrubedo pour don dans le clan
    >```
    >*En sortie :*
    >```fix
    >0cc001507s54jI766U0Dm3828u123he.2777F74aB.1019a31wA.688J52bZ.229r15IY.3425J101rE.4777u97Wv.2477v70PH.2015j77qR.2015j77qR.2015j77qR.125E19fz.688J52bZ.2718u104pm.364w19aa.4109v64Iy.404Q20aV.30h9dL.4777u97Wv.565T41Wq.30h9dL.2718u104pm.688J52bZ.4777u97Wv.404Q20aV.30h9dL.4114Q64QG.4777u97Wv.404Q20aV.1019a31wA.4114Q64QG.12U4Ug.4777u97Wv.896P0ZQ.4109v64Iy.4777u97Wv.921x0Sq.896P0ZQ.1019a31wA.4114Q64QG
    >```
    >*A noter que le script d'encodage garde en memoire les clés de décodage pour permetre le decodage des informations stockées et que celui-ci a été crée par nous et ne relève pas d'un autre système d'encodage*
- Il vous est possible de supprimer toute trace de votre utilisaion de la todo en utilisant la commande : `[prefix]todo deluser` (attention cette action est irréversible).
- __Vos données sont enregistré sous cette forme :__
    ```json
    {
        "iduser": {
            "default": {
                "éléments": [
                    "Element1",
                    "Element2",
                    "Element3",
                    "Element..."
                ],
                "sous_classe_default": {
                    "éléments": [
                        "Element1",
                        "Element2",
                        "Element3",
                        "Element..."
                    ]
                }
            },
            "classe_thème": {
                "éléments": [
                    "Element1",
                    "Element2",
                    "Element3",
                    "Element..."
                ],
                "classe_sous_thème": {
                    "éléments": [
                        "Element1",
                        "Element2",
                        "Element3",
                        "Element..."
                    ]
                }
            }
        }
    }
    ```
    >#### __Nous collectons donc :__ 
    >* `iduser` : votre `id` d'utilisateur (qui est lié à votre compte Discord).
    >* `Element`, `classe`, `thème`, `élements`, `Element[index]` : definie par les commandes que vous avez effectué ainsi que le contenu que vous avez fournie.
- Vous pouvez voir à tout momment vos données enregistrées avec la commande `[prefix]todo view` (si votre todo est "encodé" vous la verrez sous sa forme tel qu'elle soit enregistré donc sous forme "encodé").
- Dans le cas de perte de données, corruption, vole ou autre problème nous ne nous portons dans aucun cas responsable des problèmes engendré et responsabilité.
- Aucune issue d'erreur ou d'enregistrement n'est gardée dans les logs du script du bot par respect de la non conservation d'information "inutile ou qui pourrais être sensible".
***
## 2. Utilisation

- Nous considérons l'utilisation de la commande `[prefix]todo [parametre]` dans un cadre [*publique**](#*Publique**-:) de se fait nous considerons aussi l'ensemble de vos données comme [*publique**](#*Publique**-:).
- Il est donc fortement déconseillé de stocker au sein de la todo toutes informations personnelles ou sensible (mot de passe, indentifiant ou autre information personnel qui ne devrais pas se retrouver dans le dommaine [*publique**](#*Publique**-:)).
- Lorsque vous utiliser la commande `[prefix]todo [parmetre]` vous ête l'unique et le seul responsable de sont utilisation et du contenue de celle-ci.
***
## 3. "Droit"

- Vous pouvez à tout momment supprimer l'ensemble des données stockées par la commande en effectuant la commande : `[prefix]todo deluser`.
- Vous pouvez aussi voire l'ensemble des données recupérer en utilisant la commande : `[prefix]todo view`.
- Si vous n'accepter pas l'ensemble des conditions d'utilisation de la todo vous ne serez soumis à aucune forme de collecte de données mais vous ne pourrez donc nullement utiliser la commande `[prefix]todo [parametre]` (A noter que pour reconnaitre la validtion de l'acceptation des conditions d'utilisation votre `id` et stocker pour une duré de 10min avant d'être totalement supprimer après se délais le bot ne gardera pas en memoire votre passage).
***
## 4. Important

- Nous ne nous portons nullement garant de toute utilisation de la commande `[prefix]todo [parametre]` et rejetons toute responsabilitée liée à une mauvaise utilisation de celle-ci, l'utilisateur étant le garant et responsable de l'utilisation qu'il en fait.
- De même que nous ne nous portons nullement responsable en cas de perte, vole, corruption, supression ou autre de vos données.
- Par ailleurs, vos données ne seront transmises en aucun cas à une tierce partie, de même qui ne seront non plus en aucun cas traitées par un sricpt (hormis le script d'encodage qui se charge d'encoder les données par ailleurs, il ne garde en memoire que les clées de décodage pour les différents encodages)
- En cas de problème ou autre, nous nous autorisons la lecture du contnenu de votre `todo` pour touvrer la raison ainsi qu'une solution à votre porblème.
- En utilisant la todo vous affirmez avoir lu et accepté l'ensemble de ces conditions d'utilisations.
***

<br>
<br>

> #### *Publique** : 
>*Nous considerons l'utilisation de la commande dans un salon publique et donc que l'ensemble des membres de celui-ci vois le contenu de votre commande (`[prefix]todo [parametre]`)*

<br>

[revenir en haut](#Todo---condition-d'utilisation)
