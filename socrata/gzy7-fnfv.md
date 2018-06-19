# 2013 Proposed Budget, FTEs, All Funds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-proposed-budget-ftes-all-funds-71797) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/gzy7-fnfv) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/gzy7-fnfv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/gzy7-fnfv/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | gzy7-fnfv |
| Name | 2013 Proposed Budget, FTEs, All Funds |
| Attribution | King County Executive |
| Category | Budget |
| Tags | budget, 2013, budget2013 |
| Created | 2012-09-23T20:36:12Z |
| Publication Date | 2012-09-23T20:42:34Z |

## Description

King County budget proposed September 2012 by Executive for 2013, FTEs, all funds, broken down by strategic area and appropriation unit. See http://www.kingcounty.gov/budget for more.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | series tag     | strategic_area                     | Strategic Area                     | text      | text        |
| Yes      | series tag     | appropriation_unit                 | Appropriation Unit                 | text      | text        |
| Yes      | numeric metric | general_fund_adopted_1             | 2011 General Fund Adopted          | number    | number      |
| Yes      | numeric metric | non_general_fund_adopted_1         | 2011 Non-General Fund Adopted      | number    | number      |
| Yes      | numeric metric | general_fund_adopted_2             | 2012 General Fund Adopted          | number    | number      |
| Yes      | numeric metric | non_general_fund_adopted_2         | 2012 Non-General Fund Adopted      | number    | number      |
| Yes      | numeric metric | general_fund_proposed_1            | 2013 General Fund Proposed         | number    | number      |
| Yes      | numeric metric | non_general_fund_proposed_1        | 2013 Non-General Fund Proposed     | number    | number      |
| Yes      | series tag     | general_fund_proposed_2            | 2014 General Fund Proposed         | text      | text        |
| Yes      | numeric metric | non_general_fund_proposed_2        | 2014 Non-General Fund Proposed     | number    | number      |
| Yes      | numeric metric | general_fund_amount_of_change      | General Fund Amount of Change      | number    | number      |
| Yes      | numeric metric | non_general_fund_amount_of_change  | Non-General Fund Amount of Change  | number    | number      |
| Yes      | numeric metric | general_fund_percent_of_change     | General Fund Percent of Change     | percent   | percent     |
| Yes      | numeric metric | non_general_fund_percent_of_change | Non-General Fund Percent of Change | percent   | percent     |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gzy7-fnfv d:2013-01-01T00:00:00.000Z t:strategic_area="Justice and Safety" t:appropriation_unit="Adult And Juvenile Detention" m:general_fund_amount_of_change=-47.78 m:general_fund_percent_of_change=-5.1 m:general_fund_proposed_1=891.72 m:general_fund_adopted_2=939.5 m:general_fund_adopted_1=951.5

series e:gzy7-fnfv d:2013-01-01T00:00:00.000Z t:strategic_area="Justice and Safety" t:appropriation_unit="District Court" m:general_fund_amount_of_change=7.5 m:general_fund_percent_of_change=3.1 m:general_fund_proposed_1=252 m:general_fund_adopted_2=244.5 m:general_fund_adopted_1=245.45

series e:gzy7-fnfv d:2013-01-01T00:00:00.000Z t:strategic_area="Justice and Safety" t:appropriation_unit="Drug Enforcement Forfeits" m:general_fund_amount_of_change=0 m:general_fund_percent_of_change=0 m:general_fund_proposed_1=4 m:general_fund_adopted_2=4 m:general_fund_adopted_1=3
```

## Meta Commands

```ls
metric m:general_fund_adopted_1 p:float l:"2011 General Fund Adopted" t:dataTypeName=number

metric m:non_general_fund_adopted_1 p:float l:"2011 Non-General Fund Adopted" t:dataTypeName=number

metric m:general_fund_adopted_2 p:float l:"2012 General Fund Adopted" t:dataTypeName=number

