# D -- $$ By Year By Source

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/d-by-year-by-source-41134) |
| Metadata | [Link](https://data.wa.gov/api/views/sf64-aecy) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/sf64-aecy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/sf64-aecy/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | sf64-aecy |
| Name | D -- $$ By Year By Source |
| Created | 2012-10-19T19:02:39Z |
| Publication Date | 2012-10-19T19:06:33Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                    | Data Type | Render Type |
| ======== | ============== | ==================================================== | ======================================================= | ========= | =========== |
| Yes      | time           | year                                                 | Year                                                    | number    | number      |
| Yes      | numeric metric | state_general_obligation_bonds                       | State -- General Obligation Bonds                       | money     | money       |
| Yes      | numeric metric | state_puget_sound_acquisitions_and_restoration_funds | State -- Puget Sound Acquisitions and Restoration Funds | money     | money       |
| Yes      | numeric metric | state_family_forest_fish_passage_program             | State -- Family Forest Fish Passage Program             | money     | money       |
| Yes      | numeric metric | state_estuary_and_salmon_restoration_program         | State -- Estuary and Salmon Restoration Program         | money     | money       |
| Yes      | numeric metric | local_match                                          | Local -- Match                                          | money     | money       |
| Yes      | numeric metric | federal_pacific_coast_salmon_recovery_fund           | Federal -- Pacific Coast Salmon Recovery Fund           | money     | money       |
| Yes      | numeric metric | federal_pacific_states_marine_fisheries_commission   | Federal -- Pacific States Marine Fisheries Commission   | money     | money       |
| Yes      | numeric metric | federal_hatchery_reform                              | Federal -- Hatchery Reform                              | money     | money       |
| Yes      | numeric metric | federal_puget_sound_critical_stock                   | Federal -- Puget Sound Critical Stock                   | money     | money       |
| Yes      | numeric metric | federal_coded_wire_tags                              | Federal -- Coded Wire Tags                              | money     | money       |
| Yes      | numeric metric | total                                                | Total                                                   | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:sf64-aecy d:1999-01-01T00:00:00.000Z m:federal_hatchery_reform=0 m:total=31555133 m:local_match=11805133 m:federal_puget_sound_critical_stock=0 m:federal_coded_wire_tags=0 m:federal_pacific_coast_salmon_recovery_fund=19750000 m:state_estuary_and_salmon_restoration_program=0 m:federal_pacific_states_marine_fisheries_commission=0 m:state_general_obligation_bonds=0 m:state_puget_sound_acquisitions_and_restoration_funds=0 m:state_family_forest_fish_passage_program=0

series e:sf64-aecy d:2000-01-01T00:00:00.000Z m:federal_hatchery_reform=3176004 m:total=84735943 m:local_match=26669939 m:federal_puget_sound_critical_stock=0 m:federal_coded_wire_tags=0 m:federal_pacific_coast_salmon_recovery_fund=17850000 m:state_estuary_and_salmon_restoration_program=0 m:federal_pacific_states_marine_fisheries_commission=0 m:state_general_obligation_bonds=37040000 m:state_puget_sound_acquisitions_and_restoration_funds=0 m:state_family_forest_fish_passage_program=0

series e:sf64-aecy d:2001-01-01T00:00:00.000Z m:federal_hatchery_reform=4415070 m:total=53698937 m:local_match=19170867 m:federal_puget_sound_critical_stock=0 m:federal_coded_wire_tags=0 m:federal_pacific_coast_salmon_recovery_fund=30113000 m:state_estuary_and_salmon_restoration_program=0 m:federal_pacific_states_marine_fisheries_commission=0 m:state_general_obligation_bonds=0 m:state_puget_sound_acquisitions_and_restoration_funds=0 m:state_family_forest_fish_passage_program=0
```

## Meta Commands

```ls
metric m:state_general_obligation_bonds p:double l:"State -- General Obligation Bonds" t:dataTypeName=money

metric m:state_puget_sound_acquisitions_and_restoration_funds p:double l:"State -- Puget Sound Acquisitions and Restoration Funds" t:dataTypeName=money

metric m:state_family_forest_fish_passage_program p:double l:"State -- Family Forest Fish Passage Program" t:dataTypeName=money

metric m:state_estuary_and_salmon_restoration_program p:double l:"State -- Estuary and Salmon Restoration Program" t:dataTypeName=money

metric m:local_match p:integer l:"Local -- Match" t:dataTypeName=money

metric m:federal_pacific_coast_salmon_recovery_fund p:integer l:"Federal -- Pacific Coast Salmon Recovery Fund" t:dataTypeName=money

metric m:federal_pacific_states_marine_fisheries_commission p:double l:"Federal -- Pacific States Marine Fisheries Commission" t:dataTypeName=money

metric m:federal_hatchery_reform p:double l:"Federal -- Hatchery Reform" t:dataTypeName=money

metric m:federal_puget_sound_critical_stock p:double l:"Federal -- Puget Sound Critical Stock" t:dataTypeName=money

metric m:federal_coded_wire_tags p:double l:"Federal -- Coded Wire Tags" t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

entity e:sf64-aecy l:"D -- $$ By Year By Source" t:url=https://data.wa.gov/api/views/sf64-aecy

property e:sf64-aecy t:meta.view v:id=sf64-aecy v:averageRating=0 v:name="D -- $$ By Year By Source"

property e:sf64-aecy t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:sf64-aecy t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year | state_general_obligation_bonds | state_puget_sound_acquisitions_and_restoration_funds | state_family_forest_fish_passage_program | state_estuary_and_salmon_restoration_program | local_match | federal_pacific_coast_salmon_recovery_fund | federal_pacific_states_marine_fisheries_commission | federal_hatchery_reform | federal_puget_sound_critical_stock | federal_coded_wire_tags | total     | 
| ==== | ============================== | ==================================================== | ======================================== | ============================================ | =========== | ========================================== | ================================================== | ======================= | ================================== | ======================= | ========= | 
| 1999 | 0.0                            | 0.0                                                  | 0.0                                      | 0.0                                          | 11805133    | 19750000                                   | 0.0                                                | 0.0                     | 0.0                                | 0.0                     | 31555133  | 
| 2000 | 37040000                       | 0.0                                                  | 0.0                                      | 0.0                                          | 26669939    | 17850000                                   | 0.0                                                | 3176004                 | 0.0                                | 0.0                     | 84735943  | 
| 2001 | 0.0                            | 0.0                                                  | 0.0                                      | 0.0                                          | 19170867    | 30113000                                   | 0.0                                                | 4415070                 | 0.0                                | 0.0                     | 53698937  | 
| 2002 | 26351000                       | 0.0                                                  | 0.0                                      | 0.0                                          | 11325322    | 33800000                                   | 0.0                                                | 3501484                 | 0.0                                | 0.0                     | 74977806  | 
| 2003 | 0.0                            | 0.0                                                  | 0.0                                      | 0.0                                          | 661362      | 27503700                                   | 0.0                                                | 2996132                 | 0.0                                | 0.0                     | 31161194  | 
| 2004 | 12000000                       | 0.0                                                  | 2000000                                  | 0.0                                          | 13245642    | 25868000                                   | 0.0                                                | 2681967                 | 0.0                                | 0.0                     | 55795609  | 
| 2005 | 0.0                            | 0.0                                                  | 0.0                                      | 0.0                                          | 15809315    | 24518200                                   | 0.0                                                | 2234439                 | 0.0                                | 0.0                     | 42561954  | 
| 2006 | 18000000                       | 0.0                                                  | 4150000                                  | 0.0                                          | 14850013    | 23410000                                   | 0.0                                                | 221322                  | 0.0                                | 0.0                     | 60631335  | 
| 2007 | 0.0                            | 0.0                                                  | 0.0                                      | 0.0                                          | 28688005    | 23410000                                   | 340303                                             | 0.0                     | 0.0                                | 0.0                     | 52438308  | 
| 2008 | 18000000                       | 40750000                                             | 6000000                                  | 0.0                                          | 20726449    | 23500000                                   | 390960                                             | 0.0                     | 0.0                                | 0.0                     | 109367409 | 
```