---
swagger: "2.0"
x-collection-name: ClimaCell
x-complete: 0
info:
  title: ClimaCell Delete Groups Group
  description: |-
    ### Delete a Group

    Removes a Group with the ```group_id``` from the system. Note that the user information will be lost.
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
  /daily:
    post:
      summary: Post Daily
      description: "### Daily (Coming Soon)\nThe ```\u200Bdaily\u200B``` API call
        provides the daily forecast with weather parameter summaries for the next
        16 \u200Bdays\u200B. The weather data includes daily minimum and maximum values
        for temperature, feels-like, dew point, pressure, humidity, and visibility,
        along with accumulated precipitation, list of precipitation types and wind
        information."
      operationId: -daily-coming-soonthe-daily-api-call-provides-the-daily-forecast-with-weather-parameter-summaries-fo
      x-api-path-slug: daily-post
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Daily
  /weather_grid:
    post:
      summary: Post Weather Gr
      description: "## Weather Grid\nThe ```\u200Bweather_grid\u200B``` API call returns
        weather information for each cell in a \u200Bdefined \u200Bgrid, for the requested
        date and time. The call defines the geo\u200Bcorners of the area and the dimensions
        of the grid (defaults to a 3x3 grid). Instead of having to calculate sample
        locations, evenly distributed, across the area, weather_grid \u200Bcalculates
        this information for you and\u200B allows you to create a rectangle and divide
        it into equally\u200B-distanced and sized cells. The weather information returned
        is identical to the above calls. Due to the \u2018square\u2019 like properties
        of the dimensions (e.g. 3 X 3), keep in mind the actual size of the rectangle
        you are asking for. In other words, a long and thin grid providing 3 x 3 cells,
        would create elongated and thin weather cells. . The aspect ratio of each
        cell is going to be the same as the grid itself. \u200BA refined, X by Y cell
        request is coming soon.\u200BThe weather parameters returned are detailed
        in the \u200B__Weather\u200B Data__ section."
      operationId: -weather-gridthe-weather-grid-api-call-returns-weather-information-for-each-cell-in-a-defined-grid-f
      x-api-path-slug: weather-grid-post
      parameters:
      - in: body
        name: box
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Weather
      - Grid
  /weather_map_layer/{ts}/{z}/{x}/{y}.png:
    get:
      summary: Get Weather Map Layer Ts Z X Y .png
      description: "## Weather Map Layer (Visual Tiles)\nThe ```weather_map``` is
        a tiled image call compatible with most modern mapping UI libraries:\n  *
        OpenLayers (see \u200Bhttps://openlayers.org/en/latest/apidoc/ol.source.XYZ.html\u200B)\n
        \ * Leaflets\n  * MapBox\n  * Google Maps\n\nThe call displays a precipitation
        heatmap on your existing geography user interface. You can overlay an actual
        precipitation layer. In the future, Climacell will support other weather parameter
        overlays.\n\nThe tile grid is composed of 256x256 pixel tiles with (x,y) coordinates,
        where (0,0) is at thenorthwest corner of the map. x increase as the map goes
        east, and y increases as it goes south.\n\n![tiile layer|150x150](/api-docs/custom/tile_layer.png)\n\nNote:
        For more information about Tiling, please visit\nhttps://wiki.openstreetmap.org/wiki/Slippy_map_tilenames"
      operationId: -weather-map-layer-visual-tilesthe-weather-map-is-a-tiled-image-call-compatible-with-most-modern-map
      x-api-path-slug: weather-map-layertszxy-png-get
      parameters:
      - in: path
        name: ts
        description: Requested timestamp for the map
      - in: path
        name: x
        description: The x coordinate for the map
      - in: path
        name: "y"
        description: The y coordinate for the map
      - in: path
        name: z
        description: The zoom level for the map
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Weather
      - Map
      - Layer
      - Ts
      - Z
      - X
      - "Y"
      - Png
  /locations:
    get:
      summary: Get Locations
      description: |-
        ### List all Locations
        Pages through the list of the Locations for your user account. You can specify the maximum number of results to be retuned, and from which result to start.
      operationId: -list-all-locationspages-through-the-list-of-the-locations-for-your-user-account-you-can-specify-the
      x-api-path-slug: locations-get
      parameters:
      - in: query
        name: limit
        description: The maximum number of records to load
      - in: query
        name: offset
        description: The number of records to skip
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
    post:
      summary: Post Locations
      description: |-
        ### Create a Location

        Creates a new Location in your organization, and name it. The name of the location is used in the notifications for triggered alerts at the location.
        ###
        The system attaches a unique ID to each location you create. This ID is used to refer to the location and manage it in the following ```locations``` API calls.
      operationId: -create-a-locationcreates-a-new-location-in-your-organization-and-name-it-the-name-of-the-location-i
      x-api-path-slug: locations-post
      parameters:
      - in: body
        name: location
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
  /locations/{location_id}:
    get:
      summary: Get Locations Location
      description: |-
        ### Retrieve a Location

        Get a single location back with its information by specifying its ```location_id```.
      operationId: -retrieve-a-locationget-a-single-location-back-with-its-information-by-specifying-its-location-id
      x-api-path-slug: locationslocation-id-get
      parameters:
      - in: path
        name: location_id
        description: UUID of the Location
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
      - Location
    put:
      summary: Put Locations Location
      description: |-
        ### Update a Location

        Updates the details of a Location designated by its ```location_id```.
      operationId: -update-a-locationupdates-the-details-of-a-location-designated-by-its-location-id
      x-api-path-slug: locationslocation-id-put
      parameters:
      - in: body
        name: location
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: UUID of the Location
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
      - Location
    delete:
      summary: Delete Locations Location
      description: |-
        ### Delete a Location

        Removes a location with the ```location_id``` from the system. If the location was part of any alert, the alert is removed.
      operationId: -delete-a-locationremoves-a-location-with-the-location-id-from-the-system-if-the-location-was-part-o
      x-api-path-slug: locationslocation-id-delete
      parameters:
      - in: path
        name: location_id
        description: UUID of the Location
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
      - Location
  /groups:
    get:
      summary: Get Groups
      description: |-
        ### List all Groups
        Page through a list of all your groups. You can specify the maximum number of results to be retuned, and from which result to start.
      operationId: -list-all-groupspage-through-a-list-of-all-your-groups-you-can-specify-the-maximum-number-of-results
      x-api-path-slug: groups-get
      parameters:
      - in: query
        name: limit
        description: The maximum number of records to load
      - in: query
        name: offset
        description: The number of records to skip
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Groups
    post:
      summary: Post Groups
      description: |-
        ### Create a Group

        Creates a new Group, and name it. The system attaches a unique ID to each group you create. This ID is used to refer to the group and manage it in the following ```groups``` API calls.
      operationId: -create-a-groupcreates-a-new-group-and-name-it-the-system-attaches-a-unique-id-to-each-group-you-cre
      x-api-path-slug: groups-post
      parameters:
      - in: body
        name: group
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Groups
  /groups/{group_id}:
    get:
      summary: Get Groups Group
      description: |-
        ### Retrieve a Group

        Get a single group with its information by specifying its ```group_id```.
      operationId: -retrieve-a-groupget-a-single-group-with-its-information-by-specifying-its-group-id
      x-api-path-slug: groupsgroup-id-get
      parameters:
      - in: path
        name: group_id
        description: UUID of the Group
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Groups
      - Group
    put:
      summary: Put Groups Group
      description: |-
        ### Update a Group

        Updates the name of a Group with a ```group_id```.
      operationId: -update-a-groupupdates-the-name-of-a-group-with-a-group-id
      x-api-path-slug: groupsgroup-id-put
      parameters:
      - in: body
        name: group
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: group_id
        description: UUID of the Group
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Groups
      - Group
    delete:
      summary: Delete Groups Group
      description: |-
        ### Delete a Group

        Removes a Group with the ```group_id``` from the system. Note that the user information will be lost.
      operationId: -delete-a-groupremoves-a-group-with-the-group-id-from-the-system-note-that-the-user-information-will
      x-api-path-slug: groupsgroup-id-delete
      parameters:
      - in: path
        name: group_id
        description: UUID of the Group
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Groups
      - Group
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