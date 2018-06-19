# Licensed Stables FOR FY 2017-11102016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensed-stables-for-fy-2017-11102016) |
| Metadata | [Link](https://data.maryland.gov/api/views/ud9e-zxcs) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ud9e-zxcs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ud9e-zxcs/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ud9e-zxcs |
| Name | Licensed Stables FOR FY 2017-11102016 |
| Attribution | MD Dept. of Agriculture |
| Category | Agriculture |
| Tags | licensed stables |
| Created | 2016-11-21T17:56:20Z |
| Publication Date | 2016-11-21T17:58:48Z |

## Description

Licensed Stables in Maryland for FY 2017

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| Yes      | series tag  | stable_name         | STABLE NAME         | text      | text        |
| Yes      | series tag  | county              | COUNTY              | text      | text        |
| Yes      | series tag  | barn_city           | BARN CITY           | text      | text        |
| Yes      | series tag  | stable_phone_number | STABLE PHONE NUMBER | text      | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ud9e-zxcs d:2017-01-01T00:00:00.000Z t:barn_city="WEST RIVER" t:stable_phone_number=410-867-0380 t:county="ANNE ARUNDEL" t:stable_name="6 M FARM" m:row_number.ud9e-zxcs=1

series e:ud9e-zxcs d:2017-01-01T00:00:00.000Z t:barn_city=HARWOOD t:stable_phone_number=410-798-1941 t:county="ANNE ARUNDEL" t:stable_name="A & A STABLES" m:row_number.ud9e-zxcs=2

series e:ud9e-zxcs d:2017-01-01T00:00:00.000Z t:barn_city=CROWNSVILLE t:county="ANNE ARUNDEL" t:stable_name="ABBINGTON STABLES" m:row_number.ud9e-zxcs=3
```

## Meta Commands

```ls
metric m:row_number.ud9e-zxcs p:long l:"Row Number"

entity e:ud9e-zxcs l:"Licensed Stables FOR FY 2017-11102016" t:attribution="MD Dept. of Agriculture" t:url=https://data.maryland.gov/api/views/ud9e-zxcs

property e:ud9e-zxcs t:meta.view v:id=ud9e-zxcs v:category=Agriculture v:averageRating=0 v:name="Licensed Stables FOR FY 2017-11102016" v:attribution="MD Dept. of Agriculture"

property e:ud9e-zxcs t:meta.view.license v:name="Public Domain"

property e:ud9e-zxcs t:meta.view.owner v:id=5i5x-vf5f v:screenName=teachoaa v:displayName=teachoaa

property e:ud9e-zxcs t:meta.view.tableauthor v:id=5i5x-vf5f v:screenName=teachoaa v:roleName=editor v:displayName=teachoaa
```

## Top Records

```ls
| stable_name                 | county       | barn_city     | stable_phone_number | 
| =========================== | ============ | ============= | =================== | 
| 6 M FARM                    | ANNE ARUNDEL | WEST RIVER    | 410-867-0380        | 
| A & A STABLES               | ANNE ARUNDEL | HARWOOD       | 410-798-1941        | 
| ABBINGTON STABLES           | ANNE ARUNDEL | CROWNSVILLE   |                     | 
| BACK FIELDS FARM, LLC       | ANNE ARUNDEL | DAVIDSONVILLE |                     | 
| BADGER'S RETREAT FARM       | ANNE ARUNDEL | CHURCHTON     |                     | 
| BAYWOOD FARMS, LLC          | ANNE ARUNDEL | HARWOOD       | 410-867-7923        | 
| BLUE CLOVER EVENTING        | ANNE ARUNDEL | WEST RIVER    |                     | 
| BLUEBIRD FARM               | ANNE ARUNDEL | FRIENDSHIP    | 301-855-7844        | 
| BRIDLE PATH EQUESTRIAN, LLC | ANNE ARUNDEL | ANNAPOLIS     | 410-757-2487        | 
| BURRAGES END STABLES, LLC.  | ANNE ARUNDEL | LOTHIAN       | 443-370-8738        | 
```