# Transfers to the State General fund from Gaming

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transfers-to-the-state-general-fund-from-gaming) |
| Metadata | [Link](https://data.ct.gov/api/views/j6mp-nsv2) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/j6mp-nsv2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/j6mp-nsv2/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | j6mp-nsv2 |
| Name | Transfers to the State General fund from Gaming |
| Attribution | Dept. of Consumer Protection |
| Category | Government |
| Tags | lottery, casinos, bingo, raffles, bazaar, otb, pair-mutuel |
| Created | 2014-08-08T18:55:49Z |
| Publication Date | 2014-08-08T18:59:14Z |

## Description

This data set shows all transfers to the State General Fund from all sources of gaming.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | numeric metric | fye_6_30                  | FYE 6/30                  | number    | number      |
| Yes      | numeric metric | lottery                   | Lottery                   | money     | money       |
| Yes      | numeric metric | plainfield_greyhound      | Plainfield Greyhound      | money     | money       |
| Yes      | numeric metric | bridgeport_shoreline_star | Bridgeport Shoreline Star | money     | money       |
| Yes      | numeric metric | hartford_jai_alai         | Hartford Jai Alai         | money     | money       |
| Yes      | numeric metric | milford_jai_alai          | Milford Jai Alai          | money     | money       |
| Yes      | numeric metric | pari_mutuel_subtotal      | Pari-mutuel Subtotal      | money     | money       |
| Yes      | numeric metric | off_track_betting         | Off-Track Betting         | money     | money       |
| Yes      | numeric metric | charitable_games          | Charitable Games          | money     | money       |
| Yes      | numeric metric | foxwoods                  | Foxwoods                  | money     | money       |
| Yes      | numeric metric | mohegan_sun               | Mohegan Sun               | money     | money       |
| Yes      | numeric metric | casino_subtotal           | Casino Subtotal           | money     | money       |
| Yes      | series tag     | grand_total               | Grand Total               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:j6mp-nsv2 d:2014-08-08T11:55:52.000Z t:grand_total=$8,150,000 m:fye_6_30=1972 m:lottery=8150000

series e:j6mp-nsv2 d:2014-08-08T11:55:52.000Z t:grand_total="* 16,500,000" m:fye_6_30=1973 m:lottery=16500000

series e:j6mp-nsv2 d:2014-08-08T11:55:52.000Z t:grand_total="* 16,000,000" m:fye_6_30=1974 m:lottery=16000000
```

## Meta Commands

```ls
metric m:fye_6_30 p:integer l:"FYE 6/30" t:dataTypeName=number

metric m:lottery p:long l:Lottery t:dataTypeName=money

metric m:plainfield_greyhound p:integer l:"Plainfield Greyhound" t:dataTypeName=money

metric m:bridgeport_shoreline_star p:integer l:"Bridgeport Shoreline Star" t:dataTypeName=money

metric m:hartford_jai_alai p:integer l:"Hartford Jai Alai" t:dataTypeName=money

metric m:milford_jai_alai p:integer l:"Milford Jai Alai" t:dataTypeName=money

metric m:pari_mutuel_subtotal p:integer l:"Pari-mutuel Subtotal" t:dataTypeName=money

metric m:off_track_betting p:integer l:"Off-Track Betting" t:dataTypeName=money

metric m:charitable_games p:integer l:"Charitable Games" t:dataTypeName=money

metric m:foxwoods p:long l:Foxwoods t:dataTypeName=money

metric m:mohegan_sun p:long l:"Mohegan Sun" t:dataTypeName=money

metric m:casino_subtotal p:long l:"Casino Subtotal" t:dataTypeName=money

entity e:j6mp-nsv2 l:"Transfers to the State General fund from Gaming" t:attribution="Dept. of Consumer Protection" t:url=https://data.ct.gov/api/views/j6mp-nsv2

property e:j6mp-nsv2 t:meta.view v:id=j6mp-nsv2 v:category=Government v:attributionLink=http://www.ct.gov/dcp/lib/dcp/pdf/gaming/stmt2014.pdf v:averageRating=0 v:name="Transfers to the State General fund from Gaming" v:attribution="Dept. of Consumer Protection"

property e:j6mp-nsv2 t:meta.view.license v:name="Public Domain"

property e:j6mp-nsv2 t:meta.view.owner v:id=ewkk-db5a v:screenName=WilliamR v:displayName=WilliamR

property e:j6mp-nsv2 t:meta.view.tableauthor v:id=ewkk-db5a v:screenName=WilliamR v:roleName=editor v:displayName=WilliamR
```

## Top Records

```ls
| :updated_at | fye_6_30 | lottery  | plainfield_greyhound | bridgeport_shoreline_star | hartford_jai_alai | milford_jai_alai | pari_mutuel_subtotal | off_track_betting | charitable_games | foxwoods | mohegan_sun | casino_subtotal | grand_total  | 
| =========== | ======== | ======== | ==================== | ========================= | ================= | ================ | ==================== | ================= | ================ | ======== | =========== | =============== | ============ | 
| 1407498952  | 1972     | 8150000  |                      |                           |                   |                  |                      |                   |                  |          |             |                 | $8,150,000   | 
| 1407498952  | 1973     | 16500000 |                      |                           |                   |                  |                      |                   |                  |          |             |                 | * 16,500,000 | 
| 1407498952  | 1974     | 16000000 |                      |                           |                   |                  |                      |                   |                  |          |             |                 | * 16,000,000 | 
| 1407498952  | 1975     | 15000000 |                      |                           |                   |                  |                      |                   |                  |          |             |                 | * 15,000,000 | 
| 1407498952  | 1976     | 31900000 | 4924536              | 225333                    | 384241            |                  | 5534110              |                   |                  |          |             |                 | * 37,434,110 | 
| 1407498952  | 1977     | 25341822 | 9897029              | 7539664                   | 4215515           | 949904           | 22602112             | 8000000           |                  |          |             |                 | * 55,943,934 | 
| 1407498952  | 1978     | 41790050 | 8119339              | 4850208                   | 4708105           | 4556746          | 22234398             | 8800000           |                  |          |             |                 | * 72,824,448 | 
| 1407498952  | 1979     | 43117000 | 7806377              | 5092827                   | 4199321           | 4416805          | 21515330             | 7800000           |                  |          |             |                 | * 72,432,330 | 
| 1407498952  | 1980     | 54535048 | 7176368              | 4739781                   | 4188854           | 4738019          | 20843022             | 13100000          |                  |          |             |                 | * 88,478,070 | 
| 1407498952  | 1981     | 57653000 | 7517524              | 4659929                   | 3930327           | 4096110          | 20203890             | 13500000          |                  |          |             |                 | * 91,356,890 | 
```