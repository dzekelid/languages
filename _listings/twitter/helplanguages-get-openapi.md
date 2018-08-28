---
swagger: "2.0"
x-collection-name: Twitter
x-complete: 0
info:
  title: Twitter Help Langues
  description: Returns the list of languages supported by Twitter along with the language
    code supported by Twitter
  version: "1.1"
host: api.twitter.com
basePath: /1.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /help/languages:
    get:
      summary: Help Langues
      description: Returns the list of languages supported by Twitter along with the
        language code supported by Twitter
      operationId: returns-the-list-of-languages-supported-by-twitter-along-with-the-language-code-supported-by-twitter
      x-api-path-slug: helplanguages-get
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