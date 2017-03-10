# State Drug Utilization Data 1991

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-1991) |
| Metadata | [Link](https://data.medicaid.gov/api/views/cnf4-jwwr) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/cnf4-jwwr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/cnf4-jwwr/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | cnf4-jwwr |
| Name | State Drug Utilization Data 1991 |
| Attribution | Centers for Medicare and Medicaid Services |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T17:19:41Z |
| Publication Date | 2016-09-16T17:55:53Z |
| Rows Updated | 2017-02-03T05:11:07Z |

## Description

Drug utilization data are reported by states for covered outpatient drugs that are paid for by state Medicaid agencies since the start of the Medicaid Drug Rebate Program. The data includes state, drug name, National Drug Code, number of prescriptions and dollars reimbursed.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:cnf4-jwwr l:"State Drug Utilization Data 1991" t:attribution="Centers for Medicare and Medicaid Services" t:url=https://data.medicaid.gov/api/views/cnf4-jwwr

property e:cnf4-jwwr t:meta.view d:2017-03-10T16:08:23.128Z v:id=cnf4-jwwr v:category="State Drug Utilization" v:attributionLink=http://www.medicaid.gov/Medicaid-CHIP-Program-Information/By-Topics/Benefits/Prescription-Drugs/Drug-Utilization-Review.html v:averageRating=0 v:name="State Drug Utilization Data 1991" v:attribution="Centers for Medicare and Medicaid Services"

property e:cnf4-jwwr t:meta.view.owner d:2017-03-10T16:08:23.128Z v:id=e4sc-6x5y v:profileImageUrlMedium=/api/users/e4sc-6x5y/profile_images/THUMB v:profileImageUrlLarge=/api/users/e4sc-6x5y/profile_images/LARGE v:screenName="Daniella Kuttner" v:profileImageUrlSmall=/api/users/e4sc-6x5y/profile_images/TINY v:displayName="Daniella Kuttner"

property e:cnf4-jwwr t:meta.view.tableauthor d:2017-03-10T16:08:23.128Z v:id=e4sc-6x5y v:profileImageUrlMedium=/api/users/e4sc-6x5y/profile_images/THUMB v:profileImageUrlLarge=/api/users/e4sc-6x5y/profile_images/LARGE v:screenName="Daniella Kuttner" v:profileImageUrlSmall=/api/users/e4sc-6x5y/profile_images/TINY v:displayName="Daniella Kuttner"

property e:cnf4-jwwr t:meta.view.metadata.custom_fields.common_core d:2017-03-10T16:08:23.128Z v:Bureau_Code=009:00 v:Program_Code=009:076
```