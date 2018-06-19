# Form 700 Schedule D

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/form-700-schedule-d) |
| Metadata | [Link](https://data.sfgov.org/api/views/kpf8-y8tj) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/kpf8-y8tj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/kpf8-y8tj/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | kpf8-y8tj |
| Name | Form 700 Schedule D |
| Attribution | Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, form 700, schedules, sei, statement of economic interests |
| Created | 2016-05-18T18:08:25Z |
| Publication Date | 2016-06-13T22:37:29Z |

## Description

Gifts from businesses (such as tickets to sporting or entertainment events) Link to Form 700 overview: http://www.fppc.ca.gov/Form700.html

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | filer_name        | Filer Name        | text      | text        |
| Yes      | series tag     | department_name   | Department Name   | text      | text        |
| Yes      | series tag     | position_name     | Position Name     | text      | text        |
| Yes      | series tag     | offices           | Offices           | text      | text        |
| Yes      | time           | period_end        | Period End        | date      | date        |
| No       |                | period_start      | Period Start      | date      | date        |
| Yes      | series tag     | filer_id          | Filer             | text      | text        |
| No       |                | filing_date       | Filing Date       | date      | date        |
| Yes      | series tag     | filing_id         | Filing            | text      | text        |
| No       |                | id                | Id                | text      | text        |
| Yes      | series tag     | transaction_type  | Transaction Type  | text      | text        |
| Yes      | series tag     | name_of_source    | Name Of Source    | text      | text        |
| No       |                | address           | Address           | text      | text        |
| Yes      | series tag     | city              | City              | text      | text        |
| Yes      | series tag     | state             | State             | text      | text        |
| Yes      | series tag     | zip               | Zipcode           | text      | text        |
| Yes      | series tag     | business_activity | Business Activity | text      | text        |
| No       |                | gift_date         | Gift Date         | date      | date        |
| Yes      | numeric metric | amount            | Amount            | money     | money       |
| Yes      | series tag     | description       | Description       | text      | text        |
```

## Time Field

```ls
Value = period_end
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = period_start,filing_date,id,address,gift_date
```

## Data Commands

```ls
series e:kpf8-y8tj d:2016-12-31T08:00:00.000Z t:zip=94117 t:filer_name="McDonnell, Eric" t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Recreation & Parks Commission,electionDate:None" t:description="Outside Land Tickets" t:transaction_type=ScheduleD t:filer_id=SFO-153315 t:state=CA t:name_of_source="SF Recreation & Parks Department" t:department_name="EOBCDH_Recreation & Parks Commission" t:position_name=Commissioner t:filing_id=164564994 t:city="San Francisco" m:amount=300

series e:kpf8-y8tj d:2016-12-31T08:00:00.000Z t:zip=94103 t:filer_name="Richards, Dennis" t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Planning Commission,electionDate:None" t:description="Comp. Ticket to Spring Symposium" t:transaction_type=ScheduleD t:filer_id=SFO-153839 t:state=Ca t:name_of_source="San Francisco Housing Action Coalition" t:department_name="EOBCDH_Planning Commission" t:position_name=Commissioner t:filing_id=164563959 t:city="San Francisco" m:amount=75

series e:kpf8-y8tj d:2016-12-31T08:00:00.000Z t:zip=94103 t:filer_name="Richards, Dennis" t:transaction_type=ScheduleD t:name_of_source="SST Investments" t:state=Ca t:position_name=Commissioner t:city="San Francisco" t:business_activity="Real Estate Development and Investment" t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Planning Commission,electionDate:None" t:description="Holiday Luncheon Meal" t:filer_id=SFO-153839 t:department_name="EOBCDH_Planning Commission" t:filing_id=164563959 m:amount=100
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:kpf8-y8tj l:"Form 700 Schedule D" t:attribution="Ethics Commission" t:url=https://data.sfgov.org/api/views/kpf8-y8tj

property e:kpf8-y8tj t:meta.view v:id=kpf8-y8tj v:category="City Management and Ethics" v:averageRating=0 v:name="Form 700 Schedule D" v:attribution="Ethics Commission"

property e:kpf8-y8tj t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:kpf8-y8tj t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:kpf8-y8tj t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| filer_name       | department_name                      | position_name | offices                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | period_end | period_start | filer_id   | filing_date | filing_id | id                               | transaction_type | name_of_source                         | address    | city          | state | zip   | business_activity                      | gift_date  | amount | description                      | 
| ================ | ==================================== | ============= | =========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ========== | ============ | ========== | =========== | ========= | ================================ | ================ | ====================================== | ========== | ============= | ===== | ===== | ====================================== | ========== | ====== | ================================ | 
| McDonnell, Eric  | EOBCDH_Recreation & Parks Commission | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Recreation & Parks Commission,electionDate:None                                                                                                                                                                                                                                                                                                                       | 1483171200 | 1451635200   | SFO-153315 | 1491283524  | 164564994 | 6ffb6473475848f0a8f69393699a3461 | ScheduleD        | SF Recreation & Parks Department       | [REDACTED] | San Francisco | CA    | 94117 |                                        | 1501830000 | 300.0  | Outside Land Tickets             | 
| Richards, Dennis | EOBCDH_Planning Commission           | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Planning Commission,electionDate:None                                                                                                                                                                                                                                                                                                                                 | 1483171200 | 1451635200   | SFO-153839 | 1491279687  | 164563959 | c329ef7433a4493db0102a1853b09a05 | ScheduleD        | San Francisco Housing Action Coalition | [REDACTED] | San Francisco | Ca    | 94103 |                                        | 1464159600 | 75.0   | Comp. Ticket to Spring Symposium | 
| Richards, Dennis | EOBCDH_Planning Commission           | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Planning Commission,electionDate:None                                                                                                                                                                                                                                                                                                                                 | 1483171200 | 1451635200   | SFO-153839 | 1491279687  | 164563959 | 1d6870973aec4fcfbb564ffa2451bd70 | ScheduleD        | SST Investments                        | [REDACTED] | San Francisco | Ca    | 94103 | Real Estate Development and Investment | 1482220800 | 100.0  | Holiday Luncheon Meal            | 
| Richards, Dennis | EOBCDH_Planning Commission           | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Planning Commission,electionDate:None                                                                                                                                                                                                                                                                                                                                 | 1483171200 | 1451635200   | SFO-153839 | 1491279687  | 164563959 | e31c7de58e9e4e129c13014ebe422064 | ScheduleD        | SIA Consulting                         | [REDACTED] | San Francisco | Ca    | 94103 | Architecture and Engineering           | 1482220800 | 200.0  | Holiday Dinner                   | 
| Jung, Charles    | EOBCDH_Elections Commission          | Member        | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Member,filerDivisionBoardDistrict:Elections Commission,electionDate:None                                                                                                                                                                                                                                                                                                                                      | 1483171200 | 1451635200   | SFO-153644 | 1491264848  | 164557760 | 049a0a11077d4cceb99c77a89d39585a | ScheduleD        | First Legal Deposition Services        | [REDACTED] | Los Angeles   | CA    | 90026 | Depositions                            | 1475305200 | 200.0  | Ticket to AAAJ-LA Gala           | 
| Jung, Charles    | EOBCDH_Elections Commission          | Member        | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Member,filerDivisionBoardDistrict:Elections Commission,electionDate:None                                                                                                                                                                                                                                                                                                                                      | 1483171200 | 1451635200   | SFO-153644 | 1491264848  | 164557760 | 6d21765f266f4ce59677757d74334fb1 | ScheduleD        | Mark Punzalan                          | [REDACTED] | Redwood City  | CA    | 94063 | Attorney                               | 1482480000 | 65.0   | Baby present                     | 
| Jung, Charles    | EOBCDH_Elections Commission          | Member        | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Member,filerDivisionBoardDistrict:Elections Commission,electionDate:None                                                                                                                                                                                                                                                                                                                                      | 1483171200 | 1451635200   | SFO-153644 | 1491264848  | 164557760 | d0389717168e4090bc5477adccad351f | ScheduleD        | Katherine Ikeda                        | [REDACTED] | San Francisco | CA    | 94115 |                                        | 1452844800 | 300.0  | Tickets                          | 
| Jung, Charles    | EOBCDH_Elections Commission          | Member        | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Member,filerDivisionBoardDistrict:Elections Commission,electionDate:None                                                                                                                                                                                                                                                                                                                                      | 1483171200 | 1451635200   | SFO-153644 | 1491264848  | 164557760 | 88575d9e0072465cae84d7de56644f39 | ScheduleD        | Gluck Daniel LLP                       | [REDACTED] | San Francisco | CA    | 94104 | Law firm                               | -285004800 | 59.99  | Alcohol                          | 
| Lee, Edwin       | EOBCDH_Mayor Office of the           | Mayor         | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Mayor,filerDivisionBoardDistrict:Mayor Office of the,electionDate:None|leavingDate:None,filerAgency:Bay Area Air Quality Management District,assumingDate:None,filerPosition:Board Member,filerDivisionBoardDistrict:Board,electionDate:None|leavingDate:None,filerAgency:Association of Bay Area Governments,assumingDate:None,filerPosition:Board Member,filerDivisionBoardDistrict:Board,electionDate:None | 1483171200 | 1451635200   | SFO-151819 | 1491263784  | 164555996 | 14bf7b9f97384554be5cfa45598b485b | ScheduleD        | Victor Makras                          | [REDACTED] | San Francisco | CA    | 94114 | Real Estate                            | 1481097600 | 200.0  | Flower Arrangement               | 
| Lee, Edwin       | EOBCDH_Mayor Office of the           | Mayor         | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Mayor,filerDivisionBoardDistrict:Mayor Office of the,electionDate:None|leavingDate:None,filerAgency:Bay Area Air Quality Management District,assumingDate:None,filerPosition:Board Member,filerDivisionBoardDistrict:Board,electionDate:None|leavingDate:None,filerAgency:Association of Bay Area Governments,assumingDate:None,filerPosition:Board Member,filerDivisionBoardDistrict:Board,electionDate:None | 1483171200 | 1451635200   | SFO-151819 | 1491263784  | 164555996 | c4a5dd26802144d4a6ce0aa0dda121d3 | ScheduleD        | Clark Construction Group               | [REDACTED] | San Francisco | CA    | 94588 | Construction                           | 1481702400 | 115.0  | Two bottles of wine.             | 
```