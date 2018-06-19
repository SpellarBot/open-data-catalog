# 311 Service Requests - Alley Lights Out

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-alley-lights-out-f7c04) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/t28b-ys7j) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/t28b-ys7j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/t28b-ys7j/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | t28b-ys7j |
| Name | 311 Service Requests - Alley Lights Out |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | streets, alleys, lights |
| Created | 2012-04-05T20:07:54Z |
| Publication Date | 2017-04-20T10:29:43Z |

## Description

This dataset contains all open 311 reports of one or more lights out on a wooden pole in the alley and all completed requests since January 1, 2011.  If two requests regarding the same address are made within 30 calendar days of each other, the newest CSR is automatically given the status of ?Duplicate (Open)?.   Once the alley light is repaired, the CSR status will read ?Completed? for the original request and ?Duplicate (Closed)? for any duplicate requests. Data is updated daily.

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
series e:t28b-ys7j d:2011-01-01T00:00:00.000Z t:ward=14 t:zip_code=60632 t:police_district=9 t:status="Completed - Dup" t:service_request_number=11-00001814 t:type_of_service_request="Alley Light Out" t:community_area=58 t:street_address="4316 S SACRAMENTO AVE" m:longitude=-87.69933194705028 m:latitude=41.81517646745516

series e:t28b-ys7j d:2011-01-01T00:00:00.000Z t:ward=34 t:zip_code=60643 t:police_district=5 t:status="Completed - Dup" t:service_request_number=11-00002131 t:type_of_service_request="Alley Light Out" t:community_area=53 t:street_address="12256 S THROOP ST" m:longitude=-87.65386985854649 m:latitude=41.67114764355224

series e:t28b-ys7j d:2011-01-01T00:00:00.000Z t:ward=18 t:zip_code=60629 t:police_district=8 t:status="Completed - Dup" t:service_request_number=11-00002721 t:type_of_service_request="Alley Light Out" t:community_area=66 t:street_address="6949 S ROCKWELL ST" m:longitude=-87.68820480368018 m:latitude=41.76717991767958
```

## Meta Commands

```ls
metric m:latitude p:long l:Latitude t:dataTypeName=number

metric m:longitude p:long l:Longitude t:dataTypeName=number

entity e:t28b-ys7j l:"311 Service Requests - Alley Lights Out" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/t28b-ys7j

property e:t28b-ys7j t:meta.view v:id=t28b-ys7j v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Alley Lights Out" v:attribution="City of Chicago"

property e:t28b-ys7j t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:t28b-ys7j t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| creation_date       | status          | completion_date     | service_request_number | type_of_service_request | street_address        | zip_code | x_coordinate     | y_coordinate     | ward | police_district | community_area | latitude           | longitude          | 
| =================== | =============== | =================== | ====================== | ======================= | ===================== | ======== | ================ | ================ | ==== | =============== | ============== | ================== | ================== | 
|                     | STATUS          |                     | SERVICE REQUEST NUMBER | TYPE OF SERVICE REQUEST | STREET ADDRESS        |          |                  |                  |      |                 |                |                    |                    | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-02T00:00:00 | 11-00001814            | Alley Light Out         | 4316 S SACRAMENTO AVE | 60632    | 1157077.82962754 | 1875878.20800447 | 14   | 9               | 58             | 41.81517646745516  | -87.69933194705028 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-02T00:00:00 | 11-00002131            | Alley Light Out         | 12256 S THROOP ST     | 60643    | 1169885.18988818 | 1823490.1964662  | 34   | 5               | 53             | 41.67114764355224  | -87.65386985854649 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-02T00:00:00 | 11-00002721            | Alley Light Out         | 6949 S ROCKWELL ST    | 60629    | 1160242.32740792 | 1858411.16951698 | 18   | 8               | 66             | 41.76717991767958  | -87.68820480368018 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-02T00:00:00 | 11-00002731            | Alley Light Out         | 5300 S WASHTENAW AVE  | 60632    | 1159271.90601236 | 1869409.61562889 | 14   | 9               | 63             | 41.797381114669676 | -87.69146089039006 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-02T00:00:00 | 11-00003144            | Alley Light Out         | 12442 S LA SALLE ST   | 60628    | 1177527.17909801 | 1822448.27412904 | 9    | 5               | 53             | 41.66811969055759  | -87.62593190085083 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-02T00:00:00 | 11-00003188            | Alley Light Out         | 9410 S RACINE AVE     | 60620    | 1169976.96250524 | 1842378.65757736 | 21   | 22              | 73             | 41.722978614106935 | -87.65298790565937 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-02T00:00:00 | 11-00003273            | Alley Light Out         | 10531 S AVENUE E      | 60617    | 1203823.48118116 | 1835742.52229254 | 10   | 4               | 52             | 41.70396765780105  | -87.52924094215103 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00001316            | Alley Light Out         | 5132 S NASHVILLE AVE  | 60638    | 1133247.0698825  | 1869829.87361304 | 23   | 8               | 56             | 41.79902799484382  | -87.78688959608697 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00002259            | Alley Light Out         | 5400 N NEVA AVE       | 60656    | 1127676.79528426 | 1935426.03580553 | 41   | 16              | 10             | 41.97912874964131  | -87.80583880940901 | 
```