metric m:non_general_fund_adopted_2 p:float l:"2012 Non-General Fund Adopted" t:dataTypeName=number

metric m:general_fund_proposed_1 p:float l:"2013 General Fund Proposed" t:dataTypeName=number

metric m:non_general_fund_proposed_1 p:float l:"2013 Non-General Fund Proposed" t:dataTypeName=number

metric m:non_general_fund_proposed_2 p:float l:"2014 Non-General Fund Proposed" t:dataTypeName=number

metric m:general_fund_amount_of_change p:float l:"General Fund Amount of Change" t:dataTypeName=number

metric m:non_general_fund_amount_of_change p:float l:"Non-General Fund Amount of Change" t:dataTypeName=number

metric m:general_fund_percent_of_change p:float l:"General Fund Percent of Change" t:dataTypeName=percent

metric m:non_general_fund_percent_of_change p:float l:"Non-General Fund Percent of Change" t:dataTypeName=percent

entity e:gzy7-fnfv l:"2013 Proposed Budget, FTEs, All Funds" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/gzy7-fnfv

property e:gzy7-fnfv t:meta.view v:id=gzy7-fnfv v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="2013 Proposed Budget, FTEs, All Funds" v:attribution="King County Executive"

property e:gzy7-fnfv t:meta.view.license v:name="Public Domain"

property e:gzy7-fnfv t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:gzy7-fnfv t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| strategic_area     | appropriation_unit             | general_fund_adopted_1 | non_general_fund_adopted_1 | general_fund_adopted_2 | non_general_fund_adopted_2 | general_fund_proposed_1 | non_general_fund_proposed_1 | general_fund_proposed_2 | non_general_fund_proposed_2 | general_fund_amount_of_change | non_general_fund_amount_of_change | general_fund_percent_of_change | non_general_fund_percent_of_change | 
| ================== | ============================== | ====================== | ========================== | ====================== | ========================== | ======================= | =========================== | ======================= | =========================== | ============================= | ================================= | ============================== | ================================== | 
| Justice and Safety | Adult And Juvenile Detention   | 951.5                  |                            | 939.5                  |                            | 891.72                  |                             |                         |                             | -47.78                        |                                   | -5.10                          |                                    | 
| Justice and Safety | District Court                 | 245.45                 |                            | 244.5                  |                            | 252                     |                             |                         |                             | 7.5                           |                                   | 3.10                           |                                    | 
| Justice and Safety | Drug Enforcement Forfeits      | 3                      |                            | 4                      |                            | 4                       |                             |                         |                             | 0                             |                                   | 0.00                           |                                    | 
| Justice and Safety | Jail Health Services           | 140.5                  |                            | 141.9                  |                            | 136.7                   |                             |                         |                             | -5.2                          |                                   | -3.70                          |                                    | 
| Justice and Safety | Judicial Administration        | 203                    |                            | 201.5                  |                            | 199                     |                             |                         |                             | -2.5                          |                                   | -1.20                          |                                    | 
| Justice and Safety | Office Of Emergency Management | 4                      |                            | 6                      |                            | 6                       |                             |                         |                             | 0                             |                                   | 0.00                           |                                    | 
| Justice and Safety | Office Of The Public Defender  | 18.75                  |                            | 18.75                  |                            | 19.75                   |                             |                         |                             | 1                             |                                   | 5.30                           |                                    | 
| Justice and Safety | Prosecuting Attorney           | 458.8                  |                            | 463.3                  |                            | 457.3                   |                             |                         |                             | -6                            |                                   | -1.30                          |                                    | 
| Justice and Safety | Sheriff                        | 995.8                  |                            | 958.8                  |                            | 960.25                  |                             |                         |                             | 1.45                          |                                   | 0.20                           |                                    | 
| Justice and Safety | Superior Court                 | 371.85                 |                            | 361                    |                            | 357.5                   |                             |                         |                             | -3.5                          |                                   | -1.00                          |                                    | 
```