# Usage

## Traffic cameras feeds

The current image for a specific camera is accessible at a URL of the following form, where the value of the `ptzid` parameter is found in the `cameras.json` file in this repository.

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
