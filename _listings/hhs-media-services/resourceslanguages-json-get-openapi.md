---
swagger: "2.0"
x-collection-name: HHS Media Services
x-complete: 0
info:
  title: HHS Media Services Get Languages
  description: Returns the list Languages.
  termsOfService: http://www.hhs.gov/web/socialmedia/policies/tos.html#ready
  version: "2"
host: api.digitalmedia.hhs.gov
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /resources/languages.json:
    get:
      summary: Get Languages
      description: Returns the list Languages.
      operationId: getLanguages
      x-api-path-slug: resourceslanguages-json-get
      parameters:
      - in: query
        name: max
        description: The maximum number of records to return
      - in: query
        name: offset
        description: The offset of the records set to return for pagination
      - in: query
        name: sort
        description: '* Set of fields to sort the records by'
      responses:
        200:
          description: OK
      tags:
      - Resources
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