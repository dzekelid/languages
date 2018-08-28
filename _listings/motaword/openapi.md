swagger: "2.0"
x-collection-name: MotaWord
x-complete: 1
info:
  title: Mota Word
  description: use-motaword-api-to-post-and-track-your-translation-projects-
  version: alpha-0.1.0
host: api.motaword.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /languages:
    get:
      summary: Get a list of supported languages
      description: Get a list of supported languages.
      operationId: getLanguages
      x-api-path-slug: languages-get
      responses:
        200:
          description: OK
      tags:
      - Languages
  /projects/{id}/download/{language}:
    post:
      summary: Download the latest translation package.
      description: Download only the translation package of this language. You must
        have given a /package call beforehand and wait until the packaging status
        is 'completed'.
      operationId: downloadLanguage
      x-api-path-slug: projectsiddownloadlanguage-post
      parameters:
      - in: path
        name: id
        description: Project ID
      - in: path
        name: language
        description: Language code
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Download
      - Language
  /projects/{id}/package/{language}:
    post:
      summary: Package the translation of a specific target language to be downloaded.
      description: Package the translation of a specific target language to be downloaded..
      operationId: packageLanguage
      x-api-path-slug: projectsidpackagelanguage-post
      parameters:
      - in: query
        name: async
        description: If you want to package and download the translation synchronously,
          mark this parameter as 0
      - in: path
        name: id
        description: Project ID
      - in: path
        name: language
        description: Language code
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Package
      - Language