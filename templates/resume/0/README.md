# healthcheck
[![Build Status](https://travis-ci.org/maxwo/healthcheck.svg?branch=master)](https://travis-ci.org/maxwo/healthcheck)

A dummy project implementing a health check for testing purposes.

## Get healthcheck state
curl http://127.0.0.1:8080/healthcheck

## Set healthcheck state
curl -X PUT -H 'Content-type: application/json' -d 'true' http://127.0.0.1:8080/healthcheck
