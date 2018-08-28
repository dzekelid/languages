---
swagger: "2.0"
x-collection-name: Code.gov
x-complete: 0
info:
  title: Code.gov Get a list of programming languages found in our code inventory.
  description: This returns a list of the programming languages that are used in the
    indexed code inventory. When a repo is index the programming language is extracted
    written to a file.
  version: 1.0.0
host: api.code.gov
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
      summary: Get a list of programming languages found in our code inventory.
      description: This returns a list of the programming languages that are used
        in the indexed code inventory. When a repo is index the programming language
        is extracted written to a file.
      operationId: getLanguages
      x-api-path-slug: languages-get
      parameters:
      - in: query
        name: from
        description: Specify an offset to return
      - in: query
        name: size
        description: Number of programming languages to return
      responses:
        200:
          description: OK
      tags:
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