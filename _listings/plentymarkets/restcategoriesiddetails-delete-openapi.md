---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Delete category details for the specified languages
  description: Delete category details for the specified languages.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/categories/{id}/details:
    delete:
      summary: Delete category details for the specified languages
      description: Delete category details for the specified languages.
      operationId: deleteRestCategoriesDetails
      x-api-path-slug: restcategoriesiddetails-delete
      parameters:
      - in: body
        name: /rest/categories/{id}/details
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Category
      - Detailsthe
      - Specified
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