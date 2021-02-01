# Symfony-Reference

# All

New project without Git

    $ symfony new project1 --no-git

Help

    $ symfony new --help 

# Project Structure

Composer creates a Symfony application structure.

    $ ls -1ap --group-directories-first
    ./
    ../
    bin/
    config/
    public/
    src/
    var/
    vendor/
    .env
    .gitignore
    composer.json
    composer.lock
    symfony.lock

Directory | Description |
--- | --- |
`bin`       |   contains the `console` tool - a command-line utility to execute various types of commands
`public`    |   contains the web files. In a Symfony skeleton application, it contains one file: index.ph
`config`    |   contains the configuration files
`public`    |   contains the 
`src`       |   contains the source code
`var`       |   contains temporary files
`vendor`    |   contains third party dependencies
&nbsp;      |   &nbsp;
.env        |   &nbsp;
.gitignore  |   &nbsp;

# Components

## Installation

    $ composer require symfony/asset

    $ composer require symfony/string 

## Component List

Component | Description | Resources
--- | --- | --- |
Asset | Manages URL generation and versioning of web assets such as CSS stylesheets, JavaScript files and image files | &nbsp;
BrowserKit | Simulates the behavior of a web browser | &nbsp;



# Fast Track Book Review

## Step 1: Checking Work Environment

<b>Work Environment<b>

<ol>
<li>A Computer</li>
<li>Choose database (MySQL), queue manager etc</li>
<li>IDE - Visual Studio Code</li>
<li>Terminal</li>
<li>Git</li>
<li>PHP</li>
<li>Composer</li>
<li>Docker and Docker Compose</li>
<li>Symfony CLI<li>
</ol>

<b>Symfony CLI<b>

    $ symfony server:ca:install

    $ symfony book:check-requirements

Almost always prefix a command in terminal with `symfony` like in `symfony composer` instead of just `composer`, or `symfony console` instead of `./bin/console`.

## Step 2: Introducing the Project


### windows setup symfony

install git (needed for symfony)
install xampp
install composer binary from getcomposer.org 
install symfony binary from symfony.org - install using defaults

### (1) check if computer meets all requirements

    $ symfony check:requirements

### (2) run this for a traditional web application

    $ symfony new my_project_name --full

### (3) run this for a traditional web application - using composer

    $ composer create-project symfony/website-skeleton my_project_name

### (4) run this for a building a microservice, console application or API

    $ symfony new my_project_name

### (5) run this for a building a microservice, console application or API - using composer

    $ composer create-project symfony/skeleton my_project_name

### show info about a project

    $ cd prj1
    $ php bin/console about

### clear cache

    $ php bin/console cache:clear

### php ini info

    $ php --ini

### annotations for routing

$ composer require annotations

$ php bin/console cache:clear
$ php bin/console cache:warmup
$ php bin/console router


$ php bin/console debug:route

### web debug toolbar for symfony

$ composer require symfony/profiler-pack

$ composer require twig


