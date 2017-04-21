# Civil Unions YTD 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/civil-unions-ytd-2012-117e6) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jjmh-uh4q) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jjmh-uh4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jjmh-uh4q/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jjmh-uh4q |
| Name | Civil Unions YTD 2012 |
| Attribution | Department of Health |
| Category | Health |
| Tags | civil, unions |
| Created | 2013-01-05T01:15:35Z |
| Publication Date | 2013-01-05T01:29:53Z |

## Description

Statistics on Civil Unions

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | gender     | Gender | text      | text        |
| Yes      | numeric metric | oahu       | Oahu   | number    | number      |
| Yes      | numeric metric | hawaii     | Hawaii | number    | number      |
| Yes      | numeric metric | maui       | Maui   | number    | number      |
| Yes      | numeric metric | kauai      | Kauai  | number    | number      |
| Yes      | numeric metric | total      | Total  | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jjmh-uh4q d:2012-01-01T00:00:00.000Z t:gender=F/F m:total=437 m:kauai=59 m:maui=107 m:oahu=222 m:hawaii=49

series e:jjmh-uh4q d:2012-01-01T00:00:00.000Z t:gender=M/F m:total=21 m:kauai=3 m:maui=1 m:oahu=15 m:hawaii=2

series e:jjmh-uh4q d:2012-01-01T00:00:00.000Z t:gender=M/M m:total=265 m:kauai=27 m:maui=72 m:oahu=136 m:hawaii=30
```

## Meta Commands

```ls
metric m:oahu p:integer l:Oahu t:dataTypeName=number

metric m:hawaii p:integer l:Hawaii t:dataTypeName=number

metric m:maui p:integer l:Maui t:dataTypeName=number

metric m:kauai p:integer l:Kauai t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:jjmh-uh4q l:"Civil Unions YTD 2012" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/jjmh-uh4q

property e:jjmh-uh4q t:meta.view v:id=jjmh-uh4q v:category=Health v:attributionLink=http://www.hawaii.gov/doh v:averageRating=0 v:name="Civil Unions YTD 2012" v:attribution="Department of Health"

property e:jjmh-uh4q t:meta.view.license v:name="Creative Commons Attribution | No Derivative Works 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by-nd/3.0/legalcode v:logoUrl=images/licenses/cc30bynd.png

property e:jjmh-uh4q t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:jjmh-uh4q t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| gender | oahu | hawaii | maui | kauai | total | 
| ====== | ==== | ====== | ==== | ===== | ===== | 
| F/F    | 222  | 49     | 107  | 59    | 437   | 
| M/F    | 15   | 2      | 1    | 3     | 21    | 
| M/M    | 136  | 30     | 72   | 27    | 265   | 
```