# Office Disposition- Type Contact

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/office-disposition-type-contact-bf486) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/x2zj-69gq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/x2zj-69gq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/x2zj-69gq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | x2zj-69gq |
| Name | Office Disposition- Type Contact |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, law, borough, contact, address, program |
| Created | 2013-02-12T17:11:58Z |
| Publication Date | 2013-06-21T20:07:49Z |

## Description

Department Of Probation Office Contact Details

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                             | Data Type | Render Type |
| ======== | =========== | ================================ | ================================ | ========= | =========== |
| No       | time        | :updated_at                      | updated_at                       | meta_data | meta_data   |
| Yes      | series tag  | borough_offices_disposition_type | Borough Offices Disposition Type | text      | text        |
| Yes      | series tag  | contact                          | Contact                          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:x2zj-69gq d:2013-02-12T09:12:00.000Z t:borough_offices_disposition_type="Bronx Adult Services" t:contact="(718) 537-5197" m:row_number.x2zj-69gq=1

series e:x2zj-69gq d:2013-02-12T09:12:00.000Z t:borough_offices_disposition_type="Bronx Juvenile Services" t:contact="(718) 590-3180" m:row_number.x2zj-69gq=2

series e:x2zj-69gq d:2013-02-12T09:12:00.000Z t:borough_offices_disposition_type="South Bronx NeON" t:contact="(718) 537-5197" m:row_number.x2zj-69gq=3
```

## Meta Commands

```ls
metric m:row_number.x2zj-69gq p:long l:"Row Number"

entity e:x2zj-69gq l:"Office Disposition- Type Contact" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/x2zj-69gq

property e:x2zj-69gq t:meta.view v:id=x2zj-69gq v:category="City Government" v:attributionLink=http://www.nyc.gov/html/prob/html/contact/contact.shtml v:averageRating=0 v:name="Office Disposition- Type Contact" v:attribution="Department of Probation (DOP)"

property e:x2zj-69gq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:x2zj-69gq t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | borough_offices_disposition_type | contact        | 
| =========== | ================================ | ============== | 
| 1360660320  | Bronx Adult Services             | (718) 537-5197 | 
| 1360660320  | Bronx Juvenile Services          | (718) 590-3180 | 
| 1360660320  | South Bronx NeON                 | (718) 537-5197 | 
| 1360660320  | Kings Adult Services             | (718) 802-4320 | 
| 1360660320  | Kings Juvenile Services          | (718) 802-2663 | 
| 1360660320  | Brownsville NeON                 | (718) 345-1351 | 
| 1360660320  | Manhattan Adult Services         | (212) 442-9562 | 
| 1360660320  | Manhattan Juvenile Services      | (212) 676-8521 | 
| 1360660320  | Harlem NeON                      | (212) 280-4804 | 
| 1360660320  | Queens Adult Services            | (718) 286-3045 | 
```