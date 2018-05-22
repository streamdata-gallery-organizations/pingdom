---
swagger: "2.0"
x-collection-name: Pingdom
x-complete: 0
info:
  title: Results API Get Raw Check Results
  description: Return a list of raw test results for a specified check
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
  ? |2-

        /api/{version}/results/{checkid}
  : ? |2-

          get
    : summary: Get Raw Check Results
      description: Return a list of raw test results for a specified check
      operationId: get-raw-check-results
      x-api-path-slug: apiversionresultscheckid-get
      parameters:
      - in: query
        name: from
        description: Start of period
        type: <td>integer</td>
      - in: query
        name: includeanalysis
        description: Attach available root cause analysis identifiers to corresponding
          results
        type: <td>boolean</td>
      - in: query
        name: limit
        description: Number of results to show (Will be set to 1000 if the provided
          value is greater than 1000)
        type: <td>integer</td>
      - in: query
        name: maxresponse
        description: Maximum response time (ms)
        type: <td>integer</td>
      - in: query
        name: minresponse
        description: Minimum response time (ms)
        type: <td>integer</td>
      - in: query
        name: offset
        description: Number of results to skip (Max value is 43200)
        type: <td>integer</td>
      - in: query
        name: probes
        description: Filter to only show results from a list of probes
        type: <td>string</td>
      - in: query
        name: status
        description: Filter to only show results with specified statuses
        type: <td>string</td>
      - in: query
        name: to
        description: End of period
        type: <td>integer</td>
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
      - Results
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