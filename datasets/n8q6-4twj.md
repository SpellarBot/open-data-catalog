# Calendar Year 2015 & 2016 Master Contract Sales Data by Customer, Contract, Vendor

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/calendar-year-2015-2016-master-contract-sales-data-by-customer-contract-vendor) |
| Metadata | [Link](https://data.wa.gov/api/views/n8q6-4twj) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/n8q6-4twj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/n8q6-4twj/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | n8q6-4twj |
| Name | Calendar Year 2015 & 2016 Master Contract Sales Data by Customer, Contract, Vendor |
| Category | Procurements and Contracts |
| Tags | master contracts, contracts, procurement, spend, vendor |
| Created | 2016-07-18T21:31:37Z |
| Publication Date | 2016-11-23T01:54:49Z |

## Description

DES is publishing Master Contract spend as data becomes available. The spend is reported by vendors and is reported by contract and customer. Includes OMWBE, Vet and Small Business status as well.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | customer_type     | Customer Type     | text      | text        |
| Yes      | series tag     | customer_name     | Customer Name     | text      | text        |
| Yes      | series tag     | contract_number   | Contract Number   | text      | text        |
| Yes      | series tag     | contract_title    | Contract Title    | text      | text        |
| Yes      | series tag     | vendor_name       | Vendor Name       | text      | text        |
| Yes      | time           | year              | Year              | number    | text        |
| Yes      | numeric metric | q1_sales_reported | Q1 Sales Reported | money     | money       |
| Yes      | numeric metric | q2_sales_reported | Q2 Sales Reported | money     | money       |
| Yes      | numeric metric | q3_sales_reported | Q3 Sales Reported | money     | money       |
| Yes      | numeric metric | q4_sales_reported | Q4 Sales Reported | money     | money       |
| Yes      | series tag     | omwbe             | OMWBE             | text      | text        |
| Yes      | series tag     | vet_owned         | Vet Owned         | text      | text        |
| Yes      | series tag     | small_business    | Small Business    | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:n8q6-4twj d:2016-01-01T00:00:00.000Z t:vet_owned=N t:small_business=N t:customer_name="ACCOUNTANCY STATE BOARD OF" t:contract_number=04411 t:contract_title="Office Supplies & Paper" t:vendor_name="OFFICE DEPOT BUSINESS SOLUTIONS DIVISION" t:customer_type=AGY m:q1_sales_reported=0 m:q2_sales_reported=0 m:q4_sales_reported=0 m:q3_sales_reported=15

series e:n8q6-4twj d:2016-01-01T00:00:00.000Z t:vet_owned=N t:small_business=N t:customer_name="ACCOUNTANCY STATE BOARD OF" t:contract_number=03706 t:contract_title="Active for MFD Reports ONLY" t:vendor_name="SHARP ELECTRONICS CORPORATION" t:customer_type=AGY m:q1_sales_reported=908 m:q2_sales_reported=967 m:q4_sales_reported=0 m:q3_sales_reported=1026

series e:n8q6-4twj d:2016-01-01T00:00:00.000Z t:vet_owned=N t:small_business=N t:customer_name="ACCOUNTANCY STATE BOARD OF" t:contract_number=01913 t:contract_title="Travel Services, Agent Assisted & Internet" t:vendor_name="CLASSIC TRAVEL, INC." t:customer_type=AGY m:q1_sales_reported=155 m:q2_sales_reported=210 m:q4_sales_reported=0 m:q3_sales_reported=245
```

## Meta Commands

```ls
metric m:q1_sales_reported p:double l:"Q1 Sales Reported" t:dataTypeName=money

metric m:q2_sales_reported p:double l:"Q2 Sales Reported" t:dataTypeName=money

metric m:q3_sales_reported p:double l:"Q3 Sales Reported" t:dataTypeName=money

metric m:q4_sales_reported p:double l:"Q4 Sales Reported" t:dataTypeName=money

entity e:n8q6-4twj l:"Calendar Year 2015 & 2016 Master Contract Sales Data by Customer, Contract, Vendor" t:url=https://data.wa.gov/api/views/n8q6-4twj

property e:n8q6-4twj t:meta.view v:id=n8q6-4twj v:category="Procurements and Contracts" v:averageRating=0 v:name="Calendar Year 2015 & 2016 Master Contract Sales Data by Customer, Contract, Vendor"

property e:n8q6-4twj t:meta.view.owner v:id=vrr3-nct2 v:profileImageUrlMedium=/api/users/vrr3-nct2/profile_images/THUMB v:profileImageUrlLarge=/api/users/vrr3-nct2/profile_images/LARGE v:screenName="DES-Rebecca Linville" v:profileImageUrlSmall=/api/users/vrr3-nct2/profile_images/TINY v:displayName="DES-Rebecca Linville"

property e:n8q6-4twj t:meta.view.tableauthor v:id=vrr3-nct2 v:profileImageUrlMedium=/api/users/vrr3-nct2/profile_images/THUMB v:profileImageUrlLarge=/api/users/vrr3-nct2/profile_images/LARGE v:screenName="DES-Rebecca Linville" v:profileImageUrlSmall=/api/users/vrr3-nct2/profile_images/TINY v:roleName=publisher v:displayName="DES-Rebecca Linville"
```

## Top Records

```ls
| customer_type | customer_name              | contract_number | contract_title                               | vendor_name                              | year | q1_sales_reported | q2_sales_reported | q3_sales_reported | q4_sales_reported | omwbe | vet_owned | small_business | 
| ============= | ========================== | =============== | ============================================ | ======================================== | ==== | ================= | ================= | ================= | ================= | ===== | ========= | ============== | 
| AGY           | ACCOUNTANCY STATE BOARD OF | 04411           | Office Supplies & Paper                      | OFFICE DEPOT BUSINESS SOLUTIONS DIVISION | 2016 | 0.0               | 0.0               | 15                | 0.0               |       | N         | N              | 
| AGY           | ACCOUNTANCY STATE BOARD OF | 03706           | Active for MFD Reports ONLY                  | SHARP ELECTRONICS CORPORATION            | 2016 | 908               | 967               | 1026              | 0.0               |       | N         | N              | 
| AGY           | ACCOUNTANCY STATE BOARD OF | 01913           | Travel Services, Agent Assisted & Internet   | CLASSIC TRAVEL, INC.                     | 2016 | 155               | 210               | 245               | 0.0               |       | N         | N              | 
| AGY           | ACCOUNTANCY STATE BOARD OF | 06012           | WSCA-NASPO Mobile Phones                     | VERIZON WIRELESS                         | 2016 | 120               | 342               | 270               | 0.0               |       | N         | N              | 
| AGY           | ACCOUNTANCY STATE BOARD OF | 08215           | Information Technology Professional Services | EVE CORP.                                | 2016 | 0.0               | 1700              | 1318              | 0.0               |       | N         | Y              | 
| AGY           | ACCOUNTANCY STATE BOARD OF | 07412           | Onsite Document Destruction Services         | HAROLD LEMAY ENTERPRIZES                 | 2016 | 14                | 9                 | 382               | 0.0               |       | N         | N              | 
| AGY           | ACCOUNTANCY STATE BOARD OF | 00612           | Commercial Card Solutions                    | U.S. BANCORP                             | 2016 | 4336              | 9586              | 7005              | 0.0               |       | N         | N              | 
| AGY           | ACCOUNTANCY STATE BOARD OF | 01114           | NASPO Data Communications                    | HEWLETT PACKARD                          | 2016 | 1131              | 0.0               | 0.0               | 0.0               |       | N         | N              | 
| AGY           | ACCOUNTANCY STATE BOARD OF | 07114           | Cisco - Data Communications (T12-MST-642)    | CISCO SYSTEMS, INC.                      | 2016 | 2389              | 0.0               | 0.0               | 0.0               |       | Y         | N              | 
| AGY           | ACCOUNTANCY STATE BOARD OF | 00612           | Commercial Card Solutions                    | U.S. BANCORP                             | 2015 | 9475              | 21354             | 9344              | 3501              |       | N         | N              | 
```