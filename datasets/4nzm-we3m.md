# ARRA Grant Expenditures As Of COB May 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-expenditures-as-of-cob-may-31-2016) |
| Metadata | [Link](https://data.mo.gov/api/views/4nzm-we3m) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/4nzm-we3m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/4nzm-we3m/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 4nzm-we3m |
| Name | ARRA Grant Expenditures As Of COB May 31, 2016 |
| Category | Government Administration |
| Created | 2016-06-02T20:05:41Z |
| Publication Date | 2016-06-02T20:08:27Z |

## Description

Data that shows how every dollar received by the State of Missouri under the American Reinvestment and Recovery Act of 2009 has been spent including the name of the state agency that made the expenditure, category of expenditure and the names of vendors receiving payments.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | agency_name    | Agency Name    | text      | text        |
| Yes      | series tag     | program_name   | Program Name   | text      | text        |
| Yes      | series tag     | vendor_name    | Vendor Name    | text      | text        |
| Yes      | numeric metric | payments_total | Payments Total | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4nzm-we3m d:2016-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="CRYSTAL LAKE FISHERIES INC" m:payments_total=52809.14

series e:4nzm-we3m d:2016-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FLOWERS FISH FARM LLC" m:payments_total=37285.06

series e:4nzm-we3m d:2016-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FRENCH FARMS" m:payments_total=21755.01
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=number

entity e:4nzm-we3m l:"ARRA Grant Expenditures As Of COB May 31, 2016" t:url=https://data.mo.gov/api/views/4nzm-we3m

property e:4nzm-we3m t:meta.view v:id=4nzm-we3m v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Expenditures As Of COB May 31, 2016"

property e:4nzm-we3m t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:4nzm-we3m t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| agency_name | program_name                             | vendor_name                   | payments_total     | 
| =========== | ======================================== | ============================= | ================== | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | CRYSTAL LAKE FISHERIES INC    | 52809.14           | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | FLOWERS FISH FARM LLC         | 37285.06           | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | FRENCH FARMS                  | 21755.01           | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | SCHRIEFERS OFFICE EQUIPMENT   | 24.5               | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | AG PROCESSING INC             | 5027409.0199999996 | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | AMERICAN ENERGY PRODUCERS INC | 6                  | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | FASTENAL CO                   | 38.1               | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | GLOBAL FUELS LLC              | 143305.29999999999 | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | LIFE LINE FOODS LLC           | 6867444.7800000003 | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | MID-AMERICA BIOFUELS LLC      | 4564791.5          | 
```