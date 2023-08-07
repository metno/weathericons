
# Weather icons

This is a redesigned set of icons, meant to be used in conjunction
with version 2.0 of Locationforecast, Nowcast and Oceanforecast.
They are available in PNG, SVG and PDF formats. The images are the
same as used on [Yr](https://yr.no/), but the filenames are different
to correspond with the symbol codes in Locationforecast

The icon files are meant to be downloaded and bundled with your application.
There is no need for an API to fetch individual icons on demand.

**Note:** There is a typing error in `lightssleetshowersandthunder` and
`lightssnowshowersandthunder` (an extra "s" after "light"). Unfortunately,
correcting this would mean breaking existing applications, so it has been
postponed to the next version of locationforecast/nowcast.

## Variants

Some symbols come in three different variants, for day, night and [polar
twilight](https://en.wikipedia.org/wiki/Polar_night#Polar_twilight)
respectively. Others (the ones without sun or moon) are constant during the
day. Locationforecast/2.0 will specify the correct variant to use for each
hour.

|Code|Old id|Description|Icons|
|----|------|-----------|-----|
|clearsky|1|Clear sky|<img src='svg/clearsky_day.svg' width='36'/><img src='svg/clearsky_night.svg' width='36'/><img src='svg/clearsky_polartwilight.svg' width='36'/>|
|cloudy|4|Cloudy|<img src='svg/cloudy.svg' width='36'/>|
|fair|2|Fair|<img src='svg/fair_day.svg' width='36'/><img src='svg/fair_night.svg' width='36'/><img src='svg/fair_polartwilight.svg' width='36'/>|
|fog|15|Fog|<img src='svg/fog.svg' width='36'/>|
|heavyrain|10|Heavy rain|<img src='svg/heavyrain.svg' width='36'/>|
|heavyrainandthunder|11|Heavy rain and thunder|<img src='svg/heavyrainandthunder.svg' width='36'/>|
|heavyrainshowers|41|Heavy rain showers|<img src='svg/heavyrainshowers_day.svg' width='36'/><img src='svg/heavyrainshowers_night.svg' width='36'/><img src='svg/heavyrainshowers_polartwilight.svg' width='36'/>|
|heavyrainshowersandthunder|25|Heavy rain showers and thunder|<img src='svg/heavyrainshowersandthunder_day.svg' width='36'/><img src='svg/heavyrainshowersandthunder_night.svg' width='36'/><img src='svg/heavyrainshowersandthunder_polartwilight.svg' width='36'/>|
|heavysleet|48|Heavy sleet|<img src='svg/heavysleet.svg' width='36'/>|
|heavysleetandthunder|32|Heavy sleet and thunder|<img src='svg/heavysleetandthunder.svg' width='36'/>|
|heavysleetshowers|43|Heavy sleet showers|<img src='svg/heavysleetshowers_day.svg' width='36'/><img src='svg/heavysleetshowers_night.svg' width='36'/><img src='svg/heavysleetshowers_polartwilight.svg' width='36'/>|
|heavysleetshowersandthunder|27|Heavy sleet showers and thunder|<img src='svg/heavysleetshowersandthunder_day.svg' width='36'/><img src='svg/heavysleetshowersandthunder_night.svg' width='36'/><img src='svg/heavysleetshowersandthunder_polartwilight.svg' width='36'/>|
|heavysnow|50|Heavy snow|<img src='svg/heavysnow.svg' width='36'/>|
|heavysnowandthunder|34|Heavy snow and thunder|<img src='svg/heavysnowandthunder.svg' width='36'/>|
|heavysnowshowers|45|Heavy snow showers|<img src='svg/heavysnowshowers_day.svg' width='36'/><img src='svg/heavysnowshowers_night.svg' width='36'/><img src='svg/heavysnowshowers_polartwilight.svg' width='36'/>|
|heavysnowshowersandthunder|29|Heavy snow showers and thunder|<img src='svg/heavysnowshowersandthunder_day.svg' width='36'/><img src='svg/heavysnowshowersandthunder_night.svg' width='36'/><img src='svg/heavysnowshowersandthunder_polartwilight.svg' width='36'/>|
|lightrain|46|Light rain|<img src='svg/lightrain.svg' width='36'/>|
|lightrainandthunder|30|Light rain and thunder|<img src='svg/lightrainandthunder.svg' width='36'/>|
|lightrainshowers|40|Light rain showers|<img src='svg/lightrainshowers_day.svg' width='36'/><img src='svg/lightrainshowers_night.svg' width='36'/><img src='svg/lightrainshowers_polartwilight.svg' width='36'/>|
|lightrainshowersandthunder|24|Light rain showers and thunder|<img src='svg/lightrainshowersandthunder_day.svg' width='36'/><img src='svg/lightrainshowersandthunder_night.svg' width='36'/><img src='svg/lightrainshowersandthunder_polartwilight.svg' width='36'/>|
|lightsleet|47|Light sleet|<img src='svg/lightsleet.svg' width='36'/>|
|lightsleetandthunder|31|Light sleet and thunder|<img src='svg/lightsleetandthunder.svg' width='36'/>|
|lightsleetshowers|42|Light sleet showers|<img src='svg/lightsleetshowers_day.svg' width='36'/><img src='svg/lightsleetshowers_night.svg' width='36'/><img src='svg/lightsleetshowers_polartwilight.svg' width='36'/>|
|lightsnow|49|Light snow|<img src='svg/lightsnow.svg' width='36'/>|
|lightsnowandthunder|33|Light snow and thunder|<img src='svg/lightsnowandthunder.svg' width='36'/>|
|lightsnowshowers|44|Light snow showers|<img src='svg/lightsnowshowers_day.svg' width='36'/><img src='svg/lightsnowshowers_night.svg' width='36'/><img src='svg/lightsnowshowers_polartwilight.svg' width='36'/>|
|lightssleetshowersandthunder|26|Light sleet showers and thunder|<img src='svg/lightssleetshowersandthunder_day.svg' width='36'/><img src='svg/lightssleetshowersandthunder_night.svg' width='36'/><img src='svg/lightssleetshowersandthunder_polartwilight.svg' width='36'/>|
|lightssnowshowersandthunder|28|Light snow showers and thunder|<img src='svg/lightssnowshowersandthunder_day.svg' width='36'/><img src='svg/lightssnowshowersandthunder_night.svg' width='36'/><img src='svg/lightssnowshowersandthunder_polartwilight.svg' width='36'/>|
|partlycloudy|3|Partly cloudy|<img src='svg/partlycloudy_day.svg' width='36'/><img src='svg/partlycloudy_night.svg' width='36'/><img src='svg/partlycloudy_polartwilight.svg' width='36'/>|
|rain|9|Rain|<img src='svg/rain.svg' width='36'/>|
|rainandthunder|22|Rain and thunder|<img src='svg/rainandthunder.svg' width='36'/>|
|rainshowers|5|Rain showers|<img src='svg/rainshowers_day.svg' width='36'/><img src='svg/rainshowers_night.svg' width='36'/><img src='svg/rainshowers_polartwilight.svg' width='36'/>|
|rainshowersandthunder|6|Rain showers and thunder|<img src='svg/rainshowersandthunder_day.svg' width='36'/><img src='svg/rainshowersandthunder_night.svg' width='36'/><img src='svg/rainshowersandthunder_polartwilight.svg' width='36'/>|
|sleet|12|Sleet|<img src='svg/sleet.svg' width='36'/>|
|sleetandthunder|23|Sleet and thunder|<img src='svg/sleetandthunder.svg' width='36'/>|
|sleetshowers|7|Sleet showers|<img src='svg/sleetshowers_day.svg' width='36'/><img src='svg/sleetshowers_night.svg' width='36'/><img src='svg/sleetshowers_polartwilight.svg' width='36'/>|
|sleetshowersandthunder|20|Sleet showers and thunder|<img src='svg/sleetshowersandthunder_day.svg' width='36'/><img src='svg/sleetshowersandthunder_night.svg' width='36'/><img src='svg/sleetshowersandthunder_polartwilight.svg' width='36'/>|
|snow|13|Snow|<img src='svg/snow.svg' width='36'/>|
|snowandthunder|14|Snow and thunder|<img src='svg/snowandthunder.svg' width='36'/>|
|snowshowers|8|Snow showers|<img src='svg/snowshowers_day.svg' width='36'/><img src='svg/snowshowers_night.svg' width='36'/><img src='svg/snowshowers_polartwilight.svg' width='36'/>|
|snowshowersandthunder|21|Snow showers and thunder|<img src='svg/snowshowersandthunder_day.svg' width='36'/><img src='svg/snowshowersandthunder_night.svg' width='36'/><img src='svg/snowshowersandthunder_polartwilight.svg' width='36'/>|

## Legend

You can find translations for the various symbols (in English and Norwegian)
as a CSV file named `legend.csv`.

Symbol ID                      |English                          |Bokmål                         |Nynorsk                       |Variants
-------------------------------|---------------------------------|-------------------------------|------------------------------|--------
`clearsky`                     |Clear sky                        |Klarvær                        |Klårvêr                       |yes
`fair`                         |Fair                             |Lettskyet                      |Lettskya                      |yes
`partlycloudy`                 |Partly cloudy                    |Delvis skyet                   |Delvis skya                   |yes
`cloudy`                       |Cloudy                           |Skyet                          |Skya                          |no
`lightrainshowers`             |Light rain showers               |Lette regnbyger                |Lette regnbyer                |yes
`rainshowers`                  |Rain showers                     |Regnbyger                      |Regnbyer                      |yes
`heavyrainshowers`             |Heavy rain showers               |Kraftige regnbyger             |Kraftige regnbyer             |yes
`lightrainshowersandthunder`   |Light rain showers and thunder   |Lette regnbyger og torden      |Lette regnbyer og torevêr     |yes
`rainshowersandthunder`        |Rain showers and thunder         |Regnbyger og torden            |Regnbyer og torevêr           |yes
`heavyrainshowersandthunder`   |Heavy rain showers and thunder   |Kraftige regnbyger og torden   |Kraftige regnbyer og torevêr  |yes
`lightsleetshowers`            |Light sleet showers              |Lette sluddbyger               |Lette sluddbyer               |yes
`sleetshowers`                 |Sleet showers                    |Sluddbyger                     |Sluddbyer                     |yes
`heavysleetshowers`            |Heavy sleet showers              |Kraftige sluddbyger            |Kraftige sluddbyer            |yes
`lightssleetshowersandthunder` |Light sleet showers and thunder  |Lette sluddbyger og torden     |Lette sluddbyer og torevêr    |yes
`sleetshowersandthunder`       |Sleet showers and thunder        |Sluddbyger og torden           |Sluddbyer og torevêr          |yes
`heavysleetshowersandthunder`  |Heavy sleet showers and thunder  |Kraftige sluddbyger og torden  |Kraftige sluddbyer og torevêr |yes
`lightsnowshowers`             |Light snow showers               |Lette snøbyger                 |Lette snøbyer                 |yes
`snowshowers`                  |Snow showers                     |Snøbyger                       |Snøbyer                       |yes
`heavysnowshowers`             |Heavy snow showers               |Kraftige snøbyger              |Kraftige snøbyer              |yes
`lightssnowshowersandthunder`  |Light snow showers and thunder   |Lette snøbyger og torden       |Lette snøbyer og torevêr      |yes
`snowshowersandthunder`        |Snow showers and thunder         |Snøbyger og torden             |Snøbyer og torevêr            |yes
`heavysnowshowersandthunder`   |Heavy snow showers and thunder   |Kraftige snøbyger og torden    |Kraftige snøbyer og torevêr   |yes
`lightrain`                    |Light rain                       |Lett regn                      |Lett regn                     |no
`rain`                         |Rain                             |Regn                           |Regn                          |no
`heavyrain`                    |Heavy rain                       |Kraftig regn                   |Kraftig regn                  |no
`lightrainandthunder`          |Light rain and thunder           |Lett regn og torden            |Lett regn og torevêr          |no
`rainandthunder`               |Rain and thunder                 |Regn og torden                 |Regn og torevêr               |no
`heavyrainandthunder`          |Heavy rain and thunder           |Kraftig regn og torden         |Kraftig regn og torevêr       |no
`lightsleet`                   |Light sleet                      |Lett sludd                     |Lett sludd                    |no
`sleet`                        |Sleet                            |Sludd                          |Sludd                         |no
`heavysleet`                   |Heavy sleet                      |Kraftig sludd                  |Kraftig sludd                 |no
`lightsleetandthunder`         |Light sleet and thunder          |Lett sludd og torden           |Lett sludd og torevêr         |no
`sleetandthunder`              |Sleet and thunder                |Sludd og torden                |Sludd og torevêr              |no
`heavysleetandthunder`         |Heavy sleet and thunder          |Kraftig sludd og torden        |Kraftig sludd og torevêr      |no
`lightsnow`                    |Light snow                       |Lett snø                       |Lett snø                      |no
`snow`                         |Snow                             |Snø                            |Snø                           |no
`heavysnow`                    |Heavy snow                       |Kraftig snø                    |Kraftig snø                   |no
`lightsnowandthunder`          |Light snow and thunder           |Lett snø og torden             |Lett snø og torevêr           |no
`snowandthunder`               |Snow and thunder                 |Snø og torden                  |Snø og torevêr                |no
`heavysnowandthunder`          |Heavy snow and thunder           |Kraftig snø og torden          |Kraftig snø og torevêr        |no
`fog`                          |Fog                              |Tåke                           |Skodde                        |no

## Algorithm

You can potentially try to reconstruct the weather icons in the API from the
locationforecast data. A description of the symbol algorithms is too long
to document and support officially, but you can have a look at the [source code
on GitHub](https://github.com/metno/weather_symbol) if you are interested.

