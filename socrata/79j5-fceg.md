# Foxwoods Slot Machine Contributions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foxwoods-slot-machine-contributions) |
| Metadata | [Link](https://data.ct.gov/api/views/79j5-fceg) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/79j5-fceg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/79j5-fceg/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 79j5-fceg |
| Name | Foxwoods Slot Machine Contributions |
| Attribution | CT Dept. of Consumer Protection |
| Category | Government |
| Tags | foxwoods, slots, slots contribution |
| Created | 2014-05-23T17:24:05Z |
| Publication Date | 2014-10-10T18:48:39Z |

## Description

Slot Machine Contributions to State of Connecticut

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                   | Data Type | Render Type |
| ======== | ============== | ==================================================== | ====================================================== | ========= | =========== |
| No       | time           | :updated_at                                          | updated_at                                             | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year_month                                    | Fiscal Year/Month                                      | text      | text        |
| Yes      | numeric metric | handle                                               | Handle                                                 | money     | money       |
| Yes      | numeric metric | win                                                  | Win                                                    | money     | money       |
| Yes      | numeric metric | hold                                                 | Hold %                                                 | percent   | percent     |
| Yes      | numeric metric | payout                                               | Payout %                                               | percent   | percent     |
| Yes      | series tag     | weighted_average_of_machines                         | Weighted Average # of Machines                         | text      | text        |
| Yes      | numeric metric | slot_machine_contributions_to_state_of_connecticut_1 | Slot Machine Contributions to State of Connecticut (1) | money     | money       |
| Yes      | numeric metric | free_play_coupons_redeemed_at_slot_machines_3        | Free Play Coupons Redeemed at Slot Machines (3)        | money     | money       |
| Yes      | numeric metric | free_play_contribution_4                             | Free Play Contribution (4)                             | money     | money       |
| Yes      | numeric metric | total_contributions_1                                | Total Contributions (1)                                | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:79j5-fceg d:2014-10-10T11:48:11.000Z t:weighted_average_of_machines="* 5,774" t:fiscal_year_month="Total FY 2014/2015" m:free_play_coupons_redeemed_at_slot_machines_3=11656159 m:handle=1097336087 m:slot_machine_contributions_to_state_of_connecticut_1=22828230 m:hold=8.32 m:total_contributions_1=23231164 m:win=91312921 m:free_play_contribution_4=402934 m:payout=91.68

series e:79j5-fceg d:2014-10-10T11:48:11.000Z t:weighted_average_of_machines="* 5,773" t:fiscal_year_month="August (3) (4)" m:free_play_coupons_redeemed_at_slot_machines_3=6231115 m:handle=565132210 m:slot_machine_contributions_to_state_of_connecticut_1=11743405 m:hold=8.31 m:total_contributions_1=12009409 m:win=46973621 m:free_play_contribution_4=266004 m:payout=91.69

series e:79j5-fceg d:2014-10-10T11:48:11.000Z t:weighted_average_of_machines="* 5,775" t:fiscal_year_month="July 2014 (3) (4)" m:free_play_coupons_redeemed_at_slot_machines_3=5425044 m:handle=532203877 m:slot_machine_contributions_to_state_of_connecticut_1=11084825 m:hold=8.33 m:total_contributions_1=11221755 m:win=44339300 m:free_play_contribution_4=136930 m:payout=91.67
```

## Meta Commands

```ls
metric m:handle p:long l:Handle t:dataTypeName=money

metric m:win p:integer l:Win t:dataTypeName=money

metric m:hold p:float l:"Hold %" t:dataTypeName=percent

metric m:payout p:float l:"Payout %" t:dataTypeName=percent

metric m:slot_machine_contributions_to_state_of_connecticut_1 p:integer l:"Slot Machine Contributions to State of Connecticut (1)" t:dataTypeName=money

metric m:free_play_coupons_redeemed_at_slot_machines_3 p:integer l:"Free Play Coupons Redeemed at Slot Machines (3)" t:dataTypeName=money

metric m:free_play_contribution_4 p:integer l:"Free Play Contribution (4)" t:dataTypeName=money

metric m:total_contributions_1 p:integer l:"Total Contributions (1)" t:dataTypeName=money

entity e:79j5-fceg l:"Foxwoods Slot Machine Contributions" t:attribution="CT Dept. of Consumer Protection" t:url=https://data.ct.gov/api/views/79j5-fceg

property e:79j5-fceg t:meta.view v:id=79j5-fceg v:category=Government v:attributionLink="http://www.ct.gov/dcp/cwp/view.asp?a=4332&q=480854" v:averageRating=0 v:name="Foxwoods Slot Machine Contributions" v:attribution="CT Dept. of Consumer Protection"

property e:79j5-fceg t:meta.view.owner v:id=ewkk-db5a v:screenName=WilliamR v:displayName=WilliamR

property e:79j5-fceg t:meta.view.tableauthor v:id=ewkk-db5a v:screenName=WilliamR v:roleName=editor v:displayName=WilliamR
```

## Top Records

```ls
| :updated_at | fiscal_year_month    | handle     | win       | hold | payout | weighted_average_of_machines | slot_machine_contributions_to_state_of_connecticut_1 | free_play_coupons_redeemed_at_slot_machines_3 | free_play_contribution_4 | total_contributions_1 | 
| =========== | ==================== | ========== | ========= | ==== | ====== | ============================ | ==================================================== | ============================================= | ======================== | ===================== | 
| 1412941691  | Total FY 2014/2015   | 1097336087 | 91312921  | 8.32 | 91.68  | * 5,774                      | 22828230                                             | 11656159                                      | 402934                   | 23231164              | 
| 1412941691  | August (3) (4)       | 565132210  | 46973621  | 8.31 | 91.69  | * 5,773                      | 11743405                                             | 6231115                                       | 266004                   | 12009409              | 
| 1412941691  | July 2014 (3) (4)    | 532203877  | 44339300  | 8.33 | 91.67  | * 5,775                      | 11084825                                             | 5425044                                       | 136930                   | 11221755              | 
| 1412941691  | Total FY 2013/2014   | 6096879163 | 507881725 | 8.33 | 91.67  | * 5,825                      | 126970431                                            | 70216886                                      | 4557211                  | 131527642             | 
| 1412941691  | June (3) (4)         | 479133141  | 37692798  | 7.87 | 92.13  | * 5,793                      | 9423200                                              | 6756532                                       | 652581                   | 10075781              | 
| 1412941691  | May (3) (4)          | 541779518  | 43718359  | 8.07 | 91.93  | * 5,817                      | 10929590                                             | 8077990                                       | 817243                   | 11746833              | 
| 1412941691  | April(3) (4)         | 507841230  | 39785415  | 7.83 | 92.17  | * 5,820                      | 9946354                                              | 7854900                                       | 869626                   | 10815980              | 
| 1412941691  | March(3) (4)         | 566010289  | 44588068  | 7.88 | 92.12  | * 5,821                      | 11147017                                             | 9064481                                       | 1039948                  | 12186965              | 
| 1412941691  | February (3) (4)     | 479298292  | 39342846  | 8.21 | 91.79  | * 5,823                      | 9835711                                              | 6791161                                       | 615862                   | 10451573              | 
| 1412941691  | January 2014 (3) (4) | 433326706  | 37074032  | 8.56 | 91.44  | * 5,830                      | 9268508                                              | 4333157                                       | 63753                    | 9332261               | 
```