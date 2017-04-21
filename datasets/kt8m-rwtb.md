# Iowa Arts Council Grants Fiscal Years 2015 and 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-arts-council-grants-fiscal-years-2015-and-2016) |
| Metadata | [Link](https://data.iowa.gov/api/views/kt8m-rwtb) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/kt8m-rwtb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/kt8m-rwtb/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | kt8m-rwtb |
| Name | Iowa Arts Council Grants Fiscal Years 2015 and 2016 |
| Attribution | Iowa Arts Council, Iowa Department of Cultural Affairs SalesForce Database |
| Category | Communities & People |
| Tags | arts & culture, arts, culture, grants |
| Created | 2015-10-13T14:42:49Z |
| Publication Date | 2016-10-14T20:04:07Z |

## Description

Grants given by the Iowa Arts Council for Fiscal Year 2015 (July 1, 2014- June 30, 2015) and Fiscal Year 2016 (July 1, 2015-June 30, 2016). beginning July 1, 2014.

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                        | Data Type | Render Type |
| ======== | ============== | =========================================== | =========================================== | ========= | =========== |
| Yes      | time           | fiscal_year                                 | Fiscal Year                                 | number    | number      |
| Yes      | series tag     | grants_grants_number                        | Grants: Grants Number                       | text      | text        |
| Yes      | series tag     | grant_type                                  | Grant Type                                  | text      | text        |
| Yes      | series tag     | grantee_name                                | Grantee Name                                | text      | text        |
| Yes      | series tag     | fiscal_sponsor                              | Fiscal Sponsor                              | text      | text        |
| Yes      | series tag     | project_title                               | Project Title                               | text      | text        |
| Yes      | series tag     | applicant_status                            | Applicant Status                            | text      | text        |
| Yes      | series tag     | applicant_institution_type                  | Applicant Institution Type                  | text      | text        |
| Yes      | series tag     | applicant_arts_discipline                   | Applicant Arts Discipline                   | text      | text        |
| Yes      | series tag     | type_of_activity_supported                  | Type of Activity Supported                  | text      | text        |
| Yes      | numeric metric | actual_individuals_benefitting_from_project | Actual Individuals Benefitting from Project | number    | number      |
| Yes      | numeric metric | number_of_ia_artists_engaged                | Number of IA Artists Engaged                | number    | number      |
| Yes      | numeric metric | number_of_non_ia_artists_engaged            | Number of Non-IA Artists Engaged            | number    | number      |
| Yes      | numeric metric | total_artists_engaged                       | Total Artists Engaged                       | number    | number      |
| Yes      | numeric metric | youth_engaged_in_person                     | Youth Engaged In-Person                     | number    | number      |
| Yes      | numeric metric | grant_award                                 | Grant Award                                 | money     | money       |
| Yes      | numeric metric | funding_returned                            | Funding Returned                            | money     | money       |
| Yes      | numeric metric | grant_amount_spent                          | Grant Amount Spent                          | money     | money       |
| Yes      | numeric metric | in_kind_match                               | In-Kind Match                               | money     | money       |
| Yes      | series tag     | congressional_district                      | Congressional District                      | text      | number      |
| Yes      | series tag     | senate_district                             | Senate District                             | text      | number      |
| Yes      | series tag     | house_district                              | House District                              | text      | number      |
| Yes      | numeric metric | cash_match                                  | Cash Match                                  | money     | money       |
| Yes      | series tag     | applicant_city                              | Applicant City                              | text      | text        |
| Yes      | series tag     | applicant_state                             | Applicant State                             | text      | text        |
| Yes      | series tag     | applicant_zip                               | Applicant Zip                               | text      | text        |
| Yes      | series tag     | county                                      | County                                      | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kt8m-rwtb d:2015-01-01T00:00:00.000Z t:applicant_institution_type="Elementary School" t:grant_type="Big Yellow School Bus Grant" t:applicant_zip=50801 t:fiscal_sponsor="Creston Community School District" t:applicant_state=Iowa t:senate_district=11 t:house_district=21 t:applicant_arts_discipline=Humanities t:congressional_district=5 t:applicant_city=Creston t:grants_grants_number=201507-225 t:project_title="BYSB Trip to Musical Theatre Performance" t:county=Union t:type_of_activity_supported=Concert/Performance/Reading t:grantee_name="Creston Elementary School" t:applicant_status="Government- Municipal" m:funding_returned=0 m:grant_award=200 m:total_artists_engaged=10 m:number_of_ia_artists_engaged=0 m:cash_match=0 m:youth_engaged_in_person=130 m:number_of_non_ia_artists_engaged=10 m:in_kind_match=0 m:actual_individuals_benefitting_from_project=145 m:grant_amount_spent=200

series e:kt8m-rwtb d:2015-01-01T00:00:00.000Z t:applicant_institution_type="Elementary School" t:grant_type="Big Yellow School Bus Grant" t:applicant_zip=50265 t:applicant_state=Iowa t:house_district=43 t:senate_district=22 t:applicant_arts_discipline=Humanities t:congressional_district=3 t:applicant_city="West Des Moines" t:grants_grants_number=201507-233 t:project_title="BYSB Trip to Performance of ""The Best Christmas Pageant Ever" t:county=Polk t:type_of_activity_supported=Concert/Performance/Reading t:grantee_name="Iowa Christian Academy" t:applicant_status="Organization- Non-Profit" m:funding_returned=0 m:grant_award=200 m:total_artists_engaged=30 m:number_of_ia_artists_engaged=0 m:cash_match=0 m:youth_engaged_in_person=23 m:number_of_non_ia_artists_engaged=30 m:in_kind_match=0 m:actual_individuals_benefitting_from_project=25 m:grant_amount_spent=200

series e:kt8m-rwtb d:2015-01-01T00:00:00.000Z t:applicant_institution_type="Elementary School" t:grant_type="Big Yellow School Bus Grant" t:applicant_zip=50327-8031 t:fiscal_sponsor="Southeast Polk Community School District" t:applicant_state=Iowa t:senate_district=15 t:house_district=30 t:applicant_arts_discipline=Humanities t:congressional_district=3 t:applicant_city="Pleasant Hill" t:grants_grants_number=201507-270 t:project_title="BYSB Trip to Ballet Performance of The Nutcracker" t:county=Polk t:type_of_activity_supported=Concert/Performance/Reading t:grantee_name="Centennial Elementary School" t:applicant_status="Government- Municipal" m:funding_returned=0 m:grant_award=200 m:total_artists_engaged=80 m:number_of_ia_artists_engaged=80 m:cash_match=0 m:youth_engaged_in_person=74 m:number_of_non_ia_artists_engaged=0 m:in_kind_match=0 m:actual_individuals_benefitting_from_project=81 m:grant_amount_spent=200
```

## Meta Commands

```ls
metric m:actual_individuals_benefitting_from_project p:integer l:"Actual Individuals Benefitting from Project" t:dataTypeName=number

metric m:number_of_ia_artists_engaged p:integer l:"Number of IA Artists Engaged" t:dataTypeName=number

metric m:number_of_non_ia_artists_engaged p:integer l:"Number of Non-IA Artists Engaged" t:dataTypeName=number

metric m:total_artists_engaged p:integer l:"Total Artists Engaged" t:dataTypeName=number

metric m:youth_engaged_in_person p:integer l:"Youth Engaged In-Person" t:dataTypeName=number

metric m:grant_award p:integer l:"Grant Award" t:dataTypeName=money

metric m:funding_returned p:double l:"Funding Returned" t:dataTypeName=money

metric m:grant_amount_spent p:double l:"Grant Amount Spent" t:dataTypeName=money

metric m:in_kind_match p:integer l:"In-Kind Match" t:dataTypeName=money

metric m:cash_match p:integer l:"Cash Match" t:dataTypeName=money

entity e:kt8m-rwtb l:"Iowa Arts Council Grants Fiscal Years 2015 and 2016" t:attribution="Iowa Arts Council, Iowa Department of Cultural Affairs SalesForce Database" t:url=https://data.iowa.gov/api/views/kt8m-rwtb

property e:kt8m-rwtb t:meta.view v:id=kt8m-rwtb v:category="Communities & People" v:averageRating=0 v:name="Iowa Arts Council Grants Fiscal Years 2015 and 2016" v:attribution="Iowa Arts Council, Iowa Department of Cultural Affairs SalesForce Database"

property e:kt8m-rwtb t:meta.view.license v:name="Public Domain"

property e:kt8m-rwtb t:meta.view.owner v:id=uss5-yayd v:profileImageUrlMedium=/api/users/uss5-yayd/profile_images/THUMB v:profileImageUrlLarge=/api/users/uss5-yayd/profile_images/LARGE v:screenName="Iowa Department of Cultural Affairs" v:profileImageUrlSmall=/api/users/uss5-yayd/profile_images/TINY v:displayName="Iowa Department of Cultural Affairs"

property e:kt8m-rwtb t:meta.view.tableauthor v:id=uss5-yayd v:profileImageUrlMedium=/api/users/uss5-yayd/profile_images/THUMB v:profileImageUrlLarge=/api/users/uss5-yayd/profile_images/LARGE v:screenName="Iowa Department of Cultural Affairs" v:profileImageUrlSmall=/api/users/uss5-yayd/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Cultural Affairs"
```

## Top Records

```ls
| fiscal_year | grants_grants_number | grant_type                           | grantee_name                             | fiscal_sponsor                           | project_title                                                                                       | applicant_status         | applicant_institution_type | applicant_arts_discipline | type_of_activity_supported  | actual_individuals_benefitting_from_project | number_of_ia_artists_engaged | number_of_non_ia_artists_engaged | total_artists_engaged | youth_engaged_in_person | grant_award | funding_returned | grant_amount_spent | in_kind_match | congressional_district | senate_district | house_district | cash_match | applicant_city  | applicant_state | applicant_zip | county     | 
| =========== | ==================== | ==================================== | ======================================== | ======================================== | =================================================================================================== | ======================== | ========================== | ========================= | =========================== | =========================================== | ============================ | ================================ | ===================== | ======================= | =========== | ================ | ================== | ============= | ====================== | =============== | ============== | ========== | =============== | =============== | ============= | ========== | 
| 2015        | 201507-225           | Big Yellow School Bus Grant          | Creston Elementary School                | Creston Community School District        | BYSB Trip to Musical Theatre Performance                                                            | Government- Municipal    | Elementary School          | Humanities                | Concert/Performance/Reading | 145                                         | 0                            | 10                               | 10                    | 130                     | 200         | 0                | 200                | 0             | 5                      | 11              | 21             | 0          | Creston         | Iowa            | 50801         | Union      | 
| 2015        | 201507-233           | Big Yellow School Bus Grant          | Iowa Christian Academy                   |                                          | BYSB Trip to Performance of "The Best Christmas Pageant Ever                                        | Organization- Non-Profit | Elementary School          | Humanities                | Concert/Performance/Reading | 25                                          | 0                            | 30                               | 30                    | 23                      | 200         | 0                | 200                | 0             | 3                      | 22              | 43             | 0          | West Des Moines | Iowa            | 50265         | Polk       | 
| 2015        | 201507-270           | Big Yellow School Bus Grant          | Centennial Elementary School             | Southeast Polk Community School District | BYSB Trip to Ballet Performance of The Nutcracker                                                   | Government- Municipal    | Elementary School          | Humanities                | Concert/Performance/Reading | 81                                          | 80                           | 0                                | 80                    | 74                      | 200         | 0                | 200                | 0             | 3                      | 15              | 30             | 0          | Pleasant Hill   | Iowa            | 50327-8031    | Polk       | 
| 2015        | 201507-286           | Big Yellow School Bus Grant          | Audubon Middle School                    | Audubon Community School District        | BYSB Trip to Performance at Martha-Ellen Tye Performing Arts Institute 2014-15 Youth Matinee Series | Government- Municipal    | Middle School              | Humanities                | Concert/Performance/Reading | 44                                          | 0                            | 4                                | 4                     | 40                      | 200         | 0                | 200                | 0             | 5                      | 6               | 12             | 0          | Audubon         | Iowa            | 50025         | Audubon    | 
| 2015        | 201507-294           | Big Yellow School Bus Grant          | Graettinger-Terril Elementary School     | Graettinger-Terril Community School      | BYSB Trip to Youth Matinee Series                                                                   | Government- Municipal    | Elementary School          | Humanities                | Concert/Performance/Reading | 84                                          | 0                            | 20                               | 20                    | 76                      | 200         | 0                | 200                | 0             | 4                      | 1               | 2              | 0          | Terill          | Iowa            | 51364         | Clay       | 
| 2015        | 201507-295           | Big Yellow School Bus Grant          | Lawton Bronson Junior-Senior High School | Lawton Bronson Community School District | BYSB Trip to Sioux City Art Center                                                                  | Government- Municipal    | Secondary School           | Humanities                | Exhibition                  | 28                                          | 0                            | 5                                | 5                     | 26                      | 200         | 0                | 200                | 0             | 4                      | 3               | 5              | 0          | Lawton          | Iowa            | 51030-7700    | Woodbury   | 
| 2015        | 201507-312           | Cultural Leadership Partners Program | Summer of the Arts                       |                                          | CLP Funding for FY15                                                                                | Organization- Non-Profit | Fair/Festival              | Multidisciplinary         | Operating Support           | 100000                                      | 694                          | 210                              | 904                   | 10000                   | 10000       | 0                | 10000              | 0             | 2                      | 43              | 85             | 150000     | Iowa City       | Iowa            | 52244-3128    | Johnson    | 
| 2015        | 201507-318           | Cultural Leadership Partners Program | Living History Farms                     |                                          | CLP Funding for FY15                                                                                | Organization- Non-Profit | None of the Above          | Humanities                | Operating Support           | 101015                                      | 8                            | 2                                | 10                    | 50865                   | 20000       | 0                | 20000              | 0             | 3                      | 20              | 40             | 150000     | Urbandale       | Iowa            | 50322         | Polk       | 
| 2015        | 201507-335           | Cultural Leadership Partners Program | Spencer Community Theatre                |                                          | CLP Funding for FY15                                                                                | Organization- Non-Profit | Performance Facility       | Theatre                   | Operating Support           | 7700                                        | 0                            | 0                                | 0                     | 1026                    | 10000       | 0                | 10000              | 0             | 4                      | 1               | 2              | 150000     | Spencer         | Iowa            | 51301         | Clay       | 
| 2015        | 201507-336           | Cultural Leadership Partners Program | Waterloo-Cedar Falls Symphony Orchestra  |                                          | CLP Funding for FY15                                                                                | Organization- Non-Profit | Performing Group           | Music                     | Operating Support           | 15500                                       | 175                          | 15                               | 190                   | 9500                    | 12000       | 0                | 12000              | 0             | 1                      | 30              | 59             | 150000     | Cedar Falls     | Iowa            | 50614-0803    | Black Hawk | 
```