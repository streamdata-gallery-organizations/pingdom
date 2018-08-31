---
swagger: "2.0"
x-collection-name: Pingdom
x-complete: 0
info:
  title: Servertime API Get Current Server Time
  description: Get the current time of the API server.
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? |2-

        /api/{version}/analysis/{checkid}
  : ? |2-

          get
    : summary: Get Root Cause Analysis Results List
      description: Returns a list of the latest root cause analysis results for a
        specified check.
      operationId: get-root-cause-analysis-results-list
      x-api-path-slug: apiversionanalysischeckid-get
      parameters:
      - in: query
        name: from
        description: Return only results with timestamp of first test greater or equal
          to this value
        type: <td>integer</td>
      - in: query
        name: limit
        description: Limits the number of returned results to the specified quantity
        type: <td>integer</td>
      - in: query
        name: offset
        description: Offset for listing
        type: <td>integer</td>
      - in: query
        name: to
        description: Return only results with timestamp of first test less or equal
          to this value
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
      tags:
      - Analysis
  '/checks ':
    ' get ':
      summary: Get Checks
      description: Gets a list of all checks that are visible to you as a user or
        a customer depending on the request context.
      operationId: getChecks
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
      summary: Get Check
      description: Gets info about a check, current SLA, last result and its status.
      operationId: getChecksCheck
      x-api-path-slug: checkscheckid-get
      responses:
        200:
          description: OK
      tags:
      - Checks
    ' put ':
      summary: Update Check
      description: Updates a check.
      operationId: putChecksCheck
      x-api-path-slug: checkscheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
    ' delete ':
      summary: Delete Check
      description: Deletes a check.
      operationId: deleteChecksCheck
      x-api-path-slug: checkscheckid-delete
      responses:
        200:
          description: OK
      tags:
      - Checks
  '/checks/{checkId}/lastvalue ':
    ' get ':
      summary: Get Checks Lastvalue
      description: Gets the absolute last value of a specific check.
      operationId: getChecksCheckLastvalue
      x-api-path-slug: checkscheckidlastvalue-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  /checks/{checkId}/results/{millisecondsUtc}:
    ' get ':
      summary: Get Checks Results
      description: Gets a specific check result by a numeric java timestamp.
      operationId: getChecksCheckResultsMillisecondsutcDetailLevelDetailLevel
      x-api-path-slug: checkscheckidresultsmillisecondsutc-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  /checks/{checkId}/results:
    ' get ':
      summary: Get Checks Results
      description: Gets the most recent check results.
      operationId: getChecksCheckResultsMostrecentMostrecent&amp;detailLevelDetailLevel
      x-api-path-slug: checkscheckidresults-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  ? |2-

        /api/{version}/checks
  : ? |2-

          get
    : summary: Get Check List
      description: Returns a list overview of all checks.
      operationId: |2-

        getApiVersionChecks
      x-api-path-slug: apiversionchecks-get
      parameters:
      - in: query
        name: include_tags
        description: Include tag list for each check
        type: <td>boolean</td>
      - in: query
        name: limit
        description: Limits the number of returned probes to the specified quantity
        type: <td>integer</td>
      - in: query
        name: offset
        description: Offset for listing
        type: <td>integer</td>
      - in: query
        name: tags
        description: Tag list separated by commas
        type: <td>string</td>
      responses:
        200:
          description: OK
      tags:
      - Checks
  ? |2-

        /api/{version}/credits
  : ? |2-

          get
    : summary: Get Credits List
      description: Returns information about remaining checks, SMS credits and SMS
        auto-refill status.
      operationId: get-credits-list
      x-api-path-slug: apiversioncredits-get
      responses:
        200:
          description: OK
      tags:
      - Credits
  ? |2-

        /api/{version}/probes
  : ? |2-

          get
    : summary: Get Probe Server List
      description: Returns a list of all Pingdom probe servers for Uptime and Transaction
        checks.
      operationId: get-probe-server-list
      x-api-path-slug: apiversionprobes-get
      parameters:
      - in: query
        name: includedeleted
        description: Include old probes that are no longer in use
        type: <td>boolean</td>
      - in: query
        name: limit
        description: Limits the number of returned probes to the specified quantity
        type: <td>integer</td>
      - in: query
        name: offset
        description: Offset for listing
        type: <td>integer</td>
      - in: query
        name: onlyactive
        description: Return only active probes
        type: <td>boolean</td>
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
      tags:
      - Proves
  ? |2-

        /api/{version}/reference
  : ? |2-

          get
    : summary: Get Reference
      description: Get a reference of regions, timezones and date/time/number formats
        and their identifiers.
      operationId: get-reference
      x-api-path-slug: apiversionreference-get
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
      tags:
      - Reerence
  ? |2-

        /api/{version}/reports.email
  : ? |2-

          get
    : summary: Get Email Report Subscription List
      description: Returns a list of email report subscriptions.
      operationId: get-email-report-subscription-list
      x-api-path-slug: apiversionreports-email-get
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
      tags:
      - Reports
  ? |2-

        /api/{version}/reports.public
  : ? |2-

          get
    : summary: Get Public Report List
      description: Returns a list of public (web-based) reports.
      operationId: get-public-report-list
      x-api-path-slug: apiversionreports-public-get
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
      tags:
      - Reports
  ? |2-

        /api/{version}/reports.shared
  : ? |2-

          get
    : summary: Get Shared Reports (Banners) List
      description: Returns a list of shared reports (banners).
      operationId: get-shared-reports-banners-list
      x-api-path-slug: apiversionreports-shared-get
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
      tags:
      - Reports
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
  ? |2-

        /api/{version}/servertime
  : ? |2-

          get
    : summary: Get Current Server Time
      description: Get the current time of the API server.
      operationId: get-current-server-time
      x-api-path-slug: apiversionservertime-get
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
      tags:
      - Servertime
host: api.pingdom.com
basePath: /
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