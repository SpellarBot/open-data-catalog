# 2005 Campaign Payments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2005-campaign-payments-2bbe5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9mjx-v8ip) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9mjx-v8ip/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9mjx-v8ip/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9mjx-v8ip |
| Name | 2005 Campaign Payments |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T22:56:26Z |
| Publication Date | 2013-06-21T20:03:38Z |

## Description

A listing of campaign public funds payments for candidates for City office during the 2005 election cycle

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | numeric metric | election   | ELECTION   | number    | number      |
| Yes      | series tag     | candid     | CANDID     | text      | number      |
| Yes      | series tag     | candname   | CANDNAME   | text      | text        |
| Yes      | numeric metric | officecd   | OFFICECD   | number    | number      |
| Yes      | series tag     | officeboro | OFFICEBORO | text      | text        |
| Yes      | numeric metric | officedist | OFFICEDIST | number    | number      |
| Yes      | series tag     | canclass   | CANCLASS   | text      | text        |
| Yes      | numeric metric | primarypay | PRIMARYPAY | number    | number      |
| Yes      | numeric metric | generalpay | GENERALPAY | number    | number      |
| Yes      | numeric metric | runoffpay  | RUNOFFPAY  | number    | number      |
| Yes      | numeric metric | totalpay   | TOTALPAY   | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9mjx-v8ip d:2005-01-01T00:00:00.000Z t:candname="Addabbo, Joseph P" t:canclass=P m:generalpay=0 m:election=2005 m:totalpay=0 m:officedist=32 m:primarypay=0 m:officecd=5 m:runoffpay=0

series e:9mjx-v8ip d:2005-01-01T00:00:00.000Z t:candname="Akbar, Celestina" t:candid=884 t:canclass=P m:generalpay=0 m:election=2005 m:totalpay=0 m:officedist=23 m:primarypay=0 m:officecd=5 m:runoffpay=0

series e:9mjx-v8ip d:2005-01-01T00:00:00.000Z t:candname="Antoine, Royston" t:candid=864 t:canclass=P m:generalpay=0 m:election=2005 m:totalpay=59900 m:officedist=41 m:primarypay=59900 m:officecd=5 m:runoffpay=0
```

## Meta Commands

```ls
metric m:election p:integer l:ELECTION t:dataTypeName=number

metric m:officecd p:integer l:OFFICECD t:dataTypeName=number

metric m:officedist p:integer l:OFFICEDIST t:dataTypeName=number

metric m:primarypay p:float l:PRIMARYPAY t:dataTypeName=number

metric m:generalpay p:float l:GENERALPAY t:dataTypeName=number

metric m:runoffpay p:integer l:RUNOFFPAY t:dataTypeName=number

metric m:totalpay p:float l:TOTALPAY t:dataTypeName=number

entity e:9mjx-v8ip l:"2005 Campaign Payments" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/9mjx-v8ip

property e:9mjx-v8ip t:meta.view v:id=9mjx-v8ip v:category="City Government" v:averageRating=0 v:name="2005 Campaign Payments" v:attribution="Campaign Finance Board (CFB)"

property e:9mjx-v8ip t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9mjx-v8ip t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| election | candid | candname          | officecd | officeboro | officedist | canclass | primarypay | generalpay | runoffpay | totalpay  | 
| ======== | ====== | ================= | ======== | ========== | ========== | ======== | ========== | ========== | ========= | ========= | 
|          |        | CANDNAME          |          | OFFICEBORO |            | CANCLASS |            |            |           |           | 
| 2005     |        | Addabbo, Joseph P | 5        |            | 32         | P        | 0          | 0          | 0         | 0         | 
| 2005     | 884    | Akbar, Celestina  | 5        |            | 23         | P        | 0          | 0          | 0         | 0         | 
| 2005     | 864    | Antoine, Royston  | 5        |            | 41         | P        | 59900.00   | 0          | 0         | 59900.00  | 
| 2005     | 838    | Arroyo, Maria C   | 5        |            | 17         | P        | 0          | 0          | 0         | 0         | 
| 2005     | 51     | Avella, Tony      | 5        |            | 19         | P        | 0          | 75120.00   | 0         | 75120.00  | 
| 2005     | 591    | Baez, Maria       | 5        |            | 14         | P        | 0          | 0          | 0         | 0         | 
| 2005     | 835    | Baldeo, Albert J  | 5        |            | 28         | P        | 82500.00   | 0          | 0         | 82500.00  | 
| 2005     |        | Barron, Charles   | 5        |            | 42         | P        | 82500.00   | 58577.00   | 0         | 141077.00 | 
| 2005     | 560    | Bernace, Victor A | 5        |            | 7          | P        | 48900.00   | 0          | 0         | 48900.00  | 
```