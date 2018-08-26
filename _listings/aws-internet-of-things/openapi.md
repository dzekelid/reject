---
swagger: "2.0"
x-collection-name: AWS Internet of Things
x-complete: 1
info:
  title: AWS Internet of Things API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=RejectCertificateTransfer:
    get:
      summary: Reject Certificate Transfer
      description: Rejects a pending certificate transfer.
      operationId: rejectCertificateTransfer
      x-api-path-slug: actionrejectcertificatetransfer-get
      parameters:
      - in: query
        name: certificateId
        description: The ID of the certificate
        type: string
      - in: query
        name: rejectReason
        description: The reason the certificate transfer was rejected
        type: string
      responses:
        200:
          description: OK
      tags:
      - Certificate Transfers
---