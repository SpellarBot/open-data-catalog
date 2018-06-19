# WAOFM - April 1 - Population Change and Rank by County, 2010 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waofm-april-1-population-change-and-rank-by-county-2010-to-present-2bd56) |
| Metadata | [Link](https://data.wa.gov/api/views/x2dd-99tj) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/x2dd-99tj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/x2dd-99tj/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | x2dd-99tj |
| Name | WAOFM - April 1 - Population Change and Rank by County, 2010 to Present |
| Attribution | Washington State Office of Financial Management, Forecasting and Research Division |
| Category | Demographics |
| Tags | wa, washington, ofm, state, county, population, change, rank, annexation |
| Created | 2014-07-14T18:15:41Z |
| Publication Date | 2016-06-30T18:21:22Z |

## Description

Population change and rank by county, 2010 to present.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name      | Data Type | Render Type |
| ======== | ============== | =========== | ========= | ========= | =========== |
| Yes      | series tag     | county_name | COUNTY    | text      | text        |
| Yes      | numeric metric | pop_2010    | POP_2010  | number    | number      |
| Yes      | numeric metric | pop_2011    | POP_2011  | number    | number      |
| Yes      | numeric metric | pop_2012    | POP_2012  | number    | number      |
| Yes      | numeric metric | pop_2013    | POP_2013  | number    | number      |
| Yes      | numeric metric | pop_2014    | POP_2014  | number    | number      |
| Yes      | numeric metric | pop_2015    | POP_2015  | number    | number      |
| Yes      | numeric metric | pop_2016    | POP_2016  | number    | number      |
| Yes      | numeric metric | nc_10_11    | NC_10-11  | number    | number      |
| Yes      | numeric metric | nc_11_12    | NC_11-12  | number    | number      |
| Yes      | numeric metric | nc_12_13    | NC_12-13  | number    | number      |
| Yes      | numeric metric | nc_13_14    | NC_13-14  | number    | number      |
| Yes      | numeric metric | nc_14_15    | NC_14-15  | number    | number      |
| Yes      | numeric metric | nc_15_16    | NC_15-16  | number    | number      |
| Yes      | numeric metric | pc_10_11    | PC_10-11  | percent   | percent     |
| Yes      | numeric metric | pc_11_12    | PC_11-12  | percent   | percent     |
| Yes      | numeric metric | pc_12_13    | PC_12-13  | percent   | percent     |
| Yes      | numeric metric | pc_13_14    | PC_13-14  | percent   | percent     |
| Yes      | numeric metric | pc_14_15    | PC_14-15  | percent   | percent     |
| Yes      | numeric metric | pc_15_16    | PC_15-16  | percent   | percent     |
| Yes      | numeric metric | st_2010     | ST_2010   | percent   | percent     |
| Yes      | numeric metric | st_2011     | ST_2011   | percent   | percent     |
| Yes      | numeric metric | st_2012     | ST_2012   | percent   | percent     |
| Yes      | numeric metric | st_2013     | ST_2013   | percent   | percent     |
| Yes      | numeric metric | st_2014     | ST_2014   | percent   | percent     |
| Yes      | numeric metric | st_2015     | ST_2015   | percent   | percent     |
| Yes      | numeric metric | st_2016     | ST_2016   | percent   | percent     |
| Yes      | numeric metric | rank_2010   | RANK_2010 | number    | number      |
| Yes      | numeric metric | rank_2011   | RANK_2011 | number    | number      |
| Yes      | numeric metric | rank_2012   | RANK_2012 | number    | number      |
| Yes      | numeric metric | rank_2013   | RANK_2013 | number    | number      |
| Yes      | numeric metric | rank_2014   | RANK_2014 | number    | number      |
| Yes      | numeric metric | rank_2015   | RANK_2015 | number    | number      |
| Yes      | numeric metric | rank_2016   | RANK_2016 | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x2dd-99tj d:2010-01-01T00:00:00.000Z t:county_name=Adams m:pc_10_11=1.19 m:nc_10_11=222 m:pc_11_12=0.53 m:nc_11_12=100 m:nc_12_13=150 m:pc_15_16=0.52 m:nc_15_16=100 m:pc_13_14=1.04 m:pop_2015=19410 m:pop_2016=19510 m:rank_2016=31 m:rank_2015=31 m:rank_2014=31 m:pc_14_15=0.05 m:rank_2013=31 m:rank_2012=31 m:rank_2011=31 m:rank_2010=31 m:nc_13_14=200 m:st_2016=0.27 m:st_2015=0.27 m:pc_12_13=0.79 m:st_2012=0.28 m:pop_2014=19400 m:st_2011=0.28 m:pop_2013=19200 m:pop_2012=19050 m:st_2014=0.28 m:st_2013=0.28 m:pop_2011=18950 m:pop_2010=18728 m:st_2010=0.28 m:nc_14_15=10

series e:x2dd-99tj d:2010-01-01T00:00:00.000Z t:county_name=Asotin m:pc_10_11=0.12 m:nc_10_11=27 m:pc_11_12=0.23 m:nc_11_12=50 m:nc_12_13=100 m:pc_15_16=0.64 m:nc_15_16=140 m:pc_13_14=0.69 m:pop_2015=22010 m:pop_2016=22150 m:rank_2016=28 m:rank_2015=28 m:rank_2014=28 m:pc_14_15=0.27 m:rank_2013=28 m:rank_2012=28 m:rank_2011=28 m:rank_2010=28 m:nc_13_14=150 m:st_2016=0.31 m:st_2015=0.31 m:pc_12_13=0.46 m:st_2012=0.32 m:pop_2014=21950 m:st_2011=0.32 m:pop_2013=21800 m:pop_2012=21700 m:st_2014=0.32 m:st_2013=0.32 m:pop_2011=21650 m:pop_2010=21623 m:st_2010=0.32 m:nc_14_15=60

series e:x2dd-99tj d:2010-01-01T00:00:00.000Z t:county_name=Benton m:pc_10_11=1.55 m:nc_10_11=2723 m:pc_11_12=1.18 m:nc_11_12=2100 m:nc_12_13=3400 m:pc_15_16=1.01 m:nc_15_16=1910 m:pc_13_14=1.69 m:pop_2015=188590 m:pop_2016=190500 m:rank_2016=10 m:rank_2015=10 m:rank_2014=10 m:pc_14_15=1.12 m:rank_2013=10 m:rank_2012=10 m:rank_2011=10 m:rank_2010=10 m:nc_13_14=3100 m:st_2016=2.65 m:st_2015=2.67 m:pc_12_13=1.89 m:st_2012=2.64 m:pop_2014=186500 m:st_2011=2.63 m:pop_2013=183400 m:pop_2012=180000 m:st_2014=2.68 m:st_2013=2.66 m:pop_2011=177900 m:pop_2010=175177 m:st_2010=2.61 m:nc_14_15=2090
```

## Meta Commands

```ls
metric m:pop_2010 p:integer l:POP_2010 d:"Total population 2010" t:dataTypeName=number

metric m:pop_2011 p:integer l:POP_2011 d:"Total population 2011" t:dataTypeName=number

metric m:pop_2012 p:integer l:POP_2012 d:"Total population 2012" t:dataTypeName=number

metric m:pop_2013 p:integer l:POP_2013 d:"Total population 2013" t:dataTypeName=number

metric m:pop_2014 p:integer l:POP_2014 d:"Total population 2014" t:dataTypeName=number

metric m:pop_2015 p:integer l:POP_2015 d:"Total populaiton 2015" t:dataTypeName=number

metric m:pop_2016 p:integer l:POP_2016 d:"Total population 2014" t:dataTypeName=number

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

entity e:x2dd-99tj l:"WAOFM - April 1 - Population Change and Rank by County, 2010 to Present" t:attribution="Washington State Office of Financial Management, Forecasting and Research Division" t:url=https://data.wa.gov/api/views/x2dd-99tj

property e:x2dd-99tj t:meta.view v:id=x2dd-99tj v:category=Demographics v:attributionLink=http://www.ofm.wa.gov/pop/april1/default.asp v:averageRating=0 v:name="WAOFM - April 1 - Population Change and Rank by County, 2010 to Present" v:attribution="Washington State Office of Financial Management, Forecasting and Research Division"

property e:x2dd-99tj t:meta.view.license v:name="Public Domain"

property e:x2dd-99tj t:meta.view.owner v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:displayName="Thomas Kimpel"

property e:x2dd-99tj t:meta.view.tableauthor v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"
```

## Top Records

```ls
| county_name | pop_2010 | pop_2011 | pop_2012 | pop_2013 | pop_2014 | pop_2015 | pop_2016 | nc_10_11 | nc_11_12 | nc_12_13 | nc_13_14 | nc_14_15 | nc_15_16 | pc_10_11 | pc_11_12 | pc_12_13 | pc_13_14 | pc_14_15 | pc_15_16 | st_2010 | st_2011 | st_2012 | st_2013 | st_2014 | st_2015 | st_2016 | rank_2010 | rank_2011 | rank_2012 | rank_2013 | rank_2014 | rank_2015 | rank_2016 | 
| =========== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | 
| Adams       | 18728    | 18950    | 19050    | 19200    | 19400    | 19410    | 19510    | 222      | 100      | 150      | 200      | 10       | 100      | 1.19     | 0.53     | 0.79     | 1.04     | 0.05     | 0.52     | 0.28    | 0.28    | 0.28    | 0.28    | 0.28    | 0.27    | 0.27    | 31        | 31        | 31        | 31        | 31        | 31        | 31        | 
| Asotin      | 21623    | 21650    | 21700    | 21800    | 21950    | 22010    | 22150    | 27       | 50       | 100      | 150      | 60       | 140      | 0.12     | 0.23     | 0.46     | 0.69     | 0.27     | 0.64     | 0.32    | 0.32    | 0.32    | 0.32    | 0.32    | 0.31    | 0.31    | 28        | 28        | 28        | 28        | 28        | 28        | 28        | 
| Benton      | 175177   | 177900   | 180000   | 183400   | 186500   | 188590   | 190500   | 2723     | 2100     | 3400     | 3100     | 2090     | 1910     | 1.55     | 1.18     | 1.89     | 1.69     | 1.12     | 1.01     | 2.61    | 2.63    | 2.64    | 2.66    | 2.68    | 2.67    | 2.65    | 10        | 10        | 10        | 10        | 10        | 10        | 10        | 
| Chelan      | 72453    | 72700    | 73200    | 73600    | 74300    | 75030    | 75910    | 247      | 500      | 400      | 700      | 730      | 880      | 0.34     | 0.69     | 0.55     | 0.95     | 0.98     | 1.17     | 1.08    | 1.07    | 1.07    | 1.07    | 1.07    | 1.06    | 1.06    | 18        | 18        | 17        | 17        | 17        | 17        | 17        | 
| Clallam     | 71404    | 71600    | 72000    | 72350    | 72500    | 72650    | 73410    | 196      | 400      | 350      | 150      | 150      | 760      | 0.27     | 0.56     | 0.49     | 0.21     | 0.21     | 1.05     | 1.06    | 1.06    | 1.06    | 1.05    | 1.04    | 1.03    | 1.02    | 19        | 19        | 19        | 19        | 19        | 19        | 18        | 
| Clark       | 425363   | 428000   | 431250   | 435500   | 442800   | 451820   | 461010   | 2637     | 3250     | 4250     | 7300     | 9020     | 9190     | 0.62     | 0.76     | 0.99     | 1.68     | 2.04     | 2.03     | 6.33    | 6.32    | 6.33    | 6.33    | 6.35    | 6.40    | 6.42    | 5         | 5         | 5         | 5         | 5         | 5         | 5         | 
| Columbia    | 4078     | 4100     | 4100     | 4100     | 4080     | 4090     | 4050     | 22       | 0        | 0        | -20      | 10       | -40      | 0.54     | 0.00     | 0.00     | -0.49    | 0.25     | -0.98    | 0.06    | 0.06    | 0.06    | 0.06    | 0.06    | 0.06    | 0.06    | 37        | 37        | 37        | 37        | 37        | 37        | 37        | 
| Cowlitz     | 102410   | 102700   | 103050   | 103300   | 103700   | 104280   | 104850   | 290      | 350      | 250      | 400      | 580      | 570      | 0.28     | 0.34     | 0.24     | 0.39     | 0.56     | 0.55     | 1.52    | 1.52    | 1.51    | 1.50    | 1.49    | 1.48    | 1.46    | 12        | 12        | 12        | 12        | 12        | 12        | 12        | 
| Douglas     | 38431    | 38650    | 38900    | 39280    | 39700    | 39990    | 40720    | 219      | 250      | 380      | 420      | 290      | 730      | 0.57     | 0.65     | 0.98     | 1.07     | 0.73     | 1.83     | 0.57    | 0.57    | 0.57    | 0.57    | 0.57    | 0.57    | 0.57    | 26        | 26        | 26        | 26        | 26        | 26        | 26        | 
| Ferry       | 7551     | 7600     | 7650     | 7650     | 7660     | 7710     | 7700     | 49       | 50       | 0        | 10       | 50       | -10      | 0.65     | 0.66     | 0.00     | 0.13     | 0.65     | -0.13    | 0.11    | 0.11    | 0.11    | 0.11    | 0.11    | 0.11    | 0.11    | 36        | 36        | 36        | 36        | 36        | 36        | 36        | 
```