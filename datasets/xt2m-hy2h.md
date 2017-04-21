# Approved Water Well And Closed Loop Well Grouts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/approved-water-well-and-closed-loop-well-grouts-77de0) |
| Metadata | [Link](https://data.illinois.gov/api/views/xt2m-hy2h) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xt2m-hy2h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xt2m-hy2h/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xt2m-hy2h |
| Name | Approved Water Well And Closed Loop Well Grouts |
| Attribution | Illinois Department of Public Health - Division of Environmental Health |
| Category | Public Health |
| Tags | grout, water, well |
| Created | 2014-10-09T15:23:47Z |
| Publication Date | 2014-10-29T14:43:32Z |

## Description

Approved Grouts for Well Casing Annular Space, Well and Borehole Abandonment, and Closed Loop Wells Meeting American National Standards Institute (ANSI)/NSF International (NSF) STD 60  Last Update October 2014

## Columns

```ls
| Included | Schema Type | Field Name      | Name             | Data Type | Render Type |
| ======== | =========== | =============== | ================ | ========= | =========== |
| No       | time        | :updated_at     | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | company         | Company          | text      | text        |
| Yes      | series tag  | product_name    | Product Name     | text      | text        |
| Yes      | series tag  | materials       | Materials        | text      | text        |
| Yes      | series tag  | specified_use_s | Specified Use(s) | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xt2m-hy2h d:2014-10-09T08:24:16.000Z t:specified_use_s="Well casing annular space, well abandonment & closed loop wells" t:materials="Sodium bentonite" t:product_name="Bentonite Grout" t:company="Black Hills Bentonite LLC" m:row_number.xt2m-hy2h=1

series e:xt2m-hy2h d:2014-10-09T08:24:16.000Z t:specified_use_s="Well abandonment" t:materials="Sodium bentonite" t:product_name="Bentonite Plug 3/8"" & 3/4"" chips" t:company="Black Hills Bentonite LLC" m:row_number.xt2m-hy2h=2

series e:xt2m-hy2h d:2014-10-09T08:24:16.000Z t:specified_use_s="Well casing annular space, well abandonment & closed loop wells" t:materials="Sodium bentonite" t:product_name="BH 20 Grout" t:company="Black Hills Bentonite LLC" m:row_number.xt2m-hy2h=3
```

## Meta Commands

```ls
metric m:row_number.xt2m-hy2h p:long l:"Row Number"

entity e:xt2m-hy2h l:"Approved Water Well And Closed Loop Well Grouts" t:attribution="Illinois Department of Public Health - Division of Environmental Health" t:url=https://data.illinois.gov/api/views/xt2m-hy2h

property e:xt2m-hy2h t:meta.view v:id=xt2m-hy2h v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/private-water v:averageRating=0 v:name="Approved Water Well And Closed Loop Well Grouts" v:attribution="Illinois Department of Public Health - Division of Environmental Health"

property e:xt2m-hy2h t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:xt2m-hy2h t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| :updated_at | company                                 | product_name                     | materials                                                 | specified_use_s                                                 | 
| =========== | ======================================= | ================================ | ========================================================= | =============================================================== | 
| 1412843056  | Black Hills Bentonite LLC               | Bentonite Grout                  | Sodium bentonite                                          | Well casing annular space, well abandonment & closed loop wells | 
| 1412843056  | Black Hills Bentonite LLC               | Bentonite Plug 3/8" & 3/4" chips | Sodium bentonite                                          | Well abandonment                                                | 
| 1412843056  | Black Hills Bentonite LLC               | BH 20 Grout                      | Sodium bentonite                                          | Well casing annular space, well abandonment & closed loop wells | 
| 1412843056  | Black Hills Bentonite LLC               | BH Grout Ultra                   | Sodium bentonite & thermal enhancement compound           | Closed loop wells                                               | 
| 1412843056  | Black Hills Bentonite LLC               | Thermal Grout Lite               | Sodium bentonite & thermal enhancement compound           | Closed loop wells                                               | 
| 1412843056  | Black Hills Bentonite LLC               | Thermal Grout Select             | Sodium bentonite & thermal enhancement compound           | Closed loop wells                                               | 
| 1412843056  | Black Hills Bentonite LLC/Geo Pro, Inc. | PowerTEC                         | Grout additive                                            | Closed loop wells                                               | 
| 1412843056  | Black Hills Bentonite LLC/Geo Pro, Inc. | PowerTECx                        | Grout additive                                            | Closed loop wells                                               | 
| 1412843056  | TCC Materials                           | Thermaseal C Geothermal Grout    | Geothermal Grout Mix                                      | Closed loop wells                                               | 
| 1412843056  | CETCO                                   | Belle Crumbles                   | Two step mixture of granular sodium bentonite and polymer | Closed loop wells & abandoned boreholes                         | 
```