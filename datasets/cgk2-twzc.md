# Parole Board Decisions for Initial Interviews by Crime Type: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parole-board-decisions-for-initial-interviews-by-crime-type-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/cgk2-twzc) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cgk2-twzc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cgk2-twzc/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cgk2-twzc |
| Name | Parole Board Decisions for Initial Interviews by Crime Type: Beginning 2008 |
| Attribution | NYS Department of Corrections and Community Supervision |
| Category | Public Safety |
| Tags | parole board decisions, initial interviews |
| Created | 2014-01-28T20:40:53Z |
| Publication Date | 2015-11-30T16:19:59Z |

## Description

Represents Initial interview decisions made by the NYS Board of Parole by crime type and month and calendar year.

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type | Render Type |
| ======== | =========== | ========== | ========== | ========= | =========== |
| No       |             | year       | Year       | number    | number      |
| No       |             | month      | Month      | text      | text        |
| Yes      | series tag  | month_code | Month Code | text      | number      |
| Yes      | series tag  | decision   | Decision   | text      | text        |
| Yes      | series tag  | crime      | Crime      | text      | text        |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:cgk2-twzc d:2012-01-01T00:00:00.000Z t:month_code=1 t:crime="DRUG OFFENSES" t:decision=APPROVED m:row_number.cgk2-twzc=1

series e:cgk2-twzc d:2012-01-01T00:00:00.000Z t:month_code=1 t:crime="DRUG OFFENSES" t:decision=APPROVED m:row_number.cgk2-twzc=2

series e:cgk2-twzc d:2012-01-01T00:00:00.000Z t:month_code=1 t:crime="DRUG OFFENSES" t:decision=APPROVED m:row_number.cgk2-twzc=3
```

## Meta Commands

```ls
metric m:row_number.cgk2-twzc p:long l:"Row Number"

entity e:cgk2-twzc l:"Parole Board Decisions for Initial Interviews by Crime Type: Beginning 2008" t:attribution="NYS Department of Corrections and Community Supervision" t:url=https://data.ny.gov/api/views/cgk2-twzc

property e:cgk2-twzc t:meta.view v:id=cgk2-twzc v:category="Public Safety" v:attributionLink=http://www.doccs.ny.gov v:averageRating=0 v:name="Parole Board Decisions for Initial Interviews by Crime Type: Beginning 2008" v:attribution="NYS Department of Corrections and Community Supervision"

property e:cgk2-twzc t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cgk2-twzc t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cgk2-twzc t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | month   | month_code | decision | crime           | 
| ==== | ======= | ========== | ======== | =============== | 
| 2012 | JANUARY | 1          | APPROVED | DRUG OFFENSES   | 
| 2012 | JANUARY | 1          | APPROVED | DRUG OFFENSES   | 
| 2012 | JANUARY | 1          | APPROVED | DRUG OFFENSES   | 
| 2012 | JANUARY | 1          | APPROVED | DRUG OFFENSES   | 
| 2012 | JANUARY | 1          | APPROVED | DRUG OFFENSES   | 
| 2012 | JANUARY | 1          | APPROVED | DRUG OFFENSES   | 
| 2012 | JANUARY | 1          | APPROVED | DRUG OFFENSES   | 
| 2012 | JANUARY | 1          | APPROVED | DRUG OFFENSES   | 
| 2012 | JANUARY | 1          | APPROVED | DRUG OFFENSES   | 
| 2012 | JANUARY | 1          | APPROVED | LEGISLATIVE VFO | 
```