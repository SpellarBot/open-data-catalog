# Licensing Center Customer Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensing-center-customer-information) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/azp6-hepu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/azp6-hepu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/azp6-hepu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | azp6-hepu |
| Name | Licensing Center Customer Information |
| Attribution | Department of Consumer Affairs (DCA) |
| Category | Business |
| Tags | city government, business, dca, department of consumer affairs, license |
| Created | 2016-01-26T19:10:03Z |
| Publication Date | 2016-07-13T17:13:52Z |

## Description

This data set features a monthly snapshot of customer service information at the DCA Licensing Center.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | licensing_office            | Licensing Office            | text          | text          |
| Yes      | time           | month                       | Month                       | calendar_date | calendar_date |
| Yes      | numeric metric | customers_served            | Customers Served            | number        | number        |
| No       |                | average_wait_time           | Average Wait Time           | number        | text          |
| No       |                | average_transaction_time    | Average Transaction Time    | number        | text          |
| Yes      | numeric metric | average_satisfaction_rating | Average Satisfaction Rating | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = average_wait_time,average_transaction_time
```

## Data Commands

```ls
series e:azp6-hepu d:2015-08-01T00:00:00.000Z t:licensing_office="42 Broadway" m:average_satisfaction_rating=4.84 m:customers_served=7758

series e:azp6-hepu d:2015-09-01T00:00:00.000Z t:licensing_office="42 Broadway" m:average_satisfaction_rating=4.86 m:customers_served=7870

series e:azp6-hepu d:2015-10-01T00:00:00.000Z t:licensing_office="42 Broadway" m:average_satisfaction_rating=4.89 m:customers_served=6712
```

## Meta Commands

```ls
metric m:customers_served p:integer l:"Customers Served" d:"The number of customers served during the selected month" t:dataTypeName=number

metric m:average_satisfaction_rating p:float l:"Average Satisfaction Rating" d:"Customer satisfaction rating on a 5-point scale, with 5 being the best and 1 being the worst." t:dataTypeName=number

entity e:azp6-hepu l:"Licensing Center Customer Information" t:attribution="Department of Consumer Affairs (DCA)" t:url=https://data.cityofnewyork.us/api/views/azp6-hepu

property e:azp6-hepu t:meta.view v:id=azp6-hepu v:category=Business v:averageRating=0 v:name="Licensing Center Customer Information" v:attribution="Department of Consumer Affairs (DCA)"

property e:azp6-hepu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:azp6-hepu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| licensing_office | month               | customers_served | average_wait_time | average_transaction_time | average_satisfaction_rating | 
| ================ | =================== | ================ | ================= | ======================== | =========================== | 
| 42 Broadway      | 2015-08-01T00:00:00 | 7758             | 10.6              | 11.3                     | 4.84                        | 
| 42 Broadway      | 2015-09-01T00:00:00 | 7870             | 7.7               | 11                       | 4.86                        | 
| 42 Broadway      | 2015-10-01T00:00:00 | 6712             | 3.8               | 11.4                     | 4.89                        | 
| 42 Broadway      | 2015-11-01T00:00:00 | 5669             | 5.1               | 11.2                     | 4.9                         | 
| 42 Broadway      | 2015-12-01T00:00:00 | 6489             | 4.4               | 11.4                     | 4.88                        | 
| 42 Broadway      | 2016-01-01T00:00:00 | 5225             | 6.6               | 11.7                     | 4.88                        | 
| 42 Broadway      | 2016-02-01T00:00:00 | 6496             | 8.5               | 10.7                     | 4.88                        | 
| Queens           | 2016-02-01T00:00:00 | 249              | 1                 | 19.2                     |                             | 
| 42 Broadway      | 2016-03-01T00:00:00 | 9072             | 14.9              | 10.8                     | 4.9                         | 
| Queens           | 2016-03-01T00:00:00 | 470              | 1.6               | 15.6                     |                             | 
```