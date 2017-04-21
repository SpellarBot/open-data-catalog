# Solar Cities by Total Installed Solar PV Capacity, End of 2015 (Source: Shining Cities 2016)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/first-in-nation-2013-the-solar-stars-cities-with-more-than-50-watts-of-installed-solar-pv--d2db6) |
| Metadata | [Link](https://data.hawaii.gov/api/views/y8bh-mdgv) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/y8bh-mdgv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/y8bh-mdgv/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | y8bh-mdgv |
| Name | Solar Cities by Total Installed Solar PV Capacity, End of 2015 (Source: Shining Cities 2016) |
| Created | 2014-05-02T23:20:05Z |
| Publication Date | 2016-11-28T22:29:26Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================== | ========= | =========== |
| Yes      | series tag     | principal_city                            | City                                       | text      | text        |
| Yes      | series tag     | cumulative_solar_pv_capacity_mw           | State                                      | text      | text        |
| Yes      | numeric metric | solar_pv_capacity_per_capita_watts_person | Total Solar PV Rank                        | number    | number      |
| Yes      | numeric metric | cumulative_solar_electricity_capacity_mw  | Cumulative Solar Electricity Capacity (MW) | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y8bh-mdgv d:2015-01-01T00:00:00.000Z t:cumulative_solar_pv_capacity_mw=CA t:principal_city="Los Angeles" m:cumulative_solar_electricity_capacity_mw=215 m:solar_pv_capacity_per_capita_watts_person=1

series e:y8bh-mdgv d:2015-01-01T00:00:00.000Z t:cumulative_solar_pv_capacity_mw=CA t:principal_city="San Diego" m:cumulative_solar_electricity_capacity_mw=189 m:solar_pv_capacity_per_capita_watts_person=2

series e:y8bh-mdgv d:2015-01-01T00:00:00.000Z t:cumulative_solar_pv_capacity_mw=AZ t:principal_city=Phoenix m:cumulative_solar_electricity_capacity_mw=147 m:solar_pv_capacity_per_capita_watts_person=3
```

## Meta Commands

```ls
metric m:solar_pv_capacity_per_capita_watts_person p:integer l:"Total Solar PV Rank" t:dataTypeName=number

metric m:cumulative_solar_electricity_capacity_mw p:integer l:"Cumulative Solar Electricity Capacity (MW)" t:dataTypeName=number

entity e:y8bh-mdgv l:"Solar Cities by Total Installed Solar PV Capacity, End of 2015 (Source: Shining Cities 2016)" t:url=https://data.hawaii.gov/api/views/y8bh-mdgv

property e:y8bh-mdgv t:meta.view v:id=y8bh-mdgv v:averageRating=0 v:name="Solar Cities by Total Installed Solar PV Capacity, End of 2015 (Source: Shining Cities 2016)"

property e:y8bh-mdgv t:meta.view.owner v:id=vf6n-ptiq v:screenName=Kathy v:displayName=Kathy

property e:y8bh-mdgv t:meta.view.tableauthor v:id=vf6n-ptiq v:screenName=Kathy v:roleName=publisher v:displayName=Kathy
```

## Top Records

```ls
| principal_city | cumulative_solar_pv_capacity_mw | solar_pv_capacity_per_capita_watts_person | cumulative_solar_electricity_capacity_mw | 
| ============== | =============================== | ========================================= | ======================================== | 
| Los Angeles    | CA                              | 1                                         | 215                                      | 
| San Diego      | CA                              | 2                                         | 189                                      | 
| Phoenix        | AZ                              | 3                                         | 147                                      | 
| Honolulu       | HI                              | 4                                         | 146                                      | 
| San Jose       | CA                              | 5                                         | 141                                      | 
```