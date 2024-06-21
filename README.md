![opstodo](https://raw.githubusercontent.com/tododev/opstodo/ceda603/docs/banner.png)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

# opstodo

## find_or_rescue

 when run locally:

 http://localhost:8080/swagger-ui.html#/main

 http://localhost:8080/swagger-ui.html#/pipeline-api

 or on stage server installation:

 https://your-app.up.railway.app/swagger-ui.html

## wordpeak

 install Railway CLI first, as described step-by-step in the Railway "Getting started" manuals!

 Having a Railway account do:

`railway login`

 `railway init` creates the app with a new project name (see the rename section).

## KUI
 set up MySQL db on Railway following the steps in this tutorial:

 https://docs.railway.app/databases/mysql

 You will need the DB TABLE SCHEMA - check `./_Project/schema.sql`

 `railway connect mysql`

 `railway service rename {old_name} {new_name}`

## 202203dp

  Change to better project name:

 `railway project rename newname`

## ir-llvm

 https://railway.app/project/{your-project-id}/service/{service-id}

## getperl
 `railway login`

 `railway connect mysql`

## signal-promise
 `railway login`

 `railway logs --tail 500`

## LinearAlgebraX-jl
 edit .env only uses to run MySQL locally:

 1. `SPRING_DATASOURCE_URL=jdbc:mysql://localhost:3306/opstodo_db`

 2. `SPRING_DATASOURCE_USERNAME={local mysql username}`

 3. `SPRING_DATASOURCE_PASSWORD={local mysql password}`

## openboxes

`railway login`

`railway init`

`./gradlew clean build`

## na9da-github-com

 `git add .`

 `git commit -m "first commit"`

 `git push`

 `railway up`

# Cockatrice

`railway run ./gradlew bootRun`

`railway open`

`start chrome https://localhost:8080`

## argo-client-python

 `{server_uri}` local = `http://localhost:8080`

 GET `{server_uri}/api/gramps-to-markdown`

 POST `{server_uri}/api/aoe_cachecleaner`

 JSON Payload: `{"tenant_id": "2222","label": "mario-bukkit-mod","enabled": false}`

# libRETS

# opstodo-starter

A barebones Spring Boot app, which can easily be deployed to Railway.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new)

## edoc-patched

Make sure you have Java and Gradle installed. Also, install the [Railway CLI](https://docs.railway.app/develop/cli).

```sh
$ git clone https://github.com/tododev/opstodo.git
$ cd opstodo
$ ./gradlew build
$ railway run ./gradlew bootRun
```

Your app should now be running on [localhost:8080](http://localhost:8080/).

```
SPRING_DATASOURCE_URL=jdbc:mysql://localhost:3306/opstodo_db
```

## johnie-se-old

```sh
$ railway init
$ railway up
$ railway open
```

## math-go-way

For more information about using Java on Railway, see these articles:

- [Java on Railway](https://docs.railway.app/languages/java)
