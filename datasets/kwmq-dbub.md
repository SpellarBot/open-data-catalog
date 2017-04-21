# 2013 Campaign Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-campaign-expenditures-e8c6d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kwmq-dbub) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kwmq-dbub/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kwmq-dbub/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kwmq-dbub |
| Name | 2013 Campaign Expenditures |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T23:18:19Z |
| Publication Date | 2013-06-21T19:53:43Z |

## Description

A listing of campaign expenditures for candidates for City office dating back from the 2013 election cycle

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | numeric metric | election   | ELECTION   | number    | number      |
| Yes      | numeric metric | officecd   | OFFICECD   | number    | number      |
| Yes      | series tag     | candid     | CANDID     | text      | number      |
| Yes      | series tag     | canclass   | CANCLASS   | text      | text        |
| Yes      | series tag     | candlast   | CANDLAST   | text      | text        |
| Yes      | series tag     | candfirst  | CANDFIRST  | text      | text        |
| Yes      | series tag     | candmi     | CANDMI     | text      | text        |
| Yes      | series tag     | committee  | COMMITTEE  | text      | text        |
| Yes      | numeric metric | filing     | FILING     | number    | number      |
| Yes      | series tag     | schedule   | SCHEDULE   | text      | text        |
| Yes      | series tag     | pageno     | PAGENO     | text      | text        |
| Yes      | series tag     | sequenceno | SEQUENCENO | text      | text        |
| Yes      | series tag     | refno      | REFNO      | text      | text        |
| No       |                | inv_date   | INV_DATE   | date      | date        |
| Yes      | time           | date       | DATE       | date      | date        |
| Yes      | series tag     | name       | NAME       | text      | text        |
| Yes      | series tag     | c_code     | C_CODE     | text      | text        |
| Yes      | series tag     | org_ind    | ORG_IND    | text      | text        |
| Yes      | numeric metric | strno      | STRNO      | number    | number      |
| Yes      | series tag     | strname    | STRNAME    | text      | text        |
| Yes      | series tag     | apartment  | APARTMENT  | text      | text        |
| Yes      | series tag     | pay_method | PAY_METHOD | text      | text        |
| Yes      | numeric metric | amnt       | AMNT       | number    | number      |
| Yes      | series tag     | purposecd  | PURPOSECD  | text      | text        |
| Yes      | series tag     | purpose    | PURPOSE    | text      | text        |
| Yes      | series tag     | explain    | EXPLAIN    | text      | text        |
| Yes      | series tag     | exemptcd   | EXEMPTCD   | text      | text        |
| Yes      | series tag     | rr_ind     | RR_IND     | text      | text        |
| Yes      | series tag     | seg_ind    | SEG_IND    | text      | text        |
```

## Time Field

```ls
Value = date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = inv_date
```

## Data Commands

```ls
series e:kwmq-dbub d:2010-05-26T07:00:00.000Z t:candlast="Vallone, Jr." t:purposecd=OFFCE t:candid=240 t:c_code=OTHR t:purpose="Office Expenses" t:canclass=UN t:candmi=F t:seg_ind=N t:schedule=F t:candfirst=Peter t:refno=R0006242 t:pay_method=Full t:committee=L t:org_ind=Y t:name="Amazon Mktplace" t:explain="Window 7 Purchase" t:rr_ind=N m:amnt=464.97 m:election=2013 m:officecd=6 m:filing=1

series e:kwmq-dbub d:2010-02-26T08:00:00.000Z t:candlast=Rivera t:purposecd=OFFCE t:candid=361 t:c_code=CORP t:purpose="Office Expenses" t:canclass=UN t:seg_ind=N t:schedule=F t:refno=R0001632 t:candfirst=Joel t:pay_method=Full t:committee=L t:org_ind=Y t:name=AT&T t:explain="Phone Service" t:rr_ind=N m:amnt=296.74 m:election=2013 m:officecd=6 m:filing=1

series e:kwmq-dbub d:2010-05-04T07:00:00.000Z t:candlast=Lisyanskiy t:purposecd=OFFCE t:candid=1163 t:c_code=CORP t:purpose="Office Expenses" t:canclass=UN t:seg_ind=N t:schedule=F t:refno=R0000449 t:candfirst=John t:pay_method=Full t:committee=H t:org_ind=Y t:name=AUTHIRIZE.NET t:explain="monthly fee" t:rr_ind=N m:amnt=5 m:election=2013 m:officecd=5 m:filing=1
```

## Meta Commands

```ls
metric m:election p:integer l:ELECTION t:dataTypeName=number

metric m:officecd p:integer l:OFFICECD t:dataTypeName=number

metric m:filing p:integer l:FILING t:dataTypeName=number

