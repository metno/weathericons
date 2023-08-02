
# MET Weather API icons

## Weather icons

This is a redesigned set of icons, meant to be used in conjunction
with version 2.0 of Locationforecast, Nowcast and Oceanforecast.
They are available in PNG, SVG and PDF formats. The images are the
same as used on [Yr](https://yr.no/), but the filenames are different
to correspond with the symbol codes in Locationforecast

The icon files are meant to be downloaded and bundled with your application.
There is no need for an API to fetch individual icons on demand.

{: .note }
There is a typing error in `lightssleetshowersandthunder` and
`lightssnowshowersandthunder` (an extra "s" after "light"). Unfortunately,
correcting this would mean breaking existing applications, so it has been
postponed to the next version of locationforecast/nowcast.

### Variants

Some symbols come in three different variants, for day, night and [polar
twilight](https://en.wikipedia.org/wiki/Polar_night#Polar_twilight)
respectively. Others (the ones without sun or moon) are constant during the
day. Locationforecast/2.0 will specify the correct variant to use for each
hour.

### Algorithm

You can potentially try to reconstruct the weather icons in the API from the
locationforecast data. A description of the symbol algorithms is too long
to document and support officially, but you can have a look at the [source code
on GitHub](https://github.com/metno/weather_symbol) if you are interested.

## Alerting icons

You can download alerting icons in SVG format (which can be converted to PNG)
from the [Yr GitHub page](https://github.com/nrkno/yr-warning-icons).

### Variants

Each warning icon includes a yellow, orange, and red variant.
You can find descriptions of what the icons represent on the Yr help pages
in [English](https://hjelp.yr.no/hc/en-us/articles/360014052634)
and [Norwegian](https://hjelp.yr.no/hc/no/articles/360014052634).

Event type|Icon id
----------|--------
Avalanches|`icon-warning-avalanches`
BlowingSnow|`icon-warning-snow`
DrivingConditions|`icon-warning-drivingconditions`
Flood|`icon-warning-flood`
ForestFire|`icon-warning-forestfire`
Gale|`icon-warning-wind`
Ice|`icon-warning-ice`
Icing|`icon-warning-generic`
Landslide|`icon-warning-landslide`
PolarLow|`icon-warning-polarlow`
Rain|`icon-warning-rain`
RainFlood|`icon-warning-rainflood`
Snow|`icon-warning-snow`
StormSurge|`icon-warning-stormsurge`
Lightning|`icon-warning-lightning`
Wind|`icon-warning-wind`
Unknown|`icon-warning-generic`

In addition there is an extreme warning icon, `icon-warning-extreme`, which only is available in red.

## License

The original icons as used on yr.no can be found on GitHub:
- [weather icons](https://github.com/YR/weather-symbols/)
- [alert icons](https://github.com/nrkno/yr-warning-icons)

The icons are copyright (c) 2015-2017 Yr and licensed under the [MIT
License](https://github.com/YR/weather-symbols/blob/master/LICENSE).
