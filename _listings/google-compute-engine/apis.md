---
name: Google Compute Engine
x-slug: google-compute-engine
description: Google Compute Engine delivers virtual machines running in Googles innovative
  data centers and worldwide fiber network. Compute Engines tooling and workflow support
  enable scaling from single instances to global, load-balanced cloud computing.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: VPN Gateway
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpn-gateway/master/_listings/google-compute-engine/apis.md
specificationVersion: "0.14"
apis:
- name: Compute Engine - Get Target Pool VPN Gateways
  x-api-slug: projectregionsregiontargetvpngateways-get
  description: Retrieves a list of target VPN gateways available to the specified
    project and region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpn-gateway/master/_listings/google-compute-engine/projectregionsregiontargetvpngateways-get-openapi.md
- name: Compute Engine - Create Target Pool VPN Gateway
  x-api-slug: projectregionsregiontargetvpngateways-post
  description: Creates a target VPN gateway in the specified project and region using
    the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpn-gateway/master/_listings/google-compute-engine/projectregionsregiontargetvpngateways-post-openapi.md
- name: Compute Engine - Delete Target Pool VPN Gateway
  x-api-slug: projectregionsregiontargetvpngatewaystargetvpngateway-delete
  description: Deletes the specified target VPN gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpn-gateway/master/_listings/google-compute-engine/projectregionsregiontargetvpngatewaystargetvpngateway-delete-openapi.md
- name: Compute Engine - Get Target Pool VPN Gateway
  x-api-slug: projectregionsregiontargetvpngatewaystargetvpngateway-get
  description: Returns the specified target VPN gateway. Get a list of available target
    VPN gateways by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Compute, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpn-gateway/master/_listings/google-compute-engine/projectregionsregiontargetvpngatewaystargetvpngateway-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.vision.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.compute.engine.stack.network
- type: x-code
  url: https://cloud.google.com/compute/docs/api/libraries
- type: x-documentation
  url: https://cloud.google.com/compute/docs/reference/latest/
- type: x-guides
  url: https://cloud.google.com/compute/docs/api/how-tos/how-tos
- type: x-rate-limits
  url: https://cloud.google.com/compute/docs/api-rate-limits
- type: x-sla
  url: https://cloud.google.com/compute/sla
- type: x-website
  url: https://cloud.google.com/compute/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---