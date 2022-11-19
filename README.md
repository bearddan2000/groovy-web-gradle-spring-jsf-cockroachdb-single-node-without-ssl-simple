# groovy-web-gradle-spring-jsf-cockroachdb-single-node-without-ssl-simple

## Description
A jsf springboot groovy gradle build,
that connects to cockroach database.

A groovy gradle build, that connects to single node
cockroach database without ssl.

## Tech stack
- springboot
  - jsf
- gradle
  - postgres drivers
  - lombok
- bootstrap
- jquery
- dataTable

## Docker stack
- cockroachdb/cockroach:v19.2.2
- gradle:jdk11

## To run
`sudo ./install.sh -u`
- [web app](http://localhost)
- [webui](http://localhost:8080)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
