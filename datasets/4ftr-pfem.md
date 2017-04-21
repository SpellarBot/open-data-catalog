# LADWP Energy Efficiency for FY 13-14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ladwp-energy-efficiency-for-fy-13-14-4f9a4) |
| Metadata | [Link](https://data.lacity.org/api/views/4ftr-pfem) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/4ftr-pfem/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/4ftr-pfem/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 4ftr-pfem |
| Name | LADWP Energy Efficiency for FY 13-14 |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Tags | energy efficiency, conservation |
| Created | 2014-05-15T01:05:53Z |
| Publication Date | 2014-05-19T20:35:47Z |

## Description

Listing of LADWP's Energy Efficiency Programs and Energy Savings for Fiscal Year 2013-14

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | type_of_program | Type of Program | text      | text        |
| Yes      | series tag     | program         | Program         | text      | text        |
| Yes      | series tag     | metric          | Metric          | text      | text        |
| Yes      | numeric metric | 7_13            | 7/13            | number    | number      |
| Yes      | numeric metric | 8_13            | 8/13            | number    | number      |
| Yes      | numeric metric | 9_13            | 9/13            | number    | number      |
| Yes      | numeric metric | 10_13           | 10/13           | number    | number      |
| Yes      | numeric metric | 11_13           | 11/13           | number    | number      |
| Yes      | numeric metric | 12_13           | 12/13           | number    | number      |
| Yes      | numeric metric | 1_14            | 1/14            | number    | number      |
| Yes      | numeric metric | 2_14            | 2/14            | number    | number      |
| Yes      | numeric metric | 3_14            | 3/14            | number    | number      |
| Yes      | numeric metric | 4_14            | 4/14            | number    | number      |
| Yes      | numeric metric | 5_14            | 5/14            | number    | number      |
| Yes      | numeric metric | 6_14            | 6/14            | number    | number      |
| Yes      | numeric metric | total_ytd       | Total YTD       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4ftr-pfem d:2014-05-14T18:05:57.000Z t:program="Chiller Efficiency (CEP)" t:metric="Monthly KWh Target" t:type_of_program="CII Program" m:1_14=240000 m:7_13=60000 m:11_13=240000 m:3_14=300000 m:2_14=300000 m:6_14=420000 m:4_14=360000 m:10_13=180000 m:8_13=120000 m:5_14=360000 m:12_13=240000 m:9_13=180000 m:total_ytd=3000000

series e:4ftr-pfem d:2014-05-14T18:05:57.000Z t:program="Chiller Efficiency (CEP)" t:metric="Monthly KWh Actual" t:type_of_program="CII Program" m:7_13=40815 m:3_14=628644 m:10_13=966634 m:9_13=380234 m:total_ytd=2016327

series e:4ftr-pfem d:2014-05-14T18:05:57.000Z t:program="Commercial Lightning Efficiency Offering" t:metric="Monthly KWh Target" t:type_of_program="CII Program" m:1_14=1790000 m:7_13=1720000 m:11_13=2440000 m:3_14=4670000 m:2_14=4170000 m:6_14=2870000 m:4_14=6040000 m:10_13=2930000 m:8_13=2160000 m:5_14=4810000 m:12_13=1590000 m:9_13=810000 m:total_ytd=36000000
```

## Meta Commands

```ls
metric m:7_13 p:integer l:7/13 t:dataTypeName=number

metric m:8_13 p:integer l:8/13 t:dataTypeName=number

metric m:9_13 p:integer l:9/13 t:dataTypeName=number

metric m:10_13 p:integer l:10/13 t:dataTypeName=number

metric m:11_13 p:integer l:11/13 t:dataTypeName=number

metric m:12_13 p:integer l:12/13 t:dataTypeName=number

metric m:1_14 p:integer l:1/14 t:dataTypeName=number

metric m:2_14 p:integer l:2/14 t:dataTypeName=number

metric m:3_14 p:integer l:3/14 t:dataTypeName=number

metric m:4_14 p:integer l:4/14 t:dataTypeName=number

metric m:5_14 p:integer l:5/14 t:dataTypeName=number

metric m:6_14 p:integer l:6/14 t:dataTypeName=number

metric m:total_ytd p:integer l:"Total YTD" t:dataTypeName=number

entity e:4ftr-pfem l:"LADWP Energy Efficiency for FY 13-14" t:attribution=LADWP t:url=https://data.lacity.org/api/views/4ftr-pfem

property e:4ftr-pfem t:meta.view v:id=4ftr-pfem v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LADWP Energy Efficiency for FY 13-14" v:attribution=LADWP

property e:4ftr-pfem t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:4ftr-pfem t:meta.view.owner v:id=7q7s-tyf3 v:screenName="Steve Baule" v:displayName="Steve Baule"

property e:4ftr-pfem t:meta.view.tableauthor v:id=7q7s-tyf3 v:screenName="Steve Baule" v:roleName=publisher v:displayName="Steve Baule"
```

## Top Records

```ls
| :updated_at | type_of_program | program                                  | metric             | 7_13    | 8_13    | 9_13    | 10_13   | 11_13   | 12_13    | 1_14    | 2_14    | 3_14    | 4_14    | 5_14    | 6_14    | total_ytd | 
| =========== | =============== | ======================================== | ================== | ======= | ======= | ======= | ======= | ======= | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ========= | 
| 1400090757  | CII Program     | Chiller Efficiency (CEP)                 | Monthly KWh Target | 60000   | 120000  | 180000  | 180000  | 240000  | 240000   | 240000  | 300000  | 300000  | 360000  | 360000  | 420000  | 3000000   | 
| 1400090757  | CII Program     | Chiller Efficiency (CEP)                 | Monthly KWh Actual | 40815   |         | 380234  | 966634  |         |          |         |         | 628644  |         |         |         | 2016327   | 
| 1400090757  | CII Program     | Commercial Lightning Efficiency Offering | Monthly KWh Target | 1720000 | 2160000 | 810000  | 2930000 | 2440000 | 1590000  | 1790000 | 4170000 | 4670000 | 6040000 | 4810000 | 2870000 | 36000000  | 
| 1400090757  | CII Program     | Commercial Lightning Efficiency Offering | Monthly KWh Actual | 1223787 | 2913115 | 2200443 | 3621522 | 2038983 | 873599   | 1679075 | 3371061 | 4477011 |         |         |         | 22398596  | 
| 1400090757  | CII Program     | Custom Performance Program (CPP)         | Monthly KWh Target | 1080000 | 2160000 | 3240000 | 3240000 | 4320000 | 4320000  | 4320000 | 5400000 | 5400000 | 6480000 | 6480000 | 7560000 | 54000000  | 
| 1400090757  | CII Program     | Custom Performance Program (CPP)         | Monthly KWh Actual |         | 6417086 | 4295993 | 1669587 | 2930443 | 11067813 | 1910259 | 3551044 | 2764502 |         |         |         | 34606727  | 
| 1400090757  | CII Program     | Low Income Economic Development Program  | Monthly KWh Target | 20000   | 40000   | 60000   | 60000   | 80000   | 80000    | 80000   | 100000  | 100000  | 120000  | 120000  | 140000  | 1000000   | 
| 1400090757  | CII Program     | Low Income Economic Development Program  | Monthly KWh Actual | 150000  | 150000  | 150000  | 150000  | 150000  | 150000   | 150000  | 150000  |         |         |         |         | 1200000   | 
| 1400090757  | CII Program     | Refrigeration                            | Monthly KWh Target | 80000   | 160000  | 240000  | 240000  | 320000  | 320000   | 320000  | 400000  | 400000  | 480000  | 480000  | 560000  | 4000000   | 
| 1400090757  | CII Program     | Refrigeration                            | Monthly KWh Actual |         |         | 573796  |         |         | 612      |         | 179286  | 0       |         |         |         | 753694    | 
```