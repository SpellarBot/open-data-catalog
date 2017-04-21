# Region 4 Combined Fix-it Enhance 100% List - 2018-2021 STIP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/region-4-combined-fix-it-enhance-100-list-2018-2021-stip) |
| Metadata | [Link](https://data.oregon.gov/api/views/ccbz-8fft) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ccbz-8fft/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ccbz-8fft/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ccbz-8fft |
| Name | Region 4 Combined Fix-it Enhance 100% List - 2018-2021 STIP |
| Attribution | Oregon Department of Transportation |
| Category | Transportation |
| Created | 2016-08-31T14:41:09Z |
| Publication Date | 2016-08-31T14:54:54Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | fix_it_category_s   | FIX-IT CATEGORY(S)  | text      | text        |
| Yes      | series tag     | project_name        | PROJECT NAME        | text      | text        |
| Yes      | series tag     | county              | COUNTY              | text      | text        |
| Yes      | series tag     | hwy                 | HWY#                | text      | text        |
| Yes      | series tag     | route               | ROUTE               | text      | text        |
| Yes      | numeric metric | beg_mp              | BEG MP              | number    | number      |
| Yes      | numeric metric | end_mp              | END MP              | number    | number      |
| Yes      | series tag     | description         | Description         | text      | text        |
| Yes      | numeric metric | total_cost          | Total Cost          | money     | money       |
| Yes      | numeric metric | 15_18_funding       | 15-18 Funding       | money     | money       |
| Yes      | numeric metric | other_or_match      | Other or Match      | money     | money       |
| Yes      | numeric metric | enhance             | Enhance             | money     | money       |
| Yes      | numeric metric | pre_scope_total_est | PRE-SCOPE TOTAL EST | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ccbz-8fft d:2016-08-31T14:41:12.000Z t:project_name="US197: THE DALLES BRIDGE #06635Q" t:county=WASCO t:description="Deck replacement with pedestrian facility" t:route=US197 t:fix_it_category_s=BRIDGE t:hwy=4 m:other_or_match=18452500 m:total_cost=36905000 m:beg_mp=0 m:pre_scope_total_est=23448700 m:end_mp=0.25

series e:ccbz-8fft d:2016-08-31T14:41:12.000Z t:project_name="US26: WARM SPRINGS HIGHWAY CULVERTS" t:county="JEFFERSON 
WASCO" t:description="Repair or replace critical and poort culverts on priority routes" t:route=US26 t:fix_it_category_s=CULVERT t:hwy=53 m:total_cost=755000 m:beg_mp=65.79 m:end_mp=114.73

series e:ccbz-8fft d:2016-08-31T14:41:12.000Z t:project_name="I-84: COLUMBIA RIVER HIGHWAY CULVERTS" t:county="HOOD RIVER
WASCO
SHERMAN
GILLIAM
MORROW" t:description="Repair or replace critical and poor culverts on priority routes" t:route=I84 t:fix_it_category_s=CULVERT t:hwy=2 m:total_cost=697000 m:beg_mp=63.34 m:pre_scope_total_est=1600000 m:end_mp=157.87
```

## Meta Commands

```ls
metric m:beg_mp p:float l:"BEG MP" t:dataTypeName=number

metric m:end_mp p:float l:"END MP" t:dataTypeName=number

metric m:total_cost p:integer l:"Total Cost" t:dataTypeName=money

metric m:15_18_funding p:integer l:"15-18 Funding" t:dataTypeName=money

metric m:other_or_match p:double l:"Other or Match" t:dataTypeName=money

metric m:enhance p:integer l:Enhance t:dataTypeName=money

metric m:pre_scope_total_est p:double l:"PRE-SCOPE TOTAL EST" t:dataTypeName=money

entity e:ccbz-8fft l:"Region 4 Combined Fix-it Enhance 100% List - 2018-2021 STIP" t:attribution="Oregon Department of Transportation" t:url=https://data.oregon.gov/api/views/ccbz-8fft

property e:ccbz-8fft t:meta.view v:id=ccbz-8fft v:category=Transportation v:averageRating=0 v:name="Region 4 Combined Fix-it Enhance 100% List - 2018-2021 STIP" v:attribution="Oregon Department of Transportation"

property e:ccbz-8fft t:meta.view.license v:name="Public Domain"

property e:ccbz-8fft t:meta.view.owner v:id=kg3r-f9r3 v:screenName="Abbey Driscoll" v:displayName="Abbey Driscoll"

property e:ccbz-8fft t:meta.view.tableauthor v:id=kg3r-f9r3 v:screenName="Abbey Driscoll" v:roleName=editor v:displayName="Abbey Driscoll"
```

## Top Records

```ls
| :updated_at | fix_it_category_s                  | project_name                                                                                                                | county                                  | hwy | route    | beg_mp | end_mp | description                                                                                      | total_cost | 15_18_funding | other_or_match | enhance | pre_scope_total_est | 
| =========== | ================================== | =========================================================================================================================== | ======================================= | === | ======== | ====== | ====== | ================================================================================================ | ========== | ============= | ============== | ======= | =================== | 
| 1472654472  | BRIDGE                             | US197: THE DALLES BRIDGE #06635Q                                                                                            | WASCO                                   | 4   | US197    | 0.00   | 0.25   | Deck replacement with pedestrian facility                                                        | 36905000   |               | 18452500.00    |         | 23448700            | 
| 1472654472  | CULVERT                            | US26: WARM SPRINGS HIGHWAY CULVERTS                                                                                         | JEFFERSON WASCO                         | 53  | US26     | 65.79  | 114.73 | Repair or replace critical and poort culverts on priority routes                                 | 755000     |               |                |         |                     | 
| 1472654472  | CULVERT                            | I-84: COLUMBIA RIVER HIGHWAY CULVERTS                                                                                       | HOOD RIVER WASCO SHERMAN GILLIAM MORROW | 2   | I84      | 63.34  | 157.87 | Repair or replace critical and poor culverts on priority routes                                  | 697000     |               |                |         | 1600000             | 
| 1472654472  | FISH PASSAGE                       | US395: CROOKED CREEK CULVERT & COGSWELL CREEK CULVERT                                                                       | LAKE                                    | 19  | US395    | 130.47 | 130.51 | Replace double box culvert w/single span culvert                                                 | 1683000    | 380000        |                |         | 1490000             | 
| 1472654472  | OPS/ARTS/ADA                       | US26: HARWOOD AVE TO COMBS FLAT ROAD (3RD ST, PRINEVILLE)                                                                   | CROOK                                   | 41  | US26     | 18.90  | 19.80  | Sign, signal and ADA improvements.                                                               | 1763200    | 315000        |                |         | 1336600             | 
| 1472654472  | ENHANCE                            | MAIN ST/9TH - NE COMBS FLAT (PRINEVILLE)                                                                                    | CROOK                                   |     |          |        |        | Bike and pedestrian path along Ochoco abandoned rail line                                        | 885000     |               | 536000         | 349000  |                     | 
| 1472654472  | OPS/TDM                            | REGION 4 TRANSIT SUPPORT                                                                                                    | VARIOUS                                 | N/A | VARIOUS  |        |        | Researching statewide and expectations for both TDM & Transit                                    | 1031837    |               |                |         | 0.0                 | 
| 1472654472  | OPS (TRAFFIC)/ENHANCE HWY LEVERAGE | LOWER JOHN DAY ITS PRIORITIES ? Shaniko RWIS ($120k) ? Rufus VMS ($988k) ? US97 SB @ Biggs ($900k) ? Hood River VMS ($990k) | VARIOUS                                 |     | US97/I84 |        |        | ITS upgrades including variable message signs and remote weather info system install             | 2008000    | 508000        |                |         | 1000000             | 
| 1472654472  | OPS (ITS)                          | OR39 @ WASHBURN WAY COMMUNICATION                                                                                           | KLAMATH                                 | 50  | OR39     | -3.93  | -4.46  | New signal cabinet including rack and switch and fiber optic connection at Washburn Way and OR39 | 200000     |               |                |         | 200000              | 
| 1472654472  | OPS PRIORITIES                     | REGION 4 ROCKFALL                                                                                                           | VARIOUS                                 |     |          |        |        | R4 rockfall and slide mitigation                                                                 |            |               |                |         |                     | 
```