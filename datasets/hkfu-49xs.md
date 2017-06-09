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
series e:hkfu-49xs d:2016-11-22T00:00:00.000Z t:account_desc="OFFICE SUPPLIES" t:check=4229 t:department="OSPCD ADMINISTRATION" t:item=1 t:vendor_name=4IMPRINT t:org_description="OSPCD-ADMIN ORDINARY MAINT" t:category_of_gov="General Government" m:amount=870.66

series e:hkfu-49xs d:2016-08-31T00:00:00.000Z t:account_desc="PRINTING & STATIONERY" t:check=3991 t:department="POLICE DEPARTMENT" t:item=2 t:vendor_name=4IMPRINT t:org_description="POLICE ORDINARY MAINTENANCE" t:category_of_gov="General Government" m:amount=357.44

series e:hkfu-49xs d:2016-08-31T00:00:00.000Z t:account_desc=STATIONERY t:check=3992 t:department="POLICE DEPARTMENT" t:item=3 t:vendor_name=4IMPRINT t:org_description="POLICE-ANIMAL CTL ORD MAINT" t:category_of_gov="General Government" m:amount=722.6
```

## Meta Commands

```ls
metric m:amount p:float l:Amount t:dataTypeName=number

entity e:hkfu-49xs l:"Open Checkbook Data FY17" t:attribution="City of Somerville Finance Department" t:url=https://data.somervillema.gov/api/views/hkfu-49xs

property e:hkfu-49xs t:meta.view d:2017-06-09T13:51:45.131Z v:id=hkfu-49xs v:category=Finance v:attributionLink=http://www.somervillema.gov/departments/finance v:averageRating=0 v:name="Open Checkbook Data FY17" v:attribution="City of Somerville Finance Department"

property e:hkfu-49xs t:meta.view.license d:2017-06-09T13:51:45.131Z v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:hkfu-49xs t:meta.view.owner d:2017-06-09T13:51:45.131Z v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:hkfu-49xs t:meta.view.tableauthor d:2017-06-09T13:51:45.131Z v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| item | category_of_gov    | vendor_name             | amount  | check_date          | department            | check  | org_description                | account_desc                   | 
| ==== | ================== | ======================= | ======= | =================== | ===================== | ====== | ============================== | ============================== | 
| 1    | General Government | 4IMPRINT                | 870.66  | 2016-11-22T00:00:00 | OSPCD ADMINISTRATION  | 4229   | OSPCD-ADMIN ORDINARY MAINT     | OFFICE SUPPLIES                | 
| 2    | General Government | 4IMPRINT                | 357.44  | 2016-08-31T00:00:00 | POLICE DEPARTMENT     | 3991   | POLICE ORDINARY MAINTENANCE    | PRINTING & STATIONERY          | 
| 3    | General Government | 4IMPRINT                | 722.60  | 2016-08-31T00:00:00 | POLICE DEPARTMENT     | 3992   | POLICE-ANIMAL CTL ORD MAINT    | STATIONERY                     | 
| 4    | General Government | 4IMPRINT                | 1474.28 | 2016-08-24T00:00:00 | BOARD OF HEALTH       | 3966   | MT AUBURN COMM BENEFIT FUNDING | OTHER SUPPLIES                 | 
| 6    | Education          | A C MOORE INC           | 74.84   | 2016-08-10T00:00:00 | SCHOOL ADMINISTRATION | 603403 | COMMSCH SACC-DW-CIVIC          | SACC-DW-EDUCSUPP               | 
| 12   | Education          | A C MOORE INC           | 327.82  | 2016-08-31T00:00:00 | SCHOOL ADMINISTRATION | 604041 | COMMSCH SACC-DW-CIVIC          | SACC-DW-EDUCSUPP               | 
| 16   | Education          | A C MOORE INC           | 189.27  | 2016-09-28T00:00:00 | SCHOOL ADMINISTRATION | 605065 | COMMSCH SACC-DW-CIVIC          | SACC-DW-EDUCSUPP               | 
| 32   | Education          | A C MOORE INC           | 945.38  | 2016-11-16T00:00:00 | SCHOOL ADMINISTRATION | 606883 | COMMSCH SACC-DW-CIVIC          | SACC-DW-EDUCSUPP               | 
| 49   | Education          | A C MOORE INC           | 943.27  | 2016-12-21T00:00:00 | SCHOOL ADMINISTRATION | 608377 | COMMSCH SACC-DW-CIVIC          | SACC-DW-EDUCSUPP               | 
| 50   | Education          | A DAIGGER & COMPANY INC | 18.24   | 2016-10-19T00:00:00 | SCHOOL ADMINISTRATION | 605815 | ESCS-SUPPLIES-ESCS-REG         | ESCS-SUPPLIES-ESCS-REG-SUPPLIE | 
```