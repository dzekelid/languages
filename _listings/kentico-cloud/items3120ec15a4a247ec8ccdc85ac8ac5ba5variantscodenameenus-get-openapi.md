---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 0
info:
  title: Kentico Cloud View a language variant by language codename
  description: Retrieve content of a variant of a content item. The content item is
    specified by its internal ID and the project language is specified by its codename.
  version: 1.0.0
host: deliver.kenticocloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /items/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5/variants/codename/en-US:
    get:
      summary: View a language variant by language codename
      description: Retrieve content of a variant of a content item. The content item
        is specified by its internal ID and the project language is specified by its
        codename.
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5VariantsCodenameEnUSGet
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5variantscodenameenus-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Language
      - Variant
      - By
      - Language
      - Codename
    put:
      summary: Upsert a variant by language codename
      description: "Add content to a variant in an active project language, or update
        an existing language variant. The content item is specified by its internal
        ID and the project language is specified by its codename.\r\n\r\n**Note:**
        Only the elements specified in the request body will be modified. Any existing
        comments attached to these elements will be lost on update."
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5VariantsCodenameEnUSPut
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5variantscodenameenus-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Upsert
      - Variant
      - By
      - Language
      - Codename
    delete:
      summary: Delete a variant by language codename
      description: "Delete a specific language variant. The content item is specified
        by its external ID and the project language is specified by its codename.\r\n\r\nNote
        that when you delete the last variant of a content item, the whole content
        item is deleted."
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5VariantsCodenameEnUSDelete3
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5variantscodenameenus-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Variant
      - By
      - Language
      - Codename
  /items/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5/variants/00000000-0000-0000-0000-000000000000:
    get:
      summary: View a language variant by language ID
      description: Retrieve content of a language variant of a content item. Both
        the content item and the project language are specified by their internal
        IDs.
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5Variants00000000000000000000000000000000Get
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5variants00000000000000000000000000000000-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Language
      - Variant
      - By
      - Language
      - ID
    put:
      summary: Upsert a variant by language ID
      description: "Add content to a variant in an active project language, or update
        an existing language variant. Both the content item and project language are
        specified by their internal IDs.\r\n\r\n**Note:** Only the elements specified
        in the request body will be modified. Any existing comments attached to these
        elements will be lost on update."
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5Variants00000000000000000000000000000000Put
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5variants00000000000000000000000000000000-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Upsert
      - Variant
      - By
      - Language
      - ID
    delete:
      summary: Delete a variant by language ID
      description: "Delete a specific language variant. Both the content item and
        the project language are specified by their internal IDs.\r\n\r\nNote that
        when you delete the last variant of a content item, the whole content item
        is deleted."
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5Variants00000000000000000000000000000000Delete
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5variants00000000000000000000000000000000-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Variant
      - By
      - Language
      - ID
  /items/external-id/59713/variants/00000000-0000-0000-0000-000000000000:
    get:
      summary: View a language variant by language ID
      description: Retrieve content of a variant of a content item. The content item
        is specified by its external ID and the project language is specified by its
        internal ID.
      operationId: ItemsExternalId59713Variants00000000000000000000000000000000Get
      x-api-path-slug: itemsexternalid59713variants00000000000000000000000000000000-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Language
      - Variant
      - By
      - Language
      - ID
    put:
      summary: Upsert a variant by language ID
      description: "Add content to a variant in an active project language, or update
        an existing language variant. The content item is specified by its external
        ID and the project language is specified by its internal ID.\r\n\r\n**Note:**
        Only the elements specified in the request body will be modified. Any existing
        comments attached to these elements will be lost on update."
      operationId: ItemsExternalId59713Variants00000000000000000000000000000000Put
      x-api-path-slug: itemsexternalid59713variants00000000000000000000000000000000-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Upsert
      - Variant
      - By
      - Language
      - ID
    delete:
      summary: Delete a variant by language ID
      description: "Delete a specific language variant. The content item is specified
        by its external ID and the project language is specified by its internal ID.\r\n\r\nNote
        that when you delete the last variant of a content item, the whole content
        item is deleted."
      operationId: ItemsExternalId59713Variants00000000000000000000000000000000Delete
      x-api-path-slug: itemsexternalid59713variants00000000000000000000000000000000-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Variant
      - By
      - Language
      - ID
  /items/external-id/59713/variants/codename/en-US:
    get:
      summary: View a language variant by language codename
      description: Retrieve content of a variant of a content item. The content item
        is specified by its external ID and the project language is specified by its
        codename.
      operationId: ItemsExternalId59713VariantsCodenameEnUSGet
      x-api-path-slug: itemsexternalid59713variantscodenameenus-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Language
      - Variant
      - By
      - Language
      - Codename
    put:
      summary: Upsert a variant by language codename
      description: "Add content to a variant in an active project language, or update
        an existing language variant. The content item is specified by its external
        ID and the project language is specified by its codename.\r\n\r\n**Note:**
        Only the elements specified in the request body will be modified. Any existing
        comments attached to these elements will be lost on update."
      operationId: ItemsExternalId59713VariantsCodenameEnUSPut
      x-api-path-slug: itemsexternalid59713variantscodenameenus-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Upsert
      - Variant
      - By
      - Language
      - Codename
  /items/codename/on_roasts/variants:
    get:
      summary: List language variants
      description: Retrieve a list of language variants of a content item specified
        by its codename.
      operationId: ItemsCodenameOnRoastsVariantsGet
      x-api-path-slug: itemscodenameon-roastsvariants-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - List
      - Language
      - Variants
  /items/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5/variants:
    get:
      summary: List language variants
      description: Retrieve a list of language variants of a content item specified
        by its internal ID.
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5VariantsGet
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5variants-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - List
      - Language
      - Variants
  /items/codename/on_roasts/variants/00000000-0000-0000-0000-000000000000:
    get:
      summary: View a language variant by language ID
      description: Retrieve content of a variant of a content item. The content item
        is specified by codename and the project language is specified its internal
        ID.
      operationId: ItemsCodenameOnRoastsVariants00000000000000000000000000000000Get
      x-api-path-slug: itemscodenameon-roastsvariants00000000000000000000000000000000-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Language
      - Variant
      - By
      - Language
      - ID
    put:
      summary: Upsert a variant by language ID
      description: "Add content to a variant in an active project language, or update
        an existing language variant. The content item is specified by its codename
        and the project language is specified by its internal ID.\r\n\r\n**Note:**
        Only the elements specified in the request body will be modified. Any existing
        comments attached to these elements will be lost on update."
      operationId: ItemsCodenameOnRoastsVariants00000000000000000000000000000000Put
      x-api-path-slug: itemscodenameon-roastsvariants00000000000000000000000000000000-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Upsert
      - Variant
      - By
      - Language
      - ID
    delete:
      summary: Delete a variant by language ID
      description: "Delete a specific language variant. The content item is specified
        by codename and the project language is specified its internal ID.\r\n\r\nNote
        that when you delete the last variant of a content item, the whole content
        item is deleted."
      operationId: ItemsCodenameOnRoastsVariants00000000000000000000000000000000Delete
      x-api-path-slug: itemscodenameon-roastsvariants00000000000000000000000000000000-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Variant
      - By
      - Language
      - ID
  /items/codename/on_roasts/variants/codename/en-US:
    get:
      summary: View a language variant by language codename
      description: Retrieve content of a language variant of a content item. Both
        the content item and the language are specified by their codenames.
      operationId: ItemsCodenameOnRoastsVariantsCodenameEnUSGet
      x-api-path-slug: itemscodenameon-roastsvariantscodenameenus-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Language
      - Variant
      - By
      - Language
      - Codename
    put:
      summary: Upsert a variant by language codename
      description: "Add content to a variant in an active project language, or update
        an existing language variant. Both the content item and project language are
        specified by their codenames.\r\n\r\n**Note:** Only the elements specified
        in the request body will be modified. Any existing comments attached to these
        elements will be lost on update."
      operationId: ItemsCodenameOnRoastsVariantsCodenameEnUSPut
      x-api-path-slug: itemscodenameon-roastsvariantscodenameenus-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Upsert
      - Variant
      - By
      - Language
      - Codename
  /items/external-id/59713/variants:
    get:
      summary: List language variants
      description: Retrieve a list of language variants of a content item specified
        by its external ID.
      operationId: ItemsExternalId59713VariantsGet
      x-api-path-slug: itemsexternalid59713variants-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - List
      - Language
      - Variants
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