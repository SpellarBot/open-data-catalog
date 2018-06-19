# Capital Commitments -- Exec

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-commitments) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tiex-dv5v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tiex-dv5v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tiex-dv5v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tiex-dv5v |
| Name | Capital Commitments -- Exec |
| Attribution | Mayor?s Office of Management & Budget (OMB) |
| Category | City Government |
| Created | 2016-05-03T22:34:50Z |
| Publication Date | 2016-05-04T15:05:27Z |

## Description

This file contains capital commitment data by project type, budget line and source of funds.  The dollar values in this table are in thousands.  The data is created in Exective Budget to match commitment numbers in the Capital Commitment Plan publication .

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | time           | published_date           | Published Date           | text      | text        |
| Yes      | series tag     | project_type             | Project Type             | text      | text        |
| Yes      | series tag     | project_type_description | Project Type Description | text      | text        |
| Yes      | series tag     | budget_line              | Budget Line              | text      | text        |
| Yes      | series tag     | budget_line_description  | Budget Line Description  | text      | text        |
| Yes      | series tag     | funding_type             | Funding Type             | text      | text        |
| No       |                | first_fiscal_year        | First Fiscal Year        | number    | number      |
| Yes      | numeric metric | fiscal_year_1_amount     | Fiscal Year 1 $ amount   | money     | money       |
| Yes      | numeric metric | fiscal_year_2_amount     | Fiscal Year 2 $ amount   | number    | number      |
| Yes      | numeric metric | fiscal_year_3_amount     | Fiscal Year 3 $ amount   | number    | number      |
| Yes      | numeric metric | fiscal_year_4_amount     | Fiscal Year 4 $ amount   | number    | number      |
| Yes      | numeric metric | fiscal_year_5_amount     | Fiscal Year 5 $ amount   | number    | number      |
```

## Time Field

```ls
Value = published_date
Format & Zone = yyyyMMdd
```

## Series Fields

```ls
Excluded Fields = first_fiscal_year
```

## Data Commands

```ls
series e:tiex-dv5v d:2016-04-26T00:00:00.000Z t:project_type_description="HOUSING & DEVELOPMENT" t:budget_line=HDKN525 t:funding_type=CITY t:project_type=HD m:fiscal_year_3_amount=0 m:fiscal_year_2_amount=500 m:fiscal_year_1_amount=0 m:fiscal_year_4_amount=0 m:fiscal_year_5_amount=0

series e:tiex-dv5v d:2016-04-26T00:00:00.000Z t:project_type_description=EDUCATION t:budget_line="E M4001" t:funding_type=CITY t:budget_line_description=FIT t:project_type=E m:fiscal_year_3_amount=0 m:fiscal_year_2_amount=150 m:fiscal_year_1_amount=40 m:fiscal_year_4_amount=0 m:fiscal_year_5_amount=0

series e:tiex-dv5v d:2016-04-26T00:00:00.000Z t:project_type_description="DEPARTMENT FOR THE AGING" t:budget_line=AGDN100 t:funding_type=CITY t:budget_line_description="CHINESE-AMERICAN PLANNING COUNCIL" t:project_type=AG m:fiscal_year_3_amount=0 m:fiscal_year_2_amount=0 m:fiscal_year_1_amount=503 m:fiscal_year_4_amount=0 m:fiscal_year_5_amount=0
```

## Meta Commands

```ls
metric m:fiscal_year_1_amount p:integer l:"Fiscal Year 1 $ amount" t:dataTypeName=money

metric m:fiscal_year_2_amount p:integer l:"Fiscal Year 2 $ amount" t:dataTypeName=number

metric m:fiscal_year_3_amount p:integer l:"Fiscal Year 3 $ amount" t:dataTypeName=number

metric m:fiscal_year_4_amount p:integer l:"Fiscal Year 4 $ amount" t:dataTypeName=number

metric m:fiscal_year_5_amount p:integer l:"Fiscal Year 5 $ amount" t:dataTypeName=number

entity e:tiex-dv5v l:"Capital Commitments -- Exec" t:attribution="Mayor?s Office of Management & Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/tiex-dv5v

property e:tiex-dv5v t:meta.view v:id=tiex-dv5v v:category="City Government" v:averageRating=0 v:name="Capital Commitments -- Exec" v:attribution="Mayor?s Office of Management & Budget (OMB)"

property e:tiex-dv5v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tiex-dv5v t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| published_date | project_type | project_type_description | budget_line | budget_line_description                                   | funding_type | first_fiscal_year | fiscal_year_1_amount | fiscal_year_2_amount | fiscal_year_3_amount | fiscal_year_4_amount | fiscal_year_5_amount | 
| ============== | ============ | ======================== | =========== | ========================================================= | ============ | ================= | ==================== | ==================== | ==================== | ==================== | ==================== | 
| 20160426       | HD           | HOUSING & DEVELOPMENT    | HDKN525     |                                                           | CITY         | 2016              | 0                    | 500                  | 0                    | 0                    | 0                    | 
| 20160426       | E            | EDUCATION                | E M4001     | FIT                                                       | CITY         | 2016              | 40                   | 150                  | 0                    | 0                    | 0                    | 
| 20160426       | AG           | DEPARTMENT FOR THE AGING | AGDN100     | CHINESE-AMERICAN PLANNING COUNCIL                         | CITY         | 2016              | 503                  | 0                    | 0                    | 0                    | 0                    | 
| 20160426       | AG           | DEPARTMENT FOR THE AGING | AGDN145     | ELMCOR YOUTH AND ADULT ACTIVITIES, INC.                   | CITY         | 2016              | 0                    | 0                    | 510                  | 0                    | 0                    | 
| 20160426       | AG           | DEPARTMENT FOR THE AGING | AGDN169     | GLENRIDGE SENIOR CENTER                                   | CITY         | 2016              | 0                    | 118                  | 0                    | 0                    | 0                    | 
| 20160426       | AG           | DEPARTMENT FOR THE AGING | AGDN184     | HEBREW HOME FOR THE AGED                                  | CITY         | 2016              | 1658                 | 0                    | 1149                 | 0                    | 0                    | 
| 20160426       | AG           | DEPARTMENT FOR THE AGING | AGDN216     | JEWISH COMMUNITY COUNCIL OF GREATER CONEY ISLAND (JCCGCI) | CITY         | 2016              | 119                  | 331                  | 0                    | 0                    | 0                    | 
| 20160426       | AG           | DEPARTMENT FOR THE AGING | AGDN235     | LENOX HILL NEIGHBORHOOD ASSOCIATION                       | CITY         | 2016              | 236                  | 0                    | 0                    | 3596                 | 0                    | 
| 20160426       | AG           | DEPARTMENT FOR THE AGING | AGDN262     | MET COUNCIL ON JEWISH POVERTY                             | CITY         | 2016              | 282                  | 164                  | 2907                 | 257                  | 0                    | 
| 20160426       | AG           | DEPARTMENT FOR THE AGING | AGDN334     | PRESBYTERIAN SENIOR SERVICES                              | CITY         | 2016              | 50                   | 0                    | 0                    | 0                    | 0                    | 
```