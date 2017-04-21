# Green Building Education

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/green-building-education) |
| Metadata | [Link](https://data.austintexas.gov/api/views/gzz4-cedg) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/gzz4-cedg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/gzz4-cedg/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | gzz4-cedg |
| Name | Green Building Education |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | green building, education, seminars, graduates, energy, austin energy |
| Created | 2016-08-25T16:37:44Z |
| Publication Date | 2017-01-31T16:13:15Z |

## Description

Austin Energy Green Building education programs reach out to the entire community ? from the casually interested to building professionals. Monthly professional development Seminars help building professionals keep up with the latest in the field while earning continuing education hours. The Green Boots educational series for residential builders and trades provides the nuts and bolts to making green goals a reality. The public learns about green building principles and practices through the Green by Design workshop and the annual Cool House Tour co-produced with the Texas Solar Energy Society. This spreadsheet includes the estimated number of attendees at Green Building seminars, classes and events.
Note: Certain class results are blank cells because they were not offered at that time or the data was not tracked.

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                       | Data Type     | Render Type   |
| ======== | ============== | ========================================================== | ========================================================== | ============= | ============= |
| Yes      | time           | fiscal_year                                                | Fiscal Year                                                | calendar_date | calendar_date |
| Yes      | numeric metric | aegb_professional_development_seminars_estimated_attendees | AEGB Professional Development Seminars Estimated Attendees | number        | number        |
| Yes      | numeric metric | aia_approved_continuing_education_hours_offered3           | AIA-Approved Continuing Education Hours Offered            | number        | number        |
| Yes      | numeric metric | gbci_approved_continuing_education_hours_offered3          | GBCI-Approved Continuing Education Hours Offered           | number        | number        |
| Yes      | numeric metric | green_by_design_attendees                                  | Green by Design Attendees                                  | number        | number        |
| Yes      | numeric metric | green_boots_module_attendees4                              | Green Boots Module Attendees                               | number        | number        |
| Yes      | numeric metric | green_boots_certified_graduates                            | Green Boots Certified Graduates                            | number        | number        |
| Yes      | numeric metric | cool_house_tour_attendees                                  | Cool House Tour Attendees                                  | number        | number        |
| Yes      | numeric metric | aegb_educational_seminars_estimated_attendees              | Other AEGB Educational Events Attendees                    | number        | number        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:gzz4-cedg d:2016-01-01T00:00:00.000Z m:green_by_design_attendees=136 m:cool_house_tour_attendees=1008 m:gbci_approved_continuing_education_hours_offered3=28 m:aegb_professional_development_seminars_estimated_attendees=760 m:aegb_educational_seminars_estimated_attendees=47 m:aia_approved_continuing_education_hours_offered3=79

series e:gzz4-cedg d:2015-01-01T00:00:00.000Z m:green_by_design_attendees=159 m:cool_house_tour_attendees=743 m:gbci_approved_continuing_education_hours_offered3=28 m:aegb_professional_development_seminars_estimated_attendees=925 m:aegb_educational_seminars_estimated_attendees=0 m:aia_approved_continuing_education_hours_offered3=96

series e:gzz4-cedg d:2014-01-01T00:00:00.000Z m:green_by_design_attendees=127 m:cool_house_tour_attendees=990 m:gbci_approved_continuing_education_hours_offered3=39 m:aegb_professional_development_seminars_estimated_attendees=680 m:aegb_educational_seminars_estimated_attendees=93 m:aia_approved_continuing_education_hours_offered3=97.5 m:green_boots_certified_graduates=20 m:green_boots_module_attendees4=250
```

## Meta Commands

```ls
metric m:aegb_professional_development_seminars_estimated_attendees p:integer l:"AEGB Professional Development Seminars Estimated Attendees" t:dataTypeName=number

metric m:aia_approved_continuing_education_hours_offered3 p:float l:"AIA-Approved Continuing Education Hours Offered" d:"Represents the number of credits a professional could earn per year, not the entire number offered" t:dataTypeName=number

metric m:gbci_approved_continuing_education_hours_offered3 p:float l:"GBCI-Approved Continuing Education Hours Offered" d:"Represents the number of credits a professional could earn per year, not the entire number offered" t:dataTypeName=number

metric m:green_by_design_attendees p:integer l:"Green by Design Attendees" d:"Represents the number of credits a professional could earn per year, not the entire number offered" t:dataTypeName=number

metric m:green_boots_module_attendees4 p:integer l:"Green Boots Module Attendees" d:"Represents number of Attendees per Module (similar to how we report Seminar attendance)" t:dataTypeName=number

metric m:green_boots_certified_graduates p:integer l:"Green Boots Certified Graduates" t:dataTypeName=number

metric m:cool_house_tour_attendees p:integer l:"Cool House Tour Attendees" t:dataTypeName=number

metric m:aegb_educational_seminars_estimated_attendees p:integer l:"Other AEGB Educational Events Attendees" t:dataTypeName=number

entity e:gzz4-cedg l:"Green Building Education" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/gzz4-cedg

property e:gzz4-cedg t:meta.view v:id=gzz4-cedg v:category=Utility v:averageRating=0 v:name="Green Building Education" v:attribution="Austin Energy"

property e:gzz4-cedg t:meta.view.license v:name="Public Domain"

property e:gzz4-cedg t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:gzz4-cedg t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year         | aegb_professional_development_seminars_estimated_attendees | aia_approved_continuing_education_hours_offered3 | gbci_approved_continuing_education_hours_offered3 | green_by_design_attendees | green_boots_module_attendees4 | green_boots_certified_graduates | cool_house_tour_attendees | aegb_educational_seminars_estimated_attendees | 
| =================== | ========================================================== | ================================================ | ================================================= | ========================= | ============================= | =============================== | ========================= | ============================================= | 
| 2016-01-01T00:00:00 | 760                                                        | 79                                               | 28                                                | 136                       |                               |                                 | 1008                      | 47                                            | 
| 2015-01-01T00:00:00 | 925                                                        | 96                                               | 28                                                | 159                       |                               |                                 | 743                       | 0                                             | 
| 2014-01-01T00:00:00 | 680                                                        | 97.5                                             | 39                                                | 127                       | 250                           | 20                              | 990                       | 93                                            | 
| 2013-01-01T00:00:00 | 601                                                        | 75.5                                             | 73.5                                              | 45                        | 93                            | 14                              | 1150                      |                                               | 
| 2012-01-01T00:00:00 | 593                                                        | 68                                               | 71                                                | 142                       | 252                           | 21                              | 1600                      |                                               | 
| 2011-01-01T00:00:00 | 548                                                        | 80.5                                             | 70                                                | 171                       | 228                           | 26                              | 2200                      |                                               | 
| 2010-01-01T00:00:00 | 598                                                        | 66                                               |                                                   | 377                       | 307                           | 29                              | 1800                      |                                               | 
| 2009-01-01T00:00:00 | 663                                                        | 66                                               |                                                   | 505                       | 447                           | 32                              | 1650                      |                                               | 
| 2008-01-01T00:00:00 | 696                                                        | 28                                               |                                                   | 651                       |                               |                                 | 1500                      |                                               | 
| 2007-01-01T00:00:00 | 606                                                        | 28                                               |                                                   | 696                       |                               |                                 | 2000                      |                                               | 
```