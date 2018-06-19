# Construction Pipeline

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/construction-pipeline-5ff8f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/iwdd-99mu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/iwdd-99mu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/iwdd-99mu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | iwdd-99mu |
| Name | Construction Pipeline |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | construction pipeline |
| Created | 2016-04-22T17:28:01Z |
| Publication Date | 2016-04-22T21:46:42Z |

## Description

Pursuant to  312(a) of the City Charter, as amended by Local Law 63 of 2011, the Mayor's Office is required to publish a plan and schedule for each City agency detailing the anticipated contracting actions of each agency for the upcoming fiscal year for certain categories of procurement.

## Columns

```ls
| Included | Schema Type | Field Name                         | Name                                 | Data Type | Render Type |
| ======== | =========== | ================================== | ==================================== | ========= | =========== |
| No       | time        | :updated_at                        | updated_at                           | meta_data | meta_data   |
| No       |             | estimated_bid_date                 | Estimated Bid Date                   | text      | text        |
| Yes      | series tag  | agency                             | Agency                               | text      | text        |
| Yes      | series tag  | agency_unit                        | Agency Unit                          | text      | text        |
| Yes      | series tag  | trade_s                            | Trade(s)                             | text      | text        |
| Yes      | series tag  | project_description                | Project Description                  | text      | text        |
| Yes      | series tag  | award_method                       | Award Method                         | text      | text        |
| Yes      | series tag  | project_id                         | Project ID                           | text      | text        |
| Yes      | series tag  | epin                               | EPIN                                 | text      | text        |
| Yes      | series tag  | engineer_s_estimate_amount_in_000s | Engineer's Estimate (Amount in 000s) | text      | text        |
| Yes      | series tag  | status_of_bid                      | Status of Bid                        | text      | text        |
| Yes      | series tag  | borough_of_work_bronx              | Borough of Work - Bronx              | text      | text        |
| Yes      | series tag  | borough_of_work_brooklyn           | Borough of Work -Brooklyn            | text      | text        |
| Yes      | series tag  | borough_of_work_manhattan          | Borough of Work -Manhattan           | text      | text        |
| Yes      | series tag  | borough_of_work_queens             | Borough of Work -Queens              | text      | text        |
| Yes      | series tag  | borough_of_work_staten_island      | Borough of Work -Staten Island       | text      | text        |
| Yes      | series tag  | borough_of_work_upstate            | Borough of Work -Upstate             | text      | text        |
| Yes      | series tag  | pre_bid_meeting_y_n                | Pre-bid Meeting? (Y/N)               | text      | text        |
| Yes      | series tag  | subject_to_ll1_y_n                 | Subject to LL1? (Y/N)                | text      | text        |
| Yes      | series tag  | federal_or_state_goals             | Federal or State Goals?              | text      | text        |
| Yes      | series tag  | is_apprenticeship_required_y_n     | Is Apprenticeship Required? (Y/N)    | text      | text        |
| Yes      | series tag  | subject_to_a_pla_y_n               | Subject to a PLA? (Y/N)              | text      | text        |
| Yes      | series tag  | subject_to_damages_for_delay       | Subject to Damages for Delay?        | text      | text        |
| Yes      | series tag  | onenyc_y_n                         | OneNYC? (Y/N)                        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = estimated_bid_date
```

## Data Commands

```ls
series e:iwdd-99mu d:2016-04-22T14:45:08.000Z t:onenyc_y_n=No t:status_of_bid=Pre-Solicitation t:epin=85005P0011 t:subject_to_a_pla_y_n=No t:agency=DDC t:award_method="Competitive Sealed Bid" t:subject_to_ll1_y_n=Yes t:engineer_s_estimate_amount_in_000s=7,828 t:agency_unit=INFRASTRUCTURE t:project_description="VICTORY BLVD & MANOR ROAD INTERSECTION IMPROVEMENT" t:borough_of_work_staten_island=X t:trade_s=Construction t:is_apprenticeship_required_y_n=Yes t:subject_to_damages_for_delay=Yes t:project_id=HWR00505 t:pre_bid_meeting_y_n=Yes m:row_number.iwdd-99mu=1

series e:iwdd-99mu d:2016-04-22T14:45:08.000Z t:onenyc_y_n=No t:status_of_bid=Pre-Solicitation t:epin=85005P0011 t:subject_to_a_pla_y_n=No t:agency=DDC t:award_method="Competitive Sealed Bid" t:subject_to_ll1_y_n=Yes t:engineer_s_estimate_amount_in_000s=5,324 t:agency_unit=INFRASTRUCTURE t:project_description="INTERSECTION IMPROVEMENT VICTORY BLVD & CLOVE ROAD" t:borough_of_work_staten_island=X t:trade_s=Construction t:is_apprenticeship_required_y_n=Yes t:subject_to_damages_for_delay=Yes t:project_id=HWR00504 t:pre_bid_meeting_y_n=Yes m:row_number.iwdd-99mu=2

series e:iwdd-99mu d:2016-04-22T14:45:08.000Z t:onenyc_y_n=No t:status_of_bid=Pre-Solicitation t:epin=85007S0008 t:subject_to_a_pla_y_n=No t:agency=DDC t:award_method="Competitive Sealed Bid" t:subject_to_ll1_y_n=Yes t:agency_unit=INFRASTRUCTURE t:engineer_s_estimate_amount_in_000s="100 - 500" t:project_description="BRONX ZOOWAY STREETSCAPE PHASE II" t:trade_s=CONSTRUCTION t:is_apprenticeship_required_y_n=Yes t:subject_to_damages_for_delay=Yes t:project_id=HWXD203 t:borough_of_work_bronx=X t:pre_bid_meeting_y_n=Yes m:row_number.iwdd-99mu=3
```

## Meta Commands

