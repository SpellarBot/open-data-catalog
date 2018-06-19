# 2009 Campaign Contributions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2009-campaign-contributions-fdb81) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bbs3-q5us) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bbs3-q5us/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bbs3-q5us/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bbs3-q5us |
| Name | 2009 Campaign Contributions |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T23:33:35Z |
| Publication Date | 2013-06-21T19:51:35Z |

## Description

A listing of campaign contributions for candidates for City office during the 209 election cycle

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
| Yes      | time           | date       | DATE       | date      | date        |
| No       |                | refunddate | REFUNDDATE | date      | date        |
| Yes      | series tag     | name       | NAME       | text      | text        |
| Yes      | series tag     | c_code     | C_CODE     | text      | text        |
| Yes      | numeric metric | strno      | STRNO      | number    | number      |
| Yes      | series tag     | strname    | STRNAME    | text      | text        |
| Yes      | series tag     | apartment  | APARTMENT  | text      | text        |
| Yes      | series tag     | boroughcd  | BOROUGHCD  | text      | text        |
| Yes      | series tag     | occupation | OCCUPATION | text      | text        |
| Yes      | series tag     | empname    | EMPNAME    | text      | text        |
| Yes      | numeric metric | empstrno   | EMPSTRNO   | number    | number      |
| Yes      | series tag     | empstrname | EMPSTRNAME | text      | text        |
| Yes      | numeric metric | amnt       | AMNT       | number    | number      |
| Yes      | numeric metric | matchamnt  | MATCHAMNT  | number    | number      |
| Yes      | numeric metric | prevamnt   | PREVAMNT   | number    | number      |
| Yes      | numeric metric | pay_method | PAY_METHOD | number    | number      |
| Yes      | numeric metric | intermno   | INTERMNO   | number    | number      |
| Yes      | series tag     | intermname | INTERMNAME | text      | text        |
| Yes      | series tag     | intstrno   | INTSTRNO   | text      | text        |
| Yes      | series tag     | intstrnm   | INTSTRNM   | text      | text        |
| Yes      | series tag     | intaptno   | INTAPTNO   | text      | text        |
| Yes      | series tag     | intst      | INTST      | text      | text        |
| Yes      | series tag     | intzip     | INTZIP     | text      | number      |
| Yes      | series tag     | intempname | INTEMPNAME | text      | text        |
| Yes      | numeric metric | intempstno | INTEMPSTNO | number    | number      |
| Yes      | series tag     | intempstnm | INTEMPSTNM | text      | text        |
| Yes      | series tag     | intempcity | INTEMPCITY | text      | text        |
| Yes      | series tag     | intempst   | INTEMPST   | text      | text        |
| Yes      | series tag     | intoccupa  | INTOCCUPA  | text      | text        |
| Yes      | series tag     | purposecd  | PURPOSECD  | text      | text        |
| Yes      | series tag     | exemptcd   | EXEMPTCD   | text      | text        |
| Yes      | numeric metric | adjtypecd  | ADJTYPECD  | number    | number      |
| Yes      | series tag     | rr_ind     | RR_IND     | text      | text        |
| Yes      | series tag     | seg_ind    | SEG_IND    | text      | text        |
| Yes      | series tag     | int_c_code | INT_C_CODE | text      | text        |
```

## Time Field

```ls
Value = date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = refunddate
```

## Data Commands

```ls
series e:bbs3-q5us d:2007-12-10T08:00:00.000Z t:seg_ind=N t:schedule=M t:candfirst=Adolfo t:refno=R0005211 t:committee=K t:candlast="Carrion, Jr." t:name="1725 Crosby Realty LLC" t:c_code=LLC t:rr_ind=N t:canclass=UN m:adjtypecd=1 m:amnt=-1000 m:prevamnt=0 m:election=2009 m:pay_method=0 m:officecd=3 m:filing=4 m:matchamnt=0

