# ARRA Grant Expenditures as of COB May 31, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-expenditures-as-of-cob-may-31-2012-10035) |
| Metadata | [Link](https://data.mo.gov/api/views/wnys-nx3n) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/wnys-nx3n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/wnys-nx3n/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | wnys-nx3n |
| Name | ARRA Grant Expenditures as of COB May 31, 2012 |
| Category | Government |
| Created | 2012-06-01T17:58:55Z |
| Publication Date | 2012-06-01T18:03:30Z |

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
series e:wnys-nx3n d:2012-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="CRYSTAL LAKE FISHERIES INC" m:payments_total=52809.14

series e:wnys-nx3n d:2012-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FLOWERS FISH FARM LLC" m:payments_total=37285.06

series e:wnys-nx3n d:2012-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FRENCH FARMS" m:payments_total=21755.01
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:wnys-nx3n l:"ARRA Grant Expenditures as of COB May 31, 2012" t:url=https://data.mo.gov/api/views/wnys-nx3n

property e:wnys-nx3n t:meta.view v:id=wnys-nx3n v:category=Government v:averageRating=0 v:name="ARRA Grant Expenditures as of COB May 31, 2012"

property e:wnys-nx3n t:meta.view.owner v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:displayName="Carolyn Aggeler"

property e:wnys-nx3n t:meta.view.tableauthor v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:roleName=editor v:displayName="Carolyn Aggeler"
```

## Top Records

```ls
| agency_name | program_name                             | vendor_name                   | payments_total | 
| =========== | ======================================== | ============================= | ============== | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | CRYSTAL LAKE FISHERIES INC    | 52809.14       | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | FLOWERS FISH FARM LLC         | 37285.06       | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | FRENCH FARMS                  | 21755.01       | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | AG PROCESSING INC             | 5027409.02     | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | AMERICAN ENERGY PRODUCERS INC | 6.00           | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | FASTENAL CO                   | 38.10          | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | GLOBAL FUELS LLC              | 143305.30      | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | LIFE LINE FOODS LLC           | 6867444.78     | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | MID-AMERICA BIOFUELS LLC      | 4564791.50     | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | MID-MISSOURI ENERGY INC       | 3211382.62     | 
```