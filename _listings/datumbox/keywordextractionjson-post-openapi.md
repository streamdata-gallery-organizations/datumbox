---
swagger: "2.0"
x-collection-name: Datumbox
x-complete: 0
info:
  title: Datumbox Extracts the Keywords of the Document
  description: The Keyword Extraction function enables you to extract from an arbitrary
    document all the keywords and word-combinations along with their occurrences in
    the text.
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
  /DocumentSimilarity.json:
    post:
      summary: Estimates the similarity between 2 Documents
      description: The Document Similarity function estimates the degree of similarity
        between two documents. It can be used to detect duplicate webpages or detect
        plagiarism.
      operationId: DocumentSimilarity
      x-api-path-slug: documentsimilarityjson-post
      parameters:
      - in: formData
        name: copy
        description: The second text
      - in: formData
        name: original
        description: The first text
      responses:
        200:
          description: OK
      tags:
      - DocumentsSimilarity
  /EducationalDetection.json:
    post:
      summary: Classifies the Document as educational or noeducational
      description: The Educational Detection function classifies the documents as
        educational or non-educational based on their context. It can be used to detect
        whether a website is educational or not.
      operationId: EducationalDetection
      x-api-path-slug: educationaldetectionjson-post
      parameters:
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Educational
      - Detection
  /GenderDetection.json:
    post:
      summary: Gender Detection Service
      description: The Gender Detection function identifies if a particular document
        is written-by or targets-to a man or a woman based on the context, the words
        and the idioms found in the text.
      operationId: GenderDetection
      x-api-path-slug: genderdetectionjson-post
      parameters:
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Gender
      - Detection
  /KeywordExtraction.json:
    post:
      summary: Extracts the Keywords of the Document
      description: The Keyword Extraction function enables you to extract from an
        arbitrary document all the keywords and word-combinations along with their
        occurrences in the text.
      operationId: KeywordExtraction
      x-api-path-slug: keywordextractionjson-post
      parameters:
      - in: formData
        name: "n"
        description: The number of keyword combinations (n-grams) that you wish to
          extract
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Keyword
      - Extraction
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