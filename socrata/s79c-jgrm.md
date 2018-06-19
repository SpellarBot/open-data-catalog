# 2003 Campaign Contributions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2003-campaign-contributions-4e48a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/s79c-jgrm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/s79c-jgrm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/s79c-jgrm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | s79c-jgrm |
| Name | 2003 Campaign Contributions |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T22:29:40Z |
| Publication Date | 2013-06-21T19:54:59Z |

## Description

A listing of campaign contributions for candidates for City office during the 2003 election cycle

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
series e:s79c-jgrm d:2003-10-22T07:00:00.000Z t:strname="WEST 43RD STREET" t:candlast=James t:candid=480 t:c_code=PCOMP t:canclass=P t:seg_ind=N t:refno=R0001449 t:candfirst=Letitia t:schedule=ABC t:committee=I t:name="1199/SEIU NYS POLITICAL ACTION" t:rr_ind=N t:boroughcd=M m:amnt=2750 m:prevamnt=0 m:election=2003 m:pay_method=2 m:strno=310 m:officecd=5 m:filing=10 m:matchamnt=0

series e:s79c-jgrm d:2003-06-27T07:00:00.000Z t:seg_ind=N t:schedule=ABC t:candfirst=Leroy t:refno=R0001562 t:committee=J t:candlast=Comrie t:name="A CUOMO FOR GOVERNOR, INC" t:candid=420 t:c_code=PCOMP t:rr_ind=N t:canclass=P t:candmi=G m:amnt=500 m:prevamnt=0 m:election=2003 m:pay_method=2 m:officecd=5 m:filing=4 m:matchamnt=0

series e:s79c-jgrm d:2003-10-30T08:00:00.000Z t:seg_ind=N t:schedule=ABC t:candfirst=Christine t:refno=R0001566 t:committee=J t:candlast=Quinn t:name="ABATE, CATHERINE M" t:candid=204 t:c_code=IND t:rr_ind=N t:canclass=P t:candmi=C m:amnt=75 m:prevamnt=0 m:election=2003 m:pay_method=2 m:officecd=5 m:filing=10 m:matchamnt=0
```

## Meta Commands

```ls
metric m:election p:integer l:ELECTION t:dataTypeName=number

metric m:officecd p:integer l:OFFICECD t:dataTypeName=number

metric m:filing p:integer l:FILING t:dataTypeName=number

metric m:strno p:integer l:STRNO t:dataTypeName=number

metric m:empstrno p:integer l:EMPSTRNO t:dataTypeName=number

metric m:amnt p:integer l:AMNT t:dataTypeName=number

metric m:matchamnt p:integer l:MATCHAMNT t:dataTypeName=number

metric m:prevamnt p:integer l:PREVAMNT t:dataTypeName=number

metric m:pay_method p:integer l:PAY_METHOD t:dataTypeName=number

metric m:intermno p:integer l:INTERMNO t:dataTypeName=number

metric m:intempstno p:integer l:INTEMPSTNO t:dataTypeName=number

metric m:adjtypecd p:integer l:ADJTYPECD t:dataTypeName=number

entity e:s79c-jgrm l:"2003 Campaign Contributions" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/s79c-jgrm

property e:s79c-jgrm t:meta.view v:id=s79c-jgrm v:category="City Government" v:averageRating=0 v:name="2003 Campaign Contributions" v:attribution="Campaign Finance Board (CFB)"

