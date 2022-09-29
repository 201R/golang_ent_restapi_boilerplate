# golang_restapi_boilerplate

## Description

Golang REST API boilerplate for typical project, including interactive API documentation.

## Table of Contents

-   [Interactive API documentation](#interactive-api-documentation)
-   [Features](#features)
-   [Quick run](#quick-run)
-   [How to use it](#how-to-use-it)
-   [Comfortable development](#comfortable-development)
-   [Links](#links)
-   [Database](#database)
-   [Tests](#tests)
-   [License](#license)

## Interactive API documentation

[![API docs](img/swagger.png)](https://github.com/201R/golang_restapi_boilerplate)

## Features

-   [x] Database ([entgo](https://github.com/ent/ent)).
-   [x] Migration ([atlas](https://github.com/ariga/atlas)).
-   [x] Config
-   [ ] Admin and User roles. ([Casbin Rbac](https://github.com/casbin/casbin))
-   [x] Mailing
-   [ ] Sign in and sign up via email.
-   [ ] Redis
-   [ ] Social sign in (Apple, Facebook, Google, Twitter).
-   [ ] I18N
-   [ ] File uploads. Support local and Amazon S3 drivers.
-   [x] Swagger.
-   [ ] nginx.
-   [x] Adminer([Adminer](https://www.adminer.org/))
-   [ ] Docker.
-   [ ] CI (Github Actions).
-   [ ] Monitoring ([Grafana](https://grafana.com/docs/loki/latest/api/))
-   [ ] Unit Test([Testify](https://github.com/stretchr/testify))

## Quick run

```bash
git clone --depth 1 https://github.com/201R/golang_restapi_boilerplate.git my-app
cd my-app/
cp .ini.exemple .ini
docker-compose up -d
```

For check status run

```bash
docker-compose logs
```

## How to use it

## Comfortable development

## Links

-   Swagger: http://localhost:8090/swagger/index.html
-   Adminer: http://localhost:8080/

## Database

## License

This project is licensed under the terms of the MIT license.
