# Développement logiciel *FLOSS*
*Par Sayah El Yatim ([@sqyqh](https://github.com/sqyqh "GitHub - Sayah El Yatim")) et Thibault Truffert ([@cevantime](https://github.com/cevantime "GitHub - Thibault Truffert")) sous licence [CC-by 4.0](LICENSE.md)*

---

***Attention :***
*Le QCM prévu ce jeudi 27 janvier se déroulant en distanciel (conditions sanitaires obligent), vous pourrez donc, même si les ressources ne sont pas toutes sur le dépôt, rechercher les réponses attendues en ligne ou sur toute autre document pertinent pour y répondre.*

***Rappel :***
*Votre contribution correspond à 80% de la notation finale, à laquelle s'ajoutent les 10% du QCM, ainsi que les 10% de participation orale/écrite tant en formation que sur ce dépôt.*

---

## Définitions
*Free/Libre/Open-Source Software (FLOSS)* est une expression qui permet à la fois de désigner les logiciels libres et les logiciels à code source ouvert. Ces deux modèles différent dans leur philosophie, mais leur modes de développement logiciel restent similaires.

Attention, un logiciel libre, ou *Free software* n'est pas forcément un logiciel gratuit. Les logiciels libres peuvent être payants, comme par exemple *RedHat Linux*.

 Plus globalement, en termes de types licences, on a par exemple :
 - *Freeware* : logiciels gratuits,
 - *Shareware* : logiciels payants AVEC période d'essai gratuite. Dans cette famille de licence, on y trouve aussi,
 - *Free Software* : logiciels libres, on considère parfois aussi certains logiciels *open-source* comme tels,
 - *Abandonware* : logiciels considéré comme abandonné car n'est plus mis en vente, ni mis à jour.

### *Open-Source*
 Selon l'[OSI](https://opensource.org/) (*Open Source Initiative*), l'approche *open source* est définie par ces **10 principes** :

 1. Redistribution libre
 2. Disponibilité du code source
 3. Travaux dérivés
 4. Intégrité du code source de l'auteur
 5. Non discrimination de personne ou groupe
 6. Non discrimination de domaine ou compétence
 7. Distribution de la licence
 8. Non spécificité à un produit
 9. Non restriction d'autres logiciels
 10. Neutralité technologique

### *Free software*, logiciel libre
 Selon la [FSF](https://fsf.org) (*Free Software Foundation*) dont le fondateur Richard M. Stallman est à l'origine du terme *free software*, l'approche du logiciel libre est légèrement différente bien que ressemblante techniquement avec celle de l'*open source*, un *logiciel libre* se définit par ces **4 libertés** :

 0. La liberté d'**utiliser** le logiciel, pour quelque usage que ce soit
 1. La liberté d’**étudier** le fonctionnement du programme, et de l’adapter à vos propres besoins
 2. La liberté de **redistribuer** des copies à tout le monde
 3. La liberté d’**améliorer** le programme et de **publier** vos améliorations

 **Ces libertés sont notées de 0 à 3**, comme d'usage dans un programme informatique. Le 0 ne représente donc pas ici la nullité.

 Ces deux approches diffèrent car l'une s'attache aux avantages liés au développement à travers la réutilisation d'un code source. L'autre est une approche sociale qui vise à construire une société de technologies libres.

 > « Pratiquement tous les logiciels « open source » sont des logiciels libres ; les deux termes décrivent pratiquement la même catégorie de logiciel. Mais ils représentent des vues basées sur des valeurs fondamentalement différentes. L'« open source » est une méthodologie de développement ; le logiciel libre est un mouvement social. » — Richard M. Stallman dans [Pourquoi l'« open source » passe à côté du problème que soulève le logiciel libre.](http://www.gnu.org/philosophy/open-source-misses-the-point.fr.html)

Une licence est **un contrat de droit privé de mise à disposition** (logiciel, matériel...).

**Le logiciel libre n'est pas :**
- "libre de droits" ou dans le "domaine public" car un logiciel libre appartient toujours à son auteur qui utilise une licence pour en préciser les conditions d'utilisation,
- "opposé à la propriété intellectuelle", car **le logiciel libre se fonde sur le droit d'auteur**.

**Le logiciel libre :**
- contribue à un patrimoine commun, universel,
- permet de s'approprier les technologies,
- changer notre façon de développer, distribuer et commercialiser les logiciels,
- retire les barrières à l'entrée comme avec les systèmes embarqués libérés : Arduino, Raspberry Pi, BIOS libres, microgiciels divers...

**Économie du logiciel libre en bref :**
- Dons, mécénats...
- Publicités (éventuellement)
- Ventes matérielles (support physique)
- Support (hotline, techniciens sur place etc.)
- Services (installation, mise à jour etc.)

On a donc des modèles économiques souvent bien différents de ceux de l'industrie traditionnelle. L'économie de dons et de service est très présente

*Le logiciel libre : son développement est distribué, ses cycles de développement sont très rapides, les interdépendances sont fortes, ses sources sont disponibles.*

## Histoire du logiciel
Au départ et jusqu'à la fin des années 60, les logiciels étaient fournis avec les ordinateurs, **distribués comme des compléments pour du matériel déjà très coûteux**.

> "Je pense qu'il y a un marché mondial pour peut-être cinq ordinateurs." - Thomas Watson, president d'IBM, 1943

## Droit d'auteur, Licences, Brevets

**4 outils essentiels à la protection d'une création originelle :**
- **secret industriel :** on cache les secrets de fabrications,
- **droit d'auteur :** permet de vendre ou de partager des licences d'utilisation du logiciel,
- **marque :** permet d'identifier et de reconnaître l'image publique d'un produit, d'une suite de produits, d'une entreprise, d'une association, d'une fondation etc.,
- **brevet :** protection d'une solution technique à un problème technique et qui ne s'identifie pas à un produit en particulier.

Quelques organismes à connaître concernant la protection de la Propriété Intellectuelle :
- ***INPI :*** Institut Nationale de la Propriété Intellectuelle (français),
- ***EPO :*** Bureau européen des brevets,
- ***USPTO :*** US Patent Office,
- ***WIPO/OMPI :*** Organisation Mondiale pour la Propriété Intellectuel (affilié aux Nations Unies).

### Droit d'auteur
En France, le droit d'auteur se fonde sur les textes du [*Code de la Propriété Intellectuelle*](https://www.legifrance.gouv.fr/codes/texte_lc/LEGITEXT000006069414/2021-01-21/)

Le droit d'auteur est un droit automatique :
> Article L111-1 du Code de la Propriété Intellectuelle
L'auteur d'une oeuvre de l'esprit jouit sur cette oeuvre, du seul fait de sa création, d'un droit de propriété incorporelle exclusif et opposable à tous.

À la fois moral :
> Article L121-1 du Code de la Propriété Intellectuelle
L’auteur jouit du droit au respect de son nom, de sa
qualité et de son oeuvre.
Ce droit est attaché à sa personne.
Il est perpétuel, inaliénable et imprescriptible.

Et patrimonial :
> Article L122-4 du Code de la Propriété Intellectuelle
Toute représentation ou reproduction intégrale ou
partielle faite sans le consentement de l’auteur ou de ses ayants droit ou ayants cause est illicite.


## Les licences GNU
## Organisation et Modèles économiques

---

## Projet : Appel à contribution
- Une présentation de **10 minutes** de votre contribution.
- Rapport de **3 à 4 pages** à rendre sur votre travail indiquant :
	- code qui a motivé votre choix de projet,
	- les acquis en classe / alternance qui vous ont permis de contribuer,
	- les différents échanges avec les responsables du projet,
	- les difficultés rencontrées (code, communication, organisation...),
	- la description de la requête envoyée et de son accueil par la communauté,
	- etc. la liste n'étant pas exhaustive et tous les moyens qui pourront appuyer la qualité de votre contribution seront évidemment les bienvenus !
- La contribution doit porter **sur du développement**, et non pas sur une quelconque documentation ou traduction.

---

## Pour aller plus loin
### Sitographie
- [*The Debian social contract.*](https://www.debian.org/social_contract#guidelines) Debian, 2004.
- [*The Open Source Definition.*](https://opensource.org/osd) Open Source Initiative, 2007.
- [*What is free software?*](https://www.gnu.org/philosophy/free-sw.en.html) Free Software Foundation, 2019.
- [*Philosophy of the GNU Project.*](https://www.gnu.org/philosophy/philosophy.en.html) Free Software Foundation, 2018.
- [*Open Source Guides.*](https://opensource.guide/) GitHub & friends, 2020.
- [*APRIL, promouvoir et défendre le logiciel libre.*](https://april.org) Association loi 1901.

### Bibliographie
- Raymond, Eric S. [*The cathedral & the bazaar : musings on Linux and open source by an accidental revolutionary.*](http://www.catb.org/~esr/writings/cathedral-bazaar/) O'Reilly, 1999.
- Williams, Sam. *Free as in freedom : Richard Stallman's crusade for free software*. O'Reilly, 2002.
- Fogel, Karl. [*Producing open source software : how to run a successful free software project.*](https://producingoss.com/) O'Reilly, 2005.
- Rosen, Lawrence E. [*Open source licensing : software freedom and intellectual property law.*](https://www.rosenlaw.com/oslbook.htm) Prentice Hall, 2005.
- Ghosh, Rishab A. *CODE : collaborative ownership and the digital economy*. MIT Press, 2005.
- Ribas, Stéphane (dir.). Guillaud, Patrick.  Ubeda, Stéphane. [*Logiciels et objets libres. Animer une communauté.*](https://framabook.org/logiciels-et-objets-libres/) Framasoft, 2016.
- Masutti, Christophe. [*Libertés numériques. Guide de bonnes pratiques à l’usage des DuMo.*](https://framabook.org/libertes-numeriques/) Framasoft, 2017.
- Paloque-Berges, Camille. Masutti, Christophe. [*Histoires et cultures du Libre. Des logiciels partagés aux licences échangées.*](https://framabook.org/histoiresetculturesdulibre/) Framasoft, 2013.
- Jean, Benjamin. [*Option Libre. Du bon usage des licences libres.*](https://framabook.org/optionlibre-dubonusagedeslicenceslibres/) Framasoft, 2011.
