---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Baseentry Action Reject
  description: Reject the entry and mark the pending flags (if any) as moderated (this
    will make the entry non-playable).
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/baseentry/action/reject:
    get:
      summary: Get Service Baseentry Action Reject
      description: Reject the entry and mark the pending flags (if any) as moderated
        (this will make the entry non-playable).
      operationId: baseEntry.reject
      x-api-path-slug: servicebaseentryactionreject-get
      parameters:
      - in: query
        name: entryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Baseentry
      - Action
      - Reject
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