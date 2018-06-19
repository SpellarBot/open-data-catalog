# Replacement Projects by school

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/replacement-projects-by-school) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kydh-ijhc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kydh-ijhc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kydh-ijhc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kydh-ijhc |
| Name | Replacement Projects by school |
| Attribution | NYC School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, projects |
| Created | 2016-05-31T21:48:40Z |
| Publication Date | 2016-06-02T14:10:45Z |

## Description

Replacement project detail by school.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | existing_site_identified | Existing Site Identified | text      | text        |
| Yes      | series tag     | proposed_leased_facility | Proposed Leased Facility | text      | text        |
| Yes      | series tag     | district                 | District                 | text      | number      |
| Yes      | series tag     | project                  | Project #                | text      | text        |
| Yes      | series tag     | school                   | School                   | text      | text        |
| Yes      | series tag     | boro                     | Boro                     | text      | text        |
| Yes      | series tag     | forecast_capacity        | Forecast Capacity        | text      | text        |
| Yes      | series tag     | design_start             | Design Start             | text      | text        |
| Yes      | series tag     | constr_start             | Constr Start             | text      | text        |
| Yes      | series tag     | actual_est_compl         | Actual /Est. Compl       | text      | text        |
| Yes      | numeric metric | total_est_cost           | Total Est. Cost          | number    | number      |
| Yes      | numeric metric | previousappropriations   | PreviousAppropriations   | number    | number      |
| Yes      | numeric metric | fundingreq_dfy_15_19     | FundingReq'dFY 15-19     | number    | number      |
| Yes      | numeric metric | needed_tocomplete        | Needed toComplete        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kydh-ijhc d:2016-06-02T07:08:34.000Z t:project=DSF0000775874 t:existing_site_identified=Yes t:boro=X t:design_start=Sep-13 t:school="P.S. 315" t:proposed_leased_facility=Yes t:constr_start=Mar-15 t:district=10 t:actual_est_compl=Sep-17 t:forecast_capacity=Replacement m:total_est_cost=17.01 m:previousappropriations=0.49 m:fundingreq_dfy_15_19=16.52 m:needed_tocomplete=0

series e:kydh-ijhc d:2016-06-02T07:08:34.000Z t:project=DSF0000800056 t:existing_site_identified=Yes t:boro=X t:design_start=Sep-14 t:school="HS REPLACEMENT @ 1211 SOUTHERN BOULEVARD" t:proposed_leased_facility=Yes t:constr_start=Jul-15 t:district=12 t:actual_est_compl=Apr-16 t:forecast_capacity=Replacement m:total_est_cost=9.99 m:previousappropriations=0 m:fundingreq_dfy_15_19=9.99 m:needed_tocomplete=0

series e:kydh-ijhc d:2016-06-02T07:08:34.000Z t:project=DSF0000798568 t:existing_site_identified=Yes t:boro=Q t:design_start=Mar-15 t:school="P.S. 19 MINISCHOOL" t:proposed_leased_facility=No t:constr_start=Jul-16 t:district=24 t:actual_est_compl=Sep-18 t:forecast_capacity=Replacement m:total_est_cost=15.27 m:previousappropriations=0 m:fundingreq_dfy_15_19=15.27 m:needed_tocomplete=0
```

## Meta Commands

```ls
metric m:total_est_cost p:float l:"Total Est. Cost" t:dataTypeName=number

metric m:previousappropriations p:float l:PreviousAppropriations t:dataTypeName=number

metric m:fundingreq_dfy_15_19 p:float l:"FundingReq'dFY 15-19" t:dataTypeName=number

metric m:needed_tocomplete p:float l:"Needed toComplete" t:dataTypeName=number

entity e:kydh-ijhc l:"Replacement Projects by school" t:attribution="NYC School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/kydh-ijhc

property e:kydh-ijhc t:meta.view v:id=kydh-ijhc v:category=Education v:averageRating=0 v:name="Replacement Projects by school" v:attribution="NYC School Construction Authority (SCA)"

property e:kydh-ijhc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kydh-ijhc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | existing_site_identified | proposed_leased_facility | district | project       | school                                   | boro | forecast_capacity | design_start | constr_start | actual_est_compl | total_est_cost | previousappropriations | fundingreq_dfy_15_19 | needed_tocomplete | 
| =========== | ======================== | ======================== | ======== | ============= | ======================================== | ==== | ================= | ============ | ============ | ================ | ============== | ====================== | ==================== | ================= | 
| 1464851314  | Yes                      | Yes                      | 10       | DSF0000775874 | P.S. 315                                 | X    | Replacement       | Sep-13       | Mar-15       | Sep-17           | 17.01          | 0.49                   | 16.52                | 0.00              | 
| 1464851314  | Yes                      | Yes                      | 12       | DSF0000800056 | HS REPLACEMENT @ 1211 SOUTHERN BOULEVARD | X    | Replacement       | Sep-14       | Jul-15       | Apr-16           | 9.99           | 0.00                   | 9.99                 | 0.00              | 
| 1464851314  | Yes                      | No                       | 24       | DSF0000798568 | P.S. 19 MINISCHOOL                       | Q    | Replacement       | Mar-15       | Jul-16       | Sep-18           | 15.27          | 0.00                   | 15.27                | 0.00              | 
| 1464851314  | Yes                      | No                       | 25       | DSF0000798203 | P.S. 24                                  | Q    | Replacement       | Dec-14       | Mar-16       | Sep-18           | 8.68           | 0.00                   | 8.67                 | 0.00              | 
```