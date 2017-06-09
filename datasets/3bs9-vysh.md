# Open Checkbook Data FY15

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-checkbook-data-fy15) |
| Metadata | [Link](https://data.somervillema.gov/api/views/3bs9-vysh) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/3bs9-vysh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/3bs9-vysh/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | 3bs9-vysh |
| Name | Open Checkbook Data FY15 |
| Attribution | City of Somerville Auditing Department |
| Category | Finance |
| Tags | open checkbook, finance, fy15 |
| Created | 2016-02-01T15:12:57Z |
| Publication Date | 2016-02-01T15:30:16Z |

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
series e:3bs9-vysh d:2015-06-30T00:00:00.000Z t:account_desc="NEIGHBORHOOD IMP. COUNCIL" t:check=1999 t:department="COMMUNICATIONS DEPARTMENT" t:item=1 t:vendor_name=4IMPRINT t:org_description="COMMUNICATIONS ORDINARY MAINT" t:category_of_gov="General Government" m:amount=995.12

series e:3bs9-vysh d:2014-08-13T00:00:00.000Z t:account_desc="OTHER SUPPLIES" t:check=1094 t:department="BOARD OF HEALTH" t:item=2 t:vendor_name=4IMPRINT t:org_description="MASS IN MOTION '14" t:category_of_gov="General Government" m:amount=958.27

series e:3bs9-vysh d:2014-10-29T00:00:00.000Z t:account_desc="PROMOTIONAL MATERIALS" t:check=1286 t:department="BOARD OF HEALTH" t:item=4 t:vendor_name=4IMPRINT t:org_description="MASS.IN MOTION '15" t:category_of_gov="General Government" m:amount=953.15
```

## Meta Commands

```ls
metric m:amount p:float l:Amount t:dataTypeName=number

entity e:3bs9-vysh l:"Open Checkbook Data FY15" t:attribution="City of Somerville Auditing Department" t:url=https://data.somervillema.gov/api/views/3bs9-vysh

property e:3bs9-vysh t:meta.view d:2017-06-09T13:52:08.944Z v:id=3bs9-vysh v:category=Finance v:attributionLink=http://www.somervillema.gov/departments/finance/auditing v:averageRating=0 v:name="Open Checkbook Data FY15" v:attribution="City of Somerville Auditing Department"

property e:3bs9-vysh t:meta.view.license d:2017-06-09T13:52:08.944Z v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:3bs9-vysh t:meta.view.owner d:2017-06-09T13:52:08.944Z v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:3bs9-vysh t:meta.view.tableauthor d:2017-06-09T13:52:08.944Z v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| item | category_of_gov    | vendor_name                            | amount    | check_date          | department                 | check  | org_description                | account_desc              | 
| ==== | ================== | ====================================== | ========= | =================== | ========================== | ====== | ============================== | ========================= | 
| 1    | General Government | 4IMPRINT                               | 995.12    | 2015-06-30T00:00:00 | COMMUNICATIONS DEPARTMENT  | 1999   | COMMUNICATIONS ORDINARY MAINT  | NEIGHBORHOOD IMP. COUNCIL | 
| 2    | General Government | 4IMPRINT                               | 958.27    | 2014-08-13T00:00:00 | BOARD OF HEALTH            | 1094   | MASS IN MOTION '14             | OTHER SUPPLIES            | 
| 4    | General Government | 4IMPRINT                               | 953.15    | 2014-10-29T00:00:00 | BOARD OF HEALTH            | 1286   | MASS.IN MOTION '15             | PROMOTIONAL MATERIALS     | 
| 5    | General Government | 4IMPRINT                               | 2124.00   | 2014-10-08T00:00:00 | BOARD OF HEALTH            | 1232   | SOCIAL NORMS/MKTNG/MEDIA '14   | OTHER SUPPLIES            | 
| 6    | General Government | 7TH MASS.REGIMENT                      | 1000.00   | 2015-05-20T00:00:00 | VETERANS SERVICES          | 586357 | VETERANS BENEFITS ORDINARY MNT | PROFESSIONL & TECHNCL SVC | 
| 7    | Public Works       | A AND C DEMOLITION AND SITE LLC        | 5700.00   | 2014-10-08T00:00:00 | DEPARTMENT OF PUBLIC WORKS | 578918 | DPW-SNOW REMVL ORDINARY MAINT  | SNOW REMOVAL              | 
| 10   | Public Works       | A AND C DEMOLITION AND SITE LLC        | 147645.00 | 2015-07-08T00:00:00 | DEPARTMENT OF PUBLIC WORKS | 589150 | DPW-SNOW REMVL ORDINARY MAINT  | SNOW REMOVAL              | 
| 11   | General Government | A A E EMBROIDERY & SCREEN PRINTING INC | 2553.00   | 2015-05-20T00:00:00 | OFFICE OF MAYOR            | 586358 | CONVERSE/FILL IN BLANK EXP     | UNIFORMS                  | 
| 12   | General Government | A A E EMBROIDERY & SCREEN PRINTING INC | 1760.00   | 2015-03-04T00:00:00 | RECREATION AND YOUTH       | 583710 | REC/YOUTH PROG ORDINARY MAINT  | UNIFORMS                  | 
| 13   | General Government | A A E EMBROIDERY & SCREEN PRINTING INC | 2314.00   | 2015-03-04T00:00:00 | RECREATION AND YOUTH       | 583710 | PARKS AND RECREATION           | UNIFORMS                  | 
```