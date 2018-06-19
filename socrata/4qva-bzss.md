# Compulsive Gambler's Fund

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/compulsive-gamblers-fund) |
| Metadata | [Link](https://data.ct.gov/api/views/4qva-bzss) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/4qva-bzss/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/4qva-bzss/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 4qva-bzss |
| Name | Compulsive Gambler's Fund |
| Attribution | CT Dept. of Consumer Protection |
| Category | Government |
| Tags | compulsive gambler |
| Created | 2014-09-17T12:10:10Z |
| Publication Date | 2014-09-17T12:12:00Z |

## Description

Public Act 86-312 established a permanent program for the treatment and rehabilitation of compulsive gamblers in the State

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year                      | Fiscal Year                      | text      | text        |
| Yes      | numeric metric | plainfield_greyhound_park_perf   | Plainfield Greyhound Park Perf   | money     | money       |
| Yes      | numeric metric | plainfield_greyhound_park_amount | Plainfield Greyhound Park Amount | money     | money       |
| Yes      | numeric metric | bridgeport_shoreline_star_perf   | Bridgeport Shoreline Star Perf   | money     | money       |
| Yes      | numeric metric | bridgeport_shoreline_star_amount | Bridgeport Shoreline Star Amount | money     | money       |
| Yes      | numeric metric | hartford_jai_alai_perf           | Hartford Jai Alai Perf           | money     | money       |
| Yes      | numeric metric | hartford_jai_alai_amount         | Hartford Jai Alai Amount         | money     | money       |
| Yes      | numeric metric | bridgeport_jai_alai_perf         | Bridgeport Jai Alai Perf         | money     | money       |
| Yes      | numeric metric | bridgeport_jai_alaiamount        | Bridgeport Jai AlaiAmount        | money     | money       |
| Yes      | numeric metric | milford_jai_alai_perf            | Milford Jai Alai Perf            | money     | money       |
| Yes      | numeric metric | milford_jai_alai_amount          | Milford Jai Alai Amount          | money     | money       |
| Yes      | numeric metric | off_track_betting_perf           | Off-Track Betting Perf           | money     | money       |
| Yes      | numeric metric | off_track_betting_amount         | Off-Track Betting Amount         | money     | money       |
| Yes      | numeric metric | total_perf                       | Total Perf                       | money     | money       |
| Yes      | numeric metric | total_amount                     | Total Amount                     | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4qva-bzss d:2014-09-17T05:10:13.000Z t:fiscal_year=1983 m:total_amount=160575 m:bridgeport_jai_alai_perf=221 m:hartford_jai_alai_perf=271 m:total_perf=1662 m:hartford_jai_alai_amount=36585 m:off_track_betting_amount=14325 m:milford_jai_alai_perf=263 m:off_track_betting_perf=573 m:bridgeport_jai_alaiamount=29835 m:plainfield_greyhound_park_amount=44325 m:milford_jai_alai_amount=35505 m:plainfield_greyhound_park_perf=334

series e:4qva-bzss d:2014-09-17T05:10:13.000Z t:fiscal_year=1984 m:total_amount=149660 m:bridgeport_jai_alai_perf=236 m:hartford_jai_alai_perf=201 m:total_perf=1611 m:hartford_jai_alai_amount=27135 m:off_track_betting_amount=15425 m:milford_jai_alai_perf=223 m:off_track_betting_perf=617 m:bridgeport_jai_alaiamount=31860 m:plainfield_greyhound_park_amount=45135 m:milford_jai_alai_amount=30105 m:plainfield_greyhound_park_perf=334

series e:4qva-bzss d:2014-09-17T05:10:13.000Z t:fiscal_year=1985 m:total_amount=152545 m:bridgeport_jai_alai_perf=216 m:hartford_jai_alai_perf=229 m:total_perf=1635 m:hartford_jai_alai_amount=30915 m:off_track_betting_amount=15475 m:milford_jai_alai_perf=237 m:off_track_betting_perf=619 m:bridgeport_jai_alaiamount=29160 m:plainfield_greyhound_park_amount=45000 m:milford_jai_alai_amount=31995 m:plainfield_greyhound_park_perf=334
```

## Meta Commands

```ls
metric m:plainfield_greyhound_park_perf p:integer l:"Plainfield Greyhound Park Perf" t:dataTypeName=money

metric m:plainfield_greyhound_park_amount p:integer l:"Plainfield Greyhound Park Amount" t:dataTypeName=money

metric m:bridgeport_shoreline_star_perf p:integer l:"Bridgeport Shoreline Star Perf" t:dataTypeName=money

metric m:bridgeport_shoreline_star_amount p:integer l:"Bridgeport Shoreline Star Amount" t:dataTypeName=money

metric m:hartford_jai_alai_perf p:integer l:"Hartford Jai Alai Perf" t:dataTypeName=money

metric m:hartford_jai_alai_amount p:integer l:"Hartford Jai Alai Amount" t:dataTypeName=money

metric m:bridgeport_jai_alai_perf p:integer l:"Bridgeport Jai Alai Perf" t:dataTypeName=money

metric m:bridgeport_jai_alaiamount p:integer l:"Bridgeport Jai AlaiAmount" t:dataTypeName=money

metric m:milford_jai_alai_perf p:integer l:"Milford Jai Alai Perf" t:dataTypeName=money

metric m:milford_jai_alai_amount p:integer l:"Milford Jai Alai Amount" t:dataTypeName=money

metric m:off_track_betting_perf p:integer l:"Off-Track Betting Perf" t:dataTypeName=money

metric m:off_track_betting_amount p:integer l:"Off-Track Betting Amount" t:dataTypeName=money

metric m:total_perf p:integer l:"Total Perf" t:dataTypeName=money

metric m:total_amount p:integer l:"Total Amount" t:dataTypeName=money

entity e:4qva-bzss l:"Compulsive Gambler's Fund" t:attribution="CT Dept. of Consumer Protection" t:url=https://data.ct.gov/api/views/4qva-bzss

property e:4qva-bzss t:meta.view v:id=4qva-bzss v:category=Government v:attributionLink="http://www.ct.gov/dcp/cwp/view.asp?a=4107&q=493804" v:averageRating=0 v:name="Compulsive Gambler's Fund" v:attribution="CT Dept. of Consumer Protection"

property e:4qva-bzss t:meta.view.license v:name="Public Domain"

property e:4qva-bzss t:meta.view.owner v:id=ewkk-db5a v:screenName=WilliamR v:displayName=WilliamR

property e:4qva-bzss t:meta.view.tableauthor v:id=ewkk-db5a v:screenName=WilliamR v:roleName=editor v:displayName=WilliamR
```

## Top Records

```ls
| :updated_at | fiscal_year | plainfield_greyhound_park_perf | plainfield_greyhound_park_amount | bridgeport_shoreline_star_perf | bridgeport_shoreline_star_amount | hartford_jai_alai_perf | hartford_jai_alai_amount | bridgeport_jai_alai_perf | bridgeport_jai_alaiamount | milford_jai_alai_perf | milford_jai_alai_amount | off_track_betting_perf | off_track_betting_amount | total_perf | total_amount | 
| =========== | =========== | ============================== | ================================ | ============================== | ================================ | ====================== | ======================== | ======================== | ========================= | ===================== | ======================= | ====================== | ======================== | ========== | ============ | 
| 1410930613  | 1983        | 334                            | 44325                            |                                |                                  | 271                    | 36585                    | 221                      | 29835                     | 263                   | 35505                   | 573                    | 14325                    | 1662       | 160575       | 
| 1410930613  | 1984        | 334                            | 45135                            |                                |                                  | 201                    | 27135                    | 236                      | 31860                     | 223                   | 30105                   | 617                    | 15425                    | 1611       | 149660       | 
| 1410930613  | 1985        | 334                            | 45000                            |                                |                                  | 229                    | 30915                    | 216                      | 29160                     | 237                   | 31995                   | 619                    | 15475                    | 1635       | 152545       | 
| 1410930613  | 1986        | 336                            | 45405                            |                                |                                  | 224                    | 30240                    | 260                      | 35100                     | 214                   | 28890                   | 627                    | 15675                    | 1661       | 155310       | 
| 1410930613  | 1987        | 287                            | 38790                            |                                |                                  | 247                    | 33345                    | 251                      | 33885                     | 218                   | 29430                   | 622                    | 15550                    | 1625       | 151000       | 
| 1410930613  | 1988        | 379                            | 51165                            |                                |                                  | 234                    | 31590                    | 137                      | 18495                     | 274                   | 36990                   | 618                    | 15450                    | 1642       | 153690       | 
| 1410930613  | 1989        | 330                            | 44595                            |                                |                                  | 260                    | 35100                    | 255                      | 34425                     | 229                   | 30915                   | 621                    | 15575                    | 1695       | 160610       | 
| 1410930613  | 1990        | 334                            | 45135                            |                                |                                  | 325                    | 43875                    | 233                      | 31455                     | 231                   | 31185                   | 628                    | 15700                    | 1751       | 167350       | 
| 1410930613  | 1991        | 334                            | 45135                            |                                |                                  | 309                    | 41715                    | 243                      | 32805                     | 228                   | 30780                   | 623                    | 15575                    | 1737       | 166010       | 
| 1410930613  | 1992        | 339                            | 46080                            |                                |                                  | 346                    | 46755                    | 240                      | 32400                     | 230                   | 31050                   | 456                    | 11400                    | 1611       | 167685       | 
```