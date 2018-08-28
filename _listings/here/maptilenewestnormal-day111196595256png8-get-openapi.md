---
swagger: "2.0"
x-collection-name: HERE
x-complete: 0
info:
  title: HERE Map Tile API Foreign Language Support
  description: |-
    *Request a map tile with labels in a foreign language*

    The `lg` query parameter is used to define the language used on the map tiles. Consult the  Map Tile API Reference for a full list of available languages.



    * **lg**  `enum`
     \- Alters the language of the labels displayed on the map. Three letter MARC code, for example `rus` for Russian language.

     Valid values are : `ara` - Arabic, `chi` - Chinese, `cht` - Chinese (Trad), `dut` - Dutch, `eng` - English, `fre` - French, `ger` - German, `gle` - Gaelic, `gre` - Greek, `heb` - Hebrew, `hin` - Hindi, `ind` - Indonesian, `ita` - Italian, `per` - Persian, `pol` - Polish, `por` - Portuguese, `rus` - Russian, `sin` - Sinhalese, `spa` - Spanish, `tha` - Thai, `tur` - Turkish, `ukr` - Ukranian, `urd` - Urdu, `vie` - Vietnamese, `wel` - Welsh

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  version: 1.0.0
host: 1.aerial.maps.cit.api.here.com
basePath: /maptile/2.1/maptile/newest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /maptile/newest/normal.day/13/6693/3575/256/png8:
    get:
      summary: Support for Multiple Languages
      description: |-
        *Request a map tile with labels in two languages*

        The `lg` query parameter is used to define the first language used on the map tiles. The `lg2` query parameter is used to define a supplementary second language. Consult the  Map Tile API Reference for a full list of available languages.



        * **lg**  `enum`
         \- Alters the language of the labels displayed on the map. Three letter MARC code, for example `rus` for Russian language.

         Valid values are : `ara` - Arabic, `chi` - Chinese, `cht` - Chinese (Trad), `dut` - Dutch, `eng` - English, `fre` - French, `ger` - German, `gle` - Gaelic, `gre` - Greek, `heb` - Hebrew, `hin` - Hindi, `ind` - Indonesian, `ita` - Italian, `per` - Persian, `pol` - Polish, `por` - Portuguese, `rus` - Russian, `sin` - Sinhalese, `spa` - Spanish, `tha` - Thai, `tur` - Turkish, `ukr` - Ukranian, `urd` - Urdu, `vie` - Vietnamese, `wel` - Welsh

        * **lg2**  `enum`
         \- Alters the second language of the labels displayed on the map. Three letter MARC code, for example `rus` for Russian language.

         Valid values are : `ara` - Arabic, `chi` - Chinese, `cht` - Chinese (Trad), `dut` - Dutch, `eng` - English, `fre` - French, `ger` - German, `gle` - Gaelic, `gre` - Greek, `heb` - Hebrew, `hin` - Hindi, `ind` - Indonesian, `ita` - Italian, `per` - Persian, `pol` - Polish, `por` - Portuguese, `rus` - Russian, `sin` - Sinhalese, `spa` - Spanish, `tha` - Thai, `tur` - Turkish, `ukr` - Ukranian, `urd` - Urdu, `vie` - Vietnamese, `wel` - Welsh

        * **app_id**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

        * **app_code**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
      operationId: MaptileNewestNormalDay1366933575256Png8Get
      x-api-path-slug: maptilenewestnormal-day1366933575256png8-get
      parameters:
      - in: query
        name: app_code
      - in: query
        name: app_id
      - in: query
        name: lg
      - in: query
        name: lg2
      responses:
        200:
          description: OK
      tags:
      - SupportMultiple
      - Languages
  /maptile/newest/normal.day/11/1196/595/256/png8:
    get:
      summary: Foreign Language Support
      description: |-
        *Request a map tile with labels in a foreign language*

        The `lg` query parameter is used to define the language used on the map tiles. Consult the  Map Tile API Reference for a full list of available languages.



        * **lg**  `enum`
         \- Alters the language of the labels displayed on the map. Three letter MARC code, for example `rus` for Russian language.

         Valid values are : `ara` - Arabic, `chi` - Chinese, `cht` - Chinese (Trad), `dut` - Dutch, `eng` - English, `fre` - French, `ger` - German, `gle` - Gaelic, `gre` - Greek, `heb` - Hebrew, `hin` - Hindi, `ind` - Indonesian, `ita` - Italian, `per` - Persian, `pol` - Polish, `por` - Portuguese, `rus` - Russian, `sin` - Sinhalese, `spa` - Spanish, `tha` - Thai, `tur` - Turkish, `ukr` - Ukranian, `urd` - Urdu, `vie` - Vietnamese, `wel` - Welsh

        * **app_id**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

        * **app_code**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
      operationId: MaptileNewestNormalDay111196595256Png8Get
      x-api-path-slug: maptilenewestnormal-day111196595256png8-get
      parameters:
      - in: query
        name: app_code
      - in: query
        name: app_id
      - in: query
        name: lg
      responses:
        200:
          description: OK
      tags:
      - Foreign
      - Language
      - Support
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