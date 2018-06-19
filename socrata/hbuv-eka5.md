# Performance Metrics - Family & Support Services - Domestic Violence Service Help Line Monthly Utilization

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-family-support-services-domestic-violence-service-help-line-monthly-ut-72d3f) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/hbuv-eka5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/hbuv-eka5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/hbuv-eka5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | hbuv-eka5 |
| Name | Performance Metrics - Family & Support Services - Domestic Violence Service Help Line Monthly Utilization |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, human services |
| Created | 2011-08-01T17:01:57Z |
| Publication Date | 2014-09-02T22:06:31Z |

## Description

This metric tracks the number of domestic violence service calls received by the Domestic Violence Help Line per month. The city has developed a multi-layered response to the domestic violence crisis, including the Help Line, services provided by delegate agencies and services provided by advocates at our Community Service Centers. DFSS funds approximately 30 community based delegate agencies under the Family Violence Prevention Initiative to serve domestic violence victims and their children at programs located throughout Chicago.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | month           | Month           | text      | text        |
| Yes      | time           | year            | Year            | number    | text        |
| Yes      | numeric metric | number_of_calls | Number of Calls | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hbuv-eka5 d:2011-01-01T00:00:00.000Z t:month=11-Jan m:number_of_calls=1538

series e:hbuv-eka5 d:2011-01-01T00:00:00.000Z t:month=11-Feb m:number_of_calls=1339

series e:hbuv-eka5 d:2011-01-01T00:00:00.000Z t:month=11-Mar m:number_of_calls=1526
```

## Meta Commands

```ls
metric m:number_of_calls p:integer l:"Number of Calls" t:dataTypeName=number

entity e:hbuv-eka5 l:"Performance Metrics - Family & Support Services - Domestic Violence Service Help Line Monthly Utilization" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/hbuv-eka5

property e:hbuv-eka5 t:meta.view v:id=hbuv-eka5 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Family & Support Services - Domestic Violence Service Help Line Monthly Utilization" v:attribution="City of Chicago"

property e:hbuv-eka5 t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:hbuv-eka5 t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| month  | year | number_of_calls | 
| ====== | ==== | =============== | 
| 11-Jan | 2011 | 1538            | 
| 11-Feb | 2011 | 1339            | 
| 11-Mar | 2011 | 1526            | 
| 11-Apr | 2011 | 1651            | 
| 11-May | 2011 | 1510            | 
| 11-Jun | 2011 | 1536            | 
| 11-Jul | 2011 | 1761            | 
| 11-Aug | 2011 | 1899            | 
| 11-Sep | 2011 | 1645            | 
| 11-Oct | 2011 | 1519            | 
```