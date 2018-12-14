simple wp-mysql
====

Overview
Create a development environment for wordpress with mysql container.

## Description
This create 2 containers. One is a wordpress container and the other is a container for mysql. You can access both from browsers or terminal through localhost and operate them.
_
## Demo

## VS.

## Requirement
Install docker & docker-compose.

## Usage
use command in the ./docker/ directry

Starting
$docker-compose up / $docker-compose up -d
 The first time, it may take a few minutes to build the environment.

Closing
ctrl c / $docker-compose down

Access to your wp
Default:"http://localhost:8001/"
You need exchange the port number when that port number has been arleady used or you want create other development environments.

Access to mysql
Default:"http://localhost:13306/"
You need exchange the port number when that port number has been arleady used or you want create other development environments.

You can change ports number from docker-compose.yml.

## Install

## Contribution

## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author
Shotaroh Horiguchi

[tcnksm](https://github.com/tcnksm)
