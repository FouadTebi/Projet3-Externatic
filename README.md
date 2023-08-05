# Project 3 - EXTERNATIC

EXTERNATIC est un cabinet de recrutement spécialisé dans le domaine du numérique. Ils mettent en relation des entreprises avec des professionnels qualifiés tels que développeurs, ingénieurs informatiques et experts en cybersécurité. Leur expertise et leur réseau leur permettent d’identifier les talents adaptés aux besoins des entreprises. Externatic propose également des services de conseil en ressources humaines et en développement des talents. Leur connaissance pointue de l’industrie en fait un partenaire privilégié pour les entreprises à la recherche de compétences numériques.

## Développement du Site

### Collaboration de 5 personnes | Durée de création : 5 semaines

Dans le cadre de ce projet, une équipe de 5 personnes passionnées s'est réunie pour créer un site pour un cabinet de recrutement. Chaque membre de l'équipe avait un rôle spécifique défini afin de maximiser l'efficacité de notre collaboration.

Nous avons travaillé en étroite collaboration pendant une période de 5 semaines, en mettant en application nos connaissances techniques acquises dans les domaines du Symfony, PHP, du CSS et de Twig pour développer un site fonctionnel, convivial et attrayant.

### Besoins du client

EXTERNATIC souhaitait une refonte de leur site internet, développer une application web et mobile à destination des candidats, liée au site Externatic.fr. Cet outil vient en complément et support de leur expertises de consultants en recrutement.
Elle offre un accès à l’entreprise, au candidat et à l’administrateur. 
Le site permet le partage d’offres d’emploi et offre la possibilité aux candidats d’uploader leurs fichiers, tels que le CV. Cela simplifie le processus de candidature et favorise une expérience fluide pour les postulants.

### Fonctionnalités

-	Espace candidat / entreprise / admin avec login.
-	Un back-office pour gérer toutes les offres d’emploi ainsi l’enregistrement des entreprises (notamment pour valider ou supprimer un compte entreprise).
-	 Navigation fluide entre toutes les pages du site avec une expérience utilisateur optimale.
-	Recherche multicritère pour le candidat / Présentation des offres et quelques partenaires.
-	Prise en compte du statut du visiteur non connecté.

### Travail personnel

Pour ce projet j'ai réalisé la page d'offres d'emploi en totalité, soit côté front ou back.

- Réalisation du CRUD adéquate de cette page avec le framework Symfony.

- Création de la Dashboard candidat ainsi entreprise avec du Twig, scss et du JS.

- Mise en place du dark mode en scss et JS.

- Mise en place de la sécurité du formulaire de connexion et d'inscription.

## Technologies Employées

- HTML/SCSS
- Javascript
- PHP
- Symfony
- TWIG / Doctrine
- Composer / yarn
- MySQL
- Git/GitHub

## Les étapes pour visualiser le projet

Pour la visualisation du projet il faut suivre les étapes suivantes:

1. Vérifier si composer est installé sur votre ordinateur
2. Vérifier si yarn & node sont installés sur votre ordinateur

### Après ces étapes

1. Clonez le repository depuis Github.
2. Exécuter la commande `composer install`
3. Exécuter la commande `yarn install`
4. Exécuter la commande `yarn encore dev` pour build les assets

### Pour l'affichage

1. Exécuter la commande `symfony server:start` pour lancer le serveur web php local
2. Exécuter la commande `yarn run dev --watch` pour lancer votre serveur local de ressources (ou `yarn dev-server` faire de même avec Hot Module Reload activé)

### Utilisateurs Windows

Si vous développez sous Windows, vous devez éditer votre configuration git pour changer vos règles de fin de ligne avec cette commande:

`git config --global core.autocrlf true`

Le `.editorconfig` dans le répertoire racine. Vous avez probablement besoin de `EditorConfig` si votre IDE est VSCode.

### Exécuter localement avec Docker

1. Remplir DATABASE_URL variable en .env.local avec le fichier
`DATABASE_URL="mysql://root:password@externatic:3306/<choose_a_db_name>"`
2. Installez Docker Desktop et exécutez la commande:
```bash
docker-compose up -d
```
3. Attendez un peu et visitez http://localhost:8000

## Contrôle qualité

* [GrumPHP](https://github.com/phpro/grumphp)
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)
* [PHPStan](https://github.com/phpstan/phpstan)
* [PHPMD](http://phpmd.org)
* [ESLint](https://eslint.org/)
* [Sass-Lint](https://github.com/sasstools/sass-lint)

## Me contacter

Pour plus de renseignements contactez-moi sur [LinkedIn](https://www.linkedin.com/in/fouadtebi/), je suis plus réactif.

**Merci**.

