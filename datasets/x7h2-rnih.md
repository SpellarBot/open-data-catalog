# Non-Fatal Shootings - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/non-fatal-shootings-2013-53e18) |
| Metadata | [Link](https://data.maryland.gov/api/views/x7h2-rnih) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/x7h2-rnih/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/x7h2-rnih/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | x7h2-rnih |
| Name | Non-Fatal Shootings - 2013 |
| Attribution | Maryland Coordination and Analysis Center |
| Category | Public Safety |
| Tags | mcac, crime, shooting, 2013 |
| Created | 2014-08-14T17:54:22Z |
| Publication Date | 2014-08-14T18:32:47Z |

## Description

2013 Non-Fatal Shootings as reported to the Maryland Coordination and Analysis Center (MCAC)

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type     | Render Type   |
| ======== | ============== | ========== | ======== | ============= | ============= |
| Yes      | series tag     | type       | Type     | text          | text          |
| Yes      | time           | date       | Date     | calendar_date | calendar_date |
| Yes      | numeric metric | time       | Time     | number        | number        |
| Yes      | series tag     | location   | Location | text          | text          |
| Yes      | series tag     | city       | City     | text          | text          |
| Yes      | series tag     | county     | County   | text          | text          |
| Yes      | series tag     | zip        | Zip      | text          | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:x7h2-rnih d:2013-08-27T00:00:00.000Z t:zip=0 t:county=Baltimore t:location="Unknown location in Baltimore County" t:type=NFS t:city=Unknown m:time=1428

series e:x7h2-rnih d:2013-01-10T00:00:00.000Z t:zip=21213 t:county="Balto. City" t:location="2000 Hoffman St." t:type=NFS t:city=Baltimore m:time=1040

series e:x7h2-rnih d:2013-12-18T00:00:00.000Z t:zip=21213 t:county="Balto. City" t:location="3200 Brendan Ave" t:type=NFS t:city=Baltimore m:time=1826
```

## Meta Commands

```ls
metric m:time p:integer l:Time d:"Time of incident" t:dataTypeName=number

entity e:x7h2-rnih l:"Non-Fatal Shootings - 2013" t:attribution="Maryland Coordination and Analysis Center" t:url=https://data.maryland.gov/api/views/x7h2-rnih

property e:x7h2-rnih t:meta.view v:id=x7h2-rnih v:category="Public Safety" v:attributionLink=http://www.mcac.maryland.gov v:averageRating=0 v:name="Non-Fatal Shootings - 2013" v:attribution="Maryland Coordination and Analysis Center"

property e:x7h2-rnih t:meta.view.owner v:id=pazu-5dxe v:screenName="Matt Sokol" v:lastNotificationSeenAt=1492112731 v:displayName="Matt Sokol"

property e:x7h2-rnih t:meta.view.tableauthor v:id=pazu-5dxe v:screenName="Matt Sokol" v:roleName=administrator v:lastNotificationSeenAt=1492112731 v:displayName="Matt Sokol"
```

## Top Records

```ls
| type | date                | time | location                             | city           | county          | zip   | 
| ==== | =================== | ==== | ==================================== | ============== | =============== | ===== | 
| NFS  | 2013-08-27T00:00:00 | 1428 | Unknown location in Baltimore County | Unknown        | Baltimore       | 0     | 
| NFS  | 2013-01-10T00:00:00 | 1040 | 2000 Hoffman St.                     | Baltimore      | Balto. City     | 21213 | 
| NFS  | 2013-12-18T00:00:00 | 1826 | 3200 Brendan Ave                     | Baltimore      | Balto. City     | 21213 | 
| NFS  | 2013-02-20T00:00:00 | 2359 | 11610 Citrine Ct                     | Glendale       | Prince George's | 20769 | 
| NFS  | 2013-10-13T00:00:00 | 100  | 214 Green St                         | Fruitland      | Wicomico        | 21826 | 
| NFS  | 2013-05-23T00:00:00 | 2222 | 1723 Hollins St                      | Baltimore      | Balto. City     | 21223 | 
| NFS  | 2013-04-19T00:00:00 | 3    | 104 Back River Neck Rd.              | Essex          | Baltimore       | 21221 | 
| NFS  | 2013-02-02T00:00:00 | 336  | 3411 Reisterstown Rd.                | Baltimore      | Balto. City     | 21215 | 
| NFS  | 2013-09-19T00:00:00 | 2235 | 5321 85th Ave                        | New Carrollton | Prince George's | 20784 | 
| NFS  | 2013-10-11T00:00:00 | 134  | 100 Penn St                          | Baltimore      | Balto. City     | 21201 | 
```