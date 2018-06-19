# 2009 Campaign Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2009-campaign-expenditures-6c91e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vg63-xw6u) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vg63-xw6u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vg63-xw6u/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vg63-xw6u |
| Name | 2009 Campaign Expenditures |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T23:07:46Z |
| Publication Date | 2013-06-21T19:52:08Z |

## Description

A listing of campaign expenditures for candidates for City office during the 2009 election cycle

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
series e:vg63-xw6u d:2009-12-24T08:00:00.000Z t:candlast=Hackshaw t:purposecd=PROFL t:candid=405 t:c_code=CORP t:purpose="Prof. Srvcs." t:canclass=P t:candmi=H t:seg_ind=N t:schedule=F t:candfirst=Rock t:refno=R0001492 t:pay_method=Full t:committee=H t:org_ind=Y t:name="1 & 1 Internet Inc." t:explain=Website t:rr_ind=N m:amnt=29.97 m:election=2009 m:officecd=5 m:filing=16

series e:vg63-xw6u d:2009-06-26T07:00:00.000Z t:candlast=Hackshaw t:purposecd=LITER t:candid=405 t:c_code=CORP t:purpose="Campgn Lit." t:canclass=P t:candmi=H t:seg_ind=N t:schedule=F t:candfirst=Rock t:refno=R0000715 t:pay_method=Full t:committee=H t:org_ind=Y t:name="1 & 1 Internet Inc." t:explain="website building" t:rr_ind=N m:amnt=29.97 m:election=2009 m:officecd=5 m:filing=9

series e:vg63-xw6u d:2009-09-23T07:00:00.000Z t:candlast=Hackshaw t:purposecd=PROFL t:candid=405 t:c_code=CORP t:purpose="Prof. Srvcs." t:canclass=P t:candmi=H t:seg_ind=N t:schedule=F t:candfirst=Rock t:refno=R0001370 t:pay_method=Full t:committee=H t:org_ind=Y t:name="1 & 1 Internet Inc." t:explain=website t:rr_ind=N m:amnt=29.97 m:election=2009 m:officecd=5 m:filing=13
```

## Meta Commands

```ls
metric m:election p:integer l:ELECTION t:dataTypeName=number

metric m:officecd p:integer l:OFFICECD t:dataTypeName=number

metric m:filing p:integer l:FILING t:dataTypeName=number

metric m:strno p:integer l:STRNO t:dataTypeName=number

metric m:amnt p:float l:AMNT t:dataTypeName=number

entity e:vg63-xw6u l:"2009 Campaign Expenditures" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/vg63-xw6u

property e:vg63-xw6u t:meta.view v:id=vg63-xw6u v:category="City Government" v:averageRating=0 v:name="2009 Campaign Expenditures" v:attribution="Campaign Finance Board (CFB)"

property e:vg63-xw6u t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vg63-xw6u t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| election | officecd | candid | canclass | candlast  | candfirst | candmi | committee | filing | schedule | pageno | sequenceno | refno    | inv_date   | date       | name                | c_code | org_ind | strno | strname | apartment | pay_method | amnt   | purposecd | purpose          | explain           | exemptcd | rr_ind | seg_ind | 
| ======== | ======== | ====== | ======== | ========= | ========= | ====== | ========= | ====== | ======== | ====== | ========== | ======== | ========== | ========== | =================== | ====== | ======= | ===== | ======= | ========= | ========== | ====== | ========= | ================ | ================= | ======== | ====== | ======= | 
| 2009     | 5        | 405    | P        | Hackshaw  | Rock      | H      | H         | 16     | F        |        |            | R0001492 | 1261641600 | 1261641600 | 1 & 1 Internet Inc. | CORP   | Y       |       |         |           | Full       | 29.97  | PROFL     | Prof. Srvcs.     | Website           |          | N      | N       | 
| 2009     | 5        | 405    | P        | Hackshaw  | Rock      | H      | H         | 9      | F        |        |            | R0000715 | 1245999600 | 1245999600 | 1 & 1 Internet Inc. | CORP   | Y       |       |         |           | Full       | 29.97  | LITER     | Campgn Lit.      | website building  |          | N      | N       | 
| 2009     | 5        | 405    | P        | Hackshaw  | Rock      | H      | H         | 13     | F        |        |            | R0001370 | 1253689200 | 1253689200 | 1 & 1 Internet Inc. | CORP   | Y       |       |         |           | Full       | 29.97  | PROFL     | Prof. Srvcs.     | website           |          | N      | N       | 
| 2009     | 5        | 459    | P        | Koppell   | G. Oliver |        | L         | 3      | F        |        |            | R0000871 | 1175410800 | 1176706800 | 1 800 we answer     | CORP   | Y       |       |         |           | Final      | 131.00 | OFFCE     | Office Expenses  | answering service |          | N      | N       | 
| 2009     | 5        | 459    | P        | Koppell   | G. Oliver |        | L         | 1      | F        |        |            | R0000555 | 1149663600 | 1149663600 | 1 800 we answer     | CORP   | Y       |       |         |           | Final      | 107.21 | OFFCE     | Office Expenses  | answering svc     |          | N      | N       | 
| 2009     | 5        | 459    | P        | Koppell   | G. Oliver |        | L         | 4      | F        |        |            | R0001048 | 1159858800 | 1159858800 | 1 800 we answer     | CORP   | Y       |       |         |           | Full       | 0.30   | OTHER     | Other: explntion | CHECK FEE         |          | N      | N       | 
| 2009     | 5        | 459    | P        | Koppell   | G. Oliver |        | L         | 4      | F        |        |            | R0001052 | 1176706800 | 1176706800 | 1 800 we answer     | CORP   | Y       |       |         |           | Full       | 0.61   | OFFCE     | Office Expenses  | ANSWER SVC        |          | N      | N       | 
| 2009     | 5        | 459    | P        | Koppell   | G. Oliver |        | L         | 5      | F        |        |            | R0001021 | 1211612400 | 1211612400 | 1 800 we answer     | CORP   | Y       |       |         |           | Full       | 130.81 | LITER     | Campgn Lit.      | ANSWER SVC        |          | N      | N       | 
| 2009     | 2        | 326    | P        | de Blasio | Bill      |        | L         | 5      | F        |        |            | R0003535 | 1200038400 | 1200297600 | 1-800 Flower        | CORP   | Y       |       |         |           | Final      | 56.00  | OTHER     | Other: explntion | flowers           |          | N      | N       | 
| 2009     | 2        | 326    | P        | de Blasio | Bill      |        | L         | 8      | F        |        |            | R0007355 | 1240902000 | 1240988400 | 1-800 Flower        | CORP   | Y       |       |         |           | Full       | 42.79  | OTHER     | Other: explntion | flowers           |          | N      | N       | 
```