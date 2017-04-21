# Form 700 Schedule C

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/form-700-schedule-c) |
| Metadata | [Link](https://data.sfgov.org/api/views/fkhv-84jp) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/fkhv-84jp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/fkhv-84jp/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | fkhv-84jp |
| Name | Form 700 Schedule C |
| Attribution | Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, form 700, schedules, sei, statement of economic interests |
| Created | 2016-05-18T18:11:05Z |
| Publication Date | 2016-06-13T22:37:15Z |

## Description

Non-governmental salaries of public official and spouse/registered domestic partnerships Link to Form 700 overview: http://www.fppc.ca.gov/Form700.html

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | filer_name                    | Filer Name                    | text      | text        |
| Yes      | series tag     | department_name               | Department Name               | text      | text        |
| Yes      | series tag     | position_name                 | Position Name                 | text      | text        |
| Yes      | series tag     | offices                       | Offices                       | text      | text        |
| Yes      | time           | period_start                  | Period Start                  | date      | date        |
| No       |                | period_end                    | Period End                    | date      | date        |
| No       |                | filing_date                   | Filing Date                   | date      | date        |
| Yes      | series tag     | filer_id                      | Filer                         | text      | text        |
| Yes      | series tag     | filing_id                     | Filing                        | text      | text        |
| No       |                | id                            | Id                            | text      | text        |
| Yes      | series tag     | transaction_type              | Transaction Type              | text      | text        |
| Yes      | series tag     | name_of_income_source         | Name Of Income Source         | text      | text        |
| No       |                | income_address                | Income Address                | text      | text        |
| Yes      | series tag     | income_city                   | Income City                   | text      | text        |
| Yes      | series tag     | income_state                  | Income State                  | text      | text        |
| Yes      | series tag     | income_zip                    | Income Zip                    | text      | text        |
| Yes      | series tag     | income_business_activity      | Income Business Activity      | text      | text        |
| Yes      | series tag     | income_business_position      | Income Business Position      | text      | text        |
| Yes      | numeric metric | income_gross_income           | Income Gross Income           | money     | money       |
| Yes      | series tag     | income_gross_income_as_range  | Income Gross Income As Range  | text      | text        |
| Yes      | series tag     | reason_for_income             | Reason For Income             | text      | text        |
| Yes      | series tag     | reason_for_income_sale        | Reason For Income Sale        | text      | text        |
| Yes      | series tag     | reason_for_income_other       | Reason For Income Other       | text      | text        |
| Yes      | series tag     | income_sources                | Income Sources                | text      | text        |
| Yes      | series tag     | loan_name_of_lender           | Loan Name Of Lender           | text      | text        |
| No       |                | loan_address                  | Loan Address                  | text      | text        |
| Yes      | series tag     | loan_city                     | Loan City                     | text      | text        |
| Yes      | series tag     | loan_state                    | Loan State                    | text      | text        |
| Yes      | series tag     | loan_zip                      | Loan Zipcode                  | text      | text        |
| Yes      | series tag     | loan_business_activity        | Loan Business Activity        | text      | text        |
| Yes      | numeric metric | loan_highest_balance          | Loan Highest Balance          | money     | money       |
| Yes      | series tag     | loan_highest_balance_as_range | Loan Highest Balance As Range | text      | text        |
| Yes      | numeric metric | loan_interest_rate            | Loan Interest Rate            | percent   | percent     |
| Yes      | series tag     | loan_term                     | Loan Term                     | text      | text        |
| Yes      | series tag     | loan_security                 | Loan Security                 | text      | text        |
```

## Time Field

```ls
Value = period_start
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = period_end,filing_date,id,income_address,loan_address
```

## Data Commands

```ls
series e:fkhv-84jp d:2016-01-01T08:00:00.000Z t:reason_for_income="Other Salary + Equity" t:name_of_income_source=Adobe t:filer_name="Wadhwani, David" t:income_business_position="SVP, Digital Media @ Adobe" t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Trustee,filerDivisionBoardDistrict:Fine Arts Museums,electionDate:None" t:transaction_type=ScheduleC t:filer_id=SFO-153819 t:income_zip=94113 t:income_city="San Francisco" t:income_state=CA t:department_name="EOBCDH_Fine Arts Museums" t:income_gross_income_as_range="Over $100,000" t:position_name=Trustee t:filing_id=164678242 m:loan_interest_rate=0 m:income_gross_income=100000 m:loan_highest_balance=0

series e:fkhv-84jp d:2016-01-01T08:00:00.000Z t:reason_for_income=Salary t:income_business_activity=Software t:filer_name="Wadhwani, David" t:income_business_position=CEO t:transaction_type=ScheduleC t:position_name=Trustee t:name_of_income_source=AppDynamics t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Trustee,filerDivisionBoardDistrict:Fine Arts Museums,electionDate:None" t:filer_id=SFO-153819 t:income_zip=94107 t:income_city="San Francisco" t:income_state=CA t:department_name="EOBCDH_Fine Arts Museums" t:income_gross_income_as_range="Over $100,000" t:filing_id=164678242 m:loan_interest_rate=0 m:income_gross_income=100000 m:loan_highest_balance=0

series e:fkhv-84jp d:2016-01-01T08:00:00.000Z t:reason_for_income=Salary t:name_of_income_source=Cisco t:filer_name="Wadhwani, David" t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Trustee,filerDivisionBoardDistrict:Fine Arts Museums,electionDate:None" t:transaction_type=ScheduleC t:filer_id=SFO-153819 t:income_zip=94107 t:income_city="San Francisco" t:income_state=CA t:department_name="EOBCDH_Fine Arts Museums" t:income_gross_income_as_range="Over $100,000" t:position_name=Trustee t:filing_id=164678242 m:loan_interest_rate=0 m:income_gross_income=100000 m:loan_highest_balance=0
```

## Meta Commands

```ls
metric m:income_gross_income p:double l:"Income Gross Income" t:dataTypeName=money

metric m:loan_highest_balance p:double l:"Loan Highest Balance" t:dataTypeName=money

metric m:loan_interest_rate p:float l:"Loan Interest Rate" t:dataTypeName=percent

entity e:fkhv-84jp l:"Form 700 Schedule C" t:attribution="Ethics Commission" t:url=https://data.sfgov.org/api/views/fkhv-84jp

property e:fkhv-84jp t:meta.view v:id=fkhv-84jp v:category="City Management and Ethics" v:averageRating=0 v:name="Form 700 Schedule C" v:attribution="Ethics Commission"

property e:fkhv-84jp t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:fkhv-84jp t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:fkhv-84jp t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| filer_name        | department_name                         | position_name | offices                                                                                                                                                                                                         | period_start | period_end | filing_date | filer_id   | filing_id | id                               | transaction_type | name_of_income_source         | income_address | income_city   | income_state | income_zip | income_business_activity                                     | income_business_position   | income_gross_income | income_gross_income_as_range | reason_for_income                              | reason_for_income_sale | reason_for_income_other | income_sources | loan_name_of_lender | loan_address | loan_city | loan_state | loan_zip | loan_business_activity | loan_highest_balance | loan_highest_balance_as_range | loan_interest_rate | loan_term | loan_security | 
| ================= | ======================================= | ============= | =============================================================================================================================================================================================================== | ============ | ========== | =========== | ========== | ========= | ================================ | ================ | ============================= | ============== | ============= | ============ | ========== | ============================================================ | ========================== | =================== | ============================ | ============================================== | ====================== | ======================= | ============== | =================== | ============ | ========= | ========== | ======== | ====================== | ==================== | ============================= | ================== | ========= | ============= | 
| Wadhwani, David   | EOBCDH_Fine Arts Museums                | Trustee       | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Trustee,filerDivisionBoardDistrict:Fine Arts Museums,electionDate:None                                            | 1451635200   | 1483171200 | 1492192465  | SFO-153819 | 164678242 | 872922b135594eb68b8c4c45f4b83a72 | ScheduleC        | Adobe                         | [REDACTED]     | San Francisco | CA           | 94113      |                                                              | SVP, Digital Media @ Adobe | 100000.0            | Over $100,000                | Other Salary + Equity                          |                        |                         |                |                     |              |           |            |          |                        | 0.0                  |                               | 0.0                |           |               | 
| Wadhwani, David   | EOBCDH_Fine Arts Museums                | Trustee       | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Trustee,filerDivisionBoardDistrict:Fine Arts Museums,electionDate:None                                            | 1451635200   | 1483171200 | 1492192465  | SFO-153819 | 164678242 | d76efcb74baf4394a348f5c26478de35 | ScheduleC        | AppDynamics                   | [REDACTED]     | San Francisco | CA           | 94107      | Software                                                     | CEO                        | 100000.0            | Over $100,000                | Salary                                         |                        |                         |                |                     |              |           |            |          |                        | 0.0                  |                               | 0.0                |           |               | 
| Wadhwani, David   | EOBCDH_Fine Arts Museums                | Trustee       | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Trustee,filerDivisionBoardDistrict:Fine Arts Museums,electionDate:None                                            | 1451635200   | 1483171200 | 1492192465  | SFO-153819 | 164678242 | 802c3849b98d4eb6ae455289c411c74d | ScheduleC        | Cisco                         | [REDACTED]     | San Francisco | CA           | 94107      |                                                              |                            | 100000.0            | Over $100,000                | Salary                                         |                        |                         |                |                     |              |           |            |          |                        | 0.0                  |                               | 0.0                |           |               | 
| Bernal, Dan       | EOBCDH_Public Health Commission         |               | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:2017-04-04T00:00:00.0000000-07:00,filerPosition:Commissioner,filerDivisionBoardDistrict:Public Health Commission,electionDate:None   | 1459839600   | 1491289200 | 1492019130  | SFO-154605 | 164653746 | 6f27abec94004cbf95108a2372226bef | ScheduleC        | Nicole Hollis Interior Design | [REDACTED]     | San Francisco | CA           | 94103      | Interior Design                                              | Associate                  | 100000.0            | Over $100,000                | Spouse or Registered Domestic Partner's Income |                        |                         |                |                     |              |           |            |          |                        | 0.0                  |                               | 0.0                |           |               | 
| Bernal, Dan       | EOBCDH_Public Health Commission         |               | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:2017-04-04T00:00:00.0000000-07:00,filerPosition:Commissioner,filerDivisionBoardDistrict:Public Health Commission,electionDate:None   | 1459839600   | 1491289200 | 1492019130  | SFO-154605 | 164653746 | 816d7dce48a04409a4a44460bec0e437 | ScheduleC        | Nancy Pelosi for Congress     | [REDACTED]     | Washington    | DC           | 20005      | Campaign Committee                                           | Consultant                 | 10000.0             | $10,001 - $100,000           | Other Consulting Income                        |                        |                         |                |                     |              |           |            |          |                        | 0.0                  |                               | 0.0                |           |               | 
| Donaldson, Roger  | EOBCDH_Elections Commission             | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None                                    | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | 786c9ed6f973436793fd89aef749370d | ScheduleC        |                               |                |               |              |            |                                                              |                            | 0.0                 |                              |                                                |                        |                         |                | Roger Donaldson     | [REDACTED]   | Hawthorne | CA         | 90250    | self                   | 10000.0              | $10,001 - $100,000            | 0.0                |           | None          | 
| Cohen, Malia      | EOBCDH_Workforce Investment Board       | Member        | leavingDate:2017-03-14T00:00:00.0000000-07:00,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Member,filerDivisionBoardDistrict:Workforce Investment Board,electionDate:None       | 1451635200   | 1489474800 | 1491857097  | SFO-151833 | 164635708 | 92533a3ae28b4f67ab639751bd61c9a7 | ScheduleC        | Boxer and Gerson, LLP         | [REDACTED]     | Oakland       | CA           | 94612      | Attorney at Law                                              |                            | 100000.0            | Over $100,000                | Spouse or Registered Domestic Partner's Income |                        |                         |                |                     |              |           |            |          |                        | 0.0                  |                               | 0.0                |           |               | 
| Cohen, Malia      | EOBCDH_Workforce Investment Board       | Member        | leavingDate:2017-03-14T00:00:00.0000000-07:00,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Member,filerDivisionBoardDistrict:Workforce Investment Board,electionDate:None       | 1451635200   | 1489474800 | 1491857097  | SFO-151833 | 164635708 | 9b28e1dda17a4f368b494a7f3a311cc8 | ScheduleC        | Power Forward, LLC            | [REDACTED]     | San Francisco | CA           | 94107      | Consulting                                                   | Managing Partner           | 1000.0              | $1,001 - $10,000             | Salary                                         |                        |                         |                |                     |              |           |            |          |                        | 0.0                  |                               | 0.0                |           |               | 
| Millman, Jennifer | EOBCDH_Revenue Bond Oversight Committee |               | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:2017-03-28T00:00:00.0000000-07:00,filerPosition:Member,filerDivisionBoardDistrict:Revenue Bond Oversight Committee,electionDate:None | 1459234800   | 1490684400 | 1491585297  | SFO-154604 | 164620509 | dbc50895c62c4c3d8c25488a7fe59499 | ScheduleC        | Louie & Wong                  | [REDACTED]     | San Francisco | CA           | 94111      | Budget and legislative analysis for the Board of Supervisors | Senior Analyst             | 10000.0             | $10,001 - $100,000           | Salary                                         |                        |                         |                |                     |              |           |            |          |                        | 0.0                  |                               | 0.0                |           |               | 
| Millman, Jennifer | EOBCDH_Revenue Bond Oversight Committee |               | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:2017-03-28T00:00:00.0000000-07:00,filerPosition:Member,filerDivisionBoardDistrict:Revenue Bond Oversight Committee,electionDate:None | 1459234800   | 1490684400 | 1491585297  | SFO-154604 | 164620509 | e6256d7823814419b9346950bb44fbc2 | ScheduleC        | Debra A Newman                | [REDACTED]     | San Francisco | CA           | 94102      | Budget and legislative analysis for the Board of Supervisors | Senior Analyst             | 10000.0             | $10,001 - $100,000           | Salary                                         |                        |                         |                |                     |              |           |            |          |                        | 0.0                  |                               | 0.0                |           |               | 
```