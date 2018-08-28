swagger: "2.0"
x-collection-name: Swagger
x-complete: 1
info:
  title: Swagger Generator
  description: this-is-an-online-swagger-codegen-server---you-can-find-out-more-at-httpsgithub-comswaggerapiswaggercodegen-or-on-irc-freenode-net-swaggerhttpswagger-ioirc-
  termsOfService: http://swagger.io/terms/
  contact:
    name: apiteam@swagger.io
  version: 2.2.3
host: generator.swagger.io
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /gen/clients/{language}:
    get:
      summary: Returns options for a client library
      description: Returns options for a client library.
      operationId: getClientOptions
      x-api-path-slug: genclientslanguage-get
      parameters:
      - in: path
        name: language
        description: The target language for the client library
      responses:
        200:
          description: OK
      tags:
      - Generate
      - Clients
      - Language
    post:
      summary: Generates a client library
      description: Accepts a `GeneratorInput` options map for spec location and generation
        options
      operationId: generateClient
      x-api-path-slug: genclientslanguage-post
      parameters:
      - in: body
        name: body
        description: Configuration for building the client library
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: language
        description: The target language for the client library
      responses:
        200:
          description: OK
      tags:
      - Generate
      - Clients
      - Language