# Weekly Community Improvement Numbers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/weekly-community-improvement-numbers) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/6d4u-fgst) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/6d4u-fgst/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/6d4u-fgst/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | 6d4u-fgst |
| Name | Weekly Community Improvement Numbers |
| Attribution | City of Jackson - Police Department |
| Category | Community Development |
| Tags | community, neighborhood associations, connected, city of jackson, super neighborhood, citizen engagement, city hall, constituent services, community improvement |
| Created | 2016-03-23T15:03:39Z |
| Publication Date | 2017-03-10T21:09:59Z |

## Description

This data is comprised of all the community improvement activities carried out throughout the City. This information is updated weekly.

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                          | Data Type     | Render Type   |
| ======== | ============== | ============================================= | ============================================= | ============= | ============= |
| Yes      | time           | week_reported                                 | Week Reported                                 | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_inspections                         | Number of Inspections                         | number        | number        |
| Yes      | numeric metric | number_of_hearing_notices_mailed              | Number of Hearing Notices Mailed              | number        | number        |
| Yes      | numeric metric | number_of_cases_presented_to_hearing_officers | Number of Cases Presented to Hearing Officers | number        | number        |
| Yes      | numeric metric | number_of_311_complaints_received             | Number of 311 Complaints Received             | number        | number        |
| Yes      | numeric metric | number_of_311_complaints_resolved             | Number of 311 Complaints Resolved             | number        | number        |
| Yes      | numeric metric | number_of_initiated_demolition_cases          | Number of Initiated Demolition Cases          | number        | number        |
| Yes      | numeric metric | number_of_demolition_cases_completed          | Number of Demolition Cases Completed          | number        | number        |
| Yes      | numeric metric | number_of_initiated_board_up_cases            | Number of Initiated Board Up Cases            | number        | number        |
| Yes      | numeric metric | number_of_board_up_cases_completed            | Number of Board Up Cases completed            | number        | number        |
| Yes      | numeric metric | number_of_initiated_grass_and_weed_cases      | Number of Initiated Grass and Weed Cases      | number        | number        |
| Yes      | numeric metric | number_of_grass_and_weed_casses_completed     | Number of Grass and Weed Casses Completed     | number        | number        |
| Yes      | numeric metric | number_of_housing_inspections                 | Number of Housing Inspections                 | number        | number        |
| Yes      | numeric metric | number_of_lots_completed_by_inmate_labor      | Number of Lots Completed by Inmate Labor      | number        | number        |
| Yes      | numeric metric | number_of_lots_completed_by_supervisors       | Number of Lots Completed by Supervisors       | number        | number        |
| Yes      | numeric metric | money_saved_board_up_cases                    | Money Saved: Board-up Cases                   | money         | money         |
| Yes      | numeric metric | money_saved_demolition_cases                  | Money Saved: Demolition Cases                 | money         | money         |
| Yes      | numeric metric | money_saved_grass_and_weed_cases              | Money Saved: Grass and Weed Cases             | money         | money         |
| Yes      | numeric metric | money_saved_inmate_labor                      | Money Saved: Inmate Labor                     | money         | money         |
| Yes      | numeric metric | money_saved_supervisor_completion             | Money Saved: Supervisor Completion            | money         | money         |
```

## Time Field

```ls
Value = week_reported
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6d4u-fgst d:2016-01-07T00:00:00.000Z m:money_saved_supervisor_completion=0 m:number_of_311_complaints_resolved=12 m:number_of_lots_completed_by_inmate_labor=0 m:money_saved_demolition_cases=4635 m:number_of_grass_and_weed_casses_completed=6 m:number_of_311_complaints_received=6 m:number_of_inspections=106 m:number_of_hearing_notices_mailed=38 m:money_saved_board_up_cases=1251.94 m:number_of_board_up_cases_completed=1 m:money_saved_grass_and_weed_cases=3863.89 m:number_of_housing_inspections=1 m:number_of_initiated_demolition_cases=0 m:number_of_cases_presented_to_hearing_officers=37 m:number_of_demolition_cases_completed=3 m:number_of_initiated_board_up_cases=0 m:money_saved_inmate_labor=0 m:number_of_lots_completed_by_supervisors=0 m:number_of_initiated_grass_and_weed_cases=1

