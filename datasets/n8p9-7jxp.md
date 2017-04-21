# 2013 Campaign Contributions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-campaign-contributions-4a482) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/n8p9-7jxp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/n8p9-7jxp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/n8p9-7jxp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | n8p9-7jxp |
| Name | 2013 Campaign Contributions |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T23:23:00Z |
| Publication Date | 2013-06-21T19:50:31Z |

## Description

A listing of campaign contributions for candidates for City office during the 2013 election cycle

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | numeric metric | election   | ELECTION   | number    | number      |
| Yes      | numeric metric | officecd   | OFFICECD   | number    | number      |
| Yes      | series tag     | candid     | CANDID     | text      | text        |
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
series e:n8p9-7jxp d:2007-06-14T07:00:00.000Z t:strname="E Sunrise Hwy" t:candlast=Weiner t:candid=BB t:c_code=LLC t:canclass=UN t:candmi=D t:seg_ind=N t:refno=R0001183 t:candfirst=Anthony t:schedule=ABC t:committee=J t:name="AC I ManahawkinLLC" t:rr_ind=N t:boroughcd=Z m:amnt=2200 m:prevamnt=0 m:election=2013 m:pay_method=2 m:strno=20 m:officecd=1 m:filing=1 m:matchamnt=0

series e:n8p9-7jxp d:2007-06-14T07:00:00.000Z t:strname="E Sunrise Hwy" t:candlast=Weiner t:candid=BB t:c_code=LLC t:canclass=UN t:candmi=D t:seg_ind=N t:refno=R0007352 t:candfirst=Anthony t:schedule=M t:committee=J t:name="AC I ManahawkinLLC" t:rr_ind=N t:boroughcd=Z m:adjtypecd=2 m:amnt=-2200 m:prevamnt=0 m:election=2013 m:pay_method=0 m:strno=20 m:officecd=1 m:filing=1 m:matchamnt=0

series e:n8p9-7jxp d:2008-07-08T07:00:00.000Z t:intermname="Adelsberg, Steven" t:occupation=CPA t:intempname="Samuel Adelsberg & Co." t:candlast=Weiner t:intempst=NY t:empname="S. Adelsburg" t:intzip=11237 t:candid=BB t:c_code=IND t:intoccupa=Accountant t:canclass=UN t:candmi=D t:intempcity="Great Neck" t:seg_ind=N t:int_c_code=IND t:schedule=ABC t:candfirst=Anthony t:refno=R0005292 t:committee=J t:name="Adelsburg, Erwin" t:intempstnm="Northway Blvd" t:empstrname="Northern Blvd" t:intst=NY t:rr_ind=N m:empstrno=280 m:amnt=3500 m:prevamnt=0 m:election=2013 m:pay_method=4 m:intermno=49 m:intempstno=280 m:officecd=1 m:filing=1 m:matchamnt=0
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

metric m:pay_method p:integer l:PAY_METHOD t:dataTypeName=number

metric m:intermno p:integer l:INTERMNO t:dataTypeName=number

metric m:intempstno p:integer l:INTEMPSTNO t:dataTypeName=number

metric m:adjtypecd p:integer l:ADJTYPECD t:dataTypeName=number

entity e:n8p9-7jxp l:"2013 Campaign Contributions" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/n8p9-7jxp

property e:n8p9-7jxp t:meta.view v:id=n8p9-7jxp v:category="City Government" v:averageRating=0 v:name="2013 Campaign Contributions" v:attribution="Campaign Finance Board (CFB)"

