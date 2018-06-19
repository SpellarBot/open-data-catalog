# ARRA Grant Expenditures As Of COB June 30, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-expenditures-as-of-cob-june-30-2016) |
| Metadata | [Link](https://data.mo.gov/api/views/mqqt-f7zm) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/mqqt-f7zm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/mqqt-f7zm/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | mqqt-f7zm |
| Name | ARRA Grant Expenditures As Of COB June 30, 2016 |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2016-07-01T14:47:19Z |
| Publication Date | 2016-07-01T14:49:28Z |

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
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mqqt-f7zm d:2016-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="CRYSTAL LAKE FISHERIES INC" m:payments_total=52809.14

series e:mqqt-f7zm d:2016-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FLOWERS FISH FARM LLC" m:payments_total=37285.06

series e:mqqt-f7zm d:2016-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FRENCH FARMS" m:payments_total=21755.01
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:mqqt-f7zm l:"ARRA Grant Expenditures As Of COB June 30, 2016" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/mqqt-f7zm

property e:mqqt-f7zm t:meta.view v:id=mqqt-f7zm v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Expenditures As Of COB June 30, 2016" v:attribution="Office of Administration"

property e:mqqt-f7zm t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:mqqt-f7zm t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| agency_name | program_name                             | vendor_name                   | payments_total | 
| =========== | ======================================== | ============================= | ============== | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | CRYSTAL LAKE FISHERIES INC    | 52809.14       | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | FLOWERS FISH FARM LLC         | 37285.06       | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | FRENCH FARMS                  | 21755.01       | 
| AGRICULTURE | AQUACULTURE ASSISTANCE PROGRAM           | SCHRIEFERS OFFICE EQUIPMENT   | 24.5           | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | AG PROCESSING INC             | 5027409.01     | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | AMERICAN ENERGY PRODUCERS INC | 6              | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | FASTENAL CO                   | 38.1           | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | GLOBAL FUELS LLC              | 143305.29      | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | LIFE LINE FOODS LLC           | 6867444.78     | 
| AGRICULTURE | BUDGET STABILIZATION STATE FISCAL RELIEF | MID-AMERICA BIOFUELS LLC      | 4564791.5      | 
```