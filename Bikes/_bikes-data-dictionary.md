# Data Dictionary



## Identifier

<!-- `instant`: Record index. -->

`dteday`: Date.

## Features

`hr` *(numeric)*: Hour of the day.
- Index from `0` to `23`.

`temp_c` *(numeric)*: Temperature in Celsius.

`feels_like_c` *(numeric)*: "Feels like" temperature in Celsius.

`hum` *(numeric)*: Humidity percentage.

`windspeed` *(numeric)*: Wind speed.

`weathersit` *(categorical)*: Weather situation (severity of weather).
- `1`: Clear, Few clouds, Partly cloudy
- `2`: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
- `3`: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
- `4`: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog

`season` *(categorical)*: Season.
- `1`: Winter
- `2`: Spring
- `3`: Summer
- `4`: Fall

`holiday` *(binary)*: Is holiday?

`workingday` *(binary)*: Is working day?
- `0`: Either weekend or holiday; `1` otherwise.

## Output variable

`casual` *(numeric)*: Count of casual users.

`registered` *(numeric)*: Count of registered users.