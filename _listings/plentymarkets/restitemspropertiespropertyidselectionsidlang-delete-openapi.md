---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Delete a property selection language
  description: Deletes a property selection language. The ID of the selection and
    the language must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/categories/{id}/details:
    delete:
      summary: Delete category details for the specified languages
      description: Delete category details for the specified languages.
      operationId: deleteRestCategoriesDetails
      x-api-path-slug: restcategoriesiddetails-delete
      parameters:
      - in: body
        name: /rest/categories/{id}/details
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Category
      - Detailsthe
      - Specified
      - Languages
  /rest/items/properties/{propertyId}/selections/{id}:
    post:
      summary: Creates a property selection lang
      description: Creates a property selection lang.
      operationId: postRestItemsPropertiesPropertySelections
      x-api-path-slug: restitemspropertiespropertyidselectionsid-post
      parameters:
      - in: body
        name: /rest/items/properties/{propertyId}/selections/{id}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Property
      - Selection
      - Lang
  /rest/payments/methodNames/{paymentMethodId}/{lang}:
    get:
      summary: Gets a payment method name by id and lang
      description: Gets a payment method name by id and lang. The ID and the requested
        lang of the payment method must be specified.
      operationId: getRestPaymentsMethodnamesPaymentmethodLang
      x-api-path-slug: restpaymentsmethodnamespaymentmethodidlang-get
      parameters:
      - in: path
        name: lang
      - in: path
        name: paymentMethodId
      responses:
        200:
          description: OK
      tags:
      - S
      - Payment
      - Method
      - Name
      - By
      - Id
      - Lang
  /rest/items/properties/{propertyId}/selections/{id}/{lang}:
    delete:
      summary: Delete a property selection language
      description: Deletes a property selection language. The ID of the selection
        and the language must be specified.
      operationId: deleteRestItemsPropertiesPropertySelectionsLang
      x-api-path-slug: restitemspropertiespropertyidselectionsidlang-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Selection
      - Language
    get:
      summary: List property selections by language
      description: Lists the property selections of a property for a specific language.
        The ID and language of the property must be specified.
      operationId: getRestItemsPropertiesPropertySelectionsLang
      x-api-path-slug: restitemspropertiespropertyidselectionsidlang-get
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - List
      - Property
      - Selections
      - By
      - Language
  /rest/items/property_groups/{id}/names/{lang}:
    get:
      summary: Get a property group name in a language
      description: Gets a property group name in the specified language. The ID of
        the property group name and the language code must be specified.
      operationId: getRestItemsPropertyGroupsNamesLang
      x-api-path-slug: restitemsproperty-groupsidnameslang-get
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Property
      - Group
      - Name
      - In
      - Language
  /rest/items/{itemId}/variations/{variationId}/variation_properties/{propertyId}/texts:
    post:
      summary: Create property value text by language
      description: Saves text for a specific property of the type Text in the specified
        language. The ID of the property and the language must be specified.
      operationId: postRestItemsItemVariationsVariationVariationPropertiesPropertyTexts
      x-api-path-slug: restitemsitemidvariationsvariationidvariation-propertiespropertyidtexts-post
      parameters:
      - in: body
        name: /rest/items/{itemId}/variations/{variationId}/variation_properties/{propertyId}/texts
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: itemId
      - in: path
        name: propertyId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Value
      - Text
      - By
      - Language
  /rest/items/{itemId}/variations/{variationId}/variation_properties/{propertyId}/texts/{lang}:
    delete:
      summary: Delete property value text by language
      description: Deletes the text saved for a specific property of the type Text
        in the specified language. The ID of the property  and the language must be
        specified.
      operationId: deleteRestItemsItemVariationsVariationVariationPropertiesPropertyTextsLang
      x-api-path-slug: restitemsitemidvariationsvariationidvariation-propertiespropertyidtextslang-delete
      parameters:
      - in: path
        name: itemId
      - in: path
        name: lang
      - in: path
        name: propertyId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Value
      - Text
      - By
      - Language
    get:
      summary: Get property value text by language
      description: Gets the value text saved for a specific property of the type Text
        in the specified language. The ID of the property  and the language must be
        specified.
      operationId: getRestItemsItemVariationsVariationVariationPropertiesPropertyTextsLang
      x-api-path-slug: restitemsitemidvariationsvariationidvariation-propertiespropertyidtextslang-get
      parameters:
      - in: path
        name: itemId
      - in: path
        name: lang
      - in: path
        name: propertyId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Value
      - Text
      - By
      - Language
    put:
      summary: Update property value text by language
      description: Updates the text saved for a specific property of the type Text
        in the specified language. The ID of the property and the language must be
        specified.
      operationId: putRestItemsItemVariationsVariationVariationPropertiesPropertyTextsLang
      x-api-path-slug: restitemsitemidvariationsvariationidvariation-propertiespropertyidtextslang-put
      parameters:
      - in: body
        name: /rest/items/{itemId}/variations/{variationId}/variation_properties/{propertyId}/texts/{lang}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: itemId
      - in: path
        name: lang
      - in: path
        name: propertyId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Value
      - Text
      - By
      - Language
  /rest/properties/systemlang:
    get:
      summary: Get system language
      description: Gets the system language.
      operationId: getRestPropertiesSystemlang
      x-api-path-slug: restpropertiessystemlang-get
      responses:
        200:
          description: OK
      tags:
      - System
      - Language
  /rest/items/attribute_values/{valueId}/names:
    get:
      summary: Get name and language for an attribute value ID
      description: Gets name and language for an attribute value ID. The attribute
        value ID must be specified.
      operationId: getRestItemsAttributeValuesValueNames
      x-api-path-slug: restitemsattribute-valuesvalueidnames-get
      parameters:
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Name
      - Languagean
      - Attribute
      - Value
      - ID
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