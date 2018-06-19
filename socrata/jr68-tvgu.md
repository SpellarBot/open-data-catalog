# Home Health Rates Effective

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-health-rates-effective) |
| Metadata | [Link](https://data.ct.gov/api/views/jr68-tvgu) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/jr68-tvgu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/jr68-tvgu/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | jr68-tvgu |
| Name | Home Health Rates Effective |
| Category | Health and Human Services |
| Tags | opm, ltc, home health care |
| Created | 2015-05-04T16:39:43Z |
| Publication Date | 2015-05-04T16:41:15Z |

## Description

This data provides a list of home health care providers and their private pay rates for long term care services as of January 1st, 2015.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | agency                  | AGENCY                  | text      | text        |
| Yes      | series tag     | town                    | Town                    | text      | text        |
| Yes      | numeric metric | skilled_nursing_visits  | Skilled Nursing Visits  | money     | money       |
| Yes      | numeric metric | therapies_phys_visits   | Therapies Phys Visits   | money     | money       |
| Yes      | numeric metric | therapies_occup_visits  | Therapies Occup Visits  | money     | money       |
| Yes      | numeric metric | therapies_speech_visits | Therapies Speech Visits | money     | money       |
| Yes      | numeric metric | personal_care_attendant | Personal Care Attendant | money     | money       |
| Yes      | numeric metric | hha_hrs                 | HHA Hrs.                | money     | money       |
| Yes      | numeric metric | private_duty_rn_hrs     | Private Duty RN Hrs.    | money     | money       |
| Yes      | numeric metric | private_duty_lpn_hrs    | Private Duty LPN Hrs.   | money     | money       |
| Yes      | time           | year                    | Year                    | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jr68-tvgu d:2015-01-01T00:00:00.000Z t:agency="VNS, Inc. of Southern CT" t:town=Ansonia m:therapies_phys_visits=140 m:skilled_nursing_visits=140 m:hha_hrs=30 m:therapies_speech_visits=140 m:therapies_occup_visits=140

series e:jr68-tvgu d:2015-01-01T00:00:00.000Z t:agency="Help At Home, Inc." t:town=Avon m:personal_care_attendant=20

series e:jr68-tvgu d:2015-01-01T00:00:00.000Z t:agency="Tender Heart Homecare, LLC" t:town=Bantam m:personal_care_attendant=15 m:private_duty_rn_hrs=37.5 m:private_duty_lpn_hrs=30 m:hha_hrs=15
```

## Meta Commands

```ls
metric m:skilled_nursing_visits p:double l:"Skilled Nursing Visits" t:dataTypeName=money

metric m:therapies_phys_visits p:double l:"Therapies Phys Visits" t:dataTypeName=money

metric m:therapies_occup_visits p:double l:"Therapies Occup Visits" t:dataTypeName=money

metric m:therapies_speech_visits p:double l:"Therapies Speech Visits" t:dataTypeName=money

metric m:personal_care_attendant p:double l:"Personal Care Attendant" t:dataTypeName=money

metric m:hha_hrs p:double l:"HHA Hrs." t:dataTypeName=money

metric m:private_duty_rn_hrs p:double l:"Private Duty RN Hrs." t:dataTypeName=money

metric m:private_duty_lpn_hrs p:double l:"Private Duty LPN Hrs." t:dataTypeName=money

entity e:jr68-tvgu l:"Home Health Rates Effective" t:url=https://data.ct.gov/api/views/jr68-tvgu

property e:jr68-tvgu t:meta.view v:id=jr68-tvgu v:category="Health and Human Services" v:averageRating=0 v:name="Home Health Rates Effective"

property e:jr68-tvgu t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:jr68-tvgu t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| agency                              | town       | skilled_nursing_visits | therapies_phys_visits | therapies_occup_visits | therapies_speech_visits | personal_care_attendant | hha_hrs | private_duty_rn_hrs | private_duty_lpn_hrs | year | 
| =================================== | ========== | ====================== | ===================== | ====================== | ======================= | ======================= | ======= | =================== | ==================== | ==== | 
| VNS, Inc. of Southern CT            | Ansonia    | 140.00                 | 140.00                | 140.00                 | 140.00                  |                         | 30.00   |                     |                      | 2015 | 
| Help At Home, Inc.                  | Avon       |                        |                       |                        |                         | 20.00                   |         |                     |                      | 2015 | 
| Tender Heart Homecare, LLC          | Bantam     |                        |                       |                        |                         | 15.00                   | 15.00   | 37.50               | 30.00                | 2015 | 
| VNA Northwest                       | Bantam     | 145.00                 | 155.00                | 155.00                 | 155.00                  |                         | 80.00   |                     |                      | 2015 | 
| Berlin VNA                          | Berlin     | 145.00                 | 100.00                | 100.00                 | 129.00                  |                         | 35.00   |                     |                      | 2015 | 
| Euro-American Connections, LLC      | Berlin     |                        |                       |                        |                         | 20.00                   | 20.00   |                     |                      | 2015 | 
| Euro-American Homecare, LLC         | Berlin     |                        |                       |                        |                         | 22.00                   | 22.00   |                     |                      | 2015 | 
| Bethel VNA                          | Bethel     | 140.00                 | 140.00                | 140.00                 | 140.00                  |                         | 35.00   |                     |                      | 2015 | 
| Besa Companions and Homemakers      | Bloomfield |                        |                       |                        |                         | 22.00                   |         |                     |                      | 2015 | 
| Comfort Keepers of Greater Hartford | Bloomfield |                        |                       |                        |                         | 23.50                   | 23.50   |                     |                      | 2015 | 
```