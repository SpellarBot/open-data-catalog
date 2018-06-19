# Private Pay Rates for Home and Community-Based Long Term Care Services 2014 Home And CBS Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/private-pay-rates-for-home-and-community-based-long-term-care-services-2014-home-and-cbs-r) |
| Metadata | [Link](https://data.ct.gov/api/views/efa5-f6zx) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/efa5-f6zx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/efa5-f6zx/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | efa5-f6zx |
| Name | Private Pay Rates for Home and Community-Based Long Term Care Services 2014 Home And CBS Rates |
| Category | Government |
| Tags | long term care, opm |
| Created | 2014-06-26T16:49:57Z |
| Publication Date | 2014-06-26T16:54:57Z |

## Description

This survey provides a list of home and community-based providers and their private pay rates for long term care services.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | agency                      | AGENCY                      | text      | text        |
| Yes      | series tag     | town                        | Town                        | text      | text        |
| Yes      | series tag     | adult_day_care_full_day     | Adult Day Care Full Day     | text      | text        |
| Yes      | series tag     | adult_day_care_half_day     | Adult Day Care Half Day     | text      | text        |
| Yes      | series tag     | chore_svcs                  | Chore Svcs.                 | text      | text        |
| Yes      | series tag     | home_maker_svcs             | Home-maker Svcs.            | text      | text        |
| Yes      | series tag     | companion_svcs              | Companion Svcs.             | text      | text        |
| Yes      | series tag     | live_in_companion           | Live-In Companion           | text      | text        |
| Yes      | series tag     | home_delivered_single_meal  | Home-Delivered Single Meal  | text      | text        |
| Yes      | numeric metric | home_delivered_double_meal  | Home-Delivered Double Meal  | money     | text        |
| Yes      | numeric metric | 2_way_pers_installation_fee | 2-Way PERS Installation Fee | percent   | percent     |
| Yes      | series tag     | 2_way_pers_monthly_fee      | 2-Way PERS Monthly Fee      | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:efa5-f6zx d:2014-01-01T00:00:00.000Z t:companion_svcs=$25.00 t:home_maker_svcs=$30.00 t:agency="Seabury Community Outreach" t:2_way_pers_monthly_fee=$54.95 t:town=Bloomfield m:2_way_pers_installation_fee=12

series e:efa5-f6zx d:2014-01-01T00:00:00.000Z t:companion_svcs=$26.50 t:home_maker_svcs=$26.50 t:chore_svcs=$45.00 t:agency="Hebrew Health Visiting Nurses" t:2_way_pers_monthly_fee=$58.33 t:town=Bloomfield m:2_way_pers_installation_fee=50

series e:efa5-f6zx d:2014-01-01T00:00:00.000Z t:agency="Town of Bloomfield, Senior Svcs." t:town=Bloomfield m:home_delivered_double_meal=6
```

## Meta Commands

```ls
metric m:home_delivered_double_meal p:double l:"Home-Delivered Double Meal" t:dataTypeName=money

metric m:2_way_pers_installation_fee p:float l:"2-Way PERS Installation Fee" t:dataTypeName=percent

entity e:efa5-f6zx l:"Private Pay Rates for Home and Community-Based Long Term Care Services 2014 Home And CBS Rates" t:url=https://data.ct.gov/api/views/efa5-f6zx

property e:efa5-f6zx t:meta.view v:id=efa5-f6zx v:category=Government v:averageRating=0 v:name="Private Pay Rates for Home and Community-Based Long Term Care Services 2014 Home And CBS Rates"

property e:efa5-f6zx t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:efa5-f6zx t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| agency                             | town       | adult_day_care_full_day | adult_day_care_half_day | chore_svcs | home_maker_svcs | companion_svcs | live_in_companion | home_delivered_single_meal | home_delivered_double_meal | 2_way_pers_installation_fee | 2_way_pers_monthly_fee | 
| ================================== | ========== | ======================= | ======================= | ========== | =============== | ============== | ================= | ========================== | ========================== | =========================== | ====================== | 
| VNS, Inc. of Southern CT           | Ansonia    |                         |                         |            | $18.50          | $17.00         |                   |                            |                            |                             |                        | 
| Companions and Homemakers          | Avon       |                         |                         |            | $18.50          | $16.50         | $200.00           |                            |                            |                             |                        | 
| Friendship Circle Adult Day Center | Avon       | $71.00                  | $47.00                  |            |                 |                |                   |                            |                            |                             |                        | 
| Help At home, Inc.                 | Avon       |                         |                         | $18.50     | $18.50          | $17.50         |                   |                            |                            |                             |                        | 
| Euro-American Connections, LLC     | Berlin     |                         |                         | $18.00     | $17.00          | $16.00         | $175.00           |                            |                            |                             |                        | 
| Euro-American Homecare, LLC        | Berlin     |                         |                         |            | $20.00          | $19.00         | $210.00           |                            |                            |                             |                        | 
| Berlin VNA                         | Berlin     |                         |                         |            | $45.00          |                |                   |                            |                            |                             |                        | 
| Companions and Homemakers          | Berlin     |                         |                         |            | $18.50          | $16.50         | $200.00           |                            |                            |                             |                        | 
| Bethel VNA                         | Bethel     |                         |                         |            | $22.00          |                |                   |                            |                            |                             |                        | 
| Besa Companions and Homemakers     | Bloomfield |                         |                         |            | $18.50          | $18.50         |                   |                            |                            |                             |                        | 
```