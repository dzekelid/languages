swagger: "2.0"
x-collection-name: Bookeo
x-complete: 1
info:
  title: Bookeo
  version: 1.0.0
host: api.bookeo.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /settings/languages:
    get:
      summary: Retrieve all supported languages
      description: Retrieve all supported languages.
      operationId: getSettingsLanguages
      x-api-path-slug: settingslanguages-get
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Languages