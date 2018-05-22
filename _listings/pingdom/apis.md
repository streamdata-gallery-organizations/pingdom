---
name: Pingdom
x-slug: pingdom
description: " Monitor your website\u2019s availability and performance for free with
  Pingdom and always be the first to know when your website is down. No installation
  required."
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
x-kinRank: "7"
x-alexaRank: "5592"
tags: Pingdom
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apis.md
specificationVersion: "0.14"
apis:
- name: Analysis API Get Root Cause Analysis Results List
  x-api-slug: analysis-api
  description: Returns a list of the latest root cause analysis results for a specified
    check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    :////
        /api/{version}/analysis/{checkid}
  tags: Analysis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionanalysischeckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionanalysischeckid-get-openapi.md
- name: Analysis API
  x-api-slug: analysis-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: :///
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
- name: Checks API Checks
  x-api-slug: checks-api
  description: Gets a list of all checks that are visible to you as a user or a customer
    depending on the request context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checks-get-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Gets info about a check, current SLA, last result and its status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckid-get-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Updates a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckid-put-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Deletes a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckid-delete-openapi.md
- name: Checks API Checks {checkId} Lastvalue
  x-api-slug: checks-api
  description: Gets the absolute last value of a specific check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks/{checkId}/lastvalue '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckidlastvalue-get-openapi.md
- name: Checks API Checks {checkId} Results {millisecondsUtc}?detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets a specific check result by a numeric java timestamp.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks/{checkId}/results/{millisecondsUtc}?detail_level={detail_level} '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckidresultsmillisecondsutcdetail-leveldetail-level-get-openapi.md
- name: Checks API Checks {checkId} Results?mostrecent={mostrecent}&amp;detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets the most recent check results.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks/{checkId}/results?mostrecent={mostrecent}&amp;detail_level={detail_level} '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckidresultsmostrecentmostrecentampdetail-leveldetail-level-get-openapi.md
- name: Checks API Checks {checkId} Results?fromUtc={fromUtc}&amp;toUtc={toUtc}&amp;detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets check results between two dates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: 'https://api.pingdom.com////checks/{checkId}/results?fromUtc={fromUtc}&amp;toUtc={toUtc}&amp;detail_level={detail_level} '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/checkscheckidresultsfromutcfromutcamptoutctoutcampdetail-leveldetail-level-get-openapi.md
- name: Checks API Get Check List
  x-api-slug: checks-api
  description: Returns a list overview of all checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/checks
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionchecks-get-openapi.md
- name: Checks API
  x-api-slug: checks-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
- name: Credits API Get Credits List
  x-api-slug: credits-api
  description: Returns information about remaining checks, SMS credits and SMS auto-refill
    status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/credits
  tags: Credits
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversioncredits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversioncredits-get-openapi.md
- name: Credits API
  x-api-slug: credits-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
- name: Probes API Get Probe Server List
  x-api-slug: probes-api
  description: Returns a list of all Pingdom probe servers for Uptime and Transaction
    checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/probes
  tags: Proves
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionprobes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionprobes-get-openapi.md
- name: Probes API
  x-api-slug: probes-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
- name: Reference API Get Reference
  x-api-slug: reference-api
  description: Get a reference of regions, timezones and date/time/number formats
    and their identifiers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/reference
  tags: Reerence
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreference-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreference-get-openapi.md
- name: Reference API
  x-api-slug: reference-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
- name: Reports API Get Email Report Subscription List
  x-api-slug: reports-api
  description: Returns a list of email report subscriptions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/reports.email
  tags: Reports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreportsemail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreportsemail-get-openapi.md
- name: Reports API Get Public Report List
  x-api-slug: reports-api
  description: Returns a list of public (web-based) reports.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/reports.public
  tags: Reports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreportspublic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreportspublic-get-openapi.md
