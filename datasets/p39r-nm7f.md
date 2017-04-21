# Enforcement Fines

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/enforcement-fines) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/p39r-nm7f) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/p39r-nm7f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/p39r-nm7f/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | p39r-nm7f |
| Name | Enforcement Fines |
| Attribution | Conflict of Interest Board (CONFLICTS) |
| Category | City Government |
| Tags | coib, enforcement, fines |
| Created | 2015-02-26T17:23:05Z |
| Publication Date | 2017-04-10T16:31:17Z |

## Description

This list contains information on the fines collected by the Enforcement Unit.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                     | Data Type     | Render Type   |
| ======== | ============== | ========================== | ======================== | ============= | ============= |
| Yes      | time           | date                       | Date                     | calendar_date | calendar_date |
| Yes      | series tag     | case_number                | Case Number              | text          | text          |
| Yes      | series tag     | case_name                  | Case Name                | text          | text          |
| Yes      | series tag     | agency                     | Agency                   | text          | text          |
| Yes      | series tag     | 3_way_settlement           | 3-Way Settlement         | text          | text          |
| Yes      | numeric metric | fine_paid_to_coib          | Fine paid to COIB        | money         | money         |
| Yes      | series tag     | exp_of_amount_paid_to_coib | Explanation of COIB Fine | text          | text          |
| Yes      | numeric metric | fine_paid_to_agency        | Fine Paid to Agency      | money         | money         |
| Yes      | series tag     | other_penalty_value        | Other Penalty Value      | text          | text          |
| Yes      | numeric metric | other_penalty              | Other Penalty            | money         | text          |
| Yes      | numeric metric | suspension_of_days         | Suspension Days          | number        | number        |
| Yes      | numeric metric | suspension_value           | Suspension Value         | money         | money         |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:p39r-nm7f d:2017-03-24T00:00:00.000Z t:case_number=2014-216 t:case_name=O'Brien t:agency=HRA m:fine_paid_to_coib=1500

series e:p39r-nm7f d:2017-03-24T00:00:00.000Z t:case_number=2017-157 t:case_name=Morgan t:agency=DSNY t:3_way_settlement=X m:suspension_of_days=3 m:suspension_value=486

series e:p39r-nm7f d:2017-03-24T00:00:00.000Z t:case_number=2015-858d t:case_name=Noel t:agency=DOT t:3_way_settlement=X m:fine_paid_to_agency=1500 m:fine_paid_to_coib=1000
```

## Meta Commands

```ls
metric m:fine_paid_to_coib p:integer l:"Fine paid to COIB" d:"Amount of payment made to the Board" t:dataTypeName=money

metric m:fine_paid_to_agency p:integer l:"Fine Paid to Agency" d:"Amount paid to the respondent's City agency" t:dataTypeName=money

metric m:other_penalty p:long l:"Other Penalty" d:"Description of any other penalty imposed (such as salary reduction due to demotion)" t:dataTypeName=money

metric m:suspension_of_days p:integer l:"Suspension Days" d:"Number of days imposed by suspension" t:dataTypeName=number

metric m:suspension_value p:double l:"Suspension Value" d:"Value of the suspension to the respondent in lost income" t:dataTypeName=money

entity e:p39r-nm7f l:"Enforcement Fines" t:attribution="Conflict of Interest Board (CONFLICTS)" t:url=https://data.cityofnewyork.us/api/views/p39r-nm7f

property e:p39r-nm7f t:meta.view v:id=p39r-nm7f v:category="City Government" v:averageRating=0 v:name="Enforcement Fines" v:attribution="Conflict of Interest Board (CONFLICTS)"

property e:p39r-nm7f t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:p39r-nm7f t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| date                | case_number | case_name   | agency  | 3_way_settlement | fine_paid_to_coib | exp_of_amount_paid_to_coib                                                    | fine_paid_to_agency | other_penalty_value | other_penalty | suspension_of_days | suspension_value | 
| =================== | =========== | =========== | ======= | ================ | ================= | ============================================================================= | =================== | =================== | ============= | ================== | ================ | 
| 2017-03-24T00:00:00 | 2014-216    | O'Brien     | HRA     |                  | 1500              |                                                                               |                     |                     |               |                    |                  | 
| 2017-03-24T00:00:00 | 2016-881    | Youssef     | DEP     | X                |                   |                                                                               |                     | Resign from DEP     |               |                    |                  | 
| 2017-03-24T00:00:00 | 2017-157    | Morgan      | DSNY    | X                |                   |                                                                               |                     |                     |               | 3                  | 486.00           | 
| 2017-03-24T00:00:00 | 2015-858d   | Noel        | DOT     | X                | 1000              |                                                                               | 1500                |                     |               |                    |                  | 
| 2017-03-24T00:00:00 | 2016-593    | Gillenwater | ACS     | X                |                   |                                                                               | 1250                |                     |               |                    |                  | 
| 2017-02-17T00:00:00 | 2016-735    | Myers       | FISA    | X                | 2500              |                                                                               |                     |                     |               |                    |                  | 
| 2017-02-17T00:00:00 | 2016-002    | Peters      | ACS     | X                |                   |                                                                               |                     |                     |               | 15                 | 4000.00          | 
| 2017-02-17T00:00:00 | 2015-516    | Harris      | DOE     |                  | 1000              | Due to showing of financial hardship, fine was reduced from $40,000 to $1,000 |                     |                     |               |                    |                  | 
| 2017-02-17T00:00:00 | 2015-550    | Edwards     | Council |                  | 1000              | Due to showing of financial hardship, fine was reduced from $8,000 to $1,000  |                     |                     |               |                    |                  | 
| 2017-02-17T00:00:00 | 2016-090    | Vega        | NYPD    |                  | 5000              | Due to showing of financial hardship, fine was reduced from $75,000 to $5,000 |                     |                     |               |                    |                  | 
```