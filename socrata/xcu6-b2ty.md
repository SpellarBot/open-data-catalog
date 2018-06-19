# Deer Kill Locations 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deer-kill-locations-2010) |
| Metadata | [Link](https://data.iowa.gov/api/views/xcu6-b2ty) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/xcu6-b2ty/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/xcu6-b2ty/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | xcu6-b2ty |
| Name | Deer Kill Locations 2010 |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | asset, inventory, deer, deer kill, maintenance, iowa dot, iowa department of transportation |
| Created | 2016-06-09T05:57:53Z |
| Publication Date | 2016-06-09T05:59:23Z |

## Description

This database is a yearly snapshot of deer kill sites as entered by Maintenance field crews. This does not necessarily correlate to crash data related to deer impacts; this is strictly deer downed within the right of way that are documented and moved by Maintenance staff. The data in this layer is for Fiscal Year 2010 only.

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
series e:xcu6-b2ty d:2009-07-10T00:00:00.000Z t:rms_county=22 t:sex=Male t:route_name="US 18 E" t:costcenter=552822 t:objectid=39482 t:district=2 m:rms_milepost=287.40000000000003 m:burial=7

series e:xcu6-b2ty d:2009-07-10T00:00:00.000Z t:rms_county=22 t:sex=Female t:route_name="IA 13 N" t:costcenter=552822 t:objectid=39483 t:district=2 m:rms_milepost=82.10000000000001 m:burial=7

series e:xcu6-b2ty d:2009-07-10T00:00:00.000Z t:rms_county=97 t:sex=Unknown t:route_name="I 29 N" t:costcenter=553602 t:objectid=39484 t:district=3 m:rms_milepost=143.8 m:burial=1
```

## Meta Commands

```ls
metric m:rms_milepost p:float l:RMS_MILEPOST d:"RMS Milepost" t:dataTypeName=number

metric m:burial p:integer l:BURIAL d:Burial t:dataTypeName=number

metric m:response_to_complaint p:long l:RESPONSE_TO_COMPLAINT d:"Response to Complaint?" t:dataTypeName=number

entity e:xcu6-b2ty l:"Deer Kill Locations 2010" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/xcu6-b2ty

property e:xcu6-b2ty t:meta.view v:id=xcu6-b2ty v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/Historic_Deer_Kill_Locations/MapServer/5 v:averageRating=0 v:name="Deer Kill Locations 2010" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:xcu6-b2ty t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:xcu6-b2ty t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| costcenter | calyear | fiscal_year | fy_quarter | dk_date    | rms_county | route_name | rms_milepost                                      | sex     | comments | latitude                                           | longitude                                          | burial_description | burial | response_to_complaint | district | objectid | 
| ========== | ======= | =========== | ========== | ========== | ========== | ========== | ================================================= | ======= | ======== | ================================================== | ================================================== | ================== | ====== | ===================== | ======== | ======== | 
| 552822     | 2009    | 2010        | 1          | 1247184000 | 22         | US 18 E    | 287.40000000000003410605131648480892181396484375  | Male    |          | 43.05182592999999968697011354379355907440185546875 | -91.4673572100000029649891075678169727325439453125 |                    | 7      |                       | 2        | 39482    | 
| 552822     | 2009    | 2010        | 1          | 1247184000 | 22         | IA 13 N    | 82.1000000000000085265128291212022304534912109375 | Female  |          | 42.9404357199999964223025017417967319488525390625  | -91.3401396299999959182969178073108196258544921875 |                    | 7      |                       | 2        | 39483    | 
| 553602     | 2009    | 2010        | 1          | 1247184000 | 97         | I 29 N     | 143.80000000000001136868377216160297393798828125  | Unknown |          | 42.435371500000002242813934572041034698486328125   | -96.3751453800000064120467868633568286895751953125 |                    | 1      |                       | 3        | 39484    | 
| 553605     | 2009    | 2010        | 1          | 1247184000 | 81         | US 71 N    | 140                                               | Female  |          | 42.3114714700000007496782927773892879486083984375  | -95.1007300100000065867789089679718017578125       |                    | 7      |                       | 3        | 39485    | 
| 552822     | 2009    | 2010        | 1          | 1247184000 | 22         | US 18 E    | 303                                               | Male    |          | 43.035829100000000835279934108257293701171875      | -91.207763099999993983146850951015949249267578125  |                    | 7      |                       | 2        | 39486    | 
| 552809     | 2009    | 2010        | 1          | 1247184000 | 7          | US 218 N   | 193.80000000000001136868377216160297393798828125  | Female  |          | 42.62677593000000086931322584860026836395263671875 | -92.4481411299999962238871376030147075653076171875 |                    | 1      |                       | 2        | 39487    | 
| 556806     | 2009    | 2010        | 1          | 1247184000 | 31         | US 151 N   | 84                                                | Female  |          | 42.335897410000001173102646134793758392333984375   | -90.8658850999999998521161614917218685150146484375 |                    | 1      |                       | 6        | 39488    | 
| 556806     | 2009    | 2010        | 1          | 1247184000 | 31         | US 151 N   | 81                                                | Female  |          | 42.31939177000000285033820546232163906097412109375 | -90.919539490000005343972588889300823211669921875  |                    | 1      |                       | 6        | 39489    | 
| 556806     | 2009    | 2010        | 1          | 1247184000 | 31         | US 61 N    | 184.700000000000017053025658242404460906982421875 | Female  |          | 42.4347707200000030525188776664435863494873046875  | -90.68242440000000215150066651403903961181640625   |                    | 1      |                       | 6        | 39490    | 
| 555662     | 2009    | 2010        | 1          | 1247184000 | 62         | US 63 N    | 62                                                | Male    |          | 41.27572971000000023877873900346457958221435546875 | -92.6445810599999930445846985094249248504638671875 |                    | 1      |                       | 5        | 39491    | 
```