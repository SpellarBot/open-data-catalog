# Lottery Gross Sales, Prizes, Agent Commissions And Transfers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-gross-sales-prizes-agent-commissions-and-transfers) |
| Metadata | [Link](https://data.ct.gov/api/views/sdpj-q7rw) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/sdpj-q7rw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/sdpj-q7rw/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | sdpj-q7rw |
| Name | Lottery Gross Sales, Prizes, Agent Commissions And Transfers |
| Attribution | CT Dept of Consumer Protection |
| Category | Government |
| Tags | lottery gross sales, prizes, agent commissions |
| Created | 2014-10-14T18:53:56Z |
| Publication Date | 2014-10-14T18:56:46Z |

## Description

Lottery Gross Sales, Prizes, Agent Commissions And Transfers

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| No       | time           | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year                   | Fiscal Year                   | text      | text        |
| Yes      | series tag     | game                          | Game                          | text      | text        |
| Yes      | numeric metric | gross_sales                   | Gross Sales                   | money     | money       |
| Yes      | numeric metric | prizes                        | Prizes                        | money     | money       |
| Yes      | numeric metric | agent_commissions             | Agent Commissions             | money     | money       |
| Yes      | numeric metric | transfers_to_the_general_fund | Transfers to the General Fund | money     | money       |
| Yes      | numeric metric | percent                       | Percent                       | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sdpj-q7rw d:2014-10-14T11:53:59.000Z t:fiscal_year=1979 t:game=Weekly m:transfers_to_the_general_fund=3917000 m:percent=30.4 m:agent_commissions=605841 m:gross_sales=12871166 m:prizes=7953527

series e:sdpj-q7rw d:2014-10-14T11:53:59.000Z t:game=Instant m:transfers_to_the_general_fund=18200000 m:percent=36.6 m:agent_commissions=2649310 m:gross_sales=49725859 m:prizes=26749512

series e:sdpj-q7rw d:2014-10-14T11:53:59.000Z t:game=Daily m:transfers_to_the_general_fund=21000000 m:percent=36 m:agent_commissions=2915308 m:gross_sales=58327191 m:prizes=33334646
```

## Meta Commands

```ls
metric m:gross_sales p:integer l:"Gross Sales" t:dataTypeName=money

metric m:prizes p:integer l:Prizes t:dataTypeName=money

metric m:agent_commissions p:integer l:"Agent Commissions" t:dataTypeName=money

metric m:transfers_to_the_general_fund p:integer l:"Transfers to the General Fund" t:dataTypeName=money

metric m:percent p:float l:Percent t:dataTypeName=percent

entity e:sdpj-q7rw l:"Lottery Gross Sales, Prizes, Agent Commissions And Transfers" t:attribution="CT Dept of Consumer Protection" t:url=https://data.ct.gov/api/views/sdpj-q7rw

property e:sdpj-q7rw t:meta.view v:id=sdpj-q7rw v:category=Government v:attributionLink="http://www.ct.gov/dcp/cwp/view.asp?a=4332&q=480854" v:averageRating=0 v:name="Lottery Gross Sales, Prizes, Agent Commissions And Transfers" v:attribution="CT Dept of Consumer Protection"

property e:sdpj-q7rw t:meta.view.license v:name="Public Domain"

property e:sdpj-q7rw t:meta.view.owner v:id=ewkk-db5a v:screenName=WilliamR v:displayName=WilliamR

property e:sdpj-q7rw t:meta.view.tableauthor v:id=ewkk-db5a v:screenName=WilliamR v:roleName=editor v:displayName=WilliamR
```

## Top Records

```ls
| :updated_at | fiscal_year | game    | gross_sales | prizes   | agent_commissions | transfers_to_the_general_fund | percent | 
| =========== | =========== | ======= | =========== | ======== | ================= | ============================= | ======= | 
| 1413287639  | 1979        | Weekly  | 12871166    | 7953527  | 605841            | 3917000                       | 30.4    | 
| 1413287639  |             | Instant | 49725859    | 26749512 | 2649310           | 18200000                      | 36.6    | 
| 1413287639  |             | Daily   | 58327191    | 33334646 | 2915308           | 21000000                      | 36.0    | 
| 1413287639  |             | Total   | 120924216   | 68037685 | 6170459           | 43117000                      | 35.7    | 
| 1413287639  | 1980        | Weekly  | 11525566    | 7203548  | 543883            | 3500000                       | 30.4    | 
| 1413287639  |             | Instant | 45505590    | 25011521 | 2301209           | 17735048                      | 39.0    | 
| 1413287639  |             | Daily   | 73167966    | 39837734 | 3647986           | 33300000                      | 45.5    | 
| 1413287639  |             | Total   | 130199122   | 72052803 | 6493078           | 54535048                      | 41.9    | 
| 1413287639  | 1981        | Weekly  | 10103356    | 7636663  | 476104            | 1503000                       | 14.9    | 
| 1413287639  |             | Instant | 56162297    | 30511317 | 3030895           | 21500000                      | 38.3    | 
```