# Family & Adult Court Contact Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/family-adult-court-contact-information-bae12) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/su6u-afcg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/su6u-afcg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/su6u-afcg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | su6u-afcg |
| Name | Family & Adult Court Contact Information |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, law, contact, justice, programs, cd, community district |
| Created | 2013-02-12T17:50:04Z |
| Publication Date | 2013-06-21T20:07:16Z |

## Description

This is the contact list for the Family and Adult Court Information.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | location    | Location   | text      | text        |
| Yes      | series tag  | contact     | Contact    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:su6u-afcg d:2013-02-12T09:50:05.000Z t:location="Brooklyn Juvenile Services" t:contact="(718) 802-2663" m:row_number.su6u-afcg=1

series e:su6u-afcg d:2013-02-12T09:50:05.000Z t:location="Bronx Juvenile Services" t:contact="(718) 590-3180" m:row_number.su6u-afcg=2

series e:su6u-afcg d:2013-02-12T09:50:05.000Z t:location="Queens Juvenile Services" t:contact="(718) 657-4385" m:row_number.su6u-afcg=3
```

## Meta Commands

```ls
metric m:row_number.su6u-afcg p:long l:"Row Number"

entity e:su6u-afcg l:"Family & Adult Court Contact Information" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/su6u-afcg

property e:su6u-afcg t:meta.view v:id=su6u-afcg v:category="City Government" v:attributionLink=http://www.nyc.gov/html/prob/html/family/contact.shtml v:averageRating=0 v:name="Family & Adult Court Contact Information" v:attribution="Department of Probation (DOP)"

property e:su6u-afcg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:su6u-afcg t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | location                        | contact        | 
| =========== | =============================== | ============== | 
| 1360662605  | Brooklyn Juvenile Services      | (718) 802-2663 | 
| 1360662605  | Bronx Juvenile Services         | (718) 590-3180 | 
| 1360662605  | Queens Juvenile Services        | (718) 657-4385 | 
| 1360662605  | Manhattan Juvenile Services     | (212) 676-8521 | 
| 1360662605  | Harlem NeON                     | (212) 280-4804 | 
| 1360662605  | Staten Island Juvenile Services | (718) 556-4000 | 
| 1360662605  | Media Inquiries                 | (212) 361-8957 | 
| 1360662605  | General Inquiries               | (212) 361-8973 | 
| 1360662605  | Brooklyn Adult Services         | (718) 802-4320 | 
| 1360662605  | Queens Adult Services           | (718) 286-3045 | 
```