# March 2014 Open

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/march-2014-open-7f78b) |
| Metadata | [Link](https://data.illinois.gov/api/views/8vxd-vi2h) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8vxd-vi2h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8vxd-vi2h/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8vxd-vi2h |
| Name | March 2014 Open |
| Attribution | Illinois Criminal Justice Information Authority |
| Category | Public Safety |
| Tags | grants, open grants, icjia, criminal justice, criminal, justice, criminal justice authority, criminal justice information authority, illinois criminal justice information authority |
| Created | 2014-03-19T18:32:09Z |
| Publication Date | 2014-03-19T18:37:53Z |

## Description

This is a listing of all grants administered by the ICJIA that were open on March 19, 2014.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type     | Render Type   |
| ======== | ============== | ========================================= | ========================================= | ============= | ============= |
| Yes      | series tag     | program_agency_fund_recipient             | Program Agency / Fund Recipient           | text          | text          |
| Yes      | series tag     | program_title_type                        | Program Title / Type                      | text          | text          |
| Yes      | series tag     | county_location_of_recipient              | County (location of recipient)            | text          | text          |
| Yes      | series tag     | zip_code                                  | Zip Code                                  | text          | text          |
| Yes      | series tag     | federal_program_or_state_fund_source_name | Federal Program or State Fund Source Name | text          | text          |
| Yes      | time           | grant_start                               | Grant Start                               | calendar_date | calendar_date |
| No       |                | grant_end                                 | Grant End                                 | calendar_date | calendar_date |
| Yes      | numeric metric | total_amount_of_program_funds             | Total Amount of Program Funds             | money         | money         |
```

## Time Field

```ls
Value = grant_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = grant_end
```

## Data Commands

```ls
series e:8vxd-vi2h d:2013-09-01T00:00:00.000Z t:federal_program_or_state_fund_source_name="Adult Redeploy Illinois" t:county_location_of_recipient=Franklin t:zip_code=62454 t:program_agency_fund_recipient="2nd Judicial Circuit" t:program_title_type="Adult Redeploy Illinois" m:total_amount_of_program_funds=352207

series e:8vxd-vi2h d:2013-06-17T00:00:00.000Z t:federal_program_or_state_fund_source_name="Adult Redeploy Illinois" t:county_location_of_recipient=Effingham t:zip_code=62471 t:program_agency_fund_recipient="4th Judicial Circuit" t:program_title_type="Adult Redeploy Illinois" m:total_amount_of_program_funds=152000

series e:8vxd-vi2h d:2013-07-01T00:00:00.000Z t:federal_program_or_state_fund_source_name="Adult Redeploy Illinois" t:county_location_of_recipient=McDONOUGH t:zip_code=61455 t:program_agency_fund_recipient="9th JUDICIAL CIRCUIT" t:program_title_type="Adult Redeploy Illinois" m:total_amount_of_program_funds=490783.78
```

## Meta Commands

```ls
metric m:total_amount_of_program_funds p:double l:"Total Amount of Program Funds" t:dataTypeName=money

entity e:8vxd-vi2h l:"March 2014 Open" t:attribution="Illinois Criminal Justice Information Authority" t:url=https://data.illinois.gov/api/views/8vxd-vi2h

property e:8vxd-vi2h t:meta.view v:id=8vxd-vi2h v:category="Public Safety" v:attributionLink=http://www.icjia.state.il.us v:averageRating=0 v:name="March 2014 Open" v:attribution="Illinois Criminal Justice Information Authority"

property e:8vxd-vi2h t:meta.view.owner v:id=avuj-ix5c v:screenName="Jude Lemrow" v:displayName="Jude Lemrow"

property e:8vxd-vi2h t:meta.view.tableauthor v:id=avuj-ix5c v:screenName="Jude Lemrow" v:roleName=publisher v:displayName="Jude Lemrow"
```

## Top Records

```ls
| program_agency_fund_recipient                        | program_title_type                              | county_location_of_recipient | zip_code   | federal_program_or_state_fund_source_name    | grant_start         | grant_end           | total_amount_of_program_funds | 
| ==================================================== | =============================================== | ============================ | ========== | ============================================ | =================== | =================== | ============================= | 
| 2nd Judicial Circuit                                 | Adult Redeploy Illinois                         | Franklin                     | 62454      | Adult Redeploy Illinois                      | 2013-09-01T00:00:00 | 2014-06-30T00:00:00 | 352207.00                     | 
| 4th Judicial Circuit                                 | Adult Redeploy Illinois                         | Effingham                    | 62471      | Adult Redeploy Illinois                      | 2013-06-17T00:00:00 | 2014-06-30T00:00:00 | 152000.00                     | 
| 9th JUDICIAL CIRCUIT                                 | Adult Redeploy Illinois                         | McDONOUGH                    | 61455      | Adult Redeploy Illinois                      | 2013-07-01T00:00:00 | 2014-06-30T00:00:00 | 490783.78                     | 
| ADV & SAS                                            | Illinois Health Cares                           | LA SALLE                     | 61364      | Fund 184 Violence Prevention Grants (Legacy) | 2013-06-01T00:00:00 | 2014-06-30T00:00:00 | 36900.00                      | 
| Albany Park Community Center                         | Illinois Community Violence Prevention Programs | Cook                         | 60625-5248 | Violence Prevention Programs                 | 2012-11-01T00:00:00 | 2013-10-31T00:00:00 | 361163.00                     | 
| All Our Children's Advocacy Center                   | CHILD ADVOCACY CENTER SERVICES (VOCA)           | Cook                         | 60558-1162 | VICTIMS OF CRIME ACT                         | 2013-03-01T00:00:00 | 2014-02-28T00:00:00 | 75342.00                      | 
| ALLIANCE AGAINST INTOXICATED MOTORISTS               | STATEWIDE SERVICES TO VICTIMS OF DRUNK DRIVERS  | Cook                         | 60173-4787 | VICTIMS OF CRIME ACT                         | 2013-10-01T00:00:00 | 2014-09-30T00:00:00 | 78934.00                      | 
| Alliance for the Mentally Ill of Greater Chicago     | Crisis Intervention Team (CIT)                  | Cook                         | 60642      | JUSTICE ASSISTANCE GRANT                     | 2013-10-01T00:00:00 | 2014-09-30T00:00:00 | 97038.00                      | 
| AMY SCHULTZ CHILD ADVOCACY CENTER                    | CHILD ADVOCACY CENTER SERVICES (VOCA)           | Jefferson                    | 62864-5046 | VICTIMS OF CRIME ACT                         | 2013-10-01T00:00:00 | 2014-09-30T00:00:00 | 32239.00                      | 
| Ann & Robert H. Lurie Children's Hospital of Chicago | SERVICES TO VICTIMS OF CHILD ABUSE              | Cook                         | 60611-2605 | VICTIMS OF CRIME ACT                         | 2013-10-01T00:00:00 | 2014-09-30T00:00:00 | 52479.00                      | 
```