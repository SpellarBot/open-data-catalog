# Directory Of DOP Family & Adult Court Contact Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-dop-family-adult-court-contact-information-a54b0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/f46j-m4iq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/f46j-m4iq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/f46j-m4iq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | f46j-m4iq |
| Name | Directory Of DOP Family & Adult Court Contact Information |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, family, adult, court, contact, information |
| Created | 2013-02-07T14:57:01Z |
| Publication Date | 2013-06-21T20:09:11Z |

## Description

List of DOP Family and Adult Court Contact Information

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
series e:f46j-m4iq d:2013-02-07T06:57:02.000Z t:location="Brooklyn Juvenile Services" t:contact="(718) 802-2663" m:row_number.f46j-m4iq=1

series e:f46j-m4iq d:2013-02-07T06:57:02.000Z t:location="Bronx Juvenile Services" t:contact="(718) 590-3180" m:row_number.f46j-m4iq=2

series e:f46j-m4iq d:2013-02-07T06:57:02.000Z t:location="Queens Juvenile Services" t:contact="(718) 657-4385" m:row_number.f46j-m4iq=3
```

## Meta Commands

```ls
metric m:row_number.f46j-m4iq p:long l:"Row Number"

entity e:f46j-m4iq l:"Directory Of DOP Family & Adult Court Contact Information" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/f46j-m4iq

property e:f46j-m4iq t:meta.view v:id=f46j-m4iq v:category="City Government" v:attributionLink=http://www.nyc.gov/html/prob/html/family/contact.shtml v:averageRating=0 v:name="Directory Of DOP Family & Adult Court Contact Information" v:attribution="Department of Probation (DOP)"

property e:f46j-m4iq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:f46j-m4iq t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | location                        | contact        | 
| =========== | =============================== | ============== | 
| 1360220222  | Brooklyn Juvenile Services      | (718) 802-2663 | 
| 1360220222  | Bronx Juvenile Services         | (718) 590-3180 | 
| 1360220222  | Queens Juvenile Services        | (718) 657-4385 | 
| 1360220222  | Manhattan Juvenile Services     | (212) 676-8521 | 
| 1360220222  | Harlem NeON                     | (212) 280-4804 | 
| 1360220222  | Staten Island Juvenile Services | (718) 556-4000 | 
| 1360220222  | Media Inquiries                 | (212) 361-8957 | 
| 1360220222  | General Inquiries               | (212) 361-8973 | 
| 1360220222  | Brooklyn Adult Services         | (718) 802-4320 | 
| 1360220222  | Queens Adult Services           | (718) 286-3045 | 
```