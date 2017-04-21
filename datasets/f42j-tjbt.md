# Private Pay Rates for Home and Community-Based Long Term Care Services 2014 Home Health Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/private-pay-rates-for-home-and-community-based-long-term-care-services-2014-home-health-ra) |
| Metadata | [Link](https://data.ct.gov/api/views/f42j-tjbt) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/f42j-tjbt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/f42j-tjbt/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | f42j-tjbt |
| Name | Private Pay Rates for Home and Community-Based Long Term Care Services 2014 Home Health Rates |
| Category | Government |
| Tags | long term care, opm |
| Created | 2014-06-26T17:26:59Z |
| Publication Date | 2014-06-26T17:30:34Z |

## Description

This survey provides a list of home and community-based providers and their private pay rates for long term care services.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                      | Data Type | Render Type |
| ======== | ============== | ======================= | ========================= | ========= | =========== |
| Yes      | series tag     | agency                  | AGENCY                    | text      | text        |
| Yes      | series tag     | town                    | Town                      | text      | text        |
| Yes      | series tag     | skilled_nursing_visits  | Skilled Nursing Visits    | text      | text        |
| Yes      | series tag     | therapies_phys_visits   | Therapies - Phys Visits   | text      | text        |
| Yes      | series tag     | therapies_occup_visits  | Therapies - Occup Visits  | text      | text        |
| Yes      | series tag     | therapies_speech_visits | Therapies - Speech Visits | text      | text        |
| Yes      | series tag     | personal_care_attendant | Personal Care Attendant   | text      | text        |
| Yes      | series tag     | hha_hrs                 | HHA Hrs.                  | text      | text        |
| Yes      | series tag     | private_duty_rn         | Private Duty - RN         | text      | text        |
| Yes      | series tag     | private_duty_lpn        | Private Duty - LPN        | text      | text        |
| Yes      | numeric metric | none                    | (none)                    | money     | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:none p:long l:(none) t:dataTypeName=money

entity e:f42j-tjbt l:"Private Pay Rates for Home and Community-Based Long Term Care Services 2014 Home Health Rates" t:url=https://data.ct.gov/api/views/f42j-tjbt

property e:f42j-tjbt t:meta.view v:id=f42j-tjbt v:category=Government v:averageRating=0 v:name="Private Pay Rates for Home and Community-Based Long Term Care Services 2014 Home Health Rates"

property e:f42j-tjbt t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:f42j-tjbt t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| agency                              | town       | skilled_nursing_visits | therapies_phys_visits | therapies_occup_visits | therapies_speech_visits | personal_care_attendant | hha_hrs | private_duty_rn | private_duty_lpn | none | 
| =================================== | ========== | ====================== | ===================== | ====================== | ======================= | ======================= | ======= | =============== | ================ | ==== | 
| VNS, Inc. of Southern CT            | Ansonia    | $120.00                | $120.00               | $120.00                | $120.00                 |                         | $27.00  |                 |                  |      | 
| Help At Home, Inc.                  | Avon       |                        |                       |                        |                         | $20.00                  |         |                 |                  |      | 
| VNA Northwest                       | Bantam     | $145.00                | $155.00               | $155.00                | $155.00                 |                         | $80.00  |                 |                  |      | 
| Berlin VNA                          | Berlin     | $145.00                | $100.00               | $100.00                | $129.00                 |                         | $40.00  |                 |                  |      | 
| Euro-American Connections, LLC      | Berlin     |                        |                       |                        |                         | $19.00                  |         |                 |                  |      | 
| Euro-American Homecare, LLC         | Berlin     |                        |                       |                        |                         | $22.00                  |         |                 |                  |      | 
| Bethel VNA                          | Bethel     | $140.00                | $140.00               | $140.00                | $140.00                 |                         | $35.00  |                 |                  |      | 
| Besa Companions and Homemakers      | Bloomfield |                        |                       |                        |                         | $22.00                  |         |                 |                  |      | 
| Comfort Keepers of Greater Hartford | Bloomfield |                        |                       |                        |                         | $21.00                  | $21.00  |                 |                  |      | 
| Global Horizon Home Care            | Bloomfield | $130.00                | $140.00               | $140.00                | $140.00                 | $28.00                  | $34.00  | $65.00          | $55.00           |      | 
```