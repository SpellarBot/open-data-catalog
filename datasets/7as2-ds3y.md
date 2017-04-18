# 311 Service Requests - Pot Holes Reported

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-pot-holes-reported-c4116) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/7as2-ds3y) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/7as2-ds3y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/7as2-ds3y/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 7as2-ds3y |
| Name | 311 Service Requests - Pot Holes Reported |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | streets, pot holes |
| Created | 2011-09-30T09:11:02Z |
| Publication Date | 2017-04-18T10:44:09Z |

## Description

The Chicago Department of Transportation (CDOT) oversees the patching of potholes on over 4,000 miles of arterial and residential streets in Chicago. CDOT receives reports of potholes through the 311 call center and uses a computerized mapping and tracking system to identify pothole locations and efficiently schedule crews.  One call to 311 can generate multiple pothole repairs. When a crew arrives to repair a 311 pothole, it fills all the other potholes within the block.  Pothole repairs are generally completed within 7 days from the first report of a pothole to 311. Weather conditions, particularly frigid temps and precipitation, influence how long a repair takes.  On days when weather is cooperative and there is no precipitation, crews can fill several thousand potholes.  

If a previous request is already open for a buffer of 4 addresses the request is given the status of "Duplicate (Open)".  For example, if there is an existing CSR for 6535 N Western and a new request is received for 6531 N Western (which is within four addresses of the original CSR) then the new request is given a status of "Duplicate (Open)".

Once the street is repaired, the status in CSR will read “Completed” for the original request and "Duplicate (Closed)" for any duplicate requests.  A service request also receives the status of “Completed” when the reported address is inspected but no potholes are found or have already been filled.  If another issue is found with the street, such as a “cave-in” or “failed utility cut”, then it is directed to the appropriate department or contractor. 

Data Owner: Transportation. Time Period: All open requests and all completed requests since January 1, 2011. Frequency: Data is updated daily.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type     | Render Type   |
| ======== | ============== | ================================== | ================================== | ============= | ============= |
| Yes      | time           | creation_date                      | CREATION DATE                      | calendar_date | calendar_date |
| Yes      | series tag     | status                             | STATUS                             | text          | text          |
| No       |                | completion_date                    | COMPLETION DATE                    | calendar_date | calendar_date |
| Yes      | series tag     | service_request_number             | SERVICE REQUEST NUMBER             | text          | text          |
| Yes      | series tag     | type_of_service_request            | TYPE OF SERVICE REQUEST            | text          | text          |
| Yes      | series tag     | current_activity                   | CURRENT ACTIVITY                   | text          | text          |
| Yes      | series tag     | most_recent_action                 | MOST RECENT ACTION                 | text          | text          |
| Yes      | numeric metric | number_of_potholes_filled_on_block | NUMBER OF POTHOLES FILLED ON BLOCK | number        | number        |
| Yes      | series tag     | street_address                     | STREET ADDRESS                     | text          | text          |
| Yes      | series tag     | zip                                | ZIP                                | text          | number        |
| No       |                | x_coordinate                       | X COORDINATE                       | number        | number        |
| No       |                | y_coordinate                       | Y COORDINATE                       | number        | number        |
| Yes      | series tag     | ward                               | Ward                               | text          | number        |
| Yes      | series tag     | police_district                    | Police District                    | text          | number        |
| Yes      | series tag     | community_area                     | Community Area                     | text          | number        |
| Yes      | series tag     | ssa                                | SSA                                | text          | text          |
| No       |                | latitude                           | LATITUDE                           | number        | number        |
| No       |                | longitude                          | LONGITUDE                          | number        | number        |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = completion_date,x_coordinate,y_coordinate,latitude,longitude
```

## Data Commands

```ls
series e:7as2-ds3y d:2011-01-01T00:00:00.000Z t:zip=60643 t:ward=19 t:police_district=22 t:most_recent_action="Pothole Patched" t:status=Completed t:service_request_number=11-00002021 t:current_activity="Dispatch Crew" t:community_area=72 t:type_of_service_request="Pot Hole in Street" t:street_address="1642 W 99TH ST" m:number_of_potholes_filled_on_block=5

