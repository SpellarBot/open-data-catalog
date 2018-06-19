# Deer Kill Locations 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deer-kill-locations-2007) |
| Metadata | [Link](https://data.iowa.gov/api/views/i2pa-xk8y) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/i2pa-xk8y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/i2pa-xk8y/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | i2pa-xk8y |
| Name | Deer Kill Locations 2007 |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | asset, inventory, deer, deer kill, maintenance, iowa dot, iowa department of transportation |
| Created | 2016-06-09T06:03:05Z |
| Publication Date | 2016-06-09T06:04:32Z |

## Description

This database is a yearly snapshot of deer kill sites as entered by Maintenance field crews. This does not necessarily correlate to crash data related to deer impacts; this is strictly deer downed within the right of way that are documented and moved by Maintenance staff. The data in this layer is for Fiscal Year 2007 only.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | costcenter            | COSTCENTER            | text      | text        |
| No       |                | calyear               | CALYEAR               | number    | number      |
| No       |                | fiscal_year           | FISCAL_YEAR           | number    | number      |
| No       |                | fy_quarter            | FY_QUARTER            | number    | number      |
| Yes      | time           | dk_date               | DK_DATE               | date      | date        |
| Yes      | series tag     | rms_county            | RMS_COUNTY            | text      | number      |
| Yes      | series tag     | route_name            | ROUTE_NAME            | text      | text        |
| Yes      | numeric metric | rms_milepost          | RMS_MILEPOST          | number    | number      |
| Yes      | series tag     | sex                   | SEX                   | text      | text        |
| Yes      | series tag     | comments              | COMMENTS              | text      | text        |
| No       |                | latitude              | LATITUDE              | number    | number      |
| No       |                | longitude             | LONGITUDE             | number    | number      |
| Yes      | series tag     | burial_description    | BURIAL_DESCRIPTION    | text      | text        |
| Yes      | numeric metric | burial                | BURIAL                | number    | number      |
| Yes      | numeric metric | response_to_complaint | RESPONSE_TO_COMPLAINT | number    | number      |
| Yes      | series tag     | district              | DISTRICT              | text      | number      |
| Yes      | series tag     | objectid              | OBJECTID              | text      | number      |
```

## Time Field

```ls
Value = dk_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fiscal_year,latitude,longitude,calyear,fy_quarter
```

## Data Commands

```ls
series e:i2pa-xk8y d:2006-07-14T00:00:00.000Z t:rms_county=24 t:sex=Female t:route_name="US 59 N" t:costcenter=553612 t:objectid=8321 t:district=3 m:rms_milepost=114.10000000000001 m:burial=1

series e:i2pa-xk8y d:2006-07-14T00:00:00.000Z t:rms_county=51 t:sex=Male t:route_name="IA 1 N" t:costcenter=555851 t:objectid=8322 t:district=5 m:rms_milepost=19.2 m:burial=1

series e:i2pa-xk8y d:2006-07-14T00:00:00.000Z t:rms_county=7 t:sex=Unknown t:route_name="I 380 N" t:costcenter=552807 t:objectid=8323 t:district=2 m:rms_milepost=66 m:burial=1
```

## Meta Commands

```ls
metric m:rms_milepost p:double l:RMS_MILEPOST d:"RMS Milepost" t:dataTypeName=number

metric m:burial p:integer l:BURIAL d:Burial t:dataTypeName=number

metric m:response_to_complaint p:long l:RESPONSE_TO_COMPLAINT d:"Response to Complaint?" t:dataTypeName=number

entity e:i2pa-xk8y l:"Deer Kill Locations 2007" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/i2pa-xk8y

property e:i2pa-xk8y t:meta.view v:id=i2pa-xk8y v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/Historic_Deer_Kill_Locations/MapServer/8 v:averageRating=0 v:name="Deer Kill Locations 2007" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:i2pa-xk8y t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:i2pa-xk8y t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| costcenter | calyear | fiscal_year | fy_quarter | dk_date    | rms_county | route_name | rms_milepost                                           | sex     | comments | latitude                                           | longitude                                          | burial_description | burial | response_to_complaint | district | objectid | 
| ========== | ======= | =========== | ========== | ========== | ========== | ========== | ====================================================== | ======= | ======== | ================================================== | ================================================== | ================== | ====== | ===================== | ======== | ======== | 
| 553612     | 2006    | 2007        | 1          | 1152835200 | 24         | US 59 N    | 114.1000000000000085265128291212022304534912109375     | Female  |          | 42.1602393200000022943640942685306072235107421875  | -95.439489710000003697132342495024204254150390625  |                    | 1      |                       | 3        | 8321     | 
| 555851     | 2006    | 2007        | 1          | 1152835200 | 51         | IA 1 N     | 19.199999999999999289457264239899814128875732421875    | Male    |          | 40.9315787000000028683643904514610767364501953125  | -91.94880521999999700710759498178958892822265625   |                    | 1      |                       | 5        | 8322     | 
| 552807     | 2006    | 2007        | 1          | 1152835200 | 7          | I 380 N    | 66                                                     | Unknown |          | 42.44947361999999912995917838998138904571533203125 | -92.209229910000004792891559191048145294189453125  |                    | 1      |                       | 2        | 8323     | 
| 555851     | 2006    | 2007        | 1          | 1152835200 | 89         | IA 1 N     | 6.29999999999999982236431605997495353221893310546875   | Female  |          | 40.75932891000000068970621214248239994049072265625 | -91.9557518900000019357321434654295444488525390625 |                    | 1      |                       | 5        | 8324     | 
| 555851     | 2006    | 2007        | 1          | 1152835200 | 89         | IA 16 E    | 13.300000000000000710542735760100185871124267578125    | Unknown |          | 40.85709784000000155401721713133156299591064453125 | -92.1112432999999981575456331484019756317138671875 |                    | 1      |                       | 5        | 8325     | 
| 556603     | 2006    | 2007        | 1          | 1152835200 | 6          | US 30 E    | 220                                                    | Male    |          | 41.9642115799999970704448060132563114166259765625  | -92.2602196999999932813807390630245208740234375    |                    | 1      |                       | 6        | 8326     | 
| 555627     | 2006    | 2007        | 1          | 1152835200 | 20         | US 69 N    | 38                                                     | Female  |          | 41.00412000000000034560798667371273040771484375    | -93.76958349000000225714757107198238372802734375   |                    | 7      |                       | 5        | 8327     | 
| 555627     | 2006    | 2007        | 1          | 1152835200 | 27         | I 35 N     | 1.8000000000000000444089209850062616169452667236328125 | Female  |          | 40.59500762999999778912751935422420501708984375    | -93.9151789200000024493419914506375789642333984375 |                    | 1      |                       | 5        | 8328     | 
| 552634     | 2006    | 2007        | 1          | 1152835200 | 34         | IA 14 N    | 170.5                                                  | Unknown |          | 42.90846496000000342974090017378330230712890625    | -92.810009239999999408610165119171142578125        |                    | 1      |                       | 2        | 8329     | 
| 555854     | 2006    | 2007        | 1          | 1153008000 | 54         | IA 21 N    | 1.3000000000000000444089209850062616169452667236328125 | Female  |          | 41.18663830999999930781996226869523525238037109375 | -92.3343897200000043312684283591806888580322265625 |                    | 1      |                       | 5        | 8330     | 
```