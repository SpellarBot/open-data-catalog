# Recycling Diversion and Capture Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recycling-diversion-and-capture-rates-dcaef) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gaq9-z3hz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gaq9-z3hz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gaq9-z3hz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gaq9-z3hz |
| Name | Recycling Diversion and Capture Rates |
| Attribution | Department of Sanitation (DSNY) |
| Category | Environment |
| Tags | sanitation, dsny, refuse, recycle, recycling, plastic, metal, paper, community, community district, tonnage, capture, diversion, clean web |
| Created | 2011-10-21T20:29:47Z |
| Publication Date | 2013-06-21T19:42:15Z |

## Description

For each Community District, its Recycling Diversion rate (percentage of total municipal solid waste collected by the Department of Sanitation (DSNY that is disposed of by recycling) and Capture Rate (% of total Paper or Metal/Glass/Plastic in the waste stream that is disposed of by recycling).

## Columns

```ls
| Included | Schema Type    | Field Name                                                                 | Name                                                                                    | Data Type | Render Type |
| ======== | ============== | ========================================================================== | ======================================================================================= | ========= | =========== |
| Yes      | series tag     | zone                                                                       | Zone                                                                                    | text      | text        |
| Yes      | series tag     | district                                                                   | District                                                                                | text      | text        |
| Yes      | series tag     | fiscal_month_number                                                        | Fiscal Month Number                                                                     | text      | number      |
| Yes      | time           | fiscal_year                                                                | Fiscal Year                                                                             | number    | number      |
| Yes      | series tag     | month_name                                                                 | Month Name                                                                              | text      | text        |
| Yes      | numeric metric | diversion_rate_total_total_recycling_total_waste_                          | Diversion Rate-Total (Total Recycling / Total Waste)                                    | number    | number      |
| Yes      | numeric metric | capture_rate_paper_total_paper_max_paper_                                  | Capture Rate-Paper (Total Paper / Max Paper)                                            | number    | number      |
| Yes      | numeric metric | capture_rate_mgp_total_mgp_max_mgp_                                        | Capture Rate-MGP (Total MGP / Max MGP)                                                  | number    | number      |
| Yes      | numeric metric | capture_rate_total_total_recycling_leaves_recycling_max_paper_max_mgp_x100 | Capture Rate-Total ((Total Recycling - Leaves (Recycling)) / (Max Paper + Max MGP))x100 | number    | number      |
| Yes      | series tag     | report_version                                                             | Report Version                                                                          | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gaq9-z3hz d:2010-01-01T00:00:00.000Z t:fiscal_month_number=11 t:report_version=Preliminary t:month_name=May t:district=MN01 t:zone=Manhattan m:capture_rate_total_total_recycling_leaves_recycling_max_paper_max_mgp_x100=58.17548421760927 m:diversion_rate_total_total_recycling_total_waste_=29.27665128471074 m:capture_rate_mgp_total_mgp_max_mgp_=70.18897504989712 m:capture_rate_paper_total_paper_max_paper_=54.36418863721333

series e:gaq9-z3hz d:2010-01-01T00:00:00.000Z t:fiscal_month_number=11 t:report_version=Preliminary t:month_name=May t:district=MN02 t:zone=Manhattan m:capture_rate_total_total_recycling_leaves_recycling_max_paper_max_mgp_x100=52.65407008739176 m:diversion_rate_total_total_recycling_total_waste_=26.498014918158198 m:capture_rate_mgp_total_mgp_max_mgp_=78.96740781007655 m:capture_rate_paper_total_paper_max_paper_=44.3061294956033

series e:gaq9-z3hz d:2010-01-01T00:00:00.000Z t:fiscal_month_number=11 t:report_version=Preliminary t:month_name=May t:district=MN03 t:zone=Manhattan m:capture_rate_total_total_recycling_leaves_recycling_max_paper_max_mgp_x100=43.99317105744572 m:diversion_rate_total_total_recycling_total_waste_=13.098489950168535 m:capture_rate_mgp_total_mgp_max_mgp_=39.4573747627649 m:capture_rate_paper_total_paper_max_paper_=47.50990064774443
```

## Meta Commands

```ls
metric m:diversion_rate_total_total_recycling_total_waste_ p:double l:"Diversion Rate-Total (Total Recycling / Total Waste)" t:dataTypeName=number

metric m:capture_rate_paper_total_paper_max_paper_ p:double l:"Capture Rate-Paper (Total Paper / Max Paper)" t:dataTypeName=number

metric m:capture_rate_mgp_total_mgp_max_mgp_ p:double l:"Capture Rate-MGP (Total MGP / Max MGP)" t:dataTypeName=number

metric m:capture_rate_total_total_recycling_leaves_recycling_max_paper_max_mgp_x100 p:double l:"Capture Rate-Total ((Total Recycling - Leaves (Recycling)) / (Max Paper + Max MGP))x100" t:dataTypeName=number

entity e:gaq9-z3hz l:"Recycling Diversion and Capture Rates" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/gaq9-z3hz

property e:gaq9-z3hz t:meta.view v:id=gaq9-z3hz v:category=Environment v:averageRating=0 v:name="Recycling Diversion and Capture Rates" v:attribution="Department of Sanitation (DSNY)"

property e:gaq9-z3hz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gaq9-z3hz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| zone      | district | fiscal_month_number | fiscal_year | month_name | diversion_rate_total_total_recycling_total_waste_ | capture_rate_paper_total_paper_max_paper_ | capture_rate_mgp_total_mgp_max_mgp_ | capture_rate_total_total_recycling_leaves_recycling_max_paper_max_mgp_x100 | report_version | 
| ========= | ======== | =================== | =========== | ========== | ================================================= | ========================================= | =================================== | ========================================================================== | ============== | 
| Manhattan | MN01     | 11                  | 2010        | May        | 29.27665128471074                                 | 54.36418863721333                         | 70.18897504989712                   | 58.17548421760927                                                          | Preliminary    | 
| Manhattan | MN02     | 11                  | 2010        | May        | 26.498014918158198                                | 44.3061294956033                          | 78.96740781007655                   | 52.65407008739176                                                          | Preliminary    | 
| Manhattan | MN03     | 11                  | 2010        | May        | 13.098489950168535                                | 47.50990064774443                         | 39.4573747627649                    | 43.99317105744572                                                          | Preliminary    | 
| Manhattan | MN04     | 11                  | 2010        | May        | 23.12284619426574                                 | 37.37981430019573                         | 72.95261708509696                   | 45.94728955709539                                                          | Preliminary    | 
| Manhattan | MN05     | 11                  | 2010        | May        | 23.78701035903557                                 | 41.13240782129411                         | 66.60389097792556                   | 47.267046776243184                                                         | Preliminary    | 
| Manhattan | MN06     | 11                  | 2010        | May        | 25.414851507225517                                | 42.41544252002771                         | 75.99028254954865                   | 50.50172160651501                                                          | Preliminary    | 
| Manhattan | MN07     | 11                  | 2010        | May        | 24.381685580830855                                | 43.01477133685949                         | 65.57694753203836                   | 48.448722871767814                                                         | Preliminary    | 
| Manhattan | MN08     | 11                  | 2010        | May        | 24.47817040494805                                 | 43.50095429530655                         | 64.84051678971925                   | 48.640447372909755                                                         | Preliminary    | 
| Manhattan | MN09     | 11                  | 2010        | May        | 13.032073855464882                                | 49.73270669761759                         | 36.0796750024943                    | 43.770103007129954                                                         | Preliminary    | 
| Manhattan | MN10     | 11                  | 2010        | May        | 9.136803709369874                                 | 33.21156946037611                         | 27.431499457387808                  | 30.687275406081554                                                         | Preliminary    | 
```