# WDFW-Hatchery Reform & Challenges

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wdfw-hatchery-reform-challenges-93b2f) |
| Metadata | [Link](https://data.wa.gov/api/views/yad4-zsfv) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/yad4-zsfv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/yad4-zsfv/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | yad4-zsfv |
| Name | WDFW-Hatchery Reform & Challenges |
| Attribution | Washington Department of Fish and Wildlife |
| Category | Natural Resources & Environment |
| Tags | wdfw, hatcheries, salmon |
| Created | 2013-07-31T00:05:20Z |
| Publication Date | 2013-08-16T00:30:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                      | Data Type | Render Type |
| ======== | ============== | ================== | ========================= | ========= | =========== |
| No       | time           | :updated_at        | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | facility_name      | Facility Name             | text      | text        |
| Yes      | series tag     | action_needed      | Action Needed             | text      | text        |
| Yes      | series tag     | action_needed_desc | Action Needed Description | text      | text        |
| Yes      | series tag     | fund_source        | Fund Source               | text      | text        |
| Yes      | series tag     | schedule           | Schedule                  | text      | text        |
| Yes      | numeric metric | costs              | Costs                     | number    | number      |
| Yes      | series tag     | costs_notes        | Costs Notes               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yad4-zsfv d:2013-07-30T17:08:26.000Z t:schedule=2009/Complete t:fund_source="Federal (M.A.)" t:facility_name="Beaver Creek Hatchery" t:action_needed_desc="Set up vertical incubation for fall Chinook" t:action_needed="Facility Improvement" m:costs=5000

series e:yad4-zsfv d:2013-07-30T17:08:26.000Z t:schedule=2009 t:fund_source="Federal (M.A.)" t:facility_name="Beaver Creek Hatchery" t:action_needed_desc="Repair bird netting around raceways and install bird netting on the rearing pond" t:action_needed="Facility Improvement" m:costs=15000

series e:yad4-zsfv d:2013-07-30T17:08:26.000Z t:schedule=2009 t:fund_source="Federal (M.A.)" t:facility_name="Beaver Creek Hatchery" t:action_needed_desc="Repair rearing pond docks" t:action_needed="Facility Improvement" m:costs=5000
```

## Meta Commands

```ls
metric m:costs p:integer l:Costs d:"Estimated Major Reform/Renovation Costs: Results of 2004 review of hatchery facilities; HAIP-Hatchery Action Imp Plans documentation; GAUOBogden Report 2004 includes: Prevent pollutant contamination, HSRG projects, keep hatchery operational." t:dataTypeName=number

entity e:yad4-zsfv l:"WDFW-Hatchery Reform & Challenges" t:attribution="Washington Department of Fish and Wildlife" t:url=https://data.wa.gov/api/views/yad4-zsfv

property e:yad4-zsfv t:meta.view v:id=yad4-zsfv v:category="Natural Resources & Environment" v:attributionLink=http://wdfw.wa.gov/score v:averageRating=0 v:name="WDFW-Hatchery Reform & Challenges" v:attribution="Washington Department of Fish and Wildlife"

property e:yad4-zsfv t:meta.view.owner v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:displayName="WDFW Data"

property e:yad4-zsfv t:meta.view.tableauthor v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:roleName=publisher v:displayName="WDFW Data"
```

## Top Records

```ls
| :updated_at | facility_name          | action_needed            | action_needed_desc                                                               | fund_source    | schedule      | costs  | costs_notes | 
| =========== | ====================== | ======================== | ================================================================================ | ============== | ============= | ====== | =========== | 
| 1375204106  | Beaver Creek Hatchery  | Facility Improvement     | Set up vertical incubation for fall Chinook                                      | Federal (M.A.) | 2009/Complete | 5000   |             | 
| 1375204106  | Beaver Creek Hatchery  | Facility Improvement     | Repair bird netting around raceways and install bird netting on the rearing pond | Federal (M.A.) | 2009          | 15000  |             | 
| 1375204106  | Beaver Creek Hatchery  | Facility Improvement     | Repair rearing pond docks                                                        | Federal (M.A.) | 2009          | 5000   |             | 
| 1375204106  | Beaver Creek Hatchery  | Facility Improvement     | Repair bridge to rearing pond                                                    | Federal (M.A.) | 2009          | 5000   |             | 
| 1375204106  | Beaver Creek Hatchery  | Environmental Compliance | Repair B.C. barrier dam and fish ladder/collection facilities                    | Federal (M.A.) | 2010          | 870000 |             | 
| 1375204106  | Beaver Creek Hatchery  | Facility Improvement     | Replace domestic water transfer system                                           | Federal (M.A.) | 2011          |        | TBD         | 
| 1375204106  | Beaver Creek Hatchery  | Facility Improvement     | Upgrade fish collection facility                                                 | Federal (M.A.) | 2011          |        | TBD         | 
| 1375204106  | Beaver Creek Hatchery  | Facility Improvement     | Replace hatchery residence roofs                                                 | Federal (M.A.) | 2011          |        | TBD         | 
| 1375204106  | Bingham Creek Hatchery |                          | Replace concrete ponds                                                           |                |               |        |             | 
| 1375204106  | Bingham Creek Hatchery |                          | Upgrade adult handling facility                                                  |                |               |        |             | 
```