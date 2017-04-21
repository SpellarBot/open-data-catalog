# Table 4: FY2015 Value-Based Incentive Payment Amount

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-4-fy2014-value-based-incentive-payment-amount) |
| Metadata | [Link](https://data.medicare.gov/api/views/vtqa-m4zn) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/vtqa-m4zn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/vtqa-m4zn/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | vtqa-m4zn |
| Name | Table 4: FY2015 Value-Based Incentive Payment Amount |
| Category | Hospital Compare |
| Tags | hospital, linking quality to payment |
| Created | 2014-07-21T16:53:44Z |
| Publication Date | 2016-12-19T02:15:42Z |

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| Yes      | series tag     | incentive_payment_range                  | Incentive Payment Range                  | text      | text        |
| Yes      | numeric metric | number_of_hospitals_receiving_this_range | Number of Hospitals Receiving this Range | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vtqa-m4zn d:2015-01-01T00:00:00.000Z t:incentive_payment_range=>$1,000,000 m:number_of_hospitals_receiving_this_range=314

series e:vtqa-m4zn d:2015-01-01T00:00:00.000Z t:incentive_payment_range="$950,001 to $1,000,000" m:number_of_hospitals_receiving_this_range=30

series e:vtqa-m4zn d:2015-01-01T00:00:00.000Z t:incentive_payment_range="$900,001 to $950,000" m:number_of_hospitals_receiving_this_range=23
```

## Meta Commands

```ls
metric m:number_of_hospitals_receiving_this_range p:integer l:"Number of Hospitals Receiving this Range" t:dataTypeName=number

entity e:vtqa-m4zn l:"Table 4: FY2015 Value-Based Incentive Payment Amount" t:url=https://data.medicare.gov/api/views/vtqa-m4zn

property e:vtqa-m4zn t:meta.view v:id=vtqa-m4zn v:category="Hospital Compare" v:averageRating=0 v:name="Table 4: FY2015 Value-Based Incentive Payment Amount"

property e:vtqa-m4zn t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:vtqa-m4zn t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:vtqa-m4zn t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| incentive_payment_range | number_of_hospitals_receiving_this_range | 
| ======================= | ======================================== | 
| >$1,000,000             | 314                                      | 
| $950,001 to $1,000,000  | 30                                       | 
| $900,001 to $950,000    | 23                                       | 
| $850,001 to $900,000    | 35                                       | 
| $800,001 to $850,000    | 44                                       | 
| $750,001 to $800,000    | 43                                       | 
| $700,001 to $750,000    | 56                                       | 
| $650,001 to $700,000    | 61                                       | 
| $600,001 to $650,000    | 72                                       | 
| $550,001 to $600,000    | 81                                       | 
```