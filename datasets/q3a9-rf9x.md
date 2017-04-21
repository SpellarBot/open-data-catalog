# Oregon Recovery and Reinvestment Act Data - March, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-recovery-and-reinvestment-act-data-march-2012-7f215) |
| Metadata | [Link](https://data.oregon.gov/api/views/q3a9-rf9x) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/q3a9-rf9x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/q3a9-rf9x/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | q3a9-rf9x |
| Name | Oregon Recovery and Reinvestment Act Data - March, 2012 |
| Attribution | State of Oregon Economic Recovery Executive Team (ERET) |
| Category | Administrative |
| Tags | oregon, arra, recovery and reinvestment act, stimulus, reporting, jobs, employment |
| Created | 2011-07-14T21:46:08Z |
| Publication Date | 2012-04-20T20:49:33Z |

## Description

This spreadsheet contains Oregon Recovery and Reinvestment Act (ARRA) Data reported on the State of Oregon Recovery site (http://oregon.gov/recovery/StimulusReporting/ARRA_Projects.shtml). Please note that this data reflects the preliminary data from the most recent reporting period of the American Recovery and Reinvestment Act of 2009, including data through March 30, 2011. This data available for viewing through an interactive map site. For this, and other information on ARRA projects, please visit Oregon's Economic Recovery site: http://www.oregon.gov/recovery. For the latest recovery award data, please visit http://www.recovery.gov.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | numeric metric | sort_order             | SORT ORDER             | number    | number      |
| Yes      | series tag     | prime_number           | PRIME NUMBER           | text      | text        |
| Yes      | series tag     | recipient_type         | RECIPIENT TYPE         | text      | text        |
| Yes      | series tag     | county                 | COUNTY                 | text      | text        |
| Yes      | series tag     | category               | CATEGORY               | text      | text        |
| Yes      | series tag     | award_name             | AWARD NAME             | text      | text        |
| Yes      | series tag     | project_name           | PROJECT NAME           | text      | text        |
| Yes      | series tag     | recipient              | RECIPIENT              | text      | text        |
| Yes      | numeric metric | award_amount           | AWARD AMOUNT           | money     | money       |
| Yes      | numeric metric | amount_expended        | AMOUNT EXPENDED        | money     | money       |
| Yes      | numeric metric | jobs_funded            | JOBS FUNDED            | number    | number      |
| Yes      | series tag     | project_status         | PROJECT STATUS         | text      | text        |
| Yes      | series tag     | project_description    | PROJECT DESCRIPTION    | text      | text        |
| No       |                | address                | ADDRESS                | text      | text        |
| Yes      | series tag     | city                   | CITY                   | text      | text        |
| Yes      | series tag     | state                  | STATE                  | text      | text        |
| Yes      | series tag     | zipcode                | ZIPCODE                | text      | text        |
| Yes      | series tag     | congressional_district | CONGRESSIONAL DISTRICT | text      | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:q3a9-rf9x d:2012-01-01T00:00:00.000Z t:award_name=AmeriCorps t:category="Community Service" t:project_name="State Recovery Formula -Award #729" t:project_status=Completed t:county=Multnomah t:zipcode=97206-7564 t:prime_number=09RFHOR001 t:state=OR t:congressional_district=3 t:recipient_type=SUB t:project_description="28 AmeriCorps members will enhance the ability of Impact NW to address poverty related issues.  One team serves at Impact NW to enhance capacity of the organization.  A second team serves with Portland Public Schools." t:recipient="Portland Impact, Inc." t:city=Portland m:amount_expended=366325.78 m:award_amount=366326 m:sort_order=1996

series e:q3a9-rf9x d:2012-01-01T00:00:00.000Z t:award_name=AmeriCorps t:category="Community Service" t:project_name="State Competitive Recovery Programs -Award #730" t:project_status=Completed t:county=Multnomah t:zipcode=97227-1560 t:prime_number=09RCHOR002 t:state=OR t:congressional_district=3 t:recipient_type=SUB t:project_description="AmeriCorps funding supports 24 full time members serving across Oregon at Community Action Agencies, and 10 part time members serving at local agencies during the summer." t:recipient="American Red Cross Oregon Trail Chapter" t:city=Portland m:amount_expended=301805.74 m:award_amount=317815 m:sort_order=1998

series e:q3a9-rf9x d:2012-01-01T00:00:00.000Z t:award_name=AmeriCorps t:category="Community Service" t:project_name="State Compettiive Recovery Programs -Award #731" t:project_status=Completed t:county=Lane t:zipcode=97403-5295 t:prime_number=09RCHOR002 t:state=OR t:congressional_district=4 t:recipient_type=SUB t:project_description="American Recovery and Reinvestment Act AmeriCorps Competitive - University of Oregon" t:recipient="University of Oregon" t:city=Eugene m:amount_expended=84284.22 m:award_amount=88934 m:sort_order=1999
```

## Meta Commands

```ls
metric m:sort_order p:integer l:"SORT ORDER" t:dataTypeName=number

metric m:award_amount p:double l:"AWARD AMOUNT" t:dataTypeName=money

metric m:amount_expended p:double l:"AMOUNT EXPENDED" t:dataTypeName=money

metric m:jobs_funded p:float l:"JOBS FUNDED" t:dataTypeName=number

entity e:q3a9-rf9x l:"Oregon Recovery and Reinvestment Act Data - March, 2012" t:attribution="State of Oregon Economic Recovery Executive Team (ERET)" t:url=https://data.oregon.gov/api/views/q3a9-rf9x

property e:q3a9-rf9x t:meta.view v:id=q3a9-rf9x v:category=Administrative v:attributionLink=http://www.oregon.gov/recovery v:averageRating=0 v:name="Oregon Recovery and Reinvestment Act Data - March, 2012" v:attribution="State of Oregon Economic Recovery Executive Team (ERET)"

property e:q3a9-rf9x t:meta.view.owner v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"

property e:q3a9-rf9x t:meta.view.tableauthor v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"
```

## Top Records

```ls
| sort_order | prime_number    | recipient_type | county     | category          | award_name                   | project_name                                                   | recipient                               | award_amount | amount_expended | jobs_funded | project_status | project_description                                                                                                                                                                                                                                    | address                   | city      | state | zipcode    | congressional_district | 
| ========== | =============== | ============== | ========== | ================= | ============================ | ============================================================== | ======================================= | ============ | =============== | =========== | ============== | ====================================================================================================================================================================================================================================================== | ========================= | ========= | ===== | ========== | ====================== | 
| 1996       | 09RFHOR001      | SUB            | Multnomah  | Community Service | AmeriCorps                   | State Recovery Formula -Award #729                             | Portland Impact, Inc.                   | 366326       | 366325.78       |             | Completed      | 28 AmeriCorps members will enhance the ability of Impact NW to address poverty related issues. One team serves at Impact NW to enhance capacity of the organization. A second team serves with Portland Public Schools.                                | 7211 SE 62nd Avenue       | Portland  | OR    | 97206-7564 | 3                      | 
| 1998       | 09RCHOR002      | SUB            | Multnomah  | Community Service | AmeriCorps                   | State Competitive Recovery Programs -Award #730                | American Red Cross Oregon Trail Chapter | 317815       | 301805.74       |             | Completed      | AmeriCorps funding supports 24 full time members serving across Oregon at Community Action Agencies, and 10 part time members serving at local agencies during the summer.                                                                             | 3131 N. Vancouver         | Portland  | OR    | 97227-1560 | 3                      | 
| 1999       | 09RCHOR002      | SUB            | Lane       | Community Service | AmeriCorps                   | State Compettiive Recovery Programs -Award #731                | University of Oregon                    | 88934        | 84284.22        |             | Completed      | American Recovery and Reinvestment Act AmeriCorps Competitive - University of Oregon                                                                                                                                                                   | 5219 University of Oregon | Eugene    | OR    | 97403-5295 | 4                      | 
| 13131      | 41-50-M09042    | PRIME          | Deschutes  | Community Service | Broadband Mapping            | State Broadband Data and Development Grant Program Award #2356 | Public Utility Commission of Oregon     | 5658302      | 1797998.74      | 3.46        | On Schedule    | One Economy and its partners will collaborate with the PUC and Oregon's Department of Administrative Services, Enterprise Information Strategy and Policy Division to collect and map broadband infrastructure and availability of broadband services. | 550 Capitol St NE         | Salem     | OR    | 97308-2148 | 2                      | 
| 13         | B-09-DY-41-0001 | SUB            | Baker      | Community Service | Community Development Grants | Haines Wastewater System Improvements Award #1                 | City of Haines                          | 1249650      | 1249650         | 0.89        | Completed      | The City of Haines will use recovery funds to make mandated improvements to its wastewater system in accordance with the Oregon Department of Environmental Quality standards.                                                                         | 819 Front Street          | Haines    | OR    | 978330208  | 2                      | 
| 17         | B-09-DY-41-0001 | SUB            | Marion     | Community Service | Community Development Grants | City of Silverton Award #2                                     | City of Silverton                       | 1095000      | 1095000         |             | Completed      | The City of Silverton will use recovery funds to construct a 4,000-to 5,000-square-foot senior center with a modern and efficient kitchen, larger dining area and offices for center staff.                                                            | 306 S Water Street        | Silverton | OR    | 973812002  | 5                      | 
| 19         | B-09-DY-41-0001 | SUB            | Tillamook  | Community Service | Community Development Grants | Hebo Water System Upgrades Award #11                           | Tillamook County                        | 1216132      | 1060009         | 0           | Completed      | The Hebo Joint Water and Sanitary Improvement Authority, located in Tillamook County, will use the recovery funds to upgrade the water system.                                                                                                         | 307550 Hwy. 101 S.        | Hebo      | OR    | 97122      | 5                      | 
| 12744      | 0901ORCOS2      | SUB            | Douglas    | Community Service | Community Service Grant      | CSBG ARRA Douglas and Josephine Counties -Award #2060          | United Community Action Network         | 456187       | 456187          |             | Completed      | UCAN provides emergency relief services to area homeless and assists them in accessing services. UCAN also provides transportation services for the elderly to medical appointments in Douglas and Josephine Counties.                                 | 280 Kenneth Ford Dr       | Roseburg  | OR    | 97470-1034 | 4                      | 
| 12745      | 0901ORCOS2      | SUB            | Washington | Community Service | Community Service Grant      | CAO CSBG ARRA Washington County -Award #2088                   | Community Action Organization           | 570880       | 570880          |             | Completed      | Programs and services to support employment, health and housing stability in Washington County.                                                                                                                                                        | 1001 SW Baseline St       | Hillsboro | OR    | 97123-3822 | 1                      | 
| 12746      | 0901ORCOS2      | SUB            | Washington | Community Service | Community Service Grant      | CSBG ARRA Washington County -Award #2087                       | Washington County                       | 22691.11     | 22691.11        |             | On Schedule    | Provided meals and nutrition education to students during the summer.                                                                                                                                                                                  | 155 N First Ave. MS#4     | Hillsboro | OR    | 97124      | 1                      | 
```