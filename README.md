# Symfony Sample Application "My Albums"

## Idea
This project arose while writing a blog article about PHP frameworks and the first steps with Symfony.

The application is simple manager for music albums. The idea is inspired by the tutorial of the Zend Framework.

There is just one entity **Album** with **artist** and **title** fields. The application uses **Twitter Bootstrap** and the 
[Bootstrap for Symfony2](http://bootstrap.braincrafted.com/) bundle.

## Installation

* git clone git@github.com:bjoerne2/symfony-myalbums.git
* cd symfony-myalbum
* Create database, e.g. symfony_myalbums
* Install composer ([http://getcomposer.org/](http://getcomposer.org/))
* composer update --prefer-dist
* php app/console doctrine:schema:update --force
* Open in Browser: http://localhost/symfony-myalbums/web/app_dev.php/album/

## Blog

My blog is written in **German**.

Blog articles (in german)

* [Symfony Teil 1: Vergleich von PHP-Frameworks](http://www.bjoerne.com/symfony-vergleich-von-php-frameworks)
* [Symfony Teil 2: Scaffolding mit der Kommandozeile](http://www.bjoerne.com/symfony-scaffolding-kommandozeile)
* [Symfony Teil 3: Twitter Bootstrap und Custom CSS](http://www.bjoerne.com/symfony-twitter-bootstrap-custom-css)