series e:bbs3-q5us d:2007-12-10T08:00:00.000Z t:seg_ind=N t:schedule=ABC t:candfirst=Adolfo t:refno=R0004413 t:committee=K t:candlast="Carrion, Jr." t:name="1725 Crosby Realty LLC" t:c_code=LLC t:rr_ind=N t:canclass=UN m:amnt=1000 m:prevamnt=0 m:election=2009 m:pay_method=2 m:officecd=3 m:filing=4 m:matchamnt=0

series e:bbs3-q5us d:2009-07-30T07:00:00.000Z t:candlast=Burck t:empname="j school" t:candid=1466 t:c_code=IND t:canclass=NP t:candmi=J t:seg_ind=N t:refno=R0000953 t:candfirst=Robert t:schedule=ABC t:committee=H t:name="a, j" t:rr_ind=N t:boroughcd=Z m:amnt=15 m:prevamnt=0 m:election=2009 m:pay_method=1 m:officecd=1 m:filing=12 m:matchamnt=0
```

## Meta Commands

```ls
metric m:election p:integer l:ELECTION t:dataTypeName=number

metric m:officecd p:integer l:OFFICECD t:dataTypeName=number

metric m:filing p:integer l:FILING t:dataTypeName=number

metric m:strno p:integer l:STRNO t:dataTypeName=number

metric m:empstrno p:integer l:EMPSTRNO t:dataTypeName=number

metric m:amnt p:float l:AMNT t:dataTypeName=number

metric m:matchamnt p:float l:MATCHAMNT t:dataTypeName=number

metric m:prevamnt p:float l:PREVAMNT t:dataTypeName=number

metric m:pay_method p:float l:PAY_METHOD t:dataTypeName=number

metric m:intermno p:integer l:INTERMNO t:dataTypeName=number

metric m:intempstno p:integer l:INTEMPSTNO t:dataTypeName=number

metric m:adjtypecd p:integer l:ADJTYPECD t:dataTypeName=number

entity e:bbs3-q5us l:"2009 Campaign Contributions" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/bbs3-q5us

property e:bbs3-q5us t:meta.view v:id=bbs3-q5us v:category="City Government" v:averageRating=0 v:name="2009 Campaign Contributions" v:attribution="Campaign Finance Board (CFB)"

