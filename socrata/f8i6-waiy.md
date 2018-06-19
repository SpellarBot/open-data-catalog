# College Access Challenge Grant Program (CACGP) Subgrantees: 2008-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/college-access-challenge-grant-program-cacgp-sub-grantees) |
| Metadata | [Link](https://data.ny.gov/api/views/f8i6-waiy) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/f8i6-waiy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/f8i6-waiy/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | f8i6-waiy |
| Name | College Access Challenge Grant Program (CACGP) Subgrantees: 2008-2016 |
| Attribution | New York State Higher Education Services Corporation |
| Category | Education |
| Tags | grants, postsecondary schools, education |
| Created | 2013-08-12T19:27:16Z |
| Publication Date | 2016-07-07T16:27:25Z |

## Description

The overall goal of New York's College Access Challenge Grant (CACG) is to increase the number of low-income, minority and underserved students who are prepared to apply for, get accepted to and succeed in college, with a priority on families living below the poverty-level.This data includes the names of the organizations that received CACGP sub-grants during the Award Period, the number of students and families that received (or will receive) services from the sub-grantee, and the grant amount awarded to each organization.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | sub_grantee_name         | Sub Grantee Name         | text      | text        |
| Yes      | series tag     | street_address           | Street Address           | text      | text        |
| Yes      | series tag     | city                     | City                     | text      | text        |
| Yes      | series tag     | state                    | State                    | text      | text        |
| Yes      | series tag     | zip                      | Zip                      | text      | text        |
| Yes      | series tag     | phone_number             | Phone Number             | text      | text        |
| Yes      | series tag     | website                  | Website                  | url       | url         |
| Yes      | series tag     | services_provided        | Services Provided        | text      | text        |
| Yes      | series tag     | population_served        | Population Served        | text      | text        |
| Yes      | numeric metric | cacg_recipient_headcount | CACG Recipient Headcount | number    | number      |
| Yes      | series tag     | area_served              | Area Served              | text      | text        |
| Yes      | series tag     | award_period             | Award Period             | text      | text        |
| Yes      | numeric metric | award_amount             | Award Amount             | money     | money       |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:f8i6-waiy d:2008-01-01T00:00:00.000Z t:zip=10075 t:area_served="11235 - 11101 - 10007" t:award_period="Academic Year 2015-2016" t:sub_grantee_name="City University of New York" t:phone_number=646-664-8764 t:website=http://cuny.edu t:state=N.Y. t:services_provided="Outreach and information on the benefits of postsecondary education -  Academic Enrichment, Tutoring - Mentoring - College Completion Services" t:population_served="College Students" t:street_address="East 80th Street" t:city="New York" m:award_amount=202676 m:cacg_recipient_headcount=50

series e:f8i6-waiy d:2008-01-01T00:00:00.000Z t:zip=10701 t:area_served=10701 t:award_period="Academic Year 2015-2016" t:sub_grantee_name="Yonkers Partners in Education, Inc." t:phone_number=914-377-4882 t:website=http://ypie.org t:state=N.Y. t:services_provided="Outreach and information on the benefits of postsecondary education - Outreach and information on how to pay for college - FAFSA and Financial Aid form completion assistance - Academic Enrichment, Tutoring and SAT / ACT preparation services - College Visits" t:population_served="High School Students - Middle School Students ? Parents" t:street_address="86 Main Street, Suite 301" t:city=Yonkers m:award_amount=492354 m:cacg_recipient_headcount=618

series e:f8i6-waiy d:2008-01-01T00:00:00.000Z t:zip=11101 t:area_served="10011 - 11231 - 11694 - 11203 - 11214 - 10457 - 10033 - 10314" t:award_period="Academic Year 2015-2016" t:sub_grantee_name="New York City Outward Bound Center, Inc." t:phone_number=718-706-9900 t:website=http://nycoutwardbound.org t:state=N.Y. t:services_provided="Outreach and information on the benefits of postsecondary education - Outreach and information on how to pay for college - FAFSA and Financial Aid Form completion and assistance - College Visits - Professional Development for School Counselors" t:population_served="High School Students - Parents - Professional Staff" t:street_address="29-46 Northern Boulevard" t:city="Long Island City" m:award_amount=183667 m:cacg_recipient_headcount=786
```

## Meta Commands

```ls
metric m:cacg_recipient_headcount p:integer l:"CACG Recipient Headcount" d:"Number of recipients as measured by proposed number of students to receive at least one service during the academic year." t:dataTypeName=number

metric m:award_amount p:integer l:"Award Amount" d:"Total CACG dollars provided to the subgrantee" t:dataTypeName=money

entity e:f8i6-waiy l:"College Access Challenge Grant Program (CACGP) Subgrantees: 2008-2016" t:attribution="New York State Higher Education Services Corporation" t:url=https://data.ny.gov/api/views/f8i6-waiy

property e:f8i6-waiy t:meta.view v:id=f8i6-waiy v:category=Education v:attributionLink=http://www.hesc.ny.gov/content.nsf/CA/College_Access_Challenge_Grant v:averageRating=0 v:name="College Access Challenge Grant Program (CACGP) Subgrantees: 2008-2016" v:attribution="New York State Higher Education Services Corporation"

property e:f8i6-waiy t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:f8i6-waiy t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:f8i6-waiy t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| sub_grantee_name                                    | street_address                              | city             | state | zip   | phone_number | website                                   | services_provided                                                                                                                                                                                                                                                                          | population_served                                                            | cacg_recipient_headcount | area_served                                                   | award_period            | award_amount | 
| =================================================== | =========================================== | ================ | ===== | ===== | ============ | ========================================= | ========================================================================================================================================================================================================================================================================================== | ============================================================================ | ======================== | ============================================================= | ======================= | ============ | 
| City University of New York                         | East 80th Street                            | New York         | N.Y.  | 10075 | 646-664-8764 | [http://cuny.edu, null]                   | Outreach and information on the benefits of postsecondary education - Academic Enrichment, Tutoring - Mentoring - College Completion Services                                                                                                                                              | College Students                                                             | 50                       | 11235 - 11101 - 10007                                         | Academic Year 2015-2016 | 202676       | 
| Yonkers Partners in Education, Inc.                 | 86 Main Street, Suite 301                   | Yonkers          | N.Y.  | 10701 | 914-377-4882 | [http://ypie.org, null]                   | Outreach and information on the benefits of postsecondary education - Outreach and information on how to pay for college - FAFSA and Financial Aid form completion assistance - Academic Enrichment, Tutoring and SAT / ACT preparation services - College Visits                          | High School Students - Middle School Students ? Parents                      | 618                      | 10701                                                         | Academic Year 2015-2016 | 492354       | 
| New York City Outward Bound Center, Inc.            | 29-46 Northern Boulevard                    | Long Island City | N.Y.  | 11101 | 718-706-9900 | [http://nycoutwardbound.org, null]        | Outreach and information on the benefits of postsecondary education - Outreach and information on how to pay for college - FAFSA and Financial Aid Form completion and assistance - College Visits - Professional Development for School Counselors                                        | High School Students - Parents - Professional Staff                          | 786                      | 10011 - 11231 - 11694 - 11203 - 11214 - 10457 - 10033 - 10314 | Academic Year 2015-2016 | 183667       | 
| Sports & Arts in School Foundation                  | 12 Queens Boulevard Suite 1                 | Woodside Queens  | N.Y.  | 11377 | 347-417-8120 | [http://sasfny.org, null]                 | Outreach and information on the benefits of postsecondary education - Outreach and information on how to pay for college - Academic Enrichment, Tutoring - College Visits - Mentoring                                                                                                      | Middle School Students ? Parents                                             | 75                       | 10052 - 10550                                                 | Academic Year 2015-2016 | 50000        | 
| State University of New York                        | T-8 State University Plaza                  | Albany           | N.Y.  | 12246 | 518-320-1399 | [http://suny.edu, null]                   | Outreach and information on the benefits of postsecondary education - Academic Enrichment, Tutoring - Mentoring - College Completion Services                                                                                                                                              | College Students                                                             | 400                      | 12246                                                         | Academic Year 2015-2016 | 300000       | 
| NYS Office of Children and Family Services          | 52 Washington Street Room 236 N             | Rensselaer       | N.Y.  | 12144 | 518-408-0285 | [http://youthincare.org, null]            | Outreach and information on the benefits of postsecondary education - Outreach and information on how to pay for college - FAFSA and Financial Aid form completion assistance - College Visits - Mentoring                                                                                 | High School Students - Middle School Students                                | 400                      | 12144                                                         | Academic Year 2015-2016 | 400000       | 
| Veteran's Outreach Center                           | 459 South Avenue                            | Rochester        | N.Y.  | 14620 | 585-295-7800 | [http://veteransoutreachcenter.org, null] | Outreach and information on how to pay for college - FAFSA and Financial Aid form completion assistance                                                                                                                                                                                    | Adult Learners - Veterans                                                    | 300                      | 14620                                                         | Academic Year 2015-2016 | 72980        | 
| Cypress Hills Local Development Corp.               | 999 Jamaica Avenue, Success Center Room B29 | Brooklyn         | N.Y.  | 11208 | 718-647-2100 | [http://cypresshills.org, null]           | Outreach and information on the benefits of postsecondary education - Outreach and information on how to pay for college - FAFSA and Financial Aid form completion assistance - Academic Enrichment, Tutoring and SAT / ACT preparation services - Mentoring - College Completion Services | Middle School Students - High School Students - Parents - College Students   | 645                      | 11208                                                         | Academic Year 2015-2016 | 75000        | 
| Syracuse University                                 | 804 University Avenue, Suite 009            | Syracuse         | N.Y.  | 13244 | 315-443-3867 | [http://syr.edu, null]                    | Outreach and information on the benefits of postsecondary education - Outreach and information on how to pay for college - FAFSA and Financial Aid Form completion and assistance - College Visits                                                                                         | High School Students - Parents                                               | 100                      | 13601                                                         | Academic Year 2015-2016 | 49988        | 
| Commission on Independent Colleges and Universities | 17 Elk Street                               | Albany           | N.Y.  | 12224 | 518-436-4781 | [http://cicu.org, null]                   | Outreach and information on the benefits of postsecondary education - Outreach and information on how to pay for college - College Visits - College Fairs -Professional Development for School Counselors                                                                                  | High School Students - Middle School Students ? Parents - Professional Staff | 3100                     | 10040 - 11203 - 10463 - 10029 - 14760 - 14880 - 14895         | Academic Year 2015-2016 | 400000       | 
```