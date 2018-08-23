---
swagger: "2.0"
x-collection-name: Weather Underground
x-complete: 0
info:
  title: Weather Underground Get Key Geolookup Q 94107
  description: This example will return the geographic attributes of zip code 94107
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