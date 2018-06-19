# Lead Based Paint Dwelling Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lead-based-paint-dwelling-statistics-23b30) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/azyf-k3d6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/azyf-k3d6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/azyf-k3d6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | azyf-k3d6 |
| Name | Lead Based Paint Dwelling Statistics |
| Attribution | Department of City Planning (DCP) |
| Category | Public Safety |
| Tags | dcp, city, planning, lead, base, paint, statistics |
| Created | 2013-02-13T20:17:18Z |
| Publication Date | 2013-02-13T20:38:31Z |

## Description

Statistics of occupied units with Lead Based Paint

## Columns

```ls
| Included | Schema Type    | Field Name                                                        | Name                                                               | Data Type | Render Type |
| ======== | ============== | ================================================================= | ================================================================== | ========= | =========== |
| No       | time           | :updated_at                                                       | updated_at                                                         | meta_data | meta_data   |
| Yes      | series tag     | year_built                                                        | Year Built                                                         | text      | text        |
| Yes      | numeric metric | total_units                                                       | Total Units                                                        | number    | text        |
| Yes      | series tag     | estimate_of_percent_of_units_with_lbp                             | Estimate of Percent of Units with LBP                              | text      | text        |
| Yes      | numeric metric | estimated_units_with_lbp                                          | Estimated Units with LBP                                           | number    | text        |
| Yes      | numeric metric | lbp_units_occupied_by_families_less_than_or_equal_to_50_of_median | LBP Units occupied by Families Less than or Equal to 50% of Median | number    | text        |
| Yes      | numeric metric | lbp_units_occupied_by_families_less_than_or_equal_to_80_of_median | LBP Units occupied by Families Less than or Equal to 80% of Median | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:azyf-k3d6 d:2013-02-13T12:17:31.000Z t:year_built=1960+ t:estimate_of_percent_of_units_with_lbp=0% m:total_units=779347

series e:azyf-k3d6 d:2013-02-13T12:17:31.000Z t:year_built=1947-1959 t:estimate_of_percent_of_units_with_lbp=69% m:lbp_units_occupied_by_families_less_than_or_equal_to_80_of_median=170555 m:lbp_units_occupied_by_families_less_than_or_equal_to_50_of_median=119294 m:total_units=458592 m:estimated_units_with_lbp=316428

series e:azyf-k3d6 d:2013-02-13T12:17:31.000Z t:year_built="Before 1947" t:estimate_of_percent_of_units_with_lbp=90% m:lbp_units_occupied_by_families_less_than_or_equal_to_80_of_median=840807 m:lbp_units_occupied_by_families_less_than_or_equal_to_50_of_median=562158 m:total_units=1800057 m:estimated_units_with_lbp=1620051
```

## Meta Commands

```ls
metric m:total_units p:long l:"Total Units" t:dataTypeName=number

metric m:estimated_units_with_lbp p:long l:"Estimated Units with LBP" t:dataTypeName=number

metric m:lbp_units_occupied_by_families_less_than_or_equal_to_50_of_median p:long l:"LBP Units occupied by Families Less than or Equal to 50% of Median" t:dataTypeName=number

metric m:lbp_units_occupied_by_families_less_than_or_equal_to_80_of_median p:long l:"LBP Units occupied by Families Less than or Equal to 80% of Median" t:dataTypeName=number

entity e:azyf-k3d6 l:"Lead Based Paint Dwelling Statistics" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/azyf-k3d6

property e:azyf-k3d6 t:meta.view v:id=azyf-k3d6 v:category="Public Safety" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/pub/conplan12_amended_vol2.pdf v:averageRating=80 v:name="Lead Based Paint Dwelling Statistics" v:attribution="Department of City Planning (DCP)"

property e:azyf-k3d6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:azyf-k3d6 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | year_built  | total_units | estimate_of_percent_of_units_with_lbp | estimated_units_with_lbp | lbp_units_occupied_by_families_less_than_or_equal_to_50_of_median | lbp_units_occupied_by_families_less_than_or_equal_to_80_of_median | 
| =========== | =========== | =========== | ===================================== | ======================== | ================================================================= | ================================================================= | 
| 1360757851  | 1960+       | 779,347     | 0%                                    |                          |                                                                   |                                                                   | 
| 1360757851  | 1947-1959   | 458,592     | 69%                                   | 316,428                  | 119,294                                                           | 170,555                                                           | 
| 1360757851  | Before 1947 | 1,800,057   | 90%                                   | 1,620,051                | 562,158                                                           | 840,807                                                           | 
| 1360757851  | TOTAL       | 3,037,996   |                                       | 1,936,479                | 681,452                                                           | 1,011,362                                                         | 
```