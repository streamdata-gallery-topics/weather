---
swagger: "2.0"
x-collection-name: Weather Underground
x-complete: 0
info:
  title: Weather Underground Get Key Radar Image.gif Maxlat 42.35%26maxlon 109.311%26minlat
    39.27%26minlon 114.644%26wth 600%26height 480%26newmaps 1
  description: This example will return dynamic radar image around Salt Lake City,
    UT with a Base Map background. See Docs for all the options for creating these
    images.
  version: 1.0.0
host: api.wunderground.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{key}/geolookup/q/CA/San_Francisco.json:
    get:
      summary: Get Key Geolookup Q Ca San Francisco
      description: This example will return the geographic attributes of San Francisco
        CA.    Use {2 letter state code} /    {City Name}
      operationId: Get_USA_Geolocate_example_
      x-api-path-slug: keygeolookupqcasan-francisco-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: state
        description: The state
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Geolookup
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/geolookup/q/France/Paris.json:
    get:
      summary: Get Key Geolookup Q France Paris
      description: This example will return the geographic attributes of Paris, France.
        Use {Full Country Name} / {City Name}
      operationId: Get_Outside_of_USA_Geolocate_example_
      x-api-path-slug: keygeolookupqfranceparis-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: country
        description: The country
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Geolookup
      - Q
      - France
      - Paris
      - Json
  /{key}/geolookup/q/autoip.json:
    get:
      summary: Get Key Geolookup Q Autoip
      description: This example will return the geographic attributes associated with
        the IP address location of the user.
      operationId: Get_IPAddress_example_
      x-api-path-slug: keygeolookupqautoip-json-get
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Geolookup
      - Q
      - Autoip
      - Json
  /{key}/geolookup/q/94107.json:
    get:
      summary: Get Key Geolookup Q 94107
      description: This example will return the geographic attributes of zip code
        94107
      operationId: Get_ZIP_geolocate_example_
      x-api-path-slug: keygeolookupq94107-json-get
      parameters:
      - in: path
        name: zip_code
        description: The zip code
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Geolookup
      - Q
      - "94107"
      - Json
  /{key}/geolookup/q/SFO.json:
    get:
      summary: Get Key Geolookup Q Sfo
      description: 'This example will return the geographic attributes of San Francisco
        International Airport (Airport Code: SFO)'
      operationId: Get_Airport_geolocate_example_
      x-api-path-slug: keygeolookupqsfo-json-get
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Geolookup
      - Q
      - SFO
      - Json
  /{key}/geolookup/q/37.776289,-122.395234.json:
    get:
      summary: Get Key Geolookup Q 37.776289, 122.395234
      description: This example will return the the geographic attributes of Latitude
        37.776289 N, Longitude 122.395234 W
      operationId: Get_Lat_Long_geolocate_example_
      x-api-path-slug: keygeolookupq37-776289122-395234-json-get
      parameters:
      - in: path
        name: latitude
        description: The latitude
        type: string
        format: string
      - in: path
        name: longitude
        description: The longitude
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Geolookup
      - Q
      - "37"
      - "776289"
      - "-122"
      - "395234"
      - Json
  /{key}/conditions/q/pws:KCATAHOE2.json:
    get:
      summary: Get Key Conditions Q Pws Kcatahoe2
      description: This example will return the the current weather conditions at
        the Personal Weather Station (pws) KCATAHOE2
      operationId: Get_pws_example_
      x-api-path-slug: keyconditionsqpwskcatahoe2-json-get
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Conditions
      - Q
      - Pws:KCATAHOE2
      - Json
  /{key}/conditions/q/CA/San_Francisco.json:
    get:
      summary: Get Key Conditions Q Ca San Francisco
      description: This example will return the current conditions in San Francisco,
        California
      operationId: Get_Conditions_example_
      x-api-path-slug: keyconditionsqcasan-francisco-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: state
        description: The state
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Conditions
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/astronomy/q/CA/San_Francisco.json:
    get:
      summary: Get Key Astronomy Q Ca San Francisco
      description: This example will return the Astronomy of San Francisco, California
      operationId: Get_Astronomy_example_
      x-api-path-slug: keyastronomyqcasan-francisco-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: state
        description: The state
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Astronomy
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/forecast/q/CA/San_Francisco.json:
    get:
      summary: Get Key Forecast Q Ca San Francisco
      description: This example will return the 3 Day Forecast Summary for San Francisco,
        California
      operationId: Get_forecast3_example_
      x-api-path-slug: keyforecastqcasan-francisco-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: state
        description: The state
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Forecast
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/almanac/q/{state}/San_Francisco.json:
    get:
      summary: Get Key Almanac Q Ca San Francisco
      description: This example will return Today's Average Highs/Lows and Record
        Highs/Lows for San Francisco, California.
      operationId: Get_almanac_example_
      x-api-path-slug: keyalmanacqstatesan-francisco-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: state
        description: The state
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Almanac
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/conditions/forecast/lang:FR/q/France/Paris.json:
    get:
      summary: Get Key Conditions Forecast Lang Fr Q France Paris
      description: This example will return Current Conditions and a 3 day simple
        Forecast for Paris France in French. See documentation page for full list
        of language code options.
      operationId: Get_French_example_
      x-api-path-slug: keyconditionsforecastlangfrqfranceparis-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: country
        description: The country
        type: string
        format: string
      - in: path
        name: language
        description: The language
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Conditions
      - Forecast
      - Lang:FR
      - Q
      - France
      - Paris
      - Json
  /{key}/conditions/forecast/lang:SP/q/Spain/Alicante.json:
    get:
      summary: Get Key Conditions Forecast Lang Sp Q Spain Alicante
      description: This example will return Current Conditions and a 3 day simple
        Forecast for Alicante, Spain in Spanish. See documentation page for full list
        of language code options.
      operationId: Get_Spanish_example_
      x-api-path-slug: keyconditionsforecastlangspqspainalicante-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: country
        description: The country
        type: string
        format: string
      - in: path
        name: language
        description: The language
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Conditions
      - Forecast
      - Lang:SP
      - Q
      - Spain
      - Alicante
      - Json
  /{key}/forecast10day/q/CA/San_Francisco.json:
    get:
      summary: Get Key Forecast10day Q Ca San Francisco
      description: This example will return the 10 Day Forecast Summary for San Francisco,
        California
      operationId: Get_forecast10_example_
      x-api-path-slug: keyforecast10dayqcasan-francisco-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: state
        description: The state
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Forecast10day
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/hourly/q/CA/San_Francisco.json:
    get:
      summary: Get Key Hourly Q Ca San Francisco
      description: This example will return a detailed hourly forecast for the 'next'
        36 hours in San Francisco, California
      operationId: Get_OneDay_hourly_example_
      x-api-path-slug: keyhourlyqcasan-francisco-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: state
        description: The state
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Hourly
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/satellite/q/CA/San_Francisco.json:
    get:
      summary: Get Key Satellite Q Ca San Francisco
      description: This example will return URL's for satellite (visual and IR) images
        for San Francisco, California
      operationId: Get_satellite_example_
      x-api-path-slug: keysatelliteqcasan-francisco-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: state
        description: The state
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Satellite
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/radar/image.gif?maxlat=42.35%26maxlon=-109.311%26minlat=39.27%26minlon=-114.644%26width=600%26height=480%26newmaps=0:
    get:
      summary: Get Key Radar Image.gif Maxlat 42.35%26maxlon 109.311%26minlat 39.27%26minlon
        114.644%26wth 600%26height 480%26newmaps 0
      description: This example will return dynamic radar image around Salt Lake City,
        UT with a transparent background. See Docs for all the options for creating
        these images.
      operationId: Get_radar_example_
      x-api-path-slug: keyradarimage-gifmaxlat42-3526maxlon109-31126minlat39-2726minlon114-64426width60026height48026newmaps0-get
      parameters:
      - in: query
        name: height
        description: The height
        type: string
        format: string
      - in: query
        name: maxlat
        description: Max longitude
        type: string
        format: string
      - in: query
        name: maxlon
        description: Max longitude
        type: string
        format: string
      - in: query
        name: minlat
        description: Min latitude
        type: string
        format: string
      - in: query
        name: minlon
        description: Min longitude
        type: string
        format: string
      - in: query
        name: width
        description: The width
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Radar
      - Image
      - Gif?maxlat=42
      - 35%26maxlon=-109
      - 311%26minlat=39
      - 27%26minlon=-114
      - 644%26width=600%26height=480%26newmaps=0
  /{key}/radar/image.gif?maxlat=42.35%26maxlon=-109.311%26minlat=39.27%26minlon=-114.644%26width=600%26height=480%26newmaps=1:
    get:
      summary: Get Key Radar Image.gif Maxlat 42.35%26maxlon 109.311%26minlat 39.27%26minlon
        114.644%26wth 600%26height 480%26newmaps 1
      description: This example will return dynamic radar image around Salt Lake City,
        UT with a Base Map background. See Docs for all the options for creating these
        images.
      operationId: Get_radar_example2_
      x-api-path-slug: keyradarimage-gifmaxlat42-3526maxlon109-31126minlat39-2726minlon114-64426width60026height48026newmaps1-get
      parameters:
      - in: query
        name: height
        description: The height
        type: string
        format: string
      - in: query
        name: maxlat
        description: Max longitude
        type: string
        format: string
      - in: query
        name: maxlon
        description: Max longitude
        type: string
        format: string
      - in: query
        name: minlat
        description: Min latitude
        type: string
        format: string
      - in: query
        name: minlon
        description: Min longitude
        type: string
        format: string
      - in: query
        name: width
        description: The width
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Radar
      - Image
      - Gif?maxlat=42
      - 35%26maxlon=-109
      - 311%26minlat=39
      - 27%26minlon=-114
      - 644%26width=600%26height=480%26newmaps=1
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