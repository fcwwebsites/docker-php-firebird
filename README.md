# PHP with Firebird module Dockerfile

[![Docker Pulls](https://img.shields.io/docker/pulls/fcwwebsites/php-firebird-mysql.svg)](https://hub.docker.com/r/fcwwebsites/php-firebird-mysql/)
[![Docker Stars](https://img.shields.io/docker/stars/fcwwebsites/php-firebird-mysql.svg)](https://hub.docker.com/r/fcwwebsites/php-firebird-mysql/)

## Description

 Minimal PHP with Firebird module + nginx

### Volumes

 * /usr/share/nginx/html

### Exposed Ports

 * 80

## Run

	$ docker run -d \
		--name php-firebird \	
		-p 80:80 \
		-v /somehostdir/php/:/usr/share/nginx/html/ \
		almeida/php-firebird
