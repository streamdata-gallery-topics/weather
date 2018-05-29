---
name: Weatherbit
x-slug: weatherbit
description: Our mission at Weatherbit.io is pretty simple. It is to provide the highest
  quality weather forecasts, observations, and historical weather data at the best
  price. We constantly improve our platform every day. Our Weather APIs grow with
  you. Have a feature request? Let us know on our Support Forum! Our commitment to
  data quality is unparalleled. Our forecast system uses global forecast models (GFS/ECMWF),
  in combination with local short range high resolution models to derive the most
  accurate, and relevant forecast apis on the web.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Weather
created: "2018-05-28"
modified: "2018-05-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/apis.md
specificationVersion: "0.14"
apis:
- name: Weatherbit Get Bulk History Daily City Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?city={city}&country={country}
  tags: Weather,Bulk, History, Daily, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Bulk History Daily City
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a City ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?city_id={city_id}
  tags: Weather,Bulk, History, Daily, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailycity-idcity-id-get-openapi.md
- name: Weatherbit Get Bulk History Daily IP
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given IP Address, or auto.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?ip={ip}
  tags: Weather,Bulk, History, Daily, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailyipip-get-openapi.md
- name: Weatherbit Get Bulk History Daily Lat Lon
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a lat, and lon.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?lat={lat}&lon={lon}
  tags: Weather,Bulk, History, Daily, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailylatlatlonlon-get-openapi.md
- name: Weatherbit Get Bulk History Daily Postal Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?postal_code={postal_code}
  tags: Weather,Bulk, History, Daily, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Bulk History Daily Station
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a station ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?station={station}
  tags: Weather,Bulk, History, Daily, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistorydailystationstation-get-openapi.md
- name: Weatherbit Get Bulk History Hourly City & Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?city={city}&country={country}
  tags: Weather,Bulk, History, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Bulk History Hourly City
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a City ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?city_id={city_id}
  tags: Weather,Bulk, History, Hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get Bulk History Hourly IP
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given IP Address, or auto.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?ip={ip}
  tags: Weather,Bulk, History, Hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlyipip-get-openapi.md
- name: Weatherbit Get Bulk History Hourly Lat & Lon
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a lat, and lon.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?lat={lat}&lon={lon}
  tags: Weather,Bulk, History, Hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get Bulk History Hourly Postal Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?postal_code={postal_code}
  tags: Weather,Bulk, History, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Bulk History Hourly Station
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a station ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?station={station}
  tags: Weather,Bulk, History, Hourly, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkhistoryhourlystationstation-get-openapi.md
- name: Weatherbit Get Bulk File
  x-api-slug: weatherbit
  description: '**(Advanced/Advanced+/Enterprise plans only)** Downloads bulk data
    files - OPTIONS: (forecast16d.json.gz - 16 day forecasts for cities > 1000 population,
    current.json.gz - Current observations for cities > 1000 population).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/{file}
  tags: Weather,Bulk, File
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkfile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/bulkfile-get-openapi.md
- name: Weatherbit Get Current Cities
  x-api-slug: weatherbit
  description: '**(Advanced/Advanced+/Enterprise plans only)** Returns a group of
    Current Observations - Given a list of City IDs.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?city={city}
  tags: Weather,Current, Cities, Cities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentcitycity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentcitycity-get-openapi.md
- name: Weatherbit Get Current IP
  x-api-slug: weatherbit
  description: Returns a Current Observation - Given an IP address, or auto.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?ip={ip}
  tags: Weather,Current, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentipip-get-openapi.md
- name: Weatherbit Get Current Lat & Lon
  x-api-slug: weatherbit
  description: Returns a Current Observation - given a lat, and a lon.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?lat={lat}&lon={lon}
  tags: Weather,Current, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentlatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentlatlatlonlon-get-openapi.md
- name: Weatherbit Get Current Postla Code Code
  x-api-slug: weatherbit
  description: Returns current weather observation - Given a Postal Code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?postal_code={postal_code}
  tags: Weather,Current, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentpostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentpostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Current Station Station
  x-api-slug: weatherbit
  description: Returns a Current Observation - Given a station ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?station={station}
  tags: Weather,Current, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentstationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentstationstation-get-openapi.md
- name: Weatherbit Get Current Stations Stations
  x-api-slug: weatherbit
  description: '**(Advanced/Advanced+/Enterprise plans only)** Returns a group of
    Current Observations - Given a list of Station Call IDs.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?stations={stations}
  tags: Weather,Current, Stations, Stations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentstationsstations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/currentstationsstations-get-openapi.md
- name: Weatherbit Get Forecast 3hourly City & Country
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?city={city}&country={country}
  tags: Weather,Forecast, 3hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast3hourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast3hourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Forecast 3hourly City
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?city_id={city_id}
  tags: Weather,Forecast, 3hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast3hourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast3hourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get Forecast 3hourly IP
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?ip={ip}
  tags: Weather,Forecast, 3hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast3hourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast3hourlyipip-get-openapi.md
- name: Weatherbit Get Forecast 3hourly Lat & Lon
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?lat={lat}&lon={lon}
  tags: Weather,Forecast, 3hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast3hourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast3hourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get Forecast 3hourly Postla Code Code
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour
    period. Every point has a datetime string in the format "YYYY-MM-DD:HH". Time
    is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?postal_code={postal_code}
  tags: Weather,Forecast, 3hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast3hourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecast3hourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Forecast Daily City & Country
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.
    Accepts a city in the format of City,ST or City. The state, and country parameters
    can be provided to make the search more accurate.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?city={city}&country={country}
  tags: Weather,Forecast, Daily, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecastdailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecastdailycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Forecast Daily City
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?city_id={city_id}
  tags: Weather,Forecast, Daily, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecastdailycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecastdailycity-idcity-id-get-openapi.md
