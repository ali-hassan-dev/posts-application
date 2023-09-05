# Posts Application

Explore the Posts Application, a social platform that connects users through posts and profiles.

## Table of Contents

1. [Running Locally](#running-locally)
1. [Tech Stack](#tech-stack)
1. [Routes](#routes)
1. [Features](#features)

## Running Locally

1. Clone this repo
1. `cd jobs-app`
1. `composer install`
1. `npm install`
1. `cp .env.example .env`
1. Add your local database credentials in the .env file
1. `php artisan migrate`
1. `php artisan storage:link`
1. `php artisan serve`

## Tech Stack

1. Laravel
1. Tailwind
1. MySQL

## Routes

* / --> home page
* /posts --> shows all posts of all users and a form to add a post
* /user/:username/posts --> shows all posts and likes received by a user
* posts/:id --> shows single post

## Features

1. View posts.
1. Like and unlike posts.
1. View the profiles.
1. Create and delete posts.
