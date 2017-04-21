# 2003 Campaign Payments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2003-campaign-payments-7d0b8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ms66-xjfq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ms66-xjfq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ms66-xjfq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ms66-xjfq |
| Name | 2003 Campaign Payments |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T22:07:58Z |
| Publication Date | 2013-06-21T20:03:43Z |

## Description

A listing of campaign payments for candidates for City office during 2001 election cycle

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | numeric metric | election   | ELECTION   | number    | number      |
| Yes      | series tag     | candid     | CANDID     | text      | text        |
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
Value = 2003
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ms66-xjfq d:2003-01-01T00:00:00.000Z t:candname="Addabbo, Joseph P" t:candid=HF t:canclass=P m:generalpay=82500 m:election=2003 m:totalpay=82500 m:officedist=32 m:primarypay=0 m:officecd=5 m:runoffpay=0

series e:ms66-xjfq d:2003-01-01T00:00:00.000Z t:candname="Alamo-Estrada, Agustin" t:candid=IR t:canclass=P m:generalpay=360 m:election=2003 m:totalpay=57188 m:officedist=17 m:primarypay=56828 m:officecd=5 m:runoffpay=0

series e:ms66-xjfq d:2003-01-01T00:00:00.000Z t:candname="Arangio, Jennifer" t:candid=728 t:canclass=P m:generalpay=36196 m:election=2003 m:totalpay=56821 m:officedist=5 m:primarypay=20625 m:officecd=5 m:runoffpay=0
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

entity e:ms66-xjfq l:"2003 Campaign Payments" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/ms66-xjfq

property e:ms66-xjfq t:meta.view v:id=ms66-xjfq v:category="City Government" v:averageRating=0 v:name="2003 Campaign Payments" v:attribution="Campaign Finance Board (CFB)"

property e:ms66-xjfq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ms66-xjfq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| election | candid | candname               | officecd | officeboro | officedist | canclass | primarypay | generalpay | runoffpay | totalpay  | 
| ======== | ====== | ====================== | ======== | ========== | ========== | ======== | ========== | ========== | ========= | ========= | 
|          | CANDID | CANDNAME               |          | OFFICEBORO |            | CANCLASS |            |            |           |           | 
| 2003     | HF     | Addabbo, Joseph P      | 5        |            | 32         | P        | 0          | 82500.00   | 0         | 82500.00  | 
| 2003     | IR     | Alamo-Estrada, Agustin | 5        |            | 17         | P        | 56828.00   | 360.00     | 0         | 57188.00  | 
| 2003     | 728    | Arangio, Jennifer      | 5        |            | 5          | P        | 20625.00   | 36196.00   | 0         | 56821.00  | 
| 2003     | 51     | Avella, Tony           | 5        |            | 19         | P        | 0          | 70256.00   | 0         | 70256.00  | 
| 2003     | 591    | Baez, Maria            | 5        |            | 14         | P        | 76260.00   | 10415.00   | 0         | 86675.00  | 
| 2003     | DD     | Barron, Charles        | 5        |            | 42         | P        | 56184.00   | 10120.00   | 0         | 66304.00  | 
| 2003     | 560    | Bernace, Victor A      | 5        |            | 7          | P        | 44060.00   | 0          | 0         | 44060.00  | 
| 2003     | HB     | Betancourt Jr, Ismael  | 5        |            | 13         | P        | 100000.00  | 0          | 0         | 100000.00 | 
| 2003     | 752    | Booker, Derek S        | 5        |            | 42         | P        | 0          | 0          | 0         | 0         | 
```