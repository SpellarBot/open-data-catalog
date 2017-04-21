# Curb Ramps on NYS-Owned Highways

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/curb-ramps-on-nys-owned-highways) |
| Metadata | [Link](https://data.ny.gov/api/views/hmbc-hni2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/hmbc-hni2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/hmbc-hni2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | hmbc-hni2 |
| Name | Curb Ramps on NYS-Owned Highways |
| Attribution | New York State Department of Transportation (DOT) |
| Category | Transportation |
| Created | 2015-12-15T18:43:00Z |
| Publication Date | 2015-12-16T12:35:26Z |

## Description

This data set includes all curb ramps located on the road system under the jurisdiction of New York State Department of Transportation (DOT). It contains the Regional Office responsible for the management of the feature, the state county where the feature is located and the route name and number for all curb ramps on state-owned routes within New York State.  The data set does not include curb ramps located on non-state owned routes such as those owned by cities, towns or villages within the state

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | geographic_id | Geographic ID | text      | number      |
| Yes      | series tag     | region        | Region        | text      | number      |
| Yes      | series tag     | county        | County        | text      | text        |
| Yes      | series tag     | route         | Route         | text      | text        |
| Yes      | series tag     | road          | Road          | text      | text        |
| Yes      | numeric metric | milepoint     | Milepoint     | number    | number      |
| No       |                | lat           | Latitude      | number    | number      |
| Yes      | numeric metric | lon           | Longitude     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = lat
```

## Data Commands

```ls
series e:hmbc-hni2 d:2015-12-15T10:43:03.000Z t:region=1 t:geographic_id=0 t:county=GREEN t:route=NY23A t:road="Route 23A" m:lon=-74.09286262 m:milepoint=21.6104

series e:hmbc-hni2 d:2015-12-15T10:43:03.000Z t:region=1 t:geographic_id=1 t:county=GREEN t:route=NY23A t:road="Main St" m:lon=-74.14960649 m:milepoint=18.5922

series e:hmbc-hni2 d:2015-12-15T10:43:03.000Z t:region=1 t:geographic_id=2 t:county=GREEN t:route=NY23A t:road="Main St" m:lon=-74.13750116 m:milepoint=19.2192
```

## Meta Commands

```ls
metric m:milepoint p:float l:Milepoint d:"The closest milepoint, based on the linear referencing system, within 1/10th mile sections, in proximity to where the curb ramp feature is located. Blank indicates the curb ramp is not maintained by NYS DOT." t:dataTypeName=number

metric m:lon p:double l:Longitude d:"Longitudinal location point of the curb ramp feature" t:dataTypeName=number

entity e:hmbc-hni2 l:"Curb Ramps on NYS-Owned Highways" t:attribution="New York State Department of Transportation (DOT)" t:url=https://data.ny.gov/api/views/hmbc-hni2

property e:hmbc-hni2 t:meta.view v:id=hmbc-hni2 v:category=Transportation v:averageRating=0 v:name="Curb Ramps on NYS-Owned Highways" v:attribution="New York State Department of Transportation (DOT)"

property e:hmbc-hni2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:hmbc-hni2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| :updated_at | geographic_id | region | county | route | road      | milepoint | lat         | lon          | 
| =========== | ============= | ====== | ====== | ===== | ========= | ========= | =========== | ============ | 
| 1450176183  | 0             | 1      | GREEN  | NY23A | Route 23A | 21.6104   | 42.19456038 | -74.09286262 | 
| 1450176183  | 1             | 1      | GREEN  | NY23A | Main St   | 18.5922   | 42.1956799  | -74.14960649 | 
| 1450176183  | 2             | 1      | GREEN  | NY23A | Main St   | 19.2192   | 42.19561033 | -74.13750116 | 
| 1450176183  | 3             | 1      | GREEN  | NY23A | Main St   | 18.6308   | 42.19583154 | -74.14884144 | 
| 1450176183  | 4             | 1      | GREEN  | NY23A | Main St   | 19.3663   | 42.19574013 | -74.13460265 | 
| 1450176183  | 5             | 1      | GREEN  | NY23A | Main St   | 19.5317   | 42.19576153 | -74.13139493 | 
| 1450176183  | 6             | 1      | GREEN  | NY23A | Main St   | 19.6147   | 42.19577694 | -74.12975656 | 
| 1450176183  | 7             | 1      | GREEN  | NY23A | Main St   | 19.719    | 42.1957737  | -74.12776569 | 
| 1450176183  | 8             | 1      | GREEN  | NY23A | Main St   | 18.7898   | 42.1959982  | -74.14567059 | 
| 1450176183  | 9             | 1      | GREEN  | NY23A | Main St   | 18.7467   | 42.19606862 | -74.14649897 | 
```