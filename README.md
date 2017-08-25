# DCGoss Test Image
[![Build Status](https://travis-ci.org/joeblackwaslike/docker-dcgoss.svg?branch=master)](https://travis-ci.org/joeblackwaslike/docker-dcgoss) [![Docker Pulls](https://img.shields.io/docker/pulls/joeblackwaslike/dcgoss.svg)](https://hub.docker.com/r/joeblackwaslike/dcgoss/) [![Github Repo](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/joeblackwaslike/docker-dcgoss)


## Maintainer
Joe Black | <me@joeblack.nyc> | [github](https://github.com/joeblackwaslike)


## Introduction
This container contains [goss](https://github.com/aelsabbahy/goss) and [dgoss](https://github.com/aelsabbahy/goss/tree/master/extras/dgoss) for testing docker containers


## Using this image
*See [examples](examples)*

1. Copy the `tests` directory to the base of your repository.
2. Follow directions for dcgoss, substituting `dcgoss edit` and `dcgoss run` with
   `tests/edit` and `tests/run` respectively.
3. Set your Makefile `test` target to `tests/run <docker-compose-service>`
4. `make test`
