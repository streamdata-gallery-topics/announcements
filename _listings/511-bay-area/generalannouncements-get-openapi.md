---
swagger: "2.0"
x-collection-name: 511 Bay Area
x-complete: 0
info:
  title: Bay Area 511 Transit API San Francisco 511 General Announcements API
  description: San francisco 511 general announcements api.
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: api.511.org
basePath: /transit
paths:
  /GeneralAnnouncements:
    get:
      summary: San Francisco 511 General Announcements API
      description: San francisco 511 general announcements api.
      operationId: GeneralAnnouncementsGet
      x-api-path-slug: generalannouncements-get
      parameters:
      - in: query
        name: api_key
      responses:
        200:
          description: OK
      tags:
      - "511"
      - San
      - Francisco
      - "511"
      - General
      - Announcements
      - API
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