series e:6d4u-fgst d:2016-01-14T00:00:00.000Z m:money_saved_supervisor_completion=0 m:number_of_311_complaints_resolved=12 m:number_of_lots_completed_by_inmate_labor=4 m:money_saved_demolition_cases=4340 m:number_of_grass_and_weed_casses_completed=15 m:number_of_311_complaints_received=8 m:number_of_inspections=219 m:number_of_hearing_notices_mailed=47 m:money_saved_board_up_cases=4975.94 m:number_of_board_up_cases_completed=4 m:money_saved_grass_and_weed_cases=11441.68 m:number_of_housing_inspections=0 m:number_of_initiated_demolition_cases=2 m:number_of_cases_presented_to_hearing_officers=14 m:number_of_demolition_cases_completed=2 m:number_of_initiated_board_up_cases=1 m:money_saved_inmate_labor=1500 m:number_of_lots_completed_by_supervisors=0 m:number_of_initiated_grass_and_weed_cases=9

series e:6d4u-fgst d:2016-01-21T00:00:00.000Z m:money_saved_supervisor_completion=0 m:number_of_311_complaints_resolved=11 m:number_of_lots_completed_by_inmate_labor=1 m:money_saved_demolition_cases=12134 m:number_of_grass_and_weed_casses_completed=14 m:number_of_311_complaints_received=8 m:number_of_inspections=176 m:number_of_hearing_notices_mailed=36 m:money_saved_board_up_cases=2161.12 m:number_of_board_up_cases_completed=2 m:money_saved_grass_and_weed_cases=10161.52 m:number_of_housing_inspections=0 m:number_of_initiated_demolition_cases=9 m:number_of_cases_presented_to_hearing_officers=0 m:number_of_demolition_cases_completed=6 m:number_of_initiated_board_up_cases=2 m:money_saved_inmate_labor=581.64 m:number_of_lots_completed_by_supervisors=0 m:number_of_initiated_grass_and_weed_cases=11
```

## Meta Commands

```ls
metric m:number_of_inspections p:integer l:"Number of Inspections" t:dataTypeName=number

metric m:number_of_hearing_notices_mailed p:integer l:"Number of Hearing Notices Mailed" t:dataTypeName=number

metric m:number_of_cases_presented_to_hearing_officers p:integer l:"Number of Cases Presented to Hearing Officers" t:dataTypeName=number

metric m:number_of_311_complaints_received p:integer l:"Number of 311 Complaints Received" t:dataTypeName=number

metric m:number_of_311_complaints_resolved p:integer l:"Number of 311 Complaints Resolved" t:dataTypeName=number

metric m:number_of_initiated_demolition_cases p:integer l:"Number of Initiated Demolition Cases" t:dataTypeName=number

metric m:number_of_demolition_cases_completed p:integer l:"Number of Demolition Cases Completed" t:dataTypeName=number

metric m:number_of_initiated_board_up_cases p:integer l:"Number of Initiated Board Up Cases" t:dataTypeName=number

metric m:number_of_board_up_cases_completed p:integer l:"Number of Board Up Cases completed" t:dataTypeName=number

metric m:number_of_initiated_grass_and_weed_cases p:integer l:"Number of Initiated Grass and Weed Cases" t:dataTypeName=number

metric m:number_of_grass_and_weed_casses_completed p:integer l:"Number of Grass and Weed Casses Completed" t:dataTypeName=number

metric m:number_of_housing_inspections p:integer l:"Number of Housing Inspections" t:dataTypeName=number

metric m:number_of_lots_completed_by_inmate_labor p:integer l:"Number of Lots Completed by Inmate Labor" t:dataTypeName=number

metric m:number_of_lots_completed_by_supervisors p:integer l:"Number of Lots Completed by Supervisors" t:dataTypeName=number

metric m:money_saved_board_up_cases p:double l:"Money Saved: Board-up Cases" t:dataTypeName=money

metric m:money_saved_demolition_cases p:double l:"Money Saved: Demolition Cases" t:dataTypeName=money

metric m:money_saved_grass_and_weed_cases p:double l:"Money Saved: Grass and Weed Cases" t:dataTypeName=money

metric m:money_saved_inmate_labor p:double l:"Money Saved: Inmate Labor" t:dataTypeName=money

metric m:money_saved_supervisor_completion p:double l:"Money Saved: Supervisor Completion" t:dataTypeName=money

entity e:6d4u-fgst l:"Weekly Community Improvement Numbers" t:attribution="City of Jackson - Police Department" t:url=https://data.jacksonms.gov/api/views/6d4u-fgst

property e:6d4u-fgst t:meta.view v:id=6d4u-fgst v:category="Community Development" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Weekly Community Improvement Numbers" v:attribution="City of Jackson - Police Department"

property e:6d4u-fgst t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:displayName="Justin Bruce"

property e:6d4u-fgst t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:displayName="Justin Bruce"
```