# State Drug Utilization Data 1991

## Dataset

* [Dataset URL](https://data.medicaid.gov/api/views/cnf4-jwwr/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/state-drug-utilization-data-1991)
* [Metadata URL](https://data.medicaid.gov/api/views/cnf4-jwwr)
* Id = cnf4-jwwr
* Name = State Drug Utilization Data 1991
* Attribution = Centers for Medicare and Medicaid Services
* [Attribution Link](http://www.medicaid.gov/Medicaid-CHIP-Program-Information/By-Topics/Benefits/Prescription-Drugs/Drug-Utilization-Review.html)
* Category = State Drug Utilization
* Tags = [drug utilization, medicaid reimbursements, pharmacy]
* Created = 2015-06-11T17:19:41Z
* Publication Date = 2016-09-16T17:55:53Z
* Rows Updated = 2017-02-03T05:11:07Z

## Description

Drug utilization data are reported by states for covered outpatient drugs that are paid for by state Medicaid agencies since the start of the Medicaid Drug Rebate Program. The data includes state, drug name, National Drug Code, number of prescriptions and dollars reimbursed.

## Columns

```ls
| Name       | Field Name  | Data Type | Render Type | Schema Type | Included | 
| ========== | =========== | ========= | =========== | =========== | ======== | 
| updated_at | :updated_at | meta_data | meta_data   | time        | No       | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:cnf4-jwwr l:"State Drug Utilization Data 1991" t:attribution="Centers for Medicare and Medicaid Services" t:url=https://data.medicaid.gov/api/views/cnf4-jwwr

property e:cnf4-jwwr t:meta.view d:2017-03-07T16:12:34.021Z v:id=cnf4-jwwr v:category="State Drug Utilization" v:attributionLink=http://www.medicaid.gov/Medicaid-CHIP-Program-Information/By-Topics/Benefits/Prescription-Drugs/Drug-Utilization-Review.html v:averageRating=0 v:name="State Drug Utilization Data 1991" v:attribution="Centers for Medicare and Medicaid Services"

property e:cnf4-jwwr t:meta.view.owner d:2017-03-07T16:12:34.021Z v:id=e4sc-6x5y v:profileImageUrlMedium=/api/users/e4sc-6x5y/profile_images/THUMB v:profileImageUrlLarge=/api/users/e4sc-6x5y/profile_images/LARGE v:screenName="Daniella Kuttner" v:profileImageUrlSmall=/api/users/e4sc-6x5y/profile_images/TINY v:displayName="Daniella Kuttner"

property e:cnf4-jwwr t:meta.view.tableauthor d:2017-03-07T16:12:34.021Z v:id=e4sc-6x5y v:profileImageUrlMedium=/api/users/e4sc-6x5y/profile_images/THUMB v:profileImageUrlLarge=/api/users/e4sc-6x5y/profile_images/LARGE v:screenName="Daniella Kuttner" v:profileImageUrlSmall=/api/users/e4sc-6x5y/profile_images/TINY v:displayName="Daniella Kuttner"

property e:cnf4-jwwr t:meta.view.metadata.custom_fields.common_core d:2017-03-07T16:12:34.021Z v:Bureau_Code=009:00 v:Program_Code=009:076
```