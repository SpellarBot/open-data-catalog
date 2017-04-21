# Small Grant Projects Funded by the Developmental Disabilities Planning Council: Beginning 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/small-grant-projects-funded-by-the-developmental-disabilities-planning-council-beginning-2) |
| Metadata | [Link](https://data.ny.gov/api/views/3rdq-5smg) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/3rdq-5smg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/3rdq-5smg/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 3rdq-5smg |
| Name | Small Grant Projects Funded by the Developmental Disabilities Planning Council: Beginning 2004 |
| Attribution | New York State Developmental Disabilities Planning Council |
| Category | Human Services |
| Tags | developmental disabilities, projects, grants |
| Created | 2014-02-28T19:49:01Z |
| Publication Date | 2015-12-14T16:31:17Z |

## Description

Dataset includes general information about every grants project funded by the NYDDPC from 2004 to present

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                       | Data Type     | Render Type   |
| ======== | ============== | ======================== | ========================== | ============= | ============= |
| Yes      | series tag     | project_title            | Project Title              | text          | text          |
| Yes      | time           | project_start_date       | Project Start Date         | calendar_date | calendar_date |
| No       |                | project_end_date         | Project End Date           | calendar_date | calendar_date |
| Yes      | numeric metric | grant_amount             | Grant Amount               | money         | money         |
| Yes      | series tag     | project_description      | Project Description        | text          | text          |
| Yes      | series tag     | grantee_name             | Grantee Name               | text          | text          |
| Yes      | series tag     | street_address           | Street Address             | text          | text          |
| Yes      | series tag     | city                     | City                       | text          | text          |
| Yes      | series tag     | state                    | State                      | text          | text          |
| Yes      | series tag     | zip_code                 | Zip Code                   | text          | number        |
| Yes      | series tag     | grantee_category         | Grantee Category           | text          | text          |
| Yes      | numeric metric | contract_duration_cycles | Contract Duration (Cycles) | number        | number        |
```

## Time Field

```ls
Value = project_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_end_date
```

## Data Commands

```ls
series e:3rdq-5smg d:2004-02-01T00:00:00.000Z t:zip_code=14620 t:project_title="Partners in Policymaking" t:state=NY t:grantee_name="The Advocacy Center" t:street_address="590 South Avenue" t:grantee_category="Advocacy Services" t:project_description="To conduct Partners in Policymaking training program in NYS" t:city=Rochester m:grant_amount=200000 m:contract_duration_cycles=5

series e:3rdq-5smg d:2004-06-01T00:00:00.000Z t:zip_code=13503 t:project_title="Nursing Home Transition" t:state=NY t:grantee_name="Resource Center for Independent Living" t:street_address="401-409 Columbia Street" t:grantee_category="Disability Services" t:project_description="Nursing Home Transition initiative" t:city=Utica m:grant_amount=15000 m:contract_duration_cycles=2

series e:3rdq-5smg d:2004-06-01T00:00:00.000Z t:zip_code=14608 t:project_title="Nursing Home Transition" t:state=NY t:grantee_name="Center for Disability Rights" t:street_address="412 State Street" t:grantee_category="Disability Services" t:project_description="Nursing Home Transition initiative" t:city=Rochester m:grant_amount=15000 m:contract_duration_cycles=2
```

## Meta Commands

```ls
metric m:grant_amount p:integer l:"Grant Amount" d:"Total dollar amount of grant" t:dataTypeName=money

metric m:contract_duration_cycles p:integer l:"Contract Duration (Cycles)" d:"Describes the number of grant-cycles covered by the project. A grant cycle may run 12, 15 or 18 months." t:dataTypeName=number

entity e:3rdq-5smg l:"Small Grant Projects Funded by the Developmental Disabilities Planning Council:  Beginning 2004" t:attribution="New York State Developmental Disabilities Planning Council" t:url=https://data.ny.gov/api/views/3rdq-5smg

property e:3rdq-5smg t:meta.view v:id=3rdq-5smg v:category="Human Services" v:attributionLink=http://ddpc.ny.gov v:averageRating=0 v:name="Small Grant Projects Funded by the Developmental Disabilities Planning Council:  Beginning 2004" v:attribution="New York State Developmental Disabilities Planning Council"

property e:3rdq-5smg t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:3rdq-5smg t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:3rdq-5smg t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| project_title                             | project_start_date  | project_end_date    | grant_amount | project_description                                                         | grantee_name                                                  | street_address          | city      | state | zip_code | grantee_category                    | contract_duration_cycles | 
| ========================================= | =================== | =================== | ============ | =========================================================================== | ============================================================= | ======================= | ========= | ===== | ======== | =================================== | ======================== | 
| Partners in Policymaking                  | 2004-02-01T00:00:00 | 2005-01-31T00:00:00 | 200000       | To conduct Partners in Policymaking training program in NYS                 | The Advocacy Center                                           | 590 South Avenue        | Rochester | NY    | 14620    | Advocacy Services                   | 5                        | 
| Nursing Home Transition                   | 2004-06-01T00:00:00 | 2005-05-31T00:00:00 | 15000        | Nursing Home Transition initiative                                          | Resource Center for Independent Living                        | 401-409 Columbia Street | Utica     | NY    | 13503    | Disability Services                 | 2                        | 
| Nursing Home Transition                   | 2004-06-01T00:00:00 | 2005-05-31T00:00:00 | 15000        | Nursing Home Transition initiative                                          | Center for Disability Rights                                  | 412 State Street        | Rochester | NY    | 14608    | Disability Services                 | 2                        | 
| Nursing Home Transition                   | 2004-06-01T00:00:00 | 2005-05-31T00:00:00 | 15000        | Nursing Home Transition initiative                                          | Center for Independence of the Disabled, NY (CIDNY)           | 841 Broadway, Suite 301 | New York  | NY    | 10003    | Disability Services                 | 2                        | 
| Nursing Home Transition                   | 2004-06-01T00:00:00 | 2005-05-31T00:00:00 | 15000        | Nursing Home Transition initiative                                          | Westchester Disabled On the Move                              | 984 North Broadway      | Yonkers   | NY    | 10701    | Disability Services                 | 2                        | 
| Family Resource Network Planning Summit   | 2004-07-01T00:00:00 | 2005-06-30T00:00:00 | 15000        | To conduct a Family Resource Network Planning Summit                        | Support Center for Non Profit Management                      | 42 Broadway, 20th Floor | New York  | NY    | 10004    | For Profit/Proprietary              | 1                        | 
| Positive Behavior Supports                | 2004-07-01T00:00:00 | 2005-06-30T00:00:00 | 230000       | Capacity development for school based teams on Positive Behavior Supports.  | Westchester Institute for Human Development                   | 326 Cedarwood Hall      | Valhalla  | NY    | 10595    | Not-for-Profit                      | 3                        | 
| 20th Anniversary Statewide FSS Conference | 2004-08-01T00:00:00 | 2005-07-31T00:00:00 | 27850        | 20th Anniversary Statewide Family Support Services Conference               | NYS Office for People with Developmental Disabilities (OPWDD) | 44 Holland Avenue       | Albany    | NY    | 12229    | Government Agency                   | 1                        | 
| Health Education Model for Adults with DD | 2004-08-01T00:00:00 | 2005-07-31T00:00:00 | 20000        | Develop a health education model for adults with developmental disabilities | ARC of Monroe                                                 | 1000 Elmwood Avenue     | Rochester | NY    | 14620    | Developmental Disabilities Services | 3                        | 
| Health Education Model for Adults with DD | 2004-08-01T00:00:00 | 2005-07-31T00:00:00 | 20000        | Develop a health education model for adults with developmental disabilities | Sinergia, Inc.                                                | 2082 Lexington Avenue   | New York  | NY    | 10035    | Developmental Disabilities Services | 3                        | 
```