swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/mypreferences/locale:
    get:
      summary: Get locale
      description: Returns the locale of the currently logged in user. If the user
        has no language preference explicitly set (the default setting), or is anonymous,
        this will be the browser locale detected by Jira. If browser detection is
        in effect, the "Accept-Language" browser header is used and falls back to
        the Jira site default locale if no match is found.
      operationId: com.atlassian.jira.rest.v2.preference.CurrentUserPreferencesResource.getLocale_get
      x-api-path-slug: api2mypreferenceslocale-get
      responses:
        200:
          description: OK
      tags:
      - Locale