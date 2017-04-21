# 2005 Campaign Contributions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2005-campaign-contributions-8fd6d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/64gx-bycn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/64gx-bycn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/64gx-bycn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 64gx-bycn |
| Name | 2005 Campaign Contributions |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T22:38:06Z |
| Publication Date | 2013-06-21T20:03:14Z |

## Description

A listing of campaign contributions for candidates for City office during the 2005 election cycle

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
| Yes      | numeric metric | intstrno   | INTSTRNO   | number    | number      |
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
series e:64gx-bycn d:2004-12-15T08:00:00.000Z t:seg_ind=N t:schedule=ABC t:candfirst=Bill t:refno=R0001609 t:committee=K t:candlast=Perkins t:name="121st Street Block Association" t:candid=D2 t:c_code=OTHR t:rr_ind=N t:canclass=P m:amnt=200 m:prevamnt=0 m:election=2005 m:pay_method=2 m:officecd=4 m:filing=6 m:matchamnt=0

series e:64gx-bycn d:2005-03-04T08:00:00.000Z t:intermname="MURRAY, PAUL" t:intempname="LOEWEN DEVELOPMENT-HOPKINSON L" t:candlast=Wright t:intempst=NY t:intzip=10573 t:candid=828 t:c_code=LLC t:intoccupa=DEVELOPER t:canclass=P t:intempcity=LARCHMONT t:seg_ind=N t:int_c_code=IND t:schedule=ABC t:candfirst=Keith t:refno=R0000652 t:committee=H t:name="504 WEST 136TH STREET LLC" t:intempstnm="BOSTON POST ROAD" t:intst=NY t:rr_ind=N m:amnt=250 m:prevamnt=0 m:election=2005 m:pay_method=2 m:intermno=1 m:intempstno=2365 m:officecd=4 m:filing=7 m:matchamnt=0

series e:64gx-bycn d:2005-04-08T07:00:00.000Z t:seg_ind=N t:schedule=ABC t:candfirst=Adriano t:refno=R0002544 t:committee=H t:candlast=Espaillat t:name="505 West 168th Realty" t:candid=93 t:c_code=LLC t:rr_ind=N t:canclass=P m:amnt=500 m:prevamnt=0 m:election=2005 m:pay_method=2 m:officecd=4 m:filing=8 m:matchamnt=0
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

metric m:intstrno p:integer l:INTSTRNO t:dataTypeName=number

metric m:intempstno p:integer l:INTEMPSTNO t:dataTypeName=number

metric m:adjtypecd p:integer l:ADJTYPECD t:dataTypeName=number

entity e:64gx-bycn l:"2005 Campaign Contributions" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/64gx-bycn

property e:64gx-bycn t:meta.view v:id=64gx-bycn v:category="City Government" v:averageRating=0 v:name="2005 Campaign Contributions" v:attribution="Campaign Finance Board (CFB)"

