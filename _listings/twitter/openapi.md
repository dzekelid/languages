swagger: "2.0"
x-collection-name: Twitter
x-complete: 1
info:
  title: Twitter
  description: the-twitter-api-gives-you-programmatic-control-over-any-twitter-account-and-most-aspect-of-the-platform--allowing-developers-to-build-social-applications-that-use-the-platform-and-automate-interactions-between-users-
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