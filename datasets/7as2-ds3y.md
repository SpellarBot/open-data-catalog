# 311 Service Requests - Pot Holes Reported

## Dataset

* [Dataset URL](https://data.cityofchicago.org/api/views/7as2-ds3y/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/311-service-requests-pot-holes-reported-c4116)
* [Metadata URL](https://data.cityofchicago.org/api/views/7as2-ds3y)
* Id = 7as2-ds3y
* Name = 311 Service Requests - Pot Holes Reported
* Attribution = City of Chicago
* [Attribution Link](http://www.cityofchicago.org)
* Category = Service Requests
* Tags = [streets, pot holes]
* Created = 2011-09-30T09:11:02Z
* Publication Date = 2017-03-07T12:05:59Z
* Rows Updated = 2017-03-07T12:04:42Z

## Description

The Chicago Department of Transportation (CDOT) oversees the patching of potholes on over 4,000 miles of arterial and residential streets in Chicago. CDOT receives reports of potholes through the 311 call center and uses a computerized mapping and tracking system to identify pothole locations and efficiently schedule crews.  One call to 311 can generate multiple pothole repairs. When a crew arrives to repair a 311 pothole, it fills all the other potholes within the block.  Pothole repairs are generally completed within 7 days from the first report of a pothole to 311. Weather conditions, particularly frigid temps and precipitation, influence how long a repair takes.  On days when weather is cooperative and there is no precipitation, crews can fill several thousand potholes.  

If a previous request is already open for a buffer of 4 addresses the request is given the status of "Duplicate (Open)".  For example, if there is an existing CSR for 6535 N Western and a new request is received for 6531 N Western (which is within four addresses of the original CSR) then the new request is given a status of "Duplicate (Open)".

Once the street is repaired, the status in CSR will read ?Completed? for the original request and "Duplicate (Closed)" for any duplicate requests.  A service request also receives the status of ?Completed? when the reported address is inspected but no potholes are found or have already been filled.  If another issue is found with the street, such as a ?cave-in? or ?failed utility cut?, then it is directed to the appropriate department or contractor. 

Data Owner: Transportation. Time Period: All open requests and all completed requests since January 1, 2011. Frequency: Data is updated daily.

## Columns

```ls
| Name                               | Field Name                         | Data Type     | Render Type   | Schema Type    | Included | 
| ================================== | ================================== | ============= | ============= | ============== | ======== | 
| CREATION DATE                      | creation_date                      | calendar_date | calendar_date | time           | Yes      | 
| STATUS                             | status                             | text          | text          | series tag     | Yes      | 
| COMPLETION DATE                    | completion_date                    | calendar_date | calendar_date |                | No       | 
| SERVICE REQUEST NUMBER             | service_request_number             | text          | text          | series tag     | Yes      | 
| TYPE OF SERVICE REQUEST            | type_of_service_request            | text          | text          | series tag     | Yes      | 
| CURRENT ACTIVITY                   | current_activity                   | text          | text          | series tag     | Yes      | 
| MOST RECENT ACTION                 | most_recent_action                 | text          | text          | series tag     | Yes      | 
| NUMBER OF POTHOLES FILLED ON BLOCK | number_of_potholes_filled_on_block | number        | number        | numeric metric | Yes      | 
| STREET ADDRESS                     | street_address                     | text          | text          |                | No       | 
| ZIP                                | zip                                | text          | number        | series tag     | Yes      | 
| X COORDINATE                       | x_coordinate                       | number        | number        |                | No       | 
| Y COORDINATE                       | y_coordinate                       | number        | number        |                | No       | 
| Ward                               | ward                               | text          | number        | series tag     | Yes      | 
| Police District                    | police_district                    | text          | number        | series tag     | Yes      | 
| Community Area                     | community_area                     | number        | number        | numeric metric | Yes      | 
| SSA                                | ssa                                | text          | text          | series tag     | Yes      | 
| LATITUDE                           | latitude                           | number        | number        | numeric metric | Yes      | 
| LONGITUDE                          | longitude                          | number        | number        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = y_coordinate,x_coordinate,completion_date,street_address
Annotation Fields = 
```

## Data Commands

```ls
series e:7as2-ds3y d:2011-01-01T00:00:00.000Z t:zip=60620 t:ward=17 t:police_district=6 t:status="Completed - Dup" t:service_request_number=11-00002110 t:type_of_service_request="Pot Hole in Street" m:community_area=69 m:longitude=-87.63854 m:latitude=41.75608

series e:7as2-ds3y d:2011-01-01T00:00:00.000Z t:zip=60629 t:ward=13 t:police_district=8 t:status="Completed - Dup" t:ssa=3 t:service_request_number=11-00002209 t:type_of_service_request="Pot Hole in Street" m:community_area=65 m:longitude=-87.7225 m:latitude=41.76401

series e:7as2-ds3y d:2011-01-01T00:00:00.000Z t:zip=60647 t:ward=1 t:police_district=14 t:status="Completed - Dup" t:service_request_number=11-00002224 t:type_of_service_request="Pot Hole in Street" m:community_area=22 m:longitude=-87.6877 m:latitude=41.92501
```

## Meta Commands

```ls
metric m:number_of_potholes_filled_on_block l:"NUMBER OF POTHOLES FILLED ON BLOCK" t:dataTypeName=number

metric m:community_area l:"Community Area" t:dataTypeName=number

metric m:latitude l:LATITUDE t:dataTypeName=number

metric m:longitude l:LONGITUDE t:dataTypeName=number

entity e:7as2-ds3y l:"311 Service Requests - Pot Holes Reported" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/7as2-ds3y

property e:7as2-ds3y t:meta.view d:2017-03-08T00:57:05.917Z v:id=7as2-ds3y v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Pot Holes Reported" v:attribution="City of Chicago"

property e:7as2-ds3y t:meta.view.owner d:2017-03-08T00:57:05.917Z v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false

property e:7as2-ds3y t:meta.view.tableauthor d:2017-03-08T00:57:05.917Z v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```