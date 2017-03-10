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
| Category | Environmental |
| Created | 2013-07-17T12:58:22Z |
| Publication Date | 2013-09-18T14:22:42Z |
| Rows Updated | 2013-09-18T14:14:06Z |

## Description

A list of drop-off locations to recycle waste oil, oil filters, tires, automotive batteries, metal scrap, aluminum cans, tin cans, glass, plastic, corrugated boxes newspapers and other papers.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | zone          | Zone          | text      | text        |
| Yes      | series tag     | business_name | Business Name | text      | text        |
| Yes      | series tag     | phone         | Phone         | text      | text        |
| Yes      | numeric metric | status        | status        | number    | number      |
| Yes      | series tag     | oil           | Oil           | text      | text        |
| Yes      | series tag     | oil_filter    | Oil Filter    | text      | text        |
| Yes      | series tag     | fluids        | Fluids        | text      | text        |
| Yes      | series tag     | tires         | Tires         | text      | text        |
| Yes      | series tag     | batteries     | Batteries     | text      | text        |
| Yes      | series tag     | newspapers    | Newspapers    | text      | text        |
| Yes      | series tag     | scrap_metal   | Scrap Metal   | text      | text        |
| Yes      | series tag     | aluminum      | Aluminum      | text      | text        |
| Yes      | series tag     | zip_code      | Zip Code      | text      | text        |
| No       |                | latitude      | latitude      | number    | text        |
| No       |                | longitude     | longitude     | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = longitude,latitude
```

## Data Commands

```ls
series e:qzi7-nx8g d:2013-07-17T08:39:44.000Z t:business_name="Tex-Con Oil Company" t:phone=512-444-1941 t:zip_code=78744 t:batteries=Yes t:zone=Southeast t:oil_filter=Yes t:oil=Yes m:status=1

series e:qzi7-nx8g d:2013-07-17T08:40:05.000Z t:business_name="Home Chemical Collection" t:phone=512-974-4343 t:zip_code=78744 t:batteries=Yes t:zone=Southeast t:oil_filter=Yes t:oil=Yes m:status=1

series e:qzi7-nx8g d:2013-07-17T08:40:06.000Z t:business_name="City of Austin Landfill" t:phone=512-243-1894 t:zip_code=78719 t:aluminum=Yes t:fluids=Yes t:tires=Yes t:batteries=Yes t:newspapers=Yes t:scrap_metal=Yes t:zone=Southeast t:oil_filter=Yes t:oil=Yes m:status=1
```

## Meta Commands

```ls
metric m:status p:integer l:status t:dataTypeName=number

entity e:qzi7-nx8g l:"Recycle Drop Off Locations" t:attribution="City of Austin Watershed Protection" t:url=https://data.austintexas.gov/api/views/qzi7-nx8g

property e:qzi7-nx8g t:meta.view d:2017-03-10T16:33:56.373Z v:id=qzi7-nx8g v:category=Environmental v:attributionLink=http://www.austintexas.gov/department/watershed-protection v:averageRating=0 v:name="Recycle Drop Off Locations" v:attribution="City of Austin Watershed Protection"

property e:qzi7-nx8g t:meta.view.license d:2017-03-10T16:33:56.373Z v:name="Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:qzi7-nx8g t:meta.view.owner d:2017-03-10T16:33:56.373Z v:id=2z47-i38b v:screenName="Watershed Education" v:roleName=publisher v:displayName="Watershed Education"

property e:qzi7-nx8g t:meta.view.tableauthor d:2017-03-10T16:33:56.373Z v:id=2z47-i38b v:screenName="Watershed Education" v:roleName=publisher v:displayName="Watershed Education"
```