PROJET 3 OHMYFOOD - OPENCLASSROOMS

OBJECTIF : DYNAMISEZ UNE PAGE WEB AVEC DES ANIMATIONS CSS

TABLE DES MATIÈRES:

I.SCENARIO
II.FONCTIONNALITÉES
III.COMPÉTENCES ÉVALUÉES
IV.CONTRAINTES TECHNIQUES
  A.GENERAL
  B.CONTENU DES PAGES
    1. Page d’accueil (x1)
    2. Pages de menu (x4)
    3. Footer
    4. Header
  C.EFFETS GRAPHIQUES ET ANIMATIONS
    1. Boutons
    2. Page d’accueil
    3. Pages de menu
V.RESSOURCES ET TECHNOLOGIES
VI.ETAT DU PROJET

------------------------------------------------------------------------------------------------------------------------------------------

I.SCENARIO

Vous venez d’être recruté chez Ohmyfood en tant que développeur junior.
L'objectif est de développer un site 100% mobile qui répertorie les menus de restaurants gastronomiques.
En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée.

II.FONCTIONNALITÉES

- Les usagers pourront rechercher des hébergements dans la ville de leur choix.
  Le champ de recherche est donc un champ de saisie, dont le texte peut être édité par l’usager.
  En revanche, à ce stade, le bouton de recherche ne sera pas fonctionnel.
- Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité. Pour l’instant les liens seront vides.
- Les filtres ne seront pas fonctionnels pour cette version, en revanche, il faut qu’ils changent d’apparence au survol.
  L’effet le plus approprié nous est libre d'interprétation et de conception.
- Dans le menu, les liens “Hébergements” et “Activités” sont des ancres qui doivent mener aux sections de la page.

III.COMPÉTENCES ÉVALUÉES

- Utiliser un système de gestion de versions pour le suivi du projet et son hébergement.
- Mettre en place son environnement Front-End.
- Intégrer du contenu conformément à une maquette.
- Implémenter une interface responsive.

IV.CONTRAINTES TECHNIQUES:

  A.GENERAL
  
   - Maquette mobile fournies à respecter (version tablette et desktop libre de conception tant qu’aucun élément
     n’est coupé et que le texte a une taille suffisante).
   - Les couleurs de la charte sont: Primaire(#9356DC) Secondaire(#FF79DA) Tertiaire(#99E2D0).
   - Le développement devra se faire en CSS, sans JavaScript.
   - Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus.
   - Le code devra utiliser les balises sémantiques et ne doit contenir aucune erreur ni alerte au validateur W3C HTML et CSS.
   - Le site devra être compatible avec les dernières versions de Chrome et Firefox.
   - Séparer le HTML et le CSS et à organiser le dossier de rendu.
   - Versionner son code avec Git et déployer la page sur GitHub Pages ou GitLab Pages.
  
  B.CONTENU DES PAGES
  
    1. Page d’accueil (x1)

      - Affichage de la localisation des restaurants.
      - Une courte présentation de l’entreprise.
      - Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

    2. Pages de menu (x4)

      - 4 pages contenant chacune le menu d’un restaurant.

    3. Footer

      - Le footer est identique sur toutes les pages.
      - Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

    4. Header

      - Le header est présent sur toutes les pages.
      - Sur la page d’accueil, il contient le logo du site.
      - Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil
        
  C.EFFETS GRAPHIQUES ET ANIMATIONS
   
    1. Boutons
      
      - Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
      - L’ombre portée devra également être plus visible.
      - À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
        bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se
        remplir progressivement. Pour cette première version, l’effet peut être apparaître au
        survol sur desktop au lieu du clic.
        
    2. Page d’accueil
      
      - Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur
        cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à
        3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
        utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
        toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
        graphique du site.
        
    3. Pages de menu
      
      - À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
        décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe
        “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
         
      - Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
        Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
        la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
        sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
        des points de suspension. Un exemple de l’effet attendu est fourni.

V.RESSOURCES ET TECHNOLOGIES

- Git Bash
- GitHub
- Visual studio code (plugin : prettier)
- Fontawesome
- Google Fonts
- Openclassrooms
- HTML5
- CSS3
- SCSS
- SASS

VI.ÉTAT DU PROJET

-Version définitive en contexte de formation.
-Des modifications pourraient avoir lieu après Décembre 2021.

(auteur : Renaud Fagnou)