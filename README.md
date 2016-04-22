# Book Review Site In Drupal - April 22, 2016

## Description

This Drupal application allows for authenticated users known as "reviewers" to create their own book review, edit it and delete it. Anonymous users have the ability to view all contents of the site except a coupon code.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Composer]

## Installation

* `git clone https://github.com/jwuerch/Druapl-CR-1.git`
* change into the new directory
* `echo export PATH="$HOME/.composer/vendor/bin:$PATH" >> ~/.bash_profile`
* Start up mamp and point servers to main directory
* Go to localhost:8888/phpmyadmin in browser and import `drupal_cr_1.sql.zip` DB found in Drupal-CR-1/sites/DB-Backup
* Create DB username `jwuerch` with password `admin`
* Go to localhost:8888 to view Drupal project.

## Databases Used
* `drupal_cr_1`

## Usernames and Passwords
* DB: `jwuerch:admin`
* Drupal site maintenance account: `jwuerch:admin`
* Reviewer user: `reviewer:admin`

## Running / Development

* `ember server`
* Visit your app at [http://localhost:8888](http://localhost:8888).

### Deploying

All you need to deploy is to visit localhost:8888. The app is currently not hosted.

##License

This software is licensed under the MIT license.
Copyright (c) 2016 _**Jason Wuerch**_.
