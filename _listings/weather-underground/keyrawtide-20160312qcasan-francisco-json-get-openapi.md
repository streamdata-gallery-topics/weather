---
swagger: "2.0"
x-collection-name: Weather Underground
x-complete: 0
info:
  title: Weather Underground Get Key Rawte 20160312 Q Ca San Francisco
  description: This example will return raw tide data for San Francisco, California
    on March 3 2016.    This request only works in the USA.
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
  /{key}/almanac/q/CA/San_Francisco.json:
    get:
      summary: Get Key Almanac Q Ca San Francisco
      description: This example will return Today's Average Highs/Lows and Record
        Highs/Lows for San Francisco, California.
      operationId: Get_almanac_example_
      x-api-path-slug: keyalmanacqcasan-francisco-json-get
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
  /{key}/alerts/q/CA/San_Francisco.json:
    get:
      summary: Get Key Alerts Q Ca San Francisco
      description: This example will return active severe alerts for San Francisco,
        California.    This request only works in the USA, Canada and Europe.
      operationId: Get_alerts_example_
      x-api-path-slug: keyalertsqcasan-francisco-json-get
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Alerts
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/tide/q/CA/San_Francisco.json:
    get:
      summary: Get Key Te Q Ca San Francisco
      description: This example will return 4 days of tides for San Francisco, California
        starting 'today'.    This request only works in the USA.
      operationId: Get_Tide_example1_
      x-api-path-slug: keytideqcasan-francisco-json-get
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Tide
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/tide_20160312/q/CA/San_Francisco.json:
    get:
      summary: Get Key Te 20160312 Q Ca San Francisco
      description: This example will return 4 days of tides for San Francisco, California
        following March 3 2012.    This request only works in the USA.
      operationId: Get_Tide_example2_
      x-api-path-slug: keytide-20160312qcasan-francisco-json-get
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Tide
      - "20160312"
      - Q
      - CA
      - San
      - Francisco
      - Json
  /{key}/rawtide_20160312/q/CA/San_Francisco.json:
    get:
      summary: Get Key Rawte 20160312 Q Ca San Francisco
      description: This example will return raw tide data for San Francisco, California
        on March 3 2016.    This request only works in the USA.
      operationId: Get_Tide_RAW_example_
      x-api-path-slug: keyrawtide-20160312qcasan-francisco-json-get
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Rawtide
      - "20160312"
      - Q
      - CA
      - San
      - Francisco
      - Json
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