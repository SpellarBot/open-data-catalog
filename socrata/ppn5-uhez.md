# ARRA Grant Expenditures as of COB June 30, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-expenditures-as-of-cob-june-30-2012-665a8) |
| Metadata | [Link](https://data.mo.gov/api/views/ppn5-uhez) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/ppn5-uhez/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/ppn5-uhez/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | ppn5-uhez |
| Name | ARRA Grant Expenditures as of COB June 30, 2012 |
| Category | Government |
| Created | 2012-07-02T19:40:58Z |
| Publication Date | 2012-07-02T19:44:15Z |

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
series e:ppn5-uhez d:2012-01-01T00:00:00.000Z t:program_name="BUDGET STABILIZATION STATE FISCAL RELIEF" t:agency_name=JUDICIARY t:vendor_name=BP m:payments_total=269.05

series e:ppn5-uhez d:2012-01-01T00:00:00.000Z t:program_name="BUDGET STABILIZATION STATE FISCAL RELIEF" t:agency_name="MENTAL HEALTH" t:vendor_name=AT&T m:payments_total=125.36

series e:ppn5-uhez d:2012-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="CRYSTAL LAKE FISHERIES INC" m:payments_total=52809.14
```

## Meta Commands

```ls
metric m:payments_total p:decimal l:"Payments Total" t:dataTypeName=money

entity e:ppn5-uhez l:"ARRA Grant Expenditures as of COB June 30, 2012" t:url=https://data.mo.gov/api/views/ppn5-uhez

property e:ppn5-uhez t:meta.view v:id=ppn5-uhez v:category=Government v:averageRating=0 v:name="ARRA Grant Expenditures as of COB June 30, 2012"

property e:ppn5-uhez t:meta.view.owner v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:displayName="Carolyn Aggeler"

property e:ppn5-uhez t:meta.view.tableauthor v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:roleName=editor v:displayName="Carolyn Aggeler"
```

## Top Records

```ls
| agency_name   | program_name                             | vendor_name                   | payments_total     | 
| ============= | ======================================== | ============================= | ================== | 
| JUDICIARY     | BUDGET STABILIZATION STATE FISCAL RELIEF | BP                            | 269.05             | 
| MENTAL HEALTH | BUDGET STABILIZATION STATE FISCAL RELIEF | AT&T                          | 125.36             | 
| AGRICULTURE   | AQUACULTURE ASSISTANCE PROGRAM           | CRYSTAL LAKE FISHERIES INC    | 52809.14           | 
| AGRICULTURE   | AQUACULTURE ASSISTANCE PROGRAM           | FLOWERS FISH FARM LLC         | 37285.06           | 
| AGRICULTURE   | AQUACULTURE ASSISTANCE PROGRAM           | FRENCH FARMS                  | 21755.01           | 
| AGRICULTURE   | BUDGET STABILIZATION STATE FISCAL RELIEF | AG PROCESSING INC             | 5027409.0199999996 | 
| AGRICULTURE   | BUDGET STABILIZATION STATE FISCAL RELIEF | AMERICAN ENERGY PRODUCERS INC | 6                  | 
| AGRICULTURE   | BUDGET STABILIZATION STATE FISCAL RELIEF | FASTENAL CO                   | 38.1               | 
| AGRICULTURE   | BUDGET STABILIZATION STATE FISCAL RELIEF | GLOBAL FUELS LLC              | 143305.29999999999 | 
| AGRICULTURE   | BUDGET STABILIZATION STATE FISCAL RELIEF | LIFE LINE FOODS LLC           | 6867444.7800000003 | 
```