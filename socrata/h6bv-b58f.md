# Urban Districts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/montgomery-county-urban-districts) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/h6bv-b58f) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/h6bv-b58f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/h6bv-b58f/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | h6bv-b58f |
| Name | Urban Districts |
| Category | Business |
| Tags | technology, map, geographic, business, urban, district |
| Created | 2014-12-30T20:54:06Z |
| Publication Date | 2014-12-30T20:54:26Z |

## Description

Montgomery County Urban Districts

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type  | Render Type |
| ======== | ============== | =========== | ========== | ========== | =========== |
| Yes      | time           | :updated_at | updated_at | meta_data  | meta_data   |
| Yes      | numeric metric | objectid_1  | OBJECTID_1 | number     | number      |
| Yes      | series tag     | objectid    | OBJECTID   | text       | number      |
| Yes      | series tag     | name        | NAME       | text       | text        |
| Yes      | series tag     | shape       | SHAPE      | geospatial | geospatial  |
| Yes      | numeric metric | shape_area  | SHAPE.AREA | number     | number      |
| Yes      | numeric metric | shape_len   | SHAPE.LEN  | number     | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:h6bv-b58f d:1970-01-01T00:00:00.000Z t:name=WHEATON t:objectid=1 m:shape_area=8783325.24409 m:objectid_1=1

series e:h6bv-b58f d:1970-01-01T00:00:00.000Z t:name="SILVER SPRING" t:objectid=2 m:shape_area=17046383.10026 m:objectid_1=2

series e:h6bv-b58f d:1970-01-01T00:00:00.000Z t:name=BETHESDA t:objectid=3 m:shape_area=10182508.52433 m:objectid_1=3
```

## Meta Commands

```ls
metric m:objectid_1 p:integer l:OBJECTID_1 d:OBJECTID_1 t:dataTypeName=number

metric m:shape_area l:SHAPE.AREA d:SHAPE.AREA t:dataTypeName=number

metric m:shape_len l:SHAPE.LEN d:SHAPE.LEN t:dataTypeName=number

entity e:h6bv-b58f l:"Urban Districts" t:url=https://data.montgomerycountymd.gov/api/views/h6bv-b58f

property e:h6bv-b58f t:meta.view v:id=h6bv-b58f v:category=Business v:averageRating=0 v:name="Urban Districts"

property e:h6bv-b58f t:meta.view.owner v:id=hesx-43k8 v:screenName=Dan v:roleName=publisher v:displayName=Dan

property e:h6bv-b58f t:meta.view.tableauthor v:id=hesx-43k8 v:screenName=Dan v:roleName=publisher v:displayName=Dan
```