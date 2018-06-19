# Emergency Management Department - Community Outreach - First Quarter 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/emergency-management-department-community-outreach-first-quarter-2014-7264d) |
| Metadata | [Link](https://data.lacity.org/api/views/6xuk-a67v) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/6xuk-a67v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/6xuk-a67v/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 6xuk-a67v |
| Name | Emergency Management Department - Community Outreach - First Quarter 2014 |
| Category | A Safe City |
| Tags | emergency preparedness, emergency management |
| Created | 2014-05-27T17:20:17Z |
| Publication Date | 2014-05-29T23:00:47Z |

## Description

Community Outreach conducted by the Emergency Management Department for the period of January - March 2014

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | activity                    | Activity                    | text          | text          |
| Yes      | time           | date                        | Date                        | calendar_date | calendar_date |
| Yes      | series tag     | purpose                     | Purpose                     | text          | text          |
| Yes      | series tag     | category                    | Category                    | text          | text          |
| Yes      | series tag     | division                    | Division                    | text          | text          |
| Yes      | series tag     | location_or_council_distrct | Location or Council Distrct | text          | text          |
| Yes      | numeric metric | materials_distributed       | Materials Distributed       | number        | number        |
| Yes      | numeric metric | meetings_held               | Meetings Held               | number        | number        |
| Yes      | numeric metric | antendees                   | Antendees                   | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6xuk-a67v d:2014-01-11T00:00:00.000Z t:location_or_council_distrct="4831 S. Gramercy Pl., 90062" t:category="Community Outreach" t:division="Community Emergency Management" t:purpose="Conducted presentation with Emergency Preparedness Materials" t:activity="Brookins Community AME Church Emergency Preparedness Presentation" m:meetings_held=1 m:materials_distributed=150 m:antendees=150

series e:6xuk-a67v d:2014-02-05T00:00:00.000Z t:location_or_council_distrct="Port of Long Beach Adminstration Building" t:category="Community Outreach" t:division="Community Emergency Management" t:purpose="Quarterly Meeting" t:activity="AMSC Meeting" m:meetings_held=1 m:antendees=50

series e:6xuk-a67v d:2014-02-11T00:00:00.000Z t:location_or_council_distrct="Carson Community Center" t:category="Community Outreach" t:division="Community Emergency Management" t:purpose="Monthly Meeting" t:activity="SB CAER Meeting" m:meetings_held=1 m:antendees=10
```

## Meta Commands

```ls
metric m:materials_distributed p:integer l:"Materials Distributed" t:dataTypeName=number

metric m:meetings_held p:integer l:"Meetings Held" t:dataTypeName=number

metric m:antendees p:integer l:Antendees t:dataTypeName=number

entity e:6xuk-a67v l:"Emergency Management Department - Community Outreach - First Quarter 2014" t:url=https://data.lacity.org/api/views/6xuk-a67v

property e:6xuk-a67v t:meta.view v:id=6xuk-a67v v:category="A Safe City" v:averageRating=0 v:name="Emergency Management Department - Community Outreach - First Quarter 2014"

property e:6xuk-a67v t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:6xuk-a67v t:meta.view.owner v:id=vnsa-hifw v:profileImageUrlMedium=/api/users/vnsa-hifw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vnsa-hifw/profile_images/LARGE v:screenName="Emergency Management OpenData" v:profileImageUrlSmall=/api/users/vnsa-hifw/profile_images/TINY v:displayName="Emergency Management OpenData"

property e:6xuk-a67v t:meta.view.tableauthor v:id=vnsa-hifw v:profileImageUrlMedium=/api/users/vnsa-hifw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vnsa-hifw/profile_images/LARGE v:screenName="Emergency Management OpenData" v:profileImageUrlSmall=/api/users/vnsa-hifw/profile_images/TINY v:roleName=publisher v:displayName="Emergency Management OpenData"
```

## Top Records

```ls
| activity                                                              | date                | purpose                                                      | category           | division                       | location_or_council_distrct                                 | materials_distributed | meetings_held | antendees | 
| ===================================================================== | =================== | ============================================================ | ================== | ============================== | =========================================================== | ===================== | ============= | ========= | 
| Brookins Community AME Church Emergency Preparedness Presentation     | 2014-01-11T00:00:00 | Conducted presentation with Emergency Preparedness Materials | Community Outreach | Community Emergency Management | 4831 S. Gramercy Pl., 90062                                 | 150                   | 1             | 150       | 
| AMSC Meeting                                                          | 2014-02-05T00:00:00 | Quarterly Meeting                                            | Community Outreach | Community Emergency Management | Port of Long Beach Adminstration Building                   |                       | 1             | 50        | 
| SB CAER Meeting                                                       | 2014-02-11T00:00:00 | Monthly Meeting                                              | Community Outreach | Community Emergency Management | Carson Community Center                                     |                       | 1             | 10        | 
| USC Safety Task Force Meeting                                         | 2014-02-20T00:00:00 | Monthly Meeting                                              | Community Outreach | Community Emergency Management | USC Community House                                         |                       | 1             | 15        | 
| Emergency Preparedness Presentation for St Paul's Presbyterian Church | 2014-03-15T00:00:00 | Conducted presentation with Emergency Preparedness Materials | Community Outreach | Community Emergency Management | St Paul's Presbyterian Church 5100 Coliseum St., 90016      | 20                    | 1             | 20        | 
| Emergency Preparedness Presentation for Parents of the Center         | 2014-03-26T00:00:00 | Conducted presentation with Emergency Preparedness Materials | Community Outreach | Community Emergency Management | 66th St. School Early Education Center, 407 E. 67th St., LA | 40                    | 1             | 40        | 
| EP Brochures for City Libraries                                       | 2014-04-17T00:00:00 | Family Emergency Preparedness Guides - Spanish               | Community Outreach | Community Emergency Management | South DMD                                                   | 1225                  |               |           | 
| EP Brochures for City Libraries                                       | 2014-04-17T00:00:00 | Childrens' Emergency Preparedness Books - Spanish            | Community Outreach | Community Emergency Management | South DMD                                                   | 2100                  |               |           | 
| EP Brochures for City Libraries                                       | 2014-04-17T00:00:00 | Tsunami Preparedness Brochures                               | Community Outreach | Community Emergency Management | South DMD                                                   | 6600                  |               |           | 
| EP Brochures for City Libraries                                       | 2014-04-17T00:00:00 | Emergency Preparedness Checklist Information                 | Community Outreach | Community Emergency Management | South DMD                                                   | 3000                  |               |           | 
```