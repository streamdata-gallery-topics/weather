{
  "info": {
    "name": "Weatherbit Get Current City & Country",
    "_postman_id": "03621b41-c47b-4e45-8aff-1462ec04318f",
    "description": "Returns a Current Observation - Given a city in the format of City,ST or City. The state, and country parameters can be provided to make the search more accurate.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "3e5b67c3-71c2-4d87-835d-b4fd3cdf3b31",
          "name": "returns-a-current-observation--given-a-city-in-the-format-of-cityst-or-city-the-state-and-country-pa",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "current?city=:city&country=:country"
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
                  "key": "state",
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
                  "id": "city",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "country",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a Current Observation - Given a city in the format of City,ST or City"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc9e772a-4007-4f65-b22c-feef724afb7b"
            }
          ]
        }
      ]
    }
  ]
}