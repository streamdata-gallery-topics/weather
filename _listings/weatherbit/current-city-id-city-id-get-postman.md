{
  "info": {
    "name": "Weatherbit Get Current City",
    "_postman_id": "4c39766d-d59e-49a1-95bc-b7e56349bde9",
    "description": "Returns current weather observation - Given a City ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "b5174243-a44e-4673-acf2-ac3be323edc3",
          "name": "returns-current-weather-observation--given-a-city-id-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "current?city_id=:city_id"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "lang",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "marine",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "units",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "city_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns current weather observation - Given a City ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51f8043e-8401-44d8-9335-37c20bd13807"
            }
          ]
        }
      ]
    }
  ]
}