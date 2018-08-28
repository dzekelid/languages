---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get locale
  description: Returns the locale of the currently logged in user. If the user has
    no language preference explicitly set (the default setting), or is anonymous,
    this will be the browser locale detected by Jira. If browser detection is in effect,
    the "Accept-Language" browser header is used and falls back to the Jira site default
    locale if no match is found.
  termsOfService: http://atlassian.com/terms/
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