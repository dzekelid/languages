swagger: "2.0"
x-collection-name: HHS Media Services
x-complete: 1
info:
  title: HHS Media Services
  description: div-classswaggeruiwrap-extrafooterh3common-features--behaviorsh3----div-classfeatures--------ul------------listrong-sort-paramstrong-supports-multi-column-sorting-through-the-use-of-commas-as-delimiters-and-a-hyphen-to-denote-descending-order-----------------br----------------strongspanexamplesspanstrong----------------ul--------------------lispan-classexamplenamespanspan-classdescriptionsort-results-by-name-ascendingspanli--------------------lispan-classexamplenamespanspan-classdescriptionsort-results-by-name-descendingspanli--------------------lispan-classexamplenameidspanspan-classdescriptionsort-results-by-name-descending-and-then-by-id-ascendingspanli--------------------lispan-classexampleiddatecontentauthoredspanspan-classdescriptionsort-results-by-id-ascending-and-then-date-descendingspanli----------------ul------------li------------listrongdate-formatsstrong-date-input-format-is-expected-to-be-based-on-a-hrefhttpwww-ietf-orgrfcrfc3339-txtrfc-3339a--br----------------spanstrongexamplestrongspan----------------ulli20131118t184301zliul------------li--------ul----divdiv
  termsOfService: http://www.hhs.gov/web/socialmedia/policies/tos.html#ready
  version: "2"
host: api.digitalmedia.hhs.gov
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /resources/languages.json:
    get:
      summary: Get Languages
      description: Returns the list Languages.
      operationId: getLanguages
      x-api-path-slug: resourceslanguages-json-get
      parameters:
      - in: query
        name: max
        description: The maximum number of records to return
      - in: query
        name: offset
        description: The offset of the records set to return for pagination
      - in: query
        name: sort
        description: '* Set of fields to sort the records by'
      responses:
        200:
          description: OK
      tags:
      - Resources
      - Languages
  /resources/languages/{id}.json:
    get:
      summary: Get Language by ID
      description: Returns the Language identified by the 'id'.
      operationId: getLanguageById
      x-api-path-slug: resourceslanguagesid-json-get
      parameters:
      - in: path
        name: id
        description: The id of the language to look up
      responses:
        200:
          description: OK
      tags:
      - Resources
      - Languages
      - Id