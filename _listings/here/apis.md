---
name: HERE
x-slug: here
description: HERE Technologies enables people, enterprises and cities around the world
  to harness the power of location and create innovative solutions that make our lives
  safer and more efficient. We transform information from devices, vehicles, infrastructure
  and...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
x-kinRank: "7"
x-alexaRank: "3011"
tags: Languages
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/apis.md
specificationVersion: "0.14"
apis:
- name: Map Tile API - Support for Multiple Languages
  x-api-slug: maptilenewestnormal-day1366933575256png8-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day1366933575256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day1366933575256png8-get-openapi.md
- name: Map Tile API - Foreign Language Support
  x-api-slug: maptilenewestnormal-day111196595256png8-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day111196595256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day111196595256png8-get-openapi.md
- name: Map Tile API - Foreign Language Support
  x-api-slug: maptilenewestnormal-day111196595256png8-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day111196595256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day111196595256png8-get-openapi.md
- name: Map Tile API - Foreign Language Support
  x-api-slug: maptilenewestnormal-day111196595256png8-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day111196595256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day111196595256png8-get-openapi.md
- name: Map Tile API - Foreign Language Support
  x-api-slug: maptilenewestnormal-day111196595256png8-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day111196595256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day111196595256png8-get-openapi.md
- name: Map Tile API - Foreign Language Support
  x-api-slug: maptilenewestnormal-day111196595256png8-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day111196595256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/here/maptilenewestnormal-day111196595256png8-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://developer.here.com/blog/feed
- type: x-github
  url: https://github.com/heremaps
- type: x-postman-collection
  url: https://github.com/heremaps/postman-collections
- type: x-api-gallery
  url: http://healthcare.gov.api.gallery.streamdata.io
- type: x-api-stack
  url: http://here.stack.network
- type: x-blog
  url: https://developer.here.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/here-inc
- type: x-developer
  url: https://developer.here.com
- type: x-email
  url: dirk.popp@here.com
- type: x-email
  url: sebastian.kurme@here.com
- type: x-email
  url: jordan.stark@here.com
- type: x-email
  url: amy.stupavsky@here.com
- type: x-email
  url: minna.laub@here.com
- type: x-email
  url: stefanie.sirc@here.com
- type: x-email
  url: rachel.kuta@here.com
- type: x-email
  url: laurel.davis-lyons@here.com
- type: x-email
  url: linda.bradley@here.com
- type: x-email
  url: press@here.com
- type: x-twitter
  url: https://twitter.com/here
- type: x-website
  url: https://here.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---