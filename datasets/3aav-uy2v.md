# 311 Service Requests - Street Lights - One Out

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-street-lights-one-out-97736) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/3aav-uy2v) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/3aav-uy2v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/3aav-uy2v/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 3aav-uy2v |
| Name | 311 Service Requests - Street Lights - One Out |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | streets, lights |
| Created | 2012-04-05T20:04:10Z |
| Publication Date | 2017-04-21T07:18:14Z |

## Description

This dataset contains all open 311 reports of one or two lights out on metal poles on a residential or arterial street and all completed requests since January 1, 2011. Whenever CDOT receives a report of a street light outage, the electrician assigned to make the repair looks at all the lights in a group (circuit) to make sure that they are working properly.  If two requests regarding the same group are made within 30 calendar days of each other, the newest CSR is automatically given the status of ?Duplicate (Open).?   Since the electrician will be looking at all the lights in a group to verify that they are all working the ?Duplicate (Open)? address will also be observed and repaired.  Once the street lights are repaired, the CSR status will read ?Completed? for the original request and ?Duplicate (Closed)? for any duplicate requests. Data is updated daily.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | time           | creation_date           | Creation Date           | calendar_date | calendar_date |
| Yes      | series tag     | status                  | Status                  | text          | text          |
| No       |                | completion_date         | Completion Date         | calendar_date | calendar_date |
| Yes      | series tag     | service_request_number  | Service Request Number  | text          | text          |
| Yes      | series tag     | type_of_service_request | Type of Service Request | text          | text          |
| Yes      | series tag     | street_address          | Street Address          | text          | text          |
| Yes      | series tag     | zip_code                | ZIP Code                | text          | number        |
| No       |                | x_coordinate            | X Coordinate            | number        | number        |
| No       |                | y_coordinate            | Y Coordinate            | number        | number        |
| Yes      | series tag     | ward                    | Ward                    | text          | number        |
| Yes      | series tag     | police_district         | Police District         | text          | number        |
| Yes      | series tag     | community_area          | Community Area          | text          | number        |
| Yes      | numeric metric | latitude                | Latitude                | number        | number        |
| Yes      | numeric metric | longitude               | Longitude               | number        | number        |
| Yes      | series tag     | location                | Location                | text          | text          |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = completion_date,x_coordinate,y_coordinate
```

## Data Commands

```ls
series e:3aav-uy2v d:2013-01-09T00:00:00.000Z t:ward=5 t:zip_code=60619 t:police_district=4 t:location=(41.75828320385884,-87.59322411776203) t:status=Completed t:service_request_number=13-00036629 t:type_of_service_request="Street Light - 1/Out" t:community_area=43 t:street_address="7514 S KIMBARK AVE" m:longitude=-87.59322411776203 m:latitude=41.75828320385884

series e:3aav-uy2v d:2013-01-09T00:00:00.000Z t:ward=9 t:zip_code=60628 t:police_district=5 t:location=(41.71150624166045,-87.62962423539825) t:status=Completed t:service_request_number=13-00036712 t:type_of_service_request="Street Light - 1/Out" t:community_area=49 t:street_address="10057 S YALE AVE" m:longitude=-87.62962423539825 m:latitude=41.71150624166045

series e:3aav-uy2v d:2013-01-09T00:00:00.000Z t:ward=10 t:zip_code=60617 t:police_district=4 t:location=(41.689898813235565,-87.5401022889258) t:status=Completed t:service_request_number=13-00032399 t:type_of_service_request="Street Light - 1/Out" t:community_area=52 t:street_address="11308 S AVENUE O" m:longitude=-87.5401022889258 m:latitude=41.689898813235565
```

## Meta Commands

```ls
metric m:latitude p:long l:Latitude t:dataTypeName=number

metric m:longitude p:long l:Longitude t:dataTypeName=number

entity e:3aav-uy2v l:"311 Service Requests - Street Lights - One Out" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/3aav-uy2v

property e:3aav-uy2v t:meta.view v:id=3aav-uy2v v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Street Lights - One Out" v:attribution="City of Chicago"

