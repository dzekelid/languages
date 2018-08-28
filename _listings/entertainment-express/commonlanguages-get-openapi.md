---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 0
info:
  title: Entertainment Express Gets all languages.
  description: Returns a list of languages used in the API as well as the ISO code
    and language ID.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---