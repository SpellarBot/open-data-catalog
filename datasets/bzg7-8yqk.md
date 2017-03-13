# ARRA Grant Expenditures As Of COB January 31, 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-expenditures-as-of-cob-january-31-2013-51d18) |
| Metadata | [Link](https://data.mo.gov/api/views/bzg7-8yqk) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/bzg7-8yqk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/bzg7-8yqk/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | bzg7-8yqk |
| Name | ARRA Grant Expenditures As Of COB January 31, 2013 |
| Category | Government Administration |
| Created | 2013-02-01T16:57:56Z |
| Publication Date | 2013-02-01T16:59:04Z |
| Rows Updated | 2013-02-01T16:58:05Z |

## Description

Data that shows how every dollar received by the State of Missouri under the American Reinvestment and Recovery Act of 2009 has been spent including the name of the state agency that made the expenditure, category of expenditure and the names of vendors receiving payments.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | agency_name    | Agency Name    | text      | text        |
| Yes      | series tag     | program_name   | Program Name   | text      | text        |
| Yes      | series tag     | vendor_name    | Vendor Name    | text      | text        |
| Yes      | numeric metric | payments_total | Payments Total | money     | money       |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bzg7-8yqk d:2013-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="CRYSTAL LAKE FISHERIES INC" m:payments_total=52809.14

series e:bzg7-8yqk d:2013-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FLOWERS FISH FARM LLC" m:payments_total=37285.06

series e:bzg7-8yqk d:2013-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FRENCH FARMS" m:payments_total=21755.01
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:bzg7-8yqk l:"ARRA Grant Expenditures As Of COB January 31, 2013" t:url=https://data.mo.gov/api/views/bzg7-8yqk

property e:bzg7-8yqk t:meta.view v:id=bzg7-8yqk v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Expenditures As Of COB January 31, 2013"

property e:bzg7-8yqk t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight

property e:bzg7-8yqk t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```