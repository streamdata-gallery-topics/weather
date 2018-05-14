---
name: Weatherbit
description: Our mission at Weatherbit.io is pretty simple. It is to provide the highest
  quality weather forecasts, observations, and historical weather data at the best
  price. We constantly improve our platform every day. Our Weather APIs grow with
  you. Have a feature request? Let us know on our Support Forum! Our commitment to
  data quality is unparalleled. Our forecast system uses global forecast models (GFS/ECMWF),
  in combination with local short range high resolution models to derive the most
  accurate, and relevant forecast apis on the web.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
x-kinRank: "8"
x-alexaRank: ""
tags:
- Weather
created: "2018-03-24"
modified: "2018-03-24"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/apis.yaml
specificationVersion: "0.14"
apis:
- name: Weatherbit
  description: Our mission at Weatherbit
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: ""
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/ip-ip-ip-get.md
- name: Weatherbit Get Forecast Hourly City
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: https://www.weatherbit.io/api
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast-hourly-city-id-city-id-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast-hourly-city-id-city-id-get-postman.md
- name: Weatherbit Get History Daily City & Country
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer.
    LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: https://www.weatherbit.io/api
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/history-daily-city-city-country-country-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/history-daily-city-city-country-country-get-postman.md
x-common:
- type: x-blog
  url: https://www.weatherbit.io/blog
- type: x-contact-form
  url: https://www.weatherbit.io/contact
- type: x-documentation
  url: https://www.weatherbit.io/api
- type: x-github
  url: https://github.com/weatherbit
- type: x-pricing
  url: https://www.weatherbit.io/pricing
- type: x-twitter
  url: https://twitter.com/weatherbitio
- type: x-website
  url: https://www.weatherbit.io/api
- type: x-blog
  url: https://www.weatherbit.io/blog
- type: x-contact-form
  url: https://www.weatherbit.io/contact
- type: x-documentation
  url: https://www.weatherbit.io/api
- type: x-github
  url: https://github.com/weatherbit
- type: x-pricing
  url: https://www.weatherbit.io/pricing
- type: x-twitter
  url: https://twitter.com/weatherbitio
- type: x-website
  url: https://www.weatherbit.io/api
- type: x-blog
  url: https://www.weatherbit.io/blog
- type: x-contact-form
  url: https://www.weatherbit.io/contact
- type: x-documentation
  url: https://www.weatherbit.io/api
- type: x-github
  url: https://github.com/weatherbit
- type: x-pricing
  url: https://www.weatherbit.io/pricing
- type: x-twitter
  url: https://twitter.com/weatherbitio
- type: x-website
  url: https://www.weatherbit.io/api
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---