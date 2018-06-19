# State University Construction Fund (SUCF) Advertised Procurements: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-university-construction-fund-sucf-advertised-procurements-beginning-2000) |
| Metadata | [Link](https://data.ny.gov/api/views/vtxv-3j2b) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vtxv-3j2b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vtxv-3j2b/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vtxv-3j2b |
| Name | State University Construction Fund (SUCF) Advertised Procurements: Beginning 2000 |
| Attribution | State University Construction Fund |
| Category | Education |
| Tags | state university construction fund, sucf, construction, contract, education, capital, suny |
| Created | 2014-01-23T19:15:54Z |
| Publication Date | 2017-04-17T10:06:39Z |

## Description

Listing of all design procurements advertised

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | =========== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag  | project                  | Project                  | text          | text          |
| Yes      | series tag  | campus_name              | Campus Name              | text          | text          |
| Yes      | series tag  | project_title            | Project Title            | text          | text          |
| Yes      | time        | contract_advertise_date  | Contract Advertise Date  | calendar_date | calendar_date |
| Yes      | series tag  | estimated_contract_value | Estimated Contract Value | text          | text          |
| No       |             | proposal_due_date        | Proposal Due Date        | calendar_date | calendar_date |
| Yes      | series tag  | still_accepting_soq      | Still Accepting SOQ      | text          | text          |
```

## Time Field

```ls
Value = contract_advertise_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = proposal_due_date
```

## Data Commands

```ls
series e:vtxv-3j2b d:2015-09-11T00:00:00.000Z t:estimated_contract_value="$10,000,000 - Up" t:project=011006-00 t:project_title="Upgrade Central Plant - SUCF" t:campus_name="State University of New York at Albany" t:still_accepting_soq=N m:row_number.vtxv-3j2b=1

series e:vtxv-3j2b d:2015-10-19T00:00:00.000Z t:estimated_contract_value="$5,000,000 - $10,000,000" t:project=011008-00 t:project_title="Rehab Toilet Rooms for ADA - Podium" t:campus_name="State University of New York at Albany" t:still_accepting_soq=N m:row_number.vtxv-3j2b=2

series e:vtxv-3j2b d:2016-03-07T00:00:00.000Z t:estimated_contract_value="$500,000 - $1,000,000" t:project=011009-00 t:project_title="Upgrade Controls Study/Pilot Campus Wide" t:campus_name="State University of New York at Albany" t:still_accepting_soq=N m:row_number.vtxv-3j2b=3
```

## Meta Commands

```ls
metric m:row_number.vtxv-3j2b p:long l:"Row Number"

entity e:vtxv-3j2b l:"State University Construction Fund (SUCF) Advertised Procurements: Beginning 2000" t:attribution="State University Construction Fund" t:url=https://data.ny.gov/api/views/vtxv-3j2b

property e:vtxv-3j2b t:meta.view v:id=vtxv-3j2b v:category=Education v:attributionLink=http://sucf.suny.edu v:averageRating=0 v:name="State University Construction Fund (SUCF) Advertised Procurements: Beginning 2000" v:attribution="State University Construction Fund"

property e:vtxv-3j2b t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vtxv-3j2b t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:vtxv-3j2b t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| project   | campus_name                            | project_title                                                               | contract_advertise_date | estimated_contract_value | proposal_due_date   | still_accepting_soq | 
| ========= | ====================================== | =========================================================================== | ======================= | ======================== | =================== | =================== | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF                                                | 2015-09-11T00:00:00     | $10,000,000 - Up         | 2015-10-05T00:00:00 | N                   | 
| 011008-00 | State University of New York at Albany | Rehab Toilet Rooms for ADA - Podium                                         | 2015-10-19T00:00:00     | $5,000,000 - $10,000,000 | 2015-11-10T00:00:00 | N                   | 
| 011009-00 | State University of New York at Albany | Upgrade Controls Study/Pilot Campus Wide                                    | 2016-03-07T00:00:00     | $500,000 - $1,000,000    | 2016-03-30T00:00:00 | N                   | 
| 01X834-00 | State University of New York at Albany | Site Utilities Study Sanitary Sewer, Water, Storm Water And Irrigation Syst | 2006-04-24T00:00:00     | $500,000 - $1,000,000    | 2006-05-15T00:00:00 | N                   | 
| 01X842-00 | State University of New York at Albany | Program Study - Renovate Page Hall                                          | 2008-09-18T00:00:00     | $250,000 - $500,000      | 2008-10-13T00:00:00 | N                   | 
| 01X844-00 | State University of New York at Albany | Facilities Master Plan - Albany                                             | 2009-09-11T00:00:00     | $1,000,000 - $2,500,000  | 2009-10-05T00:00:00 | N                   | 
| 01XA40-00 | State University of New York at Albany | Install Podium Sky Light Domes                                              | 2008-01-04T00:00:00     | $5,000,000 - $10,000,000 | 2008-01-28T00:00:00 | N                   | 
| 01XA41-00 | State University of New York at Albany | Campus Storm Water Pond Improvements                                        | 2008-04-10T00:00:00     | $1,000,000 - $2,500,000  | 2008-05-05T00:00:00 | N                   | 
| 01XA47-00 | State University of New York at Albany | Renovate Health Center                                                      | 2012-06-29T00:00:00     | $250,000 - $500,000      | 2012-07-23T00:00:00 | N                   | 
| 01XA49-00 | State University of New York at Albany | Relocate University Data Center                                             | 2008-07-30T00:00:00     | $10,000,000 - Up         | 2008-08-25T00:00:00 | N                   | 
```