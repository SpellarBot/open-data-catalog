# LASAN: Number of Catch Basins Cleaned

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lasan-number-of-catch-basins-cleaned) |
| Metadata | [Link](https://data.lacity.org/api/views/8a3v-f7cr) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/8a3v-f7cr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/8a3v-f7cr/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 8a3v-f7cr |
| Name | LASAN: Number of Catch Basins Cleaned |
| Category | A Livable and Sustainable City |
| Tags | lasan, bureau of sanitation, sanitation, catch basins, sewers, storm drains |
| Created | 2014-11-07T22:23:56Z |
| Publication Date | 2014-11-07T22:31:25Z |

## Description

Catch Basins cleaned is reported monthly by LA Sanitation. Fiscal year runs July - June.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| No       | time           | :updated_at                   | updated_at                    | meta_data | meta_data   |
| No       |                | fy                            | FY                            | number    | number      |
| Yes      | series tag     | month                         | Month                         | text      | text        |
| Yes      | numeric metric | fymonth                       | FYMonth                       | number    | number      |
| Yes      | numeric metric | number_of_catch_basin_cleaned | NUMBER OF CATCH BASIN CLEANED | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fy
```

## Data Commands

```ls
series e:8a3v-f7cr d:2017-01-04T18:51:09.000Z t:month=JULY m:fymonth=1 m:number_of_catch_basin_cleaned=7275

series e:8a3v-f7cr d:2017-01-04T18:51:09.000Z t:month=AUGUST m:fymonth=2 m:number_of_catch_basin_cleaned=4498

series e:8a3v-f7cr d:2017-01-04T18:51:09.000Z t:month=SEPTEMBER m:fymonth=3 m:number_of_catch_basin_cleaned=3861
```

## Meta Commands

```ls
metric m:fymonth p:integer l:FYMonth t:dataTypeName=number

metric m:number_of_catch_basin_cleaned p:integer l:"NUMBER OF CATCH BASIN CLEANED" t:dataTypeName=number

entity e:8a3v-f7cr l:"LASAN:  Number of Catch Basins Cleaned" t:url=https://data.lacity.org/api/views/8a3v-f7cr

property e:8a3v-f7cr t:meta.view v:id=8a3v-f7cr v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LASAN:  Number of Catch Basins Cleaned"

property e:8a3v-f7cr t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:8a3v-f7cr t:meta.view.owner v:id=jwvk-b9mh v:profileImageUrlMedium=/api/users/jwvk-b9mh/profile_images/THUMB v:profileImageUrlLarge=/api/users/jwvk-b9mh/profile_images/LARGE v:screenName="Public Works: Sanitation OpenData" v:profileImageUrlSmall=/api/users/jwvk-b9mh/profile_images/TINY v:displayName="Public Works: Sanitation OpenData"

property e:8a3v-f7cr t:meta.view.tableauthor v:id=jwvk-b9mh v:profileImageUrlMedium=/api/users/jwvk-b9mh/profile_images/THUMB v:profileImageUrlLarge=/api/users/jwvk-b9mh/profile_images/LARGE v:screenName="Public Works: Sanitation OpenData" v:profileImageUrlSmall=/api/users/jwvk-b9mh/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Sanitation OpenData"
```

## Top Records

```ls
| :updated_at | fy   | month     | fymonth | number_of_catch_basin_cleaned | 
| =========== | ==== | ========= | ======= | ============================= | 
| 1483555869  | 2014 | JULY      | 1       | 7275                          | 
| 1483555869  | 2014 | AUGUST    | 2       | 4498                          | 
| 1483555869  | 2014 | SEPTEMBER | 3       | 3861                          | 
| 1483555869  | 2014 | OCTOBER   | 4       | 4055                          | 
| 1483555869  | 2014 | NOVEMBER  | 5       | 3685                          | 
| 1483555869  | 2014 | DECEMBER  | 6       | 5400                          | 
| 1483555869  | 2014 | JANUARY   | 7       | 6252                          | 
| 1483555869  | 2014 | FEBRUARY  | 8       | 5991                          | 
| 1483555869  | 2014 | MARCH     | 9       | 5189                          | 
| 1483555869  | 2014 | APRIL     | 10      | 6562                          | 
```