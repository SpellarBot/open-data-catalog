# EMS - Transport Count by Destination

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-transport-count-by-destination) |
| Metadata | [Link](https://data.austintexas.gov/api/views/jtkc-5pgh) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/jtkc-5pgh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/jtkc-5pgh/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | jtkc-5pgh |
| Name | EMS - Transport Count by Destination |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | ems, transports, hospitals, atcems, destinations, patient transports |
| Created | 2015-10-29T18:35:17Z |
| Publication Date | 2015-10-29T19:39:00Z |

## Description

This table shows the count of patients transported to each system-approved receiving facility by month.  The current facilities included in the list are:

?	Cedar Park Regional Medical Center
?	Dell Children's Medical Center
?	Heart Hospital of Austin
?	Lakeway Regional Medical Center
?	North Austin Medical Center
?	Saint David's Children's Hospital
?	South Austin Medical Center
?	Saint David's Emergency Center - BeeCave
?	Saint David's Emergency Center - Cedar Park
?	Saint David's Medical Center
?	Saint David's Emergency Center - Pflugerville
?	Saint David's Round Rock Medical Center
?	Seton Medical Center Austin
?	Seton Medical Center Hays
?	Seton Medical Center Williamson
?	Seton Northwest Hospital
?	Seton Southwest Hospital
?	Scott & White Hospital - Round Rock
?	University Medical Center Brackenridge
?	Westlake Medical Center

The table includes a destination of ?Other/Missing? for cases where data is either absent, incorrect, or reflects a transport to another facility.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name             | Data Type     | Render Type   |
| ======== | ============== | ======================= | ================ | ============= | ============= |
| Yes      | numeric metric | month_key               | Month Key        | number        | number        |
| Yes      | time           | month_start_date        | Month-Year       | calendar_date | calendar_date |
| Yes      | series tag     | destination_code        | Destination Code | text          | text          |
| Yes      | series tag     | destination_description | Destination Name | text          | text          |
| Yes      | numeric metric | count_transports        | Transport Count  | number        | number        |
```

## Time Field

```ls
Value = month_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jtkc-5pgh d:2012-10-01T00:00:00.000Z t:destination_code=CPRMC t:destination_description="Cedar Park Regional Medical Center" m:count_transports=55 m:month_key=201210

series e:jtkc-5pgh d:2012-10-01T00:00:00.000Z t:destination_code=DCMC t:destination_description="Dell Children's Medical Center" m:count_transports=332 m:month_key=201210

series e:jtkc-5pgh d:2012-10-01T00:00:00.000Z t:destination_code=HHOA t:destination_description="Heart Hospital of Austin" m:count_transports=60 m:month_key=201210
```

## Meta Commands

```ls
metric m:month_key p:integer l:"Month Key" d:"Year and month for record in <yyyymm> format (e.g. 201407). This format is useful for sorting records." t:dataTypeName=number

metric m:count_transports p:integer l:"Transport Count" d:"Count of patients transported to facility during month." t:dataTypeName=number

entity e:jtkc-5pgh l:"EMS - Transport Count by Destination" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/jtkc-5pgh

property e:jtkc-5pgh t:meta.view v:id=jtkc-5pgh v:category="Public Safety" v:attributionLink=http://www.austintexas.gov/department/ems v:averageRating=0 v:name="EMS - Transport Count by Destination" v:attribution="Austin-Travis County EMS"

property e:jtkc-5pgh t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:jtkc-5pgh t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| month_key | month_start_date    | destination_code | destination_description                       | count_transports | 
| ========= | =================== | ================ | ============================================= | ================ | 
| 201210    | 2012-10-01T00:00:00 | CPRMC            | Cedar Park Regional Medical Center            | 55               | 
| 201210    | 2012-10-01T00:00:00 | DCMC             | Dell Children's Medical Center                | 332              | 
| 201210    | 2012-10-01T00:00:00 | HHOA             | Heart Hospital of Austin                      | 60               | 
| 201210    | 2012-10-01T00:00:00 | LRMC             | Lakeway Regional Medical Center               | 73               | 
| 201210    | 2012-10-01T00:00:00 | NAMC             | North Austin Medical Center                   | 728              | 
| 201210    | 2012-10-01T00:00:00 | OTH              | Other/Missing                                 | 11               | 
| 201210    | 2012-10-01T00:00:00 | SAMC             | South Austin Medical Center                   | 1205             | 
| 201210    | 2012-10-01T00:00:00 | SDB              | Saint David's Emergency Center - BeeCave      | 18               | 
| 201210    | 2012-10-01T00:00:00 | SDMC             | Saint David's Medical Center                  | 972              | 
| 201210    | 2012-10-01T00:00:00 | SDP              | Saint David's Emergency Center - Pflugerville | 28               | 
```