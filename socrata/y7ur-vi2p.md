# New Distributed Renewable Energy Systems Installed In Hawaii (Source: Hawaii Public Utilities Commission)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-distributed-renewable-energy-systems-installed-in-hawaii-source-hawaii-public-utilitie) |
| Metadata | [Link](https://data.hawaii.gov/api/views/y7ur-vi2p) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/y7ur-vi2p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/y7ur-vi2p/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | y7ur-vi2p |
| Name | New Distributed Renewable Energy Systems Installed In Hawaii (Source: Hawaii Public Utilities Commission) |
| Created | 2012-11-21T18:55:46Z |
| Publication Date | 2014-10-14T21:39:44Z |

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                                 | Data Type | Render Type |
| ======== | ============== | ====================================== | ==================================================== | ========= | =========== |
| Yes      | time           | year                                   | Year                                                 | number    | number      |
| Yes      | numeric metric | heco                                   | HECO/Oahu                                            | number    | number      |
| Yes      | numeric metric | helco                                  | HELCO/Hawaii Island                                  | number    | number      |
| Yes      | numeric metric | meco                                   | MECO/Maui County                                     | number    | number      |
| Yes      | numeric metric | kiuc                                   | KIUC/Kauai                                           | number    | number      |
| Yes      | numeric metric | state_total                            | State Total                                          | number    | number      |
| Yes      | numeric metric | total_capacity_of_systems_installed_kw | Total Capacity of Distributed Systems Installed (kW) | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y7ur-vi2p d:2009-01-01T00:00:00.000Z m:state_total=1168 m:total_capacity_of_systems_installed_kw=7213 m:helco=265 m:kiuc=92 m:meco=298 m:heco=513

series e:y7ur-vi2p d:2010-01-01T00:00:00.000Z m:state_total=2190 m:total_capacity_of_systems_installed_kw=11984 m:helco=371 m:kiuc=150 m:meco=342 m:heco=1327

series e:y7ur-vi2p d:2008-01-01T00:00:00.000Z m:state_total=565 m:total_capacity_of_systems_installed_kw=4663 m:helco=116 m:kiuc=94 m:meco=135 m:heco=220
```

## Meta Commands

```ls
metric m:heco p:integer l:HECO/Oahu t:dataTypeName=number

metric m:helco p:integer l:"HELCO/Hawaii Island" t:dataTypeName=number

metric m:meco p:integer l:"MECO/Maui County" t:dataTypeName=number

metric m:kiuc p:integer l:KIUC/Kauai t:dataTypeName=number

metric m:state_total p:integer l:"State Total" t:dataTypeName=number

metric m:total_capacity_of_systems_installed_kw p:integer l:"Total Capacity of Distributed Systems Installed (kW)" t:dataTypeName=number

entity e:y7ur-vi2p l:"New Distributed Renewable Energy Systems Installed In Hawaii (Source: Hawaii Public Utilities Commission)" t:url=https://data.hawaii.gov/api/views/y7ur-vi2p

property e:y7ur-vi2p t:meta.view v:id=y7ur-vi2p v:averageRating=0 v:name="New Distributed Renewable Energy Systems Installed In Hawaii (Source: Hawaii Public Utilities Commission)"

property e:y7ur-vi2p t:meta.view.owner v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:displayName="Jerome Koehler"

property e:y7ur-vi2p t:meta.view.tableauthor v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:roleName=publisher v:displayName="Jerome Koehler"
```

## Top Records

```ls
| year | heco  | helco | meco | kiuc | state_total | total_capacity_of_systems_installed_kw | 
| ==== | ===== | ===== | ==== | ==== | =========== | ====================================== | 
| 2009 | 513   | 265   | 298  | 92   | 1168        | 7213                                   | 
| 2010 | 1327  | 371   | 342  | 150  | 2190        | 11984                                  | 
| 2008 | 220   | 116   | 135  | 94   | 565         | 4663                                   | 
| 2011 | 3435  | 804   | 1048 | 232  | 5516        | 33230                                  | 
| 2012 | 8662  | 1737  | 1682 | 479  | 12560       | 79263                                  | 
| 2013 | 14033 | 1957  | 1574 | 752  | 18316       | 115081                                 | 
```