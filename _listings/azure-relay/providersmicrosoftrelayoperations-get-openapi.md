---
swagger: "2.0"
x-collection-name: Azure Relay
x-complete: 0
info:
  title: Azure Relay API Operations List
  description: Lists all of the available Relay REST API operations.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /providers/Microsoft.Relay/operations:
    get:
      summary: Operations List
      description: Lists all of the available Relay REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoftrelayoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
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