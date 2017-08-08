# Laravel on Heroku

## Overview

This project is currently **under development**.

This is a simple example to understand the basics of **Laravel** powered by **Heroku**.

## Dependencies

### Runtime dependencies

The following libraries are used in the application.

*[Laravel](https://laravel.com/)*: The PHP Framework For Web Artisans.

*[Heroku](https://www.heroku.com/)*: Heroku is a cloud platform that lets you build, deliver, monitor and scale apps.

### Dev dependencies

The following libraries are used for the development of this project.

*[composer](https://getcomposer.org/)*: Dependency Manager for PHP.

*[npm](https://www.npmjs.com/)*: Package manager.

## How to...

### Configure

`TODO`

### Build and deploy app to Heroku

[Heroku CLI tool](https://devcenter.heroku.com/articles/heroku-cli) can help you build and deploy the app.

First you need to login with your Heroku credentials.

```
heroku login
```

Then you can create project in Heroku.

```
heroku create
```

This command will create a project in Heroku with some random name and create a remote git repository to which you can push the code thus deploying the app.

Push to Heroku remote repository.

```
git push heroku master
```

The contents of the `public` directory will be deployed to an [NGINX](https://www.nginx.com/) server with the help of the `Procfile`.

### Heroku Add-ons

`TODO`
