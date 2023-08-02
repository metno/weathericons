
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

