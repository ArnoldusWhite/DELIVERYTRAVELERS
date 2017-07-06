DELIVERYTRAVELERS
=================

[![Build Status](http://travis-ci.org/willkoua/deliverytravelers.png)](http://travis-ci.org/#!/willkoua/DELIVERYTRAVELERS)

## Table des matières
* [Description](#getting-desc)
* [Technologies](#getting-tech)
* [Démarrage](#getting-started)
    * [Préréquis](#getting-prerequis)
    * [Configuration](#getting-config)
    * [Manipulation](#getting-manip)

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
 
 Pour optimiser votre serveur, vous pouvez faire les configurations sur `php.ini` [suivantes](http://symfony.com/doc/current/performance.html). 
 <br><b>ATTENTION!</b> Ne faites que les configurations sur le fichier `php.ini` et la commande `composer` et non celles apres.

<h3 id="getting-manip">Manipulation</h3>

  1. Initialiser le projet en local [Astuce](https://help.github.com/articles/fork-a-repo/)
  2. Creer une base de donnée depuis votre PHPMyAdmin nommée `deliverytravelersDB` sous `utf8_general_ci`.
  3. Installer les dépendances dont vous avez `composer install`

A Symfony project created on July 6, 2017, 2:36 pm.
