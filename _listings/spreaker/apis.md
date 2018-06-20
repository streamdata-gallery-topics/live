---
name: Spreaker
x-slug: spreaker
description: Discover and listen to your favorite podcasts for free or sign up to
  create your own!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
x-kinRank: "8"
x-alexaRank: "13176"
tags: Live
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/live/master/_listings/spreaker/apis.md
specificationVersion: "0.14"
apis:
- name: Spreaker API Get Live Episodes
  x-api-slug: spreaker-api
  description: Retrieves all live episodes at the moment of the request
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////episodes/live
  tags: Live,Episodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/live/master/_listings/spreaker/episodeslive-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/live/master/_listings/spreaker/episodeslive-get-openapi.md
- name: Spreaker API Get Top Live Episodes
  x-api-slug: spreaker-api
  description: Retrieves live episodes sorted by rank
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////lives/top
  tags: Top,Live,Episodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/live/master/_listings/spreaker/livestop-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/live/master/_listings/spreaker/livestop-get-openapi.md
- name: Spreaker API Get Favorite Live Episodes
  x-api-slug: spreaker-api
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////user/{user_id}/lives/fan
  tags: Favorite,Live,Episodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/live/master/_listings/spreaker/useruser-idlivesfan-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/live/master/_listings/spreaker/useruser-idlivesfan-get-openapi.md
- name: Spreaker API
  x-api-slug: spreaker-api
  description: Spreaker platform enables you to host and listen thousands of radio
    shows. Spreaker provides a REST web service that enables developers to read and
    write data to Spreaker.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com//
  tags: Live
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/live/master/_listings/spreaker/openapi.md
x-common:
- type: x-base
  url: http://api.spreaker.com/
- type: x-blog
  url: http://blog.spreaker.com
- type: x-crunchbase
  url: https://crunchbase.com/organization/spreaker
- type: x-crunchbase
  url: http://www.crunchbase.com/company/spreaker
- type: x-developer
  url: http://developers.spreaker.com
- type: x-email
  url: info@spreaker.com
- type: x-email
  url: support@spreaker.com
- type: x-email
  url: advertise@spreaker.com
- type: x-email
  url: tonia.maffeo@spreaker.com
- type: x-email
  url: press@spreaker.com
- type: x-email
  url: legal@Spreaker.com
- type: x-github
  url: https://github.com/spreaker
- type: x-pricing
  url: http://www.spreaker.com/plans
- type: x-twitter
  url: https://twitter.com/spreaker
- type: x-website
  url: http://spreaker.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---