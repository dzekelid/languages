---
swagger: "2.0"
x-collection-name: The TVDB
x-complete: 0
info:
  title: The TVDB Get Languages
  description: All available languages. These language abbreviations can be used in
    the `Accept-Language` header for routes that return translation records.
  version: 2.1.2
host: api-dev.thetvdb.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /languages:
    get:
      summary: Get Languages
      description: All available languages. These language abbreviations can be used
        in the `Accept-Language` header for routes that return translation records.
      operationId: languages.get
      x-api-path-slug: languages-get
      responses:
        200:
          description: OK
      tags:
      - Television
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