# Capital Commitments--Prel\Adpt

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-commitments-adpt) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/svqu-rx2s) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/svqu-rx2s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/svqu-rx2s/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | svqu-rx2s |
| Name | Capital Commitments--Prel\Adpt |
| Attribution | Mayor's Office of Management and Budget (OMB) |
| Category | City Government |
| Tags | omb, capital, funds, management, budget |
| Created | 2016-11-29T23:00:21Z |
| Publication Date | 2017-02-08T17:07:08Z |

## Description

This dataset contains capital commitment data for project type, budget line and managing agency by city and non-City funds.   The dollar values in this table are rounded to thousands and are exclusive of IFA to match the commitment numbers published in the Preliminary and  Adopted Budget Capital Commitment Plan publication.

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
| Yes      | numeric metric | fiscal_year_1_amount     | Fiscal Year 1 $ amount   | number    | number      |
| Yes      | numeric metric | fiscal_year_2_amount     | Fiscal Year 2 $ amount   | number    | number      |
| Yes      | numeric metric | fiscal_year_3_amount     | Fiscal Year 3 $ amount   | number    | number      |
| Yes      | numeric metric | fiscal_year_4_amount     | Fiscal Year 4 $ amount   | number    | number      |
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
series e:svqu-rx2s d:2016-10-26T00:00:00.000Z t:project_type_description="DEPARTMENT FOR THE AGING" t:budget_line=AGDN100 t:funding_type=CITY t:budget_line_description="CHINESE-AMERICAN PLANNING COUNCIL" t:project_type=AG m:fiscal_year_3_amount=0 m:fiscal_year_2_amount=0 m:fiscal_year_1_amount=0 m:fiscal_year_4_amount=503

series e:svqu-rx2s d:2016-10-26T00:00:00.000Z t:project_type_description="DEPARTMENT FOR THE AGING" t:budget_line=AGDN145 t:funding_type=CITY t:budget_line_description="ELMCOR YOUTH AND ADULT ACTIVITIES, INC." t:project_type=AG m:fiscal_year_3_amount=0 m:fiscal_year_2_amount=0 m:fiscal_year_1_amount=0 m:fiscal_year_4_amount=510

series e:svqu-rx2s d:2016-10-26T00:00:00.000Z t:project_type_description="DEPARTMENT FOR THE AGING" t:budget_line=AGDN169 t:funding_type=CITY t:budget_line_description="GLENRIDGE SENIOR CENTER" t:project_type=AG m:fiscal_year_3_amount=0 m:fiscal_year_2_amount=0 m:fiscal_year_1_amount=118 m:fiscal_year_4_amount=0
```

## Meta Commands

```ls
metric m:fiscal_year_1_amount p:integer l:"Fiscal Year 1 $ amount" d:Yr1_FY t:dataTypeName=number

metric m:fiscal_year_2_amount p:integer l:"Fiscal Year 2 $ amount" d:"Year1 + 1" t:dataTypeName=number

metric m:fiscal_year_3_amount p:integer l:"Fiscal Year 3 $ amount" d:"Year1 + 2" t:dataTypeName=number

metric m:fiscal_year_4_amount p:integer l:"Fiscal Year 4 $ amount" d:"Year1 + 3" t:dataTypeName=number

entity e:svqu-rx2s l:"Capital Commitments--Prel\Adpt" t:attribution="Mayor's Office of Management and Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/svqu-rx2s

property e:svqu-rx2s t:meta.view v:id=svqu-rx2s v:category="City Government" v:averageRating=0 v:name="Capital Commitments--Prel\Adpt" v:attribution="Mayor's Office of Management and Budget (OMB)"

property e:svqu-rx2s t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:svqu-rx2s t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| published_date | project_type | project_type_description | budget_line | budget_line_description                                   | funding_type | first_fiscal_year | fiscal_year_1_amount | fiscal_year_2_amount | fiscal_year_3_amount | fiscal_year_4_amount | 
| ============== | ============ | ======================== | =========== | ========================================================= | ============ | ================= | ==================== | ==================== | ==================== | ==================== | 
| 20161026       | AG           | DEPARTMENT FOR THE AGING | AGDN100     | CHINESE-AMERICAN PLANNING COUNCIL                         | CITY         | 2017              | 0                    | 0                    | 0                    | 503                  | 
| 20161026       | AG           | DEPARTMENT FOR THE AGING | AGDN145     | ELMCOR YOUTH AND ADULT ACTIVITIES, INC.                   | CITY         | 2017              | 0                    | 0                    | 0                    | 510                  | 
| 20161026       | AG           | DEPARTMENT FOR THE AGING | AGDN169     | GLENRIDGE SENIOR CENTER                                   | CITY         | 2017              | 118                  | 0                    | 0                    | 0                    | 
| 20161026       | AG           | DEPARTMENT FOR THE AGING | AGDN184     | HEBREW HOME FOR THE AGED                                  | CITY         | 2017              | 1218                 | 1649                 | 0                    | 17                   | 
| 20161026       | AG           | DEPARTMENT FOR THE AGING | AGDN216     | JEWISH COMMUNITY COUNCIL OF GREATER CONEY ISLAND (JCCGCI) | CITY         | 2017              | 450                  | 0                    | 0                    | 0                    | 
| 20161026       | AG           | DEPARTMENT FOR THE AGING | AGDN235     | LENOX HILL NEIGHBORHOOD ASSOCIATION                       | CITY         | 2017              | 234                  | 0                    | 3596                 | 0                    | 
| 20161026       | AG           | DEPARTMENT FOR THE AGING | AGDN262     | MET COUNCIL ON JEWISH POVERTY                             | CITY         | 2017              | 446                  | 2907                 | 257                  | 0                    | 
| 20161026       | AG           | DEPARTMENT FOR THE AGING | AGDN334     | PRESBYTERIAN SENIOR SERVICES                              | CITY         | 2017              | 50                   | 0                    | 0                    | 0                    | 
| 20161026       | AG           | DEPARTMENT FOR THE AGING | AGDN380     | SERVICES NOW FOR ADULT PERSONS, INC. (SNAP)               | CITY         | 2017              | 356                  | 0                    | 0                    | 0                    | 
| 20161026       | AG           | DEPARTMENT FOR THE AGING | AGDN410     | SENIOR ACTION IN A GAY ENVIRONMENT (SAGE)                 | CITY         | 2017              | 0                    | 0                    | 0                    | 73                   | 
```