```ls
metric m:row_number.iwdd-99mu p:long l:"Row Number"

entity e:iwdd-99mu l:"Construction Pipeline" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/iwdd-99mu

property e:iwdd-99mu t:meta.view v:id=iwdd-99mu v:category="City Government" v:averageRating=0 v:name="Construction Pipeline" v:attribution="Office of the Mayor (OTM)"

property e:iwdd-99mu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:iwdd-99mu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | estimated_bid_date | agency | agency_unit      | trade_s                  | project_description                                                                       | award_method           | project_id | epin       | engineer_s_estimate_amount_in_000s | status_of_bid    | borough_of_work_bronx | borough_of_work_brooklyn | borough_of_work_manhattan | borough_of_work_queens | borough_of_work_staten_island | borough_of_work_upstate | pre_bid_meeting_y_n | subject_to_ll1_y_n | federal_or_state_goals | is_apprenticeship_required_y_n | subject_to_a_pla_y_n | subject_to_damages_for_delay | onenyc_y_n | 
| =========== | ================== | ====== | ================ | ======================== | ========================================================================================= | ====================== | ========== | ========== | ================================== | ================ | ===================== | ======================== | ========================= | ====================== | ============================= | ======================= | =================== | ================== | ====================== | ============================== | ==================== | ============================ | ========== | 
| 1461336308  | July - Sept 15     | DDC    | INFRASTRUCTURE   | Construction             | VICTORY BLVD & MANOR ROAD INTERSECTION IMPROVEMENT                                        | Competitive Sealed Bid | HWR00505   | 85005P0011 | 7,828                              | Pre-Solicitation |                       |                          |                           |                        | X                             |                         | Yes                 | Yes                |                        | Yes                            | No                   | Yes                          | No         | 
| 1461336308  | July - Sept 15     | DDC    | INFRASTRUCTURE   | Construction             | INTERSECTION IMPROVEMENT VICTORY BLVD & CLOVE ROAD                                        | Competitive Sealed Bid | HWR00504   | 85005P0011 | 5,324                              | Pre-Solicitation |                       |                          |                           |                        | X                             |                         | Yes                 | Yes                |                        | Yes                            | No                   | Yes                          | No         | 
| 1461336308  | July -Sept 15      | DDC    | INFRASTRUCTURE   | CONSTRUCTION             | BRONX ZOOWAY STREETSCAPE PHASE II                                                         | Competitive Sealed Bid | HWXD203    | 85007S0008 | 100 - 500                          | Pre-Solicitation | X                     |                          |                           |                        |                               |                         | Yes                 | Yes                |                        | Yes                            | No                   | Yes                          | No         | 
| 1461336308  | Oct -Dec 15        | DDC    | INFRASTRUCTURE   | Construction             | CHESTER AVENUE, STATEN ISLAND (W/SE-761)                                                  | Competitive Sealed Bid | SE-751     |            | 12,541                             | Pre-Solicitation |                       |                          |                           |                        | X                             |                         | Yes                 | Yes                |                        | Yes                            | No                   | Yes                          | No         | 
| 1461336308  | Oct -Dec 15        | DDC    | INFRASTRUCTURE   | Construction             | REPLACE WATER MAIN: EAST 46TH AND 47TH STREETS BETWEEN MADISON AND LEXINGTON AVENUES      | Competitive Sealed Bid | MED594     |            | 7,030                              | Pre-Solicitation |                       |                          | X                         |                        |                               |                         | Yes                 | Yes                |                        | Yes                            | No                   | Yes                          | No         | 
| 1461336308  | Oct -Dec 15        | DDC    | INFRASTRUCTURE   | CONSTRUCTION             | MORRIS ST. PEDESTRIAN BRIDGE REPLACEMENT                                                  | Competitive Sealed Bid | HBPEDMRS   |            | 10,938                             | Pre-Solicitation |                       |                          | X                         |                        |                               |                         | No                  | Yes                |                        | Yes                            | No                   | Yes                          | No         | 
| 1461336308  | Oct -Dec 15        | DDC    | INFRASTRUCTURE   | CONSTRUCTION             | Montefiore Park & Plaza Improvement (MED-629)                                             | Competitive Sealed Bid | HWPLZ003M  |            | 8,610                              | Pre-Solicitation |                       |                          | X                         |                        |                               |                         | No                  | Yes                |                        | Yes                            | No                   | Yes                          | No         | 
| 1461336308  | Oct - Dec 15       | DDC    | PUBLIC BUILDINGS | Plumbing, HVAC, Elec, GC | NYPD 84th Precinct & BK N Narc Div, Bklyn - EE Upg                                        | Competitive Sealed Bid | E12-0043   |            | 1,112                              | Pre-Solicitation |                       | X                        |                           |                        |                               |                         | No                  | Yes                |                        | No                             | Yes                  | Yes                          | No         | 
| 1461336308  | Jan -Mar 16        | DDC    | INFRASTRUCTURE   | Construction             | WIDEN ROADWAY AND PERFORM RELATED WORK: AMBOY ROAD BETWEEN RICHMOND AND ARMSTRONG AVENUES | Competitive Sealed Bid | HWR00508   |            | 4,842                              | Pre-Solicitation |                       |                          |                           |                        | X                             |                         | Yes                 | Yes                |                        | Yes                            | No                   | Yes                          | No         | 
| 1461336308  | Jan -Mar 16        | DDC    | INFRASTRUCTURE   | CONSTRUCTION             | RETAINING WALL-HIGHLAND BLVD E/B BEFORE J.ROBINSON                                        | Competitive Sealed Bid | RWK013     |            | 1,089                              | Pre-Solicitation |                       | X                        |                           |                        |                               |                         | No                  | Yes                |                        | Yes                            | No                   | Yes                          | No         | 
```