- name: Reports API Get Shared Reports (Banners) List
  x-api-slug: reports-api
  description: Returns a list of shared reports (banners).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/reports.shared
  tags: Reports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreportsshared-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionreportsshared-get-openapi.md
- name: Reports API
  x-api-slug: reports-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
- name: Results API Get Raw Check Results
  x-api-slug: results-api
  description: Return a list of raw test results for a specified check
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/results/{checkid}
  tags: Results
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionresultscheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionresultscheckid-get-openapi.md
- name: Results API
  x-api-slug: results-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
- name: Servertime API Get Current Server Time
  x-api-slug: servertime-api
  description: Get the current time of the API server.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/servertime
  tags: Servertime
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionservertime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionservertime-get-openapi.md
- name: Servertime API
  x-api-slug: servertime-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
- name: Settings API Get Account Settings
  x-api-slug: settings-api
  description: Returns all account-specific settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/settings
  tags: Settings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsettings-get-openapi.md
- name: Settings API
  x-api-slug: settings-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
- name: Single API Make A Single Test
  x-api-slug: single-api
  description: Performs a single test using a specified Pingdom probe against a specified
    target. Please note that this method is meant to be used sparingly, not to set
    up your own monitoring solution.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/single
  tags: Single
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsingle-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsingle-get-openapi.md
- name: Single API
  x-api-slug: single-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
- name: Summary API Get A Response Time / Uptime Average
  x-api-slug: summary-api
  description: Get the average time / uptime value for a specified check and time
    period.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/summary.average/{checkid}
  tags: Summary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummaryaveragecheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummaryaveragecheckid-get-openapi.md
- name: Summary API Get Response Time Averages For Each Hour Of The Day
  x-api-slug: summary-api
  description: Returns the average response time for each hour of the day (0-23) for
    a specific check over a selected time period. I.e. it shows you what an average
    day looks like during that time period.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/summary.hoursofday/{checkid}
  tags: Summary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummaryhoursofdaycheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummaryhoursofdaycheckid-get-openapi.md
- name: Summary API Get List of Outages
  x-api-slug: summary-api
  description: Get a list of status changes for a specified check and time period.
    If order is speficied to descending, the list is ordered by newest first. (Default
    is ordered by oldest first.)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/summary.outage/{checkid}
  tags: Summary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummaryoutagecheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummaryoutagecheckid-get-openapi.md
- name: Summary API Get Intervals of Average Response Time and Uptime During a Given
    Interval
  x-api-slug: summary-api
  description: |-
    For a given interval in time, return a list of sub intervals with the given resolution. Useful for generating graphs. A sub interval may be a week,
         a day or an hour depending on the choosen resolution.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/summary.performance/{checkid}
  tags: Summary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummaryperformancecheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummaryperformancecheckid-get-openapi.md
- name: Summary API Get Active Probes For A Period
  x-api-slug: summary-api
  description: Get a list of probes that performed tests for a specified check during
    a specified period.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/summary.probes/{checkid}
  tags: Summary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummaryprobescheckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversionsummaryprobescheckid-get-openapi.md
- name: Summary API
  x-api-slug: summary-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
- name: Traceroute API Make A Traceroute
  x-api-slug: traceroute-api
  description: Perform a traceroute to a specified target from a specified Pingdom
    probe.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/traceroute
  tags: Traceroute
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversiontraceroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/apiversiontraceroute-get-openapi.md
- name: Traceroute API
  x-api-slug: traceroute-api
  description: " Monitor your website\u2019s availability and performance for free
    with Pingdom and always be the first to know when your website is down. No installation
    required."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/456-pingdom.jpg
  humanURL: http://www.pingdom.com
  baseURL: https://api.pingdom.com//
  tags: Pingdom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/pingdom/master/_listings/pingdom/openapi.md
x-common:
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
- type: x-pricing
  url: https://www.pingdom.com/pricing
- type: x-twitter
  url: https://twitter.com/#!/pingdom
- type: x-website
  url: http://www.pingdom.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---