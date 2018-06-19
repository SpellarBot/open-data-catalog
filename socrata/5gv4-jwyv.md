# Table 1: Net Change in Base Operating DRG Payment Amount

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-1-net-change-in-base-operating-drg-payment-amount-438b9) |
| Metadata | [Link](https://data.medicare.gov/api/views/5gv4-jwyv) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/5gv4-jwyv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/5gv4-jwyv/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | 5gv4-jwyv |
| Name | Table 1: Net Change in Base Operating DRG Payment Amount |
| Category | Hospital Compare |
| Tags | hospital, linking quality to payment |
| Created | 2014-07-21T16:48:17Z |
| Publication Date | 2016-12-19T02:15:36Z |

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                            | Data Type | Render Type |
| ======== | ============== | ======================================== | =============================================== | ========= | =========== |
| No       | time           | :updated_at                              | updated_at                                      | meta_data | meta_data   |
| Yes      | series tag     | incentive_payment_range                  | Net Change in Base Operating DRG Payment Amount | text      | text        |
| Yes      | numeric metric | number_of_hospitals_receiving_this_range | Number of Hospitals Receiving this Range        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5gv4-jwyv d:2016-11-16T22:35:17.000Z t:incentive_payment_range=>$150,000 m:number_of_hospitals_receiving_this_range=216

series e:5gv4-jwyv d:2016-11-16T22:35:17.000Z t:incentive_payment_range="$140,001 to $150,000" m:number_of_hospitals_receiving_this_range=17

series e:5gv4-jwyv d:2016-11-16T22:35:17.000Z t:incentive_payment_range="$130,001 to $140,000" m:number_of_hospitals_receiving_this_range=39
```

## Meta Commands

```ls
metric m:number_of_hospitals_receiving_this_range p:integer l:"Number of Hospitals Receiving this Range" t:dataTypeName=number

entity e:5gv4-jwyv l:"Table 1: Net Change in Base Operating DRG Payment Amount" t:url=https://data.medicare.gov/api/views/5gv4-jwyv

property e:5gv4-jwyv t:meta.view v:id=5gv4-jwyv v:category="Hospital Compare" v:averageRating=0 v:name="Table 1: Net Change in Base Operating DRG Payment Amount"

property e:5gv4-jwyv t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:5gv4-jwyv t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:5gv4-jwyv t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | incentive_payment_range | number_of_hospitals_receiving_this_range | 
| =========== | ======================= | ======================================== | 
| 1479335717  | >$150,000               | 216                                      | 
| 1479335717  | $140,001 to $150,000    | 17                                       | 
| 1479335717  | $130,001 to $140,000    | 39                                       | 
| 1479335717  | $120,001 to $130,000    | 28                                       | 
| 1479335717  | $110,001 to $120,000    | 32                                       | 
| 1479335717  | $100,001 to $110,000    | 36                                       | 
| 1479335717  | $90,001 to $100,000     | 42                                       | 
| 1479335717  | $80,001 to $90,000      | 61                                       | 
| 1479335717  | $70,001 to $80,000      | 64                                       | 
| 1479335717  | $60,001 to $70,000      | 74                                       | 
```