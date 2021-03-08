# Register of illegal dumping sites of Slovenia

Register of illegal dumping sites of Slovenia is an environmental project which is intended to fight against illegal
waste dumps in Slovenia. It's providing users with a modern, effective and accessible system of reporting new illegal
dumping sites and updating previously recorded ones.

## Table of contents

* [Built with](#built-with)
* [How to contribute](#installation-guide)

## Features

## Built with

* [Tailwind CSS](https://tailwindcss.com) - A utility-first CSS framework packed with classes that can be composed to
  build any design, directly in your markup.
* [Vue 3](https://v3.vuejs.org) - Vue is a progressive framework for building user interfaces.
* [Inertia.js](https://inertiajs.com) - Inertia.js lets you quickly build modern single-page React, Vue and Svelte apps
  using classic server-side routing and controllers.
* [Laravel](https://laravel.com) - Laravel is a web application framework with expressive, elegant syntax.

## Installation guide

```sh
# clone the project
git clone https://github.com/jurerotar/Ocistimo-Slovenijo.git  

# change directory to newly created one
cd Ocistimo-Slovenijo  

# install composer dependencies
composer install  

# install node dependencies
npm install  

# migrate the database
php artisan migrate --seed

# after migrating, create static files required by the application
php artisan exports:make

# run development server
php artisan serve  

# compile vue components and watch for changes
npm run dev && npm run watch
```


