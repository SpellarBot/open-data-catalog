# Open Checkbook Data FY13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-checkbook-data-fy13) |
| Metadata | [Link](https://data.somervillema.gov/api/views/xkkm-7smn) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/xkkm-7smn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/xkkm-7smn/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | xkkm-7smn |
| Name | Open Checkbook Data FY13 |
| Attribution | City of Somerville Auditing Department |
| Category | Finance |
| Tags | open checkbook, finance, fy13 |
| Created | 2016-02-01T15:38:56Z |
| Publication Date | 2016-02-01T15:40:44Z |

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
series e:xkkm-7smn d:2013-05-01T00:00:00.000Z t:account_desc=SUPPLIES t:check=559845 t:department="COMMUNICATIONS DEPARTMENT" t:item=1 t:vendor_name=4IMPRINT t:org_description="CABLE/TELCO GRANT ACCOUNT" t:category_of_gov="General Government" m:amount=936.13

series e:xkkm-7smn d:2013-06-26T00:00:00.000Z t:account_desc="PROMOTIONAL MATERIALS" t:check=138 t:department="BOARD OF HEALTH" t:item=2 t:vendor_name=4IMPRINT t:org_description="MASS IN MOTION '13" t:category_of_gov="General Government" m:amount=951.87

series e:xkkm-7smn d:2013-01-09T00:00:00.000Z t:account_desc="PROGRAM SUPPLIES & MATLS" t:check=555894 t:department="BOARD OF HEALTH" t:item=3 t:vendor_name=4IMPRINT t:org_description="HLTHY KIDS,HLTHY COMM RWJ '12" t:category_of_gov="General Government" m:amount=4363.26
```

## Meta Commands

```ls
metric m:amount p:float l:Amount t:dataTypeName=number

entity e:xkkm-7smn l:"Open Checkbook Data FY13" t:attribution="City of Somerville Auditing Department" t:url=https://data.somervillema.gov/api/views/xkkm-7smn

property e:xkkm-7smn t:meta.view v:id=xkkm-7smn v:category=Finance v:attributionLink=http://www.somervillema.gov/departments/finance/ v:averageRating=0 v:name="Open Checkbook Data FY13" v:attribution="City of Somerville Auditing Department"

property e:xkkm-7smn t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:xkkm-7smn t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:xkkm-7smn t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| item | category_of_gov    | vendor_name       | amount  | check_date          | department                | check  | org_description                | account_desc              | 
| ==== | ================== | ================= | ======= | =================== | ========================= | ====== | ============================== | ========================= | 
| 1    | General Government | 4IMPRINT          | 936.13  | 2013-05-01T00:00:00 | COMMUNICATIONS DEPARTMENT | 559845 | CABLE/TELCO GRANT ACCOUNT      | SUPPLIES                  | 
| 2    | General Government | 4IMPRINT          | 951.87  | 2013-06-26T00:00:00 | BOARD OF HEALTH           | 138    | MASS IN MOTION '13             | PROMOTIONAL MATERIALS     | 
| 3    | General Government | 4IMPRINT          | 4363.26 | 2013-01-09T00:00:00 | BOARD OF HEALTH           | 555894 | HLTHY KIDS,HLTHY COMM RWJ '12  | PROGRAM SUPPLIES & MATLS  | 
| 4    | General Government | 4IMPRINT          | 352.96  | 2012-08-15T00:00:00 | BOARD OF HEALTH           | 551006 | SOC. NORMS/MKTNG/MEDIA CHNA 12 | OTHER SUPPLIES            | 
| 5    | General Government | 4IMPRINT          | 3071.04 | 2012-10-03T00:00:00 | BOARD OF HEALTH           | 552421 | SOC. NORMS/MKTNG/MEDIA CHNA 12 | OTHER SUPPLIES            | 
| 6    | General Government | 4IMPRINT          | 300.00  | 2012-09-12T00:00:00 | BOARD OF HEALTH           | 551633 | HEALTH DEPT SCAP REVOLV.       | PGM SUPPLIES & MATERIALS  | 
| 7    | General Government | 7TH MASS.REGIMENT | 1000.00 | 2013-05-22T00:00:00 | VETERANS SERVICES         | 560748 | VETERANS BENEFITS ORDINARY MNT | PROFESSIONL & TECHNCL SVC | 
| 17   | Education          | A C MOORE INC     | 768.75  | 2012-08-08T00:00:00 | SCHOOL ADMINISTRATION     | 550743 | COMMSCH SACC-DW-CIVIC          | SACC-DW-EDUCSUPP          | 
| 19   | Education          | A C MOORE INC     | 43.20   | 2012-09-19T00:00:00 | SCHOOL ADMINISTRATION     | 551866 | COMMSCH SACC-DW-CIVIC          | SACC-DW-EDUCSUPP          | 
| 21   | Education          | A C MOORE INC     | 25.96   | 2012-10-31T00:00:00 | SCHOOL ADMINISTRATION     | 553381 | COMMSCH SACC-DW-CIVIC          | SACC-DW-EDUCSUPP          | 
```