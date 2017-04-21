# Master Contract Value Added Resellers (VAR) Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/master-contract-value-added-resellers-var-report) |
| Metadata | [Link](https://data.ny.gov/api/views/cjqa-a3p4) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cjqa-a3p4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cjqa-a3p4/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cjqa-a3p4 |
| Name | Master Contract Value Added Resellers (VAR) Report |
| Attribution | New York State Office of General Services (OGS) |
| Category | Government & Finance |
| Tags | master contracts, resellers, vars |
| Created | 2015-03-24T13:39:37Z |
| Publication Date | 2017-02-01T23:13:50Z |

## Description

A listing of New York State Master contracts by vendors and associated resellers, provided by NYS Office of General Services (OGS).  The information in the dataset represents the Master contracts used by State agencies and other authorized users, and the value-added resellers associated with the Master Contract.  The information allows State agencies to see the Master Contracts and the associated resellers for payment and informational purposes.

## Columns

```ls
| Included | Schema Type | Field Name                            | Name                                    | Data Type | Render Type |
| ======== | =========== | ===================================== | ======================================= | ========= | =========== |
| No       | time        | :updated_at                           | updated_at                              | meta_data | meta_data   |
| Yes      | series tag  | master_contract_vendor_id             | Master Contract/Vendor ID #             | text      | text        |
| Yes      | series tag  | master_contract_vendor_name           | Master Contract Vendor Name             | text      | text        |
| Yes      | series tag  | master_contract_id                    | Master Contract ID #                    | text      | text        |
| Yes      | series tag  | contract_description                  | Contract Description                    | text      | text        |
| Yes      | series tag  | value_added_re_seller_var_id          | Value-Added Re-seller (VAR) ID #        | text      | text        |
| Yes      | series tag  | value_added_re_seller_var_vendor_name | Value-Added Re-seller (VAR) Vendor Name | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cjqa-a3p4 d:2017-02-01T23:13:38.000Z t:contract_description="TIRES (NEW) AND RELATED SERVIC" t:master_contract_id=OGS01-PC64867-1140268 t:master_contract_vendor_name="THE GOODYEAR TIRE & RUBBER COMPANY" t:master_contract_vendor_id=600000037 t:value_added_re_seller_var_id=1000009115 t:value_added_re_seller_var_vendor_name="THE GOODYEAR TIRE & RUBBER COMPANY" m:row_number.cjqa-a3p4=1

series e:cjqa-a3p4 d:2017-02-01T23:13:38.000Z t:contract_description="Mailing Machines, Scales, Folders, Inserters, Meter Rental and Other Items (Statewide)" t:master_contract_id=OGS01-PC65205-1140268 t:master_contract_vendor_name="PITNEY BOWES INC" t:master_contract_vendor_id=1000000122 t:value_added_re_seller_var_id=1000009724 t:value_added_re_seller_var_vendor_name="THE PITNEY BOWES BANK INC" m:row_number.cjqa-a3p4=2

series e:cjqa-a3p4 d:2017-02-01T23:13:38.000Z t:contract_description="ENTERPRISE SYSTEMS" t:master_contract_id=0000000000000000000011418 t:master_contract_vendor_name="INTERNATIONAL BUSINESS MACHINE" t:master_contract_vendor_id=1000001053 t:value_added_re_seller_var_id=1000044525 t:value_added_re_seller_var_vendor_name="ESYSTEMS INC" m:row_number.cjqa-a3p4=3
```

## Meta Commands

```ls
metric m:row_number.cjqa-a3p4 p:long l:"Row Number"

entity e:cjqa-a3p4 l:"Master Contract Value Added Resellers (VAR) Report" t:attribution="New York State Office of General Services (OGS)" t:url=https://data.ny.gov/api/views/cjqa-a3p4

property e:cjqa-a3p4 t:meta.view v:id=cjqa-a3p4 v:category="Government & Finance" v:attributionLink=http://ogs.ny.gov/BU/PC/ v:averageRating=0 v:name="Master Contract Value Added Resellers (VAR) Report" v:attribution="New York State Office of General Services (OGS)"

property e:cjqa-a3p4 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cjqa-a3p4 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cjqa-a3p4 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | master_contract_vendor_id | master_contract_vendor_name        | master_contract_id        | contract_description                                                                   | value_added_re_seller_var_id | value_added_re_seller_var_vendor_name | 
| =========== | ========================= | ================================== | ========================= | ====================================================================================== | ============================ | ===================================== | 
| 1485990818  | 600000037                 | THE GOODYEAR TIRE & RUBBER COMPANY | OGS01-PC64867-1140268     | TIRES (NEW) AND RELATED SERVIC                                                         | 1000009115                   | THE GOODYEAR TIRE & RUBBER COMPANY    | 
| 1485990818  | 1000000122                | PITNEY BOWES INC                   | OGS01-PC65205-1140268     | Mailing Machines, Scales, Folders, Inserters, Meter Rental and Other Items (Statewide) | 1000009724                   | THE PITNEY BOWES BANK INC             | 
| 1485990818  | 1000001053                | INTERNATIONAL BUSINESS MACHINE     | 0000000000000000000011418 | ENTERPRISE SYSTEMS                                                                     | 1000044525                   | ESYSTEMS INC                          | 
| 1485990818  | 1000001053                | INTERNATIONAL BUSINESS MACHINE     | 0000000000000000000011418 | ENTERPRISE SYSTEMS                                                                     | 1000044525                   | ESYSTEMS INC                          | 
| 1485990818  | 1000001053                | INTERNATIONAL BUSINESS MACHINE     | 0000000000000000000011418 | ENTERPRISE SYSTEMS                                                                     | 1100174292                   | GEMKO INFORMATION GROUP               | 
| 1485990818  | 1000001053                | INTERNATIONAL BUSINESS MACHINE     | 0000000000000000000011418 | ENTERPRISE SYSTEMS                                                                     | 1100174292                   | GEMKO INFORMATION GROUP               | 
| 1485990818  | 1000001053                | INTERNATIONAL BUSINESS MACHINE     | 0000000000000000000011418 | ENTERPRISE SYSTEMS                                                                     | 1000036235                   | LIGHTHOUSE COMPUTER SERVICES INC      | 
| 1485990818  | 1000001053                | INTERNATIONAL BUSINESS MACHINE     | 0000000000000000000011418 | ENTERPRISE SYSTEMS                                                                     | 1000036235                   | LIGHTHOUSE COMPUTER SERVICES INC      | 
| 1485990818  | 1000001053                | INTERNATIONAL BUSINESS MACHINE     | 0000000000000000000011418 | ENTERPRISE SYSTEMS                                                                     | 1100152815                   | LPA SOFTWARE SOLUTIONS LLC            | 
| 1485990818  | 1000001053                | INTERNATIONAL BUSINESS MACHINE     | 0000000000000000000011418 | ENTERPRISE SYSTEMS                                                                     | 1100152815                   | LPA SOFTWARE SOLUTIONS LLC            | 
```