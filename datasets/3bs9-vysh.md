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

property e:3bs9-vysh t:meta.view v:id=3bs9-vysh v:category=Finance v:attributionLink=http://www.somervillema.gov/departments/finance/auditing v:averageRating=0 v:name="Open Checkbook Data FY15" v:attribution="City of Somerville Auditing Department"

property e:3bs9-vysh t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:3bs9-vysh t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:3bs9-vysh t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```