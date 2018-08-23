---
swagger: "2.0"
x-collection-name: ClimaCell
x-complete: 0
info:
  title: ClimaCell Post Simple Weather
  description: |-
    ## Simple Weather Data (coming soon)
    The ???```simple_weather```??? API call provides an easy way to get weather trends from Now up to 16 days. The information received consists of weather changes that are significant to be mentioned. The information sent back per parameter:
      * Precipitation -
        * 0-6 hours - exact time precipitation starts and ends, including type and accumulation (e.g. 13:23 to 14:55, rain, 0.2 in)
        * Hourly - hours of precipitation and accumulation (e.g. 11:00, rain, 0.1 in; 15:00, rain, 0.2 in)
        * Daily - 16 days of weather (similar to the standalone Daily call).
      * Temperature -
        * 0-6 hours - realtime temperature and then time when temperature changes by 1 degree (e.g. 13:20, 45F; 14:20, 46F...)
        * Hourly - temp mean
        * Daily - Min/Max temperature
      * More to come...
  version: 1.0.0
host: api2.climacell.co
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /simple_weather:
    post:
      summary: Post Simple Weather
      description: |-
        ## Simple Weather Data (coming soon)
        The ???```simple_weather```??? API call provides an easy way to get weather trends from Now up to 16 days. The information received consists of weather changes that are significant to be mentioned. The information sent back per parameter:
          * Precipitation -
            * 0-6 hours - exact time precipitation starts and ends, including type and accumulation (e.g. 13:23 to 14:55, rain, 0.2 in)
            * Hourly - hours of precipitation and accumulation (e.g. 11:00, rain, 0.1 in; 15:00, rain, 0.2 in)
            * Daily - 16 days of weather (similar to the standalone Daily call).
          * Temperature -
            * 0-6 hours - realtime temperature and then time when temperature changes by 1 degree (e.g. 13:20, 45F; 14:20, 46F...)
            * Hourly - temp mean
            * Daily - Min/Max temperature
          * More to come...
      operationId: -simple-weather-data-coming-soonthe-simple-weather-api-call-provides-an-easy-way-to-get-weather-tren
      x-api-path-slug: simple-weather-post
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Simple
      - Weather
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