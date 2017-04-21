# 311 Service Requests - Sanitation Code Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-sanitation-code-complaints-6be8b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/me59-5fac) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/me59-5fac/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/me59-5fac/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | me59-5fac |
| Name | 311 Service Requests - Sanitation Code Complaints |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | garbage, sanitation, complaints |
| Created | 2011-09-30T09:03:09Z |
| Publication Date | 2017-04-20T08:39:59Z |

## Description

All open sanitation code complaints made to 311 and all requests completed since January 1, 2011. The Department of Streets and Sanitation investigates and remedies reported violations of Chicago?s sanitation code. Residents may request service for violations such as overflowing dumpsters and garbage in the alley.
311 sometimes receives duplicate sanitation code complaints. Requests that have been labeled as duplicates are in the same geographic area as a previous request and have been entered into 311?s Customer Service Request (CSR) system at around the same time. Duplicate complaints are labeled as such in the status field, as either "Open - Dup" or "Completed - Dup."
Data Owner: Streets and Sanitation (http://www.cityofchicago.org/content/city/en/depts/streets.html).
Time Period: January 1, 2011 to present.
Frequency: Data is updated daily.
Related Applications: 311 Service Request Status Inquiry (https://servicerequest.cityofchicago.org/web_intake_chic/Controller?op=createsrquery2) and Report Sanitation Code Complaint (https://servicerequest.cityofchicago.org/web_intake_chic/Controller?op=locform&invSRType=SCB&invSRDesc=Sanitation%20Code%20Violation&locreq=Y&stnumreqd=Y).

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type     | Render Type   |
| ======== | ============== | ========================================== | ========================================== | ============= | ============= |
| Yes      | time           | creation_date                              | Creation Date                              | calendar_date | calendar_date |
| Yes      | series tag     | status                                     | Status                                     | text          | text          |
| No       |                | completion_date                            | Completion Date                            | calendar_date | calendar_date |
| Yes      | series tag     | service_request_number                     | Service Request Number                     | text          | text          |
| Yes      | series tag     | type_of_service_request                    | Type of Service Request                    | text          | text          |
| Yes      | series tag     | what_is_the_nature_of_this_code_violation_ | What is the Nature of this Code Violation? | text          | text          |
| Yes      | series tag     | street_address                             | Street Address                             | text          | text          |
| Yes      | series tag     | zip_code                                   | ZIP Code                                   | text          | number        |
| No       |                | x_coordinate                               | X Coordinate                               | number        | number        |
| No       |                | y_coordinate                               | Y Coordinate                               | number        | number        |
| Yes      | series tag     | ward                                       | Ward                                       | text          | number        |
| Yes      | series tag     | police_district                            | Police District                            | text          | number        |
| Yes      | series tag     | community_area                             | Community Area                             | text          | number        |
| Yes      | numeric metric | latitude                                   | Latitude                                   | number        | number        |
| Yes      | numeric metric | longitude                                  | Longitude                                  | number        | number        |
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
series e:me59-5fac d:2011-01-01T00:00:00.000Z t:what_is_the_nature_of_this_code_violation_="Garbage in alley" t:ward=35 t:zip_code=60618 t:police_district=17 t:status=Completed t:service_request_number=11-00001271 t:community_area=16 t:type_of_service_request="Sanitation Code Violation" t:street_address="3731 N KIMBALL AVE" m:longitude=-87.71279114200225 m:latitude=41.949330379708314

series e:me59-5fac d:2011-01-01T00:00:00.000Z t:what_is_the_nature_of_this_code_violation_="Garbage in yard" t:ward=35 t:zip_code=60618 t:police_district=14 t:status=Completed t:service_request_number=11-00001278 t:community_area=21 t:type_of_service_request="Sanitation Code Violation" t:street_address="3036 N SAWYER AVE" m:longitude=-87.70875735748406 m:latitude=41.93635566035826

series e:me59-5fac d:2011-01-01T00:00:00.000Z t:what_is_the_nature_of_this_code_violation_="Construction Site Cleanliness/Fence" t:ward=42 t:zip_code=60654 t:police_district=18 t:status=Completed t:service_request_number=11-00001696 t:community_area=8 t:type_of_service_request="Sanitation Code Violation" t:street_address="600 N CLARK ST" m:longitude=-87.6311463966443 m:latitude=41.892427342273194
```

## Meta Commands

```ls
metric m:latitude p:long l:Latitude t:dataTypeName=number

metric m:longitude p:long l:Longitude t:dataTypeName=number

entity e:me59-5fac l:"311 Service Requests - Sanitation Code Complaints" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/me59-5fac

property e:me59-5fac t:meta.view v:id=me59-5fac v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Sanitation Code Complaints" v:attribution="City of Chicago"

property e:me59-5fac t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:me59-5fac t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| creation_date       | status    | completion_date     | service_request_number | type_of_service_request   | what_is_the_nature_of_this_code_violation_ | street_address       | zip_code | x_coordinate     | y_coordinate     | ward | police_district | community_area | latitude           | longitude          | 
| =================== | ========= | =================== | ====================== | ========================= | ========================================== | ==================== | ======== | ================ | ================ | ==== | =============== | ============== | ================== | ================== | 
|                     | STATUS    |                     | SERVICE REQUEST NUMBER | TYPE OF SERVICE REQUEST   | WHAT IS THE NATURE OF THIS CODE VIOLATION? | STREET ADDRESS       |          |                  |                  |      |                 |                |                    |                    | 
| 2011-01-01T00:00:00 | Completed | 2011-01-03T00:00:00 | 11-00001271            | Sanitation Code Violation | Garbage in alley                           | 3731 N KIMBALL AVE   | 60618    | 1153055.37797752 | 1924736.93532258 | 35   | 17              | 16             | 41.949330379708314 | -87.71279114200225 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-03T00:00:00 | 11-00001278            | Sanitation Code Violation | Garbage in yard                            | 3036 N SAWYER AVE    | 60618    | 1154187.13837605 | 1920016.88531821 | 35   | 14              | 21             | 41.93635566035826  | -87.70875735748406 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-03T00:00:00 | 11-00001696            | Sanitation Code Violation | Construction Site Cleanliness/Fence        | 600 N CLARK ST       | 60654    | 1175435.00739104 | 1904172.75039301 | 42   | 18              | 8              | 41.892427342273194 | -87.6311463966443  | 
| 2011-01-01T00:00:00 | Completed | 2011-01-03T00:00:00 | 11-00002161            | Sanitation Code Violation | Garbage in alley                           | 10047 S FOREST AVE   | 60628    | 1180021.3001262  | 1838414.71642729 | 9    | 5               | 49             | 41.711877328148155 | -87.61631763072438 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-03T00:00:00 | 11-00002373            | Sanitation Code Violation | Garbage in yard                            | 10648 S AVENUE B     | 60617    | 1204784.23999393 | 1834964.17507469 | 10   | 4               | 52             | 41.70180714214017  | -87.52574964355905 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-03T00:00:00 | 11-00002439            | Sanitation Code Violation | Garbage in alley                           | 8239 S EVANS AVE     | 60619    | 1182661.16289116 | 1850528.23840196 | 6    | 6               | 44             | 41.745057522351686 | -87.60627511877377 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-03T00:00:00 | 11-00002461            | Sanitation Code Violation | Garbage in yard                            | 7105 S EBERHART AVE  | 60619    | 1180806.00859116 | 1858020.5280188  | 6    | 3               | 69             | 41.76565998888494  | -87.61284272023427 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-03T00:00:00 | 11-00002612            | Sanitation Code Violation | Garbage in yard                            | 5218 S LOOMIS BLVD   | 60609    | 1167882.59619673 | 1870149.96676759 | 16   | 9               | 61             | 41.79923194833374  | -87.65986297069696 | 
| 2011-01-01T00:00:00 | Completed | 2011-01-03T00:00:00 | 11-00002751            | Sanitation Code Violation | Garbage in yard                            | 6928 S MAPLEWOOD AVE | 60629    | 1160569.4450213  | 1858625.58002816 | 18   | 8               | 66             | 41.76776155212092  | -87.68699986859862 | 
```