property e:3aav-uy2v t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:3aav-uy2v t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| creation_date       | status          | completion_date     | service_request_number | type_of_service_request | street_address      | zip_code | x_coordinate     | y_coordinate     | ward | police_district | community_area | latitude           | longitude          | location                               | 
| =================== | =============== | =================== | ====================== | ======================= | =================== | ======== | ================ | ================ | ==== | =============== | ============== | ================== | ================== | ====================================== | 
|                     | STATUS          |                     | SERVICE REQUEST NUMBER | TYPE OF SERVICE REQUEST | STREET ADDRESS      |          |                  |                  |      |                 |                |                    |                    | LOCATION                               | 
| 2013-01-09T00:00:00 | Completed       | 2013-01-14T00:00:00 | 13-00036629            | Street Light - 1/Out    | 7514 S KIMBARK AVE  | 60619    | 1186181.29271973 | 1855377.9278059  | 5    | 4               | 43             | 41.75828320385884  | -87.59322411776203 | (41.75828320385884,-87.59322411776203) | 
| 2013-01-09T00:00:00 | Completed       | 2013-01-14T00:00:00 | 13-00036712            | Street Light - 1/Out    | 10057 S YALE AVE    | 60628    | 1176389.19789488 | 1838249.52283384 | 9    | 5               | 49             | 41.71150624166045  | -87.62962423539825 | (41.71150624166045,-87.62962423539825) | 
| 2013-01-09T00:00:00 | Completed       | 2013-01-15T00:00:00 | 13-00032399            | Street Light - 1/Out    | 11308 S AVENUE O    | 60617    | 1200904.76567377 | 1830588.4890165  | 10   | 4               | 52             | 41.689898813235565 | -87.5401022889258  | (41.689898813235565,-87.5401022889258) | 
| 2013-01-09T00:00:00 | Completed       | 2013-01-15T00:00:00 | 13-00036769            | Street Light - 1/Out    | 5100 S STATE ST     | 60609    | 1177137.85443359 | 1871213.28607877 | 3    | 2               | 40             | 41.8019457977942   | -87.62588976253781 | (41.8019457977942,-87.62588976253781)  | 
| 2013-01-09T00:00:00 | Completed       | 2013-01-18T00:00:00 | 13-00036754            | Street Light - 1/Out    | 9400 S EWING AVE    | 60617    | 1201315.87190145 | 1843355.64351312 | 10   | 4               | 52             | 41.72492255854294  | -87.53816565542006 | (41.72492255854294,-87.53816565542006) | 
| 2011-01-10T00:00:00 | Completed - Dup | 2011-01-10T00:00:00 | 11-00040726            | Street Light - 1/Out    | 504 S LARAMIE AVE   | 60644    | 1141805.69327098 | 1897171.84208577 | 29   | 15              | 25             | 41.87390478023467  | -87.75482720289442 | (41.87390478023467,-87.75482720289442) | 
| 2011-01-10T00:00:00 | Completed - Dup | 2011-01-10T00:00:00 | 11-00045711            | Street Light - 1/Out    | 6024 W FLETCHER ST  | 60634    | 1135678.45182563 | 1920316.30008648 | 36   | 25              | 19             | 41.93752716036715  | -87.77677255497987 | (41.93752716036715,-87.77677255497987) | 
| 2011-01-10T00:00:00 | Completed - Dup | 2011-01-10T00:00:00 | 11-00046826            | Street Light - 1/Out    | 4900 S HALSTED ST   | 60609    | 1171799.94262892 | 1872291.50600304 | 3    | 9               | 61             | 41.80502343693148  | -87.64543428405335 | (41.80502343693148,-87.64543428405335) | 
| 2011-01-10T00:00:00 | Completed - Dup | 2011-01-11T00:00:00 | 11-00043524            | Street Light - 1/Out    | 5226 W SCHUBERT AVE | 60639    | 1141078.47442537 | 1917455.97897947 | 31   | 25              | 19             | 41.9295802328296   | -87.7569969091612  | (41.9295802328296,-87.7569969091612)   | 
```