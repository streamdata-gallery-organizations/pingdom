---
swagger: "2.0"
x-collection-name: Pingdom
x-complete: 0
info:
  title: Checks API Checks {checkId} Lastvalue
  description: Gets the absolute last value of a specific check.
  version: 1.0.0
host: api.pingdom.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/checks ':
    ' get ':
      summary: Checks
      description: Gets a list of all checks that are visible to you as a user or
        a customer depending on the request context.
      operationId: -checks-
      x-api-path-slug: checks-get
      responses:
        "":
          description: ""
        400:
          description: Bad input parameter
        401:
          description: Bad or expired token
        403:
          description: Bad OAuth request (wrong consumer key, bad nonce, expired timestamp
        404:
          description: File or folder not found at the specified path
        405:
          description: Request method not expected (generally should be GET or POST)
        429:
          description: Your app is making too many requests and is being rate limited
        503:
          description: If the response includes the Retry-After header, this means
            your OAuth 1
        507:
          description: User is over Dropbox storage quota
        5xx:
          description: Server error
        200:
          description: OK
      tags:
      - Checks
  '/checks/{checkId} ':
    ' get ':
      summary: Checks {checkId}
      description: Gets info about a check, current SLA, last result and its status.
      operationId: -checks-checkid-
      x-api-path-slug: checkscheckid-get
      responses:
        200:
          description: OK
      tags:
      - Checks
    ' put ':
      summary: Checks {checkId}
      description: Updates a check.
      operationId: -checks-checkid-
      x-api-path-slug: checkscheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
    ' delete ':
      summary: Checks {checkId}
      description: Deletes a check.
      operationId: -checks-checkid-
      x-api-path-slug: checkscheckid-delete
      responses:
        200:
          description: OK
      tags:
      - Checks
  '/checks/{checkId}/lastvalue ':
    ' get ':
      summary: Checks {checkId} Lastvalue
      description: Gets the absolute last value of a specific check.
      operationId: -checks-checkid-lastvalue-
      x-api-path-slug: checkscheckidlastvalue-get
      responses:
        200:
          description: OK
      tags:
      - Checks
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