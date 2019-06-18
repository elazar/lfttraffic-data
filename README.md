# Usage

## Accidents

Accidents can be fetched in JSON form from the following URL.

https://raw.githubusercontent.com/elazar/lfttraffic-data/master/accidents.json

The file contains an array of objects, each with the following properties:

* `address`
* `city`
* `time`
* `due_to`
* `latitude`
* `longitude`

## Traffic cameras

Traffic cameras can be fetched in JSON form from the following URL.

https://raw.githubusercontent.com/elazar/lfttraffic-data/master/cameras.json

The file contains an array of objects, each with the following properties:

* `main_road`
* `cross_road`
* `latitude`
* `longitude`
* `ptzid`

The current image for a specific camera is accessible at a URL of the following form, where the value of the `ptzid` parameter corresponds to the object property by the same name referenced in the list above.

```
http://www.lafayettela.gov/tcams/getTCamera.aspx?ptzid=###
```

# Credits

## Traffic camera feeds

* Sourced from http://www.lafayettela.gov/trafficcameras/traffic_cameras.aspx
* Provided by [Lafayette Consolidated Government](http://www.lafayettela.gov)

## Accident reports

* Sourced from lafayette911.org
* Provided by [Lafayette Parish Communication District](http://www.lafayettela.gov/FireDepartment/Pages/Communications.aspx)
* Accessed with the [request](https://www.npmjs.com/package/request) library
* Processed with the [cheerio](https://www.npmjs.com/package/cheerio) library

## GPS coordinates

* Provided by [Here](https://www.here.com/products/location-based-services/geocoding-tools)
* Accessed with the [node-geocoder](https://www.npmjs.com/package/node-geocoder) library

## Data hosting

* Provided by [GitHub](https://github.com)
