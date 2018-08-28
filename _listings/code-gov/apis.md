---
name: Code.gov
x-slug: code-gov
description: Code.gov leverages the power of code sharing and collaboration to help
  the US Government cut down on duplicative software development and save millions
  of taxpayer dollars for the American people.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-gov-logo.jpg
x-kinRank: "7"
x-alexaRank: "0"
tags: Languages
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/code-gov/apis.md
specificationVersion: "0.14"
apis:
- name: Code.gov API - Get a list of programming languages found in our code inventory.
  x-api-slug: languages-get
  description: This returns a list of the programming languages that are used in the
    indexed code inventory. When a repo is index the programming language is extracted
    written to a file.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-gov-logo.jpg
  humanURL: https://code.gov/
  baseURL: https://api.code.gov//
  tags: Federal Government, GitHub, Developers, API Service Provider, API Provider,
    Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/code-gov/languages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/languages/master/_listings/code-gov/languages-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://clover.api.gallery.streamdata.io
- type: x-api-stack
  url: http://code.gov.stack.network
- type: x-applications
  url: https://code.gov/#/explore-code
- type: x-developer
  url: https://api.code.gov/docs/
- type: x-documentation
  url: https://api.code.gov/docs/#
- type: x-road-map
  url: https://code.gov/#/roadmap
- type: x-twitter
  url: https://twitter.com/codedotgov
- type: x-website
  url: https://code.gov/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---