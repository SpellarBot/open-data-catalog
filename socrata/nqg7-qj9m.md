# IDOT DPIT - State of Illinois Supported Amtrak Ridership

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idot-dpit-state-of-illinois-supported-amtrak-ridership-ffa33) |
| Metadata | [Link](https://data.illinois.gov/api/views/nqg7-qj9m) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/nqg7-qj9m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/nqg7-qj9m/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | nqg7-qj9m |
| Name | IDOT DPIT - State of Illinois Supported Amtrak Ridership |
| Attribution | Illinois Department of Transportation DPIT |
| Category | Transportation |
| Tags | amtrak, train, ridership, passenger rail |
| Created | 2012-01-20T17:18:48Z |
| Publication Date | 2012-01-20T20:30:11Z |

## Description

FY 06 through FY 11 Overall Annual Ridership per Corridor *Excludes Amtrak national corridor train ridership in IL not subsidized with state funds.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | service_corridor | Service Corridor | text      | text        |
| Yes      | numeric metric | sfy06            | SFY06            | number    | text        |
| Yes      | numeric metric | sfy07            | SFY07            | number    | text        |
| Yes      | numeric metric | sfy_08           | SFY 08           | number    | text        |
| Yes      | numeric metric | sfy_09           | SFY 09           | number    | text        |
| Yes      | numeric metric | sfy_10           | SFY 10           | number    | text        |
| Yes      | numeric metric | sfy_11           | SFY 11           | number    | text        |
| Yes      | series tag     | fy11_vs_fy10     | FY11 vs. FY10    | text      | text        |
| Yes      | series tag     | fy_11_vs_fy06    | FY 11 vs FY06    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nqg7-qj9m d:2012-01-20T09:18:50.000Z t:fy_11_vs_fy06=45.2% t:fy11_vs_fy10=5.7% t:service_corridor="Hiawatha (CHI-MIL)" m:sfy_08=691897 m:sfy_09=753199 m:sfy_11=815396 m:sfy_10=771200 m:sfy07=585710 m:sfy06=561747

series e:nqg7-qj9m d:2012-01-20T09:18:50.000Z t:fy_11_vs_fy06=210.1% t:fy11_vs_fy10=4.5% t:service_corridor="Lincoln (CHI-STL)" m:sfy_08=325550 m:sfy_09=360111 m:sfy_11=412593 m:sfy_10=394993 m:sfy07=230179 m:sfy06=133036

series e:nqg7-qj9m d:2012-01-20T09:18:50.000Z t:fy_11_vs_fy06=122.6% t:fy11_vs_fy10=15.6% t:service_corridor="Illini/Saluki (CHI-CDL)" m:sfy_08=263246 m:sfy_09=266090 m:sfy_11=299462 m:sfy_10=259021 m:sfy07=202109 m:sfy06=134531
```

## Meta Commands

```ls
metric m:sfy06 p:long l:SFY06 t:dataTypeName=number

metric m:sfy07 p:long l:SFY07 t:dataTypeName=number

metric m:sfy_08 p:long l:"SFY 08" t:dataTypeName=number

metric m:sfy_09 p:long l:"SFY 09" t:dataTypeName=number

metric m:sfy_10 p:long l:"SFY 10" t:dataTypeName=number

metric m:sfy_11 p:long l:"SFY 11" t:dataTypeName=number

entity e:nqg7-qj9m l:"IDOT DPIT - State of Illinois Supported Amtrak Ridership" t:attribution="Illinois Department of Transportation DPIT" t:url=https://data.illinois.gov/api/views/nqg7-qj9m

property e:nqg7-qj9m t:meta.view v:id=nqg7-qj9m v:category=Transportation v:averageRating=0 v:name="IDOT DPIT - State of Illinois Supported Amtrak Ridership" v:attribution="Illinois Department of Transportation DPIT"

property e:nqg7-qj9m t:meta.view.license v:name="Public Domain"

property e:nqg7-qj9m t:meta.view.owner v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin

property e:nqg7-qj9m t:meta.view.tableauthor v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin
```

## Top Records

```ls
| :updated_at | service_corridor          | sfy06   | sfy07   | sfy_08  | sfy_09  | sfy_10  | sfy_11  | fy11_vs_fy10 | fy_11_vs_fy06 | 
| =========== | ========================= | ======= | ======= | ======= | ======= | ======= | ======= | ============ | ============= | 
| 1327051130  | Hiawatha (CHI-MIL)        | 561,747 | 585,710 | 691,897 | 753,199 | 771,200 | 815,396 | 5.7%         | 45.2%         | 
| 1327051130  | Lincoln (CHI-STL)         | 133,036 | 230,179 | 325,550 | 360,111 | 394,993 | 412,593 | 4.5%         | 210.1%        | 
| 1327051130  | Illini/Saluki (CHI-CDL)   | 134,531 | 202,109 | 263,246 | 266,090 | 259,021 | 299,462 | 15.6%        | 122.6%        | 
| 1327051130  | Zephyr/Sandburg (CHI-QCY) | 118,502 | 155,136 | 194,024 | 205,824 | 205,906 | 222,419 | 8.0%         | 87.7%         | 
```