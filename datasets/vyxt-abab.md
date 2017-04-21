# 2009 Campaign Payment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2009-campaign-payment-12d02) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vyxt-abab) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vyxt-abab/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vyxt-abab/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vyxt-abab |
| Name | 2009 Campaign Payment |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T23:15:46Z |
| Publication Date | 2013-06-21T20:05:23Z |

## Description

A listing of public funds payments for candidates for City office during the 2009

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
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vyxt-abab d:2009-01-01T00:00:00.000Z t:candname="Abraham, Isaac" t:candid=1231 t:canclass=P m:generalpay=0 m:election=2009 m:totalpay=88550 m:officedist=33 m:primarypay=88550 m:officecd=5 m:runoffpay=0

series e:vyxt-abab d:2009-01-01T00:00:00.000Z t:candname="Arroyo, Maria C" t:candid=838 t:canclass=P m:generalpay=22138 m:election=2009 m:totalpay=42932 m:officedist=17 m:primarypay=20794 m:officecd=5 m:runoffpay=0

series e:vyxt-abab d:2009-01-01T00:00:00.000Z t:candname="Avella, Tony" t:candid=51 t:canclass=P m:generalpay=0 m:election=2009 m:totalpay=0 m:primarypay=0 m:officecd=1 m:runoffpay=0
```

## Meta Commands

```ls
metric m:election p:integer l:ELECTION t:dataTypeName=number

metric m:officecd p:integer l:OFFICECD t:dataTypeName=number

metric m:officedist p:integer l:OFFICEDIST t:dataTypeName=number

metric m:primarypay p:float l:PRIMARYPAY t:dataTypeName=number

metric m:generalpay p:float l:GENERALPAY t:dataTypeName=number

metric m:runoffpay p:float l:RUNOFFPAY t:dataTypeName=number

metric m:totalpay p:float l:TOTALPAY t:dataTypeName=number

entity e:vyxt-abab l:"2009 Campaign Payment" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/vyxt-abab

property e:vyxt-abab t:meta.view v:id=vyxt-abab v:category="City Government" v:averageRating=0 v:name="2009 Campaign Payment" v:attribution="Campaign Finance Board (CFB)"

property e:vyxt-abab t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vyxt-abab t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| election | candid | candname              | officecd | officeboro | officedist | canclass | primarypay | generalpay | runoffpay | totalpay | 
| ======== | ====== | ===================== | ======== | ========== | ========== | ======== | ========== | ========== | ========= | ======== | 
|          |        | CANDNAME              |          | OFFICEBORO |            | CANCLASS |            |            |           |          | 
| 2009     | 1231   | Abraham, Isaac        | 5        |            | 33         | P        | 88550.00   | 0          | 0         | 88550.00 | 
| 2009     | 838    | Arroyo, Maria C       | 5        |            | 17         | P        | 20794.00   | 22138.00   | 0         | 42932.00 | 
| 2009     | 51     | Avella, Tony          | 1        |            |            | P        | 0          | 0          | 0         | 0        | 
| 2009     | 1206   | Baer, Kenneth J       | 5        |            | 33         | P        | 80646.00   | 0          | 0         | 80646.00 | 
| 2009     | 591    | Baez, Maria           | 5        |            | 14         | P        | 70170.00   | 0          | 0         | 70170.00 | 
| 2009     |        | Barron, Charles       | 5        |            | 42         | P        | 34128.00   | 4572.00    | 0         | 38700.00 | 
| 2009     | 60     | Behar, Steven Anthony | 5        |            | 19         | P        | 98557.00   | 0          | 0         | 98557.00 | 
| 2009     | 1404   | Berardelli, Gene R    | 5        |            | 46         | P        | 0          | 0          | 0         | 0        | 
| 2009     | 1273   | Berkley, Carlton      | 5        |            | 9          | P        | 0          | 0          | 0         | 0        | 
```