# Directory Of Toilets In Public Parks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-toilets-in-public-parks-b51ce) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hjae-yuav) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hjae-yuav/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hjae-yuav/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hjae-yuav |
| Name | Directory Of Toilets In Public Parks |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Recreation |
| Tags | dpr, recreation, park, public, toilet, healthy living |
| Created | 2013-01-24T21:39:57Z |
| Publication Date | 2013-06-21T20:28:16Z |

## Description

Directory of Toilets in Public Parks

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | name                | Name                | text      | text        |
| Yes      | series tag  | location            | Location            | text      | text        |
| Yes      | series tag  | open_year_round     | Open Year-Round     | text      | text        |
| Yes      | series tag  | handicap_accessible | Handicap Accessible | text      | text        |
| Yes      | series tag  | borough             | Borough             | text      | text        |
| Yes      | series tag  | comments            | Comments            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hjae-yuav d:2013-01-24T13:39:59.000Z t:location="Glenwood Road, East 100 & East 101 streets" t:name="100% Playground" t:borough=Brooklyn t:open_year_round=Yes m:row_number.hjae-yuav=1

series e:hjae-yuav d:2013-01-24T13:39:59.000Z t:location="East 174 Street, Stratford Avenue, Bronx River Avenue" t:name="174th Street Playground" t:borough=Bronx t:open_year_round=Yes m:row_number.hjae-yuav=2

series e:hjae-yuav d:2013-01-24T13:39:59.000Z t:handicap_accessible=Yes t:location="Bronx Boulevard between East 226 and East 228 streets" t:name="227 Street Playground" t:borough=Bronx t:open_year_round=Yes m:row_number.hjae-yuav=3
```

## Meta Commands

```ls
metric m:row_number.hjae-yuav p:long l:"Row Number"

entity e:hjae-yuav l:"Directory Of Toilets In Public Parks" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/hjae-yuav

property e:hjae-yuav t:meta.view v:id=hjae-yuav v:category=Recreation v:attributionLink=http://www.nycgovparks.org/facilities/bathrooms v:averageRating=0 v:name="Directory Of Toilets In Public Parks" v:attribution="Department of Parks and Recreation (DPR)"

property e:hjae-yuav t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hjae-yuav t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | name                          | location                                              | open_year_round | handicap_accessible | borough   | comments | 
| =========== | ============================= | ===================================================== | =============== | =================== | ========= | ======== | 
| 1359034799  | 100% Playground               | Glenwood Road, East 100 & East 101 streets            | Yes             |                     | Brooklyn  |          | 
| 1359034799  | 174th Street Playground       | East 174 Street, Stratford Avenue, Bronx River Avenue | Yes             |                     | Bronx     |          | 
| 1359034799  | 227 Street Playground         | Bronx Boulevard between East 226 and East 228 streets | Yes             | Yes                 | Bronx     |          | 
| 1359034799  | Abe Lincoln                   | East 135 Street, between Madison & 5 avenues          | Yes             |                     | Manhattan |          | 
| 1359034799  | Abigail Playground            | East 156 Street, Tinton Avenue                        | No              |                     | Bronx     |          | 
| 1359034799  | Agnes Haywood Playground      | East 215 Street, Barnes Avenue, East 216 Street       | Yes             |                     | Bronx     |          | 
| 1359034799  | Albemarle Park                | Albermarle Road & Dahill Road                         | Yes             | Yes                 | Brooklyn  |          | 
| 1359034799  | Albert J. Parham Playground   | Adelphi Street, Clermont, DeKalb & Willoughby avenues | Yes             | Yes                 | Brooklyn  |          | 
| 1359034799  | Alexander Hamilton Playground | Hamilton Place, West 140 to West 141 streets          | Yes             |                     | Manhattan |          | 
| 1359034799  | Alfred E. Smith Park          | Catherine Slip, Madison & South streets               | Yes             |                     | Manhattan |          | 
```