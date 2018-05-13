{
  "info": {
    "name": "Youtube Get Languages",
    "_postman_id": "f205f636-fb59-4c0d-b57e-3452fd0df50e",
    "description": "Returns a list of application languages that the YouTube website supports.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "languages",
      "item": [
        {
          "id": "2f7fefaa-831b-4684-b6ea-b830aa4cc345",
          "name": "getI18nlanguages",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/i18nLanguages?hl=%7B%7D&part=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of application languages that the YouTube website supports"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f196d374-7151-4897-a0c4-ca35520adfca"
            }
          ]
        }
      ]
    }
  ]
}