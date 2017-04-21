# Anne Arundel County Crime Totals By Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/anne-arundel-county-crime-totals-by-type-86093) |
| Metadata | [Link](https://data.maryland.gov/api/views/ha7d-yqrm) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ha7d-yqrm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ha7d-yqrm/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ha7d-yqrm |
| Name | Anne Arundel County Crime Totals By Type |
| Attribution | MSAC |
| Category | Public Safety |
| Tags | anne arundel, crime, public safety, violent crime, property crime |
| Created | 2014-07-25T16:24:00Z |
| Publication Date | 2014-07-25T16:28:59Z |

## Description

Historical crime totals by type, 1975 - present.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | time           | year                          | YEAR                          | number    | number      |
| Yes      | numeric metric | murder                        | MURDER                        | number    | number      |
| Yes      | numeric metric | rape                          | RAPE                          | number    | number      |
| Yes      | numeric metric | robbery                       | ROBBERY                       | number    | number      |
| Yes      | numeric metric | agg_assault                   | AGG. ASSAULT                  | number    | number      |
| Yes      | numeric metric | b_e                           | B & E                         | number    | number      |
| Yes      | numeric metric | larceny_theft                 | LARCENY THEFT                 | number    | number      |
| Yes      | numeric metric | m_v_theft                     | M/V THEFT                     | number    | number      |
| Yes      | numeric metric | grand_total                   | GRAND TOTAL                   | number    | number      |
| Yes      | numeric metric | percent_change                | PERCENT CHANGE                | percent   | percent     |
| Yes      | numeric metric | violent_crime_total           | VIOLENT CRIME TOTAL           | number    | number      |
| Yes      | numeric metric | violent_crime_percent         | VIOLENT CRIME PERCENT         | percent   | percent     |
| Yes      | numeric metric | violent_crime_percent_change  | VIOLENT CRIME PERCENT CHANGE  | percent   | percent     |
| Yes      | numeric metric | property_crime_totals         | PROPERTY CRIME TOTALS         | number    | number      |
| Yes      | numeric metric | property_crime_percent        | PROPERTY CRIME PERCENT        | percent   | percent     |
| Yes      | numeric metric | property_crime_percent_change | PROPERTY CRIME PERCENT CHANGE | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ha7d-yqrm d:1975-01-01T00:00:00.000Z m:murder=16 m:larceny_theft=12736 m:robbery=413 m:agg_assault=1514 m:b_e=5662 m:m_v_theft=1986 m:violent_crime_percent=9 m:property_crime_totals=20384 m:property_crime_percent=91 m:grand_total=22401 m:violent_crime_total=2017 m:rape=74

series e:ha7d-yqrm d:1976-01-01T00:00:00.000Z m:property_crime_percent_change=-13.1 m:murder=10 m:larceny_theft=11535 m:violent_crime_percent_change=-48.6 m:property_crime_percent=94.5 m:violent_crime_total=1036 m:robbery=330 m:agg_assault=619 m:b_e=4653 m:m_v_theft=1520 m:percent_change=-16.3 m:violent_crime_percent=5.5 m:property_crime_totals=17708 m:grand_total=18744 m:rape=77

series e:ha7d-yqrm d:1977-01-01T00:00:00.000Z m:property_crime_percent_change=-2.2 m:murder=16 m:larceny_theft=10783 m:violent_crime_percent_change=14.5 m:property_crime_percent=93.6 m:violent_crime_total=1186 m:robbery=396 m:agg_assault=656 m:b_e=5091 m:m_v_theft=1436 m:percent_change=-1.3 m:violent_crime_percent=6.4 m:property_crime_totals=17310 m:grand_total=18496 m:rape=118
```

## Meta Commands

```ls
metric m:murder p:integer l:MURDER t:dataTypeName=number

metric m:rape p:integer l:RAPE t:dataTypeName=number

metric m:robbery p:integer l:ROBBERY t:dataTypeName=number

metric m:agg_assault p:integer l:"AGG. ASSAULT" t:dataTypeName=number

metric m:b_e p:integer l:"B & E" t:dataTypeName=number

metric m:larceny_theft p:integer l:"LARCENY THEFT" t:dataTypeName=number

metric m:m_v_theft p:integer l:"M/V THEFT" t:dataTypeName=number

metric m:grand_total p:integer l:"GRAND TOTAL" t:dataTypeName=number

metric m:percent_change p:float l:"PERCENT CHANGE" t:dataTypeName=percent

metric m:violent_crime_total p:integer l:"VIOLENT CRIME TOTAL" t:dataTypeName=number

metric m:violent_crime_percent p:float l:"VIOLENT CRIME PERCENT" t:dataTypeName=percent

metric m:violent_crime_percent_change p:float l:"VIOLENT CRIME PERCENT CHANGE" t:dataTypeName=percent

metric m:property_crime_totals p:integer l:"PROPERTY CRIME TOTALS" t:dataTypeName=number

metric m:property_crime_percent p:float l:"PROPERTY CRIME PERCENT" t:dataTypeName=percent

metric m:property_crime_percent_change p:float l:"PROPERTY CRIME PERCENT CHANGE" t:dataTypeName=percent

entity e:ha7d-yqrm l:"Anne Arundel County Crime Totals By Type" t:attribution=MSAC t:url=https://data.maryland.gov/api/views/ha7d-yqrm

property e:ha7d-yqrm t:meta.view v:id=ha7d-yqrm v:category="Public Safety" v:attributionLink="http://www.goccp.maryland.gov/msac/crime-statistics-county.php?id=18" v:averageRating=0 v:name="Anne Arundel County Crime Totals By Type" v:attribution=MSAC

property e:ha7d-yqrm t:meta.view.license v:name="Public Domain"

property e:ha7d-yqrm t:meta.view.owner v:id=wdx2-yd94 v:screenName="Scott Shaffer" v:displayName="Scott Shaffer"

property e:ha7d-yqrm t:meta.view.tableauthor v:id=wdx2-yd94 v:screenName="Scott Shaffer" v:roleName=editor v:displayName="Scott Shaffer"
```

## Top Records

```ls
| year | murder | rape | robbery | agg_assault | b_e  | larceny_theft | m_v_theft | grand_total | percent_change | violent_crime_total | violent_crime_percent | violent_crime_percent_change | property_crime_totals | property_crime_percent | property_crime_percent_change | 
| ==== | ====== | ==== | ======= | =========== | ==== | ============= | ========= | =========== | ============== | =================== | ===================== | ============================ | ===================== | ====================== | ============================= | 
| 1975 | 16     | 74   | 413     | 1514        | 5662 | 12736         | 1986      | 22401       |                | 2017                | 9.0                   |                              | 20384                 | 91.0                   |                               | 
| 1976 | 10     | 77   | 330     | 619         | 4653 | 11535         | 1520      | 18744       | -16.3          | 1036                | 5.5                   | -48.6                        | 17708                 | 94.5                   | -13.1                         | 
| 1977 | 16     | 118  | 396     | 656         | 5091 | 10783         | 1436      | 18496       | -1.3           | 1186                | 6.4                   | 14.5                         | 17310                 | 93.6                   | -2.2                          | 
| 1978 | 17     | 68   | 349     | 710         | 4694 | 10120         | 1161      | 17119       | -7.4           | 1144                | 6.7                   | -3.5                         | 15975                 | 93.3                   | -7.7                          | 
| 1979 | 13     | 84   | 301     | 728         | 4430 | 10633         | 1264      | 17453       | 2.0            | 1126                | 6.5                   | -1.6                         | 16327                 | 93.5                   | 2.2                           | 
| 1980 | 20     | 117  | 352     | 815         | 5444 | 12215         | 1353      | 20316       | 16.4           | 1304                | 6.4                   | 15.8                         | 19012                 | 93.6                   | 16.4                          | 
| 1981 | 23     | 85   | 488     | 820         | 5105 | 12638         | 1276      | 20435       | 0.6            | 1416                | 6.9                   | 8.6                          | 19019                 | 93.1                   | 0.0                           | 
| 1982 | 19     | 83   | 420     | 844         | 4614 | 11667         | 1128      | 18775       | -8.1           | 1366                | 7.3                   | -3.5                         | 17409                 | 92.7                   | -8.5                          | 
| 1983 | 13     | 71   | 465     | 935         | 4392 | 10067         | 951       | 16894       | -10.0          | 1484                | 8.8                   | 8.6                          | 15410                 | 91.2                   | -11.5                         | 
| 1984 | 16     | 97   | 416     | 1085        | 4269 | 10131         | 941       | 16955       | 0.4            | 1614                | 9.5                   | 8.8                          | 15341                 | 90.5                   | -0.4                          | 
```