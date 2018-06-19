# ARRA Grant Expenditures As Of COB July 31, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-expenditures-as-of-cob-july-31-2012-14527) |
| Metadata | [Link](https://data.mo.gov/api/views/w32v-gn8m) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/w32v-gn8m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/w32v-gn8m/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | w32v-gn8m |
| Name | ARRA Grant Expenditures As Of COB July 31, 2012 |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2012-08-07T16:17:30Z |
| Publication Date | 2012-08-07T16:20:21Z |

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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:w32v-gn8m d:2012-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="CRYSTAL LAKE FISHERIES INC" m:payments_total=52809.14

series e:w32v-gn8m d:2012-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FLOWERS FISH FARM LLC" m:payments_total=37285.06

series e:w32v-gn8m d:2012-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FRENCH FARMS" m:payments_total=21755.01
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:w32v-gn8m l:"ARRA Grant Expenditures As Of COB July 31, 2012" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/w32v-gn8m

property e:w32v-gn8m t:meta.view v:id=w32v-gn8m v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Expenditures As Of COB July 31, 2012" v:attribution="Office of Administration"

property e:w32v-gn8m t:meta.view.owner v:id=wzcj-jrcg v:screenName=John v:displayName=John

property e:w32v-gn8m t:meta.view.tableauthor v:id=wzcj-jrcg v:screenName=John v:roleName=editor v:displayName=John
```

## Top Records

```ls
| agency_name | program_name                             | vendor_name                   | payments_total | 
| =========== | ======================================== | ============================= | ============== | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | CRYSTAL LAKE FISHERIES INC    | 52809.14       | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | FLOWERS FISH FARM LLC         | 37285.06       | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | FRENCH FARMS                  | 21755.01       | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | AG PROCESSING INC             | 5027409.01     | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | AMERICAN ENERGY PRODUCERS INC | 6              | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | FASTENAL CO                   | 38.1           | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | GLOBAL FUELS LLC              | 143305.29      | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | LIFE LINE FOODS LLC           | 6867444.78     | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | MID-AMERICA BIOFUELS LLC      | 4564791.5      | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | MID-MISSOURI ENERGY INC       | 3211382.62     | 
```