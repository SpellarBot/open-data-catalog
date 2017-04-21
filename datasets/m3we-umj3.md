# Performance Metrics - Family & Support Services - Senior Services Nutrition Monthly Utilization

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-family-support-services-senior-services-nutrition-monthly-utilization-c190d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/m3we-umj3) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/m3we-umj3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/m3we-umj3/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | m3we-umj3 |
| Name | Performance Metrics - Family & Support Services - Senior Services Nutrition Monthly Utilization |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, human services |
| Created | 2011-08-01T16:02:24Z |
| Publication Date | 2014-07-10T17:16:24Z |

## Description

This metric tracks the number of congregate and home delivered meals provided to seniors per month. DFSS, Senior Services division is the city?s Area Agency on Aging for older adults. DFSS offers a wide variety of programs and services that address the diverse needs and interests of older adults in Chicago from those who are healthy and active to those who are frail and homebound.  The Congregate Dining Program strengthens social relationships while addressing the problem of poor nutrition among older adults. Each day Senior Services provides seniors with opportunities for nutritious meals, socialization, recreation, education and volunteer activities through approximately 60 co-sponsored congregate dining sites which annually serve over 20,000 senior residents. DFSS also provides over 11,000 frail homebound older adults with hot home delivered meals five days a week.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | month                     | Month                     | text      | text        |
| Yes      | time           | year                      | Year                      | number    | text        |
| Yes      | numeric metric | home_delievered_meals     | Home Delievered Meals     | number    | number      |
| Yes      | numeric metric | congregate_dining_program | Congregate Dining Program | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:m3we-umj3 d:2011-01-01T00:00:00.000Z t:month=11-Jan m:home_delievered_meals=294310 m:congregate_dining_program=60500

series e:m3we-umj3 d:2011-01-01T00:00:00.000Z t:month=11-Feb m:home_delievered_meals=265370 m:congregate_dining_program=56176

series e:m3we-umj3 d:2011-01-01T00:00:00.000Z t:month=11-Mar m:home_delievered_meals=317833 m:congregate_dining_program=69730
```

## Meta Commands

```ls
metric m:home_delievered_meals p:integer l:"Home Delievered Meals" t:dataTypeName=number

metric m:congregate_dining_program p:integer l:"Congregate Dining Program" t:dataTypeName=number

entity e:m3we-umj3 l:"Performance Metrics - Family & Support Services - Senior Services Nutrition Monthly Utilization" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/m3we-umj3

property e:m3we-umj3 t:meta.view v:id=m3we-umj3 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Family & Support Services - Senior Services Nutrition Monthly Utilization" v:attribution="City of Chicago"

property e:m3we-umj3 t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:m3we-umj3 t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| month  | year | home_delievered_meals | congregate_dining_program | 
| ====== | ==== | ===================== | ========================= | 
| 11-Jan | 2011 | 294310                | 60500                     | 
| 11-Feb | 2011 | 265370                | 56176                     | 
| 11-Mar | 2011 | 317833                | 69730                     | 
| 11-Apr | 2011 | 294102                | 66780                     | 
| 11-May | 2011 | 306915                | 65871                     | 
| 11-Jun | 2011 | 306224                | 65306                     | 
| 11-Jul | 2011 | 293167                | 61971                     | 
| 11-Aug | 2011 | 305689                | 69947                     | 
| 11-Sep | 2011 | 301619                | 66316                     | 
| 11-Oct | 2011 | 288568                | 65601                     | 
```