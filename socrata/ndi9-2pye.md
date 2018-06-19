# Transit communities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transit-communities-fa210) |
| Metadata | [Link](https://data.seattle.gov/api/views/ndi9-2pye) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/ndi9-2pye/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/ndi9-2pye/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | ndi9-2pye |
| Name | Transit communities |
| Category | Transportation |
| Created | 2011-02-14T19:50:08Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Columns

```ls
| Included | Schema Type | Field Name              | Name                      | Data Type | Render Type |
| ======== | =========== | ======================= | ========================= | ========= | =========== |
| No       | time        | :updated_at             | updated_at                | meta_data | meta_data   |
| Yes      | series tag  | name                    | Name                      | text      | text        |
| Yes      | series tag  | typology                | Typology                  | text      | text        |
| Yes      | series tag  | current_conditions      | Current Conditions        | text      | text        |
| Yes      | series tag  | future_needs_priorities | Future Needs & Priorities | text      | text        |
| Yes      | series tag  | district                | District                  | text      | text        |
| Yes      | series tag  | neighborhood_plan       | Neighborhood Plan         | url       | url         |
| Yes      | series tag  | status_check            | Status Check              | url       | url         |
| Yes      | series tag  | city_planning           | City Planning             | url       | url         |
| Yes      | series tag  | major_transit_project   | Major Transit project?    | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ndi9-2pye d:2011-02-14T11:50:11.000Z t:typology="Mixed Use Center future" t:status_check=http://www.seattle.gov/planningcommission/docs/UniversityCommunityExecSummary.pdf t:district=Northeast t:name="University District" t:major_transit_project=http://projects.soundtransit.org/Projects-Home/North-Link/Brooklyn-Station.xml t:current_conditions="Has a core employment population" t:neighborhood_plan=http://www.seattle.gov/neighborhoods/npi/plans/university/ m:row_number.ndi9-2pye=1

series e:ndi9-2pye d:2011-02-14T11:50:11.000Z t:city_planning=http://www.seattle.gov/dpd/Planning/BallardURV/Overview/default.asp t:typology="Mixed use Center local" t:status_check=http://www.seattle.gov/planningcommission/docs/CHBExecSummary.pdf t:district=Ballard t:name=Ballard t:future_needs_priorities="Ballard is a “new urban center” Combine districts keeping identities separate" t:major_transit_project=http://www.kingcounty.gov/transportation/kcdot/MetroTransit/RapidRide/DLine.aspx t:current_conditions="High population, S edge is industrial" t:neighborhood_plan=http://www.seattle.gov/neighborhoods/npi/plans/chill/ m:row_number.ndi9-2pye=2

series e:ndi9-2pye d:2011-02-14T11:50:11.000Z t:city_planning=http://www.seattle.gov/dpd/Planning/FremontUrbanVillageRezone/Overview/default.asp t:typology="Mixed Use Center local" t:status_check=http://www.seattle.gov/planningcommission/docs/FremontExecSummary.pdf t:district="Lake Union" t:name=Fremont t:current_conditions="24 hr neighborhood" t:neighborhood_plan=http://www.seattle.gov/neighborhoods/npi/plans/fremont/ m:row_number.ndi9-2pye=3
```

## Meta Commands

```ls
metric m:row_number.ndi9-2pye p:long l:"Row Number"

entity e:ndi9-2pye l:"Transit communities" t:url=https://data.seattle.gov/api/views/ndi9-2pye

property e:ndi9-2pye t:meta.view d:2017-09-25T07:25:45.257Z v:averageRating=0 v:name="Transit communities" v:id=ndi9-2pye v:category=Transportation

property e:ndi9-2pye t:meta.view.owner d:2017-09-25T07:25:45.257Z v:displayName="Seattle IT" v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:id=pfbu-yuv5 v:screenName="Seattle IT" v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB

property e:ndi9-2pye t:meta.view.tableauthor d:2017-09-25T07:25:45.257Z v:displayName="Seattle IT" v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:id=pfbu-yuv5 v:screenName="Seattle IT" v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | name                                                | typology                  | current_conditions                                                                                                                    | future_needs_priorities                                                       | district   | neighborhood_plan                                                  | status_check                                                                              | city_planning                                                                                                                       | major_transit_project                                                                    | 
| =========== | =================================================== | ========================= | ===================================================================================================================================== | ============================================================================= | ========== | ================================================================== | ========================================================================================= | =================================================================================================================================== | ======================================================================================== | 
| 1297684211  | University District                                 | Mixed Use Center future   | Has a core employment population                                                                                                      |                                                                               | Northeast  | [http://www.seattle.gov/neighborhoods/npi/plans/university/, null] | [http://www.seattle.gov/planningcommission/docs/UniversityCommunityExecSummary.pdf, null] | [null, null]                                                                                                                        | [http://projects.soundtransit.org/Projects-Home/North-Link/Brooklyn-Station.xml, null]   | 
| 1297684211  | Ballard                                             | Mixed use Center local    | High population, S edge is industrial                                                                                                 | Ballard is a “new urban center” Combine districts keeping identities separate | Ballard    | [http://www.seattle.gov/neighborhoods/npi/plans/chill/, null]      | [http://www.seattle.gov/planningcommission/docs/CHBExecSummary.pdf, null]                 | [http://www.seattle.gov/dpd/Planning/BallardURV/Overview/default.asp, null]                                                         | [http://www.kingcounty.gov/transportation/kcdot/MetroTransit/RapidRide/DLine.aspx, null] | 
| 1297684211  | Fremont                                             | Mixed Use Center local    | 24 hr neighborhood                                                                                                                    |                                                                               | Lake Union | [http://www.seattle.gov/neighborhoods/npi/plans/fremont/, null]    | [http://www.seattle.gov/planningcommission/docs/FremontExecSummary.pdf, null]             | [http://www.seattle.gov/dpd/Planning/FremontUrbanVillageRezone/Overview/default.asp, null]                                          | [null, null]                                                                             | 
| 1297684211  | Campus Parkway - combined with University District? | Mixed Use Center regional | Major gateway to UW with many admin buildings and libraries; also some medical areas to the south along Pacific; numerous dormatories | Focus on this district being a transit node with minor MUC-R                  | Northeast  | [null, null]                                                       | [null, null]                                                                              | [null, null]                                                                                                                        | [null, null]                                                                             | 
| 1297684211  | Northgate                                           | Mixed Use Center regional | Regional draw; medical and retail employment center                                                                                   |                                                                               | North      | [http://www.seattle.gov/neighborhoods/npi/plans/northgate/, null]  | [null, null]                                                                              | [http://www.seattle.gov/DPD/Planning/Northgate_Revitalization/Overview/, null]                                                      | [http://projects.soundtransit.org/Projects-Home/North-Link/Northgate-Station.xml, null]  | 
| 1297684211  | Broadview                                           | Mixed Use Neighborhood    | Consider renaming this district                                                                                                       | May become a MUC-L if it is served by fixed rail in the future                | Northwest  | [http://www.seattle.gov/neighborhoods/npi/plans/broadview/, null]  | [http://www.seattle.gov/planningcommission/docs/BBLHLExecSummary.pdf, null]               | [http://www.seattle.gov/dpd/Planning/Neighborhood_Planning/NeighborhoodPlanUpdates/BroadviewBitterLakeHallerLake/default.asp, null] | [http://www.kingcounty.gov/transportation/kcdot/MetroTransit/RapidRide/ELine.aspx, null] | 
| 1297684211  | Crown Hill                                          | Mixed Use Neighborhood    | Large format parcels                                                                                                                  |                                                                               | Ballard    | [http://www.seattle.gov/neighborhoods/npi/plans/chill/, null]      | [http://www.seattle.gov/planningcommission/docs/CHBExecSummary.pdf, null]                 | [null, null]                                                                                                                        | [http://www.kingcounty.gov/transportation/kcdot/MetroTransit/RapidRide/DLine.aspx, null] | 
| 1297684211  | Greenwood                                           | Mixed Use Neighborhood    | Large format parcels and developments; walkability exists                                                                             | Potential for more residential                                                | Northwest  | [http://www.seattle.gov/neighborhoods/npi/plans/greenwood/, null]  | [http://www.seattle.gov/planningcommission/docs/GPRExecSummary.pdf, null]                 | [http://www.seattle.gov/dpd/Planning/GreenwoodRezone/Overview/default.asp, null]                                                    | [null, null]                                                                             | 
| 1297684211  | Lake City                                           | Mixed Use Neighborhood    | Predominantly residential                                                                                                             |                                                                               | North      | [http://www.seattle.gov/neighborhoods/npi/plans/north/, null]      | [http://www.seattle.gov/planningcommission/docs/LakeCityExecSummary.pdf, null]            | [null, null]                                                                                                                        | [null, null]                                                                             | 
| 1297684211  | North Green Lake                                    | Mixed Use Neighborhood    |                                                                                                                                       | Expand district to the south.                                                 | Northwest  | [http://www.seattle.gov/neighborhoods/npi/plans/aurlict/, null]    | [http://www.seattle.gov/planningcommission/docs/ALSExecSummary.pdf, null]                 | [http://www.seattle.gov/dpd/Planning/Aurora/Overview/, null]                                                                        | [http://www.kingcounty.gov/transportation/kcdot/MetroTransit/RapidRide/ELine.aspx, null] | 
```