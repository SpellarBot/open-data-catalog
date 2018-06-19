# MDAg Agronomic

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mdag-agronomic) |
| Metadata | [Link](https://data.maryland.gov/api/views/shum-gk8c) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/shum-gk8c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/shum-gk8c/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | shum-gk8c |
| Name | MDAg Agronomic |
| Attribution | MDA |
| Category | Agriculture |
| Tags | mda, chesapeake bay, tmdl |
| Created | 2016-03-04T14:44:42Z |
| Publication Date | 2016-07-15T13:56:30Z |

## Description

Annual implementation of agronomic BMPs in Maryland for 2010-2015, including Nutrient Management. Records available by county only.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | bmp_name       | BMP Name       | text      | text        |
| Yes      | numeric metric | annual_extent  | Annual Extent  | number    | number      |
| Yes      | series tag     | unit           | Unit           | text      | text        |
| Yes      | series tag     | watershed_name | Watershed Name | text      | text        |
| Yes      | series tag     | county         | County         | text      | text        |
| Yes      | time           | year           | Year           | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:shum-gk8c d:2012-01-01T00:00:00.000Z t:unit=Acres/year t:county=Allegany t:bmp_name="Conservation Tillage" m:annual_extent=149.38

series e:shum-gk8c d:2012-01-01T00:00:00.000Z t:unit=Acres/year t:county="Anne Arundel" t:bmp_name="Conservation Tillage" m:annual_extent=7999

series e:shum-gk8c d:2012-01-01T00:00:00.000Z t:unit=Acres/year t:county=Baltimore t:bmp_name="Conservation Tillage" m:annual_extent=23804.5
```

## Meta Commands

```ls
metric m:annual_extent p:float l:"Annual Extent" t:dataTypeName=number

entity e:shum-gk8c l:"MDAg Agronomic" t:attribution=MDA t:url=https://data.maryland.gov/api/views/shum-gk8c

property e:shum-gk8c t:meta.view v:id=shum-gk8c v:category=Agriculture v:averageRating=0 v:name="MDAg Agronomic" v:attribution=MDA

property e:shum-gk8c t:meta.view.license v:name="Public Domain"

property e:shum-gk8c t:meta.view.owner v:id=hcsr-zg76 v:screenName="Alisha Mulkey" v:displayName="Alisha Mulkey"

property e:shum-gk8c t:meta.view.tableauthor v:id=hcsr-zg76 v:screenName="Alisha Mulkey" v:roleName=editor v:displayName="Alisha Mulkey"
```

## Top Records

```ls
| bmp_name             | annual_extent | unit       | watershed_name | county       | year | 
| ==================== | ============= | ========== | ============== | ============ | ==== | 
| Conservation Tillage | 149.38        | Acres/year |                | Allegany     | 2012 | 
| Conservation Tillage | 7999          | Acres/year |                | Anne Arundel | 2012 | 
| Conservation Tillage | 23804.5       | Acres/year |                | Baltimore    | 2012 | 
| Conservation Tillage | 6568.87       | Acres/year |                | Calvert      | 2012 | 
| Conservation Tillage | 71949.2       | Acres/year |                | Caroline     | 2012 | 
| Conservation Tillage | 52742.27      | Acres/year |                | Carroll      | 2012 | 
| Conservation Tillage | 44165.53      | Acres/year |                | Cecil        | 2012 | 
| Conservation Tillage | 9791.97       | Acres/year |                | Charles      | 2012 | 
| Conservation Tillage | 88100.8       | Acres/year |                | Dorchester   | 2012 | 
| Conservation Tillage | 33642.64      | Acres/year |                | Frederick    | 2012 | 
```