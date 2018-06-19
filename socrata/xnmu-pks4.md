# Exporting Plants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/exporting-plants-09e08) |
| Metadata | [Link](https://data.oregon.gov/api/views/xnmu-pks4) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/xnmu-pks4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/xnmu-pks4/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | xnmu-pks4 |
| Name | Exporting Plants |
| Tags | exporting plants, exporting plants from oregon, shipping plants out of oregon |
| Created | 2014-08-11T16:41:05Z |
| Publication Date | 2014-11-13T21:33:03Z |

## Description

Regulations for Exporting Plants out of Oregon

## Columns

```ls
| Included | Schema Type | Field Name             | Name             | Data Type | Render Type |
| ======== | =========== | ====================== | ================ | ========= | =========== |
| No       | time        | :updated_at            | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | plant_part             | Plant            | text      | text        |
| Yes      | series tag  | destination            | Destination      | text      | text        |
| Yes      | series tag  | regulation             | Regulation       | text      | text        |
| Yes      | series tag  | requirements           | Requirements     | text      | text        |
| Yes      | series tag  | additional_information | More information | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xnmu-pks4 d:2014-08-11T09:41:08.000Z t:plant_part="All plants" t:regulation="Nursery certification" t:requirements="Shipping permit" t:destination="All of United States and OR" m:row_number.xnmu-pks4=1

series e:xnmu-pks4 d:2014-08-11T09:41:08.000Z t:plant_part="All plants - from nurseries that have tested positive for Phytophthora ramorum within the last 3 years." t:regulation="Sudden oak death (Phytophthora ramorum)" t:requirements="Federal shield" t:destination="All of United States and OR" m:row_number.xnmu-pks4=2

series e:xnmu-pks4 d:2014-08-11T09:41:08.000Z t:plant_part="All plants" t:regulation="Noxious weeds" t:requirements="Plants weed-free" t:destination="All of United States and OR" m:row_number.xnmu-pks4=3
```

## Meta Commands

```ls
metric m:row_number.xnmu-pks4 p:long l:"Row Number"

entity e:xnmu-pks4 l:"Exporting Plants" t:url=https://data.oregon.gov/api/views/xnmu-pks4

property e:xnmu-pks4 t:meta.view v:id=xnmu-pks4 v:averageRating=0 v:name="Exporting Plants"

property e:xnmu-pks4 t:meta.view.owner v:id=sjvb-xabp v:screenName="lisa rehms" v:displayName="lisa rehms"

property e:xnmu-pks4 t:meta.view.tableauthor v:id=sjvb-xabp v:screenName="lisa rehms" v:roleName=editor v:displayName="lisa rehms"
```

## Top Records

```ls
| :updated_at | plant_part                                                                                                         | destination                                                           | regulation                              | requirements                                   | additional_information | 
| =========== | ================================================================================================================== | ===================================================================== | ======================================= | ============================================== | ====================== | 
| 1407750068  | All plants                                                                                                         | All of United States and OR                                           | Nursery certification                   | Shipping permit                                |                        | 
| 1407750068  | All plants - from nurseries that have tested positive for Phytophthora ramorum within the last 3 years.            | All of United States and OR                                           | Sudden oak death (Phytophthora ramorum) | Federal shield                                 |                        | 
| 1407750068  | All plants                                                                                                         | All of United States and OR                                           | Noxious weeds                           | Plants weed-free                               |                        | 
| 1407750068  | All plants                                                                                                         | AL, AR, FL, ID MS, NC, TN, VA, WV                                     | Brown garden snail                      | Certificate                                    |                        | 
| 1407750068  | Barberry (Berberis spp.), Mahoberberis spp., Oregon grape (Mahonia spp.)                                           | IA, IL, IN, KS, MI, MN, MO, MT, NE, ND, OH, PA,?SD, WA, WI,?WV and WY | Black stem wheat rust disease           | Federal certificate - resistant varieties only |                        | 
| 1407750068  | Blueberry plants (Vaccinium corymbosum)                                                                            | GA, MI, WA                                                            | Blueberry scorch, and other viruses     | Certificate                                    |                        | 
| 1407750068  | Camellia spp.                                                                                                      | TN, TX                                                                | Camellia flower blight                  | Certificate                                    |                        | 
| 1407750068  | Chestnut (Castanea spp.), chinquapin (Castanopsis spp.), oak (Quercus spp.), tanbark oak (Lithocarpus densiflorus) | CA                                                                    | Chestnut bark disease; oak wilt disease | Certificate                                    |                        | 
| 1407750068  | Chestnut (Castanea spp.), chinquapin (Castanopsis spp.)                                                            | WA                                                                    | Chestnut diseases and insects           | Certificate                                    |                        | 
| 1407750068  | Dogwood (Cornus spp.)                                                                                              | FL                                                                    | Anthracnose disease                     | Florida permit                                 |                        | 
```