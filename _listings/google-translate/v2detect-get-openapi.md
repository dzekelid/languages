---
swagger: "2.0"
x-collection-name: Google Translate
x-complete: 0
info:
  title: Google Translate API Detect Language
  description: Detect the language of text.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /language/translate
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/detect:
    get:
      summary: Detect Language
      description: Detect the language of text.
      operationId: language.detections.list
      x-api-path-slug: v2detect-get
      parameters:
      - in: query
        name: q
        description: The text to detect
      responses:
        200:
          description: OK
      tags:
      - Language
  /v2/languages:
    get:
      summary: Get Languages
      description: List the source/target languages supported by the API
      operationId: language.languages.list
      x-api-path-slug: v2languages-get
      parameters:
      - in: query
        name: target
        description: the language and collation in which the localized results should
          be returned
      responses:
        200:
          description: OK
      tags:
      - Language
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