# 2001 Campaign Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2001-campaign-expenditures-d19c0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/k3cd-yu9d) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/k3cd-yu9d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/k3cd-yu9d/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | k3cd-yu9d |
| Name | 2001 Campaign Expenditures |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T21:49:41Z |
| Publication Date | 2013-06-21T19:55:29Z |

## Description

A listing of expenditures for candidates for City office during the 2001 election cycle

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
series e:k3cd-yu9d d:2001-07-31T07:00:00.000Z t:candlast=Chen t:purposecd=PETIT t:candid=CF t:c_code=ORG t:purpose="Petition Expns." t:canclass=P t:candmi=T t:seg_ind=N t:exemptcd=P t:schedule=F t:refno=P0005-08 t:candfirst=Ethel t:pay_method=Unknown t:committee=A t:org_ind=Y t:rr_ind=N m:amnt=4799 m:election=2001 m:officecd=5 m:filing=10

series e:k3cd-yu9d d:2011-09-13T14:49:44.000Z t:candlast=Brown t:purposecd=UNKN t:candid=EC t:c_code=IND t:purpose=Unknown t:canclass=P t:candmi=D t:seg_ind=N t:schedule=F t:refno=P0001-09 t:candfirst=Everly t:pay_method=Unknown t:committee=A t:org_ind=N t:rr_ind=N m:amnt=166 m:election=2001 m:officecd=5 m:filing=14

series e:k3cd-yu9d d:2011-09-13T14:49:44.000Z t:candlast=Martinez t:purposecd=UNKN t:candid=MJ t:c_code=IND t:purpose=Unknown t:canclass=P t:candmi=D t:seg_ind=N t:schedule=F t:refno=P0001-02 t:candfirst=Juan t:pay_method=Unknown t:committee=H t:org_ind=N t:rr_ind=N m:amnt=0 m:election=2001 m:officecd=5 m:filing=15
```

## Meta Commands

```ls
metric m:election p:integer l:ELECTION t:dataTypeName=number

metric m:officecd p:integer l:OFFICECD t:dataTypeName=number

metric m:filing p:integer l:FILING t:dataTypeName=number

metric m:strno p:integer l:STRNO t:dataTypeName=number

metric m:amnt p:float l:AMNT t:dataTypeName=number

entity e:k3cd-yu9d l:"2001 Campaign Expenditures" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/k3cd-yu9d

property e:k3cd-yu9d t:meta.view v:id=k3cd-yu9d v:category="City Government" v:averageRating=0 v:name="2001 Campaign Expenditures" v:attribution="Campaign Finance Board (CFB)"

property e:k3cd-yu9d t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:k3cd-yu9d t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| election | officecd | candid | canclass | candlast | candfirst | candmi | committee | filing | schedule | pageno | sequenceno | refno    | inv_date   | date       | name                  | c_code | org_ind | strno | strname | apartment | pay_method | amnt    | purposecd | purpose          | explain              | exemptcd | rr_ind | seg_ind | 
| ======== | ======== | ====== | ======== | ======== | ========= | ====== | ========= | ====== | ======== | ====== | ========== | ======== | ========== | ========== | ===================== | ====== | ======= | ===== | ======= | ========= | ========== | ======= | ========= | ================ | ==================== | ======== | ====== | ======= | 
|          |          | CANDID | CANCLASS | CANDLAST | CANDFIRST | CANDMI | COMMITTEE |        | SCHEDULE | PAGENO | SEQUENCENO | REFNO    |            |            | NAME                  | C_CODE | ORG_IND |       | STRNAME | APARTMENT | PAY_METHOD |         | PURPOSECD | PURPOSE          | EXPLAIN              | EXEMPTCD | RR_IND | SEG_IND | 
| 2001     | 5        | CF     | P        | Chen     | Ethel     | T      | A         | 10     | F        |        |            | P0005-08 |            | 996562800  |                       | ORG    | Y       |       |         |           | Unknown    | 4799.00 | PETIT     | Petition Expns.  |                      | P        | N      | N       | 
| 2001     | 5        | EC     | P        | Brown    | Everly    | D      | A         | 14     | F        |        |            | P0001-09 |            |            |                       | IND    | N       |       |         |           | Unknown    | 166.00  | UNKN      | Unknown          |                      |          | N      | N       | 
| 2001     | 5        | MJ     | P        | Martinez | Juan      | D      | H         | 15     | F        |        |            | P0001-02 |            |            |                       | IND    | N       |       |         |           | Unknown    | 0       | UNKN      | Unknown          |                      |          | N      | N       | 
| 2001     | 5        | CF     | P        | Chen     | Ethel     | T      | A         | 9      | F        |        |            | P0007-04 |            |            |                       | IND    | N       |       |         |           | Unknown    | 0       | UNKN      | Unknown          |                      |          | N      | N       | 
| 2001     | 5        | CF     | P        | Chen     | Ethel     | T      | A         | 10     | F        |        |            | P0005-09 |            | 998636400  |                       | IND    | N       |       |         |           | Unknown    | 84.00   | UNKN      | Unknown          |                      |          | N      | N       | 
| 2001     | 5        | 559    | P        | Wooten   | Donald    | T      | H         | 10     | D        |        |            | P0001-01 |            | 999241200  |                       | OTHR   | Y       |       |         |           |            | 1.00    | RENTO     | Office Rent      | OFFICE SPACE PROVIDE |          | N      |         | 
| 2001     | 5        | 420    | P        | Comrie   | Leroy     | G      | H         | 13     | F        |        |            | P0001-03 | 1002351600 | 1002351600 | 113TH PRECINT COUNCIL | IND    | N       |       |         |           | Full       | 50.00   | CONSV     | Constituent Svcs | TICKETS COMM EVENT   |          | N      | N       | 
| 2001     | 5        | 448    | P        | Ciafone  | John      | J      | H         | 11     | F        |        |            | P0001-01 | 999327600  | 999327600  | 4 OVER 4 COMM         | IND    | N       |       |         |           | Full       | 549.00  | LITER     | Campgn Lit.      | CAMPAIGN LITERATURE  |          | N      | N       | 
| 2001     | 5        | 448    | P        | Ciafone  | John      | J      | H         | 11     | F        |        |            | P0001-02 | 999673200  | 999673200  | 4 OVER 4 COMM         | IND    | N       |       |         |           | Full       | 549.00  | LITER     | Campgn Lit.      | CAMPAIGN LITERATURE  |          | N      | N       | 
```