property e:s79c-jgrm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:s79c-jgrm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| election | officecd | candid | canclass | candlast   | candfirst | candmi | committee | filing | schedule | pageno | sequenceno | refno    | date       | refunddate | name                           | c_code | strno | strname                | apartment | boroughcd | occupation  | empname                  | empstrno | empstrname | amnt | matchamnt | prevamnt | pay_method | intermno | intermname       | intstrno | intstrnm | intaptno | intst | intzip | intempname                 | intempstno | intempstnm    | intempcity | intempst | intoccupa                | purposecd | exemptcd | adjtypecd | rr_ind | seg_ind | int_c_code | 
| ======== | ======== | ====== | ======== | ========== | ========= | ====== | ========= | ====== | ======== | ====== | ========== | ======== | ========== | ========== | ============================== | ====== | ===== | ====================== | ========= | ========= | =========== | ======================== | ======== | ========== | ==== | ========= | ======== | ========== | ======== | ================ | ======== | ======== | ======== | ===== | ====== | ========================== | ========== | ============= | ========== | ======== | ======================== | ========= | ======== | ========= | ====== | ======= | ========== | 
|          |          | CANDID | CANCLASS | CANDLAST   | CANDFIRST | CANDMI | COMMITTEE |        | SCHEDULE | PAGENO | SEQUENCENO | REFNO    |            |            | NAME                           | C_CODE |       | STRNAME                | APARTMENT | BOROUGHCD | OCCUPATION  | EMPNAME                  |          | EMPSTRNAME |      |           |          |            |          | INTERMNAME       | INTSTRNO | INTSTRNM | INTAPTNO | INTST |        | INTEMPNAME                 |            | INTEMPSTNM    | INTEMPCITY | INTEMPST | INTOCCUPA                | PURPOSECD | EXEMPTCD |           | RR_IND | SEG_IND | INT_C_CODE | 
| 2003     | 5        | 480    | P        | James      | Letitia   |        | I         | 10     | ABC      |        |            | R0001449 | 1066806000 |            | 1199/SEIU NYS POLITICAL ACTION | PCOMP  | 310   | WEST 43RD STREET       |           | M         |             |                          |          |            | 2750 | 0         | 0        | 2          |          |                  |          |          |          |       |        |                            |            |               |            |          |                          |           |          |           | N      | N       |            | 
| 2003     | 5        | 420    | P        | Comrie     | Leroy     | G      | J         | 4      | ABC      |        |            | R0001562 | 1056697200 |            | A CUOMO FOR GOVERNOR, INC      | PCOMP  |       |                        |           |           |             |                          |          |            | 500  | 0         | 0        | 2          |          |                  |          |          |          |       |        |                            |            |               |            |          |                          |           |          |           | N      | N       |            | 
| 2003     | 5        | 204    | P        | Quinn      | Christine | C      | J         | 10     | ABC      |        |            | R0001566 | 1067500800 |            | ABATE, CATHERINE M             | IND    |       |                        |           |           |             |                          |          |            | 75   | 0         | 0        | 2          |          |                  |          |          |          |       |        |                            |            |               |            |          |                          |           |          |           | N      | N       |            | 
| 2003     | 5        | 527    | P        | Fidler     | Lewis     | A      | I         | 4      | ABC      |        |            | R0000473 | 1049616000 |            | ABRAMOWITZ, ALAN               | IND    |       |                        |           | Z         | RETIRED     |                          |          |            | 25   | 0         | 0        | 2          |          |                  |          |          |          |       |        |                            |            |               |            |          |                          |           |          |           | N      | N       |            | 
| 2003     | 5        | 361    | P        | Rivera     | Joel      |        | J         | 10     | D        |        |            | R0001622 | 1054882800 |            | Abreu, Rafael                  | IND    |       |                        |           |           |             |                          |          |            | 1875 | 0         | 0        | 0          | 102      | Perez II, Radame |          |          |          | NY    | 10469  | Mastermind Management, LTD | 668        | Crescent Ave. | Bronx      | NY       | Executive Vice President | FUNDR     |          |           | N      |         | IND        | 
| 2003     | 5        | 353    | P        | Rodriguez  | Ydanis    | A      | I         | 11     | D        |        |            | R0002022 | 1072857600 |            | Adames, Basilia                | IND    |       |                        |           |           |             |                          |          |            | 100  | 0         | 0        | 0          |          |                  |          |          |          |       |        |                            |            |               |            |          |                          | WAGES     |          |           | N      |         |            | 
| 2003     | 5        | 271    | P        | McMahon    | Michael   | E      | J         | 4      | ABC      |        |            | R0001794 | 1046937600 |            | ADB PROPERTIES LLC             | LLC    | 110   | EAST SHORE CULVER ROAD |           | Z         |             |                          |          |            | 250  | 0         | 0        | 2          |          |                  |          |          |          |       |        |                            |            |               |            |          |                          |           |          |           | N      | N       |            | 
| 2003     | 5        | 560    | P        | Bernace    | Victor    | A      | J         | 6      | ABC      |        |            | R0000869 | 1061535600 |            | AGRAMONTE, LUIS                | IND    |       |                        |           | X         | TAXI DRIVER | RIVERSIDE RADIO DISPATCH |          |            | 20   | 20        | 0        | 1          |          |                  |          |          |          |       |        |                            |            |               |            |          |                          |           |          |           | N      | N       |            | 
| 2003     | 5        | 272    | P        | Monserrate | Hiram     |        | J         | 7      | ABC      |        |            | R0001527 | 1062572400 |            | AGUSTA, PHILIP P               | IND    |       |                        |           |           |             |                          |          |            | 250  | 0         | 0        | 2          |          |                  |          |          |          |       |        |                            |            |               |            |          |                          |           |          |           | N      | N       |            | 
```