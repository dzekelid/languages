---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Language
  description: "Returns language by ID.\nUsage Plan Group\nLight\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n404\nCMN-102\nResource
    for parameter [languageId] is not found"
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/dictionary/language:
    get:
      summary: Get Language List
      description: "Returns the information about supported languages.\nUsage Plan
        Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nCMN-101\nParameter [perPage] value is invalid"
      operationId: listLanguages
      x-api-path-slug: restapiv1-0dictionarylanguage-get
      responses:
        200:
          description: OK
      tags:
      - Language
      - List
  /restapi/v1.0/dictionary/language/{languageId}:
    get:
      summary: Get Language
      description: "Returns language by ID.\nUsage Plan Group\nLight\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n404\nCMN-102\nResource
        for parameter [languageId] is not found"
      operationId: loadLanguage
      x-api-path-slug: restapiv1-0dictionarylanguagelanguageid-get
      parameters:
      - in: path
        name: languageId
        description: Internal identifier of a language
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