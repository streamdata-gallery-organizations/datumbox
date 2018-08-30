{
  "info": {
    "name": "Datumbox Gender Detection Service",
    "_postman_id": "8ec7e181-5e98-4e87-b272-65a14967490f",
    "description": "The Gender Detection function identifies if a particular document is written-by or targets-to a man or a woman based on the context, the words and the idioms found in the text.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Adult Content",
      "item": [
        {
          "id": "e5b248da-74a9-4c89-b7f9-89780c32764f",
          "name": "AdultContentDetection",
          "request": {
            "url": "http://api.datumbox.com/1.0/AdultContentDetection.json",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": "The text that you want to analyze"
                }
              ]
            },
            "description": "The Adult Content Detection function classifies the documents as adult or noadult based on their context. It can be used to detect whether a document contains content unsuitable for minors."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8cf57c09-b18d-44a6-8267-9b1426f4ca62"
            }
          ]
        }
      ]
    },
    {
      "name": "Commercial",
      "item": [
        {
          "id": "2d6401eb-8078-453a-ba7b-9d347d6a4ad2",
          "name": "CommercialDetection",
          "request": {
            "url": "http://api.datumbox.com/1.0/CommercialDetection.json",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": "The text that you want to analyze"
                }
              ]
            },
            "description": "The Commercial Detection function labels the documents as commercial or non-commercial based on their keywords and expressions. It can be used to detect whether a website is commercial or not."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1a7e43b0-a857-467b-a6a3-9114e6951686"
            }
          ]
        }
      ]
    },
    {
      "name": "DocumentsSimilarity",
      "item": [
        {
          "id": "7f36aec9-cd06-4482-bc2a-fc5aff6f4e3b",
          "name": "DocumentSimilarity",
          "request": {
            "url": "http://api.datumbox.com/1.0/DocumentSimilarity.json",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "copy",
                  "value": "{}",
                  "disabled": false,
                  "description": "The second text"
                },
                {
                  "key": "original",
                  "value": "{}",
                  "disabled": false,
                  "description": "The first text"
                }
              ]
            },
            "description": "The Document Similarity function estimates the degree of similarity between two documents. It can be used to detect duplicate webpages or detect plagiarism."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0f3b920-31c8-4868-9897-3df0084ed391"
            }
          ]
        }
      ]
    },
    {
      "name": "Educational",
      "item": [
        {
          "id": "f02cd392-0d41-4e45-8920-be6908540b35",
          "name": "EducationalDetection",
          "request": {
            "url": "http://api.datumbox.com/1.0/EducationalDetection.json",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": "The text that you want to analyze"
                }
              ]
            },
            "description": "The Educational Detection function classifies the documents as educational or non-educational based on their context. It can be used to detect whether a website is educational or not."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f176223b-63a7-45a4-b96b-660453f8b410"
            }
          ]
        }
      ]
    },
    {
      "name": "Gender",
      "item": [
        {
          "id": "65ea8c8e-8563-489f-8bd7-16baa2f1373e",
          "name": "GenderDetection",
          "request": {
            "url": "http://api.datumbox.com/1.0/GenderDetection.json",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": "The text that you want to analyze"
                }
              ]
            },
            "description": "The Gender Detection function identifies if a particular document is written-by or targets-to a man or a woman based on the context, the words and the idioms found in the text."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa5f93e1-37cd-40eb-bffa-ab0c4d7ad755"
            }
          ]
        }
      ]
    }
  ]
}