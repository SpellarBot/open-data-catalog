# Web Analytics for SFGov Sites - 2015 (Q1+Q2+Q3+Q4)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/web-analytics-for-sfgov-sites-2015-q1q2) |
| Metadata | [Link](https://data.sfgov.org/api/views/yrfc-c5yu) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/yrfc-c5yu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/yrfc-c5yu/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | yrfc-c5yu |
| Name | Web Analytics for SFGov Sites - 2015 (Q1+Q2+Q3+Q4) |
| Category | City Infrastructure |
| Tags | web, analytics, sfgov |
| Created | 2015-07-22T21:30:54Z |
| Publication Date | 2016-01-08T19:07:32Z |

## Description

Web analytics data for SFGov sites

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
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yrfc-c5yu d:2015-01-01T00:00:00.000Z t:avg_time_on_page=0:03:35 t:page_title="City and County of San Francisco" m:entrances=2593324 m:pageviews=3364231 m:unique_pageviews=2807560 m:exit=74.98 m:bounce_rate=80.88

series e:yrfc-c5yu d:2015-01-01T00:00:00.000Z t:avg_time_on_page=0:08:46 t:page_title="City and County of San Francisco : Employee Gateway" m:entrances=469758 m:pageviews=773329 m:unique_pageviews=470482 m:exit=60.69 m:bounce_rate=60.27

series e:yrfc-c5yu d:2015-01-01T00:00:00.000Z t:avg_time_on_page=0:02:46 t:page_title="Property Tax Payments | Treasurer & Tax Collector" m:entrances=200758 m:pageviews=716113 m:unique_pageviews=443887 m:exit=43.81 m:bounce_rate=52.04
```

## Meta Commands

```ls
metric m:pageviews p:integer l:Pageviews d:"Page views is the total number of pages viewed. Repeated views of a single page are counted." t:dataTypeName=number

metric m:unique_pageviews p:integer l:"Unique Pageviews" d:"Unique Pageviews is the number of visits during which the specified page was viewed at least once. A unique page view is counted for each page URL + page title combination" t:dataTypeName=number

metric m:entrances p:integer l:Entrances d:"Entrances is the number of times visitors entered the site through a specified page or set of pages." t:dataTypeName=number

metric m:bounce_rate p:float l:"Bounce Rate" d:"Bounce Rate is the percentage of single-page visits (i.e. visits in which the person left the site from the entrance page without interacting with the page)." t:dataTypeName=percent

metric m:exit p:float l:"% Exit" d:"%Exit is (number of exits) / (number of pageviews) for the page or set of pages. It indicates how often users exit from that page or set of pages when they view the page(s)." t:dataTypeName=percent

entity e:yrfc-c5yu l:"Web Analytics for SFGov Sites - 2015 (Q1+Q2+Q3+Q4)" t:url=https://data.sfgov.org/api/views/yrfc-c5yu

property e:yrfc-c5yu t:meta.view v:id=yrfc-c5yu v:category="City Infrastructure" v:averageRating=0 v:name="Web Analytics for SFGov Sites - 2015 (Q1+Q2+Q3+Q4)"

property e:yrfc-c5yu t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:yrfc-c5yu t:meta.view.owner v:id=rdx3-mhis v:screenName="SFGov Webmaster" v:displayName="SFGov Webmaster"

property e:yrfc-c5yu t:meta.view.tableauthor v:id=rdx3-mhis v:screenName="SFGov Webmaster" v:roleName=editor v:displayName="SFGov Webmaster"
```

## Top Records

```ls
| page_title                                                                             | pageviews | unique_pageviews | avg_time_on_page | entrances | bounce_rate | exit  | 
| ====================================================================================== | ========= | ================ | ================ | ========= | =========== | ===== | 
| City and County of San Francisco                                                       | 3364231   | 2807560          | 0:03:35          | 2593324   | 80.88       | 74.98 | 
| City and County of San Francisco : Employee Gateway                                    | 773329    | 470482           | 0:08:46          | 469758    | 60.27       | 60.69 | 
| Property Tax Payments | Treasurer & Tax Collector                                      | 716113    | 443887           | 0:02:46          | 200758    | 52.04       | 43.81 | 
| Controller : CCSF ePayroll ? Online Paystubs                                           | 670127    | 393553           | 0:03:43          | 388054    | 90.46       | 58.20 | 
| Treasurer & Tax Collector                                                              | 610008    | 430768           | 0:00:40          | 345770    | 13.18       | 16.53 | 
| Controller : CCSF ePayroll                                                             | 532819    | 320488           | 0:03:41          | 314902    | 89.30       | 59.36 | 
| San Francisco Department of Human Resources : Home                                     | 508740    | 413464           | 0:01:25          | 358323    | 49.32       | 44.11 | 
| San Francisco Department of Human Resources : Classification and Compensation Database | 482470    | 229315           | 0:02:07          | 133312    | 56.18       | 38.84 | 
| Department of Building Inspection                                                      | 306359    | 242447           | 0:02:00          | 221837    | 48.55       | 46.22 | 
| San Francisco Department of Human Resources : Job Seekers                              | 292018    | 235335           | 0:01:26          | 190567    | 53.12       | 47.67 | 
```