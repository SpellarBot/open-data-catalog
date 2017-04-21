# Table 2: FY2015 Distribution of Net Change in Base Operating DRG Payment Amount

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-2-fy2014-distribution-of-net-change-in-base-operating-drg-payment-amount) |
| Metadata | [Link](https://data.medicare.gov/api/views/xrgf-x36b) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/xrgf-x36b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/xrgf-x36b/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | xrgf-x36b |
| Name | Table 2: FY2015 Distribution of Net Change in Base Operating DRG Payment Amount |
| Category | Hospital Compare |
| Tags | hospital, linking quality to payment |
| Created | 2014-07-21T16:55:44Z |
| Publication Date | 2016-12-19T02:15:38Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                                            | Data Type | Render Type |
| ======== | ============== | ================= | =============================================== | ========= | =========== |
| Yes      | series tag     | percentile        | Percentile                                      | text      | text        |
| Yes      | numeric metric | incentive_payment | Net Change in Base Operating DRG Payment Amount | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xrgf-x36b d:2015-01-01T00:00:00.000Z t:percentile=Max m:incentive_payment=1750062

series e:xrgf-x36b d:2015-01-01T00:00:00.000Z t:percentile=95th m:incentive_payment=192076

series e:xrgf-x36b d:2015-01-01T00:00:00.000Z t:percentile=90th m:incentive_payment=118285
```

## Meta Commands

```ls
metric m:incentive_payment p:integer l:"Net Change in Base Operating DRG Payment Amount" t:dataTypeName=money

entity e:xrgf-x36b l:"Table 2: FY2015 Distribution of Net Change in Base Operating DRG Payment Amount" t:url=https://data.medicare.gov/api/views/xrgf-x36b

property e:xrgf-x36b t:meta.view v:id=xrgf-x36b v:category="Hospital Compare" v:averageRating=0 v:name="Table 2: FY2015 Distribution of Net Change in Base Operating DRG Payment Amount"

property e:xrgf-x36b t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:xrgf-x36b t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:xrgf-x36b t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| percentile | incentive_payment | 
| ========== | ================= | 
| Max        | 1750062           | 
| 95th       | 192076            | 
| 90th       | 118285            | 
| 80th       | 59202             | 
| 70th       | 31211             | 
| 60th       | 15748             | 
| 50th       | 5094              | 
| 40th       | -5439             | 
| 30th       | -25583            | 
| 20th       | -61310            | 
```