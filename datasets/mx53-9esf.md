# WAOFM - April 1 - Population Change and Rank by City, 2010 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waofm-april-1-population-change-and-rank-by-city-2010-to-present-25d73) |
| Metadata | [Link](https://data.wa.gov/api/views/mx53-9esf) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/mx53-9esf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/mx53-9esf/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | mx53-9esf |
| Name | WAOFM - April 1 - Population Change and Rank by City, 2010 to Present |
| Attribution | Washington State Office of Financial Management, Forecasting and Research Division |
| Category | Demographics |
| Tags | wa, washington, ofm, state, ciyy, population, change, rank, annexation |
| Created | 2014-07-14T18:31:36Z |
| Publication Date | 2016-06-30T18:22:41Z |

## Description

Population change and rank by city, 2010 to present.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | city_name  | CITY      | text      | text        |
| Yes      | numeric metric | pop_2010   | POP_2010  | number    | number      |
| Yes      | numeric metric | pop_2011   | POP_2011  | number    | number      |
| Yes      | numeric metric | pop_2012   | POP_2012  | number    | number      |
| Yes      | numeric metric | pop_2013   | POP_2013  | number    | number      |
| Yes      | numeric metric | pop_2014   | POP_2014  | number    | number      |
| Yes      | numeric metric | pop_2015   | POP_2015  | number    | number      |
| Yes      | numeric metric | pop_2016   | POP_2016  | number    | number      |
| Yes      | numeric metric | nc_10_11   | NC_10-11  | number    | number      |
| Yes      | numeric metric | nc_11_12   | NC_11-12  | number    | number      |
| Yes      | numeric metric | nc_12_13   | NC_12-13  | number    | number      |
| Yes      | numeric metric | nc_13_14   | NC_13-14  | number    | number      |
| Yes      | numeric metric | nc_14_15   | NC_14-15  | number    | number      |
| Yes      | numeric metric | nc_15_16   | NC_15-16  | number    | number      |
| Yes      | numeric metric | pc_10_11   | PC_10-11  | percent   | percent     |
| Yes      | numeric metric | pc_11_12   | PC_11-12  | percent   | percent     |
| Yes      | numeric metric | pc_12_13   | PC_12-13  | percent   | percent     |
| Yes      | numeric metric | pc_13_14   | PC_13-14  | percent   | percent     |
| Yes      | numeric metric | pc_14_15   | PC_14-15  | percent   | percent     |
| Yes      | numeric metric | pc_15_16   | PC_15-16  | percent   | percent     |
| Yes      | numeric metric | st_2010    | ST_2010   | percent   | percent     |
| Yes      | numeric metric | st_2011    | ST_2011   | percent   | percent     |
| Yes      | numeric metric | st_2012    | ST_2012   | percent   | percent     |
| Yes      | numeric metric | st_2013    | ST_2013   | percent   | percent     |
| Yes      | numeric metric | st_2014    | ST_2014   | percent   | percent     |
| Yes      | numeric metric | st_2015    | ST_2015   | percent   | percent     |
| Yes      | numeric metric | st_2016    | ST_2016   | percent   | percent     |
| Yes      | numeric metric | rank_2010  | RANK_2010 | number    | number      |
| Yes      | numeric metric | rank_2011  | RANK_2011 | number    | number      |
| Yes      | numeric metric | rank_2012  | RANK_2012 | number    | number      |
| Yes      | numeric metric | rank_2013  | RANK_2013 | number    | number      |
| Yes      | numeric metric | rank_2014  | RANK_2014 | number    | number      |
| Yes      | numeric metric | rank_2015  | RANK_2015 | number    | number      |
| Yes      | numeric metric | rank_2016  | RANK_2016 | number    | number      |
| Yes      | numeric metric | anx_10_11  | ANX_10-11 | number    | number      |
| Yes      | numeric metric | anx_11_12  | ANX_11-12 | number    | number      |
| Yes      | numeric metric | anx_12_13  | ANX_12-13 | number    | number      |
| Yes      | numeric metric | anx_13_14  | ANX_13-14 | number    | number      |
| Yes      | numeric metric | anx_14_15  | ANX_14-15 | number    | number      |
| Yes      | numeric metric | anx_15_16  | ANX_15-16 | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mx53-9esf d:2010-01-01T00:00:00.000Z t:city_name=Aberdeen m:anx_11_12=0 m:pc_10_11=-0.15 m:nc_10_11=-26 m:anx_14_15=0 m:pc_11_12=0.12 m:nc_11_12=20 m:nc_12_13=-30 m:anx_13_14=0 m:pc_15_16=0 m:nc_15_16=0 m:pc_13_14=-0.06 m:pop_2015=16780 m:pop_2016=16780 m:anx_10_11=0 m:rank_2016=61 m:rank_2015=61 m:rank_2014=60 m:pc_14_15=-0.42 m:rank_2013=60 m:rank_2012=60 m:rank_2011=60 m:rank_2010=60 m:nc_13_14=-10 m:st_2016=0.234 m:st_2015=0.238 m:pc_12_13=-0.18 m:st_2012=0.248 m:pop_2014=16850 m:st_2011=0.249 m:pop_2013=16860 m:pop_2012=16890 m:st_2014=0.242 m:st_2013=0.245 m:pop_2011=16870 m:pop_2010=16896 m:anx_12_13=0 m:st_2010=0.251 m:nc_14_15=-70 m:anx_15_16=0

series e:mx53-9esf d:2010-01-01T00:00:00.000Z t:city_name="Airway Heights" m:anx_11_12=1419 m:pc_10_11=1.73 m:nc_10_11=106 m:anx_14_15=0 m:pc_11_12=25.08 m:nc_11_12=1560 m:nc_12_13=155 m:anx_13_14=0 m:pc_15_16=0.48 m:nc_15_16=40 m:pc_13_14=0.44 m:pop_2015=8385 m:pop_2016=8425 m:anx_10_11=0 m:rank_2016=94 m:rank_2015=93 m:rank_2014=93 m:pc_14_15=5.21 m:rank_2013=92 m:rank_2012=92 m:rank_2011=107 m:rank_2010=108 m:nc_13_14=35 m:st_2016=0.117 m:st_2015=0.119 m:pc_12_13=1.99 m:st_2012=0.114 m:pop_2014=7970 m:st_2011=0.092 m:pop_2013=7935 m:pop_2012=7780 m:st_2014=0.114 m:st_2013=0.115 m:pop_2011=6220 m:pop_2010=6114 m:anx_12_13=0 m:st_2010=0.091 m:nc_14_15=415 m:anx_15_16=0

series e:mx53-9esf d:2010-01-01T00:00:00.000Z t:city_name=Albion m:anx_11_12=0 m:pc_10_11=-4.15 m:nc_10_11=-24 m:anx_14_15=0 m:pc_11_12=-1.8 m:nc_11_12=-10 m:nc_12_13=5 m:anx_13_14=0 m:pc_15_16=-1.8 m:nc_15_16=-10 m:pc_13_14=0.91 m:pop_2015=555 m:pop_2016=545 m:anx_10_11=0 m:rank_2016=232 m:rank_2015=231 m:rank_2014=231 m:pc_14_15=0 m:rank_2013=232 m:rank_2012=232 m:rank_2011=231 m:rank_2010=226 m:nc_13_14=5 m:st_2016=0.008 m:st_2015=0.008 m:pc_12_13=0.92 m:st_2012=0.008 m:pop_2014=555 m:st_2011=0.008 m:pop_2013=550 m:pop_2012=545 m:st_2014=0.008 m:st_2013=0.008 m:pop_2011=555 m:pop_2010=579 m:anx_12_13=0 m:st_2010=0.009 m:nc_14_15=0 m:anx_15_16=0
```

## Meta Commands

```ls
metric m:pop_2010 p:integer l:POP_2010 d:"Total population 2010" t:dataTypeName=number

metric m:pop_2011 p:integer l:POP_2011 d:"Total population 2011" t:dataTypeName=number

metric m:pop_2012 p:integer l:POP_2012 d:"Total population 2012" t:dataTypeName=number

metric m:pop_2013 p:integer l:POP_2013 d:"Total population 2013" t:dataTypeName=number

metric m:pop_2014 p:integer l:POP_2014 d:"Total population 2014" t:dataTypeName=number

metric m:pop_2015 p:integer l:POP_2015 d:"Total population 2015" t:dataTypeName=number

metric m:pop_2016 p:integer l:POP_2016 d:"Total population 2016" t:dataTypeName=number

metric m:nc_10_11 p:integer l:NC_10-11 d:"Numeric change in population 2010 - 2011" t:dataTypeName=number

metric m:nc_11_12 p:integer l:NC_11-12 d:"Numeric change in population 2011 - 2012" t:dataTypeName=number

metric m:nc_12_13 p:integer l:NC_12-13 d:"Numeric change in population 2012 - 2013" t:dataTypeName=number

metric m:nc_13_14 p:integer l:NC_13-14 d:"Numeric change in population 2013 - 2014" t:dataTypeName=number

metric m:nc_14_15 p:integer l:NC_14-15 d:"Numeric change in population 2014 - 2015" t:dataTypeName=number

metric m:nc_15_16 p:integer l:NC_15-16 d:"Numeric change in population 2015 - 2016" t:dataTypeName=number

metric m:pc_10_11 p:float l:PC_10-11 d:"Percent change in population 2010 - 2011" t:dataTypeName=percent

metric m:pc_11_12 p:float l:PC_11-12 d:"Percent change in population 2011 - 2012" t:dataTypeName=percent

metric m:pc_12_13 p:float l:PC_12-13 d:"Percent change in population 2012 - 2013" t:dataTypeName=percent

metric m:pc_13_14 p:float l:PC_13-14 d:"Percent change in population 2013 - 2014" t:dataTypeName=percent

metric m:pc_14_15 p:float l:PC_14-15 d:"Percent change in population 2014 - 2015" t:dataTypeName=percent

metric m:pc_15_16 p:float l:PC_15-16 d:"Percent change in population 2015 - 2016" t:dataTypeName=percent

metric m:st_2010 p:float l:ST_2010 d:"Share of state total population 2010" t:dataTypeName=percent

metric m:st_2011 p:float l:ST_2011 d:"Share of state total population 2011" t:dataTypeName=percent

metric m:st_2012 p:float l:ST_2012 d:"Share of state total population 2012" t:dataTypeName=percent

metric m:st_2013 p:float l:ST_2013 d:"Share of state total population 2013" t:dataTypeName=percent

metric m:st_2014 p:float l:ST_2014 d:"Share of state total population 2014" t:dataTypeName=percent

metric m:st_2015 p:float l:ST_2015 d:"Share of state total population 2015" t:dataTypeName=percent

metric m:st_2016 p:float l:ST_2016 d:"Share of state total population 2016" t:dataTypeName=percent

metric m:rank_2010 p:integer l:RANK_2010 d:"Population rank 2010" t:dataTypeName=number

metric m:rank_2011 p:integer l:RANK_2011 d:"Population rank 2011" t:dataTypeName=number

metric m:rank_2012 p:integer l:RANK_2012 d:"Population rank 2012" t:dataTypeName=number

metric m:rank_2013 p:integer l:RANK_2013 d:"Population rank 2013" t:dataTypeName=number

metric m:rank_2014 p:integer l:RANK_2014 d:"Population rank 2014" t:dataTypeName=number

metric m:rank_2015 p:integer l:RANK_2015 d:"Population rank 2015" t:dataTypeName=number

metric m:rank_2016 p:integer l:RANK_2016 d:"Population rank 2016" t:dataTypeName=number

metric m:anx_10_11 p:integer l:ANX_10-11 d:"Population change due to annexation 2010 -2011" t:dataTypeName=number

metric m:anx_11_12 p:integer l:ANX_11-12 d:"Population change due to annexation 2011 -2012" t:dataTypeName=number

metric m:anx_12_13 p:integer l:ANX_12-13 d:"Population change due to annexation 2012 -2013" t:dataTypeName=number

metric m:anx_13_14 p:integer l:ANX_13-14 d:"Population change due to annexation 2013 -2014" t:dataTypeName=number

metric m:anx_14_15 p:integer l:ANX_14-15 d:"Population change due to annexation 2014 - 2015" t:dataTypeName=number

metric m:anx_15_16 p:integer l:ANX_15-16 d:"Population change due to annexation 2015 -2016" t:dataTypeName=number

entity e:mx53-9esf l:"WAOFM - April 1 - Population Change and Rank by City, 2010 to Present" t:attribution="Washington State Office of Financial Management, Forecasting and Research Division" t:url=https://data.wa.gov/api/views/mx53-9esf

property e:mx53-9esf t:meta.view v:id=mx53-9esf v:category=Demographics v:attributionLink=http://www.ofm.wa.gov/pop/april1/default.asp v:averageRating=0 v:name="WAOFM - April 1 - Population Change and Rank by City, 2010 to Present" v:attribution="Washington State Office of Financial Management, Forecasting and Research Division"

property e:mx53-9esf t:meta.view.license v:name="Public Domain"

property e:mx53-9esf t:meta.view.owner v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:displayName="Thomas Kimpel"

property e:mx53-9esf t:meta.view.tableauthor v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"
```

## Top Records

```ls
| city_name         | pop_2010 | pop_2011 | pop_2012 | pop_2013 | pop_2014 | pop_2015 | pop_2016 | nc_10_11 | nc_11_12 | nc_12_13 | nc_13_14 | nc_14_15 | nc_15_16 | pc_10_11 | pc_11_12 | pc_12_13 | pc_13_14 | pc_14_15 | pc_15_16 | st_2010 | st_2011 | st_2012 | st_2013 | st_2014 | st_2015 | st_2016 | rank_2010 | rank_2011 | rank_2012 | rank_2013 | rank_2014 | rank_2015 | rank_2016 | anx_10_11 | anx_11_12 | anx_12_13 | anx_13_14 | anx_14_15 | anx_15_16 | 
| ================= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | 
| Aberdeen          | 16896    | 16870    | 16890    | 16860    | 16850    | 16780    | 16780    | -26      | 20       | -30      | -10      | -70      | 0        | -0.15    | 0.12     | -0.18    | -0.06    | -0.42    | 0.00     | 0.251   | 0.249   | 0.248   | 0.245   | 0.242   | 0.238   | 0.234   | 60        | 60        | 60        | 60        | 60        | 61        | 61        | 0         | 0         | 0         | 0         | 0         | 0         | 
| Airway Heights    | 6114     | 6220     | 7780     | 7935     | 7970     | 8385     | 8425     | 106      | 1560     | 155      | 35       | 415      | 40       | 1.73     | 25.08    | 1.99     | 0.44     | 5.21     | 0.48     | 0.091   | 0.092   | 0.114   | 0.115   | 0.114   | 0.119   | 0.117   | 108       | 107       | 92        | 92        | 93        | 93        | 94        | 0         | 1419      | 0         | 0         | 0         | 0         | 
| Albion            | 579      | 555      | 545      | 550      | 555      | 555      | 545      | -24      | -10      | 5        | 5        | 0        | -10      | -4.15    | -1.80    | 0.92     | 0.91     | 0.00     | -1.80    | 0.009   | 0.008   | 0.008   | 0.008   | 0.008   | 0.008   | 0.008   | 226       | 231       | 232       | 232       | 231       | 231       | 232       | 0         | 0         | 0         | 0         | 0         | 0         | 
| Algona            | 3014     | 3055     | 3070     | 3075     | 3090     | 3105     | 3175     | 41       | 15       | 5        | 15       | 15       | 70       | 1.36     | 0.49     | 0.16     | 0.49     | 0.49     | 2.25     | 0.045   | 0.045   | 0.045   | 0.045   | 0.044   | 0.044   | 0.044   | 138       | 138       | 138       | 138       | 138       | 138       | 136       | 0         | 0         | 0         | 0         | 0         | 0         | 
| Almira            | 284      | 285      | 285      | 285      | 280      | 280      | 275      | 1        | 0        | 0        | -5       | 0        | -5       | 0.35     | 0.00     | 0.00     | -1.75    | 0.00     | -1.79    | 0.004   | 0.004   | 0.004   | 0.004   | 0.004   | 0.004   | 0.004   | 257       | 256       | 256       | 256       | 258       | 259       | 259       | 0         | 0         | 0         | 0         | 0         | 0         | 
| Anacortes         | 15778    | 15860    | 15960    | 16080    | 16190    | 16310    | 16580    | 82       | 100      | 120      | 110      | 120      | 270      | 0.52     | 0.63     | 0.75     | 0.68     | 0.74     | 1.66     | 0.235   | 0.234   | 0.234   | 0.234   | 0.232   | 0.231   | 0.231   | 63        | 63        | 63        | 63        | 63        | 62        | 62        | 0         | 0         | 0         | 0         | 0         | 0         | 
| Arlington         | 17926    | 17930    | 17970    | 18270    | 18360    | 18490    | 18620    | 4        | 40       | 300      | 90       | 130      | 130      | 0.02     | 0.22     | 1.67     | 0.49     | 0.71     | 0.70     | 0.267   | 0.265   | 0.264   | 0.265   | 0.263   | 0.262   | 0.259   | 54        | 54        | 54        | 55        | 58        | 58        | 58        | 0         | 18        | 18        | 6         | 0         | 0         | 
| Asotin            | 1251     | 1255     | 1255     | 1265     | 1265     | 1260     | 1270     | 4        | 0        | 10       | 0        | -5       | 10       | 0.32     | 0.00     | 0.80     | 0.00     | -0.40    | 0.79     | 0.019   | 0.019   | 0.018   | 0.018   | 0.018   | 0.018   | 0.018   | 188       | 188       | 188       | 188       | 188       | 188       | 189       | 0         | 0         | 0         | 0         | 0         | 0         | 
| Auburn            | 70180    | 70705    | 71240    | 73235    | 74630    | 75545    | 77060    | 525      | 535      | 1995     | 1395     | 915      | 1515     | 0.75     | 0.76     | 2.80     | 1.90     | 1.23     | 2.01     | 1.044   | 1.045   | 1.045   | 1.064   | 1.071   | 1.070   | 1.073   | 14        | 14        | 15        | 15        | 15        | 15        | 15        | 0         | 0         | 0         | 0         | 0         | 0         | 
| Bainbridge Island | 23025    | 23030    | 23090    | 23190    | 23360    | 23390    | 23760    | 5        | 60       | 100      | 170      | 30       | 370      | 0.02     | 0.26     | 0.43     | 0.73     | 0.13     | 1.58     | 0.342   | 0.340   | 0.339   | 0.337   | 0.335   | 0.331   | 0.331   | 41        | 41        | 42        | 42        | 42        | 43        | 42        | 0         | 0         | 0         | 0         | 0         | 0         | 
```