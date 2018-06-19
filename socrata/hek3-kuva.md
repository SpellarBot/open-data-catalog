# Percent of Short-term Rentals Issued by Census Tract

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percent-of-short-term-rentals-issued-by-census-tract) |
| Metadata | [Link](https://data.austintexas.gov/api/views/hek3-kuva) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/hek3-kuva/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/hek3-kuva/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | hek3-kuva |
| Name | Percent of Short-term Rentals Issued by Census Tract |
| Attribution | City of Austin |
| Category | Permitting |
| Tags | short-term rental, census tract, rental, license |
| Created | 2013-04-05T15:48:03Z |
| Publication Date | 2013-10-31T19:01:29Z |

## Description

This data demonstrates the number of short term rental licenses that have been issued in each census tract in Austin. There is a 3 percent cap on the number of short-term rentals permitted. The Licenses Remaining column shows how many licenses are available in that census tract.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | numeric metric | census_tract       | Census Tract       | number    | number      |
| Yes      | numeric metric | 3_cap              | 3% Cap             | number    | number      |
| Yes      | numeric metric | licenses_issued    | Licenses Issued    | number    | number      |
| Yes      | numeric metric | percent_issued     | Percent Issued     | percent   | percent     |
| Yes      | numeric metric | licenses_remaining | Licenses Remaining | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hek3-kuva d:2013-04-25T14:26:08.000Z m:percent_issued=100 m:licenses_issued=15 m:licenses_remaining=0 m:census_tract=14.01 m:3_cap=15

series e:hek3-kuva d:2013-04-25T14:26:08.000Z m:percent_issued=50 m:licenses_issued=1 m:licenses_remaining=1 m:census_tract=11 m:3_cap=2

series e:hek3-kuva d:2013-04-25T14:26:08.000Z m:percent_issued=12 m:licenses_issued=3 m:licenses_remaining=22 m:census_tract=16.05 m:3_cap=25
```

## Meta Commands

```ls
metric m:census_tract p:float l:"Census Tract" t:dataTypeName=number

metric m:3_cap p:integer l:"3% Cap" t:dataTypeName=number

metric m:licenses_issued p:integer l:"Licenses Issued" t:dataTypeName=number

metric m:percent_issued p:integer l:"Percent Issued" t:dataTypeName=percent

metric m:licenses_remaining p:integer l:"Licenses Remaining" t:dataTypeName=number

entity e:hek3-kuva l:"Percent of Short-term Rentals Issued by Census Tract" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/hek3-kuva

property e:hek3-kuva t:meta.view v:id=hek3-kuva v:category=Permitting v:attributionLink=http://www.austintexas.gov/str v:averageRating=0 v:name="Percent of Short-term Rentals Issued by Census Tract" v:attribution="City of Austin"

property e:hek3-kuva t:meta.view.license v:name="Public Domain"

property e:hek3-kuva t:meta.view.owner v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:displayName=AustinGo

property e:hek3-kuva t:meta.view.tableauthor v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo
```

## Top Records

```ls
| :updated_at | census_tract | 3_cap | licenses_issued | percent_issued | licenses_remaining | 
| =========== | ============ | ===== | =============== | ============== | ================== | 
| 1366899968  | 14.01        | 15    | 15              | 100            | 0                  | 
| 1366899968  | 11           | 2     | 1               | 50             | 1                  | 
| 1366899968  | 16.05        | 25    | 3               | 12             | 22                 | 
| 1366899968  | 2.06         | 24    | 2               | 8              | 22                 | 
| 1366899968  | 18.17        | 24    | 2               | 8              | 22                 | 
| 1366899968  | 3.07         | 15    | 1               | 7              | 14                 | 
| 1366899968  | 20.02        | 32    | 2               | 6              | 30                 | 
| 1366899968  | 15.05        | 42    | 2               | 5              | 40                 | 
| 1366899968  | 4.01         | 23    | 1               | 4              | 22                 | 
| 1366899968  | 17.29        | 39    | 1               | 3              | 38                 | 
```