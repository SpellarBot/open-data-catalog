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
| Rows Updated | 2016-09-30T07:01:40Z |

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
series e:jqe8-8r6s d:2011-07-25T00:07:00.000Z t:result=negative t:species="CULEX PIPIENS" t:block="100XX W OHARE AIRPORT" t:trap_type=GRAVID t:trap=T916 t:test_id=31550 m:number_of_mosquitoes=3

series e:jqe8-8r6s d:2016-06-22T00:06:00.000Z t:result=negative t:species="CULEX RESTUANS" t:block="58XX N PULASKI RD" t:trap_type=GRAVID t:trap=T027 t:test_id=42613 m:number_of_mosquitoes=6

series e:jqe8-8r6s d:2007-07-11T03:07:41.000Z t:result=negative t:species="CULEX PIPIENS/RESTUANS" t:block="15XX W WEBSTER AVE" t:trap_type=GRAVID t:trap=T045 t:test_id=20583 m:number_of_mosquitoes=4
```

## Meta Commands

```ls
metric m:number_of_mosquitoes p:integer l:"NUMBER OF MOSQUITOES" t:dataTypeName=number

entity e:jqe8-8r6s l:"West Nile Virus (WNV) Mosquito Test Results" t:attribution="Chicago Department of Public Health" t:url=https://data.cityofchicago.org/api/views/jqe8-8r6s

property e:jqe8-8r6s t:meta.view v:id=jqe8-8r6s v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="West Nile Virus (WNV) Mosquito Test Results" v:attribution="Chicago Department of Public Health"

property e:jqe8-8r6s t:meta.view.owner v:id=pg3c-42qv v:profileImageUrlMedium=/api/users/pg3c-42qv/profile_images/THUMB v:profileImageUrlLarge=/api/users/pg3c-42qv/profile_images/LARGE v:screenName="Matt Roberts" v:profileImageUrlSmall=/api/users/pg3c-42qv/profile_images/TINY v:roleName=editor v:displayName="Matt Roberts"

property e:jqe8-8r6s t:meta.view.tableauthor v:id=pg3c-42qv v:profileImageUrlMedium=/api/users/pg3c-42qv/profile_images/THUMB v:profileImageUrlLarge=/api/users/pg3c-42qv/profile_images/LARGE v:screenName="Matt Roberts" v:profileImageUrlSmall=/api/users/pg3c-42qv/profile_images/TINY v:roleName=editor v:displayName="Matt Roberts"
```