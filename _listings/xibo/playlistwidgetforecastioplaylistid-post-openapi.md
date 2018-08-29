---
swagger: "2.0"
x-collection-name: Xibo
x-complete: 0
info:
  title: Xibo API Add a Weather Widget
  description: Add a new Weather Widget to the specified playlist
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /playlist/widget/forecastIo/{playlistId}:
    post:
      summary: Add a Weather Widget
      description: Add a new Weather Widget to the specified playlist
      operationId: WidgetWeatherAdd
      x-api-path-slug: playlistwidgetforecastioplaylistid-post
      parameters:
      - in: formData
        name: currentTemplate
        description: Current template, Pass only with overrideTemplate set to 1
      - in: formData
        name: dailyTemplate
        description: Replaces [dailyForecast] in main template, Pass only with overrideTemplate
          set to 1
      - in: formData
        name: dayConditionsOnly
        description: Flag (0, 1) Would you like to only show the Daytime weather conditions
      - in: formData
        name: duration
        description: Widget Duration
      - in: formData
        name: lang
        description: Language youd like to use, supported languages ar, az, be, bs,
          cs, de, en, el, es, fr, hr, hu, id, it, is, kw, nb, nl, pl, pt, ru, sk,
          sr, sv, tet, tr, uk, x-pig-latin, zh, zh-tw
      - in: formData
        name: latitude
        description: The latitude for this weather widget, only pass if useDisplayLocation
          set to 0
      - in: formData
        name: longitude
        description: The longitude for this weather widget, only pass if useDisplayLocation
          set to 0
      - in: formData
        name: name
        description: Optional Widget Name
      - in: formData
        name: overrideTemplate
        description: flag (0, 1) set to 0 and use templateId or set to 1 and provide
          whole template in the next parameters
      - in: path
        name: playlistId
        description: The playlist ID to add a Weather widget
      - in: formData
        name: styleSheet
        description: Optional StyleSheet, Pass only with overrideTemplate set to 1
      - in: formData
        name: templateId
        description: 'Use pre-configured templates, available options: weather-module0-5day,
          weather-module0-singleday, weather-module0-singleday2, weather-module1l,
          weather-module1p, weather-module2l, weather-module2p, weather-module3l,
          weather-module3p, weather-module4l, weather-module4p, weather-module5l,
          weather-module6v, weather-module6h'
      - in: formData
        name: units
        description: 'Units you would like to use, available options: auto, ca, si,
          uk2, us'
      - in: formData
        name: updateInterval
        description: Update interval in minutes, should be kept as high as possible,
          if data change once per hour, this should be set to 60
      - in: formData
        name: useDisplayLocation
        description: Flag (0, 1) Use the location configured on display
      - in: formData
        name: useDuration
        description: (0, 1) Select 1 only if you will provide duration parameter as
          well
      - in: formData
        name: widgetOriginalHeight
        description: This is the intended Height of the template and is used to scale
          the Widget within its region when the template is applied, Pass only with
          overrideTemplate set to 1
      - in: formData
        name: widgetOriginalWidth
        description: This is the intended Width of the template and is used to scale
          the Widget within its region when the template is applied, Pass only with
          overrideTemplate set to 1
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Widget
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