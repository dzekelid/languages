{
  "info": {
    "name": "Google Translate API Detect Language",
    "_postman_id": "a8d3ccdc-61a3-4198-9345-2dc2b8e7af1c",
    "description": "Detect the language of text.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Translate",
      "item": [
        {
          "id": "7dca8086-013d-4064-ad0f-0f5743383a86",
          "name": "language.translations.list",
          "request": {
            "url": "http://www.googleapis.com/language/translate/v2?cid=%7B%7D&format=%7B%7D&q=%7B%7D&source=%7B%7D&target=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns text translations from one language to another."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d28aa0e3-6776-42b8-8585-87a8f24b1357"
            }
          ]
        }
      ]
    },
    {
      "name": "Language",
      "item": [
        {
          "id": "ca987c6d-8df0-42b5-8f63-5c5b0322aa9c",
          "name": "language.detections.list",
          "request": {
            "url": "http://www.googleapis.com/language/translate/v2/detect?q=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detect the language of text."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "44c7c5e7-cd46-4278-a735-b25337d39d0f"
            }
          ]
        }
      ]
    }
  ]
}