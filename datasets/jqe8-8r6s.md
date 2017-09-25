# West Nile Virus (WNV) Mosquito Test Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wnv-mosquito-test-results-42116) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/jqe8-8r6s) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/jqe8-8r6s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/jqe8-8r6s/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | jqe8-8r6s |
| Name | West Nile Virus (WNV) Mosquito Test Results |
| Attribution | Chicago Department of Public Health |
| Category | Health & Human Services |
| Tags | mosquitoes, west nile virus, wnv, environmental health, public health, vector |
| Created | 2015-04-17T16:28:15Z |
| Publication Date | 2016-08-11T19:44:04Z |

## Description

List of locations and test results for pools of mosquitoes tested through the Chicago Department of Public Health Environmental Health program. The Chicago Department of Public Health maintains an environmental surveillance program for West Nile Virus (WNV).  This program includes the collection of mosquitoes from traps located throughout the city; the identification and sorting of mosquitoes collected from these traps; and the testing of specific species of mosquitoes for WNV.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| No       |                | season_year          | SEASON YEAR          | number        | text          |
| No       |                | week                 | WEEK                 | number        | text          |
| Yes      | series tag     | test_id              | TEST ID              | text          | text          |
| Yes      | series tag     | block                | BLOCK                | text          | text          |
| Yes      | series tag     | trap                 | TRAP                 | text          | text          |
| Yes      | series tag     | trap_type            | TRAP_TYPE            | text          | text          |
| Yes      | time           | test_date            | TEST DATE            | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_mosquitoes | NUMBER OF MOSQUITOES | number        | number        |
| Yes      | series tag     | result               | RESULT               | text          | text          |
| Yes      | series tag     | species              | SPECIES              | text          | text          |
| No       |                | latitude             | LATITUDE             | number        | number        |
| No       |                | longitude            | LONGITUDE            | number        | number        |
```

## Time Field

```ls
Value = test_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude,longitude,season_year,week
```

## Data Commands

```ls
series e:jqe8-8r6s d:2011-07-25T00:07:00.000Z t:result=negative t:species="CULEX PIPIENS" t:trap_type=GRAVID t:block="100XX W OHARE AIRPORT" t:trap=T916 t:test_id=31550 m:number_of_mosquitoes=3

series e:jqe8-8r6s d:2016-06-22T00:06:00.000Z t:result=negative t:species="CULEX RESTUANS" t:trap_type=GRAVID t:block="58XX N PULASKI RD" t:trap=T027 t:test_id=42613 m:number_of_mosquitoes=6

series e:jqe8-8r6s d:2007-07-11T03:07:41.000Z t:result=negative t:species="CULEX PIPIENS/RESTUANS" t:trap_type=GRAVID t:block="15XX W WEBSTER AVE" t:trap=T045 t:test_id=20583 m:number_of_mosquitoes=4
```

## Meta Commands

```ls
metric m:number_of_mosquitoes p:integer l:"NUMBER OF MOSQUITOES" t:dataTypeName=number

entity e:jqe8-8r6s l:"West Nile Virus (WNV) Mosquito Test Results" t:attribution="Chicago Department of Public Health" t:url=https://data.cityofchicago.org/api/views/jqe8-8r6s

property e:jqe8-8r6s t:meta.view d:2017-09-25T07:31:51.437Z v:averageRating=0 v:name="West Nile Virus (WNV) Mosquito Test Results" v:attribution="Chicago Department of Public Health" v:attributionLink=http://www.cityofchicago.org v:id=jqe8-8r6s v:category="Health & Human Services"

property e:jqe8-8r6s t:meta.view.owner d:2017-09-25T07:31:51.437Z v:displayName="Matt Roberts" v:profileImageUrlLarge=/api/users/pg3c-42qv/profile_images/LARGE v:profileImageUrlSmall=/api/users/pg3c-42qv/profile_images/TINY v:id=pg3c-42qv v:screenName="Matt Roberts" v:profileImageUrlMedium=/api/users/pg3c-42qv/profile_images/THUMB

property e:jqe8-8r6s t:meta.view.tableauthor d:2017-09-25T07:31:51.437Z v:displayName="Matt Roberts" v:profileImageUrlLarge=/api/users/pg3c-42qv/profile_images/LARGE v:roleName=editor v:profileImageUrlSmall=/api/users/pg3c-42qv/profile_images/TINY v:id=pg3c-42qv v:screenName="Matt Roberts" v:profileImageUrlMedium=/api/users/pg3c-42qv/profile_images/THUMB
```

## Top Records

```ls
| season_year | week | test_id | block                 | trap | trap_type | test_date           | number_of_mosquitoes | result   | species                | latitude     | longitude     | 
| =========== | ==== | ======= | ===================== | ==== | ========= | =================== | ==================== | ======== | ====================== | ============ | ============= | 
| 2011        | 29   | 31550   | 100XX W OHARE AIRPORT | T916 | GRAVID    | 2011-07-25T00:07:00 | 3                    | negative | CULEX PIPIENS          |              |               | 
| 2016        | 25   | 42613   | 58XX N PULASKI RD     | T027 | GRAVID    | 2016-06-22T00:06:00 | 6                    | negative | CULEX RESTUANS         | 41.986319851 | -87.728378456 | 
| 2007        | 27   | 20583   | 15XX W WEBSTER AVE    | T045 | GRAVID    | 2007-07-11T03:07:41 | 4                    | negative | CULEX PIPIENS/RESTUANS | 41.921704574 | -87.666963235 | 
| 2009        | 38   | 28275   | 5XX S CENTRAL AVE     | T031 | GRAVID    | 2009-09-25T00:09:00 | 4                    | negative | CULEX PIPIENS          | 41.872872862 | -87.764736532 | 
| 2011        | 34   | 32254   | 58XX N PULASKI RD     | T027 | GRAVID    | 2011-08-26T00:08:00 | 2                    | negative | CULEX RESTUANS         | 41.986319851 | -87.728378456 | 
| 2012        | 30   | 34127   | 24XX E 105TH ST       | T128 | GRAVID    | 2012-07-27T00:07:00 | 50                   | positive | CULEX PIPIENS/RESTUANS | 41.704687214 | -87.564235562 | 
| 2015        | 29   | 41361   | 100XX W OHARE AIRPORT | T905 | GRAVID    | 2015-07-23T00:07:00 | 34                   | negative | CULEX RESTUANS         |              |               | 
| 2013        | 23   | 35546   | 35XX W 51ST ST        | T062 | GRAVID    | 2013-06-07T00:06:00 | 2                    | negative | CULEX PIPIENS/RESTUANS | 41.800597087 | -87.711730345 | 
| 2014        | 34   | 39742   | 100XX W OHARE AIRPORT | T916 | GRAVID    | 2014-08-21T00:08:00 | 31                   | positive | CULEX PIPIENS/RESTUANS |              |               | 
| 2013        | 29   | 36401   | 100XX W OHARE AIRPORT | T912 | GRAVID    | 2013-07-19T00:07:00 | 50                   | negative | CULEX PIPIENS/RESTUANS |              |               | 
```