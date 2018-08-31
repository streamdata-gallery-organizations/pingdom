---
name: Pingdom
x-slug: pingdom
description: Monitor your websites availability and performance for free with Pingdom
  and always be the first to know when your website is down. No installation required.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
x-kinRank: "7"
x-alexaRank: "5876"
tags: Pingdom
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apis.md
specificationVersion: "0.14"
apis:
- name: Analysis API - Get Root Cause Analysis Results List
  x-api-slug: apiversionanalysischeckid-get
  description: Returns a list of the latest root cause analysis results for a specified
    check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: :///
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionanalysischeckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionanalysischeckid-get-openapi.md
- name: Checks API - Get Checks
  x-api-slug: checks-get
  description: Gets a list of all checks that are visible to you as a user or a customer
    depending on the request context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checks-get-openapi.md
- name: Checks API - Get Check
  x-api-slug: checkscheckid-get
  description: Gets info about a check, current SLA, last result and its status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckid-get-openapi.md
- name: Checks API - Update Check
  x-api-slug: checkscheckid-put
  description: Updates a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckid-put-openapi.md
- name: Checks API - Delete Check
  x-api-slug: checkscheckid-delete
  description: Deletes a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckid-delete-openapi.md
- name: Checks API - Get Checks Lastvalue
  x-api-slug: checkscheckidlastvalue-get
  description: Gets the absolute last value of a specific check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckidlastvalue-get-openapi.md
- name: Checks API - Get Checks Results
  x-api-slug: checkscheckidresultsmillisecondsutc-get
  description: Gets a specific check result by a numeric java timestamp.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckidresultsmillisecondsutc-get-openapi.md
- name: Checks API - Get Checks Results
  x-api-slug: checkscheckidresults-get
  description: Gets the most recent check results.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckidresults-get-openapi.md
- name: Checks API - Get Check List
  x-api-slug: apiversionchecks-get
  description: Returns a list overview of all checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionchecks-get-openapi.md
- name: Credits API - Get Credits List
  x-api-slug: apiversioncredits-get
  description: Returns information about remaining checks, SMS credits and SMS auto-refill
    status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversioncredits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversioncredits-get-openapi.md
- name: Probes API - Get Probe Server List
  x-api-slug: apiversionprobes-get
  description: Returns a list of all Pingdom probe servers for Uptime and Transaction
    checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionprobes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionprobes-get-openapi.md
- name: Reference API - Get Reference
  x-api-slug: apiversionreference-get
  description: Get a reference of regions, timezones and date/time/number formats
    and their identifiers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreference-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreference-get-openapi.md
- name: Reports API - Get Email Report Subscription List
  x-api-slug: apiversionreports-email-get
  description: Returns a list of email report subscriptions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreports-email-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreports-email-get-openapi.md
- name: Reports API - Get Public Report List
  x-api-slug: apiversionreports-public-get
  description: Returns a list of public (web-based) reports.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreports-public-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreports-public-get-openapi.md
- name: Reports API - Get Shared Reports (Banners) List
  x-api-slug: apiversionreports-shared-get
  description: Returns a list of shared reports (banners).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreports-shared-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreports-shared-get-openapi.md
- name: Results API - Get Raw Check Results
  x-api-slug: apiversionresultscheckid-get
  description: Return a list of raw test results for a specified check
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionresultscheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionresultscheckid-get-openapi.md
- name: Servertime API - Get Current Server Time
  x-api-slug: apiversionservertime-get
  description: Get the current time of the API server.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionservertime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionservertime-get-openapi.md
- name: Settings API - Get Account Settings
  x-api-slug: apiversionsettings-get
  description: Returns all account-specific settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsettings-get-openapi.md
- name: Single API - Make A Single Test
  x-api-slug: apiversionsingle-get
  description: Performs a single test using a specified Pingdom probe against a specified
    target. Please note that this method is meant to be used sparingly, not to set
    up your own monitoring solution.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsingle-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsingle-get-openapi.md
- name: Summary API - Get A Response Time / Uptime Average
  x-api-slug: apiversionsummary-averagecheckid-get
  description: Get the average time / uptime value for a specified check and time
    period.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummary-averagecheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummary-averagecheckid-get-openapi.md
- name: Summary API - Get Response Time Averages For Each Hour Of The Day
  x-api-slug: apiversionsummary-hoursofdaycheckid-get
  description: Returns the average response time for each hour of the day (0-23) for
    a specific check over a selected time period. I.e. it shows you what an average
    day looks like during that time period.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummary-hoursofdaycheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummary-hoursofdaycheckid-get-openapi.md
- name: Summary API - Get List of Outages
  x-api-slug: apiversionsummary-outagecheckid-get
  description: Get a list of status changes for a specified check and time period.
    If order is speficied to descending, the list is ordered by newest first. (Default
    is ordered by oldest first.)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummary-outagecheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummary-outagecheckid-get-openapi.md
- name: Summary API - Get Intervals of Average Response Time and Uptime During a Given
    Interval
  x-api-slug: apiversionsummary-performancecheckid-get
  description: |-
    For a given interval in time, return a list of sub intervals with the given resolution. Useful for generating graphs. A sub interval may be a week,
         a day or an hour depending on the choosen resolution.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummary-performancecheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummary-performancecheckid-get-openapi.md
- name: Summary API - Get Active Probes For A Period
  x-api-slug: apiversionsummary-probescheckid-get
  description: Get a list of probes that performed tests for a specified check during
    a specified period.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummary-probescheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummary-probescheckid-get-openapi.md
- name: Traceroute API - Make A Traceroute
  x-api-slug: apiversiontraceroute-get
  description: Perform a traceroute to a specified target from a specified Pingdom
    probe.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Monitoring, Performance, SaaS, Technology, internet, Service API, Relative
    Data, Relative StreamRank, Streams, Webhook Implementations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversiontraceroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversiontraceroute-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://pinboard.api.gallery.streamdata.io
- type: x-api-stack
  url: http://pingdom.stack.network
- type: x-base
  url: https://api.pingdom.com
- type: x-blog
  url: http://royal.pingdom.com/
- type: x-blog-rss
  url: http://royal.pingdom.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/pingdom
- type: x-crunchbase
  url: https://crunchbase.com/organization/pingdom
- type: x-developer
  url: https://www.pingdom.com/features/api/
- type: x-email
  url: sales@pingdom.com
- type: x-github
  url: https://github.com/Pingdom
- type: x-linkedin
  url: https://www.linkedin.com/company/pingdom
- type: x-pricing
  url: https://www.pingdom.com/pricing
- type: x-twitter
  url: https://twitter.com/#!/pingdom
- type: x-webhook
  url: https://www.pingdom.com/resources/webhooks/
- type: x-website
  url: http://www.pingdom.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---