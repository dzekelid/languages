swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 1
info:
  title: Entertainment Express
  description: your-gateway-to-building-incredible-movie-tv-and-game-content-discovery-experiences-
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Common/Languages/:
    get:
      summary: Gets all languages.
      description: Returns a list of languages used in the API as well as the ISO
        code and language ID.
      operationId: GetLanguages
      x-api-path-slug: commonlanguages-get
      responses:
        200:
          description: OK
      tags:
      - Common
      - Languages