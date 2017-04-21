# Deer Kill Locations 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deer-kill-locations-2013) |
| Metadata | [Link](https://data.iowa.gov/api/views/gjb9-cjen) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/gjb9-cjen/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/gjb9-cjen/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | gjb9-cjen |
| Name | Deer Kill Locations 2013 |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | asset, inventory, deer, deer kill, maintenance, iowa dot, iowa department of transportation |
| Created | 2016-06-09T05:51:39Z |
| Publication Date | 2016-06-09T05:53:25Z |

## Description

This database is a yearly snapshot of deer kill sites as entered by Maintenance field crews. This does not necessarily correlate to crash data related to deer impacts; this is strictly deer downed within the right of way that are documented and moved by Maintenance staff. The data in this layer is for Fiscal Year 2013 only.

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
series e:gjb9-cjen d:2012-07-06T00:00:00.000Z t:rms_county=38 t:sex=Female t:route_name="IA 14 N" t:costcenter=551607 t:objectid=64905 t:district=1 m:rms_milepost=115.5 m:burial=1

series e:gjb9-cjen d:2012-07-06T00:00:00.000Z t:rms_county=35 t:sex=Female t:route_name="I 35 N" t:costcenter=552635 t:objectid=64906 t:district=2 m:rms_milepost=175.5 m:burial=1

series e:gjb9-cjen d:2012-07-06T00:00:00.000Z t:rms_county=7 t:sex=Female t:route_name="US 218 N" t:costcenter=552807 t:objectid=64907 t:district=2 m:rms_milepost=188.8 m:burial=1
```

## Meta Commands

```ls
metric m:rms_milepost p:double l:RMS_MILEPOST d:"RMS Milepost" t:dataTypeName=number

metric m:burial p:integer l:BURIAL d:Burial t:dataTypeName=number

metric m:response_to_complaint p:long l:RESPONSE_TO_COMPLAINT d:"Response to Complaint?" t:dataTypeName=number

entity e:gjb9-cjen l:"Deer Kill Locations 2013" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/gjb9-cjen

property e:gjb9-cjen t:meta.view v:id=gjb9-cjen v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/Historic_Deer_Kill_Locations/MapServer/2 v:averageRating=0 v:name="Deer Kill Locations 2013" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:gjb9-cjen t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:gjb9-cjen t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| costcenter | calyear | fiscal_year | fy_quarter | dk_date    | rms_county | route_name | rms_milepost                                      | sex     | comments | latitude                                           | longitude                                          | burial_description | burial | response_to_complaint | district | objectid | 
| ========== | ======= | =========== | ========== | ========== | ========== | ========== | ================================================= | ======= | ======== | ================================================== | ================================================== | ================== | ====== | ===================== | ======== | ======== | 
| 551607     | 2012    | 2013        | 1          | 1341532800 | 38         | IA 14 N    | 115.5                                             | Female  |          | 42.23794654000000292626282316632568836212158203125 | -92.9045738699999930076955934055149555206298828125 |                    | 1      |                       | 1        | 64905    | 
| 552635     | 2012    | 2013        | 1          | 1341532800 | 35         | I 35 N     | 175.5                                             | Female  |          | 42.87896429999999980964275891892611980438232421875 | -93.350332750000006853952072560787200927734375     |                    | 1      |                       | 2        | 64906    | 
| 552807     | 2012    | 2013        | 1          | 1341532800 | 7          | US 218 N   | 188.80000000000001136868377216160297393798828125  | Female  |          | 42.55652350999999811165253049694001674652099609375 | -92.4249332600000030879527912475168704986572265625 |                    | 1      |                       | 2        | 64907    | 
| 556806     | 2012    | 2013        | 1          | 1341532800 | 31         | US 61 N    | 182.30000000000001136868377216160297393798828125  | Female  |          | 42.40287708000000321817424264736473560333251953125 | -90.6937827299999952401776681654155254364013671875 |                    | 1      |                       | 6        | 64908    | 
| 555659     | 2012    | 2013        | 1          | 1341532800 | 59         | US 65 N    | 28                                                | Female  |          | 40.9733609000000029709553928114473819732666015625  | -93.47095149000000446903868578374385833740234375   |                    | 1      |                       | 5        | 64909    | 
| 554608     | 2012    | 2013        | 1          | 1341532800 | 25         | I 80 E     | 112                                               | Male    |          | 41.544008009999998876082827337086200714111328125   | -93.9770515999999958012267597950994968414306640625 |                    | 1      |                       | 4        | 64910    | 
| 555856     | 2012    | 2013        | 1          | 1341532800 | 56         | US 218 N   | 10                                                | Male    |          | 40.52100799999999480860424228012561798095703125    | -91.45368270000000165964593179523944854736328125   |                    | 1      |                       | 5        | 64911    | 
| 555856     | 2012    | 2013        | 1          | 1341532800 | 89         | IA 81 N    | 1                                                 | Unknown |          | 40.6262358999999975139871821738779544830322265625  | -91.7632905899999968823976814746856689453125       |                    | 1      |                       | 5        | 64912    | 
| 556809     | 2012    | 2013        | 1          | 1341532800 | 49         | IA 64 E    | 44                                                | Unknown |          | 42.054810709999998152852640487253665924072265625   | -90.497156090000004269313649274408817291259765625  |                    | 1      |                       | 6        | 64913    | 
| 552635     | 2012    | 2013        | 1          | 1341532800 | 35         | US 65 N    | 161.700000000000017053025658242404460906982421875 | Unknown |          | 42.6479133200000006809204933233559131622314453125  | -93.20332541999999875770299695432186126708984375   |                    | 1      |                       | 2        | 64914    | 
```