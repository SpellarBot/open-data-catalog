# Holocaust Claims Processing Office Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/holocaust-claims-processing-office-statistics) |
| Metadata | [Link](https://data.ny.gov/api/views/ie3e-p84t) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ie3e-p84t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ie3e-p84t/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ie3e-p84t |
| Name | Holocaust Claims Processing Office Statistics |
| Attribution | New York State Department of Financial Services |
| Category | Government & Finance |
| Tags | holocaust, nazi, compensation, restitution |
| Created | 2013-03-04T16:05:21Z |
| Publication Date | 2016-02-22T23:02:20Z |

## Description

The Holocaust Claims Processing Office (?HCPO?) was established in 1997 to provide institutional assistance to individuals seeking to recover assets lost due to Nazi persecution. Claimants pay no fee for the HCPO?s services, nor does the HCPO take a percentage of the value of the assets recovered.   The mission of the HCPO is threefold: (1) recover assets deposited in banks; (2) recover proceeds of unpaid insurance policies; and, (3) recover art lost, looted, or sold under duress between 1933 and 1945.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | claim_description        | Claim Description        | text      | text        |
| Yes      | series tag  | claims_amounts_or_counts | Claims Amounts or Counts | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ie3e-p84t d:2016-02-22T15:01:47.000Z t:claims_amounts_or_counts="46 and DC" t:claim_description="Total Number of States Where Claimants Reside" m:row_number.ie3e-p84t=1

series e:ie3e-p84t d:2016-02-22T15:01:47.000Z t:claims_amounts_or_counts=40 t:claim_description="Total Number of Countries Where Claimants Reside" m:row_number.ie3e-p84t=2

series e:ie3e-p84t d:2016-02-22T15:01:47.000Z t:claims_amounts_or_counts=12,534 t:claim_description="Total Number of Claims Resolved" m:row_number.ie3e-p84t=3
```

## Meta Commands

```ls
metric m:row_number.ie3e-p84t p:long l:"Row Number"

entity e:ie3e-p84t l:"Holocaust Claims Processing Office Statistics" t:attribution="New York State Department of Financial Services" t:url=https://data.ny.gov/api/views/ie3e-p84t

property e:ie3e-p84t t:meta.view v:id=ie3e-p84t v:category="Government & Finance" v:attributionLink=http://www.dfs.ny.gov/reportpub/hcporeport12.pdf v:averageRating=0 v:name="Holocaust Claims Processing Office Statistics" v:attribution="New York State Department of Financial Services"

property e:ie3e-p84t t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ie3e-p84t t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ie3e-p84t t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | claim_description                                        | claims_amounts_or_counts | 
| =========== | ======================================================== | ======================== | 
| 1456153307  | Total Number of States Where Claimants Reside            | 46 and DC                | 
| 1456153307  | Total Number of Countries Where Claimants Reside         | 40                       | 
| 1456153307  | Total Number of Claims Resolved                          | 12,534                   | 
| 1456153307  | Total Amount Offered to HCPO Claimants                   | $173,551,122             | 
| 1456153307  | Number of Claimants with Bank Claims                     | 2507                     | 
| 1456153307  | Number of States Where Bank Claimants Reside             | 42 and DC                | 
| 1456153307  | Number of Countries Where Bank Claimants Reside          | 38                       | 
| 1456153307  | Number of Account Holders Referenced                     | 3868                     | 
| 1456153307  | Number of Bank Claims Resolved                           | 5082                     | 
| 1456153307  | Total Amount Offered to HCPO Claimants for Bank Accounts | $78,703,317              | 
```