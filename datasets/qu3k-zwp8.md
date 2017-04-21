# Deer Kill Locations 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deer-kill-locations-2006) |
| Metadata | [Link](https://data.iowa.gov/api/views/qu3k-zwp8) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/qu3k-zwp8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/qu3k-zwp8/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | qu3k-zwp8 |
| Name | Deer Kill Locations 2006 |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | asset, inventory, deer, deer kill, maintenance, iowa dot, iowa department of transportation |
| Created | 2016-06-09T06:04:47Z |
| Publication Date | 2016-06-09T06:06:19Z |

## Description

This database is a yearly snapshot of deer kill sites as entered by Maintenance field crews. This does not necessarily correlate to crash data related to deer impacts; this is strictly deer downed within the right of way that are documented and moved by Maintenance staff. The data in this layer is for Fiscal Year 2006 only.

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
series e:qu3k-zwp8 d:2005-10-21T00:00:00.000Z t:rms_county=48 t:sex=Male t:route_name="I 80 E" t:burial_description=Relocation t:costcenter=556606 t:objectid=1 t:district=6 m:rms_milepost=227.6 m:burial=7

series e:qu3k-zwp8 d:2005-10-21T00:00:00.000Z t:rms_county=9 t:sex=Male t:route_name="US 63 N" t:burial_description="Tall Grass Burial" t:costcenter=552809 t:objectid=2 t:district=2 m:rms_milepost=178 m:burial=1

series e:qu3k-zwp8 d:2005-10-21T00:00:00.000Z t:rms_county=66 t:sex=Female t:route_name="IA 9 E" t:burial_description="Tall Grass Burial" t:costcenter=552666 t:objectid=3 t:district=2 m:rms_milepost=216 m:burial=1
```

## Meta Commands

```ls
metric m:rms_milepost p:float l:RMS_MILEPOST d:"RMS Milepost" t:dataTypeName=number

metric m:burial p:integer l:BURIAL d:Burial t:dataTypeName=number

metric m:response_to_complaint p:long l:RESPONSE_TO_COMPLAINT d:"Response to Complaint?" t:dataTypeName=number

entity e:qu3k-zwp8 l:"Deer Kill Locations 2006" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/qu3k-zwp8

property e:qu3k-zwp8 t:meta.view v:id=qu3k-zwp8 v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/Historic_Deer_Kill_Locations/MapServer/9 v:averageRating=0 v:name="Deer Kill Locations 2006" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:qu3k-zwp8 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:qu3k-zwp8 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| costcenter | calyear | fiscal_year | fy_quarter | dk_date    | rms_county | route_name | rms_milepost                                        | sex     | comments | latitude                                           | longitude                                          | burial_description | burial | response_to_complaint | district | objectid | 
| ========== | ======= | =========== | ========== | ========== | ========== | ========== | =================================================== | ======= | ======== | ================================================== | ================================================== | ================== | ====== | ===================== | ======== | ======== | 
| 556606     | 2005    | 2006        | 2          | 1129852800 | 48         | I 80 E     | 227.599999999999994315658113919198513031005859375   | Male    |          | 41.68714100999999772056980873458087444305419921875 | -91.8587111199999952759753796271979808807373046875 | Relocation         | 7      |                       | 6        | 1        | 
| 552809     | 2005    | 2006        | 2          | 1129852800 | 9          | US 63 N    | 178                                                 | Male    |          | 42.70212000000000074351191869936883449554443359375 | -92.3371224899999987201226758770644664764404296875 | Tall Grass Burial  | 1      |                       | 2        | 2        | 
| 552666     | 2005    | 2006        | 2          | 1129852800 | 66         | IA 9 E     | 216                                                 | Female  |          | 43.3638384300000012672171578742563724517822265625  | -92.5770199999999903184288996271789073944091796875 | Tall Grass Burial  | 1      |                       | 2        | 3        | 
| 552666     | 2005    | 2006        | 2          | 1129852800 | 66         | US 218 N   | 243                                                 | Female  |          | 43.20461999999999846977516426704823970794677734375 | -92.73235065000000076906871981918811798095703125   | Tall Grass Burial  | 1      |                       | 2        | 4        | 
| 553607     | 2005    | 2006        | 2          | 1129852800 | 67         | I 29 N     | 107                                                 | Male    |          | 41.95968431000000009589712135493755340576171875    | -96.102680719999995062607922591269016265869140625  | Tall Grass Burial  | 1      |                       | 3        | 5        | 
| 553612     | 2005    | 2006        | 2          | 1129852800 | 24         | US 59 N    | 99.7999999999999971578290569595992565155029296875   | Male    |          | 41.97809154000000120277036330662667751312255859375 | -95.364500649999996539918356575071811676025390625  | Tall Grass Burial  | 1      |                       | 3        | 6        | 
| 554604     | 2005    | 2006        | 2          | 1129852800 | 87         | IA 2 E     | 70                                                  | Female  |          | 40.67522222000000198249836103059351444244384765625 | -94.70645247999999583043972961604595184326171875   | Tall Grass Burial  | 1      |                       | 4        | 7        | 
| 554604     | 2005    | 2006        | 2          | 1129852800 | 87         | IA 2 E     | 57                                                  | Male    |          | 40.7272522800000018605715013109147548675537109375  | -94.909559610000002294327714480459690093994140625  | Tall Grass Burial  | 1      |                       | 4        | 8        | 
| 554606     | 2005    | 2006        | 2          | 1129852800 | 2          | IA 148 N   | 31.199999999999999289457264239899814128875732421875 | Female  |          | 40.99701352000000298403392662294209003448486328125 | -94.7322115200000069989982875995337963104248046875 | Rendering Free     | 5      |                       | 4        | 9        | 
| 554606     | 2005    | 2006        | 2          | 1129852800 | 2          | IA 148 N   | 35.7000000000000028421709430404007434844970703125   | Unknown |          | 41.05085643000000317215381073765456676483154296875 | -94.7569814499999978352207108400762081146240234375 | Tall Grass Burial  | 1      |                       | 4        | 10       | 
```