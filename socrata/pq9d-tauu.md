# ICJIA Illinois Criminal Justice Information Authority Open Grants (January 2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/icjia-illinois-criminal-justice-information-authority-open-grants-january-2012-c4760) |
| Metadata | [Link](https://data.illinois.gov/api/views/pq9d-tauu) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/pq9d-tauu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/pq9d-tauu/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | pq9d-tauu |
| Name | ICJIA Illinois Criminal Justice Information Authority Open Grants (January 2012) |
| Attribution | Illinois Criminal Justice Information Authority |
| Tags | criminal justice, victim services, grants, icjia |
| Created | 2012-01-23T20:01:05Z |
| Publication Date | 2012-01-23T20:05:40Z |

## Description

This is a listing of grants administered by the Illinois Criminal Justice Information Authority that were open on January 23, 2012.

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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pq9d-tauu d:2012-01-01T00:00:00.000Z t:federal_program_fund_source_name="JUSTICE ASSISTANCE GRANT" t:county_location_of_recipient_=WINNEBAGO t:grant_end=30-Sep-12 t:grant_start=01-Oct-11 t:program_agency_fund_recipient="17th Judicial Circuit / Winnebago County" t:program_title_type="INFORMATION SYSTEMS" m:total_amount_of_federal_funds=40000

series e:pq9d-tauu d:2012-01-01T00:00:00.000Z t:federal_program_fund_source_name="VICTIMS OF CRIME ACT" t:county_location_of_recipient_="Du Page" t:grant_end=30-Sep-12 t:grant_start=01-Oct-11 t:program_agency_fund_recipient="ALLIANCE AGAINST INTOXICATED MOTORISTS" t:program_title_type="STATEWIDE SERVICES TO VICTIMS OF DRUNK DRIVERS" m:total_amount_of_federal_funds=87704

series e:pq9d-tauu d:2012-01-01T00:00:00.000Z t:federal_program_fund_source_name="JUSTICE ASSISTANCE GRANTS / ARRA" t:county_location_of_recipient_=Cook t:grant_end=28-Feb-13 t:grant_start=16-Mar-10 t:program_agency_fund_recipient="Alliance for the Mentally Ill of Greater Chicago" t:program_title_type="MENTAL HEALTH INITIATIVES" m:total_amount_of_federal_funds=249952
```

## Meta Commands

```ls
metric m:total_amount_of_federal_funds p:double l:"Total Amount of Federal Funds" t:dataTypeName=money

entity e:pq9d-tauu l:"ICJIA Illinois Criminal Justice Information Authority Open Grants (January 2012)" t:attribution="Illinois Criminal Justice Information Authority" t:url=https://data.illinois.gov/api/views/pq9d-tauu

property e:pq9d-tauu t:meta.view v:id=pq9d-tauu v:attributionLink=http://www.icjia.state.il.us/public/ v:averageRating=0 v:name="ICJIA Illinois Criminal Justice Information Authority Open Grants (January 2012)" v:attribution="Illinois Criminal Justice Information Authority"

property e:pq9d-tauu t:meta.view.owner v:id=avuj-ix5c v:screenName="Jude Lemrow" v:displayName="Jude Lemrow"

property e:pq9d-tauu t:meta.view.tableauthor v:id=avuj-ix5c v:screenName="Jude Lemrow" v:roleName=publisher v:displayName="Jude Lemrow"
```

## Top Records

```ls
| program_agency_fund_recipient                    | program_title_type                                            | county_location_of_recipient_ | federal_program_fund_source_name | grant_start | grant_end | total_amount_of_federal_funds | 
| ================================================ | ============================================================= | ============================= | ================================ | =========== | ========= | ============================= | 
| 17th Judicial Circuit / Winnebago County         | INFORMATION SYSTEMS                                           | WINNEBAGO                     | JUSTICE ASSISTANCE GRANT         | 01-Oct-11   | 30-Sep-12 | 40000.00                      | 
| ALLIANCE AGAINST INTOXICATED MOTORISTS           | STATEWIDE SERVICES TO VICTIMS OF DRUNK DRIVERS                | Du Page                       | VICTIMS OF CRIME ACT             | 01-Oct-11   | 30-Sep-12 | 87704.00                      | 
| Alliance for the Mentally Ill of Greater Chicago | MENTAL HEALTH INITIATIVES                                     | Cook                          | JUSTICE ASSISTANCE GRANTS / ARRA | 16-Mar-10   | 28-Feb-13 | 249952.00                     | 
| AMY SCHULTZ CHILD ADVOCACY CENTER                | CHILD ADVOCACY CENTER SERVICES (VOCA)                         | Jefferson                     | VICTIMS OF CRIME ACT             | 01-Oct-11   | 30-Sep-12 | 32239.00                      | 
| APNA GHAR                                        | TRANSITIONAL HOUSING AND SUPPORT SERVICES                     | Cook                          | VIOLENCE AGAINST WOMEN ACT       | 01-Nov-11   | 31-Oct-12 | 21664.00                      | 
| ARLINGTON HEIGHTS POLICE DEPARTMENT              | LAW ENFORCEMENT / PROSECUTOR-BASED VICTIM ASSISTANCE SERVICES | Cook                          | VICTIMS OF CRIME ACT             | 01-May-11   | 30-Apr-12 | 50462.00                      | 
| ASSAULT & ABUSE SERVICES OF STEPHENSON COUNTY    | SERVICES TO VICTIMS OF SEXUAL ASSAULT                         | Stephenson                    | VICTIMS OF CRIME ACT             | 01-Oct-11   | 30-Sep-12 | 48512.00                      | 
| BATAVIA POLICE DEPARTMENT                        | Law Enforcement Equipment Program                             | Kane                          | JUSTICE ASSISTANCE GRANT         | 01-Dec-11   | 31-Mar-12 | 20000.00                      | 
| BETWEEN FRIENDS                                  | SERVICES TO VICTIMS OF DOMESTIC VIOLENCE                      | Cook                          | VICTIMS OF CRIME ACT             | 01-Sep-11   | 31-Aug-12 | 122206.00                     | 
| BLACKHAWK AREA TASK FORCE (Z1TF)                 | EXPANDING MULTI-JURISDICTIONAL NARCOTICS UNITS                | Whiteside                     | JUSTICE ASSISTANCE GRANT         | 01-Jul-11   | 30-Jun-12 | 3339.00                       | 
```