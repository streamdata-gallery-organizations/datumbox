---
name: Datumbox
x-slug: datumbox
description: Build quickly and easily Intelligent Applications by using the power
  of Machine Learning!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
x-kinRank: "9"
x-alexaRank: "514549"
tags: Datumbox
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/apis.md
specificationVersion: "0.14"
apis:
- name: Datumbox Classifies the Document as adult or noadult
  x-api-slug: datumbox
  description: The Adult Content Detection function classifies the documents as adult
    or noadult based on their context. It can be used to detect whether a document
    contains content unsuitable for minors.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///AdultContentDetection.json
  tags: Adult Content,Detection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/adultcontentdetection-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/adultcontentdetection-json-post-openapi.md
- name: Datumbox Classifies the Document as commercial or nocommercial
  x-api-slug: datumbox
  description: The Commercial Detection function labels the documents as commercial
    or non-commercial based on their keywords and expressions. It can be used to detect
    whether a website is commercial or not.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///CommercialDetection.json
  tags: Commercial,Detection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/commercialdetection-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/commercialdetection-json-post-openapi.md
- name: Datumbox Estimates the similarity between 2 Documents
  x-api-slug: datumbox
  description: The Document Similarity function estimates the degree of similarity
    between two documents. It can be used to detect duplicate webpages or detect plagiarism.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///DocumentSimilarity.json
  tags: DocumentsSimilarity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/documentsimilarity-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/documentsimilarity-json-post-openapi.md
- name: Datumbox Classifies the Document as educational or noeducational
  x-api-slug: datumbox
  description: The Educational Detection function classifies the documents as educational
    or non-educational based on their context. It can be used to detect whether a
    website is educational or not.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///EducationalDetection.json
  tags: Educational,Detection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/educationaldetection-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/educationaldetection-json-post-openapi.md
- name: Datumbox Gender Detection Service
  x-api-slug: datumbox
  description: The Gender Detection function identifies if a particular document is
    written-by or targets-to a man or a woman based on the context, the words and
    the idioms found in the text.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///GenderDetection.json
  tags: Gender,Detection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/genderdetection-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/genderdetection-json-post-openapi.md
- name: Datumbox Extracts the Keywords of the Document
  x-api-slug: datumbox
  description: The Keyword Extraction function enables you to extract from an arbitrary
    document all the keywords and word-combinations along with their occurrences in
    the text.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///KeywordExtraction.json
  tags: Keyword,Extraction
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/keywordextraction-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/keywordextraction-json-post-openapi.md
- name: Datumbox Identifies the Language of the Document
  x-api-slug: datumbox
  description: The Language Detection function identifies the natural language of
    the given document based on its words and context. This classifier is able to
    detect 96 different languages.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///LanguageDetection.json
  tags: Language,Detection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/languagedetection-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/languagedetection-json-post-openapi.md
- name: Datumbox Evaluates the Readability of the Document
  x-api-slug: datumbox
  description: The Readability Assessment function determines the degree of readability
    of a document based on its terms and idioms. The texts are classified as basic,
    intermediate and advanced depending their difficulty.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///ReadabilityAssessment.json
  tags: Readability,Assessment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/readabilityassessment-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/readabilityassessment-json-post-openapi.md
- name: Datumbox Identifies the Sentiment of the Document
  x-api-slug: datumbox
  description: The Sentiment Analysis function classifies documents as positive, negative
    or neutral (lack of sentiment) depending on whether they express a positive, negative
    or neutral opinion.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///SentimentAnalysis.json
  tags: Sentiment,Analysis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/sentimentanalysis-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/sentimentanalysis-json-post-openapi.md
- name: Datumbox Classifies the Document as spam or nospam
  x-api-slug: datumbox
  description: The Spam Detection function labels documents as spam or nospam by taking
    into account their context. It can be used to filter out spam emails and comments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///SpamDetection.json
  tags: Spam,Detection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/spamdetection-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/spamdetection-json-post-openapi.md
- name: Datumbox Classifies Document as Subjective or Objective
  x-api-slug: datumbox
  description: The Subjectivity Analysis function categorizes documents as subjective
    or objective based on their writing style. Texts that express personal opinions
    are labeled as subjective and the others as objective.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///SubjectivityAnalysis.json
  tags: Subjectivity,Analysis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/subjectivityanalysis-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/subjectivityanalysis-json-post-openapi.md
- name: Datumbox Extracts the clear text from Webpage
  x-api-slug: datumbox
  description: The Text Extraction function enables you to extract the important information
    from a given webpage. Extracting the clear text of the documents is an important
    step before any other analysis.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///TextExtraction.json
  tags: Text,Extraction
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/textextraction-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/textextraction-json-post-openapi.md
- name: Datumbox Identifies the Topic of the Document
  x-api-slug: datumbox
  description: The Topic Classification function assigns documents in 12 thematic
    categories based on their keywords, idioms and jargon. It can be used to identify
    the topic of the texts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///TopicClassification.json
  tags: Topic,Classification
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/topicclassification-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/topicclassification-json-post-openapi.md
- name: Datumbox Identifies the Sentiment of Twitter Messages
  x-api-slug: datumbox
  description: The Twitter Sentiment Analysis function allows you to perform Sentiment
    Analysis on Twitter. It classifies the tweets as positive, negative or neutral
    depending on their context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0///TwitterSentimentAnalysis.json
  tags: Twitter,Sentiment,Analysis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/twittersentimentanalysis-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/twittersentimentanalysis-json-post-openapi.md
- name: Datumbox
  x-api-slug: datumbox
  description: Build quickly and easily Intelligent Applications by using the power
    of Machine Learning!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11516-datumbox.jpg
  humanURL: http://datumbox.com
  baseURL: https://api.datumbox.com/1.0/
  tags: Datumbox
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/datumbox/master/_listings/datumbox/openapi.md
x-common:
- type: x-api-json--authoritative
  url: http://apis.io/apisdef/legacy/datumbox.json
- type: x-blog
  url: http://blog.datumbox.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/Datumbox
- type: x-contact-form
  url: http://www.datumbox.com/contact/
- type: x-twitter
  url: https://twitter.com/datumbox
- type: x-developer
  url: http://www.datumbox.com/machine-learning-api/
- type: x-documentation
  url: http://www.datumbox.com/api-sandbox/
- type: x-email
  url: info@datumbox.com
- type: x-facebook
  url: https://www.facebook.com/Datumbox
- type: x-github
  url: https://github.com/datumbox
- type: x-google-plus
  url: https://plus.google.com/105921437813621882157/posts
- type: x-privacy
  url: http://www.datumbox.com/privacy-policy/
- type: x-terms-of-service
  url: http://www.datumbox.com/terms-of-use/
- type: x-website
  url: http://datumbox.com
- type: x-website
  url: http://www.datumbox.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---