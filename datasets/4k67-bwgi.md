# Emergency Management Department ? Community Outreach - Second Quarter 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/emergency-management-department-community-outreach-second-quarter-2014-816a6) |
| Metadata | [Link](https://data.lacity.org/api/views/4k67-bwgi) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/4k67-bwgi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/4k67-bwgi/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 4k67-bwgi |
| Name | Emergency Management Department ? Community Outreach - Second Quarter 2014 |
| Category | A Safe City |
| Tags | emergency preparedness, emergency management |
| Created | 2014-08-07T22:41:24Z |
| Publication Date | 2014-08-07T22:57:58Z |

## Description

Community outreach conducted by the Emergency Management Department for the period of April - June 2014.

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
series e:4k67-bwgi d:2014-04-08T00:00:00.000Z t:location_or_council_distrct="Carson Community Center" t:category="Community Outreach" t:division="Community Emergency Management" t:purpose="Attended Monthly Meeting" t:activity="SB CAER Meeting" m:meetings_held=1 m:antendees=15

series e:4k67-bwgi d:2014-04-24T00:00:00.000Z t:location_or_council_distrct="Miramonte Early Education Center,  1341 E.  70th St" t:category="Community Outreach" t:division="Community Emergency Management" t:purpose="Conducted presentation with Emergency Preparedness Materials" t:activity="Presentation for Miramonte Early Education Center" m:meetings_held=1 m:antendees=40

series e:4k67-bwgi d:2014-04-25T00:00:00.000Z t:location_or_council_distrct="2830 S. Central Ave., CA  90011" t:category="Community Outreach" t:division="Community Emergency Management" t:purpose="Provided Emergncy Preparedness Materials" t:activity="A Place Called Home Health & Garden Expo" m:materials_distributed=300
```

## Meta Commands

```ls
metric m:materials_distributed p:integer l:"Materials Distributed" t:dataTypeName=number

metric m:meetings_held p:integer l:"Meetings Held" t:dataTypeName=number

metric m:antendees p:integer l:Antendees t:dataTypeName=number

entity e:4k67-bwgi l:"Emergency Management Department ? Community Outreach - Second Quarter 2014" t:url=https://data.lacity.org/api/views/4k67-bwgi

property e:4k67-bwgi t:meta.view v:id=4k67-bwgi v:category="A Safe City" v:averageRating=0 v:name="Emergency Management Department ? Community Outreach - Second Quarter 2014"

property e:4k67-bwgi t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:4k67-bwgi t:meta.view.owner v:id=vnsa-hifw v:profileImageUrlMedium=/api/users/vnsa-hifw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vnsa-hifw/profile_images/LARGE v:screenName="Emergency Management OpenData" v:profileImageUrlSmall=/api/users/vnsa-hifw/profile_images/TINY v:displayName="Emergency Management OpenData"

property e:4k67-bwgi t:meta.view.tableauthor v:id=vnsa-hifw v:profileImageUrlMedium=/api/users/vnsa-hifw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vnsa-hifw/profile_images/LARGE v:screenName="Emergency Management OpenData" v:profileImageUrlSmall=/api/users/vnsa-hifw/profile_images/TINY v:roleName=publisher v:displayName="Emergency Management OpenData"
```

## Top Records

```ls
| activity                                          | date                | purpose                                                          | category           | division                       | location_or_council_distrct                       | materials_distributed | meetings_held | antendees | 
| ================================================= | =================== | ================================================================ | ================== | ============================== | ================================================= | ===================== | ============= | ========= | 
| DMD: West                                         |                     |                                                                  |                    |                                |                                                   |                       |               |           | 
| DMD: CENTRAL                                      |                     |                                                                  |                    |                                |                                                   |                       |               |           | 
| DMD: South                                        |                     |                                                                  |                    |                                |                                                   |                       |               |           | 
| SB CAER Meeting                                   | 2014-04-08T00:00:00 | Attended Monthly Meeting                                         | Community Outreach | Community Emergency Management | Carson Community Center                           |                       | 1             | 15        | 
| Presentation for Miramonte Early Education Center | 2014-04-24T00:00:00 | Conducted presentation with Emergency Preparedness Materials     | Community Outreach | Community Emergency Management | Miramonte Early Education Center, 1341 E. 70th St |                       | 1             | 40        | 
| A Place Called Home Health & Garden Expo          | 2014-04-25T00:00:00 | Provided Emergncy Preparedness Materials                         | Community Outreach | Community Emergency Management | 2830 S. Central Ave., CA 90011                    | 300                   |               |           | 
| Preparedness Materials Request                    | 2014-04-29T00:00:00 | Provided Emergncy Preparedness Materials                         | Community Outreach | Community Emergency Management | Faith Groups Citywide                             | 117                   |               |           | 
| Congresswoman Hahn's Senior Exhibit Briefing      | 2014-05-02T00:00:00 | Participated in Senior Fair with Emergncy Preparedness Materials | Community Outreach | Community Emergency Management | Carson Community Center                           |                       |               | 900       | 
| Area Maritime Security Committee (AMSC)           | 2014-05-07T00:00:00 | Attended Quarterly Meeting                                       | Community Outreach | Community Emergency Management | Port of Los Angeles Admin Building                |                       | 1             | 75        | 
| 1700 Block Club of 42nd Pl                        | 2014-05-10T00:00:00 | Conducted presentation with Emergncy Preparedness Materials      | Community Outreach | Community Emergency Management | CD 8 - Private Residence                          |                       | 1             | 20        | 
```