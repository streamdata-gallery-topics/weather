---
swagger: "2.0"
x-collection-name: Weather Underground
x-complete: 0
info:
  title: Weather Underground Get Key Astronomy Q Ca San Francisco
  description: This example will return the Astronomy of San Francisco, California
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