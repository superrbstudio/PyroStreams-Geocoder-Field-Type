# PyroStreams Geocoder Field Type v1.0.1-dev

This field type allows you to specify a geographic location which will be converted to latitude and longitude coordinates, these coordinates can then be used in the any Map API.
For front-end usage examples, see [Front End Usage](https://github.com/HighwayofLife/PyroStreams-Geocoder-Field-Type/wiki/Front-End-Usage).

## Changelog

_1.0.1-dev_

* Add support for field slugs: latitude and longitude (Adam Fairholm)
* Create CSS and JS files for geocoder
* Add the ability to drag the marker
* Message feedback on success and errors

_1.0.0 - August 27, 2012_

* Initial release

## Installation

Copy the contents of this directory into a "geocoder" directory in either addons/<site-ref>/field\_types/ or addons/shared\_addons/field\_types/

## Usage

After being assigned to a stream, you can specify any geographic location in the field and a map will appear showing the location. The geographic location is then saved as latitude and longitude coordinates. e.g.: "xx.xxxxx,-xx.xxxxx"

This field type will return latitude and longitude variables for use in your templates:

	{{ field_slug:latitude }}
	{{ field_slug:longitude }}

## Contributors

 * David Lewis (Author)
 * Adam Fairholm
