# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Long Term Operating Support Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-closings-long-term-operating-suppor-c00d1) |
| Metadata | [Link](https://data.illinois.gov/api/views/wbyx-c7s3) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wbyx-c7s3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wbyx-c7s3/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wbyx-c7s3 |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Long Term Operating Support Program |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T17:15:32Z |
| Publication Date | 2012-01-25T21:59:38Z |

## Description

FY2010 Governor's Report - Closings.Long Term Operating Support Program

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                           | Data Type     | Render Type   |
| ======== | ============== | ============================================== | ============================================== | ============= | ============= |
| No       |                | fiscal_year_                                   | FISCAL YEAR                                    | number        | text          |
| Yes      | series tag     | agency_name                                    | AGENCY NAME                                    | text          | text          |
| No       |                | development_address                            | DEVELOPMENT ADDRESS                            | text          | text          |
| Yes      | series tag     | county                                         | COUNTY                                         | text          | text          |
| Yes      | series tag     | grant                                          | GRANT                                          | text          | text          |
| Yes      | time           | closing_date                                   | CLOSING DATE                                   | calendar_date | calendar_date |
| Yes      | numeric metric | total_long_term_operating_system_program_award | TOTAL LONG TERM OPERATING SYSTEM PROGRAM AWARD | money         | money         |
| Yes      | numeric metric | of_units                                       | # OF UNITS                                     | number        | number        |
```

## Time Field

```ls
Value = closing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = development_address,fiscal_year_
```

## Data Commands

```ls
series e:wbyx-c7s3 d:2009-10-23T00:00:00.000Z t:grant=Grant t:county=Monroe t:agency_name="Monroe County Apartments 4 Association" m:total_long_term_operating_system_program_award=870177 m:of_units=7

series e:wbyx-c7s3 d:2009-10-29T00:00:00.000Z t:grant=Grant t:county=McHenry t:agency_name="McHenry County Community Homes, Inc" m:total_long_term_operating_system_program_award=1129233 m:of_units=8

series e:wbyx-c7s3 d:2009-10-26T00:00:00.000Z t:grant=Grant t:county=Massac t:agency_name="Light the Way of Metropolis, Inc" m:total_long_term_operating_system_program_award=1410195 m:of_units=15
```

## Meta Commands

```ls
metric m:total_long_term_operating_system_program_award p:integer l:"TOTAL LONG TERM OPERATING SYSTEM PROGRAM AWARD" t:dataTypeName=money

metric m:of_units p:integer l:"# OF UNITS" t:dataTypeName=number

entity e:wbyx-c7s3 l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Long Term Operating Support Program" t:url=https://data.illinois.gov/api/views/wbyx-c7s3

property e:wbyx-c7s3 t:meta.view v:id=wbyx-c7s3 v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Long Term Operating Support Program"

property e:wbyx-c7s3 t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:wbyx-c7s3 t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year_ | agency_name                            | development_address | county    | grant | closing_date        | total_long_term_operating_system_program_award | of_units | 
| ============ | ====================================== | =================== | ========= | ===== | =================== | ============================================== | ======== | 
| 2010         | Monroe County Apartments 4 Association | Bradford            | Monroe    | Grant | 2009-10-23T00:00:00 | 870177                                         | 7        | 
| 2010         | McHenry County Community Homes, Inc    | McHenry             | McHenry   | Grant | 2009-10-29T00:00:00 | 1129233                                        | 8        | 
| 2010         | Light the Way of Metropolis, Inc       | Metropolis          | Massac    | Grant | 2009-10-26T00:00:00 | 1410195                                        | 15       | 
| 2010         | Mt Vernon Senior Limited Partnership   | Mt Vernon           | Jefferson | Grant | 2009-10-22T00:00:00 | 1283700                                        | 14       | 
```