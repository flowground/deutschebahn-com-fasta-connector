# ![LOGO](logo.png) FaSta-Station_Facilities_Status **flow**ground Connector

## Description

A generated **flow**ground connector for the FaSta-Station_Facilities_Status API (version v1).

Generated from: https://api.apis.guru/v2/specs/deutschebahn.com/fasta/v1/swagger.json<br/>
Generated at: 2019-05-07T17:40:13+03:00

## API Description

A RESTful webservice to retrieve data about the operational state of public elevators and escalators in german railway stations operated by DB Station&Service AG. 
Note: Production and sandbox environments use the same production backend server. 

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Returns information about disruptions of facilities filtered by parameters.

#### Input Parameters
* `type` - _optional_ - type of the facility to filter by
* `equipmentnumber` - _optional_ - equipmentnumber of the facility to fetch
* `stationnumber` - _optional_ - stationnumber of the station to fetch

### Returns information about a specific disruption of a facility

#### Input Parameters
* `disruptionnumber` - _required_ - disruptionnumber of the disruption to fetch

### Access to public facilities (escalators and elevators) in railway stations

#### Input Parameters
* `type` - _optional_ - type of the facility to filter by
* `state` - _optional_ - the state of the facility to filter by
* `equipmentnumbers` - _optional_ - equipmentnumbers of the facility to filter by
* `stationnumber` - _optional_ - station number to filter by
* `area` - _optional_ - Geo coordinate rectangle in WGS84-format to filter by. Parameters must be 4 numbers exactly as follows: longitudeWest, latitudeSouth, longitudeEast, latitudeNorth.

### Returns the facility identified by its equipmentnumber

#### Input Parameters
* `equipmentnumber` - _required_ - equipmentnumber of the facility to fetch

### Returns information about the station and its facilities identified by a stationnumber.

#### Input Parameters
* `stationnumber` - _required_ - stationnumber of the station to fetch

## License

**flow**ground :- Telekom iPaaS / deutschebahn-com-fasta-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
