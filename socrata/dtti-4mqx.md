# Home And Community Based Services Rates as of January 1st, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-and-community-based-services-rates-as-of-january-1st-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/dtti-4mqx) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/dtti-4mqx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/dtti-4mqx/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | dtti-4mqx |
| Name | Home And Community Based Services Rates as of January 1st, 2015 |
| Category | Health and Human Services |
| Tags | opm, ltc, long term care |
| Created | 2015-05-04T16:32:54Z |
| Publication Date | 2015-05-04T16:34:41Z |

## Description

This data provides a list of home and community-based service providers and their private pay rates for long term care services.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | agency                      | AGENCY                      | text      | text        |
| Yes      | series tag     | town                        | Town                        | text      | text        |
| Yes      | numeric metric | adult_day_care_full_day     | Adult Day Care Full Day     | money     | money       |
| Yes      | numeric metric | adult_day_care_half_day     | Adult Day Care Half Day     | money     | money       |
| Yes      | numeric metric | chore_svcs                  | Chore Svcs.                 | money     | money       |
| Yes      | numeric metric | home_maker_svcs             | Home-maker Svcs.            | money     | money       |
| Yes      | numeric metric | companion_svcs              | Companion Svcs.             | money     | money       |
| Yes      | numeric metric | live_in_companion           | Live-In Companion           | money     | money       |
| Yes      | numeric metric | home_delivered_single_meal  | Home-Delivered Single Meal  | money     | money       |
| Yes      | numeric metric | home_delivered_double_meal  | Home-Delivered Double Meal  | money     | money       |
| Yes      | numeric metric | 2_way_pers_installation_fee | 2-Way PERS Installation Fee | number    | number      |
| Yes      | numeric metric | 2_way_persmonthly_fee       | 2-Way PERSMonthly Fee       | money     | money       |
| Yes      | time           | year                        | Year                        | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dtti-4mqx d:2015-01-01T00:00:00.000Z t:agency="VNS, Inc. of Southern CT" t:town=Ansonia m:companion_svcs=18.5 m:home_maker_svcs=20.25 m:live_in_companion=175

series e:dtti-4mqx d:2015-01-01T00:00:00.000Z t:agency="Companions and Homemakers" t:town=Avon m:companion_svcs=17.5 m:home_maker_svcs=19.5 m:live_in_companion=220

series e:dtti-4mqx d:2015-01-01T00:00:00.000Z t:agency="Friendship Circle Adult Day Center" t:town=Avon m:adult_day_care_full_day=71 m:adult_day_care_half_day=47
```

## Meta Commands

```ls
metric m:adult_day_care_full_day p:double l:"Adult Day Care Full Day" t:dataTypeName=money

metric m:adult_day_care_half_day p:double l:"Adult Day Care Half Day" t:dataTypeName=money

metric m:chore_svcs p:double l:"Chore Svcs." t:dataTypeName=money

metric m:home_maker_svcs p:double l:"Home-maker Svcs." t:dataTypeName=money

metric m:companion_svcs p:double l:"Companion Svcs." t:dataTypeName=money

metric m:live_in_companion p:double l:"Live-In Companion" t:dataTypeName=money

metric m:home_delivered_single_meal p:double l:"Home-Delivered Single Meal" t:dataTypeName=money

metric m:home_delivered_double_meal p:double l:"Home-Delivered Double Meal" t:dataTypeName=money

metric m:2_way_pers_installation_fee p:float l:"2-Way PERS Installation Fee" t:dataTypeName=number

metric m:2_way_persmonthly_fee p:double l:"2-Way PERSMonthly Fee" t:dataTypeName=money

entity e:dtti-4mqx l:"Home And Community Based Services Rates as of January 1st, 2015" t:url=https://data.ct.gov/api/views/dtti-4mqx

property e:dtti-4mqx t:meta.view v:id=dtti-4mqx v:category="Health and Human Services" v:averageRating=0 v:name="Home And Community Based Services Rates as of January 1st, 2015"

property e:dtti-4mqx t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:dtti-4mqx t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| agency                             | town    | adult_day_care_full_day | adult_day_care_half_day | chore_svcs | home_maker_svcs | companion_svcs | live_in_companion | home_delivered_single_meal | home_delivered_double_meal | 2_way_pers_installation_fee | 2_way_persmonthly_fee | year | 
| ================================== | ======= | ======================= | ======================= | ========== | =============== | ============== | ================= | ========================== | ========================== | =========================== | ===================== | ==== | 
|                                    |         |                         |                         |            |                 |                |                   |                            |                            |                             |                       | 2015 | 
| VNS, Inc. of Southern CT           | Ansonia |                         |                         |            | 20.25           | 18.50          | 175.00            |                            |                            |                             |                       | 2015 | 
| Companions and Homemakers          | Avon    |                         |                         |            | 19.50           | 17.50          | 220.00            |                            |                            |                             |                       | 2015 | 
| Friendship Circle Adult Day Center | Avon    | 71.00                   | 47.00                   |            |                 |                |                   |                            |                            |                             |                       | 2015 | 
| Help At home, Inc.                 | Avon    |                         |                         | 18.50      | 18.50           | 17.50          |                   |                            |                            |                             |                       | 2015 | 
| Tender Heart Homecare, LLC         | Bantam  |                         |                         |            | 13.00           | 13.00          | 150.00            |                            |                            |                             |                       | 2015 | 
| Companions and Homemakers          | Berlin  |                         |                         |            | 19.50           | 17.50          | 220.00            |                            |                            |                             |                       | 2015 | 
| Euro-American Connections, LLC     | Berlin  |                         |                         | 20.00      | 18.00           | 17.00          | 195.00            |                            |                            |                             |                       | 2015 | 
| Euro-American Homecare, LLC        | Berlin  |                         |                         |            | 20.00           | 19.00          | 220.00            |                            |                            |                             |                       | 2015 | 
| Bethel VNA                         | Bethel  |                         |                         |            | 22.00           |                |                   |                            |                            |                             |                       | 2015 | 
```