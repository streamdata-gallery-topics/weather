---
name: ClimaCell
x-slug: climacell
description: ClimaCell provides the most accurate weather data in the world by integrating
  proprietary data extracted from wireless networks and other new sensing technologies
  with data from traditional sensors. With 90% correlation to ground truth (vs. 50%
  using radar), it&rsquo;s the best you can get for your enterprise.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
x-kinRank: "9"
x-alexaRank: "617213"
tags: Weather
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/apis.md
specificationVersion: "0.14"
apis:
- name: ClimaCell Post Simple Weather
  x-api-slug: climacell
  description: "## Simple Weather Data (coming soon)\nThe \u200B```simple_weather```\u200B
    API call provides an easy way to get weather trends from Now up to 16 days. The
    information received consists of weather changes that are significant to be mentioned.
    The information sent back per parameter:\n  * Precipitation -\n    * 0-6 hours
    - exact time precipitation starts and ends, including type and accumulation (e.g.
    13:23 to 14:55, rain, 0.2 in)\n    * Hourly - hours of precipitation and accumulation
    (e.g. 11:00, rain, 0.1 in; 15:00, rain, 0.2 in)\n    * Daily - 16 days of weather
    (similar to the standalone Daily call).\n  * Temperature -\n    * 0-6 hours -
    realtime temperature and then time when temperature changes by 1 degree (e.g.
    13:20, 45F; 14:20, 46F...)\n    * Hourly - temp mean\n    * Daily - Min/Max temperature\n
    \ * More to come..."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//simple_weather
  tags: Weather,Simple,Weather
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/simple-weather-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/simple-weather-post-openapi.md
- name: ClimaCell Post Historical
  x-api-slug: climacell
  description: "## Historical Weather Data\nThe ```historical``` API call provides
    a time-series of weather information for a specific location and time period.
    The location can be specified as a geocode, or one of your own defined locations
    (see ```locations``` API calls). The weather parameters returned are detailed
    in the __Weather Data__ section.\n###\nNOTES:\nFor the current release, the ```historical```
    call provides data for non\xADprecipitation parameters only, all the way to 1997.
    In addition, you can get precipitation data up to 6 hours back. In the upcoming
    releases, the API will include precipitation data starting from Aug 2017 onward
    (ClimaCell\u2019s proprietary precipitation model) and precipitation classification
    (snow, rain, freezing rain) starting from Jan 2018.\nThe farther back in history
    you go, the less comprehensive the weather data will be, as a result of measurements
    availability for that period of time."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//historical
  tags: Weather,Historical
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/historical-post-openapi.md
- name: ClimaCell Post Realtime
  x-api-slug: climacell
  description: |-
    ## Current Weather Data
    The ```realtime``` API call provides weather information at the present time, down to the minute, for a specific location. The location can be specified as a geocode, or one of your own defined locations (see ```locations``` API calls). The weather parameters returned are detailed in the __Weather Data__ section.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//realtime
  tags: Weather,Realtime
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/realtime-post-openapi.md
- name: ClimaCell Post Nowcast
  x-api-slug: climacell
  description: "## Nowcast (Short\u200B Term Forecast) Weather Data\nThe ```nowcast```
    API call provides forecasting time series of up to 6 hours forward, minute-\xADby-\xADminute,
    for a specific location based on ClimaCell\u2019s proprietary sensing technology
    and model. The location can be specified as a geocode, or one of your own defined
    locations (see ```locations``` API calls). The weather parameters returned are
    detailed in the __Weather Data__ section."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//nowcast
  tags: Weather,Nowcast
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/nowcast-post-openapi.md
- name: ClimaCell Post Hourly
  x-api-slug: climacell
  description: "## Hourly Forecast Weather Data (Coming Soon)\nThe ```\u200Bhourly\u200B```
    API call provides an hourly forecast, up to 120 hours (5 days) ahead as a time
    series, for a specific location based on ClimaCell\u2019s proprietary sensing
    technology and model. The location can be specified as a geocode, or one of your
    own defined locations (see locations API calls). The weather parameters returned
    are detailed in the \u200B__Weather Data\u200B__ section."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//hourly
  tags: Weather,Hourly
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/hourly-post-openapi.md
- name: ClimaCell Post Daily
  x-api-slug: climacell
  description: "### Daily (Coming Soon)\nThe ```\u200Bdaily\u200B``` API call provides
    the daily forecast with weather parameter summaries for the next 16 \u200Bdays\u200B.
    The weather data includes daily minimum and maximum values for temperature, feels-like,
    dew point, pressure, humidity, and visibility, along with accumulated precipitation,
    list of precipitation types and wind information."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//daily
  tags: Weather,Daily
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/daily-post-openapi.md
- name: ClimaCell Post Weather Gr
  x-api-slug: climacell
  description: "## Weather Grid\nThe ```\u200Bweather_grid\u200B``` API call returns
    weather information for each cell in a \u200Bdefined \u200Bgrid, for the requested
    date and time. The call defines the geo\u200Bcorners of the area and the dimensions
    of the grid (defaults to a 3x3 grid). Instead of having to calculate sample locations,
    evenly distributed, across the area, weather_grid \u200Bcalculates this information
    for you and\u200B allows you to create a rectangle and divide it into equally\u200B-distanced
    and sized cells. The weather information returned is identical to the above calls.
    Due to the \u2018square\u2019 like properties of the dimensions (e.g. 3 X 3),
    keep in mind the actual size of the rectangle you are asking for. In other words,
    a long and thin grid providing 3 x 3 cells, would create elongated and thin weather
    cells. . The aspect ratio of each cell is going to be the same as the grid itself.
    \u200BA refined, X by Y cell request is coming soon.\u200BThe weather parameters
    returned are detailed in the \u200B__Weather\u200B Data__ section."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//weather_grid
  tags: Weather,Weather,Grid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/weather-grid-post-openapi.md
