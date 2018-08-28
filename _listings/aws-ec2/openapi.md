swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 1
info:
  title: AWS EC2 API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=RejectVpcPeeringConnection:
    get:
      summary: Reject Vpc Peering Connection
      description: Rejects a VPC peering connection request.
      operationId: rejectvpcpeeringconnection
      x-api-path-slug: actionrejectvpcpeeringconnection-get
      parameters:
      - in: query
        name: CustomerGatewayId
        description: The ID of the customer gateway
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Options
        description: Indicates whether the VPN connection requires static routes
        type: string
      - in: query
        name: Type
        description: The type of VPN connection (ipsec
        type: string
      - in: query
        name: VpnGatewayId
        description: The ID of the virtual private gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection