# Gogs API Draft

Per some discussion and [a ticket on the go-git-client repo](https://github.com/gogits/go-gogs-client/issues/19), I'm working through the structure of the contract for the Gogs API with [Swagger 2.0](https://swagger.io/specification).

## Some things to know... for now.

This is an enormous work in progress. The best way to check it out (for the time being) is to see it rendered by copying the [spec.yaml](https://raw.githubusercontent.com/patrickmcclory/gogs-api-draft/master/spec.yaml) file into an instance of [swagger-editor](http://editor.swagger.io).  

TODO:

* Get methods stubbed out based on current API structure.
* Build out current parameter, input and filter sets w/ endpoints.
* Build TODO list to evaluate which endpoints need to added to get to basic integration capability level (use screwdriver.cd as base)
* Work with community to determine how we'll break apart API implementation from core and go-gogs-client.
* build plan
* execute
* go grab a drink.
