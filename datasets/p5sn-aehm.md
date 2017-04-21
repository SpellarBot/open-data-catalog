# Public Works CIP Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-works-cip-projects) |
| Metadata | [Link](https://data.hartford.gov/api/views/p5sn-aehm) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/p5sn-aehm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/p5sn-aehm/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | p5sn-aehm |
| Name | Public Works CIP Projects |
| Attribution | City of Hartford |
| Category | Community |
| Tags | cip, projects, public works |
| Created | 2014-04-27T22:44:58Z |
| Publication Date | 2015-04-26T07:25:52Z |

## Description

Public Works Capital Improvement Projects. Updated nightly

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | project_name    | Project Name    | text      | text        |
| No       |                | address         | Address         | text      | text        |
| Yes      | series tag     | lsni_district   | LSNI District   | text      | text        |
| Yes      | series tag     | department      | Department      | text      | text        |
| Yes      | series tag     | dpw_project_num | DPW Project Num | text      | text        |
| Yes      | series tag     | currrent_status | Currrent Status | text      | text        |
| Yes      | series tag     | next_step       | Next Step       | text      | text        |
| Yes      | series tag     | project_scope   | Project Scope   | text      | text        |
| Yes      | numeric metric | project_funding | Project Funding | money     | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:p5sn-aehm d:2015-04-26T00:25:29.000Z t:lsni_district=West t:project_name="Farmington Avenue Streetscape" t:dpw_project_num=E01-07G t:department="Public Works" t:next_step=Construction t:project_scope="Streetscape improvements on Farmington Ave between Marshall & Sherman.  Improvements consist of clay brick pavers, new granite curb, decorative lighting and signal work." t:currrent_status=Design m:project_funding=6466837.86

series e:p5sn-aehm d:2015-04-26T00:25:29.000Z t:lsni_district=CityWide t:project_name="Flood Control - North and South Pond Dredging" t:dpw_project_num=DPW12-21 t:department="Public Works" t:next_step="Close Out" t:project_scope="Dredging of the North and South Meadows Ponds, Construction of sediment forebays & Various site improvements at each site." t:currrent_status="Close Out" m:project_funding=3888282

series e:p5sn-aehm d:2015-04-26T00:25:29.000Z t:lsni_district="City Wide" t:project_name="Traffic Signal & Camera Upgrade & Replacement" t:department="Public Works" m:project_funding=2500000
```

## Meta Commands

```ls
metric m:project_funding p:long l:"Project Funding" t:dataTypeName=money

entity e:p5sn-aehm l:"Public Works CIP Projects" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/p5sn-aehm

property e:p5sn-aehm t:meta.view v:id=p5sn-aehm v:category=Community v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Public Works CIP Projects" v:attribution="City of Hartford"

property e:p5sn-aehm t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:p5sn-aehm t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:p5sn-aehm t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| :updated_at | project_name                                   | address                                   | lsni_district | department   | dpw_project_num | currrent_status | next_step    | project_scope                                                                                                                                                                                                                                                                               | project_funding | 
| =========== | ============================================== | ========================================= | ============= | ============ | =============== | =============== | ============ | =========================================================================================================================================================================================================================================================================================== | =============== | 
| 1430007929  | Farmington Avenue Streetscape                  | Farmington Avenue                         | West          | Public Works | E01-07G         | Design          | Construction | Streetscape improvements on Farmington Ave between Marshall & Sherman. Improvements consist of clay brick pavers, new granite curb, decorative lighting and signal work.                                                                                                                    | $6,466,837.86   | 
| 1430007929  | Retreat Avenue                                 | Retreat Avenue                            | Central       | Public Works |                 | Design          | Construction | This is a collaborative effort between the City and Hartford Hospital to provide traffic calming along the length of Retreat Avenue. The City has already installed traffic islands at each end of the street. Hartford Hospital has retained a consultant to design the remaining portion. |                 | 
| 1430007929  | Park Ponds Restoration - Pope                  | Pope Park Pond                            | West          | Public Works | DPW12-35A       | Design          | Out to Bid   | This project consists of designing the dredging of Goodwin Park Pond and Pope Park Pond. Based on the preliminary design estimates the decision has been made to proceed with the lowest cost option which is dredging Pope Park Pond only (Design plans will be finalized for both ponds)  |                 | 
| 1430007929  | Flood Control - North and South Pond Dredging  | North & South Meadows Pump Station Ponds. | CityWide      | Public Works | DPW12-21        | Close Out       | Close Out    | Dredging of the North and South Meadows Ponds, Construction of sediment forebays & Various site improvements at each site.                                                                                                                                                                  | $3,888,282.00   | 
| 1430007929  | Firehouse #11                                  | 150 Sisson Avenue                         | West          | Public Works | DPW14-09        | Predesign       | Predesign    | Scope to be determined; Either complete renovation or demolish and replace.                                                                                                                                                                                                                 |                 | 
| 1430007929  | Fairfield Ave. Traffic Calming Study           | Fairfield Avenue                          | South         | Public Works |                 |                 |              |                                                                                                                                                                                                                                                                                             |                 | 
| 1430007929  | Wethersfield Avenue Streetscapes               | Wethersfield Avenue                       | South         | Public Works | DPW14-04        |                 |              |                                                                                                                                                                                                                                                                                             |                 | 
| 1430007929  | Asylum Hill Neighborhood Traffic Calming Study | Asylum                                    | West          | Public Works |                 |                 |              |                                                                                                                                                                                                                                                                                             |                 | 
| 1430007929  | Park Ponds Restoration (Bushnell)              | Bushnell Park Pond                        | Central       | Public Works | DPW12-35B       |                 |              |                                                                                                                                                                                                                                                                                             |                 | 
| 1430007929  | Design & Repair of City Bridges (New Park Ave) | New Park Avenue                           | West          | Public Works | DPW14-22B       |                 |              |                                                                                                                                                                                                                                                                                             |                 | 
```