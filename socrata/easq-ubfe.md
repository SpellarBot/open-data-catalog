# 2005 Campaign Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2005-campaign-expenditures-ea221) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/easq-ubfe) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/easq-ubfe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/easq-ubfe/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | easq-ubfe |
| Name | 2005 Campaign Expenditures |
| Attribution | Campaign Finance Board (CFB) |
| Category | City Government |
| Tags | finance, campaign finance board, cfb, nyccfb, campaign finance, elections, contributions, politics, campaign, funding |
| Created | 2011-09-13T22:50:44Z |
| Publication Date | 2013-06-21T20:02:28Z |

## Description

A listing of campaign expendiures for candidates for City office during the 2005 election cycle

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
series e:easq-ubfe d:2005-06-24T07:00:00.000Z t:candlast=Moskowitz t:purposecd=OTHER t:candid=BW t:c_code=CORP t:purpose="Other: explntion" t:canclass=P t:candmi=S t:seg_ind=N t:schedule=F t:candfirst=Eva t:refno=R0005335 t:pay_method=Final t:committee=A t:org_ind=Y t:name=1-800-FLOWERS.com t:explain=Flowers t:rr_ind=N m:amnt=55 m:election=2005 m:officecd=4 m:filing=10

series e:easq-ubfe d:2004-04-10T07:00:00.000Z t:candlast=Reed t:purposecd=CONSV t:candid=DC t:c_code=CORP t:purpose="Constituent Svcs" t:canclass=NP t:seg_ind=N t:schedule=F t:refno=R0000770 t:candfirst=Philip t:pay_method=Final t:committee=K t:org_ind=Y t:name="1199 Plaza Services Corp." t:explain="donation to seniors" t:rr_ind=N m:amnt=75 m:election=2005 m:officecd=6 m:filing=5

series e:easq-ubfe d:2005-08-22T07:00:00.000Z t:candlast="Carrion, Jr." t:purposecd=OTHER t:candid=ED t:c_code=CORP t:purpose="Other: explntion" t:canclass=P t:seg_ind=N t:schedule=F t:refno=R0006595 t:candfirst=Adolfo t:pay_method=Final t:committee=J t:org_ind=Y t:name=1CLICKDVD.COM t:explain=SOFTWARE t:rr_ind=N m:amnt=59 m:election=2005 m:officecd=4 m:filing=14
```

## Meta Commands

```ls
metric m:election p:integer l:ELECTION t:dataTypeName=number

metric m:officecd p:integer l:OFFICECD t:dataTypeName=number

metric m:filing p:integer l:FILING t:dataTypeName=number

metric m:strno p:integer l:STRNO t:dataTypeName=number

metric m:amnt p:float l:AMNT t:dataTypeName=number

entity e:easq-ubfe l:"2005 Campaign Expenditures" t:attribution="Campaign Finance Board (CFB)" t:url=https://data.cityofnewyork.us/api/views/easq-ubfe

property e:easq-ubfe t:meta.view v:id=easq-ubfe v:category="City Government" v:averageRating=0 v:name="2005 Campaign Expenditures" v:attribution="Campaign Finance Board (CFB)"

property e:easq-ubfe t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:easq-ubfe t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| election | officecd | candid | canclass | candlast     | candfirst | candmi | committee | filing | schedule | pageno | sequenceno | refno    | inv_date   | date       | name                      | c_code | org_ind | strno | strname                    | apartment | pay_method | amnt   | purposecd | purpose          | explain             | exemptcd | rr_ind | seg_ind | 
| ======== | ======== | ====== | ======== | ============ | ========= | ====== | ========= | ====== | ======== | ====== | ========== | ======== | ========== | ========== | ========================= | ====== | ======= | ===== | ========================== | ========= | ========== | ====== | ========= | ================ | =================== | ======== | ====== | ======= | 
|          |          | CANDID | CANCLASS | CANDLAST     | CANDFIRST | CANDMI | COMMITTEE |        | SCHEDULE | PAGENO | SEQUENCENO | REFNO    |            |            | NAME                      | C_CODE | ORG_IND |       | STRNAME                    | APARTMENT | PAY_METHOD |        | PURPOSECD | PURPOSE          | EXPLAIN             | EXEMPTCD | RR_IND | SEG_IND | 
| 2005     | 4        | BW     | P        | Moskowitz    | Eva       | S      | A         | 10     | F        |        |            | R0005335 | 1116745200 | 1119596400 | 1-800-FLOWERS.com         | CORP   | Y       |       |                            |           | Final      | 55.00  | OTHER     | Other: explntion | Flowers             |          | N      | N       | 
| 2005     | 6        | DC     | NP       | Reed         | Philip    |        | K         | 5      | F        |        |            | R0000770 | 1081580400 | 1081580400 | 1199 Plaza Services Corp. | CORP   | Y       |       |                            |           | Final      | 75.00  | CONSV     | Constituent Svcs | donation to seniors |          | N      | N       | 
| 2005     | 4        | ED     | P        | Carrion, Jr. | Adolfo    |        | J         | 14     | F        |        |            | R0006595 | 1124694000 | 1124694000 | 1CLICKDVD.COM             | CORP   | Y       |       |                            |           | Final      | 59.00  | OTHER     | Other: explntion | SOFTWARE            |          | N      | N       | 
| 2005     | 5        | 207    | P        | Nelson       | Michael   | C      | L         | 16     | F        |        |            | R0001559 | 1130655600 | 1131264000 | 3DI                       | CORP   | Y       |       |                            |           | Final      | 63.00  | CONSL     | Campgn Consuls.  | flyer design        |          | N      | N       | 
| 2005     | 4        | BW     | P        | Moskowitz    | Eva       | S      | A         | 13     | F        |        |            | R0006572 | 1125644400 | 1125990000 | 5 Star Wholesale          | CORP   | Y       | 1300  | Chester Industrial Parkway |           | Final      | 677.00 | OTHER     | Other: explntion | Primary Day Expense |          | N      | N       | 
| 2005     | 5        | LW     | P        | Recchia      | Domenic   |        | J         | 14     | F        |        |            | R0001270 | 1119769200 | 1123743600 | 504 Democractic Club      | OTHR   | Y       |       |                            |           | Final      | 200.00 | OTHER     | Other: explntion | Dinner & Journal Ad |          | N      | N       | 
| 2005     | 5        | 721    | P        | Garodnick    | Daniel    | R      | H         | 10     | F        |        |            | R0002349 | 1118386800 | 1118386800 | 504 Democratic Club       | OTHR   | Y       |       |                            |           | Final      | 125.00 | PRINT     | Print Ads        | advertisement       |          | N      | N       | 
| 2005     | 5        | 821    | P        | Vacca        | James     |        | H         | 10     | F        |        |            | R0001552 | 1120806000 | 1120806000 | 504 Democratic Club       | CORP   | Y       |       |                            |           | Final      | 75.00  | OTHER     | Other: explntion | Dinner Ticket       |          | N      | N       | 
| 2005     | 5        | 334    | P        | Gallagher    | Dennis    | P      | K         | 14     | F        |        |            | R0002113 | 1127199600 | 1127199600 | 72nd Place Precinct Club  | OTHR   | Y       |       |                            |           | Final      | 135.00 | OTHER     | Other: explntion | Donation            |          | N      | N       | 
```