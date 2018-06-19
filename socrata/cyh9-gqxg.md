# Open Checkbook Data FY16

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-checkbook-data-fy16-year-to-date) |
| Metadata | [Link](https://data.somervillema.gov/api/views/cyh9-gqxg) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/cyh9-gqxg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/cyh9-gqxg/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | cyh9-gqxg |
| Name | Open Checkbook Data FY16 |
| Attribution | City of Somerville Finance Department |
| Category | Finance |
| Tags | open checkbook, finance, fy16 |
| Created | 2016-03-10T15:01:37Z |
| Publication Date | 2016-03-10T15:03:57Z |

## Description

The City of Somerville uses this dataset to provide residents with information regarding local government spending.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | item            | Item #          | text          | number        |
| Yes      | series tag     | category_of_gov | Category of Gov | text          | text          |
| Yes      | series tag     | vendor_name     | VENDOR NAME     | text          | text          |
| Yes      | numeric metric | amount          | Amount          | number        | number        |
| Yes      | time           | check_date      | Check Date      | calendar_date | calendar_date |
| Yes      | series tag     | department      | Department      | text          | text          |
| Yes      | series tag     | check           | Check #         | text          | number        |
| Yes      | series tag     | org_description | Org Description | text          | text          |
| Yes      | series tag     | account_desc    | Account Desc    | text          | text          |
```

## Time Field

```ls
Value = check_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cyh9-gqxg d:2016-06-30T00:00:00.000Z t:account_desc="LAND ACQUISITION" t:check=602550 t:department="OSPCD ADMINISTRATION" t:item=1 t:vendor_name="15-17 BEACON STREET LLC" t:org_description="OSPCD-TRANS CAPITAL EXP" t:category_of_gov="General Government" m:amount=830

series e:cyh9-gqxg d:2016-06-30T00:00:00.000Z t:account_desc="LAND ACQUISITION" t:check=602551 t:department="OSPCD ADMINISTRATION" t:item=2 t:vendor_name="159-161 BEACON STREET LLC" t:org_description="OSPCD-TRANS CAPITAL EXP" t:category_of_gov="General Government" m:amount=430

series e:cyh9-gqxg d:2016-06-30T00:00:00.000Z t:account_desc="LAND ACQUISITION" t:check=602552 t:department="OSPCD ADMINISTRATION" t:item=3 t:vendor_name="255 BEACON STREET CONDOMINIUM" t:org_description="OSPCD-TRANS CAPITAL EXP" t:category_of_gov="General Government" m:amount=290
```

## Meta Commands

```ls
metric m:amount p:float l:Amount t:dataTypeName=number

entity e:cyh9-gqxg l:"Open Checkbook Data FY16" t:attribution="City of Somerville Finance Department" t:url=https://data.somervillema.gov/api/views/cyh9-gqxg

property e:cyh9-gqxg t:meta.view v:id=cyh9-gqxg v:category=Finance v:attributionLink=http://www.somervillema.gov/departments/finance v:averageRating=0 v:name="Open Checkbook Data FY16" v:attribution="City of Somerville Finance Department"

property e:cyh9-gqxg t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:cyh9-gqxg t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:cyh9-gqxg t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| item | category_of_gov    | vendor_name                   | amount  | check_date          | department                | check  | org_description                | account_desc            | 
| ==== | ================== | ============================= | ======= | =================== | ========================= | ====== | ============================== | ======================= | 
| 1    | General Government | 15-17 BEACON STREET LLC       | 830.00  | 2016-06-30T00:00:00 | OSPCD ADMINISTRATION      | 602550 | OSPCD-TRANS CAPITAL EXP        | LAND ACQUISITION        | 
| 2    | General Government | 159-161 BEACON STREET LLC     | 430.00  | 2016-06-30T00:00:00 | OSPCD ADMINISTRATION      | 602551 | OSPCD-TRANS CAPITAL EXP        | LAND ACQUISITION        | 
| 3    | General Government | 255 BEACON STREET CONDOMINIUM | 290.00  | 2016-06-30T00:00:00 | OSPCD ADMINISTRATION      | 602552 | OSPCD-TRANS CAPITAL EXP        | LAND ACQUISITION        | 
| 4    | General Government | 282 BEACON STREET INC         | 150.00  | 2016-06-30T00:00:00 | OSPCD ADMINISTRATION      | 602553 | OSPCD-TRANS CAPITAL EXP        | LAND ACQUISITION        | 
| 5    | General Government | 4IMPRINT                      | 64.18   | 2015-12-23T00:00:00 | GRANTS MANAGEMENT         | 3238   | GRANTS DEV ORDINARY MAINT      | OFFICE SUPPLIES         | 
| 6    | General Government | 4IMPRINT                      | 1651.33 | 2016-06-22T00:00:00 | COMMUNICATIONS DEPARTMENT | 3821   | COMMUNICATIONS ORDINARY MAINT  | PRINTING & STATIONERY   | 
| 7    | General Government | 4IMPRINT                      | 203.27  | 2015-11-12T00:00:00 | OSPCD ADMINISTRATION      | 3101   | OSPCD-HOUSING ORDINARY MAINT   | OFFICE SUPPLIES         | 
| 8    | General Government | 4IMPRINT                      | 373.41  | 2016-06-22T00:00:00 | POLICE DEPARTMENT         | 3821   | POLICE ORDINARY MAINTENANCE    | PRINTING & STATIONERY   | 
| 10   | Education          | 4IMPRINT                      | 554.78  | 2016-05-11T00:00:00 | SCHOOL ADMINISTRATION     | 3688   | SPP14 OTHER-DW-PD STIPENDS     | SCHOOL OTHER OTHER EXP. | 
| 11   | General Government | 4IMPRINT                      | 603.49  | 2015-08-19T00:00:00 | BOARD OF HEALTH           | 2827   | BOARD OF HEALTH ORDINARY MAINT | UNIFORMS                | 
```