- name: Weatherbit Get Forecast Daily IP
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?ip={ip}
  tags: Weather,Forecast, Daily, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecastdailyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecastdailyipip-get-openapi.md
- name: Weatherbit Get Forecast Daily Lat & Lon
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?lat={lat}&lon={lon}
  tags: Weather,Forecast, Daily, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecastdailylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecastdailylatlatlonlon-get-openapi.md
- name: Weatherbit Get Forecast Daily Postla Code Code
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?postal_code={postal_code}
  tags: Weather,Forecast, Daily, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecastdailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecastdailypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Forecast Hourly City & Country
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC. Accepts a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?city={city}&country={country}
  tags: Weather,Forecast, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecasthourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecasthourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Forecast Hourly City
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?city_id={city_id}
  tags: Weather,Forecast, Hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecasthourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecasthourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get Forecast Hourly IP
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?ip={ip}
  tags: Weather,Forecast, Hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecasthourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecasthourlyipip-get-openapi.md
- name: Weatherbit Get Forecast Hourly Lat & Lon
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?lat={lat}&lon={lon}
  tags: Weather,Forecast, Hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecasthourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecasthourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get Forecast Hourly Postla Code Code
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?postal_code={postal_code}
  tags: Weather,Forecast, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecasthourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/forecasthourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get History Daily City & Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer.
    LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?city={city}&country={country}
  tags: Weather,History, Daily, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get History Daily City
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a City ID. **(LIMIT 1 day for
    Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?city_id={city_id}
  tags: Weather,History, Daily, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailycity-idcity-id-get-openapi.md
- name: Weatherbit Get History Daily IP
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given IP Address, or auto. **(LIMIT
    1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?ip={ip}
  tags: Weather,History, Daily, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailyipip-get-openapi.md
- name: Weatherbit Get History Daily Lat & Lon
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a lat, and lon. **(LIMIT 1
    day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?lat={lat}&lon={lon}
  tags: Weather,History, Daily, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailylatlatlonlon-get-openapi.md
- name: Weatherbit Get History Daily Postla Code Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?postal_code={postal_code}
  tags: Weather,History, Daily, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get History Daily Station Station
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a station ID. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?station={station}
  tags: Weather,History, Daily, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historydailystationstation-get-openapi.md
- name: Weatherbit Get History Energy Bbox Lat1 Lat1 &lon1 Lon1 &lat2 Lat2 &lon2 Lon2
  x-api-slug: weatherbit
  description: 'Returns aggregate energy specific historical weather fields, over
    a specified time period. Supply a bounding box ex: lat1=40&lon1=-78&lat2=38&lon2=-80.
    This API will return UP TO 150 stations, aggregated by the specified time period
    start_date to end_date.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/energy/bbox?lat1={lat1}&lon1={lon1}&lat2={lat2}&lon2={lon2}
  tags: Weather,History, Energy, Bbox, Lat1, Lat1, &lon1, Lon1, &lat2, Lat2, &lon2,
    Lon2
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyenergybboxlat1lat1lon1lon1lat2lat2lon2lon2-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyenergybboxlat1lat1lon1lon1lat2lat2lon2lon2-get-openapi.md
- name: Weatherbit Get History Energy Lat & Lon
  x-api-slug: weatherbit
  description: Returns aggregate energy specific historical weather fields, over a
    specified time period.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/energy?lat={lat}&lon={lon}
  tags: Weather,History, Energy, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyenergylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyenergylatlatlonlon-get-openapi.md
- name: Weatherbit Get History Hourly City & Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer.
    LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?city={city}&country={country}
  tags: Weather,History, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get History Hourly City
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a City ID. **(LIMIT 1 day for
    Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?city_id={city_id}
  tags: Weather,History, Hourly, City, , City
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlycity-idcity-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlycity-idcity-id-get-openapi.md
- name: Weatherbit Get History Hourly IP
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given IP Address, or auto. **(LIMIT
    1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?ip={ip}
  tags: Weather,History, Hourly, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlyipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlyipip-get-openapi.md
- name: Weatherbit Get History Hourly Lat & Lon
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a lat, and lon. **(LIMIT 1
    day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for
    Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?lat={lat}&lon={lon}
  tags: Weather,History, Hourly, Lat, Lat, &lon, Lon
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlylatlatlonlon-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlylatlatlonlon-get-openapi.md
- name: Weatherbit Get History Hourly Postal Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?postal_code={postal_code}
  tags: Weather,History, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get History Hourly Station Station
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a station ID. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?station={station}
  tags: Weather,History, Hourly, Station, Station
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlystationstation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/historyhourlystationstation-get-openapi.md
- name: Weatherbit Get IP
  x-api-slug: weatherbit
  description: Returns a geolocation object. Given an IP address. If no IP supplied,
    will use request IP address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//ip?ip={ip}
  tags: Weather,Ip, Ip, Ip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/ipipip-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/ipipip-get-openapi.md
- name: Weatherbit
  x-api-slug: weatherbit
  description: Our mission at Weatherbit.io is pretty simple. It is to provide the
    highest quality weather forecasts, observations, and historical weather data at
    the best price. We constantly improve our platform every day. Our Weather APIs
    grow with you. Have a feature request? Let us know on our Support Forum! Our commitment
    to data quality is unparalleled. Our forecast system uses global forecast models
    (GFS/ECMWF), in combination with local short range high resolution models to derive
    the most accurate, and relevant forecast apis on the web.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Weather
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/weather/master/_listings/weatherbit/openapi.md
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
  url: http://weatherbit.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---