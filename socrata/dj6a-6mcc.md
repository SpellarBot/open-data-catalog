# Nursing Facility Private Pay Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nursing-facility-private-pay-rates) |
| Metadata | [Link](https://data.ct.gov/api/views/dj6a-6mcc) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/dj6a-6mcc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/dj6a-6mcc/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | dj6a-6mcc |
| Name | Nursing Facility Private Pay Rates |
| Category | Health and Human Services |
| Tags | opm, nursing facilities, nursing home, nursing, long-term care, ltc |
| Created | 2015-05-04T15:45:51Z |
| Publication Date | 2015-05-04T15:48:01Z |

## Description

This data provides a list of licensed nursing facilities in Connecticut as of September 30, 2014, including the number of beds and semi-private and private room rates.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                             | Data Type | Render Type |
| ======== | ============== | ============================= | ================================ | ========= | =========== |
| No       | time           | :updated_at                   | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | level_of_care                 | Level of Care                    | text      | text        |
| Yes      | series tag     | facility_name                 | FACILITY NAME                    | text      | text        |
| Yes      | series tag     | town                          | TOWN                             | text      | text        |
| Yes      | numeric metric | licensed_ccnh_beds            | Licensed CCNH Beds               | number    | number      |
| Yes      | numeric metric | room_rate_private_1_bed       | Room Rate: PRIVATE (1 BED)       | money     | money       |
| Yes      | numeric metric | room_rate_semi_private_2_beds | Room Rate: SEMI-PRIVATE (2 BEDS) | money     | money       |
| Yes      | series tag     | year                          | Year                             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dj6a-6mcc d:2015-05-04T08:45:55.000Z t:level_of_care=CCNH t:facility_name="Apple Rehab Avon" t:year=2014 t:town=Avon m:licensed_ccnh_beds=60 m:room_rate_semi_private_2_beds=410 m:room_rate_private_1_bed=424

series e:dj6a-6mcc d:2015-05-04T08:45:55.000Z t:level_of_care=CCNH t:facility_name="Avon Health Center" t:year=2014 t:town=Avon m:licensed_ccnh_beds=120 m:room_rate_semi_private_2_beds=407 m:room_rate_private_1_bed=425

series e:dj6a-6mcc d:2015-05-04T08:45:55.000Z t:level_of_care=CCNH t:facility_name="Bethel Health Care Center" t:year=2014 t:town=Bethel m:licensed_ccnh_beds=161 m:room_rate_semi_private_2_beds=430 m:room_rate_private_1_bed=470
```

## Meta Commands

```ls
metric m:licensed_ccnh_beds p:integer l:"Licensed CCNH Beds" t:dataTypeName=number

metric m:room_rate_private_1_bed p:double l:"Room Rate: PRIVATE (1 BED)" t:dataTypeName=money

metric m:room_rate_semi_private_2_beds p:double l:"Room Rate: SEMI-PRIVATE (2 BEDS)" t:dataTypeName=money

entity e:dj6a-6mcc l:"Nursing Facility Private Pay Rates" t:url=https://data.ct.gov/api/views/dj6a-6mcc

property e:dj6a-6mcc t:meta.view v:id=dj6a-6mcc v:category="Health and Human Services" v:averageRating=0 v:name="Nursing Facility Private Pay Rates"

property e:dj6a-6mcc t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:dj6a-6mcc t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| :updated_at | level_of_care | facility_name                     | town       | licensed_ccnh_beds | room_rate_private_1_bed | room_rate_semi_private_2_beds | year | 
| =========== | ============= | ================================= | ========== | ================== | ======================= | ============================= | ==== | 
| 1430729155  | CCNH          | Apple Rehab Avon                  | Avon       | 60                 | 424.00                  | 410.00                        | 2014 | 
| 1430729155  | CCNH          | Avon Health Center                | Avon       | 120                | 425.00                  | 407.00                        | 2014 | 
| 1430729155  | CCNH          | Bethel Health Care Center         | Bethel     | 161                | 470.00                  | 430.00                        | 2014 | 
| 1430729155  | CCNH          | Alexandria Manor                  | Bloomfield | 120                | 390.00                  | 370.00                        | 2014 | 
| 1430729155  | CCNH          | Vernon Manor Health Care Center   | Vernon     | 120                | 403.00                  | 373.00                        | 2014 | 
| 1430729155  | CCNH          | Bloomfield Health Care Center     | Bloomfield | 120                | 404.00                  | 375.00                        | 2014 | 
| 1430729155  | CCNH          | Caleb Hitchcock Health Center     | Bloomfield | 60                 | 445.00                  |                               | 2014 | 
| 1430729155  | CCNH          | Seabury Health Center             | Bloomfield | 60                 | 435.00                  | 435.00                        | 2014 | 
| 1430729155  | CCNH          | Touchpoints at Bloomfield         | Bloomfield | 150                | 534.00                  | 479.00                        | 2014 | 
| 1430729155  | CCNH          | Branford Hills Health Care Center | Branford   | 190                | 425.00                  | 390.00                        | 2014 | 
```