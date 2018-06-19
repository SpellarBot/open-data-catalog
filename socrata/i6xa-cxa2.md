# Deer Kill Locations 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deer-kill-locations-2009) |
| Metadata | [Link](https://data.iowa.gov/api/views/i6xa-cxa2) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/i6xa-cxa2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/i6xa-cxa2/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | i6xa-cxa2 |
| Name | Deer Kill Locations 2009 |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | asset, inventory, deer, deer kill, maintenance, iowa dot, iowa department of transportation |
| Created | 2016-06-09T05:59:41Z |
| Publication Date | 2016-06-09T06:01:15Z |

## Description

This database is a yearly snapshot of deer kill sites as entered by Maintenance field crews. This does not necessarily correlate to crash data related to deer impacts; this is strictly deer downed within the right of way that are documented and moved by Maintenance staff. The data in this layer is for Fiscal Year 2009 only.

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
series e:i6xa-cxa2 d:2008-07-11T00:00:00.000Z t:rms_county=40 t:sex=Female t:route_name="US 20 E" t:costcenter=551609 t:objectid=29498 t:district=1 m:rms_milepost=150 m:burial=1

series e:i6xa-cxa2 d:2008-07-11T00:00:00.000Z t:rms_county=38 t:sex=Female t:route_name="US 20 E" t:costcenter=551607 t:objectid=29499 t:district=1 m:rms_milepost=184.3 m:burial=1

series e:i6xa-cxa2 d:2008-07-11T00:00:00.000Z t:rms_county=22 t:sex=Female t:route_name="US 52 N" t:costcenter=552822 t:objectid=29500 t:district=2 m:rms_milepost=91.3 m:burial=1
```

## Meta Commands

```ls
metric m:rms_milepost p:double l:RMS_MILEPOST d:"RMS Milepost" t:dataTypeName=number

metric m:burial p:integer l:BURIAL d:Burial t:dataTypeName=number

metric m:response_to_complaint p:long l:RESPONSE_TO_COMPLAINT d:"Response to Complaint?" t:dataTypeName=number

entity e:i6xa-cxa2 l:"Deer Kill Locations 2009" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/i6xa-cxa2

property e:i6xa-cxa2 t:meta.view d:2017-06-09T13:53:04.725Z v:id=i6xa-cxa2 v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/Historic_Deer_Kill_Locations/MapServer/6 v:averageRating=0 v:name="Deer Kill Locations 2009" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:i6xa-cxa2 t:meta.view.owner d:2017-06-09T13:53:04.725Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:i6xa-cxa2 t:meta.view.tableauthor d:2017-06-09T13:53:04.725Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| costcenter | calyear | fiscal_year | fy_quarter | dk_date    | rms_county | route_name | rms_milepost                                      | sex     | comments | latitude                                           | longitude                                          | burial_description | burial | response_to_complaint | district | objectid | 
| ========== | ======= | =========== | ========== | ========== | ========== | ========== | ================================================= | ======= | ======== | ================================================== | ================================================== | ================== | ====== | ===================== | ======== | ======== | 
| 551609     | 2008    | 2009        | 1          | 1215734400 | 40         | US 20 E    | 150                                               | Female  |          | 42.44888920999999726291207480244338512420654296875 | -93.628240099999999301871866919100284576416015625  |                    | 1      |                       | 1        | 29498    | 
| 551607     | 2008    | 2009        | 1          | 1215734400 | 38         | US 20 E    | 184.30000000000001136868377216160297393798828125  | Female  |          | 42.462119139999998651546775363385677337646484375   | -92.99020099000000527666998095810413360595703125   |                    | 1      |                       | 1        | 29499    | 
| 552822     | 2008    | 2009        | 1          | 1215734400 | 22         | US 52 N    | 91.2999999999999971578290569595992565155029296875 | Female  |          | 42.82344262000000156831447384320199489593505859375 | -91.1712893699999966656832839362323284149169921875 |                    | 1      |                       | 2        | 29500    | 
| 554603     | 2008    | 2009        | 1          | 1215734400 | 5          | US 71 N    | 70                                                | Female  |          | 41.52099399000000090609319158829748630523681640625 | -94.9384188700000066774009610526263713836669921875 |                    | 1      |                       | 4        | 29501    | 
| 554609     | 2008    | 2009        | 1          | 1215734400 | 1          | IA 92 E    | 79.5                                              | Female  |          | 41.303503890000001774751581251621246337890625      | -94.4860239199999938364271656610071659088134765625 |                    | 1      |                       | 4        | 29502    | 
| 555856     | 2008    | 2009        | 1          | 1215734400 | 56         | US 61 N    | 12.5                                              | Male    |          | 40.547349470000000337677192874252796173095703125   | -91.428347669999993740930221974849700927734375     |                    | 1      |                       | 5        | 29503    | 
| 552641     | 2008    | 2009        | 1          | 1215734400 | 41         | US 18 E    | 156.80000000000001136868377216160297393798828125  | Female  |          | 43.1047197999999980311258696019649505615234375     | -93.716311880000006340196705423295497894287109375  |                    | 1      |                       | 2        | 29504    | 
| 552641     | 2008    | 2009        | 1          | 1215734400 | 41         | US 69 N    | 196.200000000000017053025658242404460906982421875 | Male    |          | 43.142317689999998719940776936709880828857421875   | -93.6360713499999945952367852441966533660888671875 |                    | 1      |                       | 2        | 29505    | 
| 551612     | 2008    | 2009        | 1          | 1215734400 | 94         | US 169 N   | 137.700000000000017053025658242404460906982421875 | Female  |          | 42.2678539099999994732570485211908817291259765625  | -94.1119619999999912351995590142905712127685546875 |                    | 1      |                       | 1        | 29506    | 
| 555627     | 2008    | 2009        | 1          | 1215734400 | 93         | IA 2 E     | 146                                               | Unknown |          | 40.7570417700000007243943400681018829345703125     | -93.34691983999999820298398844897747039794921875   |                    | 1      |                       | 5        | 29507    | 
```