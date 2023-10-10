# java-cli-millbuild-cockroachdb-single-node-without-ssl-data-type-uuid

## Description
Creates a small table `dog` that uses
a uuid data type.

A java gradle build, that connects to single node
cockroach database without ssl.

## Tech stack
- java
- millbuild
  - postgres drivers

## Docker stack
- cockroachdb/cockroach:v19.2.2
- nightscape/scala-mill

## To run
`sudo ./install.sh -u`
- [webui](http://localhost:8080)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
