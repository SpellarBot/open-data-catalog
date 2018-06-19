# Companies Self-Insured for Workers' Compensation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/companies-self-insured-for-workers-compensation) |
| Metadata | [Link](https://data.iowa.gov/api/views/hfe6-4nr6) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/hfe6-4nr6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/hfe6-4nr6/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | hfe6-4nr6 |
| Name | Companies Self-Insured for Workers' Compensation |
| Category | Government |
| Created | 2016-12-08T17:18:54Z |
| Publication Date | 2017-01-11T17:04:24Z |

## Description

Companies Self-Insured for Workers' Compensation in the State of Iowa pursuant to Section 87.11, Code of Iowa

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | company         | Company         | text      | text        |
| Yes      | series tag  | contact_person  | Contact Person  | text      | text        |
| Yes      | series tag  | contact_title_1 | Contact Title 1 | text      | text        |
| Yes      | series tag  | contact_title_2 | Contact Title 2 | text      | text        |
| No       |             | address1        | Address1        | text      | text        |
| No       |             | address2        | Address2        | text      | text        |
| Yes      | series tag  | city            | City            | text      | text        |
| Yes      | series tag  | state           | State           | text      | text        |
| Yes      | series tag  | zip             | ZIP             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address1,address2
```

## Data Commands

```ls
series e:hfe6-4nr6 d:2017-01-11T17:01:56.000Z t:contact_title_1="INSURANCE SPECIALIST" t:zip=62521-1820 t:company="ARCHER DANIELS MIDLAND COMPANY" t:state=IL t:contact_person="CINDY COOPER" t:city=DECATUR m:row_number.hfe6-4nr6=1

series e:hfe6-4nr6 d:2017-01-11T17:01:56.000Z t:contact_title_1="WORK COMP PROCESS OWNER" t:zip=61265-8090 t:company="DEERE & COMPANY" t:state=IL t:contact_person="KEVIN CURRAN" t:city=MOLINE m:row_number.hfe6-4nr6=2

series e:hfe6-4nr6 d:2017-01-11T17:01:56.000Z t:contact_title_1="SR. MGR, WORK COMP." t:zip=53051 t:company="KOHL'S DEPARTMENT STORES" t:state=WI t:contact_person="LAURIE FREY" t:city="MENOMONEE FALLS" m:row_number.hfe6-4nr6=3
```

## Meta Commands

```ls
metric m:row_number.hfe6-4nr6 p:long l:"Row Number"

entity e:hfe6-4nr6 l:"Companies Self-Insured for Workers' Compensation" t:url=https://data.iowa.gov/api/views/hfe6-4nr6

property e:hfe6-4nr6 t:meta.view v:id=hfe6-4nr6 v:category=Government v:averageRating=0 v:name="Companies Self-Insured for Workers' Compensation"

property e:hfe6-4nr6 t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:hfe6-4nr6 t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| :updated_at | company                                          | contact_person | contact_title_1               | contact_title_2 | address1                         | address2         | city            | state | zip        | 
| =========== | ================================================ | ============== | ============================= | =============== | ================================ | ================ | =============== | ===== | ========== | 
| 1484154116  | ARCHER DANIELS MIDLAND COMPANY                   | CINDY COOPER   | INSURANCE SPECIALIST          |                 | P. O. BOX 1470                   |                  | DECATUR         | IL    | 62521-1820 | 
| 1484154116  | DEERE & COMPANY                                  | KEVIN CURRAN   | WORK COMP PROCESS OWNER       |                 | ONE JOHN DEERE PLACE             |                  | MOLINE          | IL    | 61265-8090 | 
| 1484154116  | KOHL'S DEPARTMENT STORES                         | LAURIE FREY    | SR. MGR, WORK COMP.           |                 | N56 W17000 RIDGEWOOD DR          |                  | MENOMONEE FALLS | WI    | 53051      | 
| 1484154116  | LABOR READY MID-ATLANTIC, INC. D/B/A PEOPLEREADY | ALISON FENT    | RISK SPECIALIST               |                 | P.O. BOX 2910                    |                  | TACOMA          | WA    | 98401      | 
| 1484154116  | OWEN INDUSTRIES, INC.                            | EDWARD KORBEL  | VICE PRESIDENT, FINANCE & CFO |                 | 501 AVENUE "H"                   |                  | CARTER LAKE     | IA    | 51510      | 
| 1484154116  | QUIKTRIP CORPORATION                             | JO DYE         | RISK AND INSURANCE ANALYST    |                 | P.O. BOX 3475                    |                  | TULSA           | OK    | 74101      | 
| 1484154116  | RUAN TRANSPORTATION MANAGEMENT SYSTEMS, INC.     | BILL WALTON    | DIRECTOR OF CLAIMS            |                 | 3100 RUAN CENTER                 | 666 GRAND AVENUE | DES MOINES      | IA    | 50309      | 
| 1484154116  | RYDER SYSTEM, INC.                               | RENICA SMITH   | SI ACCOUNT MANAGER            |                 | SIX CONCOURSE PARKWAY SUITE 2300 |                  | ATLANTA         | GA    | 30328      | 
| 1484154116  | UNION ELECTRIC COMPANY                           | MARK E. BLAIR  | DIRECTOR - RISK MANAGEMENT    |                 | P.O. BOX 66149, MC 1050          |                  | ST. LOUIS       | MO    | 63166-6149 | 
| 1484154116  | WELLS ENTERPRISES, INC.                          | DAVID CALHOUN  | DIRECTOR, CORPORATE RISK MGT. |                 | ONE BLUE BUNNY DRIVE             |                  | LE MARS         | IA    | 51031-1310 | 
```