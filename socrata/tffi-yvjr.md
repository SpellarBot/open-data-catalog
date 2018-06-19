# Deer Kill Locations 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deer-kill-locations-2011) |
| Metadata | [Link](https://data.iowa.gov/api/views/tffi-yvjr) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/tffi-yvjr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/tffi-yvjr/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | tffi-yvjr |
| Name | Deer Kill Locations 2011 |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | asset, inventory, deer, deer kill, maintenance, iowa dot, iowa department of transportation |
| Created | 2016-06-09T05:55:26Z |
| Publication Date | 2016-06-09T05:56:41Z |

## Description

This database is a yearly snapshot of deer kill sites as entered by Maintenance field crews. This does not necessarily correlate to crash data related to deer impacts; this is strictly deer downed within the right of way that are documented and moved by Maintenance staff. The data in this layer is for Fiscal Year 2011 only.

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
series e:tffi-yvjr d:2010-07-09T00:00:00.000Z t:rms_county=56 t:sex=Male t:route_name="IA 2 E" t:costcenter=555856 t:objectid=48480 t:district=5 m:rms_milepost=252.1 m:burial=1

series e:tffi-yvjr d:2010-07-09T00:00:00.000Z t:rms_county=56 t:sex=Male t:route_name="IA 2 E" t:costcenter=555856 t:objectid=48481 t:district=5 m:rms_milepost=257.4 m:burial=1

series e:tffi-yvjr d:2010-07-09T00:00:00.000Z t:rms_county=94 t:sex=Female t:route_name="US 169 N" t:costcenter=551611 t:objectid=48482 t:district=1 m:rms_milepost=165.5 m:burial=1
```

## Meta Commands

```ls
metric m:rms_milepost p:double l:RMS_MILEPOST d:"RMS Milepost" t:dataTypeName=number

metric m:burial p:integer l:BURIAL d:Burial t:dataTypeName=number

metric m:response_to_complaint p:long l:RESPONSE_TO_COMPLAINT d:"Response to Complaint?" t:dataTypeName=number

entity e:tffi-yvjr l:"Deer Kill Locations 2011" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/tffi-yvjr

property e:tffi-yvjr t:meta.view v:id=tffi-yvjr v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/Historic_Deer_Kill_Locations/MapServer/4 v:averageRating=0 v:name="Deer Kill Locations 2011" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:tffi-yvjr t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:tffi-yvjr t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| costcenter | calyear | fiscal_year | fy_quarter | dk_date    | rms_county | route_name | rms_milepost                                         | sex    | comments | latitude                                           | longitude                                          | burial_description | burial | response_to_complaint | district | objectid | 
| ========== | ======= | =========== | ========== | ========== | ========== | ========== | ==================================================== | ====== | ======== | ================================================== | ================================================== | ================== | ====== | ===================== | ======== | ======== | 
| 555856     | 2010    | 2011        | 1          | 1278633600 | 56         | IA 2 E     | 252.099999999999994315658113919198513031005859375    | Male   |          | 40.63129210999999685327566112391650676727294921875 | -91.4972728299999999990177457220852375030517578125 |                    | 1      |                       | 5        | 48480    | 
| 555856     | 2010    | 2011        | 1          | 1278633600 | 56         | IA 2 E     | 257.3999999999999772626324556767940521240234375      | Male   |          | 40.62673683999999951765857986174523830413818359375 | -91.399299479999996265178197063505649566650390625  |                    | 1      |                       | 5        | 48481    | 
| 551611     | 2010    | 2011        | 1          | 1278633600 | 94         | US 169 N   | 165.5                                                | Female |          | 42.60552933999999680736436857841908931732177734375 | -94.2279519300000032444586395286023616790771484375 |                    | 1      |                       | 1        | 48482    | 
| 551611     | 2010    | 2011        | 1          | 1278633600 | 94         | US 20 E    | 132                                                  | Female |          | 42.449011630000001105145202018320560455322265625   | -93.980139989999997851555235683917999267578125     |                    | 1      |                       | 1        | 48483    | 
| 551611     | 2010    | 2011        | 1          | 1278633600 | 94         | US 169 N   | 152                                                  | Female |          | 42.42096959999999938872861093841493129730224609375 | -94.1840763400000042793180909939110279083251953125 |                    | 1      |                       | 1        | 48484    | 
| 551611     | 2010    | 2011        | 1          | 1278633600 | 94         | US 169 N   | 156.5                                                | Female |          | 42.480405689999997775885276496410369873046875      | -94.2072284700000039947553887031972408294677734375 |                    | 1      |                       | 1        | 48485    | 
| 551611     | 2010    | 2011        | 1          | 1278633600 | 94         | US 169 N   | 161                                                  | Female |          | 42.54070020000000340587575919926166534423828125    | -94.2272522500000064837877289392054080963134765625 |                    | 1      |                       | 1        | 48486    | 
| 555627     | 2010    | 2011        | 1          | 1278633600 | 93         | US 65 N    | 15.2000000000000010658141036401502788066864013671875 | Female |          | 40.794575960000003078675945289433002471923828125   | -93.4993217199999975264290696941316127777099609375 |                    | 7      |                       | 5        | 48487    | 
| 555627     | 2010    | 2011        | 1          | 1278633600 | 27         | IA 2 E     | 115.6000000000000085265128291212022304534912109375   | Male   |          | 40.7317876700000027767600840888917446136474609375  | -93.9094902700000062623075791634619235992431640625 |                    | 7      |                       | 5        | 48488    | 
| 552617     | 2010    | 2011        | 1          | 1278633600 | 17         | US 18 E    | 190.900000000000005684341886080801486968994140625    | Male   |          | 43.11717202999999898338501225225627422332763671875 | -93.1084088799999989305433700792491436004638671875 |                    | 1      |                       | 2        | 48489    | 
```