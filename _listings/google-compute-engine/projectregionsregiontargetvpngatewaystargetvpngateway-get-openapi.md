---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 0
info:
  title: Google Compute Engine API Get Target Pool VPN Gateway
  description: Returns the specified target VPN gateway. Get a list of available target
    VPN gateways by making a list() request.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /compute/v1/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/regions/{region}/targetVpnGateways:
    get:
      summary: Get Target Pool VPN Gateways
      description: Retrieves a list of target VPN gateways available to the specified
        project and region.
      operationId: compute.targetVpnGateways.list
      x-api-path-slug: projectregionsregiontargetvpngateways-get
      parameters:
      - in: query
        name: filter
        description: Sets a filter expression for filtering listed resources, in the
          form filter={expression}
      - in: query
        name: maxResults
        description: The maximum number of results per page that should be returned
      - in: query
        name: orderBy
        description: Sorts list results by a certain order
      - in: query
        name: pageToken
        description: Specifies a page token to use
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region for this request
      responses:
        200:
          description: OK
      tags:
      - VPN Gateway
    post:
      summary: Create Target Pool VPN Gateway
      description: Creates a target VPN gateway in the specified project and region
        using the data included in the request.
      operationId: compute.targetVpnGateways.insert
      x-api-path-slug: projectregionsregiontargetvpngateways-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region for this request
      responses:
        200:
          description: OK
      tags:
      - VPN Gateway
  /{project}/regions/{region}/targetVpnGateways/{targetVpnGateway}:
    delete:
      summary: Delete Target Pool VPN Gateway
      description: Deletes the specified target VPN gateway.
      operationId: compute.targetVpnGateways.delete
      x-api-path-slug: projectregionsregiontargetvpngatewaystargetvpngateway-delete
      parameters:
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region for this request
      - in: path
        name: targetVpnGateway
        description: Name of the target VPN gateway to delete
      responses:
        200:
          description: OK
      tags:
      - VPN Gateway
    get:
      summary: Get Target Pool VPN Gateway
      description: Returns the specified target VPN gateway. Get a list of available
        target VPN gateways by making a list() request.
      operationId: compute.targetVpnGateways.get
      x-api-path-slug: projectregionsregiontargetvpngatewaystargetvpngateway-get
      parameters:
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region for this request
      - in: path
        name: targetVpnGateway
        description: Name of the target VPN gateway to return
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