# Form 700 Schedule A1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/form-700-schedule-a1) |
| Metadata | [Link](https://data.sfgov.org/api/views/tzbk-2xg8) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/tzbk-2xg8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/tzbk-2xg8/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | tzbk-2xg8 |
| Name | Form 700 Schedule A1 |
| Attribution | Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, form 700, schedules, sei, statement of economic interests |
| Created | 2016-05-18T18:13:35Z |
| Publication Date | 2016-06-13T22:37:01Z |

## Description

Stocks, including those held in IRA or 401K Link to Form 700 overview: http://www.fppc.ca.gov/Form700.html

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | series tag     | filer_name                             | Filer Name                             | text      | text        |
| Yes      | series tag     | department_name                        | Department Name                        | text      | text        |
| Yes      | series tag     | position_name                          | Position Name                          | text      | text        |
| Yes      | series tag     | offices                                | Offices                                | text      | text        |
| Yes      | time           | period_start                           | Period Start                           | date      | date        |
| No       |                | period_end                             | Period End                             | date      | date        |
| No       |                | filing_date                            | Filing Date                            | date      | date        |
| Yes      | series tag     | filer_id                               | Filer                                  | text      | text        |
| Yes      | series tag     | filing_id                              | Filing                                 | text      | text        |
| No       |                | id                                     | Id                                     | text      | text        |
| Yes      | series tag     | transaction_type                       | Transaction Type                       | text      | text        |
| Yes      | series tag     | name_of_business_entity                | Name Of Business Entity                | text      | text        |
| Yes      | series tag     | business_description                   | Business Description                   | text      | text        |
| Yes      | numeric metric | fair_market_value                      | Fair Market Value                      | money     | money       |
| Yes      | series tag     | fair_market_value_as_range             | Fair Market Value As Range             | text      | text        |
| Yes      | series tag     | nature_of_investment                   | Nature Of Investment                   | text      | text        |
| Yes      | series tag     | nature_of_investment_other_description | Nature Of Investment Other Description | text      | text        |
| Yes      | numeric metric | partnership_amount                     | Partnership Amount                     | money     | money       |
| Yes      | series tag     | partnership_amount_as_range            | Partnership Amount As Range            | text      | text        |
| No       |                | date_acquired                          | Date Acquired                          | date      | date        |
| No       |                | date_disposed                          | Date Disposed                          | date      | date        |
```

## Time Field

```ls
Value = period_start
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = period_end,filing_date,id,date_acquired,date_disposed
```

## Data Commands

```ls
series e:tzbk-2xg8 d:2016-01-01T08:00:00.000Z t:filer_name="Wadhwani, David" t:nature_of_investment=Stock t:business_description=Software t:name_of_business_entity=AppDynamics t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Trustee,filerDivisionBoardDistrict:Fine Arts Museums,electionDate:None" t:partnership_amount_as_range=Unset t:transaction_type=ScheduleA1 t:filer_id=SFO-153819 t:fair_market_value_as_range="Over $1,000,000" t:department_name="EOBCDH_Fine Arts Museums" t:position_name=Trustee t:filing_id=164678242 m:fair_market_value=1000000 m:partnership_amount=0

series e:tzbk-2xg8 d:2015-10-22T07:00:00.000Z t:filer_name="Donaldson, Roger" t:nature_of_investment=Stock t:business_description="SYNAPTICS INC" t:name_of_business_entity="SYNAPTICS INC" t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None" t:partnership_amount_as_range=Unset t:transaction_type=ScheduleA1 t:filer_id=SFO-154107 t:fair_market_value_as_range="$10,001 - $100,000" t:department_name="EOBCDH_Elections Commission" t:position_name=Commissioner t:filing_id=164640934 m:fair_market_value=10000 m:partnership_amount=0

series e:tzbk-2xg8 d:2015-10-22T07:00:00.000Z t:filer_name="Donaldson, Roger" t:nature_of_investment=Stock t:business_description="Vasco Data Security" t:name_of_business_entity="Vasco Data Security" t:offices="leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None" t:partnership_amount_as_range=Unset t:transaction_type=ScheduleA1 t:filer_id=SFO-154107 t:fair_market_value_as_range="$2,000 - $10,000" t:department_name="EOBCDH_Elections Commission" t:position_name=Commissioner t:filing_id=164640934 m:fair_market_value=2000 m:partnership_amount=0
```

## Meta Commands

```ls
metric m:fair_market_value p:integer l:"Fair Market Value" t:dataTypeName=money

metric m:partnership_amount p:double l:"Partnership Amount" t:dataTypeName=money

entity e:tzbk-2xg8 l:"Form 700 Schedule A1" t:attribution="Ethics Commission" t:url=https://data.sfgov.org/api/views/tzbk-2xg8

property e:tzbk-2xg8 t:meta.view v:id=tzbk-2xg8 v:category="City Management and Ethics" v:averageRating=0 v:name="Form 700 Schedule A1" v:attribution="Ethics Commission"

property e:tzbk-2xg8 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tzbk-2xg8 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:tzbk-2xg8 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| filer_name       | department_name             | position_name | offices                                                                                                                                                                      | period_start | period_end | filing_date | filer_id   | filing_id | id                               | transaction_type | name_of_business_entity | business_description | fair_market_value | fair_market_value_as_range | nature_of_investment | nature_of_investment_other_description | partnership_amount | partnership_amount_as_range | date_acquired | date_disposed | 
| ================ | =========================== | ============= | ============================================================================================================================================================================ | ============ | ========== | =========== | ========== | ========= | ================================ | ================ | ======================= | ==================== | ================= | ========================== | ==================== | ====================================== | ================== | =========================== | ============= | ============= | 
| Wadhwani, David  | EOBCDH_Fine Arts Museums    | Trustee       | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Trustee,filerDivisionBoardDistrict:Fine Arts Museums,electionDate:None         | 1451635200   | 1483171200 | 1492192465  | SFO-153819 | 164678242 | 00918372d0ac4795b6169bec4a42178d | ScheduleA1       | AppDynamics             | Software             | 1000000           | Over $1,000,000            | Stock                |                                        | 0.0                | Unset                       |               |               | 
| Donaldson, Roger | EOBCDH_Elections Commission | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | cdb6c4ad9e154fa799919d6ca6304e6c | ScheduleA1       | SYNAPTICS INC           | SYNAPTICS INC        | 10000             | $10,001 - $100,000         | Stock                |                                        | 0.0                | Unset                       |               |               | 
| Donaldson, Roger | EOBCDH_Elections Commission | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | 13d0db0a47b3480b913dd69ebf35e976 | ScheduleA1       | Vasco Data Security     | Vasco Data Security  | 2000              | $2,000 - $10,000           | Stock                |                                        | 0.0                | Unset                       |               |               | 
| Donaldson, Roger | EOBCDH_Elections Commission | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | f6df632db02741fa881ab7fd0700c75c | ScheduleA1       | DONALDSON INC COM I     | DONALDSON INC COM I  | 2000              | $2,000 - $10,000           | Stock                |                                        | 0.0                | Unset                       |               |               | 
| Donaldson, Roger | EOBCDH_Elections Commission | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | 4a5c97b20f0a4d39a17206077afc17ce | ScheduleA1       | SALESFORCE COM          | SALESFORCE COM       | 2000              | $2,000 - $10,000           | Stock                |                                        | 0.0                | Unset                       |               |               | 
| Donaldson, Roger | EOBCDH_Elections Commission | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | 534ef7725bd242bc8f50e6614cc6a7e6 | ScheduleA1       | AMERICAN TOWER CORP     | AMERICAN TOWER CORP  | 10000             | $10,001 - $100,000         | Stock                |                                        | 0.0                | Unset                       |               |               | 
| Donaldson, Roger | EOBCDH_Elections Commission | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | 2bd8db36cf914ee5ad10ba44af0ec4dc | ScheduleA1       | Penn West Petroleum     | Penn West Petroleum  | 2000              | $2,000 - $10,000           | Stock                |                                        | 0.0                | Unset                       |               |               | 
| Donaldson, Roger | EOBCDH_Elections Commission | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | 6e4a6135513544dead6540ffd62eec7b | ScheduleA1       | Shotwell Labs           | software development | 10000             | $10,001 - $100,000         | Other                | investor                               | 0.0                | Unset                       | 1456387200    |               | 
| Donaldson, Roger | EOBCDH_Elections Commission | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | 59f1d4e29298481d884c51fdbb259581 | ScheduleA1       | PROCTER & GAMBLE CO     | PROCTER & GAMBLE CO  | 10000             | $10,001 - $100,000         | Stock                |                                        | 0.0                | Unset                       |               |               | 
| Donaldson, Roger | EOBCDH_Elections Commission | Commissioner  | leavingDate:None,filerAgency:City and County of San Francisco,assumingDate:None,filerPosition:Commissioner,filerDivisionBoardDistrict:Elections Commission,electionDate:None | 1445497200   | 1483171200 | 1491896580  | SFO-154107 | 164640934 | ecbc67c58d984e018cae190deb01a339 | ScheduleA1       | Proshares Ultra         | Proshares Ultra      | 10000             | $10,001 - $100,000         | Stock                |                                        | 0.0                | Unset                       |               |               | 
```