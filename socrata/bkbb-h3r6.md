# "Solar Stars" Cities with 50 or More Watts of Solar PV per Person, End of 2015 (Source: Shining Cities 2016)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/first-in-nation-per-capita-top-ten-u-s-states-ranked-by-grid-connected-pv-cumulative-insta-09fa1) |
| Metadata | [Link](https://data.hawaii.gov/api/views/bkbb-h3r6) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/bkbb-h3r6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/bkbb-h3r6/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | bkbb-h3r6 |
| Name | "Solar Stars" Cities with 50 or More Watts of Solar PV per Person, End of 2015 (Source: Shining Cities 2016) |
| Created | 2012-11-19T19:53:47Z |
| Publication Date | 2016-11-28T23:21:12Z |

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================== | ========= | =========== |
| Yes      | series tag     | state                                   | City                                     | text      | text        |
| Yes      | series tag     | state_2                                 | State                                    | text      | text        |
| Yes      | numeric metric | per_capita_solar_pv_installed_watts_dc_ | Per Capita Rank                          | number    | number      |
| Yes      | numeric metric | per_capita_solar_pv_installed_watts_dc  | Per Capita Solar PV Installed (Watts-DC) | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bkbb-h3r6 d:2015-01-01T00:00:00.000Z t:state=Honolulu t:state_2=HI m:per_capita_solar_pv_installed_watts_dc_=1 m:per_capita_solar_pv_installed_watts_dc=417

series e:bkbb-h3r6 d:2015-01-01T00:00:00.000Z t:state=Indianapolis t:state_2=IN m:per_capita_solar_pv_installed_watts_dc_=2 m:per_capita_solar_pv_installed_watts_dc=146

series e:bkbb-h3r6 d:2015-01-01T00:00:00.000Z t:state="San Jose" t:state_2=CA m:per_capita_solar_pv_installed_watts_dc_=3 m:per_capita_solar_pv_installed_watts_dc=139
```

## Meta Commands

```ls
metric m:per_capita_solar_pv_installed_watts_dc_ p:integer l:"Per Capita Rank" t:dataTypeName=number

metric m:per_capita_solar_pv_installed_watts_dc p:integer l:"Per Capita Solar PV Installed (Watts-DC)" t:dataTypeName=number

entity e:bkbb-h3r6 l:"""Solar Stars"" Cities with 50 or More Watts of Solar PV per Person, End of 2015 (Source: Shining Cities 2016)" t:url=https://data.hawaii.gov/api/views/bkbb-h3r6

property e:bkbb-h3r6 t:meta.view v:id=bkbb-h3r6 v:averageRating=0 v:name="""Solar Stars"" Cities with 50 or More Watts of Solar PV per Person, End of 2015 (Source: Shining Cities 2016)"

property e:bkbb-h3r6 t:meta.view.owner v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:displayName="Jerome Koehler"

property e:bkbb-h3r6 t:meta.view.tableauthor v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:roleName=publisher v:displayName="Jerome Koehler"
```

## Top Records

```ls
| state        | state_2 | per_capita_solar_pv_installed_watts_dc_ | per_capita_solar_pv_installed_watts_dc | 
| ============ | ======= | ======================================= | ====================================== | 
| Honolulu     | HI      | 1                                       | 417                                    | 
| Indianapolis | IN      | 2                                       | 146                                    | 
| San Jose     | CA      | 3                                       | 139                                    | 
| San Diego    | CA      | 4                                       | 136                                    | 
| Albuquerque  | NM      | 5                                       | 114                                    | 
```