# Austin Water Approved Plant List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-approved-plant-list) |
| Metadata | [Link](https://data.austintexas.gov/api/views/82dq-nkpk) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/82dq-nkpk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/82dq-nkpk/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 82dq-nkpk |
| Name | Austin Water Approved Plant List |
| Attribution | Austin Water |
| Category | Environmental |
| Tags | austin, water, plants, landscape, variance, xeriscape, schedule |
| Created | 2016-06-13T20:08:11Z |
| Publication Date | 2016-06-13T20:22:24Z |

## Description

Austin Water?s approved plant list specifies plants that may receive a new landscape/xeriscape watering schedule variance. A landscape must have xeric (low or very low water use) plants to receive the variance. Austin Water might approve other plants if they will be low or very low water use once established. For a list of stabilization/erosion control plants that qualify for this variance, please refer to The City of Austin?s Standard Specifications Manual Item #604S

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | plant_type      | Plant Type      | text      | text        |
| Yes      | series tag  | name            | Name            | text      | text        |
| Yes      | series tag  | scientific_name | Scientific Name | text      | text        |
| Yes      | series tag  | notes           | Notes           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:82dq-nkpk d:2016-06-13T13:08:15.000Z t:name="Ash, Texas" t:scientific_name="Fraxinus texensis" t:plant_type="Large Tree" m:row_number.82dq-nkpk=1

series e:82dq-nkpk d:2016-06-13T13:08:15.000Z t:name="Cherry, Black" t:scientific_name="Prunus serotina var. exima" t:plant_type="Large Tree" m:row_number.82dq-nkpk=2

series e:82dq-nkpk d:2016-06-13T13:08:15.000Z t:name="Cypress, Arizona" t:scientific_name="Cupressus arizonica" t:plant_type="Large Tree" m:row_number.82dq-nkpk=3
```

## Meta Commands

```ls
metric m:row_number.82dq-nkpk p:long l:"Row Number"

entity e:82dq-nkpk l:"Austin Water Approved Plant List" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/82dq-nkpk

property e:82dq-nkpk t:meta.view v:id=82dq-nkpk v:category=Environmental v:attributionLink=http://www.austintexas.gov/wateringvariances v:averageRating=0 v:name="Austin Water Approved Plant List" v:attribution="Austin Water"

property e:82dq-nkpk t:meta.view.owner v:id=dg6c-4vht v:profileImageUrlMedium=/api/users/dg6c-4vht/profile_images/THUMB v:profileImageUrlLarge=/api/users/dg6c-4vht/profile_images/LARGE v:screenName="Austin Water" v:profileImageUrlSmall=/api/users/dg6c-4vht/profile_images/TINY v:displayName="Austin Water"

property e:82dq-nkpk t:meta.view.tableauthor v:id=dg6c-4vht v:profileImageUrlMedium=/api/users/dg6c-4vht/profile_images/THUMB v:profileImageUrlLarge=/api/users/dg6c-4vht/profile_images/LARGE v:screenName="Austin Water" v:profileImageUrlSmall=/api/users/dg6c-4vht/profile_images/TINY v:roleName=editor v:displayName="Austin Water"
```

## Top Records

```ls
| :updated_at | plant_type | name                          | scientific_name            | notes | 
| =========== | ========== | ============================= | ========================== | ===== | 
| 1465823295  | Large Tree | Ash, Texas                    | Fraxinus texensis          |       | 
| 1465823295  | Large Tree | Cherry, Black                 | Prunus serotina var. exima |       | 
| 1465823295  | Large Tree | Cypress, Arizona              | Cupressus arizonica        |       | 
| 1465823295  | Large Tree | Elm, Cedar                    | Ulmus crassifolia          |       | 
| 1465823295  | Large Tree | Juniper (Cedar)               | Juniperus spp.             |       | 
| 1465823295  | Large Tree | Mesquite, Honey               | Prosopis glandulosa        |       | 
| 1465823295  | Large Tree | Oak, Bur                      | Quercus macrocarpa         |       | 
| 1465823295  | Large Tree | Oak, Chinquapin               | Quercus muhlenbergii       |       | 
| 1465823295  | Large Tree | Oak, Lacey                    | Quercus laceyi             |       | 
| 1465823295  | Large Tree | Oak, Mexican White, Monterrey | Quercus polymorpha         |       | 
```