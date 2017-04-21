# City of Colfax: Multifamily Complexes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-colfax-multifamily-complexes) |
| Metadata | [Link](https://data.wa.gov/api/views/axje-r4js) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/axje-r4js/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/axje-r4js/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | axje-r4js |
| Name | City of Colfax: Multifamily Complexes |
| Attribution | City of Colfax, Washington |
| Category | Demographics |
| Tags | colfax, planning, apartments, multifamily, housing |
| Created | 2015-04-10T15:44:05Z |
| Publication Date | 2015-04-10T15:47:11Z |

## Description

This data file has a list of all multifamily properties with numbers of units in the City of Colfax, Washington

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| No       |                | service_address | Service Address | text      | text        |
| Yes      | numeric metric | units           | Units           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = service_address
```

## Data Commands

```ls
series e:axje-r4js d:2015-04-10T08:44:09.000Z m:units=25

series e:axje-r4js d:2015-04-10T08:44:09.000Z m:units=4

series e:axje-r4js d:2015-04-10T08:44:09.000Z m:units=2
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

entity e:axje-r4js l:"City of Colfax: Multifamily Complexes" t:attribution="City of Colfax, Washington" t:url=https://data.wa.gov/api/views/axje-r4js

property e:axje-r4js t:meta.view v:id=axje-r4js v:category=Demographics v:attributionLink=http://www.Colfaxwa.org v:averageRating=0 v:name="City of Colfax: Multifamily Complexes" v:attribution="City of Colfax, Washington"

property e:axje-r4js t:meta.view.license v:name="Public Domain"

property e:axje-r4js t:meta.view.owner v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:displayName="Mike Rizzitiello"

property e:axje-r4js t:meta.view.tableauthor v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:roleName=editor v:displayName="Mike Rizzitiello"
```

## Top Records

```ls
| :updated_at | service_address        | units | 
| =========== | ====================== | ===== | 
| 1428655449  | (c) N West Trailer Crt | 25    | 
| 1428655449  | (d) East Trailer Crt   | 4     | 
| 1428655449  | Bellinger, N 803       | 2     | 
| 1428655449  | Cedar 1708             | 8     | 
| 1428655449  | Cedar, N 1615          | 3     | 
| 1428655449  | Clay, N 1110           | 4     | 
| 1428655449  | Cooper, E 312          | 2     | 
| 1428655449  | Cooper, W 211          | 4     | 
| 1428655449  | Cooper, W 218          | 2     | 
| 1428655449  | East S 1004 Apt 2      | 6     | 
```