# Cultural Affairs - Performance Metrics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cultural-affairs-performance-metrics-92019) |
| Metadata | [Link](https://data.lacity.org/api/views/e3gp-gx53) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/e3gp-gx53/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/e3gp-gx53/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | e3gp-gx53 |
| Name | Cultural Affairs - Performance Metrics |
| Attribution | Department of Cultural Affairs |
| Category | A Livable and Sustainable City |
| Tags | cultural affairs, dca |
| Created | 2014-08-26T17:13:03Z |
| Publication Date | 2014-08-26T17:18:55Z |

## Description

This dataset contains metrics that measure the operational performance of the Department of Cultural Affairs. These metrics are used on a regular basis by the department and the Mayor to evaluate progress and inform decision making.  Performance management forms the foundation of a data-driven culture of innovation and excellence in the City of Los Angeles.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                       | Name                                                                                                                      | Data Type     | Render Type   |
| ======== | ============== | ================================================================================================================ | ========================================================================================================================= | ============= | ============= |
| Yes      | time           | date_value                                                                                                       | Date Value                                                                                                                | calendar_date | calendar_date |
| Yes      | series tag     | month_year                                                                                                       | Month-Year                                                                                                                | text          | text          |
| No       |                | quarter_fy                                                                                                       | Quarter-FY                                                                                                                | text          | text          |
| Yes      | series tag     | annual_fy                                                                                                        | Annual-FY                                                                                                                 | text          | text          |
| Yes      | numeric metric | of_audience_members_visitors_and_participants_for_dca_managed_community_arts_programs_annually_fy                | # of audience members, visitors and participants for DCA-managed Community Arts programs (Annually FY)                    | number        | number        |
| Yes      | numeric metric | projected_of_audience_members_visitors_and_participants_for_dca_managed_community_arts_programs_annually_fy      | PROJECTED: # of audience members, visitors and participants for DCA-managed Community Arts programs (Annually FY)         | number        | number        |
| Yes      | numeric metric | dollar_value_of_grants_and_corporate_donations_raised_annually_fy                                                | Dollar Value of Grants and Corporate Donations Raised (Annually FY)                                                       | money         | money         |
| Yes      | numeric metric | projected_dollar_value_of_grants_and_corporate_donations_raised_annually_fy                                      | PROJECTED: Dollar Value of Grants and Corporate Donations Raised (Annually FY)                                            | money         | money         |
| Yes      | numeric metric | of_for_public_art_projects_completed_in_tandem_with_delivery_of_associated_capital_project_annually_fy           | % of "% for Public Art" Projects Completed in tandem with delivery of associated capital project (Annually FY)            | percent       | percent       |
| Yes      | numeric metric | projected_of_for_public_art_projects_completed_in_tandem_with_delivery_of_associated_capital_project_annually_fy | PROJECTED: % of "% for Public Art" Projects Completed in tandem with delivery of associated capital project (Annually FY) | percent       | percent       |
| Yes      | numeric metric | of_participants_and_audience_members_at_dca_grant_supported_programs_annually_fy                                 | # of participants and audience members at DCA grant-supported programs (Annually FY)                                      | number        | number        |
| Yes      | numeric metric | projected_of_participants_and_audience_members_at_dca_grant_supported_programs_annually_fy                       | PROJECTED: # of participants and audience members at DCA grant-supported programs (Annually FY)                           | number        | number        |
```

## Time Field

```ls
Value = date_value
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter_fy
```

## Data Commands

```ls
series e:e3gp-gx53 d:2012-06-30T00:00:00.000Z t:annual_fy="FY 2012" t:month_year=Jun-12 m:of_for_public_art_projects_completed_in_tandem_with_delivery_of_associated_capital_project_annually_fy=100 m:of_participants_and_audience_members_at_dca_grant_supported_programs_annually_fy=2899459 m:of_audience_members_visitors_and_participants_for_dca_managed_community_arts_programs_annually_fy=196125 m:dollar_value_of_grants_and_corporate_donations_raised_annually_fy=2008259

series e:e3gp-gx53 d:2013-06-30T00:00:00.000Z t:annual_fy="FY 2013" t:month_year=Jun-13 m:of_for_public_art_projects_completed_in_tandem_with_delivery_of_associated_capital_project_annually_fy=100 m:of_participants_and_audience_members_at_dca_grant_supported_programs_annually_fy=3036723 m:of_audience_members_visitors_and_participants_for_dca_managed_community_arts_programs_annually_fy=212564 m:dollar_value_of_grants_and_corporate_donations_raised_annually_fy=2634418

series e:e3gp-gx53 d:2014-06-30T00:00:00.000Z t:annual_fy="FY 2014" t:month_year=Jun-14 m:of_for_public_art_projects_completed_in_tandem_with_delivery_of_associated_capital_project_annually_fy=91 m:projected_of_audience_members_visitors_and_participants_for_dca_managed_community_arts_programs_annually_fy=220000 m:projected_of_participants_and_audience_members_at_dca_grant_supported_programs_annually_fy=3100000 m:dollar_value_of_grants_and_corporate_donations_raised_annually_fy=819432 m:projected_dollar_value_of_grants_and_corporate_donations_raised_annually_fy=645181 m:projected_of_for_public_art_projects_completed_in_tandem_with_delivery_of_associated_capital_project_annually_fy=91
```

## Meta Commands

```ls
metric m:of_audience_members_visitors_and_participants_for_dca_managed_community_arts_programs_annually_fy p:integer l:"# of audience members, visitors and participants for DCA-managed Community Arts programs (Annually FY)" t:dataTypeName=number

metric m:projected_of_audience_members_visitors_and_participants_for_dca_managed_community_arts_programs_annually_fy p:integer l:"PROJECTED: # of audience members, visitors and participants for DCA-managed Community Arts programs (Annually FY)" t:dataTypeName=number

metric m:dollar_value_of_grants_and_corporate_donations_raised_annually_fy p:integer l:"Dollar Value of Grants and Corporate Donations Raised (Annually FY)" t:dataTypeName=money

metric m:projected_dollar_value_of_grants_and_corporate_donations_raised_annually_fy p:integer l:"PROJECTED: Dollar Value of Grants and Corporate Donations Raised (Annually FY)" t:dataTypeName=money

metric m:of_for_public_art_projects_completed_in_tandem_with_delivery_of_associated_capital_project_annually_fy p:integer l:"% of ""% for Public Art"" Projects Completed in tandem with delivery of associated capital project (Annually FY)" t:dataTypeName=percent

metric m:projected_of_for_public_art_projects_completed_in_tandem_with_delivery_of_associated_capital_project_annually_fy p:integer l:"PROJECTED: % of ""% for Public Art"" Projects Completed in tandem with delivery of associated capital project (Annually FY)" t:dataTypeName=percent

metric m:of_participants_and_audience_members_at_dca_grant_supported_programs_annually_fy p:integer l:"# of participants and audience members at DCA grant-supported programs (Annually FY)" t:dataTypeName=number

metric m:projected_of_participants_and_audience_members_at_dca_grant_supported_programs_annually_fy p:integer l:"PROJECTED: # of participants and audience members at DCA grant-supported programs (Annually FY)" t:dataTypeName=number

entity e:e3gp-gx53 l:"Cultural Affairs - Performance Metrics" t:attribution="Department of Cultural Affairs" t:url=https://data.lacity.org/api/views/e3gp-gx53

property e:e3gp-gx53 t:meta.view v:id=e3gp-gx53 v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Cultural Affairs - Performance Metrics" v:attribution="Department of Cultural Affairs"

property e:e3gp-gx53 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:e3gp-gx53 t:meta.view.owner v:id=tyhz-nfmm v:screenName="Miguel Sangalang" v:displayName="Miguel Sangalang"

property e:e3gp-gx53 t:meta.view.tableauthor v:id=tyhz-nfmm v:screenName="Miguel Sangalang" v:roleName=publisher v:displayName="Miguel Sangalang"
```

## Top Records

```ls
| date_value          | month_year | quarter_fy | annual_fy | of_audience_members_visitors_and_participants_for_dca_managed_community_arts_programs_annually_fy | projected_of_audience_members_visitors_and_participants_for_dca_managed_community_arts_programs_annually_fy | dollar_value_of_grants_and_corporate_donations_raised_annually_fy | projected_dollar_value_of_grants_and_corporate_donations_raised_annually_fy | of_for_public_art_projects_completed_in_tandem_with_delivery_of_associated_capital_project_annually_fy | projected_of_for_public_art_projects_completed_in_tandem_with_delivery_of_associated_capital_project_annually_fy | of_participants_and_audience_members_at_dca_grant_supported_programs_annually_fy | projected_of_participants_and_audience_members_at_dca_grant_supported_programs_annually_fy | 
| =================== | ========== | ========== | ========= | ================================================================================================= | =========================================================================================================== | ================================================================= | =========================================================================== | ====================================================================================================== | ================================================================================================================ | ================================================================================ | ========================================================================================== | 
| 2010-06-30T00:00:00 | Jun-10     | Q4 FY10    | FY 2010   |                                                                                                   |                                                                                                             |                                                                   |                                                                             |                                                                                                        |                                                                                                                  |                                                                                  |                                                                                            | 
| 2011-06-30T00:00:00 | Jun-11     | Q4 FY11    | FY 2011   |                                                                                                   |                                                                                                             |                                                                   |                                                                             |                                                                                                        |                                                                                                                  |                                                                                  |                                                                                            | 
| 2012-06-30T00:00:00 | Jun-12     | Q4 FY12    | FY 2012   | 196125                                                                                            |                                                                                                             | 2008259                                                           |                                                                             | 100                                                                                                    |                                                                                                                  | 2899459                                                                          |                                                                                            | 
| 2012-07-31T00:00:00 | Jul-12     |            |           |                                                                                                   |                                                                                                             |                                                                   |                                                                             |                                                                                                        |                                                                                                                  |                                                                                  |                                                                                            | 
| 2012-08-31T00:00:00 | Aug-12     |            |           |                                                                                                   |                                                                                                             |                                                                   |                                                                             |                                                                                                        |                                                                                                                  |                                                                                  |                                                                                            | 
| 2012-09-30T00:00:00 | Sep-12     | Q1 FY13    |           |                                                                                                   |                                                                                                             |                                                                   |                                                                             |                                                                                                        |                                                                                                                  |                                                                                  |                                                                                            | 
| 2012-10-31T00:00:00 | Oct-12     |            |           |                                                                                                   |                                                                                                             |                                                                   |                                                                             |                                                                                                        |                                                                                                                  |                                                                                  |                                                                                            | 
| 2012-11-30T00:00:00 | Nov-12     |            |           |                                                                                                   |                                                                                                             |                                                                   |                                                                             |                                                                                                        |                                                                                                                  |                                                                                  |                                                                                            | 
| 2012-12-31T00:00:00 | Dec-12     | Q2 FY13    |           |                                                                                                   |                                                                                                             |                                                                   |                                                                             |                                                                                                        |                                                                                                                  |                                                                                  |                                                                                            | 
| 2013-01-31T00:00:00 | Jan-13     |            |           |                                                                                                   |                                                                                                             |                                                                   |                                                                             |                                                                                                        |                                                                                                                  |                                                                                  |                                                                                            | 
```