---
swagger: "2.0"
info:
  title: Amazon Lightsale API Start Instance
  version: 1.0.0
  description: Starts a specific Amazon Lightsail instance from a stopped state.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=StartInstance:
    get:
      summary: ' Start Instance '
      description: Starts a specific Amazon Lightsail instance from a stopped state
      operationId: startInstance
      parameters:
      - in: query
        name: instanceName
        description: The name of the instance (a virtual private server) to start
        type: string
      responses:
        200:
          description: OK
      tags:
      - instances
definitions: []
x-collection-name: AWS Lightsale
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