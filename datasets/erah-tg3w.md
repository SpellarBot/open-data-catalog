# Public Defender - Appointments and Dispositions, by Type - Fiscal Year 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-defender-appointments-and-dispositions-by-type-fiscal-year-2011-b72f1) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/erah-tg3w) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/erah-tg3w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/erah-tg3w/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | erah-tg3w |
| Name | Public Defender - Appointments and Dispositions, by Type - Fiscal Year 2011 |
| Attribution | Cook County Public Defender |
| Category | Public Safety |
| Created | 2011-09-19T15:52:12Z |
| Publication Date | 2014-10-09T22:06:49Z |

## Description

Data covers December 2010 through August 2011

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | month_and_totals         | Month and Totals         | text      | text        |
| Yes      | numeric metric | felony_appointments      | Felony Appointments      | number    | number      |
| Yes      | numeric metric | felony_dispositions      | Felony Dispositions      | number    | number      |
| Yes      | numeric metric | misdemeanor_appointments | Misdemeanor Appointments | number    | number      |
| Yes      | numeric metric | misdemeanor_dispositions | Misdemeanor Dispositions | number    | number      |
| Yes      | numeric metric | juvenile_appointments    | Juvenile Appointments    | number    | number      |
| Yes      | numeric metric | juvenile_dispositions    | Juvenile Dispositions    | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:erah-tg3w d:2011-01-01T00:00:00.000Z t:month_and_totals=Dec m:juvenile_appointments=563 m:juvenile_dispositions=333 m:felony_dispositions=6266 m:misdemeanor_dispositions=13923 m:felony_appointments=4764 m:misdemeanor_appointments=19588

series e:erah-tg3w d:2011-01-01T00:00:00.000Z t:month_and_totals=Jan m:juvenile_appointments=792 m:juvenile_dispositions=464 m:felony_dispositions=6626 m:misdemeanor_dispositions=13948 m:felony_appointments=5261 m:misdemeanor_appointments=14775

series e:erah-tg3w d:2011-01-01T00:00:00.000Z t:month_and_totals=Feb m:juvenile_appointments=455 m:juvenile_dispositions=416 m:felony_dispositions=5450 m:misdemeanor_dispositions=11217 m:felony_appointments=6983 m:misdemeanor_appointments=12898
```

## Meta Commands

```ls
metric m:felony_appointments p:integer l:"Felony Appointments" t:dataTypeName=number

metric m:felony_dispositions p:integer l:"Felony Dispositions" t:dataTypeName=number

metric m:misdemeanor_appointments p:integer l:"Misdemeanor Appointments" t:dataTypeName=number

metric m:misdemeanor_dispositions p:integer l:"Misdemeanor Dispositions" t:dataTypeName=number

metric m:juvenile_appointments p:integer l:"Juvenile Appointments" t:dataTypeName=number

metric m:juvenile_dispositions p:integer l:"Juvenile Dispositions" t:dataTypeName=number

entity e:erah-tg3w l:"Public Defender - Appointments and Dispositions, by Type - Fiscal Year 2011" t:attribution="Cook County Public Defender" t:url=https://datacatalog.cookcountyil.gov/api/views/erah-tg3w

property e:erah-tg3w t:meta.view v:id=erah-tg3w v:category="Public Safety" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/public_defender%2C_law_office_of/260 v:averageRating=0 v:name="Public Defender - Appointments and Dispositions, by Type - Fiscal Year 2011" v:attribution="Cook County Public Defender"

property e:erah-tg3w t:meta.view.license v:name="Public Domain"

property e:erah-tg3w t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:erah-tg3w t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month_and_totals | felony_appointments | felony_dispositions | misdemeanor_appointments | misdemeanor_dispositions | juvenile_appointments | juvenile_dispositions | 
| ================ | =================== | =================== | ======================== | ======================== | ===================== | ===================== | 
| Dec              | 4764                | 6266                | 19588                    | 13923                    | 563                   | 333                   | 
| Jan              | 5261                | 6626                | 14775                    | 13948                    | 792                   | 464                   | 
| Feb              | 6983                | 5450                | 12898                    | 11217                    | 455                   | 416                   | 
| Mar              | 4927                | 5828                | 13146                    | 10473                    | 837                   | 499                   | 
| Apr              | 4480                | 5344                | 14652                    | 11631                    | 725                   | 527                   | 
| May              | 4067                | 5156                | 13366                    | 8482                     | 836                   | 411                   | 
| Jun              | 5402                | 5778                | 15351                    | 11106                    | 787                   | 345                   | 
| Jul              | 5195                | 6575                | 14608                    | 9859                     | 655                   | 301                   | 
| Aug              | 4814                | 4291                | 13953                    | 6421                     | 523                   | 516                   | 
| Sep              | 0                   | 0                   | 0                        | 0                        | 0                     | 0                     | 
```