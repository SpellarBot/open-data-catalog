# CCRB: Attribution of Complaints to the Organized Crime Control Bureau 2005 ? 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-the-organized-crime-control-bureau-2005-2009-47d92) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/v3a6-muuw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/v3a6-muuw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/v3a6-muuw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | v3a6-muuw |
| Name | CCRB: Attribution of Complaints to the Organized Crime Control Bureau 2005 ? 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-14T22:31:21Z |
| Publication Date | 2011-09-14T22:31:21Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | organized_crime_control_bureau | Organized Crime Control Bureau | text      | text        |
| Yes      | numeric metric | 2005                           | 2005                           | number    | number      |
| Yes      | numeric metric | 2006                           | 2006                           | number    | number      |
| Yes      | numeric metric | 2007                           | 2007                           | number    | number      |
| Yes      | numeric metric | 2008                           | 2008                           | number    | number      |
| Yes      | numeric metric | 2009                           | 2009                           | number    | number      |
| Yes      | numeric metric | total                          | Total                          | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v3a6-muuw d:2005-01-01T00:00:00.000Z t:organized_crime_control_bureau="Queens Narcotics" m:2008=57 m:total=201 m:2009=27 m:2006=31 m:2007=48 m:2005=38

series e:v3a6-muuw d:2005-01-01T00:00:00.000Z t:organized_crime_control_bureau="Manhattan North Narcotics" m:2008=36 m:total=200 m:2009=45 m:2006=32 m:2007=40 m:2005=47

series e:v3a6-muuw d:2005-01-01T00:00:00.000Z t:organized_crime_control_bureau="Manhattan South Narcotics" m:2008=17 m:total=68 m:2009=13 m:2006=12 m:2007=11 m:2005=15
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:v3a6-muuw l:"CCRB: Attribution of Complaints to the Organized Crime Control Bureau 2005 ? 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/v3a6-muuw

property e:v3a6-muuw t:meta.view v:id=v3a6-muuw v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to the Organized Crime Control Bureau 2005 ? 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:v3a6-muuw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:v3a6-muuw t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| organized_crime_control_bureau | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ============================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| Queens Narcotics               | 38   | 31   | 48   | 57   | 27   | 201   | 
| Manhattan North Narcotics      | 47   | 32   | 40   | 36   | 45   | 200   | 
| Manhattan South Narcotics      | 15   | 12   | 11   | 17   | 13   | 68    | 
| Bronx Narcotics                | 49   | 49   | 97   | 64   | 66   | 325   | 
| Staten Island Narcotics        | 11   | 15   | 10   | 19   | 18   | 73    | 
| Brooklyn South Narcotics       | 60   | 53   | 87   | 97   | 47   | 344   | 
| Brooklyn North Narcotics       | 41   | 54   | 73   | 45   | 31   | 244   | 
| Narcotics                      | 5    | 4    | 1    | 1    | 2    | 13    | 
| Auto Crime                     | 2    | 3    | 3    | 3    | 1    | 12    | 
| Vice Enforcement               | 24   | 20   | 5    | 15   | 13   | 77    | 
```