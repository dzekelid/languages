---
swagger: "2.0"
x-collection-name: MotaWord
x-complete: 0
info:
  title: Mota Word Download the latest translation package.
  description: Download only the translation package of this language. You must have
    given a /package call beforehand and wait until the packaging status is 'completed'.
  version: alpha-0.1.0
host: api.motaword.com
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
      summary: Get a list of supported languages
      description: Get a list of supported languages.
      operationId: getLanguages
      x-api-path-slug: languages-get
      responses:
        200:
          description: OK
      tags:
      - Languages
  /projects/{id}/download/{language}:
    post:
      summary: Download the latest translation package.
      description: Download only the translation package of this language. You must
        have given a /package call beforehand and wait until the packaging status
        is 'completed'.
      operationId: downloadLanguage
      x-api-path-slug: projectsiddownloadlanguage-post
      parameters:
      - in: path
        name: id
        description: Project ID
      - in: path
        name: language
        description: Language code
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Download
      - Language
  /projects/{id}/package/{language}:
    post:
      summary: Package the translation of a specific target language to be downloaded.
      description: Package the translation of a specific target language to be downloaded..
      operationId: packageLanguage
      x-api-path-slug: projectsidpackagelanguage-post
      parameters:
      - in: query
        name: async
        description: If you want to package and download the translation synchronously,
          mark this parameter as 0
      - in: path
        name: id
        description: Project ID
      - in: path
        name: language
        description: Language code
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Package
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