# _OhMyFood project realised by Stan Suhail Adhin_
------------------------------------------------------
*Bienvenue sur mon profil Github, et dans le projet 4 OhMyFood, réalisé par moi.*
*Projet accepté est réalisé par Stan Suhail Adhin.*
*Vous trouverez le brief ici en [pdf](https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/IW_P4+Animations+CSS+Ohmyfood/Brief+creatif+site+Ohmyfood.pdf).*
*le guide des étapes clés en [pdf](https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/IW_P4+Animations+CSS+Ohmyfood/Guide+d%E2%80%99etapes+cles+-+OhMyFood.pdf).*

> Voici le lien de ma page publié sur github (https://suhailadhin.github.io/ohmyfood/).

![image de OhMyFood](https://github.com/suhailadhin/ohmyfood/blob/main/assets/documentation%20et%20image/16559011566667_FR_1117_P4_Banner-Ohmyfood.png)

## *Debrief du projet*

### _Présentation de l'entreprise_

> Ohmyfood est une entreprise de commande de repas en ligne. Notre concept permet aux
utilisateurs de composer leur propre menu et de réduire leur temps d’attente dans les
restaurants, car leur menu est préparé à l’avance. Plus de perte de temps à consulter la
carte !.

> Paul est un entrepreneur qui souhaite crée une plateforme non-fonctionel auprès des ces
fournisseur afin que les clients puissent regarder les menus de chaque restaurants.

> Nous souhaitons proposer à nos clients les menus de restaurants gastronomiques. Après
l’avoir développé à New-York dans un premier temps, nous souhaitons désormais élargir
notre concept à la capitale de la gastronomie : Paris.

> Classes moyennes et supérieures, connectées et souvent pressées, souhaitant déguster des
produits de qualité.

> Paul a fait appel à OpenClassroom pour crée un site web front, OpenClassroom a fait appel
à un étudiant afin de réaliser le projet pour Paul.

> La maquette est soigneusement préparé est publié sur [Figma](https://www.figma.com/file/t4449fzDnwGYmzuwQdu87V/Maquettes-Ohmyfood-(mobile-et-desktop)?node-id=0%3A1&mode=dev).

### _Objectif attendu du développeur par Paul_

![imageIllustrationPaul](https://github.com/suhailadhin/ohmyfood/blob/main/assets/documentation%20et%20image/16559016787093_Untitled%20design.png).

> Nous nous positionnons sur un marché de niche, avec les restaurants luxueux des villes
dans lesquelles nous sommes établis. Nous souhaitons être identifiés comme une
entreprise proposant des services haut de gamme.

##### *Budget*
- 20000 euros.

##### *Planning*
- sous 1 mois.

#### Présentation de développeur chargé du projet OhMyFood

> Mission accepté par le développeur Adhin Suhail Stan.
  Etudiant chez OpenClassroom, il prépare son diplome d'intégrateur, pour valider son diplome,
  il doit validé le projet OhMyFood. Il doit respecter le cahier de charge, le guide des étapes,
  il doit faire un repository en faisant des commits nécessaire afin que le projet sera terminé
  dans le temps indiqué dans le **débrief**.
  il doit ensuite validé son code via le lien de Github [GithubPagesRepository](https://github.com/suhailadhin/ohmyfood).
  auprès du **W3C**.

### _Livrables_
------------------------------------------------------------------------------------------------------------
- 1.Développer un site web en se basant sur La maquette [Figma Maquette](https://www.figma.com/file/t4449fzDnwGYmzuwQdu87V/Maquettes-Ohmyfood-(mobile-et-desktop)?node-id=0%3A1&mode=dev).

- 2.Utiliser un éditeur de code, le développeur utilsera l'éditeur VsCode.

#### _Animation_
-----------------------------------------------------------------
> Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser
les animations ou transitions CSS, pas de JavaScript ni de librairie. Pour toutes les
animations, afin de soigner le rendu du site, il est important que lorsque nous avons un effet
au hover ou lors d’un clic, nous ayons l’effet inverse lorsque l’on quitte le survol.

##### *boutons*
> Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
L’ombre portée devra également être plus visible.
<>À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se
remplir progressivement. Pour cette première version, l’effet peut apparaître au
survol sur desktop au lieu du clic.

##### *Pages d'accueil*
> Quand l’application aura plus de menus, un “loader” sera nécessaire. Sur cette
maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3
secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
graphique du site.

##### *Pages de menu*
> À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
décalage dans le temps. Ils pourront apparaître soit un par un, soit par groupe
“Entrée”, “Plat” et “Dessert”.

> Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
des points de suspension.

##### *Transition entre chaque clique de la page*

> Lorsqu'on arrive à la page d'accueil un loader doit apparaitre et
disparaitre sous 3s et lorsqu'on clique sur l'une des pages, il doit
apparaitre. Il doit etre stylisé sous Sass et compilée en css.

#### _Language informatique_
---------------------------------------------------------
- [x] #739 Ne pas utilser Javascript/ Frameworks/ Boostrapp.
- HTML, CSS, SASS.

#### _Notes_

##### *Style de police*
- Texte: Roboto via google font.
- Titre: Shrikhand.

##### *couleur*
- Primaire #9356DC;
- Secondaire #FF79DA;
- Tertiaire #99E2DO;


#### _Intégration de la maquette_
------------------------------------------------------------------------------------------------------------------------------------

- Intégrer une maquette responsive en respectant les breakpoints (mobile-first/tablette/desktop).

- Intéger l'animation demandée sur le prototype [Figma Animation](https://www.figma.com/proto/t4449fzDnwGYmzuwQdu87V/Maquettes-Ohmyfood-(mobile-et-desktop)?node-id=25368-591&scaling=scale-down&page-id=0%3A1&starting-point-node-id=25368%3A591&show-proto-sidebar=1).


- Crée un repository, commiter pour chaque étape réaliser, déployer le code sur githubpage.

##### *Validation de chaque étape*

- Chaque pages réaliser doit etre valider auprès de [W3C](https://validator.w3.org/);

- Circuit de validation : toutes les étapes du projet seront validées par Paul.

#### *Tester le projet*

Pour tester simplement & rapidement, veuillez préférer visiter la démo en ligne : [https://suhailadhin.github.io/ohmyfood/](https://suhailadhin.github.io/ohmyfood/)

Sinon, clonez le projet
```terminal
git clone https://github.com/suhailadhin/ohmyfood.git
```
Installez les dépendances de Sass
```terminal
npm install -g sass
```
> Telechager le dossier dart-sass/ ensuite crée un dossier .gitignore
