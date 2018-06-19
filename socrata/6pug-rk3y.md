# CMS Location Data File

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cms-location-data-file-48051) |
| Metadata | [Link](https://data.illinois.gov/api/views/6pug-rk3y) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/6pug-rk3y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/6pug-rk3y/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 6pug-rk3y |
| Name | CMS Location Data File |
| Attribution | cms.data@illinois.gov |
| Tags | support, zip code, county, fips |
| Created | 2011-07-29T15:09:34Z |
| Publication Date | 2011-07-29T15:09:34Z |

## Description

This file contains information to allow developers to correlate data from other extracts and determine location information.  This file does not contain GIS coordinates.  Please contact cms.data@illinois.gov for questions or to report problems with this dataset.  Please see the data definition file located in the Files and Documents section for additional details.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | zipcode          | Zipcode          | text      | text        |
| Yes      | series tag  | county           | County           | text      | text        |
| Yes      | series tag  | il_county_number | Il County Number | text      | text        |
| Yes      | series tag  | fips_code        | FIPS Code        | text      | text        |
| Yes      | series tag  | county_seat      | County Seat      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6pug-rk3y d:2011-07-29T08:09:35.000Z t:il_county_number=063 t:county=MCHENRY t:zipcode=60001 t:county_seat=Woodstock t:fips_code=111 m:row_number.6pug-rk3y=1

series e:6pug-rk3y d:2011-07-29T08:09:35.000Z t:il_county_number=050 t:county=LAKE t:zipcode=60002 t:county_seat=Waukegan t:fips_code=097 m:row_number.6pug-rk3y=2

series e:6pug-rk3y d:2011-07-29T08:09:35.000Z t:il_county_number=016 t:county=COOK t:zipcode=60004 t:county_seat=Chicago t:fips_code=031 m:row_number.6pug-rk3y=3
```

## Meta Commands

```ls
metric m:row_number.6pug-rk3y p:long l:"Row Number"

entity e:6pug-rk3y l:"CMS Location Data File" t:attribution=cms.data@illinois.gov t:url=https://data.illinois.gov/api/views/6pug-rk3y

property e:6pug-rk3y t:meta.view v:id=6pug-rk3y v:averageRating=0 v:name="CMS Location Data File" v:attribution=cms.data@illinois.gov

property e:6pug-rk3y t:meta.view.owner v:id=5xuu-nbpa v:screenName="John Cunningham" v:displayName="John Cunningham"

property e:6pug-rk3y t:meta.view.tableauthor v:id=5xuu-nbpa v:screenName="John Cunningham" v:displayName="John Cunningham"
```

## Top Records

```ls
| :updated_at | zipcode | county  | il_county_number | fips_code | county_seat | 
| =========== | ======= | ======= | ================ | ========= | =========== | 
| 1311926975  | 60001   | MCHENRY | 063              | 111       | Woodstock   | 
| 1311926975  | 60002   | LAKE    | 050              | 097       | Waukegan    | 
| 1311926975  | 60004   | COOK    | 016              | 031       | Chicago     | 
| 1311926975  | 60005   | COOK    | 016              | 031       | Chicago     | 
| 1311926975  | 60006   | COOK    | 016              | 031       | Chicago     | 
| 1311926975  | 60007   | COOK    | 016              | 031       | Chicago     | 
| 1311926975  | 60008   | COOK    | 016              | 031       | Chicago     | 
| 1311926975  | 60009   | COOK    | 016              | 031       | Chicago     | 
| 1311926975  | 60010   | LAKE    | 050              | 097       | Waukegan    | 
| 1311926975  | 60010   | LAKE    | 050              | 097       | Waukegan    | 
```