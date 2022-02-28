# spicy-djalapeno

[![spicy-djalapeno](https://github.com/galactic-filament/spicy-djalapeno/actions/workflows/python-app.yml/badge.svg)](https://github.com/galactic-filament/spicy-djalapeno/actions/workflows/python-app.yml)
[![Coverage Status](https://coveralls.io/repos/github/galactic-filament/spicy-djalapeno/badge.svg?branch=master)](https://coveralls.io/github/galactic-filament/spicy-djalapeno?branch=master)

## Libraries

| Kind                  | Name                                                                  |
|-----------------------|-----------------------------------------------------------------------|
| Web Framework         | [Django](https://www.djangoproject.com/)                              |
| SQL ORM               | [Django Models](https://docs.djangoproject.com/en/4.0/ref/models/)    |
| Logging               | [Django Logging](https://docs.djangoproject.com/en/4.0/ref/logging/)  |
| Test Framework        | [Django Tests](https://docs.djangoproject.com/en/4.0/topics/testing/) |
| Test Coverage         | [coverage](https://coverage.readthedocs.io/en/6.3.1/)                 |
| Version Management    | [poetry](https://python-poetry.org/)                                  |
| Dependency Management | [poetry](https://python-poetry.org/)                                  |

## Features Implemented

- [ ] Hello world routes
- [ ] CRUD routes for persisting posts
- [ ] Database access
- [ ] Database migrations
- [ ] Request logging to /srv/app/log/app.log
- [ ] Proper unit tests
- [ ] Unit test coverage reporting
- [ ] Automated testing using GitHub Actions
- [ ] Automated coverage reporting using Coveralls
- [ ] CRUD routes for user management
- [ ] Database model relationships
- [ ] Password encryption using bcrypt
- [ ] Routes protected via Bearer token authentication
- [ ] Routes protected via ACLs
- [ ] [~~Forms protected by CSRF~~](https://flask-wtf.readthedocs.io/en/1.0.x/) (Not necessary due to using JWT)
- [ ] Form validation
- [ ] Postman collection committed
- [ ] Postman in CI/CD steps
- [ ] Optimized Docker image
- [ ] Validates environment (env vars, database host and port are accessible)