- name: ClimaCell Get Weather Map Layer Ts Z X Y .png
  x-api-slug: climacell
  description: "## Weather Map Layer (Visual Tiles)\nThe ```weather_map``` is a tiled
    image call compatible with most modern mapping UI libraries:\n  * OpenLayers (see
    \u200Bhttps://openlayers.org/en/latest/apidoc/ol.source.XYZ.html\u200B)\n  * Leaflets\n
    \ * MapBox\n  * Google Maps\n\nThe call displays a precipitation heatmap on your
    existing geography user interface. You can overlay an actual precipitation layer.
    In the future, Climacell will support other weather parameter overlays.\n\nThe
    tile grid is composed of 256x256 pixel tiles with (x,y) coordinates, where (0,0)
    is at thenorthwest corner of the map. x increase as the map goes east, and y increases
    as it goes south.\n\n![tiile layer|150x150](/api-docs/custom/tile_layer.png)\n\nNote:
    For more information about Tiling, please visit\nhttps://wiki.openstreetmap.org/wiki/Slippy_map_tilenames"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//weather_map_layer/{ts}/{z}/{x}/{y}.png
  tags: Weather,Weather,Map,Layer,Ts,Z,X,Y,Png
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/weather-map-layertszxy-png-get-openapi.md
- name: ClimaCell Get Locations
  x-api-slug: climacell
  description: |-
    ### List all Locations
    Pages through the list of the Locations for your user account. You can specify the maximum number of results to be retuned, and from which result to start.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//locations
  tags: Weather,Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/locations-get-openapi.md
- name: ClimaCell Post Locations
  x-api-slug: climacell
  description: |-
    ### Create a Location

    Creates a new Location in your organization, and name it. The name of the location is used in the notifications for triggered alerts at the location.
    ###
    The system attaches a unique ID to each location you create. This ID is used to refer to the location and manage it in the following ```locations``` API calls.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//locations
  tags: Weather,Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/locations-post-openapi.md
- name: ClimaCell Get Locations Location
  x-api-slug: climacell
  description: |-
    ### Retrieve a Location

    Get a single location back with its information by specifying its ```location_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//locations/{location_id}
  tags: Weather,Locations,Location
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/locationslocation-id-get-openapi.md
- name: ClimaCell Put Locations Location
  x-api-slug: climacell
  description: |-
    ### Update a Location

    Updates the details of a Location designated by its ```location_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//locations/{location_id}
  tags: Weather,Locations,Location
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/locationslocation-id-put-openapi.md
- name: ClimaCell Delete Locations Location
  x-api-slug: climacell
  description: |-
    ### Delete a Location

    Removes a location with the ```location_id``` from the system. If the location was part of any alert, the alert is removed.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//locations/{location_id}
  tags: Weather,Locations,Location
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/locationslocation-id-delete-openapi.md
- name: ClimaCell Get Groups
  x-api-slug: climacell
  description: |-
    ### List all Groups
    Page through a list of all your groups. You can specify the maximum number of results to be retuned, and from which result to start.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//groups
  tags: Weather,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/groups-get-openapi.md
- name: ClimaCell Post Groups
  x-api-slug: climacell
  description: |-
    ### Create a Group

    Creates a new Group, and name it. The system attaches a unique ID to each group you create. This ID is used to refer to the group and manage it in the following ```groups``` API calls.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//groups
  tags: Weather,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/groups-post-openapi.md
- name: ClimaCell Get Groups Group
  x-api-slug: climacell
  description: |-
    ### Retrieve a Group

    Get a single group with its information by specifying its ```group_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//groups/{group_id}
  tags: Weather,Groups,Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/groupsgroup-id-get-openapi.md
- name: ClimaCell Put Groups Group
  x-api-slug: climacell
  description: |-
    ### Update a Group

    Updates the name of a Group with a ```group_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//groups/{group_id}
  tags: Weather,Groups,Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/groupsgroup-id-put-openapi.md
- name: ClimaCell Delete Groups Group
  x-api-slug: climacell
  description: |-
    ### Delete a Group

    Removes a Group with the ```group_id``` from the system. Note that the user information will be lost.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//groups/{group_id}
  tags: Weather,Groups,Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/groupsgroup-id-delete-openapi.md
- name: ClimaCell Get Groups Group Members
  x-api-slug: climacell
  description: |-
    ### List all Group Members
    Page through a list of all members of a group with a ```group_id```. You can specify the maximum number of results to be retuned, and from which result to start.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//groups/{group_id}/members
  tags: Weather,Groups,Group,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/groupsgroup-idmembers-get-openapi.md
- name: ClimaCell Post Groups Group Members
  x-api-slug: climacell
  description: "### Create a Group Member\n\nAdds a member to a group with a ```group_id```.
    \u200BMake sure you provide an accurate email address and/or phone number or alerts
    will not be received by the member."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//groups/{group_id}/members
  tags: Weather,Groups,Group,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/groupsgroup-idmembers-post-openapi.md
- name: ClimaCell Put Groups Group Members Member
  x-api-slug: climacell
  description: |-
    ### Delete a Group Member
    Updates a member with the ```member_id``` to the group with a ```group_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//groups/{group_id}/members/{member_id}
  tags: Weather,Groups,Group,Members,Member
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/groupsgroup-idmembersmember-id-put-openapi.md
- name: ClimaCell Delete Groups Group Members Member
  x-api-slug: climacell
  description: |-
    ### Delete a Group Member
    Removes a member with the ```member_id``` from the group with a ```group_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//groups/{group_id}/members/{member_id}
  tags: Weather,Groups,Group,Members,Member
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/groupsgroup-idmembersmember-id-delete-openapi.md
- name: ClimaCell Get Webhooks
  x-api-slug: climacell
  description: |-
    ### List all Webhooks
    Page through a list of all your Webhooks. You can specify the maximum number of results to be retuned, and from which result to start.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//webhooks
  tags: Weather,Webhooks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/webhooks-get-openapi.md
- name: ClimaCell Post Webhooks
  x-api-slug: climacell
  description: "### Create a Webhook\n\nCreates a new Webhook, and name it. The system
    attaches a unique ID to each webhook you create. This ID is used to refer to the
    webhook and manage it in the following \u200B```webhooks```\u200B API calls."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//webhooks
  tags: Weather,Webhooks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/webhooks-post-openapi.md
- name: ClimaCell Get Webhooks Webhook
  x-api-slug: climacell
  description: |-
    ### Retrieve a Webhook

    Get a single Webhook with its information by specifying its ```webhook_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//webhooks/{webhook_id}
  tags: Weather,Webhooks,Webhook
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/webhookswebhook-id-get-openapi.md
- name: ClimaCell Put Webhooks Webhook
  x-api-slug: climacell
  description: "### Update a Webhook\n\nUpdates the name of a Webhook with a\u200B
    ```webhook_id```."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//webhooks/{webhook_id}
  tags: Weather,Webhooks,Webhook
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/webhookswebhook-id-put-openapi.md
- name: ClimaCell Delete Webhooks Webhook
  x-api-slug: climacell
  description: |-
    ### Delete a Webhook

    Removes a Webhook with its information by specifying its ```webhook_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//webhooks/{webhook_id}
  tags: Weather,Webhooks,Webhook
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/webhookswebhook-id-delete-openapi.md
- name: ClimaCell Get Alerts
  x-api-slug: climacell
  description: |-
    ### List all Alerts

    Page through a list of all your alerts. You can specify the maximum number of results to be retuned, and from which result to start.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//alerts
  tags: Weather,Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/alerts-get-openapi.md
- name: ClimaCell Post Alerts
  x-api-slug: climacell
  description: "### Create an Alert\nCreates a new Alert with the following information:\n\n*
    ```name``` - Alert Name\n* ```location_name``` - Location name for which the alert
    pertains (location has to be created earlier)\n* ```notice``` - Prior notice in
    seconds\n* ```conditions``` - logical expression defining a weather event such
    as: rain with intensity of more than 1 mm/hr. Several expressions can be concatenated
    with \u201Cor\u201D logical operator. An alert will trigger for it if any of its
    contained conditions are met. ORs can contain any number of conditions.\n\nNOTE:\u200B
    AND condition \u200B coming soon\n\n### In addition to the format below, this
    is an example with an \"OR\" conditional statement:\n  ```\n  {\n    \"name\":
    \"alert with or\",\n    \"location_name\": \"your-location-name\",\n    \"notice\":
    3600,\n    \"conditions\": [\n      {\n        \"or\": [\n          {\n            \"parameter\":
    \"Rain\",\n            \"value\": 0.15,\n            \"operator\": \"lt\"\n          },\n
    \         {\n            \"parameter\": \"Temperature\",\n            \"value\":
    25,\n            \"operator\": \"lt\"\n          }\n        ]\n      }\n    ],\n
    \   \"groups\": [\n      {\n        \"name\": \"your-group-name\",\n        \"delivery\":
    {\n          \"sms\": true,\n          \"email\": false\n        }\n      }\n
    \   ],\n    \"webhooks\": [507f1f77bcf86cd799439011]\n  }\n  ```\n### In addition
    to the format below, this is an example with an \"AND\" conditional statement:\n\n
    \ ```\n  {\n    \"name\": \"alert with AND conditions\",\n    \"location_name\":
    \"your-location-name\",\n    \"notice\": 3600,\n    \"conditions\": [\n      {\n
    \       \"parameter\": \"Rain\",\n        \"value\": 0.15,\n        \"operator\":
    \"gt\"\n      },\n      {\n        \"parameter\": \"Temperature\",\n        \"value\":
    40,\n        \"operator\": \"lt\"\n      }\n    ],\n    \"groups\": [\n      {\n
    \       \"name\": \"your-group-name\",\n        \"delivery\": {\n          \"sms\":
    true,\n          \"email\": false\n        }\n      }\n    ],\n    \"webhooks\":
    [507f1f77bcf86cd799439011]\n  }\n  ```"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//alerts
  tags: Weather,Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/alerts-post-openapi.md
- name: ClimaCell Get Alerts Alert
  x-api-slug: climacell
  description: |-
    ### Retrieve an Alert

    Get a single alert with its information by specifying its ```alert_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//alerts/{alert_id}
  tags: Weather,Alerts,Alert
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/alertsalert-id-get-openapi.md
- name: ClimaCell Put Alerts Alert
  x-api-slug: climacell
  description: |-
    ### Update an Alert

    Updates the details of an Alert designated by its ```alert_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//alerts/{alert_id}
  tags: Weather,Alerts,Alert
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/alertsalert-id-put-openapi.md
- name: ClimaCell Delete Alerts Alert
  x-api-slug: climacell
  description: |-
    ### Delete an Alert

    Removes an alert with the ```alert_id``` from the system.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//alerts/{alert_id}
  tags: Weather,Alerts,Alert
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/alertsalert-id-delete-openapi.md
- name: ClimaCell
  x-api-slug: climacell
  description: ClimaCell provides the most accurate weather data in the world by integrating
    proprietary data extracted from wireless networks and other new sensing technologies
    with data from traditional sensors. With 90% correlation to ground truth (vs.
    50% using radar), it&rsquo;s the best you can get for your enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2
  tags: Weather
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/climacell/openapi.md
x-common:
- type: x-blog
  url: https://www.climacell.co/blog/
- type: x-crunchbase
  url: https://crunchbase.com/organization/climacell
- type: x-developer
  url: https://www.climacell.co/api/
- type: x-email
  url: info@climacell.co
- type: x-email
  url: support@climacell.co
- type: x-email
  url: sales@climacell.co
- type: x-faq
  url: https://developer.climacell.co/FAQ
- type: x-github
  url: https://github.com/climacell
- type: x-pricing
  url: https://developer.climacell.co/
- type: x-privacy-policy
  url: https://www.climacell.co/privacy/
- type: x-terms-of-service
  url: https://www.climacell.co/terms-of-service/
- type: x-twitter
  url: https://twitter.com/WeatherRevealed
- type: x-website
  url: https://www.climacell.co
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---