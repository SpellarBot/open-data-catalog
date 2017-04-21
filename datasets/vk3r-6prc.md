# Watershed Reach Index and Problem Scores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/watershed-reach-index-and-problem-scores) |
| Metadata | [Link](https://data.austintexas.gov/api/views/vk3r-6prc) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/vk3r-6prc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/vk3r-6prc/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | vk3r-6prc |
| Name | Watershed Reach Index and Problem Scores |
| Attribution | City of Austin Watershed Protection Environmental Resource Management |
| Category | Environmental |
| Tags | water quality, watershed protection, creeks, eii, environmental integrity index, ali, austin lakes index |
| Created | 2015-03-26T18:39:45Z |
| Publication Date | 2015-04-14T20:26:13Z |

## Description

The Environmental Integrity Index (EII) is a tool developed by the City of Austin?s Environmental Resource Management Division to monitor and assess the ecological integrity and the degree of impairment in Austin?s watersheds.  This feature class provides the most recent results from the EII for the City of Austin Watershed Protection Department?s Masterplanning process.  Similarly, the Austin Lakes Index was designed to provide a yearly assessment of the ecological integrity of Lake Austin, Lady Bird Lake, and Lake Long.

Index scores (from both the EII and ALI) are an integer between 0 and 100.  Excellent  88-100 | Very Good 76-87 | Good 63-75 | Fair 51-62 | Marginal38-50 | Poor 26-37 | Bad 13-25 | Very Bad 0-12.

Problem Scores are an integer between 1 and 100 with 1 being "No Problem" and 100 being a highest priority.

EII Methodology:

http://www.austintexas.gov/watershed_protection/publications/document.cfm?id=186267

Master Plan Problem Score Methodology:

http://www.austintexas.gov/watershed_protection/publications/document.cfm?id=186352

Lake Index Methodology:

http://www.austintexas.gov/watershed_protection/publications/document.cfm?id=196479

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                        | Data Type     | Render Type   |
| ======== | ============== | ============================ | =========================== | ============= | ============= |
| Yes      | series tag     | watershed_id                 | Watershed ID                | text          | number        |
| Yes      | series tag     | watershed_name               | Watershed Name              | text          | text          |
| Yes      | series tag     | integrity_score_id           | Integrity Score ID          | text          | number        |
| Yes      | series tag     | watershed_reach_id           | Watershed Reach             | text          | text          |
| Yes      | numeric metric | fiscal_year_of_observation   | Year of Observation         | number        | number        |
| Yes      | numeric metric | index_phase                  | Index Phase                 | number        | text          |
| Yes      | series tag     | index_source_type            | Index Source Type           | text          | text          |
| Yes      | numeric metric | index_reach_score            | Overall                     | number        | number        |
| Yes      | numeric metric | index_aquatic_life           | Aquatic Life                | number        | number        |
| Yes      | numeric metric | index_contact_recreation     | Contact Recreation          | number        | number        |
| Yes      | numeric metric | index_eutrophication         | Eutrophication              | number        | number        |
| Yes      | numeric metric | index_habitat                | Habitat                     | number        | number        |
| Yes      | numeric metric | index_non_contact_recreation | Non-Contact Recreation      | number        | number        |
| Yes      | numeric metric | index_sediment               | Sediment                    | number        | number        |
| Yes      | numeric metric | index_vegetation             | Vegetation                  | number        | number        |
| Yes      | numeric metric | index_water_quality          | Water Quality               | number        | number        |
| Yes      | numeric metric | problem_animal_waste         | Animal Waste Problem        | number        | number        |
| Yes      | numeric metric | problem_construction_runoff  | Construction Runoff Problem | number        | number        |
| Yes      | numeric metric | problem_fertilizer           | Fertilizer Problem          | number        | number        |
| Yes      | numeric metric | problem_litter               | Litter Problem              | number        | number        |
| Yes      | numeric metric | problem_riparian_vegetation  | Riparian Vegetation Problem | number        | number        |
| Yes      | numeric metric | problem_sediment             | Sediment Problem            | number        | number        |
| Yes      | numeric metric | problem_sewage               | Sewage Problem              | number        | number        |
| Yes      | numeric metric | problem_stability            | Stability Problem           | number        | number        |
| Yes      | numeric metric | problem_water_quality        | Water Quality Problem       | number        | number        |
| Yes      | series tag     | created_by                   | CREATED_BY                  | text          | text          |
| Yes      | time           | created_date                 | CREATED_DATE                | calendar_date | calendar_date |
| Yes      | series tag     | modified_by                  | MODIFIED_BY                 | text          | text          |
| No       |                | modified_date                | MODIFIED_DATE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = created_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = modified_date
```

## Data Commands

```ls
series e:vk3r-6prc d:2011-04-17T15:45:43.000Z t:created_by=RCLAYTON t:watershed_name="Fort Branch" t:index_source_type=EII t:watershed_reach_id=FOR1 t:modified_by=RCLAYTON t:integrity_score_id=49 t:watershed_id=9 m:problem_sewage=0 m:problem_litter=79 m:index_water_quality=0 m:problem_sediment=23 m:problem_fertilizer=0 m:index_aquatic_life=53 m:problem_riparian_vegetation=52 m:index_phase=1 m:fiscal_year_of_observation=2013 m:problem_stability=86 m:problem_construction_runoff=41 m:index_vegetation=0 m:index_reach_score=58 m:problem_water_quality=0 m:index_sediment=83 m:index_habitat=58 m:index_eutrophication=0 m:problem_animal_waste=0 m:index_contact_recreation=0 m:index_non_contact_recreation=38

series e:vk3r-6prc d:2011-04-17T15:45:43.000Z t:created_by=RCLAYTON t:watershed_name="Fort Branch" t:index_source_type=EII t:watershed_reach_id=FOR3 t:modified_by=RCLAYTON t:integrity_score_id=51 t:watershed_id=9 m:problem_sewage=0 m:problem_litter=26 m:index_water_quality=0 m:problem_sediment=23 m:problem_fertilizer=0 m:index_aquatic_life=0 m:problem_riparian_vegetation=82 m:index_phase=1 m:fiscal_year_of_observation=2013 m:problem_stability=17 m:problem_construction_runoff=65 m:index_vegetation=0 m:index_reach_score=49 m:problem_water_quality=0 m:index_sediment=83 m:index_habitat=56 m:index_eutrophication=0 m:problem_animal_waste=0 m:index_contact_recreation=0 m:index_non_contact_recreation=58

series e:vk3r-6prc d:2011-04-17T15:45:43.000Z t:created_by=RCLAYTON t:watershed_name="Fort Branch" t:index_source_type=EII t:watershed_reach_id=FOR4 t:modified_by=RCLAYTON t:integrity_score_id=52 t:watershed_id=9 m:problem_sewage=76 m:problem_litter=53 m:index_water_quality=55 m:problem_sediment=23 m:problem_fertilizer=37 m:index_aquatic_life=52 m:problem_riparian_vegetation=96 m:index_phase=1 m:fiscal_year_of_observation=2013 m:problem_stability=34 m:problem_construction_runoff=67 m:index_vegetation=0 m:index_reach_score=57 m:problem_water_quality=37 m:index_sediment=83 m:index_habitat=62 m:index_eutrophication=0 m:problem_animal_waste=63 m:index_contact_recreation=31 m:index_non_contact_recreation=58
```

## Meta Commands

```ls
metric m:fiscal_year_of_observation p:integer l:"Year of Observation" d:"The City of Austin Fiscal year the data points are associated with. FY 2014 started on 01-OCT-2013 and ended 30-SEP-2014." t:dataTypeName=number

metric m:index_phase p:integer l:"Index Phase" d:"For streams only - one of two phases. Lakes all collected in same phase." t:dataTypeName=number

metric m:index_reach_score p:integer l:Overall d:"Overall Index Score. 100 = best condition. Average of other index scores. Problem scores not included." t:dataTypeName=number

metric m:index_aquatic_life p:integer l:"Aquatic Life" d:"Aquatic Life Index score. 100 = best condition. (Bugs, diatoms abundance, diversity, pollution tolerance and other metrics)" t:dataTypeName=number

metric m:index_contact_recreation p:integer l:"Contact Recreation" d:"Contact Recreation Index score (for creeks only). 100 = best condition. (bacteria)" t:dataTypeName=number

metric m:index_eutrophication p:integer l:Eutrophication d:"Eutrophication Index score (for lakes only). 100 = best condition. In general, lower chlorophyll-a abundance and lower proportion of blue-green algae lead to a higher score to represent a superior trophic condition." t:dataTypeName=number

metric m:index_habitat p:integer l:Habitat d:"Habitat Index score. 100 = best condition. Instream cover and substrate niches." t:dataTypeName=number

metric m:index_non_contact_recreation p:integer l:"Non-Contact Recreation" d:"Non Contact Recreation Index score (creeks only). 100 = best condition. Aesthetics, odor, safety." t:dataTypeName=number

metric m:index_sediment p:integer l:Sediment d:"Sediment Index score. 100 = best condition. Metals, pcbs, pesticides average." t:dataTypeName=number

metric m:index_vegetation p:integer l:Vegetation d:"Vegetation Index score (for lakes only). 100 = best condition." t:dataTypeName=number

metric m:index_water_quality p:integer l:"Water Quality" d:"Water Quality Index score. 100 = best condition. (nutrients, temp, tss)" t:dataTypeName=number

metric m:problem_animal_waste p:integer l:"Animal Waste Problem" d:"Animal Problem score (creeks only). 100 = worst condition. Pet waste." t:dataTypeName=number

metric m:problem_construction_runoff p:integer l:"Construction Runoff Problem" d:"Construction TSS Problem score (creeks only). 100 = worst condition. Erosion and Sedimentation controls failure." t:dataTypeName=number

metric m:problem_fertilizer p:integer l:"Fertilizer Problem" d:"Fertilizer problem score (creeks only). 100 = worst condition. Nitrate." t:dataTypeName=number

metric m:problem_litter p:integer l:"Litter Problem" d:"Litter problem score (creeks only). 100 = worst condition. Trash" t:dataTypeName=number

metric m:problem_riparian_vegetation p:integer l:"Riparian Vegetation Problem" d:"Riparian Vegetation problem score (creeks only). 100 = worst condition. Not enough riparian cover." t:dataTypeName=number

metric m:problem_sediment p:integer l:"Sediment Problem" d:"Sediment problem score (creeks only). 100 = worst condition. Worst of the problems set score." t:dataTypeName=number

metric m:problem_sewage p:integer l:"Sewage Problem" d:"Sewage problem score (creeks only). 100 = worst condition. Water Quality problem caused by sewage." t:dataTypeName=number

metric m:problem_stability p:integer l:"Stability Problem" d:"Stability problem score (creeks only). 100 = worst condition. Stream bank failures." t:dataTypeName=number

metric m:problem_water_quality p:integer l:"Water Quality Problem" d:"Water Quality problem score (creeks only). 100 = worst condition. Water quality worst case." t:dataTypeName=number

entity e:vk3r-6prc l:"Watershed Reach Index and Problem Scores" t:attribution="City of Austin Watershed Protection Environmental Resource Management" t:url=https://data.austintexas.gov/api/views/vk3r-6prc

property e:vk3r-6prc t:meta.view v:id=vk3r-6prc v:category=Environmental v:averageRating=0 v:name="Watershed Reach Index and Problem Scores" v:attribution="City of Austin Watershed Protection Environmental Resource Management"

property e:vk3r-6prc t:meta.view.owner v:id=buxt-jupg v:profileImageUrlMedium=/api/users/buxt-jupg/profile_images/THUMB v:profileImageUrlLarge=/api/users/buxt-jupg/profile_images/LARGE v:screenName=Rob v:profileImageUrlSmall=/api/users/buxt-jupg/profile_images/TINY v:displayName=Rob

property e:vk3r-6prc t:meta.view.tableauthor v:id=buxt-jupg v:profileImageUrlMedium=/api/users/buxt-jupg/profile_images/THUMB v:profileImageUrlLarge=/api/users/buxt-jupg/profile_images/LARGE v:screenName=Rob v:profileImageUrlSmall=/api/users/buxt-jupg/profile_images/TINY v:roleName=publisher v:displayName=Rob
```

## Top Records

```ls
| watershed_id | watershed_name    | integrity_score_id | watershed_reach_id | fiscal_year_of_observation | index_phase | index_source_type | index_reach_score | index_aquatic_life | index_contact_recreation | index_eutrophication | index_habitat | index_non_contact_recreation | index_sediment | index_vegetation | index_water_quality | problem_animal_waste | problem_construction_runoff | problem_fertilizer | problem_litter | problem_riparian_vegetation | problem_sediment | problem_sewage | problem_stability | problem_water_quality | created_by | created_date        | modified_by | modified_date       | 
| ============ | ================= | ================== | ================== | ========================== | =========== | ================= | ================= | ================== | ======================== | ==================== | ============= | ============================ | ============== | ================ | =================== | ==================== | =========================== | ================== | ============== | =========================== | ================ | ============== | ================= | ===================== | ========== | =================== | =========== | =================== | 
| 9            | Fort Branch       | 49                 | FOR1               | 2013                       | 1           | EII               | 58                | 53                 | 0                        | 0                    | 58            | 38                           | 83             | 0                | 0                   | 0                    | 41                          | 0                  | 79             | 52                          | 23               | 0              | 86                | 0                     | RCLAYTON   | 2011-04-17T15:45:43 | RCLAYTON    | 2013-12-19T07:47:43 | 
| 9            | Fort Branch       | 51                 | FOR3               | 2013                       | 1           | EII               | 49                | 0                  | 0                        | 0                    | 56            | 58                           | 83             | 0                | 0                   | 0                    | 65                          | 0                  | 26             | 82                          | 23               | 0              | 17                | 0                     | RCLAYTON   | 2011-04-17T15:45:43 | RCLAYTON    | 2013-12-19T07:47:43 | 
| 9            | Fort Branch       | 52                 | FOR4               | 2013                       | 1           | EII               | 57                | 52                 | 31                       | 0                    | 62            | 58                           | 83             | 0                | 55                  | 63                   | 67                          | 37                 | 53             | 96                          | 23               | 76             | 34                | 37                    | RCLAYTON   | 2011-04-17T15:45:43 | RCLAYTON    | 2013-12-19T07:47:43 | 
| 108          | West Bull Creek   | 114                | WBL2               | 2014                       | 2           | EII               | 77                | 99                 | 57                       | 0                    | 76            | 83                           | 79             | 0                | 70                  | 83                   | 90                          | 17                 | 73             | 19                          | 50               | 45             | 13                | 14                    | RCLAYTON   | 2011-04-17T15:45:43 | RCLAYTON    | 2014-12-11T16:52:47 | 
| 7            | Bull Creek        | 27                 | BUL5               | 2014                       | 2           | EII               | 74                | 91                 | 73                       | 0                    | 90            | 68                           | 61             | 0                | 60                  | 18                   | 80                          | 82                 | 7              | 0                           | 100              | 75             | 4                 | 53                    | RCLAYTON   | 2011-04-17T15:45:43 | RCLAYTON    | 2014-12-11T16:52:47 | 
| 15           | Blunn Creek       | 13                 | BLU1               | 2013                       | 1           | EII               | 60                | 67                 | 25                       | 0                    | 67            | 85                           | 69             | 0                | 49                  | 95                   | 53                          | 5                  | 53             | 86                          | 38               | 59             | 53                | 34                    | RCLAYTON   | 2011-04-17T15:45:43 | RCLAYTON    | 2013-12-19T07:47:43 | 
| 113          | Williamson Creek  | 126                | WMS1               | 2013                       | 1           | EII               | 70                | 86                 | 52                       | 0                    | 59            | 84                           | 83             | 0                | 58                  | 29                   | 63                          | 71                 | 26             | 40                          | 14               | 72             | 56                | 34                    | RCLAYTON   | 2011-04-17T15:45:43 | RCLAYTON    | 2013-12-19T07:47:43 | 
| 90           | South Boggy Creek | 96                 | SBG1               | 2014                       | 2           | EII               | 66                | 49                 | 70                       | 0                    | 65            | 69                           | 65             | 0                | 75                  | 71                   | 91                          | 29                 | 67             | 64                          | 84               | 37             | 25                | 60                    | RCLAYTON   | 2011-04-17T15:45:43 | RCLAYTON    | 2014-12-11T16:52:47 | 
| 76           | Marble Creek      | 79                 | MAR1               | 2014                       | 2           | EII               | 60                | 64                 | 41                       | 0                    | 61            | 73                           | 78             | 0                | 45                  | 51                   | 79                          | 49                 | 27             | 28                          | 47               | 88             | 45                | 46                    | RCLAYTON   | 2011-04-17T15:45:43 | RCLAYTON    | 2014-12-11T16:52:47 | 
| 7            | Bull Creek        | 24                 | BUL2               | 2014                       | 2           | EII               | 84                | 97                 | 94                       | 0                    | 83            | 92                           | 61             | 0                | 76                  | 40                   | 38                          | 60                 | 13             | 73                          | 100              | 30             | 47                | 96                    | RCLAYTON   | 2011-04-17T15:45:43 | RCLAYTON    | 2014-12-11T16:52:47 | 
```