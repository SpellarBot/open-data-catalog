# NYC Council Constituent Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-council-constituent-services) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/b9km-gdpy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/b9km-gdpy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/b9km-gdpy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | b9km-gdpy |
| Name | NYC Council Constituent Services |
| Attribution | New York City Council (NYCC) |
| Category | City Government |
| Tags | stat, council, complaints, requests, city countil, constituent |
| Created | 2016-02-24T21:17:54Z |
| Publication Date | 2017-04-20T18:17:26Z |

## Description

The dataset comes from CouncilStat, which is used by many NYC Council district offices to enter and track constituent cases that can range from issues around affordable housing, to potholes and pedestrian safety. This dataset aggregates the information that individual staff have input. However, district staffs handle a wide range of complex issues. Each offices uses the program differently, and thus records cases, differently and so comparisons between accounts may be difficult. Not all offices use the program. For more info - http://labs.council.nyc/districts/data/

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | unique_key      | UNIQUE_KEY      | text          | text          |
| Yes      | series tag  | account         | ACCOUNT         | text          | text          |
| Yes      | time        | opendate        | OPENDATE        | calendar_date | calendar_date |
| Yes      | series tag  | complaint_type  | COMPLAINT_TYPE  | text          | text          |
| Yes      | series tag  | descriptor      | DESCRIPTOR      | text          | text          |
| Yes      | series tag  | zip             | ZIP             | text          | text          |
| Yes      | series tag  | borough         | BOROUGH         | text          | text          |
| Yes      | series tag  | city            | CITY            | text          | text          |
| Yes      | series tag  | council_dist    | COUNCIL_DIST    | text          | text          |
| Yes      | series tag  | community_board | COMMUNITY_BOARD | text          | text          |
| No       |             | closedate       | CLOSEDATE       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = opendate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = closedate
```

## Data Commands

```ls
series e:b9km-gdpy d:2015-01-02T00:00:00.000Z t:zip=11220 t:council_dist=NYCC38 t:descriptor="Senior Centers" t:complaint_type=Aging t:account=NYCC01 t:unique_key=NYCC01506329 t:borough=Brooklyn t:community_board="07 Brooklyn" t:city=Brooklyn m:row_number.b9km-gdpy=1

series e:b9km-gdpy d:2015-01-04T00:00:00.000Z t:zip=11373 t:council_dist=NYCC21 t:complaint_type=Aging t:account=NYCC01 t:unique_key=NYCC01506331 t:borough=Queens t:community_board="04 Queens" t:city=Elmhurst m:row_number.b9km-gdpy=2

series e:b9km-gdpy d:2015-01-04T00:00:00.000Z t:zip=11373 t:council_dist=NYCC21 t:complaint_type=Aging t:account=NYCC01 t:unique_key=NYCC01506332 t:borough=Queens t:community_board="04 Queens" t:city=Elmhurst m:row_number.b9km-gdpy=3
```

## Meta Commands

```ls
metric m:row_number.b9km-gdpy p:long l:"Row Number"

entity e:b9km-gdpy l:"NYC Council Constituent Services" t:attribution="New York City Council (NYCC)" t:url=https://data.cityofnewyork.us/api/views/b9km-gdpy

property e:b9km-gdpy t:meta.view v:id=b9km-gdpy v:category="City Government" v:averageRating=0 v:name="NYC Council Constituent Services" v:attribution="New York City Council (NYCC)"

property e:b9km-gdpy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:b9km-gdpy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| unique_key   | account | opendate            | complaint_type        | descriptor                 | zip   | borough   | city     | council_dist | community_board | closedate           | 
| ============ | ======= | =================== | ===================== | ========================== | ===== | ========= | ======== | ============ | =============== | =================== | 
| NYCC01506329 | NYCC01  | 2015-01-02T00:00:00 | Aging                 | Senior Centers             | 11220 | Brooklyn  | Brooklyn | NYCC38       | 07 Brooklyn     | 2015-01-14T00:00:00 | 
| NYCC01506331 | NYCC01  | 2015-01-04T00:00:00 | Aging                 |                            | 11373 | Queens    | Elmhurst | NYCC21       | 04 Queens       | 2016-03-25T00:00:00 | 
| NYCC01506332 | NYCC01  | 2015-01-04T00:00:00 | Aging                 |                            | 11373 | Queens    | Elmhurst | NYCC21       | 04 Queens       | 2016-03-25T00:00:00 | 
| NYCC01506333 | NYCC01  | 2015-01-04T00:00:00 | Health                | Rats/Rodents               | 10006 | Manhattan | New York | NYCC01       | 01 Manhattan    | 2017-02-23T00:00:00 | 
| NYCC01506334 | NYCC01  | 2015-01-05T00:00:00 | Land Use and Zoning   |                            | 10003 | Manhattan | New York | NYCC02       | 05 Manhattan    | 2015-01-15T00:00:00 | 
| NYCC01506335 | NYCC01  | 2015-01-06T00:00:00 | Transportation        | Pot Holes                  | 10002 | Manhattan | New York | NYCC01       | 03 Manhattan    | 2016-02-09T00:00:00 | 
| NYCC01506338 | NYCC01  | 2015-01-06T00:00:00 | Transportation        | Parking Permits            | 10002 | Manhattan | New York | NYCC01       | 03 Manhattan    | 2015-03-17T00:00:00 | 
| NYCC01506341 | NYCC01  | 2015-01-07T00:00:00 | Housing and Buildings | NYCHA Building Maintenance |       |           |          |              |                 | 2016-02-09T00:00:00 | 
| NYCC01506342 | NYCC01  | 2015-01-08T00:00:00 | Economy/Jobs          | Business Assistance        | 11355 | Queens    | Flushing | NYCC20       | 07 Queens       | 2015-01-08T00:00:00 | 
| NYCC01506343 | NYCC01  | 2015-01-08T00:00:00 | Immigration           | Visas                      | 10002 | Manhattan | New York | NYCC01       | 03 Manhattan    | 2015-01-08T00:00:00 | 
```