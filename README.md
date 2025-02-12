# Awesome Weather Widget
Contributors: halgatewood, ghuger, richardgabriel, jwetzell, mrmcx

License: [GPLv2](http://www.gnu.org/licenses/gpl-2.0.html) or later

Finally beautiful weather widgets for your beautiful WordPress website.

## Description

This plugin allows you to easily add super clean (and awesome) weather widgets to your site. 

### Weather by OpenWeatherMap or Pirate Weather
The weather data is available either by [OpenWeatherMap](https://openweathermap.org) or [Pirate Weather](https://pirateweather.net/). 

They require a free key to access the data. 

* [Open Weather Map API Key](http://openweathermap.org/appid#get)
* [Pirate Weather API Key](https://pirate-weather.apiable.io/)

Once you have the API Key, you can save it in the WordPress admin under `'Settings' -> 'Awesome Weather'`

### Setup
Use the built in widget with all of its marvelous settings or add it to a page or theme with the shortcode:
`[awesome-weather owm_city_id="4544349"]` or `[awesome-weather location="Oklahoma City"]`

## Installation

1. Add plugin to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Register for an OpenWeatherMap [API Key](http://openweathermap.org/appid#get)
1. Add your API Key to the settings field in 'Settings' -> 'Awesome Weather' (added in version 1.5.3)
1. Use shortcode or widget to display awesome weather on your awesome site

The easiest shortcode setting is just: `[awesome-weather location="Oklahoma City"]`


## Screenshots

1. Basic wide layout
2. Basic tall layout
3. Micro, using the checkbox 'Hide Stats'
4. Widget Settings
5. Background Image Option (1.2)
6. Add inline styles to your widget and set custom background colors (1.3.1)
7. Use different background images based on weather (1.5)
8. Search for the City ID directly in the widget settings (1.5)