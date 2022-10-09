# java-cli-maven-cockroachdb-single-node-without-ssl-data-type-hstore

## Description
Creates a small table `dog` that uses
a key value pair data type.

A java maven build, that connects to single node
cockroach database without ssl.

## Tech stack
- java
- maven
  - postgres drivers

## Docker stack
- cockroachdb/cockroach:v19.2.2
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- [webui](http://localhost:8080)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
