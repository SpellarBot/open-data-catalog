# San Francisco Arts Commission Grants FY2004-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-arts-commission-grants-fy2004-2014) |
| Metadata | [Link](https://data.sfgov.org/api/views/mxvq-mfs5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/mxvq-mfs5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/mxvq-mfs5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | mxvq-mfs5 |
| Name | San Francisco Arts Commission Grants FY2004-2016 |
| Attribution | San Francisco Arts Commission |
| Category | Culture and Recreation |
| Tags | art, arts, grants, culture, artists, arts organizations, cultural center, cultural centers, arts funding, grant funding, arts commission, sfac, artist |
| Created | 2015-09-02T17:26:49Z |
| Publication Date | 2017-01-26T01:04:07Z |

## Description

Grants made by the San Francisco Arts Commission (SFAC) to individual artists, arts organizations and Cultural Centers from the Cultural Equity Endowment fund between Fiscal Year 2004 and 2016. http://administrative.sanfranciscocode.org/68/

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                      | Data Type     | Render Type   |
| ======== | ============== | ======================================== | ========================================= | ============= | ============= |
| Yes      | series tag     | name_of_applicant                        | Name of Applicant                         | text          | text          |
| Yes      | series tag     | grant_category                           | Grant Category                            | text          | text          |
| Yes      | numeric metric | grant_amount                             | Grant Amount                              | money         | money         |
| Yes      | time           | grant_fiscal_year                        | Grant Fiscal Year                         | calendar_date | calendar_date |
| Yes      | series tag     | community_focus                          | Community Focus Combined                  | text          | text          |
| Yes      | series tag     | community_focus_african_american         | Community Focus: African American         | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_asian_american           | Community Focus: Asian American           | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_disabled                 | Community Focus: Disabled                 | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_immigrant                | Community Focus: Immigrant                | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_l_g_b_t_q                | Community Focus: L/G/B/T/Q                | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_latino_american          | Community Focus: Latino American          | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_multiple_people_of_color | Community Focus: Multiple People of Color | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_native                   | Community Focus: Native                   | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_native_american          | Community Focus: Native American          | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_pacific_islander         | Community Focus: Pacific Islander         | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_transgender              | Community Focus: Transgender              | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_women                    | Community Focus: Women                    | checkbox      | checkbox      |
| Yes      | series tag     | community_focus_no_specified_focus       | Community Focus: No specified focus       | checkbox      | checkbox      |
```

## Time Field

```ls
Value = grant_fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:mxvq-mfs5 d:2004-01-01T00:00:00.000Z t:community_focus_multiple_people_of_color=false t:community_focus="African American" t:community_focus_native_american=false t:community_focus_pacific_islander=false t:community_focus_native=false t:community_focus_disabled=false t:community_focus_latino_american=false t:community_focus_l_g_b_t_q=false t:community_focus_asian_american=false t:community_focus_transgender=false t:grant_category="Cultural Center" t:community_focus_african_american=true t:name_of_applicant="African American Art & Culture Complex" t:community_focus_immigrant=false t:community_focus_no_specified_focus=false m:grant_amount=307055

series e:mxvq-mfs5 d:2004-01-01T00:00:00.000Z t:community_focus_multiple_people_of_color=false t:community_focus="African American" t:community_focus_native_american=false t:community_focus_pacific_islander=false t:community_focus_native=false t:community_focus_disabled=false t:community_focus_latino_american=false t:community_focus_l_g_b_t_q=false t:community_focus_asian_american=false t:community_focus_transgender=false t:grant_category="Organization Project Grant (OPG)" t:community_focus_african_american=true t:name_of_applicant="AfroSolo Theatre Company" t:community_focus_immigrant=false t:community_focus_no_specified_focus=false m:grant_amount=11250

series e:mxvq-mfs5 d:2004-01-01T00:00:00.000Z t:community_focus_multiple_people_of_color=false t:community_focus="African American" t:community_focus_native_american=false t:community_focus_pacific_islander=false t:community_focus_native=false t:community_focus_disabled=false t:community_focus_latino_american=false t:community_focus_l_g_b_t_q=false t:community_focus_asian_american=false t:community_focus_transgender=false t:grant_category="Cultural Center" t:community_focus_african_american=true t:name_of_applicant="Bayview Opera House Ruth Williams Memorial Theater" t:community_focus_immigrant=false t:community_focus_no_specified_focus=false m:grant_amount=234825
```

## Meta Commands

```ls
metric m:grant_amount p:double l:"Grant Amount" d:"The monetary amount awarded" t:dataTypeName=money

entity e:mxvq-mfs5 l:"San Francisco Arts Commission Grants FY2004-2016" t:attribution="San Francisco Arts Commission" t:url=https://data.sfgov.org/api/views/mxvq-mfs5

property e:mxvq-mfs5 t:meta.view v:id=mxvq-mfs5 v:category="Culture and Recreation" v:attributionLink=http://www.sfartscommission.org/ v:averageRating=0 v:name="San Francisco Arts Commission Grants FY2004-2016" v:attribution="San Francisco Arts Commission"

property e:mxvq-mfs5 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:mxvq-mfs5 t:meta.view.owner v:id=et45-cce5 v:screenName=anhthang.dao-shah v:displayName=anhthang.dao-shah

property e:mxvq-mfs5 t:meta.view.tableauthor v:id=et45-cce5 v:screenName=anhthang.dao-shah v:roleName=editor v:displayName=anhthang.dao-shah
```

## Top Records

```ls
| name_of_applicant                                  | grant_category                              | grant_amount | grant_fiscal_year   | community_focus        | community_focus_african_american | community_focus_asian_american | community_focus_disabled | community_focus_immigrant | community_focus_l_g_b_t_q | community_focus_latino_american | community_focus_multiple_people_of_color | community_focus_native | community_focus_native_american | community_focus_pacific_islander | community_focus_transgender | community_focus_women | community_focus_no_specified_focus | 
| ================================================== | =========================================== | ============ | =================== | ====================== | ================================ | ============================== | ======================== | ========================= | ========================= | =============================== | ======================================== | ====================== | =============================== | ================================ | =========================== | ===================== | ================================== | 
| African American Art & Culture Complex             | Cultural Center                             | 307055.00    | 2004-01-01T00:00:00 | African American       | true                             | false                          | false                    | false                     | false                     | false                           | false                                    | false                  | false                           | false                            | false                       |                       | false                              | 
| AfroSolo Theatre Company                           | Organization Project Grant (OPG)            | 11250.00     | 2004-01-01T00:00:00 | African American       | true                             | false                          | false                    | false                     | false                     | false                           | false                                    | false                  | false                           | false                            | false                       |                       | false                              | 
| Bayview Opera House Ruth Williams Memorial Theater | Cultural Center                             | 234825.00    | 2004-01-01T00:00:00 | African American       | true                             | false                          | false                    | false                     | false                     | false                           | false                                    | false                  | false                           | false                            | false                       |                       | false                              | 
| Blues and R&B Music Foundation                     | Special Project Grants (SPG)                | 1000.00      | 2004-01-01T00:00:00 | African American       | true                             | false                          | false                    | false                     | false                     | false                           | false                                    | false                  | false                           | false                            | false                       |                       | false                              | 
| Robert Moses? Kin                                  | Cultural Equity Initiative-Level 1 (CEI_L1) | 18000.00     | 2004-01-01T00:00:00 | African American       | true                             | false                          | false                    | false                     | false                     | false                           | false                                    | false                  | false                           | false                            | false                       |                       | false                              | 
| San Francisco Black Film Festival                  | Cultural Equity Initiative-Level 1 (CEI_L1) | 18000.00     | 2004-01-01T00:00:00 | African American       | true                             | false                          | false                    | false                     | false                     | false                           | false                                    | false                  | false                           | false                            | false                       |                       | false                              | 
| ZACCHO Dance Theatre                               | Organization Project Grant (OPG)            | 15000.00     | 2004-01-01T00:00:00 | African American       | true                             | false                          | false                    | false                     | false                     | false                           | false                                    | false                  | false                           | false                            | false                       |                       | false                              | 
| Rhodessa Jones                                     | Individual Artist Commission (IAC)          | 10000.00     | 2004-01-01T00:00:00 | African American Women | true                             | false                          | false                    | false                     | false                     | false                           | false                                    | false                  | false                           | false                            | true                        |                       | false                              | 
| Shanique Scott-T Scott-Tyehimba                    | Individual Artist Commission (IAC)          | 10000.00     | 2004-01-01T00:00:00 | African American Women | true                             | false                          | false                    | false                     | false                     | false                           | false                                    | false                  | false                           | false                            | true                        |                       | false                              | 
| 3rd i South Asian Independent Film Festival        | Organization Project Grant (OPG)            | 12500.00     | 2004-01-01T00:00:00 | Asian American         | false                            | true                           | false                    | false                     | false                     | false                           | false                                    | false                  | false                           | false                            | false                       |                       | false                              | 
```