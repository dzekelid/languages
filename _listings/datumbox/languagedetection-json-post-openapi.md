---
swagger: "2.0"
x-collection-name: Datumbox
x-complete: 0
info:
  title: Datumbox Identifies the Language of the Document
  description: The Language Detection function identifies the natural language of
    the given document based on its words and context. This classifier is able to
    detect 96 different languages.
  version: 1.0.0
host: api.datumbox.com
basePath: 1.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /LanguageDetection.json:
    post:
      summary: Identifies the Language of the Document
      description: The Language Detection function identifies the natural language
        of the given document based on its words and context. This classifier is able
        to detect 96 different languages.
      operationId: LanguageDetection
      x-api-path-slug: languagedetection-json-post
      parameters:
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Language
      - Detection
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