---
swagger: "2.0"
x-collection-name: Bookeo
x-complete: 0
info:
  title: Bookeo Retrieve all supported languages
  version: 1.0.0
  description: Retrieve all supported languages.
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