metric m:strno p:integer l:STRNO t:dataTypeName=number

metric m:amnt p:double l:AMNT t:dataTypeName=number

entity e:kwmq-dbub l:"2013 Campaign Expenditures" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/kwmq-dbub

property e:kwmq-dbub t:meta.view v:id=kwmq-dbub v:category="City Government" v:averageRating=0 v:name="2013 Campaign Expenditures" v:attribution="Campaign Finance Board (CFB)"

property e:kwmq-dbub t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kwmq-dbub t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| election | officecd | candid | canclass | candlast     | candfirst | candmi | committee | filing | schedule | pageno | sequenceno | refno    | inv_date   | date       | name            | c_code | org_ind | strno | strname | apartment | pay_method | amnt   | purposecd | purpose          | explain           | exemptcd | rr_ind | seg_ind | 
| ======== | ======== | ====== | ======== | ============ | ========= | ====== | ========= | ====== | ======== | ====== | ========== | ======== | ========== | ========== | =============== | ====== | ======= | ===== | ======= | ========= | ========== | ====== | ========= | ================ | ================= | ======== | ====== | ======= | 
|          |          |        | CANCLASS | CANDLAST     | CANDFIRST | CANDMI | COMMITTEE |        | SCHEDULE | PAGENO | SEQUENCENO | REFNO    |            |            | NAME            | C_CODE | ORG_IND |       | STRNAME | APARTMENT | PAY_METHOD |        | PURPOSECD | PURPOSE          | EXPLAIN           | EXEMPTCD | RR_IND | SEG_IND | 
| 2013     | 6        | 240    | UN       | Vallone, Jr. | Peter     | F      | L         | 1      | F        |        |            | R0006242 | 1274857200 | 1274857200 | Amazon Mktplace | OTHR   | Y       |       |         |           | Full       | 464.97 | OFFCE     | Office Expenses  | Window 7 Purchase |          | N      | N       | 
| 2013     | 6        | 361    | UN       | Rivera       | Joel      |        | L         | 1      | F        |        |            | R0001632 | 1267171200 | 1267171200 | AT&T            | CORP   | Y       |       |         |           | Full       | 296.74 | OFFCE     | Office Expenses  | Phone Service     |          | N      | N       | 
| 2013     | 5        | 1163   | UN       | Lisyanskiy   | John      |        | H         | 1      | F        |        |            | R0000449 | 1272610800 | 1272956400 | AUTHIRIZE.NET   | CORP   | Y       |       |         |           | Full       | 5.00   | OFFCE     | Office Expenses  | monthly fee       |          | N      | N       | 
| 2013     | 5        | 1163   | UN       | Lisyanskiy   | John      |        | H         | 1      | F        |        |            | R0000451 | 1275289200 | 1275548400 | AUTHIRIZE.NET   | CORP   | Y       |       |         |           | Full       | 5.00   | OFFCE     | Office Expenses  | monthly fee       |          | N      | N       | 
| 2013     | 5        | 1163   | UN       | Lisyanskiy   | John      |        | H         | 1      | F        |        |            | R0000453 | 1277881200 | 1278399600 | AUTHIRIZE.NET   | CORP   | Y       |       |         |           | Full       | 5.00   | OFFCE     | Office Expenses  | monthly fee       |          | N      | N       | 
| 2013     | 5        | 1163   | UN       | Lisyanskiy   | John      |        | H         | 1      | F        |        |            | R0000468 | 1270018800 | 1270450800 | AUTHIRIZE.NET   | CORP   | Y       |       |         |           | Full       | 5.00   | OFFCE     | Office Expenses  | monthly fee       |          | N      | N       | 
| 2013     | 5        | 1163   | UN       | Lisyanskiy   | John      |        | H         | 1      | F        |        |            | R0000470 | 1264924800 | 1265184000 | AUTHIRIZE.NET   | CORP   | Y       |       |         |           | Full       | 5.00   | OFFCE     | Office Expenses  | monthly fee       |          | N      | N       | 
| 2013     | 5        | 1163   | UN       | Lisyanskiy   | John      |        | H         | 1      | F        |        |            | R0000472 | 1267344000 | 1267516800 | AUTHIRIZE.NET   | CORP   | Y       |       |         |           | Full       | 5.00   | OFFCE     | Office Expenses  | monthly fee       |          | N      | N       | 
| 2013     | 6        | 240    | UN       | Vallone, Jr. | Peter     | F      | L         | 1      | F        |        |            | R0006222 | 1268208000 | 1268208000 | Bistro          | OTHR   | Y       |       |         |           | Full       | 44.51  | OTHER     | Other: explntion | Campaign Lunch    |          | N      | N       | 
```