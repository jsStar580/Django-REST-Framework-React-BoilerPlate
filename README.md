<h1 align="left">DRF React & Redux Boilerplate</h1>

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/jsStar580/Django-React-Redux-Boilerplate/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/jsStar580/Django-React-Redux-Boilerplate/tree/main)
[![Maintainability](https://api.codeclimate.com/v1/badges/1dc1d840640dad52e38f/maintainability)](https://codeclimate.com/github/jsStar580/Django-REST-Framework-React-BoilerPlate/maintainability)

## Frontend ⭐

- Minimal Template with neccessary components✔
- Configured Redux Store✔
- Auto formatted with Prettier ✔
- React with functional components and hooks ✔
- Forms Validation with Formik ✔
- Login , example to understand the JWT auth ✔
- Server Errors Handling✔

## Backend🛠

- Django REST framework for a powerful API ✔
- Django ORM for interacting with the database✔
- Authentication With JWT (Register, Sign In) ✔
- Throttle setup ✔
- Testing with Pytest ✔
- Extra password hashers like `Argon2PasswordHasher` Recommend by official django docs. ✔

## Motivation 🎯

- A quickstart django react boilerplate with updated dependecies to start with react project.
- Material UI usage⭐

## How to Run locally 🚀

### Backend

- Install requirements after creating and activating virtual environement

  $ pip install -r requirements/local.txt

- Currently SQLite is configured, you can change it with any other as well. Then run

  $ python manage.py makemigrations
  $ python3 manage.py migrate

  To run tests:
  $ pytest

  API Documentation will be available at http://localhost:8000/api/v1/schema/redoc/

  Admin available at`http://localhost:8000/admin/`

### Frontend

    - Install dependencies in frontend app using following commands in separate terminal
    - First make sure you have installed Node.js, v18.12.1. while upgrading this setup.

    For More info https://nodejs.org/en/

    - Then run following commands in frontend dir

    $ yarn install
    $ yarn start

    -  React app available at`http://localhost:3000/`

👉 [Github Pages](https://jsStar580.github.io/Django-REST-Framework-React-BoilerPlate/)

## ⭐️ Support

Give a ⭐️ if this project helped you!

## License ©

[The MIT License](LICENSE)
