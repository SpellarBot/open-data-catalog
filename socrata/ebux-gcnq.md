# Inventory of citywide enterprise systems of record

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inventory-of-citywide-enterprise-systems-of-record) |
| Metadata | [Link](https://data.sfgov.org/api/views/ebux-gcnq) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ebux-gcnq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ebux-gcnq/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ebux-gcnq |
| Name | Inventory of citywide enterprise systems of record |
| Category | City Management and Ethics |
| Tags | inventory, open data, systems, gov code 6270.5, sb 272, sb272 |
| Created | 2016-07-01T17:45:23Z |
| Publication Date | 2016-07-07T22:40:45Z |

## Description

In compliance with CA Government Code 6270.5 (passed via SB 272), the City must publish a catalog of enterprise systems that collect data about the public. There are certain exceptions to this detailed in the Government Code. The code is available here: http://bit.ly/CAinventory

## Columns

```ls
| Included | Schema Type | Field Name               | Name                                                       | Data Type | Render Type |
| ======== | =========== | ======================== | ========================================================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at                                                 | meta_data | meta_data   |
| Yes      | series tag  | department_custodian     | Department Custodian                                       | text      | text        |
| Yes      | series tag  | data_system_name         | Department Name of Data System                             | text      | text        |
| Yes      | series tag  | purpose                  | Brief statement of purpose and general description of data | text      | text        |
| Yes      | series tag  | vendor                   | Vendor                                                     | text      | text        |
| Yes      | series tag  | product                  | Product                                                    | text      | text        |
| Yes      | series tag  | frequency_data_collected | Frequency Data Collected                                   | text      | text        |
| Yes      | series tag  | frequency_data_updated   | Frequency Data Updated                                     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ebux-gcnq d:2016-07-07T15:38:25.000Z t:product="MS Excel" t:data_system_name="PRCS Warrant Spreadsheet" t:vendor=Microsoft t:frequency_data_updated=Bi-Weekly t:purpose="Excel file created and maintained by APD to track warrants issued to PRCS clients." t:department_custodian="Adult Probation" t:frequency_data_collected=Continuous m:row_number.ebux-gcnq=1

series e:ebux-gcnq d:2016-07-07T15:38:25.000Z t:product=COTS t:data_system_name=COMPAS t:vendor="northpointe, Inc." t:frequency_data_updated=Continuous t:purpose="Risk and need assessment software." t:department_custodian="Adult Probation" t:frequency_data_collected=Continuous m:row_number.ebux-gcnq=2

series e:ebux-gcnq d:2016-07-07T15:38:25.000Z t:product=COTS t:data_system_name="Ankle Bracelet Monitoring" t:vendor="Leaders in Community Alternatives" t:frequency_data_updated=Continuous t:purpose="Vendor-provided system used to track movement of clients on Electronic Monitoring." t:department_custodian="Adult Probation" t:frequency_data_collected=Continuous m:row_number.ebux-gcnq=3
```

## Meta Commands

```ls
metric m:row_number.ebux-gcnq p:long l:"Row Number"

entity e:ebux-gcnq l:"Inventory of citywide enterprise systems of record" t:url=https://data.sfgov.org/api/views/ebux-gcnq

property e:ebux-gcnq t:meta.view v:id=ebux-gcnq v:category="City Management and Ethics" v:averageRating=0 v:name="Inventory of citywide enterprise systems of record"

property e:ebux-gcnq t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ebux-gcnq t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:ebux-gcnq t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | department_custodian | data_system_name            | purpose                                                                            | vendor                            | product   | frequency_data_collected | frequency_data_updated | 
| =========== | ==================== | =========================== | ================================================================================== | ================================= | ========= | ======================== | ====================== | 
| 1467905905  | Adult Probation      | PRCS Warrant Spreadsheet    | Excel file created and maintained by APD to track warrants issued to PRCS clients. | Microsoft                         | MS Excel  | Continuous               | Bi-Weekly              | 
| 1467905905  | Adult Probation      | COMPAS                      | Risk and need assessment software.                                                 | northpointe, Inc.                 | COTS      | Continuous               | Continuous             | 
| 1467905905  | Adult Probation      | Ankle Bracelet Monitoring   | Vendor-provided system used to track movement of clients on Electronic Monitoring. | Leaders in Community Alternatives | COTS      | Continuous               | Continuous             | 
| 1467905905  | Adult Probation      | PRCS Spreadsheet            | Post Release Community Supervision data                                            | Microsoft                         | MS Excel  | Continuous               | Monthly                | 
| 1467905905  | Adult Probation      | 1170h Spreadsheet           | 1170h Mandatory Supervision data                                                   | Microsoft                         | MS Excel  | Continuous               | Monthly                | 
| 1467905905  | Adult Probation      | PRCS Violation Spreadsheet  | PRCS client data.                                                                  | Microsoft                         | MS Excel  | Continuous               | Monthly                | 
| 1467905905  | Adult Probation      | 1170h Re-arrest spreadsheet | Rearrest data                                                                      | Microsoft                         | MS Excel  | Continuous               | Monthly                | 
| 1467905905  | Adult Probation      | PSI Assgnments              | Pre-Sentence Investigations data                                                   | Microsoft                         | MS Excel  | Continuous               | Monthly                | 
| 1467905905  | Adult Probation      | Referral spreadsheet        | Referrals to APD-funded service providers data                                     | Microsoft                         | MS Excel  | Continuous               | Monthly                | 
| 1467905905  | Adult Probation      | LCA Database                | Referral to the Community Assessment and Services Center data                      | Microsoft                         | MS Access | Continuous               | Monthly                | 
```