# Recycle Drop Off Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recycle-drop-off-locations) |
| Metadata | [Link](https://data.austintexas.gov/api/views/qzi7-nx8g) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/qzi7-nx8g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/qzi7-nx8g/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | qzi7-nx8g |
| Name | Recycle Drop Off Locations |
| Attribution | City of Austin Watershed Protection |
| Category | Environment |
| Created | 2013-07-17T12:58:22Z |
| Publication Date | 2013-09-18T14:22:42Z |

## Description

A list of drop-off locations to recycle waste oil, oil filters, tires, automotive batteries, metal scrap, aluminum cans, tin cans, glass, plastic, corrugated boxes newspapers and other papers.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | zone          | Zone          | text      | text        |
| Yes      | series tag  | business_name | Business Name | text      | text        |
| Yes      | series tag  | phone         | Phone         | text      | text        |
| Yes      | series tag  | status        | status        | text      | number      |
| Yes      | series tag  | oil           | Oil           | text      | text        |
| Yes      | series tag  | oil_filter    | Oil Filter    | text      | text        |
| Yes      | series tag  | fluids        | Fluids        | text      | text        |
| Yes      | series tag  | tires         | Tires         | text      | text        |
| Yes      | series tag  | batteries     | Batteries     | text      | text        |
| Yes      | series tag  | newspapers    | Newspapers    | text      | text        |
| Yes      | series tag  | scrap_metal   | Scrap Metal   | text      | text        |
| Yes      | series tag  | aluminum      | Aluminum      | text      | text        |
| Yes      | series tag  | zip_code      | Zip Code      | text      | text        |
| No       |             | latitude      | latitude      | number    | text        |
| No       |             | longitude     | longitude     | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:qzi7-nx8g d:2013-07-17T08:39:44.000Z t:business_name="Tex-Con Oil Company" t:oil=Yes t:oil_filter=Yes t:batteries=Yes t:zone=Southeast t:phone=512-444-1941 t:zip_code=78744 t:status=1 m:row_number.qzi7-nx8g=1

series e:qzi7-nx8g d:2013-07-17T08:40:05.000Z t:business_name="Home Chemical Collection" t:oil=Yes t:oil_filter=Yes t:batteries=Yes t:zone=Southeast t:phone=512-974-4343 t:zip_code=78744 t:status=1 m:row_number.qzi7-nx8g=2

series e:qzi7-nx8g d:2013-07-17T08:40:06.000Z t:business_name="City of Austin Landfill" t:oil_filter=Yes t:batteries=Yes t:newspapers=Yes t:aluminum=Yes t:scrap_metal=Yes t:zip_code=78719 t:oil=Yes t:zone=Southeast t:phone=512-243-1894 t:status=1 t:fluids=Yes t:tires=Yes m:row_number.qzi7-nx8g=3
```

## Meta Commands

```ls
metric m:row_number.qzi7-nx8g p:long l:"Row Number"

entity e:qzi7-nx8g l:"Recycle Drop Off Locations" t:attribution="City of Austin Watershed Protection" t:url=https://data.austintexas.gov/api/views/qzi7-nx8g

property e:qzi7-nx8g t:meta.view d:2017-09-25T07:27:27.631Z v:averageRating=0 v:name="Recycle Drop Off Locations" v:attribution="City of Austin Watershed Protection" v:attributionLink=http://www.austintexas.gov/department/watershed-protection v:id=qzi7-nx8g v:category=Environment

property e:qzi7-nx8g t:meta.view.license d:2017-09-25T07:27:27.631Z v:name="Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:qzi7-nx8g t:meta.view.owner d:2017-09-25T07:27:27.631Z v:displayName="Watershed Education" v:lastNotificationSeenAt=1504100905 v:id=2z47-i38b v:screenName="Watershed Education"

property e:qzi7-nx8g t:meta.view.tableauthor d:2017-09-25T07:27:27.631Z v:displayName="Watershed Education" v:lastNotificationSeenAt=1504100905 v:roleName=publisher v:id=2z47-i38b v:screenName="Watershed Education"
```

## Top Records

```ls
| :updated_at | zone      | business_name                    | phone        | status | oil | oil_filter | fluids | tires | batteries | newspapers | scrap_metal | aluminum | zip_code | latitude           | longitude          | 
| =========== | ========= | ================================ | ============ | ====== | === | ========== | ====== | ===== | ========= | ========== | =========== | ======== | ======== | ================== | ================== | 
| 1374050384  | Southeast | Tex-Con Oil Company              | 512-444-1941 | 1      | Yes | Yes        |        |       | Yes       |            |             |          | 78744    | 30.21197822400046  | -97.72995848699969 | 
| 1374050405  | Southeast | Home Chemical Collection         | 512-974-4343 | 1      | Yes | Yes        |        |       | Yes       |            |             |          | 78744    | 30.21303076400045  | -97.73832021699968 | 
| 1374050406  | Southeast | City of Austin Landfill          | 512-243-1894 | 1      | Yes | Yes        | Yes    | Yes   | Yes       | Yes        | Yes         | Yes      | 78719    | 30.136601191000466 | -97.67324819399965 | 
| 1374050406  | Southeast | Special Automotive Service, Inc. | 512-243-1015 | 1      | Yes | Yes        |        |       | Yes       |            |             |          | 78759    | 30.401251131000436 | -97.75333968099966 | 
| 1374050465  | South     | Lube Pit Stop                    | 512-444-8563 | 1      | Yes | Yes        |        |       | Yes       |            |             |          | 78741    | 30.23095105900046  | -97.73379059599966 | 
| 1374050264  | East      | Travis County Drop Off           | 512-473-9114 | 1      | Yes | Yes        |        |       | Yes       |            |             |          | 78704    | 30.326210362000438 | -97.6278986749997  | 
| 1374050410  | Southeast | TDs Texas Disposal Systems, Inc. | 512-243-4100 | 1      | Yes | Yes        | Yes    | Yes   | Yes       | Yes        | Yes         | Yes      | 78747    | 30.136162345000457 | -97.7587492129997  | 
| 1374050435  | South     | Volvo Clinic-River City          | 512-441-1334 | 1      | Yes | Yes        |        |       | Yes       |            |             |          | 78745    | 30.220960771000478 | -97.76516033099966 | 
| 1374050472  | South     | Advance Auto Parts               | 512-326-1166 | 1      | Yes |            |        |       |           |            |             |          | 78745    | 30.191450819000465 | -97.77308111999969 | 
| 1374050696  | South     | Quick Lube                       | 512-447-2556 | 1      | Yes | Yes        |        |       | Yes       |            |             |          | 78745    | 30.209320415000434 | -97.80440015499966 | 
```