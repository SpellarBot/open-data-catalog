# Emergency Management Department - Community Outreach - 1st Quarter 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/emergency-management-department-community-outreach-1st-quarter-2015) |
| Metadata | [Link](https://data.lacity.org/api/views/iz9s-qc6r) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/iz9s-qc6r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/iz9s-qc6r/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | iz9s-qc6r |
| Name | Emergency Management Department - Community Outreach - 1st Quarter 2015 |
| Category | A Safe City |
| Tags | emergency management, emergency preparedness |
| Created | 2015-05-27T16:51:36Z |
| Publication Date | 2015-05-27T17:01:37Z |

## Description

Community outreach activities conducted by the Community Emergency Management Division of Emergency Management Department for the period of January-March 2015.

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
series e:iz9s-qc6r d:2015-01-22T00:00:00.000Z t:location_or_council_distrct="Southern Baptist Church
14055 Van Nuys Blvd,
Pacoima, CA" t:category="Community Outreach" t:division="Community Emergency Mgmt" t:purpose=Meeting t:activity="Churches for Action Meeting" m:meetings_held=1 m:antendees=15

series e:iz9s-qc6r d:2015-02-04T00:00:00.000Z t:location_or_council_distrct="Port of Long Beach
4801 East Spring St.,
Long Beach, CA" t:category="Community Outreach" t:division="Community Emergency Mgmt" t:purpose=Meeting t:activity="AMSC Meeting" m:meetings_held=1 m:antendees=75

series e:iz9s-qc6r d:2015-02-09T00:00:00.000Z t:location_or_council_distrct="Church of Scientology
8038 S. Vermont Ave,
LA, CA, 90044" t:category="Community Outreach" t:division="Community Emergency Mgmt" t:purpose=Meeting t:activity="Los Angeles Interfaith Clergy Coalition
Monthly Meeting" m:meetings_held=1 m:antendees=10
```

## Meta Commands

```ls
metric m:materials_distributed p:integer l:"Materials Distributed" t:dataTypeName=number

metric m:meetings_held p:integer l:"Meetings Held" t:dataTypeName=number

metric m:antendees p:integer l:Antendees t:dataTypeName=number

entity e:iz9s-qc6r l:"Emergency Management Department - Community Outreach - 1st Quarter 2015" t:url=https://data.lacity.org/api/views/iz9s-qc6r

property e:iz9s-qc6r t:meta.view v:id=iz9s-qc6r v:category="A Safe City" v:averageRating=0 v:name="Emergency Management Department - Community Outreach - 1st Quarter 2015"

property e:iz9s-qc6r t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:iz9s-qc6r t:meta.view.owner v:id=vnsa-hifw v:profileImageUrlMedium=/api/users/vnsa-hifw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vnsa-hifw/profile_images/LARGE v:screenName="Emergency Management OpenData" v:profileImageUrlSmall=/api/users/vnsa-hifw/profile_images/TINY v:displayName="Emergency Management OpenData"

property e:iz9s-qc6r t:meta.view.tableauthor v:id=vnsa-hifw v:profileImageUrlMedium=/api/users/vnsa-hifw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vnsa-hifw/profile_images/LARGE v:screenName="Emergency Management OpenData" v:profileImageUrlSmall=/api/users/vnsa-hifw/profile_images/TINY v:roleName=publisher v:displayName="Emergency Management OpenData"
```

## Top Records

```ls
| activity                                                | date                | purpose           | category           | division                 | location_or_council_distrct                                 | materials_distributed | meetings_held | antendees | 
| ======================================================= | =================== | ================= | ================== | ======================== | =========================================================== | ===================== | ============= | ========= | 
| DMD: South                                              |                     |                   |                    |                          |                                                             |                       |               |           | 
| Churches for Action Meeting                             | 2015-01-22T00:00:00 | Meeting           | Community Outreach | Community Emergency Mgmt | Southern Baptist Church 14055 Van Nuys Blvd, Pacoima, CA    |                       | 1             | 15        | 
| AMSC Meeting                                            | 2015-02-04T00:00:00 | Meeting           | Community Outreach | Community Emergency Mgmt | Port of Long Beach 4801 East Spring St., Long Beach, CA     |                       | 1             | 75        | 
| Los Angeles Interfaith Clergy Coalition Monthly Meeting | 2015-02-09T00:00:00 | Meeting           | Community Outreach | Community Emergency Mgmt | Church of Scientology 8038 S. Vermont Ave, LA, CA, 90044    |                       | 1             | 10        | 
| USC Emergency Preparedness Symposium and Vendor Fair    | 2015-02-20T00:00:00 | Preparedness Fair | Community Outreach | Community Emergency Mgmt | USC Campus                                                  | 200                   |               | 250       | 
| Los Angeles Interfaith Clergy Coalition Monthly Meeting | 2015-03-09T00:00:00 | Meeting           | Community Outreach | Community Emergency Mgmt | Church of Scientology 8038 S. Vermont Ave, LA, CA, 90044    |                       | 1             | 20        | 
| Churches for Action Meeting                             | 2015-03-19T00:00:00 | Meeting           | Community Outreach | Community Emergency Mgmt | Councilman Curren Price's Office 4301 S. Central Ave., LA   |                       | 1             | 20        | 
| Price Chapel AME Church                                 | 2015-03-26T00:00:00 | Presentation      | Community Outreach | Community Emergency Mgmt | Price Chapel AME 4000 W. Slauson Ave. Los Angeles, CA 90043 | 80                    |               | 60        | 
| DMD: West                                               |                     |                   | Community Outreach | Community Emergency Mgmt |                                                             |                       |               |           | 
| Westside Center for Independent Living                  | 2015-03-27T00:00:00 | Booth             | Community Outreach | Community Emergency Mgmt | 12901 Venice Boulevard, L.A. CA 90066                       |                       |               |           | 
```