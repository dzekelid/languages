{
  "info": {
    "name": "Datumbox Identifies the Language of the Document",
    "_postman_id": "f06cf9ce-c2ba-45b8-889d-124af87b4439",
    "description": "The Language Detection function identifies the natural language of the given document based on its words and context. This classifier is able to detect 96 different languages.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Adult Content",
      "item": [
        {
          "id": "670f7703-e082-4037-a0a0-013d16458625",
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
              "id": "35dd9109-392f-428b-901d-b7b36d54c3d0"
            }
          ]
        }
      ]
    },
    {
      "name": "Commercial",
      "item": [
        {
          "id": "b560be38-dd79-4d92-a0eb-959a37c65375",
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
              "id": "dc0b0d2d-4967-4b08-8282-3a2a035eaf7f"
            }
          ]
        }
      ]
    },
    {
      "name": "DocumentsSimilarity",
      "item": [
        {
          "id": "b9347b51-43a9-4c3d-be96-26f89dded88f",
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
              "id": "59f6d774-8213-48c9-9b74-7f019e6c28a2"
            }
          ]
        }
      ]
    },
    {
      "name": "Educational",
      "item": [
        {
          "id": "8d68d090-0e03-4158-b38d-e04b3454f5d4",
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
              "id": "4ec50cf0-8b59-49e4-8685-47e6954a7af5"
            }
          ]
        }
      ]
    },
    {
      "name": "Gender",
      "item": [
        {
          "id": "58afd5e6-6778-4a12-aea4-9647a077fb0f",
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
              "id": "143cdc77-8a34-4b46-8356-3f4e376d23e8"
            }
          ]
        }
      ]
    },
    {
      "name": "Keyword",
      "item": [
        {
          "id": "15c3a9c4-0b24-4bd9-9795-7315b71d7011",
          "name": "KeywordExtraction",
          "request": {
            "url": "http://api.datumbox.com/1.0/KeywordExtraction.json",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "n",
                  "value": "{}",
                  "disabled": false,
                  "description": "The number of keyword combinations (n-grams) that you wish to extract"
                },
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": "The text that you want to analyze"
                }
              ]
            },
            "description": "The Keyword Extraction function enables you to extract from an arbitrary document all the keywords and word-combinations along with their occurrences in the text."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "049d6b3e-7943-4146-8b6b-f930de661e43"
            }
          ]
        }
      ]
    },
    {
      "name": "Language",
      "item": [
        {
          "id": "79e15680-dcb2-443e-8cda-827000c7f768",
          "name": "LanguageDetection",
          "request": {
            "url": "http://api.datumbox.com/1.0/LanguageDetection.json",
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
            "description": "The Language Detection function identifies the natural language of the given document based on its words and context. This classifier is able to detect 96 different languages."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9e8f787-5264-44e0-81b4-0d309e76f92d"
            }
          ]
        }
      ]
    }
  ]
}