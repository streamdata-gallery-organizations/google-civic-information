---
name: Google Civic Information
x-slug: google-civic-information
description: The Google Civic Information API lets developers build applications that
  display civic information to their users. For any U.S. residential address, you
  can look up who represents that address at each elected level of government. During
  supported elections, you can also look up polling places, early vote location, candidate
  data, and other election official information.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-civic-information-api.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Civic Information
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-civic-information/master/_listings/google-civic-information/apis.md
specificationVersion: "0.14"
apis:
- name: Google Civic Information API Search Political Divisions
  x-api-slug: google-civic-information-api
  description: Searches for political divisions by their natural name or OCD ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-civic-information-api.png
  humanURL: https://developers.google.com/civic-information/
  baseURL: ://www.googleapis.com//civicinfo/v2//divisions
  tags: Division
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-civic-information/master/_listings/google-civic-information/divisions-get-openapi.md
- name: Google Civic Information API List Elections
  x-api-slug: google-civic-information-api
  description: List of available elections to query.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-civic-information-api.png
  humanURL: https://developers.google.com/civic-information/
  baseURL: ://www.googleapis.com//civicinfo/v2//elections
  tags: Election
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-civic-information/master/_listings/google-civic-information/elections-get-openapi.md
- name: Google Civic Information API Lookup Representatives
  x-api-slug: google-civic-information-api
  description: Looks up political geography and representative information for a single
    address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-civic-information-api.png
  humanURL: https://developers.google.com/civic-information/
  baseURL: ://www.googleapis.com//civicinfo/v2//representatives
  tags: Representative
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-civic-information/master/_listings/google-civic-information/representatives-get-openapi.md
- name: Google Civic Information API Get Representative
  x-api-slug: google-civic-information-api
  description: Looks up representative information for a single geographic division.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-civic-information-api.png
  humanURL: https://developers.google.com/civic-information/
  baseURL: ://www.googleapis.com//civicinfo/v2//representatives/{ocdId}
  tags: Representative
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-civic-information/master/_listings/google-civic-information/representativesocdid-get-openapi.md
- name: Google Civic Information API Looks Up Voter Information
  x-api-slug: google-civic-information-api
  description: Looks up information relevant to a voter based on the voter's registered
    address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-civic-information-api.png
  humanURL: https://developers.google.com/civic-information/
  baseURL: ://www.googleapis.com//civicinfo/v2//voterinfo
  tags: Voter Information
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-civic-information/master/_listings/google-civic-information/voterinfo-get-openapi.md
- name: Google Civic Information API
  x-api-slug: google-civic-information-api
  description: The Google Civic Information API lets developers build applications
    that display civic information to their users. For any U.S. residential address,
    you can look up who represents that address at each elected level of government.
    During supported elections, you can also look up polling places, early vote location,
    candidate data, and other election official information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-civic-information-api.png
  humanURL: https://developers.google.com/civic-information/
  baseURL: ://www.googleapis.com//civicinfo/v2
  tags: Google Civic Information
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-civic-information/master/_listings/google-civic-information/openapi.md
x-common:
- type: x-data-guidelines
  url: https://developers.google.com/civic-information/docs/data_guidelines
- type: x-documentation
  url: https://developers.google.com/civic-information/docs/v2/
- type: x-embeddable
  url: https://developers.google.com/civic-information/docs/embed
- type: x-errors
  url: https://developers.google.com/civic-information/docs/v2/errors
- type: x-forum
  url: https://developers.google.com/civic-information/docs/ci_forum
- type: x-website
  url: https://developers.google.com/civic-information/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---