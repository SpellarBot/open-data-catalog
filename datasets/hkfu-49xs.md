# Open Checkbook Data FY17

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-checkbook-data-fy17) |
| Metadata | [Link](https://data.somervillema.gov/api/views/hkfu-49xs) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/hkfu-49xs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/hkfu-49xs/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | hkfu-49xs |
| Name | Open Checkbook Data FY17 |
| Attribution | City of Somerville Finance Department |
| Category | Finance |
| Tags | open checkbook, finance, fy17 |
| Created | 2016-11-09T16:04:11Z |
| Publication Date | 2017-01-23T15:27:28Z |
| Rows Updated | 2017-01-23T15:27:19Z |

## Description

The City of Somerville uses this dataset to provide residents with information regarding local government spending.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | numeric metric | item            | Item #          | number        | number        |
| Yes      | series tag     | category_of_gov | Category of Gov | text          | text          |
| Yes      | series tag     | vendor_name     | VENDOR NAME     | text          | text          |
| Yes      | numeric metric | amount          | Amount          | number        | number        |
| Yes      | time           | check_date      | Check Date      | calendar_date | calendar_date |
| Yes      | series tag     | department      | Department      | text          | text          |
| Yes      | numeric metric | check           | Check #         | number        | number        |
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
series e:hkfu-49xs d:2016-11-22T00:00:00.000Z t:account_desc="OFFICE SUPPLIES" t:department="OSPCD ADMINISTRATION" t:vendor_name=4IMPRINT t:org_description="OSPCD-ADMIN ORDINARY MAINT" t:category_of_gov="General Government" m:amount=870.66 m:check=4229 m:item=1

series e:hkfu-49xs d:2016-08-31T00:00:00.000Z t:account_desc="PRINTING & STATIONERY" t:department="POLICE DEPARTMENT" t:vendor_name=4IMPRINT t:org_description="POLICE ORDINARY MAINTENANCE" t:category_of_gov="General Government" m:amount=357.44 m:check=3991 m:item=2

series e:hkfu-49xs d:2016-08-31T00:00:00.000Z t:account_desc=STATIONERY t:department="POLICE DEPARTMENT" t:vendor_name=4IMPRINT t:org_description="POLICE-ANIMAL CTL ORD MAINT" t:category_of_gov="General Government" m:amount=722.6 m:check=3992 m:item=3
```

## Meta Commands

```ls
metric m:item p:integer l:"Item #" t:dataTypeName=number

metric m:amount l:Amount t:dataTypeName=number

metric m:check p:integer l:"Check #" t:dataTypeName=number

entity e:hkfu-49xs l:"Open Checkbook Data FY17" t:attribution="City of Somerville Finance Department" t:url=https://data.somervillema.gov/api/views/hkfu-49xs

property e:hkfu-49xs t:meta.view v:id=hkfu-49xs v:category=Finance v:attributionLink=http://www.somervillema.gov/departments/finance v:averageRating=0 v:name="Open Checkbook Data FY17" v:attribution="City of Somerville Finance Department"

property e:hkfu-49xs t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:hkfu-49xs t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"

property e:hkfu-49xs t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```