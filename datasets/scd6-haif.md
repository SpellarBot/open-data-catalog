# SFY13 Open Grants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sfy13-open-grants-9b5b0) |
| Metadata | [Link](https://data.illinois.gov/api/views/scd6-haif) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/scd6-haif/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/scd6-haif/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | scd6-haif |
| Name | SFY13 Open Grants |
| Attribution | Illinois Criminal Justice Information Authority |
| Category | Public Safety |
| Tags | grants, open grants, icjia, criminal justice, criminal, justice, criminal justice authority, criminal justice information authority, illinois criminal justice information authority |
| Created | 2014-03-20T18:25:00Z |
| Publication Date | 2014-03-20T18:37:55Z |

## Description

This is a list of all grants administered by the ICJIA that were open at any time during State Fiscal Year 2013.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| No       | time           | :updated_at                               | updated_at                                | meta_data | meta_data   |
| Yes      | series tag     | program_agency_fund_recipient             | Program Agency / Fund Recipient           | text      | text        |
| Yes      | series tag     | program_title_type                        | Program Title / Type                      | text      | text        |
| Yes      | series tag     | county_location_of_recipient              | County (location of recipient)            | text      | text        |
| Yes      | series tag     | zip_code                                  | Zip Code                                  | text      | text        |
| Yes      | series tag     | federal_program_or_state_fund_source_name | Federal Program or State Fund Source Name | text      | text        |
| Yes      | series tag     | grant_start                               | Grant Start                               | text      | text        |
| Yes      | series tag     | grant_end                                 | Grant End                                 | text      | text        |
| Yes      | numeric metric | total_amount_of_program_funds             | Total Amount of Program Funds             | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:scd6-haif d:2014-03-20T11:25:04.000Z t:federal_program_or_state_fund_source_name="JUSTICE ASSISTANCE GRANT" t:county_location_of_recipient=WINNEBAGO t:zip_code=61101-1239 t:grant_end=30-Sep-12 t:grant_start=01-Oct-11 t:program_agency_fund_recipient="17th Judicial Circuit / Winnebago County" t:program_title_type="INFORMATION SYSTEMS" m:total_amount_of_program_funds=35541

series e:scd6-haif d:2014-03-20T11:25:04.000Z t:federal_program_or_state_fund_source_name="JUSTICE ASSISTANCE GRANT" t:county_location_of_recipient=WINNEBAGO t:zip_code=61101-1239 t:grant_end=30-Sep-13 t:grant_start=08-Dec-12 t:program_agency_fund_recipient="17th Judicial Circuit / Winnebago County" t:program_title_type="Technology Improvement" m:total_amount_of_program_funds=29881

series e:scd6-haif d:2014-03-20T11:25:04.000Z t:federal_program_or_state_fund_source_name="JUVENILE ACCOUNTABILITY INITIATIVE BLOCK GRANT" t:county_location_of_recipient="DU PAGE" t:zip_code=60187 t:grant_end=30-Jun-13 t:grant_start=01-Jul-12 t:program_agency_fund_recipient="18TH JUDICIAL CIRCUIT" t:program_title_type="Probation and Court Services" m:total_amount_of_program_funds=45000
```

## Meta Commands

```ls
metric m:total_amount_of_program_funds p:double l:"Total Amount of Program Funds" t:dataTypeName=money

entity e:scd6-haif l:"SFY13 Open Grants" t:attribution="Illinois Criminal Justice Information Authority" t:url=https://data.illinois.gov/api/views/scd6-haif

property e:scd6-haif t:meta.view v:id=scd6-haif v:category="Public Safety" v:attributionLink=http://www.icjia.state.il.us v:averageRating=0 v:name="SFY13 Open Grants" v:attribution="Illinois Criminal Justice Information Authority"

property e:scd6-haif t:meta.view.owner v:id=avuj-ix5c v:screenName="Jude Lemrow" v:displayName="Jude Lemrow"

property e:scd6-haif t:meta.view.tableauthor v:id=avuj-ix5c v:screenName="Jude Lemrow" v:roleName=publisher v:displayName="Jude Lemrow"
```

## Top Records

```ls
| :updated_at | program_agency_fund_recipient                | program_title_type           | county_location_of_recipient | zip_code   | federal_program_or_state_fund_source_name      | grant_start | grant_end | total_amount_of_program_funds | 
| =========== | ============================================ | ============================ | ============================ | ========== | ============================================== | =========== | ========= | ============================= | 
| 1395314704  | 17th Judicial Circuit / Winnebago County     | INFORMATION SYSTEMS          | WINNEBAGO                    | 61101-1239 | JUSTICE ASSISTANCE GRANT                       | 01-Oct-11   | 30-Sep-12 | 35541.00                      | 
| 1395314704  | 17th Judicial Circuit / Winnebago County     | Technology Improvement       | WINNEBAGO                    | 61101-1239 | JUSTICE ASSISTANCE GRANT                       | 08-Dec-12   | 30-Sep-13 | 29881.00                      | 
| 1395314704  | 18TH JUDICIAL CIRCUIT                        | Probation and Court Services | DU PAGE                      | 60187      | JUVENILE ACCOUNTABILITY INITIATIVE BLOCK GRANT | 01-Jul-12   | 30-Jun-13 | 45000.00                      | 
| 1395314704  | 2nd Judicial Circuit Court Services          | Adult Redeploy Illinois      | FRANKLIN                     | 62812      | Adult Redeploy Illinois                        | 07-Feb-13   | 30-Sep-13 | 108463.00                     | 
| 1395314704  | 2ND JUDICIAL CIRCUIT PROBATION               | INFORMATION SHARING PROGRAM  | FRANKLIN                     | 62812      | JUVENILE ACCOUNTABILITY INITIATIVE BLOCK GRANT | 27-Jun-12   | 02-Dec-12 | 84826.00                      | 
| 1395314704  | 4th Judicial Circuit                         | Adult Redeploy Illinois      | Montgomery                   | 62471      | Adult Redeploy Illinois                        | 01-Feb-13   | 31-May-13 | 21500.00                      | 
| 1395314704  | 4th Judicial Circuit                         | Adult Redeploy Illinois      | Effingham                    | 62471      | Adult Redeploy Illinois                        | 17-Jun-13   | 30-Jun-14 | 152000.00                     | 
| 1395314704  | ADMINISTRATIVE OFFICE OF THE ILLINOIS COURTS | Security Equipment           | STATEWIDE                    | 60601      | JUSTICE ASSISTANCE GRANTS / SUPPLEMENTAL AWARD | 15-Jun-12   | 31-Dec-12 | 45020.00                      | 
| 1395314704  | ADMINISTRATIVE OFFICE OF THE ILLINOIS COURTS | Security Equipment           | STATEWIDE                    | 60601      | JUSTICE ASSISTANCE GRANT                       | 15-Jun-12   | 31-Dec-12 | 17077.00                      | 
| 1395314704  | ADV & SAS                                    | Illinois Health Cares        | LA SALLE                     | 61364      | Fund 184 Violence Prevention Grants (Legacy)   | 01-Jun-13   | 30-Jun-14 | 36900.00                      | 
```