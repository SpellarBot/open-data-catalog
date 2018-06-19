# Hispanic Population By Selected Subgroups By Borough

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hispanic-population-by-selected-subgroups-by-borough-12194) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/w9du-8cu6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/w9du-8cu6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/w9du-8cu6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | w9du-8cu6 |
| Name | Hispanic Population By Selected Subgroups By Borough |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | dcp, city, planning, population, growth, race, hispanic, borough |
| Created | 2013-02-20T22:12:49Z |
| Publication Date | 2013-06-26T17:16:29Z |

## Description

Population details of selected Hispanic groups in New York City Boroughs

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                              | Data Type | Render Type |
| ======== | ============== | =============================== | ================================= | ========= | =========== |
| Yes      | series tag     | borough                         | Borough                           | text      | text        |
| Yes      | time           | census_year                     | Census Year                       | number    | text        |
| Yes      | numeric metric | mexican                         | Mexican                           | number    | number      |
| Yes      | numeric metric | puerto_rican                    | Puerto Rican                      | number    | number      |
| Yes      | numeric metric | cuban                           | Cuban                             | number    | number      |
| Yes      | numeric metric | dominican_republic              | Dominican Republic                | number    | number      |
| Yes      | numeric metric | central_american_costarican     | Central American - CostaRican     | number    | number      |
| Yes      | numeric metric | central_american_honduran       | Central American - Honduran       | number    | number      |
| Yes      | numeric metric | central_american_guatemalan     | Central American - Guatemalan     | number    | number      |
| Yes      | numeric metric | central_american_nicaraguan     | Central American - Nicaraguan     | number    | number      |
| Yes      | numeric metric | central_american_panamanian     | Central American - Panamanian     | number    | number      |
| Yes      | numeric metric | central_american_salvadoran     | Central American - Salvadoran     | number    | number      |
| Yes      | numeric metric | other_central_american          | Other Central American            | number    | number      |
| Yes      | numeric metric | south_american_argentinean      | South American - Argentinean      | number    | number      |
| Yes      | numeric metric | south_american_bolivian         | South American - Bolivian         | number    | number      |
| Yes      | numeric metric | south_american_chilean          | South American - Chilean          | number    | number      |
| Yes      | numeric metric | south_american_colombian        | South American - Colombian        | number    | number      |
| Yes      | numeric metric | south_american_ecuadorian       | South American - Ecuadorian       | number    | number      |
| Yes      | numeric metric | south_american_paraguayan       | South American - Paraguayan       | number    | number      |
| Yes      | numeric metric | south_american_peruvian         | South American - Peruvian         | number    | number      |
| Yes      | numeric metric | south_american_uruguayan        | South American - Uruguayan        | number    | number      |
| Yes      | numeric metric | south_american_venezuelan       | South American - Venezuelan       | number    | number      |
| Yes      | numeric metric | other_south_american            | Other South American              | number    | number      |
| Yes      | numeric metric | other_hispanic_other_spaniard   | Other Hispanic - Other Spaniard   | number    | number      |
| Yes      | numeric metric | other_hispanic_spanish          | Other Hispanic - Spanish          | number    | number      |
| Yes      | numeric metric | other_hispanic_spanish_american | Other Hispanic - Spanish American | number    | number      |
| Yes      | numeric metric | all_other_hispanic_or_latino    | All Other Hispanic or Latino      | number    | number      |
```

## Time Field

```ls
Value = census_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:w9du-8cu6 d:2010-01-01T00:00:00.000Z t:borough=Bronx m:central_american_guatemalan=4645 m:south_american_peruvian=3596 m:south_american_bolivian=227 m:cuban=8785 m:puerto_rican=298921 m:south_american_argentinean=1117 m:mexican=71194 m:other_south_american=369 m:central_american_honduran=17990 m:central_american_panamanian=2372 m:dominican_republic=240987 m:south_american_colombian=4635 m:south_american_uruguayan=148 m:south_american_venezuelan=1296 m:south_american_chilean=646 m:other_hispanic_other_spaniard=2097 m:south_american_ecuadorian=23206 m:other_central_american=579 m:central_american_nicaraguan=2342 m:central_american_costarican=1095 m:other_hispanic_spanish=1635 m:other_hispanic_spanish_american=221 m:south_american_paraguayan=223 m:all_other_hispanic_or_latino=47618 m:central_american_salvadoran=5469

