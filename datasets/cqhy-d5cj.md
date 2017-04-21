# CCRB: Attribution of Complaints to the Housing Bureau 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-the-housing-bureau-2005-2009-ba9c0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cqhy-d5cj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cqhy-d5cj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cqhy-d5cj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cqhy-d5cj |
| Name | CCRB: Attribution of Complaints to the Housing Bureau 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-14T20:00:21Z |
| Publication Date | 2011-09-14T20:00:21Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | housing_bureau | Housing Bureau | text      | text        |
| Yes      | numeric metric | 2005           | 2005           | number    | number      |
| Yes      | numeric metric | 2006           | 2006           | number    | number      |
| Yes      | numeric metric | 2007           | 2007           | number    | number      |
| Yes      | numeric metric | 2008           | 2008           | number    | number      |
| Yes      | numeric metric | 2009           | 2009           | number    | number      |
| Yes      | numeric metric | total          | Total          | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cqhy-d5cj d:2005-01-01T00:00:00.000Z t:housing_bureau="Office of the Chief" m:2008=0 m:total=0 m:2009=0 m:2006=0 m:2007=0 m:2005=0

series e:cqhy-d5cj d:2005-01-01T00:00:00.000Z t:housing_bureau="HB Special operations Section" m:2008=6 m:total=30 m:2009=5 m:2006=11 m:2007=3 m:2005=5

series e:cqhy-d5cj d:2005-01-01T00:00:00.000Z t:housing_bureau="PSA 1" m:2008=31 m:total=156 m:2009=25 m:2006=39 m:2007=39 m:2005=22
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:cqhy-d5cj l:"CCRB: Attribution of Complaints to the Housing Bureau 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/cqhy-d5cj

property e:cqhy-d5cj t:meta.view v:id=cqhy-d5cj v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to the Housing Bureau 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:cqhy-d5cj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cqhy-d5cj t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| housing_bureau                | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ============================= | ==== | ==== | ==== | ==== | ==== | ===== | 
| Office of the Chief           | 0    | 0    | 0    | 0    | 0    | 0     | 
| HB Special operations Section | 5    | 11   | 3    | 6    | 5    | 30    | 
| PSA 1                         | 22   | 39   | 39   | 31   | 25   | 156   | 
| PSA 2                         | 49   | 48   | 43   | 47   | 56   | 243   | 
| PSA 3                         | 34   | 22   | 35   | 42   | 28   | 161   | 
| PSA 4                         | 12   | 9    | 10   | 12   | 18   | 61    | 
| PSA 5                         | 33   | 40   | 40   | 53   | 54   | 220   | 
| PSA 6                         | 32   | 22   | 23   | 15   | 12   | 104   | 
| PSA 7                         | 24   | 37   | 29   | 38   | 28   | 156   | 
| PSA 8                         | 31   | 24   | 23   | 29   | 10   | 117   | 
```