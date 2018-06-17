---
swagger: "2.0"
x-collection-name: ClimaCell
x-complete: 0
info:
  title: ClimaCell Post Hourly
  description: "## Hourly Forecast Weather Data (Coming Soon)\nThe ```\u200Bhourly\u200B```
    API call provides an hourly forecast, up to 120 hours (5 days) ahead as a time
    series, for a specific location based on ClimaCell\u2019s proprietary sensing
    technology and model. The location can be specified as a geocode, or one of your
    own defined locations (see locations API calls). The weather parameters returned
    are detailed in the \u200B__Weather Data\u200B__ section."
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
      description: "## Simple Weather Data (coming soon)\nThe \u200B```simple_weather```\u200B
        API call provides an easy way to get weather trends from Now up to 16 days.
        The information received consists of weather changes that are significant
        to be mentioned. The information sent back per parameter:\n  * Precipitation
        -\n    * 0-6 hours - exact time precipitation starts and ends, including type
        and accumulation (e.g. 13:23 to 14:55, rain, 0.2 in)\n    * Hourly - hours
        of precipitation and accumulation (e.g. 11:00, rain, 0.1 in; 15:00, rain,
        0.2 in)\n    * Daily - 16 days of weather (similar to the standalone Daily
        call).\n  * Temperature -\n    * 0-6 hours - realtime temperature and then
        time when temperature changes by 1 degree (e.g. 13:20, 45F; 14:20, 46F...)\n
        \   * Hourly - temp mean\n    * Daily - Min/Max temperature\n  * More to come..."
      operationId: -simple-weather-data-coming-soonthe-simple-weather-api-call-provides-an-easy-way-to-get-weather-tren
      x-api-path-slug: simple-weather-post
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Simple
      - Weather
  /historical:
    post:
      summary: Post Historical
      description: "## Historical Weather Data\nThe ```historical``` API call provides
        a time-series of weather information for a specific location and time period.
        The location can be specified as a geocode, or one of your own defined locations
        (see ```locations``` API calls). The weather parameters returned are detailed
        in the __Weather Data__ section.\n###\nNOTES:\nFor the current release, the
        ```historical``` call provides data for non\xADprecipitation parameters only,
        all the way to 1997. In addition, you can get precipitation data up to 6 hours
        back. In the upcoming releases, the API will include precipitation data starting
        from Aug 2017 onward (ClimaCell\u2019s proprietary precipitation model) and
        precipitation classification (snow, rain, freezing rain) starting from Jan
        2018.\nThe farther back in history you go, the less comprehensive the weather
        data will be, as a result of measurements availability for that period of
        time."
      operationId: -historical-weather-datathe-historical-api-call-provides-a-timeseries-of-weather-information-for-a-s
      x-api-path-slug: historical-post
      parameters:
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Historical
  /realtime:
    post:
      summary: Post Realtime
      description: |-
        ## Current Weather Data
        The ```realtime``` API call provides weather information at the present time, down to the minute, for a specific location. The location can be specified as a geocode, or one of your own defined locations (see ```locations``` API calls). The weather parameters returned are detailed in the __Weather Data__ section.
      operationId: -current-weather-datathe-realtime-api-call-provides-weather-information-at-the-present-time-down-to-
      x-api-path-slug: realtime-post
      parameters:
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Realtime
  /nowcast:
    post:
      summary: Post Nowcast
      description: "## Nowcast (Short\u200B Term Forecast) Weather Data\nThe ```nowcast```
        API call provides forecasting time series of up to 6 hours forward, minute-\xADby-\xADminute,
        for a specific location based on ClimaCell\u2019s proprietary sensing technology
        and model. The location can be specified as a geocode, or one of your own
        defined locations (see ```locations``` API calls). The weather parameters
        returned are detailed in the __Weather Data__ section."
      operationId: -nowcast-short-term-forecast-weather-datathe-nowcast-api-call-provides-forecasting-time-series-of-up
      x-api-path-slug: nowcast-post
      parameters:
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Nowcast
  /hourly:
    post:
      summary: Post Hourly
      description: "## Hourly Forecast Weather Data (Coming Soon)\nThe ```\u200Bhourly\u200B```
        API call provides an hourly forecast, up to 120 hours (5 days) ahead as a
        time series, for a specific location based on ClimaCell\u2019s proprietary
        sensing technology and model. The location can be specified as a geocode,
        or one of your own defined locations (see locations API calls). The weather
        parameters returned are detailed in the \u200B__Weather Data\u200B__ section."
      operationId: -hourly-forecast-weather-data-coming-soonthe-hourly-api-call-provides-an-hourly-forecast-up-to-120-h
      x-api-path-slug: hourly-post
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Hourly
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