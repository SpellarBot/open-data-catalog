# Building and Zoning - Certificate Of Occupancy Issued - Fiscal Year 2009 through part of Fiscal Year 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-and-zoning-certificate-of-occupancy-issued-fiscal-year-2009-through-part-of-fis-2-413f1) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/kp2x-jzc9) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kp2x-jzc9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kp2x-jzc9/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | kp2x-jzc9 |
| Name | Building and Zoning - Certificate Of Occupancy Issued - Fiscal Year 2009 through part of Fiscal Year 2011 |
| Attribution | Cook County Department of Building and Zoning |
| Category | Economic Development |
| Created | 2011-09-27T17:26:09Z |
| Publication Date | 2014-10-09T22:55:30Z |

## Description

Last Updated September 2011

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| Yes      | time           | fiscal_year                     | Fiscal Year                     | text      | text        |
| Yes      | numeric metric | certificate_of_occupancy_issued | Certificate of Occupancy Issued | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kp2x-jzc9 d:2009-01-01T00:00:00.000Z m:certificate_of_occupancy_issued=70

series e:kp2x-jzc9 d:2010-01-01T00:00:00.000Z m:certificate_of_occupancy_issued=267

series e:kp2x-jzc9 d:2011-01-01T00:00:00.000Z m:certificate_of_occupancy_issued=335
```

## Meta Commands

```ls
metric m:certificate_of_occupancy_issued p:integer l:"Certificate of Occupancy Issued" t:dataTypeName=number

entity e:kp2x-jzc9 l:"Building and Zoning - Certificate Of Occupancy Issued - Fiscal Year 2009 through part of Fiscal Year 2011" t:attribution="Cook County Department of Building and Zoning" t:url=https://datacatalog.cookcountyil.gov/api/views/kp2x-jzc9

property e:kp2x-jzc9 t:meta.view v:id=kp2x-jzc9 v:category="Economic Development" v:attributionLink=http://www.cookcountyil.gov/BuildingZoning v:averageRating=0 v:name="Building and Zoning - Certificate Of Occupancy Issued - Fiscal Year 2009 through part of Fiscal Year 2011" v:attribution="Cook County Department of Building and Zoning"

property e:kp2x-jzc9 t:meta.view.license v:name="Public Domain"

property e:kp2x-jzc9 t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:kp2x-jzc9 t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| fiscal_year | certificate_of_occupancy_issued | 
| =========== | =============================== | 
| 2009        | 70                              | 
| 2010        | 267                             | 
| 2011        | 335                             | 
| Total       | 672                             | 
```