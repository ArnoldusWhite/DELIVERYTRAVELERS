DELIVERYTRAVELERS
=================

[![Build Status](http://travis-ci.org/willkoua/deliverytravelers.png)](http://travis-ci.org/#!/willkoua/DELIVERYTRAVELERS)

## Table des matières
* [Auteur et copyright](#getting-copy)
* [Description](#getting-desc)
* [Technologies](#getting-tech)
* [Démarrage](#getting-started)
    * [Préréquis](#getting-prerequis)
    * [Configuration](#getting-config)
    * [Manipulation](#getting-manip)
    
<h2 id="getting-copy">Auteur et copyright</h2>

<h2 id="getting-desc">Description</h2>
<p><b>DELIVERYTRAVELERS</b> est un projet destiné à aider toutes personnes voulant se faire livrer ou voulant livrer
des paquets dans des endroits où les services postales ne sont pas très sur ou alors à des couts abordables. Cette 
plateforme permettra aussi à toute personnes voulant se faire un peu d'argent de profiter de leurs voyages pour 
livrer des paquets.

<h2 id="getting-tech">Technologies</h2>
Les différentes technologies utilisées sont:

* APACHE 2.4.18
* PHP 7.0.4
* PHPUnit
* MySQL 5.7.11
* JAVASCRIPT
* SYMFONY 3.3.4
* GIT

<h2 id="getting-started">Démarrage</h2>
<p><b><u>À noter:</u></b> Nous n'allons pas décrire dans les détails comment installer les technologies utilisées. 
Il est de votre responsabilité de les installer. Si vous éprouvez vraiment des difficultés à en installer certaines,
vous pouvez contacter <b>EN PRIVÉ</b> un des développeurs.</p>

<h3 id="getting-prerequis">Préréquis</h3>

Pour ce projet, nous utiliserons:

 * [composer](https://getcomposer.org/download/) pour gérer nos dépendances (coté serveur). 
 * [bower](https://bower.io/) pour gérer nos dépendances (coté client). 
 * [Gitflow](https://datasift.github.io/gitflow/IntroducingGitFlow.html) pour gérer notre dépot. 
 
 <h3 id="getting-config">Configuration</h3>
 
  1. Pour optimiser votre serveur, vous pouvez faire les configurations sur `php.ini` 
  [suivantes](http://symfony.com/doc/current/performance.html). 
  <b>ATTENTION!</b> Ne faites que les configurations sur le fichier `php.ini` et la commande `composer` 
  et non celles apres.
 2. Initialiser les parametres pour le mode développement. Pour cela, vous devez créer un fichier `parameters.yml`
      dans le repertoire `app/config/` et y inscrire le code suivant:
      <pre><code>
      parameters:
          database_host: 127.0.0.1
          database_port: null
          database_name: deliverytravelersDB
          database_user: root
          database_password: null
          mailer_transport: smtp
          mailer_host: 127.0.0.1
          mailer_user: null
          mailer_password: null
          secret: 18b55ed37b75219eb73f5d92f3a23e2ea8b5f5aa
      </code></pre>
      <b>IMPORTANT:</b> Respecter l'indexation et n'envoyé pas ce fichier dans le repo. Il est censé etre privé.

<h3 id="getting-manip">Manipulation</h3>

  1. Initialiser le projet en local [Astuce](https://help.github.com/articles/fork-a-repo/)
  2. Creer une base de donnée depuis votre PHPMyAdmin nommée `deliverytravelersDB` sous `utf8_general_ci`.
  3. Installer les dépendances coté serveur dont vous avez `composer install`
  4. Install les dépendances coté client `bower update`


<p><i>A Symfony project created on July 6, 2017, 2:36 pm.</i></p>
