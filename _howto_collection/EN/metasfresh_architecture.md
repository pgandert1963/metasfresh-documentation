---
title: metasfresh Architecture
layout: default
tags:
  - System Administration
lang: en
---
## Overview

![architecture](../../images/metasfresh_architecture.png)

## Service Details

| Service     | Dev Language     | Running on | Technologies | Repo
| :------------- | :------------- | :------------- | :------------- |  :------------- |
| WebUI        | Javascript        | Apache / Nginx | React Redux, HTML5, PostCSS | [Github](https://github.com/metasfresh/metasfresh-webui-frontend)
| WebAPI        | Java 8      | Spring Boot |REST, JSON, Swagger, Spring, hazelcast, websocket| [Github](https://github.com/metasfresh/metasfresh-webui)
| App         | Java 8, SQL       | Spring Boot | Jasper Reports, Application Dictionary| [Github](https://github.com/metasfresh/metasfresh)
| DB         | SQL, PgSQL       | Postgres (9.5+) | Application Dictionary | [Github](https://github.com/metasfresh/metasfresh)
| Reporting | JRXML | Jasperserver  | Jasper Reports 6.5.1 [Client](https://community.jaspersoft.com/project/jaspersoft-studio/releases#project_releases-old-1)| [Github](https://github.com/metasfresh/metasfresh/tree/master/de.metas.fresh/de.metas.fresh.base/src/main/jasperreports/de/metas)
| elastic Search | |  | Standard Elastic Search | [Github](https://github.com/elastic/elasticsearch)
| RabbitMQ | | |Standard  RabbitMQ | [Github](https://github.com/rabbitmq)
| Java Client| Java 8 | Java JRE 8+ | Swing | [Github](https://github.com/metasfresh/metasfresh)
||
| Optional: |
| Material Dispo         | Java 8       | Spring Boot | realtime calculation of material | [Github](https://github.com/metasfresh/metasfresh)
| Jasper Reports         | Java 8       | Spring Boot | render jasper reports | [Github](https://github.com/metasfresh/metasfresh)