series e:w9du-8cu6 d:2010-01-01T00:00:00.000Z t:borough=Brooklyn m:central_american_guatemalan=9160 m:south_american_peruvian=4222 m:south_american_bolivian=310 m:cuban=7581 m:puerto_rican=176528 m:south_american_argentinean=2760 m:mexican=94585 m:other_south_american=506 m:central_american_honduran=10071 m:central_american_panamanian=13681 m:dominican_republic=86764 m:south_american_colombian=8861 m:south_american_uruguayan=488 m:south_american_venezuelan=1916 m:south_american_chilean=1026 m:other_hispanic_other_spaniard=3249 m:south_american_ecuadorian=28684 m:other_central_american=487 m:central_american_nicaraguan=2407 m:central_american_costarican=2576 m:other_hispanic_spanish=2933 m:other_hispanic_spanish_american=280 m:south_american_paraguayan=230 m:all_other_hispanic_or_latino=29243 m:central_american_salvadoran=7737

series e:w9du-8cu6 d:2010-01-01T00:00:00.000Z t:borough=Manhattan m:central_american_guatemalan=2051 m:south_american_peruvian=3852 m:south_american_bolivian=522 m:cuban=11623 m:puerto_rican=107774 m:south_american_argentinean=4339 m:mexican=41965 m:other_south_american=278 m:central_american_honduran=4058 m:central_american_panamanian=1716 m:dominican_republic=155971 m:south_american_colombian=8411 m:south_american_uruguayan=549 m:south_american_venezuelan=2573 m:south_american_chilean=1824 m:other_hispanic_other_spaniard=5629 m:south_american_ecuadorian=14132 m:other_central_american=161 m:central_american_nicaraguan=1556 m:central_american_costarican=987 m:other_hispanic_spanish=2321 m:other_hispanic_spanish_american=133 m:south_american_paraguayan=268 m:all_other_hispanic_or_latino=27465 m:central_american_salvadoran=3419
```

## Meta Commands

```ls
metric m:mexican p:integer l:Mexican t:dataTypeName=number

metric m:puerto_rican p:integer l:"Puerto Rican" t:dataTypeName=number

metric m:cuban p:integer l:Cuban t:dataTypeName=number

metric m:dominican_republic p:integer l:"Dominican Republic" t:dataTypeName=number

metric m:central_american_costarican p:integer l:"Central American - CostaRican" t:dataTypeName=number

metric m:central_american_honduran p:integer l:"Central American - Honduran" t:dataTypeName=number

metric m:central_american_guatemalan p:integer l:"Central American - Guatemalan" t:dataTypeName=number

metric m:central_american_nicaraguan p:integer l:"Central American - Nicaraguan" t:dataTypeName=number

metric m:central_american_panamanian p:integer l:"Central American - Panamanian" t:dataTypeName=number

metric m:central_american_salvadoran p:integer l:"Central American - Salvadoran" t:dataTypeName=number

metric m:other_central_american p:integer l:"Other Central American" t:dataTypeName=number

metric m:south_american_argentinean p:integer l:"South American - Argentinean" t:dataTypeName=number

metric m:south_american_bolivian p:integer l:"South American - Bolivian" t:dataTypeName=number

metric m:south_american_chilean p:integer l:"South American - Chilean" t:dataTypeName=number

metric m:south_american_colombian p:integer l:"South American - Colombian" t:dataTypeName=number

metric m:south_american_ecuadorian p:integer l:"South American - Ecuadorian" t:dataTypeName=number

metric m:south_american_paraguayan p:integer l:"South American - Paraguayan" t:dataTypeName=number

metric m:south_american_peruvian p:integer l:"South American - Peruvian" t:dataTypeName=number

