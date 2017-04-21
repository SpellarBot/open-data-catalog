# State Employee Earnings- FY2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-employee-earnings-fy2015) |
| Metadata | [Link](https://data.ct.gov/api/views/u6ju-57ue) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/u6ju-57ue/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/u6ju-57ue/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | u6ju-57ue |
| Name | State Employee Earnings- FY2015 |
| Category | Government |
| Created | 2016-01-26T13:41:36Z |
| Publication Date | 2016-01-26T13:44:56Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | name                | NAME                | text      | text        |
| Yes      | series tag     | agency_description  | AGENCY_DESCRIPTION  | text      | text        |
| Yes      | numeric metric | earnings_amt        | EARNINGS_AMT        | money     | money       |
| Yes      | numeric metric | fringe_amt          | FRINGE_AMT          | money     | money       |
| Yes      | numeric metric | total_amt           | TOTAL_AMT           | money     | money       |
| Yes      | series tag     | earnings            | Earnings            | text      | text        |
| Yes      | series tag     | number_of_employees | Number of Employees | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:u6ju-57ue d:2015-01-01T00:00:00.000Z t:earnings=<25,000 t:number_of_employees=<25,000 t:agency_description="Department of Social Services" t:name="AARON,ROXANNE B" m:fringe_amt=284.61 m:total_amt=3207.41 m:earnings_amt=2922.8

series e:u6ju-57ue d:2015-01-01T00:00:00.000Z t:earnings=<25,000 t:number_of_employees=<25,000 t:agency_description="Board of Regents" t:name="Aaronian,Michael K." m:fringe_amt=127.39 m:total_amt=1027.39 m:earnings_amt=900

series e:u6ju-57ue d:2015-01-01T00:00:00.000Z t:earnings=100,001-150,000 t:number_of_employees=100,001-150,000 t:agency_description="Department of Children and Families" t:name="Aarons,Ingrid C." m:fringe_amt=34311.42 m:total_amt=141754.48 m:earnings_amt=107443.06
```

## Meta Commands

```ls
metric m:earnings_amt p:double l:EARNINGS_AMT t:dataTypeName=money

metric m:fringe_amt p:double l:FRINGE_AMT t:dataTypeName=money

metric m:total_amt p:double l:TOTAL_AMT t:dataTypeName=money

entity e:u6ju-57ue l:"State Employee Earnings- FY2015" t:url=https://data.ct.gov/api/views/u6ju-57ue

property e:u6ju-57ue t:meta.view v:id=u6ju-57ue v:category=Government v:averageRating=0 v:name="State Employee Earnings- FY2015"

property e:u6ju-57ue t:meta.view.owner v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:displayName="Office of the State Comptroller"

property e:u6ju-57ue t:meta.view.tableauthor v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:roleName=publisher v:displayName="Office of the State Comptroller"
```

## Top Records

```ls
| name                      | agency_description                                | earnings_amt | fringe_amt | total_amt | earnings        | number_of_employees | 
| ========================= | ================================================= | ============ | ========== | ========= | =============== | =================== | 
| AARON,ROXANNE B           | Department of Social Services                     | 2922.8       | 284.61     | 3207.41   | <25,000         | <25,000             | 
| Aaronian,Michael K.       | Board of Regents                                  | 900          | 127.39     | 1027.39   | <25,000         | <25,000             | 
| Aarons,Ingrid C.          | Department of Children and Families               | 107443.06    | 34311.42   | 141754.48 | 100,001-150,000 | 100,001-150,000     | 
| Aarons,Kasheena L.        | Department of Mental Heath and Addiction Services | 99816.18     | 35777.33   | 135593.51 | 75,001-100,000  | 75,001-100,000      | 
| Aaronsohn,Elizabeth N.    | Board of Regents                                  | 6812         | 531.35     | 7343.35   | <25,000         | <25,000             | 
| Aarrestad,Ansel O         | Department of Environmental Protection            | 12142        | 1718.44    | 13860.44  | <25,000         | <25,000             | 
| Aarrestad,Peter J         | Department of Environmental Protection            | 126295.38    | 35130.94   | 161426.32 | 100,001-150,000 | 100,001-150,000     | 
| Aarsand-Flores,Natalie M. | Department of Correction                          | 97537.65     | 29467.52   | 127005.17 | 75,001-100,000  | 75,001-100,000      | 
| Abad,Abdul Bryant         | University of Connecticut                         | 1235         | 96.33      | 1331.33   | <25,000         | <25,000             | 
| Abadia-Barrero,Cesar      | University of Connecticut                         | 67188.39     | 26478.84   | 93667.23  | 50,001-75,000   | 50,001-75,000       | 
```