property e:bbs3-q5us t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bbs3-q5us t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| election | officecd | candid | canclass | candlast     | candfirst | candmi | committee | filing | schedule | pageno | sequenceno | refno    | date       | refunddate | name                   | c_code | strno | strname       | apartment | boroughcd | occupation | empname  | empstrno | empstrname | amnt     | matchamnt | prevamnt | pay_method | intermno | intermname | intstrno | intstrnm | intaptno | intst | intzip | intempname | intempstno | intempstnm | intempcity | intempst | intoccupa | purposecd | exemptcd | adjtypecd | rr_ind | seg_ind | int_c_code | 
| ======== | ======== | ====== | ======== | ============ | ========= | ====== | ========= | ====== | ======== | ====== | ========== | ======== | ========== | ========== | ====================== | ====== | ===== | ============= | ========= | ========= | ========== | ======== | ======== | ========== | ======== | ========= | ======== | ========== | ======== | ========== | ======== | ======== | ======== | ===== | ====== | ========== | ========== | ========== | ========== | ======== | ========= | ========= | ======== | ========= | ====== | ======= | ========== | 
|          |          |        | CANCLASS | CANDLAST     | CANDFIRST | CANDMI | COMMITTEE |        | SCHEDULE | PAGENO | SEQUENCENO | REFNO    |            |            | NAME                   | C_CODE |       | STRNAME       | APARTMENT | BOROUGHCD | OCCUPATION | EMPNAME  |          | EMPSTRNAME |          |           |          |            |          | INTERMNAME | INTSTRNO | INTSTRNM | INTAPTNO | INTST |        | INTEMPNAME |            | INTEMPSTNM | INTEMPCITY | INTEMPST | INTOCCUPA | PURPOSECD | EXEMPTCD |           | RR_IND | SEG_IND | INT_C_CODE | 
| 2009     | 3        |        | UN       | Carrion, Jr. | Adolfo    |        | K         | 4      | M        |        |            | R0005211 | 1197273600 | 1199260800 | 1725 Crosby Realty LLC | LLC    |       |               |           |           |            |          |          |            | -1000.00 | 0         | 0        | 0          |          |            |          |          |          |       |        |            |            |            |            |          |           |           |          | 1         | N      | N       |            | 
| 2009     | 3        |        | UN       | Carrion, Jr. | Adolfo    |        | K         | 4      | ABC      |        |            | R0004413 | 1197273600 |            | 1725 Crosby Realty LLC | LLC    |       |               |           |           |            |          |          |            | 1000.00  | 0         | 0        | 2          |          |            |          |          |          |       |        |            |            |            |            |          |           |           |          |           | N      | N       |            | 
| 2009     | 1        | 1466   | NP       | Burck        | Robert    | J      | H         | 12     | ABC      |        |            | R0000953 | 1248937200 |            | a, j                   | IND    |       |               |           | Z         |            | j school |          |            | 15.00    | 0         | 0        | 1          |          |            |          |          |          |       |        |            |            |            |            |          |           |           |          |           | N      | N       |            | 
| 2009     | 6        | 1155   | UN       | Simon        | Brian     | W      | H         | 4      | ABC      |        |            | R0000085 | 1187420400 |            | Abena, Nzingha         | IND    |       |               |           | Q         | Retired    |          |          |            | 50.00    | 50.00     | 10.00    | 1          |          |            |          |          |          |       |        |            |            |            |            |          |           |           |          |           | N      | N       |            | 
| 2009     | 1        | 1466   | NP       | Burck        | Robert    | J      | H         | 12     | ABC      |        |            | R0001062 | 1249974000 |            | able, trice            | IND    |       |               |           | Z         |            | actress  |          |            | 15.00    | 0         | 0        | 1          |          |            |          |          |          |       |        |            |            |            |            |          |           |           |          |           | N      | N       |            | 
| 2009     | 5        | 1285   | P        | Chandra      | Ashok     |        | H         | 14     | ABC      |        |            | R0001238 | 1255503600 |            | Abraham, John          | IND    |       |               |           | Z         |            |          |          |            | 200.00   | 0         | 0        | 2          |          |            |          |          |          |       |        |            |            |            |            |          |           |           |          |           | N      | N       |            | 
| 2009     | 1        |        | UN       | Weiner       | Anthony   | D      | J         | 3      | ABC      |        |            | R0001183 | 1181804400 |            | AC I ManahawkinLLC     | LLC    | 20    | E Sunrise Hwy |           | Z         |            |          |          |            | 2200.00  | 0         | 0        | 2          |          |            |          |          |          |       |        |            |            |            |            |          |           |           |          |           | N      | N       |            | 
| 2009     | 1        |        | UN       | Weiner       | Anthony   | D      | J         | 7      | M        |        |            | R0007352 | 1181804400 | 1236754800 | AC I ManahawkinLLC     | LLC    | 20    | E Sunrise Hwy |           | Z         |            |          |          |            | -2200.00 | 0         | 0        | 0          |          |            |          |          |          |       |        |            |            |            |            |          |           |           |          | 2         | N      | N       |            | 
| 2009     | 5        | 1304   | P        | Santana      | Miguel    |        | H         | 8      | ABC      |        |            | R0000146 | 1238050800 |            | Acosta, Julio          | IND    |       |               |           | Z         |            |          |          |            | 40.00    | 0         | 0        | 2          |          |            |          |          |          |       |        |            |            |            |            |          |           |           |          |           | N      | N       |            | 
```