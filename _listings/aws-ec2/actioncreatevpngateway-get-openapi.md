---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Create Vpn Gateway
  version: 1.0.0
  description: Creates a virtual private gateway.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AttachVpnGateway:
    get:
      summary: Attach Vpn Gateway
      description: Attaches a virtual private gateway to a VPC.
      operationId: attachvpngateway
      x-api-path-slug: actionattachvpngateway-get
      parameters:
      - in: query
        name: AvailabilityZone
        description: The Availability Zone for the virtual private gateway
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Type
        description: The type of VPN connection this virtual private gateway supports
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Gateway
  /?Action=CreateVpnGateway:
    get:
      summary: Create Vpn Gateway
      description: Creates a virtual private gateway.
      operationId: createvpngateway
      x-api-path-slug: actioncreatevpngateway-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: VpnGatewayId
        description: The ID of the virtual private gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Gateway
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