---
swagger: "2.0"
x-collection-name: Datumbox
x-complete: 0
info:
  title: Datumbox Classifies the Document as commercial or nocommercial
  description: The Commercial Detection function labels the documents as commercial
    or non-commercial based on their keywords and expressions. It can be used to detect
    whether a website is commercial or not.
  version: 1.0.0
host: api.datumbox.com
basePath: 1.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /AdultContentDetection.json:
    post:
      summary: Classifies the Document as adult or noadult
      description: The Adult Content Detection function classifies the documents as
        adult or noadult based on their context. It can be used to detect whether
        a document contains content unsuitable for minors.
      operationId: AdultContentDetection
      x-api-path-slug: adultcontentdetectionjson-post
      parameters:
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Adult Content
      - Detection
  /CommercialDetection.json:
    post:
      summary: Classifies the Document as commercial or nocommercial
      description: The Commercial Detection function labels the documents as commercial
        or non-commercial based on their keywords and expressions. It can be used
        to detect whether a website is commercial or not.
      operationId: CommercialDetection
      x-api-path-slug: commercialdetectionjson-post
      parameters:
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Commercial
      - Detection
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