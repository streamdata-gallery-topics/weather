{
  "info": {
    "name": "ClimaCell Post Simple Weather",
    "_postman_id": "7a3becfc-740d-4224-8b22-79c96f245f37",
    "description": "## Simple Weather Data (coming soon)\nThe ???```simple_weather```??? API call provides an easy way to get weather trends from Now up to 16 days. The information received consists of weather changes that are significant to be mentioned. The information sent back per parameter:\n  * Precipitation -\n    * 0-6 hours - exact time precipitation starts and ends, including type and accumulation (e.g. 13:23 to 14:55, rain, 0.2 in)\n    * Hourly - hours of precipitation and accumulation (e.g. 11:00, rain, 0.1 in; 15:00, rain, 0.2 in)\n    * Daily - 16 days of weather (similar to the standalone Daily call).\n  * Temperature -\n    * 0-6 hours - realtime temperature and then time when temperature changes by 1 degree (e.g. 13:20, 45F; 14:20, 46F...)\n    * Hourly - temp mean\n    * Daily - Min/Max temperature\n  * More to come...",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Weather",
      "item": [
        {
          "id": "1bdd7355-2e1b-4eea-bc1a-36defd0261e3",
          "name": "-simple-weather-data-coming-soonthe-simple-weather-api-call-provides-an-easy-way-to-get-weather-tren",
          "request": {
            "url": "http://api2.climacell.co/v2/simple_weather",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "## Simple Weather Data (coming soon)\nThe ???```simple_weather```??? API call provides an easy way to get weather trends from Now up to 16 days. The information received consists of weather changes that are significant to be mentioned. The information sent back per parameter:\n  * Precipitation -\n    * 0-6 hours - exact time precipitation starts and ends, including type and accumulation (e.g. 13:23 to 14:55, rain, 0.2 in)\n    * Hourly - hours of precipitation and accumulation (e.g. 11:00, rain, 0.1 in; 15:00, rain, 0.2 in)\n    * Daily - 16 days of weather (similar to the standalone Daily call).\n  * Temperature -\n    * 0-6 hours - realtime temperature and then time when temperature changes by 1 degree (e.g. 13:20, 45F; 14:20, 46F...)\n    * Hourly - temp mean\n    * Daily - Min/Max temperature\n  * More to come..."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efa97ec3-1640-4bf8-88e4-875a36ab7536"
            }
          ]
        }
      ]
    }
  ]
}