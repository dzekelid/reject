---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Post Managers Reject Artistid Reason
  version: 1.0.0
  description: Post managers reject artistid reason.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/admin/event/reject:
    post:
      summary: Post Admin Event Reject
      description: Post admin event reject.
      operationId: postApiV1AdminEventReject
      x-api-path-slug: apiv1admineventreject-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Event
      - Reject
  /api/v1/admin/placeReview/{reviewId}/reject:
    post:
      summary: Post Admin Placereview Reviewid Reject
      description: Post admin placereview reviewid reject.
      operationId: postApiV1AdminPlacereviewReviewReject
      x-api-path-slug: apiv1adminplacereviewreviewidreject-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: reason
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: reviewId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Placereview
      - Reviewid
      - Reject
  /api/v1/managers/reject/{artistId}/{reason}:
    post:
      summary: Post Managers Reject Artistid Reason
      description: Post managers reject artistid reason.
      operationId: postApiV1ManagersRejectArtistReason
      x-api-path-slug: apiv1managersrejectartistidreason-post
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      - in: path
        name: reason
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Reject
      - Artistid
      - Reason
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