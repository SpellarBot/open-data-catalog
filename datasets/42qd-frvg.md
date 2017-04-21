# WDFW Juvenile Trap Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wdfw-juvenile-trap-sites-9b053) |
| Metadata | [Link](https://data.wa.gov/api/views/42qd-frvg) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/42qd-frvg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/42qd-frvg/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 42qd-frvg |
| Name | WDFW Juvenile Trap Sites |
| Attribution | WDFW, Brodie Cox |
| Category | Natural Resources & Environment |
| Tags | jmx, salmon, juveniles, trapping, monitoring |
| Created | 2012-11-16T22:22:09Z |
| Publication Date | 2013-05-31T16:09:08Z |

## Description

WDFW Juvenile salmonid trap locations active and inactive

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | name           | Name           | text      | text        |
| Yes      | series tag     | geometryid     | GEOMETRYID     | text      | text        |
| Yes      | series tag     | wdfw           | WDFW           | text      | text        |
| Yes      | series tag     | featurestatus  | FeatureStatus  | text      | text        |
| Yes      | numeric metric | wria_nr        | WRIA_NR        | number    | number      |
| Yes      | series tag     | county         | County         | text      | text        |
| Yes      | series tag     | le_region      | LE_Region      | text      | text        |
| Yes      | series tag     | watershed_name | Watershed_Name | text      | text        |
| Yes      | series tag     | sr_region      | SR_Region      | text      | text        |
| Yes      | series tag     | score1_yn      | SCORE1_yn      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:42qd-frvg d:2012-11-16T14:22:12.000Z t:watershed_name=Elwah-Dungeness t:featurestatus=Current t:le_region="North Olympic Peninsula LE" t:county=Clallam t:sr_region="Puget Sound" t:name="Dungeness Screw Trap" t:wdfw=yes t:score1_yn=n t:geometryid=P2052 m:wria_nr=18

series e:42qd-frvg d:2012-11-16T14:22:12.000Z t:watershed_name=Lewis/Salmon-Washougal t:featurestatus=Obsolete t:le_region="Lower Columbia Fish Recovery Board" t:county=Cowlitz t:sr_region="Lower Columbia" t:name="Kalama Fyke Net" t:wdfw=unknown t:score1_yn=n t:geometryid=P2055 m:wria_nr=27

series e:42qd-frvg d:2012-11-16T14:22:12.000Z t:watershed_name=Lewis/Salmon-Washougal t:featurestatus=Obsolete t:le_region="Lower Columbia Fish Recovery Board" t:county=Clark t:sr_region="Lower Columbia" t:name="Lower EF Lewis Screw Trap" t:wdfw=unknown t:score1_yn=n t:geometryid=P2056 m:wria_nr=27
```

## Meta Commands

```ls
metric m:wria_nr p:integer l:WRIA_NR t:dataTypeName=number

entity e:42qd-frvg l:"WDFW Juvenile Trap Sites" t:attribution="WDFW, Brodie Cox" t:url=https://data.wa.gov/api/views/42qd-frvg

property e:42qd-frvg t:meta.view v:id=42qd-frvg v:category="Natural Resources & Environment" v:averageRating=0 v:name="WDFW Juvenile Trap Sites" v:attribution="WDFW, Brodie Cox"

property e:42qd-frvg t:meta.view.owner v:id=b2s6-8ii9 v:profileImageUrlMedium=/api/users/b2s6-8ii9/profile_images/THUMB v:profileImageUrlLarge=/api/users/b2s6-8ii9/profile_images/LARGE v:screenName="Brodie Cox" v:profileImageUrlSmall=/api/users/b2s6-8ii9/profile_images/TINY v:displayName="Brodie Cox"

property e:42qd-frvg t:meta.view.tableauthor v:id=b2s6-8ii9 v:profileImageUrlMedium=/api/users/b2s6-8ii9/profile_images/THUMB v:profileImageUrlLarge=/api/users/b2s6-8ii9/profile_images/LARGE v:screenName="Brodie Cox" v:profileImageUrlSmall=/api/users/b2s6-8ii9/profile_images/TINY v:roleName=publisher v:displayName="Brodie Cox"
```

## Top Records

```ls
| :updated_at | name                                                 | geometryid | wdfw    | featurestatus | wria_nr | county   | le_region                                     | watershed_name            | sr_region      | score1_yn | 
| =========== | ==================================================== | ========== | ======= | ============= | ======= | ======== | ============================================= | ========================= | ============== | ========= | 
| 1353075732  | Dungeness Screw Trap                                 | P2052      | yes     | Current       | 18      | Clallam  | North Olympic Peninsula LE                    | Elwah-Dungeness           | Puget Sound    | n         | 
| 1353075732  | Kalama Fyke Net                                      | P2055      | unknown | Obsolete      | 27      | Cowlitz  | Lower Columbia Fish Recovery Board            | Lewis/Salmon-Washougal    | Lower Columbia | n         | 
| 1353075732  | Lower EF Lewis Screw Trap                            | P2056      | unknown | Obsolete      | 27      | Clark    | Lower Columbia Fish Recovery Board            | Lewis/Salmon-Washougal    | Lower Columbia | n         | 
| 1353075732  | Upper EF Lewis Screw Trap                            | P2057      | unknown | Obsolete      | 27      | Clark    | Lower Columbia Fish Recovery Board            | Lewis/Salmon-Washougal    | Lower Columbia | n         | 
| 1353075732  | Duncan Spawning Channel Trap                         | P2058      | unknown | Current       | 28      | Skamania | Lower Columbia Fish Recovery Board            | Lewis/Salmon-Washougal    | Lower Columbia | n         | 
| 1353075732  | Methow Screw Trap                                    | P2060      | yes     | Current       | 48      | Okanogan | Okanogan County and Colville Tribe            | Methow                    | Upper Columbia | n         | 
| 1353075732  | Touchet Screw Trap                                   | P2067      | yes     | Current       | 32      | Columbia | Snake River Salmon Recovery Board             | Walla Walla               | Snake River    | n         | 
| 1353075732  | Mayfield Dam Juvenile Trap                           | P2088      | yes     | Current       | 26      | Lewis    | Lower Columbia Fish Recovery Board            | Grays-Elochoman/Cowlitz   | Lower Columbia | n         | 
| 1353075732  | Yakama Roza Screw Trap (1991 Chinook Eval)           | P2241      | yes     | Obsolete      | 39      | Kittitas | Yakima Basin Fish and Wildlife Recovery Board | Lower/Upper Yakima/Naches | Mid Columbia   | 0         | 
| 1353075732  | Toutle (NF Toutle) R Scoop Trap (1991 Survival Test) | P2242      | yes     | Obsolete      | 26      | Cowlitz  | Lower Columbia Fish Recovery Board            | Grays-Elochoman/Cowlitz   | Lower Columbia | 0         | 
```