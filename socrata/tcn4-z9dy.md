# Form 700 Schedule B

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/form-700-schedule-b) |
| Metadata | [Link](https://data.sfgov.org/api/views/tcn4-z9dy) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/tcn4-z9dy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/tcn4-z9dy/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | tcn4-z9dy |
| Name | Form 700 Schedule B |
| Attribution | Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, form 700, schedules, sei, statement of economic interests |
| Created | 2016-05-18T18:20:57Z |
| Publication Date | 2016-06-13T22:36:49Z |

## Description

Rental property in the jurisdiction Link to Form 700 overview: http://www.fppc.ca.gov/Form700.html

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| Yes      | series tag     | filer_name                               | Filer Name                               | text      | text        |
| Yes      | series tag     | department_name                          | Department Name                          | text      | text        |
| Yes      | series tag     | position_name                            | Position Name                            | text      | text        |
| Yes      | series tag     | offices                                  | Offices                                  | text      | text        |
| Yes      | time           | period_start                             | Period Start                             | date      | date        |
| No       |                | period_end                               | Period End                               | date      | date        |
| No       |                | filing_date                              | Filing Date                              | date      | date        |
| Yes      | series tag     | filer_id                                 | Filer                                    | text      | text        |
| Yes      | series tag     | filing_id                                | Filing                                   | text      | text        |
| No       |                | id                                       | Id                                       | text      | text        |
| Yes      | series tag     | transaction_type                         | Transaction Type                         | text      | text        |
| No       |                | parcel_or_address                        | Parcel Or Address                        | text      | text        |
| Yes      | series tag     | city                                     | City                                     | text      | text        |
| Yes      | numeric metric | fair_market_value_schedule_b             | Fair Market Value Schedule B             | money     | money       |
| Yes      | series tag     | fair_market_value_schedule_b_as_range    | Fair Market Value Schedule B As Range    | text      | text        |
| No       |                | date_acquired                            | Date Acquired                            | date      | date        |
| No       |                | date_disposed                            | Date Disposed                            | date      | date        |
| Yes      | series tag     | nature_of_interest                       | Nature Of Interest                       | text      | text        |
| Yes      | numeric metric | nature_of_interest_lease_years_remaining | Nature Of Interest Lease Years Remaining | number    | text        |
| Yes      | series tag     | nature_of_interest_other_description     | Nature Of Interest Other Description     | text      | text        |
| Yes      | numeric metric | gross_income_received                    | Gross Income Received                    | money     | money       |
| Yes      | series tag     | gross_income_received_as_range           | Gross Income Received As Range           | text      | text        |
| Yes      | series tag     | income_sources                           | Income Sources                           | text      | text        |
| Yes      | series tag     | loanname_of_lender                       | Loan Name Of Lender                      | text      | text        |
| No       |                | loanaddress                              | Loan Address                             | text      | text        |
| Yes      | series tag     | loancity                                 | Loan City                                | text      | text        |
| Yes      | series tag     | loanstate                                | Loan State                               | text      | text        |
| Yes      | series tag     | loanzip                                  | Loan Zipcode                             | text      | text        |
| Yes      | series tag     | loanbusiness_activity                    | Loan Business Activity                   | text      | text        |
| Yes      | numeric metric | loaninterest_rate                        | Loan Interest Rate                       | percent   | percent     |
| Yes      | series tag     | loanterm                                 | Loan Term                                | text      | text        |
| Yes      | numeric metric | loanhighest_balance                      | Loan Highest Balance                     | money     | money       |
| Yes      | series tag     | loanhighest_balance_as_range             | Loan Highest Balance As Range            | text      | text        |
| Yes      | series tag     | loanguarantor                            | Loan Guarantor                           | text      | text        |
```

## Time Field

```ls
Value = period_start
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = period_end,filing_date,id,parcel_or_address,date_acquired,date_disposed,loanaddress
```

## Data Commands

```ls
series e:tcn4-z9dy d:2016-01-01T08:00:00.000Z t:filer_name="Wadhwani, David" t:loanhighest_balance_as_range=Unset t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Trustee,filerDivisionBoardDistrict:Fine Arts Museums,electionDate:None" t:transaction_type=ScheduleB t:fair_market_value_schedule_b_as_range="Over $1,000,000" t:filer_id=SFO-153819 t:department_name="EOBCDH_Fine Arts Museums" t:position_name=Trustee t:nature_of_interest="Ownership/Deed of Trust" t:gross_income_received_as_range=Unset t:filing_id=164678242 t:city="San Francisco" m:loanhighest_balance=0 m:fair_market_value_schedule_b=1000000 m:gross_income_received=0 m:loaninterest_rate=0

series e:tcn4-z9dy d:2015-10-22T07:00:00.000Z t:filer_name="Donaldson, Roger" t:transaction_type=ScheduleB t:nature_of_interest="Ownership/Deed of Trust" t:position_name=Commissioner t:city="Vallejo CA" t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None" t:loanhighest_balance_as_range=Unset t:filer_id=SFO-154107 t:income_sources=name:[REDACTED] t:fair_market_value_schedule_b_as_range="$100,001 - $1,000,000" t:department_name="EOBCDH_Elections Commission" t:gross_income_received_as_range="$10,001 - $100,000" t:filing_id=164640934 m:loanhighest_balance=0 m:fair_market_value_schedule_b=100000 m:gross_income_received=10000 m:loaninterest_rate=0

series e:tcn4-z9dy d:2015-10-22T07:00:00.000Z t:filer_name="Donaldson, Roger" t:transaction_type=ScheduleB t:nature_of_interest="Ownership/Deed of Trust" t:position_name=Commissioner t:city="Vallejo CA" t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None" t:loanhighest_balance_as_range=Unset t:filer_id=SFO-154107 t:income_sources=name:[REDACTED] t:fair_market_value_schedule_b_as_range="$100,001 - $1,000,000" t:department_name="EOBCDH_Elections Commission" t:gross_income_received_as_range="$10,001 - $100,000" t:filing_id=164640934 m:loanhighest_balance=0 m:fair_market_value_schedule_b=100000 m:gross_income_received=10000 m:loaninterest_rate=0
```

## Meta Commands

```ls
metric m:fair_market_value_schedule_b p:integer l:"Fair Market Value Schedule B" t:dataTypeName=money

metric m:nature_of_interest_lease_years_remaining p:integer l:"Nature Of Interest Lease Years Remaining" t:dataTypeName=number

metric m:gross_income_received p:double l:"Gross Income Received" t:dataTypeName=money

metric m:loaninterest_rate p:float l:"Loan Interest Rate" t:dataTypeName=percent

metric m:loanhighest_balance p:integer l:"Loan Highest Balance" t:dataTypeName=money

entity e:tcn4-z9dy l:"Form 700 Schedule B" t:attribution="Ethics Commission" t:url=https://data.sfgov.org/api/views/tcn4-z9dy

property e:tcn4-z9dy t:meta.view v:id=tcn4-z9dy v:category="City Management and Ethics" v:averageRating=0 v:name="Form 700 Schedule B" v:attribution="Ethics Commission"

property e:tcn4-z9dy t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tcn4-z9dy t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:tcn4-z9dy t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| filer_name       | department_name                   | position_name                | offices                                                                                                                                                                                                   | period_start | period_end | filing_date | filer_id   | filing_id | id                               | transaction_type | parcel_or_address        | city              | fair_market_value_schedule_b | fair_market_value_schedule_b_as_range | date_acquired | date_disposed | nature_of_interest      | nature_of_interest_lease_years_remaining | nature_of_interest_other_description | gross_income_received | gross_income_received_as_range | income_sources  | loanname_of_lender    | loanaddress | loancity   | loanstate | loanzip    | loanbusiness_activity | loaninterest_rate | loanterm | loanhighest_balance | loanhighest_balance_as_range | loanguarantor | 
| ================ | ================================= | ============================ | ========================================================================================================================================================================================================= | ============ | ========== | =========== | ========== | ========= | ================================ | ================ | ======================== | ================= | ============================ | ===================================== | ============= | ============= | ======================= | ======================================== | ==================================== | ===================== | ============================== | =============== | ===================== | =========== | ========== | ========= | ========== | ===================== | ================= | ======== | =================== | ============================ | ============= | 
| Wadhwani, David  | EOBCDH_Fine Arts Museums          | Trustee                      | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Trustee,filerDivisionBoardDistrict:Fine Arts Museums,electionDate:None                                      | 1451635200   | 1483171200 | 1492192465  | SFO-153819 | 164678242 | c6a5e32d6947424d9076f63453c942b8 | ScheduleB        | 39 6th Ave               | San Francisco     | 1000000                      | Over $1,000,000                       |               |               | Ownership/Deed of Trust |                                          |                                      | 0.0                   | Unset                          |                 |                       |             |            |           |            |                       | 0.0               |          | 0                   | Unset                        |               | 
| Donaldson, Roger | EOBCDH_Elections Commission       | Commissioner                 | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None                              | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | 2205be2f767648608d0f13d5e924f4bf | ScheduleB        | 170 B Street             | Vallejo CA        | 100000                       | $100,001 - $1,000,000                 |               |               | Ownership/Deed of Trust |                                          |                                      | 10000.0               | $10,001 - $100,000             | name:[REDACTED] |                       |             |            |           |            |                       | 0.0               |          | 0                   | Unset                        |               | 
| Donaldson, Roger | EOBCDH_Elections Commission       | Commissioner                 | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None                              | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | ee1cef5090a340499f782d24bb37071e | ScheduleB        | 174 B Street             | Vallejo CA        | 100000                       | $100,001 - $1,000,000                 |               |               | Ownership/Deed of Trust |                                          |                                      | 10000.0               | $10,001 - $100,000             | name:[REDACTED] |                       |             |            |           |            |                       | 0.0               |          | 0                   | Unset                        |               | 
| Donaldson, Roger | EOBCDH_Elections Commission       | Commissioner                 | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None                              | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | de59db4de66a441391750a6765d6b21c | ScheduleB        | 952-954 Minnesota Street | San Francisco, CA | 1000000                      | Over $1,000,000                       |               |               | Ownership/Deed of Trust |                                          |                                      | 10000.0               | $10,001 - $100,000             | name:[REDACTED] | Wells Fargo Bank      | [REDACTED]  | Des Moines | IA        | 50306-3411 | Bank                  | 0.0               | 30       | 100000              | Over $100,000                |               | 
| Donaldson, Roger | EOBCDH_Elections Commission       | Commissioner                 | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None                              | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | caae34f3d56947168dede898d7eb589b | ScheduleB        | 155 Benson Street        | Vallejo CA        | 100000                       | $100,001 - $1,000,000                 |               |               | Ownership/Deed of Trust |                                          |                                      | 10000.0               | $10,001 - $100,000             | name:[REDACTED] | PHH Mortgage Services | [REDACTED]  | Pasadena   | CA        | 94107      | Mortgage Lender       | 0.0               | 30       | 500                 | $500 - $1,000                |               | 
| Cohen, Malia     | EOBCDH_Workforce Investment Board | Member                       | leavingDate:2017-03-14T00:00:00.0000000-07:00,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Member,filerDivisionBoardDistrict:Workforce Investment Board,electionDate:None | 1451635200   | 1489474800 | 1491857097  | SFO-151833 | 164635708 | 7ff4130cd49942469edd1ee7b1f90def | ScheduleB        | 2060 Sutter Street, #501 | San Francisco     | 1000000                      | Over $1,000,000                       | 1463788800    |               | Ownership/Deed of Trust |                                          |                                      | 10000.0               | $10,001 - $100,000             | name:[REDACTED] |                       |             |            |           |            |                       | 0.0               |          | 0                   | Unset                        |               | 
| DeCaigny, Tom    | EOBCDH_Arts Commission            | Director of Cultural Affairs | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Director of Cultural Affairs,filerDivisionBoardDistrict:Arts Commission,electionDate:None                   | 1451635200   | 1483171200 | 1491422227  | SFO-152778 | 164600009 | 6606d83317ab4dfba97dbd90a78d5488 | ScheduleB        | 626 Paris Street         | San Francisco     | 1000000                      | Over $1,000,000                       |               |               | Ownership/Deed of Trust |                                          |                                      | 0.0                   | Unset                          |                 |                       |             |            |           |            |                       | 0.0               |          | 0                   | Unset                        |               | 
| DeCaigny, Tom    | EOBCDH_Arts Commission            | Director of Cultural Affairs | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Director of Cultural Affairs,filerDivisionBoardDistrict:Arts Commission,electionDate:None                   | 1451635200   | 1483171200 | 1491422227  | SFO-152778 | 164600009 | 10734488e04940b6bbb3814f33f4030c | ScheduleB        | 47 Hallam Street         | San Francisco     | 100000                       | $100,001 - $1,000,000                 |               |               | Ownership/Deed of Trust |                                          |                                      | 10000.0               | $10,001 - $100,000             | name:[REDACTED] |                       |             |            |           |            |                       | 0.0               |          | 0                   | Unset                        |               | 
| Stewart, Pablo   | EOBCDH_Human Services Commission  | Commissioner                 | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Human Services Commission,electionDate:None                         | 1451635200   | 1483171200 | 1491418525  | SFO-1350   | 164599016 | da68e23a0cd14b5683b86a7cd3cda4ab | ScheduleB        | 824 Ashbury Street       | San Francisco     | 1000000                      | Over $1,000,000                       |               |               | Ownership/Deed of Trust |                                          |                                      | 0.0                   | Unset                          |                 |                       |             |            |           |            |                       | 0.0               |          | 0                   | Unset                        |               | 
| Stewart, Pablo   | EOBCDH_Human Services Commission  | Commissioner                 | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Human Services Commission,electionDate:None                         | 1451635200   | 1483171200 | 1491418525  | SFO-1350   | 164599016 | e86db4041cbe43d598729c74083e3df9 | ScheduleB        | 951 Kealaolu Ave         | Honolulu          | 1000000                      | Over $1,000,000                       |               |               | Ownership/Deed of Trust |                                          |                                      | 10000.0               | $10,001 - $100,000             | name:[REDACTED] |                       |             |            |           |            |                       | 0.0               |          | 0                   | Unset                        |               | 
```