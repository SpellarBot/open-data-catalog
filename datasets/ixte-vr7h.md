# Spending Disclosure - Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/spending-disclosure-fiscal-year-2013-620d4) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/ixte-vr7h) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/ixte-vr7h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/ixte-vr7h/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | ixte-vr7h |
| Name | Spending Disclosure - Fiscal Year 2013 |
| Attribution | Montgomery County Department of Finance |
| Category | Finance/Tax/Property |
| Tags | financial, fiscal year 13, 2013, spending, $25, 000 or more |
| Created | 2013-08-30T19:38:39Z |
| Publication Date | 2013-09-03T19:39:48Z |

## Description

The purpose of this Spending Disclosure FY13 dataset is to allow the public to search and view summary information on payments made to recipients (referred to as suppliers) that received $25,000 or more in a fiscal year. Note that salary and benefit payments to employees, pension payments to retirees, and any information that is confidential under State or Federal law is excluded from disclosure.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | supplier_name | Supplier Name | text      | text        |
| Yes      | series tag     | zip_code      | Zip Code      | text      | text        |
| Yes      | series tag     | department    | Department    | text      | text        |
| Yes      | numeric metric | amount        | Amount        | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ixte-vr7h d:2013-01-01T00:00:00.000Z t:zip_code=55170 t:department="Not Defined" t:supplier_name="US BANK" m:amount=1200000

series e:ixte-vr7h d:2013-01-01T00:00:00.000Z t:zip_code=75266 t:department=Police t:supplier_name=VERIZON m:amount=1869.45

series e:ixte-vr7h d:2013-01-01T00:00:00.000Z t:zip_code=60197 t:department=Police t:supplier_name="WEST GROUP" m:amount=292
```

## Meta Commands

```ls
metric m:amount p:double l:Amount d:"Dollar amount paid to the supplier." t:dataTypeName=money

entity e:ixte-vr7h l:"Spending Disclosure - Fiscal Year 2013" t:attribution="Montgomery County Department of Finance" t:url=https://data.montgomerycountymd.gov/api/views/ixte-vr7h

property e:ixte-vr7h t:meta.view v:id=ixte-vr7h v:category=Finance/Tax/Property v:averageRating=0 v:name="Spending Disclosure - Fiscal Year 2013" v:attribution="Montgomery County Department of Finance"

property e:ixte-vr7h t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:ixte-vr7h t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```