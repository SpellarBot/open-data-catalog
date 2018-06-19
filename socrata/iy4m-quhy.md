# Web Analytics for SFGov sites - 2016 (Q1+Q2+Q3)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/web-analytics-for-sfgov-sites-2016-q1) |
| Metadata | [Link](https://data.sfgov.org/api/views/iy4m-quhy) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/iy4m-quhy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/iy4m-quhy/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | iy4m-quhy |
| Name | Web Analytics for SFGov sites - 2016 (Q1+Q2+Q3) |
| Category | City Infrastructure |
| Tags | web, sfgov, analytics |
| Created | 2016-04-08T20:51:02Z |
| Publication Date | 2016-10-05T18:17:44Z |

## Description

Web Analytics for SFGov sites - 2016 (Q1+Q2+Q3)

## Columns

```ls
| Included | Schema Type    | Field Name       | Name              | Data Type | Render Type |
| ======== | ============== | ================ | ================= | ========= | =========== |
| Yes      | series tag     | page_title       | Page Title        | text      | text        |
| Yes      | numeric metric | pageviews        | Pageviews         | number    | number      |
| Yes      | numeric metric | unique_pageviews | Unique Pageviews  | number    | number      |
| Yes      | series tag     | avg_time_on_page | Avg. Time on Page | text      | text        |
| Yes      | numeric metric | entrances        | Entrances         | number    | number      |
| Yes      | numeric metric | bounce_rate      | Bounce Rate       | percent   | percent     |
| Yes      | numeric metric | exit             | % Exit            | percent   | percent     |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:iy4m-quhy d:2016-01-01T00:00:00.000Z t:avg_time_on_page=0:02:44 t:page_title=SFGOV m:entrances=1160906 m:pageviews=1427743 m:unique_pageviews=1190028 m:exit=70.27 m:bounce_rate=75.54

series e:iy4m-quhy d:2016-01-01T00:00:00.000Z t:avg_time_on_page=0:03:24 t:page_title="CCSF ePayroll ? Online Paystubs | Office of the Controller" m:entrances=332963 m:pageviews=1107404 m:unique_pageviews=342323 m:exit=30.41 m:bounce_rate=13.49

series e:iy4m-quhy d:2016-01-01T00:00:00.000Z t:avg_time_on_page=0:07:43 t:page_title="Employee Gateway | SFGOV" m:entrances=583795 m:pageviews=910810 m:unique_pageviews=599486 m:exit=64.73 m:bounce_rate=23.45
```

## Meta Commands

```ls
metric m:pageviews p:integer l:Pageviews t:dataTypeName=number

metric m:unique_pageviews p:integer l:"Unique Pageviews" t:dataTypeName=number

metric m:entrances p:integer l:Entrances t:dataTypeName=number

metric m:bounce_rate p:float l:"Bounce Rate" t:dataTypeName=percent

metric m:exit p:float l:"% Exit" t:dataTypeName=percent

entity e:iy4m-quhy l:"Web Analytics for SFGov sites - 2016 (Q1+Q2+Q3)" t:url=https://data.sfgov.org/api/views/iy4m-quhy

property e:iy4m-quhy t:meta.view v:id=iy4m-quhy v:category="City Infrastructure" v:averageRating=0 v:name="Web Analytics for SFGov sites - 2016 (Q1+Q2+Q3)"

property e:iy4m-quhy t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:iy4m-quhy t:meta.view.owner v:id=rdx3-mhis v:screenName="SFGov Webmaster" v:displayName="SFGov Webmaster"

property e:iy4m-quhy t:meta.view.tableauthor v:id=rdx3-mhis v:screenName="SFGov Webmaster" v:roleName=editor v:displayName="SFGov Webmaster"
```

## Top Records

```ls
| page_title                                                 | pageviews | unique_pageviews | avg_time_on_page | entrances | bounce_rate | exit  | 
| ========================================================== | ========= | ================ | ================ | ========= | =========== | ===== | 
| SFGOV                                                      | 1427743   | 1190028          | 0:02:44          | 1160906   | 75.54       | 70.27 | 
| CCSF ePayroll ? Online Paystubs | Office of the Controller | 1107404   | 342323           | 0:03:24          | 332963    | 13.49       | 30.41 | 
| Employee Gateway | SFGOV                                   | 910810    | 599486           | 0:07:43          | 583795    | 23.45       | 64.73 | 
| City and County of San Francisco                           | 652760    | 542980           | 0:02:46          | 487789    | 74.11       | 67.82 | 
| Property Tax Payments | Treasurer & Tax Collector          | 501634    | 295433           | 0:02:44          | 153136    | 52.73       | 45.75 | 
| Treasurer & Tax Collector                                  | 441432    | 311531           | 0:00:47          | 248322    | 13.52       | 16.31 | 
| Department of Building Inspection                          | 361549    | 299611           | 0:02:59          | 283734    | 57.72       | 61.71 | 
| Controller : CCSF ePayroll ? Online Paystubs               | 360413    | 161971           | 0:03:25          | 159145    | 90.82       | 44.50 | 
| Department of Human Resources                              | 326171    | 256491           | 0:02:03          | 232465    | 28.64       | 41.04 | 
| Business Registration Renewal | Treasurer & Tax Collector  | 264161    | 177821           | 0:02:42          | 75822     | 9.56        | 30.70 | 
```