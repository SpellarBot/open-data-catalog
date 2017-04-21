# ICJIA Illinois Criminal Justice Information Authority Open Grants August 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/icjia-illinois-criminal-justice-information-authority-open-grants-august-2011-41770) |
| Metadata | [Link](https://data.illinois.gov/api/views/yzsh-n2kp) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/yzsh-n2kp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/yzsh-n2kp/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | yzsh-n2kp |
| Name | ICJIA Illinois Criminal Justice Information Authority Open Grants August 2011 |
| Attribution | Illinois Criminal Justice Information Authority |
| Tags | criminal justice, victim services, icjia, grants |
| Created | 2012-01-23T20:23:52Z |
| Publication Date | 2012-01-23T20:26:45Z |

## Description

This is a listing of grants administered by the Illinois Criminal Justice Information Authority that were open on August 30, 2011.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | series tag     | program_agency_fund_recipient    | Program Agency / Fund Recipient  | text      | text        |
| Yes      | series tag     | program_title_type               | Program Title / Type             | text      | text        |
| Yes      | series tag     | county_location_of_recipient_    | County (location of recipient)   | text      | text        |
| Yes      | series tag     | federal_program_fund_source_name | Federal Program Fund Source Name | text      | text        |
| Yes      | series tag     | grant_start                      | Grant Start                      | text      | text        |
| Yes      | series tag     | grant_end                        | Grant End                        | text      | text        |
| Yes      | numeric metric | total_amount_of_federal_funds    | Total Amount of Federal Funds    | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yzsh-n2kp d:2011-01-01T00:00:00.000Z t:federal_program_fund_source_name="JUSTICE ASSISTANCE GRANTS" t:county_location_of_recipient_=Cook t:grant_end=30-Sep-11 t:grant_start=01-Oct-10 t:program_agency_fund_recipient="COOK COUNTY ADULT PROBATION" t:program_title_type="COMMUNITY BASED TRANSITIONAL SERVICES FOR FEMALE OFFENDERS" m:total_amount_of_federal_funds=164162

series e:yzsh-n2kp d:2011-01-01T00:00:00.000Z t:federal_program_fund_source_name="JUSTICE ASSISTANCE GRANTS" t:county_location_of_recipient_=Cook t:grant_end=30-Sep-11 t:grant_start=01-Oct-10 t:program_agency_fund_recipient="COOK COUNTY SOCIAL SERVICES" t:program_title_type="COMMUNITY BASED TRANSITIONAL SERVICES FOR FEMALE OFFENDERS" m:total_amount_of_federal_funds=70000

series e:yzsh-n2kp d:2011-01-01T00:00:00.000Z t:federal_program_fund_source_name="JUSTICE ASSISTANCE GRANTS" t:county_location_of_recipient_=Will t:grant_end=30-Sep-11 t:grant_start=01-Oct-10 t:program_agency_fund_recipient="GOVERNORS STATE UNIVERSITY" t:program_title_type="COMMUNITY VIOLENCE PREVENTION" m:total_amount_of_federal_funds=20000
```

## Meta Commands

```ls
metric m:total_amount_of_federal_funds p:double l:"Total Amount of Federal Funds" t:dataTypeName=money

entity e:yzsh-n2kp l:"ICJIA Illinois Criminal Justice Information Authority Open Grants August 2011" t:attribution="Illinois Criminal Justice Information Authority" t:url=https://data.illinois.gov/api/views/yzsh-n2kp

property e:yzsh-n2kp t:meta.view v:id=yzsh-n2kp v:attributionLink=http://www.icjia.state.il.us/public/ v:averageRating=0 v:name="ICJIA Illinois Criminal Justice Information Authority Open Grants August 2011" v:attribution="Illinois Criminal Justice Information Authority"

property e:yzsh-n2kp t:meta.view.owner v:id=avuj-ix5c v:screenName="Jude Lemrow" v:displayName="Jude Lemrow"

property e:yzsh-n2kp t:meta.view.tableauthor v:id=avuj-ix5c v:screenName="Jude Lemrow" v:roleName=publisher v:displayName="Jude Lemrow"
```

## Top Records

```ls
| program_agency_fund_recipient                   | program_title_type                                         | county_location_of_recipient_ | federal_program_fund_source_name | grant_start | grant_end | total_amount_of_federal_funds | 
| =============================================== | ========================================================== | ============================= | ================================ | =========== | ========= | ============================= | 
| COOK COUNTY ADULT PROBATION                     | COMMUNITY BASED TRANSITIONAL SERVICES FOR FEMALE OFFENDERS | Cook                          | JUSTICE ASSISTANCE GRANTS        | 01-Oct-10   | 30-Sep-11 | 164162.00                     | 
| COOK COUNTY SOCIAL SERVICES                     | COMMUNITY BASED TRANSITIONAL SERVICES FOR FEMALE OFFENDERS | Cook                          | JUSTICE ASSISTANCE GRANTS        | 01-Oct-10   | 30-Sep-11 | 70000.00                      | 
| GOVERNORS STATE UNIVERSITY                      | COMMUNITY VIOLENCE PREVENTION                              | Will                          | JUSTICE ASSISTANCE GRANTS        | 01-Oct-10   | 30-Sep-11 | 20000.00                      | 
| LAKE COUNTY STATE'S ATTORNEY'S OFFICE           | COMMUNITY VIOLENCE PREVENTION                              | Lake                          | JUSTICE ASSISTANCE GRANTS        | 15-Mar-11   | 30-Sep-11 | 138318.00                     | 
| LAKE COUNTY STATE'S ATTORNEY'S OFFICE           | COMMUNITY VIOLENCE PREVENTION                              | Lake                          | JUSTICE ASSISTANCE GRANTS        | 01-Jul-11   | 30-Sep-11 | 7000.00                       | 
| ILLINOIS DEPARTMENT OF CORRECTIONS              | CORRECTIONAL INITIATIVES                                   | Statewide                     | JUSTICE ASSISTANCE GRANTS        | 01-Oct-10   | 30-Sep-11 | 414462.00                     | 
| ILLINOIS DEPARTMENT OF CORRECTIONS              | CORRECTIONAL INITIATIVES                                   | Statewide                     | JUSTICE ASSISTANCE GRANTS        | 31-Dec-10   | 30-Sep-11 | 190081.00                     | 
| ILLINOIS DEPARTMENT OF JUVENILE JUSTICE         | CORRECTIONAL INITIATIVES                                   | Statewide                     | JUSTICE ASSISTANCE GRANTS        | 01-Oct-10   | 30-Sep-11 | 459000.00                     | 
| ILLINOIS CRIMINAL JUSTICE INFORMATION AUTHORITY | PROGRAM EVALUATIONS                                        | Statewide                     | JUSTICE ASSISTANCE GRANTS        | 01-Aug-10   | 30-Sep-11 | 682900.00                     | 
| St. Leonard's Ministries                        | Ex-Offender Re-Entry Services                              | Cook                          | JUSTICE ASSISTANCE GRANTS        | 01-Jan-11   | 31-Dec-11 | 125000.00                     | 
```