series e:7as2-ds3y d:2011-01-01T00:00:00.000Z t:zip=60623 t:ward=22 t:police_district=10 t:most_recent_action="Pothole Patched" t:status=Completed t:service_request_number=11-00002273 t:current_activity="Dispatch Crew" t:community_area=30 t:type_of_service_request="Pot Hole in Street" t:street_address="3500 S PULASKI RD" m:number_of_potholes_filled_on_block=7

series e:7as2-ds3y d:2011-01-01T00:00:00.000Z t:zip=60619 t:ward=6 t:police_district=6 t:most_recent_action="Pothole Patched" t:status=Completed t:ssa=51 t:service_request_number=11-00002650 t:current_activity="Dispatch Crew" t:community_area=69 t:type_of_service_request="Pot Hole in Street" t:street_address="7851 S DR MARTIN LUTHER KING JR DR" m:number_of_potholes_filled_on_block=5
```

## Meta Commands

```ls
metric m:number_of_potholes_filled_on_block p:integer l:"NUMBER OF POTHOLES FILLED ON BLOCK" t:dataTypeName=number

entity e:7as2-ds3y l:"311 Service Requests - Pot Holes Reported" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/7as2-ds3y

property e:7as2-ds3y t:meta.view v:id=7as2-ds3y v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Pot Holes Reported" v:attribution="City of Chicago"

property e:7as2-ds3y t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:7as2-ds3y t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| creation_date       | status          | completion_date     | service_request_number | type_of_service_request | current_activity | most_recent_action | number_of_potholes_filled_on_block | street_address                | zip   | x_coordinate     | y_coordinate     | ward | police_district | community_area | ssa | latitude           | longitude          | 
| =================== | =============== | =================== | ====================== | ======================= | ================ | ================== | ================================== | ============================= | ===== | ================ | ================ | ==== | =============== | ============== | === | ================== | ================== | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00002110            | Pot Hole in Street      |                  |                    |                                    | 7600 S PARNELL AVE            | 60620 | 1173863.13003072 | 1854505.80057442 | 17   | 6               | 69             |     | 41.75607825280598  | -87.63853957634103 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00002209            | Pot Hole in Street      |                  |                    |                                    | 7100 S PULASKI RD             | 60629 | 1150934.05446561 | 1857220.94202977 | 13   | 8               | 65             | 3   | 41.764007749308014 | -87.72249910770661 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00002224            | Pot Hole in Street      |                  |                    |                                    | 2400 W FULLERTON AVE          | 60647 | 1159963.77500445 | 1915885.23341463 | 1    | 14              | 22             |     | 41.92500993476519  | -87.68770475222249 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00002247            | Pot Hole in Street      |                  |                    |                                    | 11100 S HALSTED ST            | 60628 | 1172962.77918359 | 1831243.23598926 | 34   | 22              | 75             | 45  | 41.692263123425136 | -87.6425226876268  | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00002276            | Pot Hole in Street      |                  |                    |                                    | 1200 S CLARK ST               | 60605 | 1175703.41731461 | 1895044.91267398 | 2    | 1               | 33             |     | 41.867286165270755 | -87.63058096773683 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00002947            | Pot Hole in Street      |                  |                    |                                    | 2400 N NB OUTER LAKE SHORE DR | 60614 | 1175330.3518669  | 1916458.7619222  | 43   | 23              | 7              |     | 41.92620071801162  | -87.63133087271531 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00003041            | Pot Hole in Street      |                  |                    |                                    | 1600 N ELSTON AVE             | 60642 | 1166938.46533072 | 1910765.96671356 | 32   | 14              | 24             |     | 41.91070699688122  | -87.66232724459678 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00003086            | Pot Hole in Street      |                  |                    |                                    | 7100 S PULASKI RD             | 60629 | 1150934.05446561 | 1857220.94202977 | 13   | 8               | 65             | 3   | 41.764007749308014 | -87.72249910770661 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00003439            | Pot Hole in Street      |                  |                    |                                    | 3408 N CLARK ST               | 60657 | 1169136.96248219 | 1922825.63479501 | 44   | 19              | 6              | 17  | 41.943820984368344 | -87.65396258925858 | 
| 2011-01-01T00:00:00 | Completed       | 2011-01-03T00:00:00 | 11-00002021            | Pot Hole in Street      | Dispatch Crew    | Pothole Patched    | 5                                  | 1642 W 99TH ST                | 60643 | 1166945.42467286 | 1839061.36263023 | 19   | 22              | 72             |     | 41.71403466751051  | -87.66509581640723 | 
```