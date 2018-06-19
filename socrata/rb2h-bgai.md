# DCLA Cultural Organization Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dcla-cultural-organization-resources-98f4c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rb2h-bgai) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rb2h-bgai/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rb2h-bgai/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rb2h-bgai |
| Name | DCLA Cultural Organization Resources |
| Attribution | Department of Cultural Affairs (DCLA) |
| Category | Recreation |
| Tags | dcla, culture, cultural affairs, resources, directory, listing |
| Created | 2011-10-27T20:49:20Z |
| Publication Date | 2013-06-21T19:41:09Z |

## Description

A list of organizations that provide services and/or information useful to artists and cultural organizations

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | area         | Area         | text      | text        |
| Yes      | series tag  | organization | Organization | text      | text        |
| Yes      | series tag  | description  | Description  | text      | text        |
| Yes      | series tag  | website      | Website      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rb2h-bgai d:2011-10-27T13:49:22.000Z t:organization="Alliance for the Arts" t:area=Advocacy t:website=www.allianceforarts.org m:row_number.rb2h-bgai=1

series e:rb2h-bgai d:2011-10-27T13:49:22.000Z t:organization="American Association of Museums" t:area=Advocacy t:website=www.aam-us.org m:row_number.rb2h-bgai=2

series e:rb2h-bgai d:2011-10-27T13:49:22.000Z t:organization="Americans for the Arts" t:area=Advocacy t:website=www.americansforthearts.org m:row_number.rb2h-bgai=3
```

## Meta Commands

```ls
metric m:row_number.rb2h-bgai p:long l:"Row Number"

entity e:rb2h-bgai l:"DCLA Cultural Organization Resources" t:attribution="Department of Cultural Affairs (DCLA)" t:url=https://data.cityofnewyork.us/api/views/rb2h-bgai

property e:rb2h-bgai t:meta.view v:id=rb2h-bgai v:category=Recreation v:averageRating=0 v:name="DCLA Cultural Organization Resources" v:attribution="Department of Cultural Affairs (DCLA)"

property e:rb2h-bgai t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rb2h-bgai t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | area                      | organization                                           | description                                                                                                                                                                                    | website                     | 
| =========== | ========================= | ====================================================== | ============================================================================================================================================================================================== | =========================== | 
| 1319723362  | Advocacy                  | Alliance for the Arts                                  |                                                                                                                                                                                                | www.allianceforarts.org     | 
| 1319723362  | Advocacy                  | American Association of Museums                        |                                                                                                                                                                                                | www.aam-us.org              | 
| 1319723362  | Advocacy                  | Americans for the Arts                                 |                                                                                                                                                                                                | www.americansforthearts.org | 
| 1319723362  | Advocacy                  | Metropolitan Transportation Authority Arts for Transit |                                                                                                                                                                                                | www.mta.info/mta/aft        | 
| 1319723362  | Advocacy                  | National Alliance for Media Arts and Culture           |                                                                                                                                                                                                | www.namac.org               | 
| 1319723362  | Art Service Organizations | Actors Fund                                            | A human services organization for performing artists that provides health care access information, and programs and services for those in need, crisis or transition.                          | www.actorsfund.org/services | 
| 1319723362  | Art Service Organizations | Alliance of Resident Theatres/New York                 | A service and advocacy organization for the Off Broadway, non-profit theater community.                                                                                                        | www.art-newyork.org         | 
| 1319723362  | Art Service Organizations | Arts & Business Council of New York                    | Builds partnerships between arts organizations and businesses in the New York City community.                                                                                                  | www.artsandbusiness-ny.org  | 
| 1319723362  | Art Service Organizations | Bronx Council on the Arts                              | Serves Bronx artists and arts organizations by providing financial support, re-grant funding, information services, technical assistance, professional development, and community programming. | www.bronxarts.org           | 
| 1319723362  | Art Service Organizations | Brooklyn Arts Council                                  | Offers service and support to Brooklyn artists and arts organizations, including re-grant funding.                                                                                             | www.brooklynartscouncil.org | 
```