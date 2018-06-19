# Expenditures: Transportation: As of June 30, 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-transportation-as-of-june-30-2010-09636) |
| Metadata | [Link](https://data.oregon.gov/api/views/ft6h-w68b) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ft6h-w68b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ft6h-w68b/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ft6h-w68b |
| Name | Expenditures: Transportation: As of June 30, 2010 |
| Category | Revenue & Expense |
| Created | 2011-02-09T23:37:26Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | agency_title    | AGENCY_TITLE    | text      | text        |
| Yes      | series tag     | compt_obj_title | COMPT_OBJ_TITLE | text      | text        |
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | money     | money       |
| Yes      | series tag     | vendor_name     | VENDOR_NAME     | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR_STATE    | text      | text        |
| Yes      | series tag     | agency          | AGENCY          | text      | number      |
| Yes      | numeric metric | compt_obj       | COMPT_OBJ       | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ft6h-w68b d:2010-01-01T00:00:00.000Z t:vendor_state=OR t:agency_title="TRANSPORTATION, DEPARTMENT OF" t:agency=730 t:compt_obj_title="INSTATE LODGING" t:vendor_name="BDS LLC" m:compt_obj=4106 m:cash_expense=1817.2

series e:ft6h-w68b d:2010-01-01T00:00:00.000Z t:vendor_state=CA t:agency_title="TRANSPORTATION, DEPARTMENT OF" t:agency=730 t:compt_obj_title="FUELS AND UTILITIES" t:vendor_name="ROTO ROOTER" m:compt_obj=4825 m:cash_expense=73

series e:ft6h-w68b d:2010-01-01T00:00:00.000Z t:vendor_state=MO t:agency_title="TRANSPORTATION, DEPARTMENT OF" t:agency=730 t:compt_obj_title="AGENCY PROGRAM RELATED SERVICES" t:vendor_name="WW GRAINGER INC" m:compt_obj=4975 m:cash_expense=9433.93
```

## Meta Commands

```ls
metric m:cash_expense p:decimal l:CASH_EXPENSE t:dataTypeName=money

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

entity e:ft6h-w68b l:"Expenditures: Transportation: As of June 30, 2010" t:url=https://data.oregon.gov/api/views/ft6h-w68b

property e:ft6h-w68b t:meta.view v:id=ft6h-w68b v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: Transportation: As of June 30, 2010"

property e:ft6h-w68b t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ft6h-w68b t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_title                  | compt_obj_title                   | cash_expense | vendor_name     | vendor_state | agency | compt_obj | 
| ============================= | ================================= | ============ | =============== | ============ | ====== | ========= | 
| TRANSPORTATION, DEPARTMENT OF | INSTATE LODGING                   | 1817.2       | BDS LLC         | OR           | 730    | 4106      | 
| TRANSPORTATION, DEPARTMENT OF | FUELS AND UTILITIES               | 73           | ROTO ROOTER     | CA           | 730    | 4825      | 
| TRANSPORTATION, DEPARTMENT OF | AGENCY PROGRAM RELATED SERVICES   | 9433.93      | WW GRAINGER INC | MO           | 730    | 4975      | 
| TRANSPORTATION, DEPARTMENT OF | AGENCY PROGRAM RELATED SERVICES   | 1707.5       | 4S SIGNS LLC    | OR           | 730    | 4975      | 
| TRANSPORTATION, DEPARTMENT OF | AGENCY PROGRAM RELATED SERVICES   | 431.88       | BOLL LLC        | OR           | 730    | 4975      | 
| TRANSPORTATION, DEPARTMENT OF | AGENCY PROGRAM RELATED SERVICES   | 97.92        | CLAS INC        | OR           | 730    | 4975      | 
| TRANSPORTATION, DEPARTMENT OF | AGENCY PROGRAM RELATED SERVICES   | 447.8        | JAY COIL        | OR           | 730    | 4975      | 
| TRANSPORTATION, DEPARTMENT OF | AGENCY PROGRAM RELATED SUPPLIES   | 505.23       | BOLL LLC        | OR           | 730    | 4976      | 
| TRANSPORTATION, DEPARTMENT OF | AGENCY PROGRAM RELATED SUPPLIES   | 4250         | FARM FAB        | OR           | 730    | 4976      | 
| TRANSPORTATION, DEPARTMENT OF | DISTRIBUTION TO OTHER GOVERNMENTS | 19049        | CURRY COUNTY    | OR           | 730    | 6700      | 
```