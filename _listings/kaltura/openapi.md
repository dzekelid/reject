swagger: "2.0"
x-collection-name: Kaltura
x-complete: 1
info:
  title: Kaltura VPaaS
  description: building-video-experiences-consists-of-ingesting-media-files-playing-back-videos-and-reviewing-usage-and-engagement-analytics--in-between-there-is-a-world-of-nuances-required-for-your-unique-usecase-and-application--kaltura-vpaas-is-built-on-the-principles-of-atomic-services-sdks-and-tools-that-allow-you-full-control-and-flexibility-over-every-element-and-process-in-your-medias-life-cycle-
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
  /service/categoryentry/action/reject:
    get:
      summary: Get Service Categoryentry Action Reject
      description: activate CategoryEntry when it is pending moderation
      operationId: categoryEntry.reject
      x-api-path-slug: servicecategoryentryactionreject-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: entryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryentry
      - Action
      - Reject