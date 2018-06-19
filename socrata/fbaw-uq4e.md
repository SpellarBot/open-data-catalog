# 2003 Campaign Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2003-campaign-expenditures-22163) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fbaw-uq4e) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fbaw-uq4e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fbaw-uq4e/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fbaw-uq4e |
| Name | 2003 Campaign Expenditures |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T21:58:52Z |
| Publication Date | 2013-06-21T20:04:48Z |

## Description

A listing of expenditures for candidates for City office during 2001 election cycle

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
| No       |                | inv_date   | INV_DATE   | date      | date        |
| Yes      | time           | date       | DATE       | date      | date        |
| Yes      | series tag     | name       | NAME       | text      | text        |
| Yes      | series tag     | c_code     | C_CODE     | text      | text        |
| Yes      | series tag     | org_ind    | ORG_IND    | text      | text        |
| Yes      | series tag     | strno      | STRNO      | text      | text        |
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
series e:fbaw-uq4e d:2003-04-12T07:00:00.000Z t:candlast=Comrie t:purposecd=CONSV t:candid=420 t:c_code=OTHR t:purpose="Constituent Svcs" t:canclass=P t:candmi=G t:seg_ind=N t:schedule=F t:candfirst=Leroy t:refno=R0001654 t:pay_method=Final t:committee=J t:org_ind=Y t:name="103RD PRECINCT COMM.COUNCIL" t:explain="TKTS. COMM. EVENT" t:rr_ind=N m:amnt=100 m:election=2003 m:officecd=5 m:filing=4

series e:fbaw-uq4e d:2003-06-20T07:00:00.000Z t:candlast=Gleason t:purposecd=OTHER t:candid=763 t:c_code=ORG t:purpose="Other: explntion" t:canclass=P t:candmi=J t:seg_ind=N t:schedule=F t:candfirst=Peter t:refno=R0000262 t:pay_method=Final t:committee=H t:org_ind=Y t:name="1ST PCT. COMMUNITY COUNCIL" t:explain="LUNCH EVENT" t:rr_ind=N m:amnt=150 m:election=2003 m:officecd=5 m:filing=4

series e:fbaw-uq4e d:2003-06-19T07:00:00.000Z t:candlast=Montague t:purposecd=OTHER t:candid=CB t:c_code=ORG t:purpose="Other: explntion" t:canclass=P t:candmi=M t:seg_ind=N t:schedule=F t:candfirst=Virginia t:refno=R0000530 t:pay_method=Final t:committee=H t:org_ind=Y t:name="2304-2306 LLC" t:explain="OFFICE RENT" t:rr_ind=N m:amnt=1500 m:election=2003 m:officecd=5 m:filing=5
```

## Meta Commands

```ls
metric m:election p:integer l:ELECTION t:dataTypeName=number

metric m:officecd p:integer l:OFFICECD t:dataTypeName=number

metric m:filing p:integer l:FILING t:dataTypeName=number

metric m:amnt p:float l:AMNT t:dataTypeName=number

entity e:fbaw-uq4e l:"2003 Campaign Expenditures" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/fbaw-uq4e

property e:fbaw-uq4e t:meta.view v:id=fbaw-uq4e v:category="City Government" v:averageRating=0 v:name="2003 Campaign Expenditures" v:attribution="Campaign Finance Board (CFB)"

property e:fbaw-uq4e t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fbaw-uq4e t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| election | officecd | candid | canclass | candlast | candfirst | candmi | committee | filing | schedule | pageno | sequenceno | refno    | inv_date   | date       | name                        | c_code | org_ind | strno | strname | apartment | pay_method | amnt    | purposecd | purpose          | explain           | exemptcd | rr_ind | seg_ind | 
| ======== | ======== | ====== | ======== | ======== | ========= | ====== | ========= | ====== | ======== | ====== | ========== | ======== | ========== | ========== | =========================== | ====== | ======= | ===== | ======= | ========= | ========== | ======= | ========= | ================ | ================= | ======== | ====== | ======= | 
|          |          | CANDID | CANCLASS | CANDLAST | CANDFIRST | CANDMI | COMMITTEE |        | SCHEDULE | PAGENO | SEQUENCENO | REFNO    |            |            | NAME                        | C_CODE | ORG_IND | STRNO | STRNAME | APARTMENT | PAY_METHOD |         | PURPOSECD | PURPOSE          | EXPLAIN           | EXEMPTCD | RR_IND | SEG_IND | 
| 2003     | 5        | 420    | P        | Comrie   | Leroy     | G      | J         | 4      | F        |        |            | R0001654 | 1050130800 | 1050130800 | 103RD PRECINCT COMM.COUNCIL | OTHR   | Y       |       |         |           | Final      | 100.00  | CONSV     | Constituent Svcs | TKTS. COMM. EVENT |          | N      | N       | 
| 2003     | 5        | 763    | P        | Gleason  | Peter     | J      | H         | 4      | F        |        |            | R0000262 | 1056092400 | 1056092400 | 1ST PCT. COMMUNITY COUNCIL  | ORG    | Y       |       |         |           | Final      | 150.00  | OTHER     | Other: explntion | LUNCH EVENT       |          | N      | N       | 
| 2003     | 5        | CB     | P        | Montague | Virginia  | M      | H         | 5      | F        |        |            | R0000530 | 1056006000 | 1056006000 | 2304-2306 LLC               | ORG    | Y       |       |         |           | Final      | 1500.00 | OTHER     | Other: explntion | OFFICE RENT       |          | N      | N       | 
| 2003     | 5        | 732    | P        | Sasson   | Isaac     | M      | H         | 7      | F        |        |            | R0000840 | 1062486000 | 1062486000 | 3 GEN                       | ORG    | Y       |       |         |           | Final      | 4000.00 | CMAIL     | Campgn Mlngs     | DIRECT MAILING    |          | N      | N       | 
| 2003     | 5        | 732    | P        | Sasson   | Isaac     | M      | H         | 7      | F        |        |            | R0000851 | 1062918000 | 1062918000 | 3 GEN                       | ORG    | Y       |       |         |           | Final      | 5000.00 | CMAIL     | Campgn Mlngs     | PRINTING          |          | N      | N       | 
| 2003     | 5        | 732    | P        | Sasson   | Isaac     | M      | H         | 7      | F        |        |            | R0000854 | 1062918000 | 1062918000 | 3 GEN                       | ORG    | Y       |       |         |           | Final      | 2000.00 | CMAIL     | Campgn Mlngs     | MAILING           |          | N      | N       | 
| 2003     | 5        | 732    | P        | Sasson   | Isaac     | M      | H         | 7      | F        |        |            | R0000844 | 1062658800 | 1062658800 | 3 GEN                       | ORG    | Y       |       |         |           | Final      | 3000.00 | CMAIL     | Campgn Mlngs     | MAILING           |          | N      | N       | 
| 2003     | 5        | 732    | P        | Sasson   | Isaac     | M      | H         | 6      | F        |        |            | R0000620 | 1054191600 | 1054191600 | 3 GEN                       | ORG    | Y       |       |         |           | Final      | 50.00   | CMAIL     | Campgn Mlngs     | PRINTING          |          | N      | N       | 
| 2003     | 5        | 732    | P        | Sasson   | Isaac     | M      | H         | 6      | F        |        |            | R0000623 | 1054191600 | 1054191600 | 3 GEN                       | ORG    | Y       |       |         |           | Final      | 450.00  | CMAIL     | Campgn Mlngs     | PRINTING          |          | N      | N       | 
```