property e:n8p9-7jxp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:n8p9-7jxp t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| election | officecd | candid | canclass | candlast  | candfirst | candmi | committee | filing | schedule | pageno | sequenceno | refno    | date       | refunddate | name               | c_code | strno | strname       | apartment | boroughcd | occupation | empname           | empstrno | empstrname    | amnt     | matchamnt | prevamnt | pay_method | intermno | intermname        | intstrno | intstrnm | intaptno | intst | intzip | intempname             | intempstno | intempstnm    | intempcity | intempst | intoccupa  | purposecd | exemptcd | adjtypecd | rr_ind | seg_ind | int_c_code | 
| ======== | ======== | ====== | ======== | ========= | ========= | ====== | ========= | ====== | ======== | ====== | ========== | ======== | ========== | ========== | ================== | ====== | ===== | ============= | ========= | ========= | ========== | ================= | ======== | ============= | ======== | ========= | ======== | ========== | ======== | ================= | ======== | ======== | ======== | ===== | ====== | ====================== | ========== | ============= | ========== | ======== | ========== | ========= | ======== | ========= | ====== | ======= | ========== | 
|          |          | CANDID | CANCLASS | CANDLAST  | CANDFIRST | CANDMI | COMMITTEE |        | SCHEDULE | PAGENO | SEQUENCENO | REFNO    |            |            | NAME               | C_CODE |       | STRNAME       | APARTMENT | BOROUGHCD | OCCUPATION | EMPNAME           |          | EMPSTRNAME    |          |           |          |            |          | INTERMNAME        | INTSTRNO | INTSTRNM | INTAPTNO | INTST |        | INTEMPNAME             |            | INTEMPSTNM    | INTEMPCITY | INTEMPST | INTOCCUPA  | PURPOSECD | EXEMPTCD |           | RR_IND | SEG_IND | INT_C_CODE | 
| 2013     | 1        | BB     | UN       | Weiner    | Anthony   | D      | J         | 1      | ABC      |        |            | R0001183 | 1181804400 |            | AC I ManahawkinLLC | LLC    | 20    | E Sunrise Hwy |           | Z         |            |                   |          |               | 2200.00  | 0         | 0        | 2          |          |                   |          |          |          |       |        |                        |            |               |            |          |            |           |          |           | N      | N       |            | 
| 2013     | 1        | BB     | UN       | Weiner    | Anthony   | D      | J         | 1      | M        |        |            | R0007352 | 1181804400 | 1236754800 | AC I ManahawkinLLC | LLC    | 20    | E Sunrise Hwy |           | Z         |            |                   |          |               | -2200.00 | 0         | 0        | 0          |          |                   |          |          |          |       |        |                        |            |               |            |          |            |           |          | 2         | N      | N       |            | 
| 2013     | 1        | BB     | UN       | Weiner    | Anthony   | D      | J         | 1      | ABC      |        |            | R0005292 | 1215500400 |            | Adelsburg, Erwin   | IND    |       |               |           |           | CPA        | S. Adelsburg      | 280      | Northern Blvd | 3500.00  | 0         | 0        | 4          | 49       | Adelsberg, Steven |          |          |          | NY    | 11237  | Samuel Adelsberg & Co. | 280        | Northway Blvd | Great Neck | NY       | Accountant |           |          |           | N      | N       | IND        | 
| 2013     | 6        | 1160   | UN       | Diaz, Jr. | Ruben     |        | L         | 1      | M        |        |            | R0003248 | 1278399600 | 1278658800 | Alicea, Victor     | IND    |       |               |           | M         |            |                   |          |               | -100.00  | 0         | 0        | 0          |          |                   |          |          |          |       |        |                        |            |               |            |          |            |           |          | 2         | N      | Y       |            | 
| 2013     | 1        | BB     | UN       | Weiner    | Anthony   | D      | J         | 1      | ABC      |        |            | R0003095 | 1200038400 |            | Almaya, Victor     | IND    |       |               |           |           |            |                   |          |               | 4950.00  | 0         | 0        | 4          |          |                   |          |          |          |       |        |                        |            |               |            |          |            |           |          |           | N      | N       |            | 
| 2013     | 6        | 361    | UN       | Rivera    | Joel      |        | L         | 1      | N        |        |            | R0000042 |            |            | Alvarez, Albert    | IND    |       |               |           |           |            |                   |          |               | 534.70   | 0         | 0        | 0          |          |                   |          |          |          |       |        |                        |            |               |            |          |            |           |          |           | N      | N       |            | 
| 2013     | 5        | 1093   | UN       | Dobrin    | Todd      | A      | H         | 1      | ABC      |        |            | R0000768 | 1210921200 |            | Amorosa, Denise    | IND    |       |               |           | Z         | Mom        | Self Employed Mom | 7        | Casey Ln      | 100.00   | 0         | 0        | 2          |          |                   |          |          |          |       |        |                        |            |               |            |          |            |           |          |           | N      | N       |            | 
| 2013     | 1        | BB     | UN       | Weiner    | Anthony   | D      | J         | 1      | ABC      |        |            | R0006379 | 1217314800 |            | Andrea, Mary       | IND    |       |               |           |           |            |                   |          |               | 1000.00  | 0         | 0        | 2          | 32       | Aquino, Robert J  |          |          |          | NY    | 11545  | Parkway Hospital       |            | 113th St      | Queens     | NY       | President  |           |          |           | N      | N       | IND        | 
| 2013     | 5        | 1159   | UN       | Narcisse  | Mercedes  |        | H         | 1      | ABC      |        |            | R0000344 | 1197532800 |            | aristide, marie    | IND    |       |               |           | K         | retired    |                   |          |               | 20.00    | 20.00     | 0        | 1          |          |                   |          |          |          |       |        |                        |            |               |            |          |            |           |          |           | N      | N       |            | 
```