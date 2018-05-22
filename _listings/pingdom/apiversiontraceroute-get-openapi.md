---
swagger: "2.0"
x-collection-name: Pingdom
x-complete: 0
info:
  title: Traceroute API Make A Traceroute
  description: Perform a traceroute to a specified target from a specified Pingdom
    probe.
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

        /api/{version}/traceroute
  : ? |2-

          get
    : summary: Make A Traceroute
      description: Perform a traceroute to a specified target from a specified Pingdom
        probe.
      operationId: make-a-traceroute
      x-api-path-slug: apiversiontraceroute-get
      parameters:
      - in: query
        name: host
        description: Target host
        type: <td>string</td>
      - in: query
        name: probeid
        description: Probe identifier
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
        apps:
          description: app_allow
        devices:
          description: device_link
        members:
          description: member_invite
        passwords:
          description: tfa_enable
        sharing:
          description: shmodel_create
        team_admin_actions:
          description: sf_external_accept_allow
      tags:
      - Traceroute
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