metric m:south_american_uruguayan p:integer l:"South American - Uruguayan" t:dataTypeName=number

metric m:south_american_venezuelan p:integer l:"South American - Venezuelan" t:dataTypeName=number

metric m:other_south_american p:integer l:"Other South American" t:dataTypeName=number

metric m:other_hispanic_other_spaniard p:integer l:"Other Hispanic - Other Spaniard" t:dataTypeName=number

metric m:other_hispanic_spanish p:integer l:"Other Hispanic - Spanish" t:dataTypeName=number

metric m:other_hispanic_spanish_american p:integer l:"Other Hispanic - Spanish American" t:dataTypeName=number

metric m:all_other_hispanic_or_latino p:integer l:"All Other Hispanic or Latino" t:dataTypeName=number

entity e:w9du-8cu6 l:"Hispanic Population By Selected Subgroups By Borough" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/w9du-8cu6

property e:w9du-8cu6 t:meta.view v:id=w9du-8cu6 v:category="City Government" v:averageRating=0 v:name="Hispanic Population By Selected Subgroups By Borough" v:attribution="Department of City Planning (DCP)"

property e:w9du-8cu6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:w9du-8cu6 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| borough       | census_year | mexican | puerto_rican | cuban | dominican_republic | central_american_costarican | central_american_honduran | central_american_guatemalan | central_american_nicaraguan | central_american_panamanian | central_american_salvadoran | other_central_american | south_american_argentinean | south_american_bolivian | south_american_chilean | south_american_colombian | south_american_ecuadorian | south_american_paraguayan | south_american_peruvian | south_american_uruguayan | south_american_venezuelan | other_south_american | other_hispanic_other_spaniard | other_hispanic_spanish | other_hispanic_spanish_american | all_other_hispanic_or_latino | 
| ============= | =========== | ======= | ============ | ===== | ================== | =========================== | ========================= | =========================== | =========================== | =========================== | =========================== | ====================== | ========================== | ======================= | ====================== | ======================== | ========================= | ========================= | ======================= | ======================== | ========================= | ==================== | ============================= | ====================== | =============================== | ============================ | 
| Bronx         | 2010        | 71194   | 298921       | 8785  | 240987             | 1095                        | 17990                     | 4645                        | 2342                        | 2372                        | 5469                        | 579                    | 1117                       | 227                     | 646                    | 4635                     | 23206                     | 223                       | 3596                    | 148                      | 1296                      | 369                  | 2097                          | 1635                   | 221                             | 47618                        | 
| Brooklyn      | 2010        | 94585   | 176528       | 7581  | 86764              | 2576                        | 10071                     | 9160                        | 2407                        | 13681                       | 7737                        | 487                    | 2760                       | 310                     | 1026                   | 8861                     | 28684                     | 230                       | 4222                    | 488                      | 1916                      | 506                  | 3249                          | 2933                   | 280                             | 29243                        | 
| Manhattan     | 2010        | 41965   | 107774       | 11623 | 155971             | 987                         | 4058                      | 2051                        | 1556                        | 1716                        | 3419                        | 161                    | 4339                       | 522                     | 1824                   | 8411                     | 14132                     | 268                       | 3852                    | 549                      | 2573                      | 278                  | 5629                          | 2321                   | 133                             | 27465                        | 
| Queens        | 2010        | 92835   | 102881       | 11020 | 88061              | 1749                        | 8546                      | 13700                       | 2842                        | 3977                        | 21342                       | 353                    | 6345                       | 3268                    | 3184                   | 70290                    | 98512                     | 2775                      | 22886                   | 1743                     | 3580                      | 1439                 | 5485                          | 4265                   | 453                             | 42219                        | 
| Staten Island | 2010        | 18684   | 37517        | 1831  | 4918               | 266                         | 1735                      | 864                         | 199                         | 607                         | 592                         | 47                     | 608                        | 161                     | 346                    | 2526                     | 2675                      | 38                        | 1462                    | 76                       | 254                       | 86                   | 1333                          | 781                    | 23                              | 3422                         | 
```