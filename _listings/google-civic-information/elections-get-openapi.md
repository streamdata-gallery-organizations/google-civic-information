---
swagger: "2.0"
x-collection-name: Google Civic Information
x-complete: 0
info:
  title: Google Civic Information API List Elections
  description: List of available elections to query.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /civicinfo/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /divisions:
    get:
      summary: Search Political Divisions
      description: Searches for political divisions by their natural name or OCD ID.
      operationId: civicinfo.divisions.search
      x-api-path-slug: divisions-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: query
        description: The search query
      responses:
        200:
          description: OK
      tags:
      - Division
  /elections:
    get:
      summary: List Elections
      description: List of available elections to query.
      operationId: civicinfo.elections.electionQuery
      x-api-path-slug: elections-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Election
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