property e:64gx-bycn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:64gx-bycn t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| election | officecd | candid | canclass | candlast      | candfirst | candmi | committee | filing | schedule | pageno | refno    | date       | refunddate | name                           | c_code | strno | strname | apartment | boroughcd | occupation | empname                        | empstrno | empstrname | amnt    | matchamnt | prevamnt | pay_method | intermno | intermname   | intstrno | intstrnm | intaptno | intst | intzip | intempname                     | intempstno | intempstnm       | intempcity | intempst | intoccupa | purposecd | exemptcd | adjtypecd | rr_ind | seg_ind | int_c_code | 
| ======== | ======== | ====== | ======== | ============= | ========= | ====== | ========= | ====== | ======== | ====== | ======== | ========== | ========== | ============================== | ====== | ===== | ======= | ========= | ========= | ========== | ============================== | ======== | ========== | ======= | ========= | ======== | ========== | ======== | ============ | ======== | ======== | ======== | ===== | ====== | ============================== | ========== | ================ | ========== | ======== | ========= | ========= | ======== | ========= | ====== | ======= | ========== | 
|          |          | CANDID | CANCLASS | CANDLAST      | CANDFIRST | CANDMI | COMMITTEE |        | SCHEDULE | PAGENO | REFNO    |            |            | NAME                           | C_CODE |       | STRNAME | APARTMENT | BOROUGHCD | OCCUPATION | EMPNAME                        |          | EMPSTRNAME |         |           |          |            |          | INTERMNAME   |          | INTSTRNM | INTAPTNO | INTST |        | INTEMPNAME                     |            | INTEMPSTNM       | INTEMPCITY | INTEMPST | INTOCCUPA | PURPOSECD | EXEMPTCD |           | RR_IND | SEG_IND | INT_C_CODE | 
| 2005     | 4        | D2     | P        | Perkins       | Bill      |        | K         | 6      | ABC      |        | R0001609 | 1103097600 |            | 121st Street Block Association | OTHR   |       |         |           |           |            |                                |          |            | 200.00  | 0         | 0        | 2          |          |              |          |          |          |       |        |                                |            |                  |            |          |           |           |          |           | N      | N       |            | 
| 2005     | 4        | 828    | P        | Wright        | Keith     |        | H         | 7      | ABC      |        | R0000652 | 1109923200 |            | 504 WEST 136TH STREET LLC      | LLC    |       |         |           |           |            |                                |          |            | 250.00  | 0         | 0        | 2          | 1        | MURRAY, PAUL |          |          |          | NY    | 10573  | LOEWEN DEVELOPMENT-HOPKINSON L | 2365       | BOSTON POST ROAD | LARCHMONT  | NY       | DEVELOPER |           |          |           | N      | N       | IND        | 
| 2005     | 4        | 93     | P        | Espaillat     | Adriano   |        | H         | 8      | ABC      |        | R0002544 | 1112943600 |            | 505 West 168th Realty          | LLC    |       |         |           |           |            |                                |          |            | 500.00  | 0         | 0        | 2          |          |              |          |          |          |       |        |                                |            |                  |            |          |           |           |          |           | N      | N       |            | 
| 2005     | 4        | 93     | P        | Espaillat     | Adriano   |        | H         | 11     | M        |        | R0004813 | 1112943600 | 1114066800 | 505 West 168th Realty          | LLC    |       |         |           |           |            |                                |          |            | -500.00 | 0         | 0        | 0          |          |              |          |          |          |       |        |                                |            |                  |            |          |           |           |          | 1         | N      | N       |            | 
| 2005     | 4        | 148    | P        | Stringer      | Scott     | M      | J         | 7      | ABC      |        | R0007182 | 1110441600 |            | Aaronson, Jo Ann               | IND    |       |         |           | M         |            |                                |          |            | 50.00   | 50.00     | 0        | 2          |          |              |          |          |          |       |        |                                |            |                  |            |          |           |           |          |           | N      | N       |            | 
| 2005     | 3        | 260    | P        | Thompson, Jr. | William   | C      | J         | 6      | ABC      |        | R0010915 | 1105430400 |            | Abato, John P                  | IND    |       |         |           | M         |            |                                |          |            | 1500.00 | 0         | 0        | 2          |          |              |          |          |          |       |        |                                |            |                  |            |          |           |           |          |           | N      | N       |            | 
| 2005     | 5        | 232    | P        | Weprin        | David     | I      | K         | 16     | ABC      |        | R0002582 | 1130569200 |            | Abbe, Richard                  | IND    |       |         |           |           |            | Iroquois Capital Management LL |          |            | 2750.00 | 0         | 0        | 2          |          |              |          |          |          |       |        |                                |            |                  |            |          |           |           |          |           | N      | N       |            | 
| 2005     | 5        | 867    | P        | Dickens       | Inez      | E      | H         | 16     | ABC      |        | R0001965 | 1131264000 |            | Abraham, Leah                  | IND    |       |         |           | Z         | Owner      | Sette Panni Bakery             |          |            | 500.00  | 0         | 0        | 2          |          |              |          |          |          |       |        |                                |            |                  |            |          |           |           |          |           | N      | N       |            | 
| 2005     | 5        | 854    | P        | Duggan        | Essie     | M      | H         | 8      | ABC      |        | R0000037 | 1114671600 |            | Abraham, Roy                   | IND    |       |         |           | Z         |            | Self Employed                  |          |            | 100.00  | 0         | 0        | 2          |          |              |          |          |          |       |        |                                |            |                  |            |          |           |           |          |           | N      | N       |            | 
```