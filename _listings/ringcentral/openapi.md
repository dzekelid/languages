swagger: "2.0"
x-collection-name: RingCentral
x-complete: 1
info:
  title: RingCentral Connect Platform API Explorer
  description: this-is-an-interactive-api-explorer-for-the-ringcentral-connect-platform--to-use-this-service-you-will-need-to-have-a-developer-account---links--a-hrefhttpsnetstorage-ringcentral-comdpwapiexplorerrcplatform-basic-ymlv20180514092722-target-blankringcentral-api-specaspannbspnbspopenapi-fka-swagger-formatnbspnbspnbspnbspspana-hrefhttpsgithub-comoaiopenapispecification-target-blanklearn-more-about-openapia
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