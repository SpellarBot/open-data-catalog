# Expenditures: ESD: Lane:Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-lane-fiscal-year-2014-4475b) |
| Metadata | [Link](https://data.oregon.gov/api/views/jnpy-s9uu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/jnpy-s9uu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/jnpy-s9uu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | jnpy-s9uu |
| Name | Expenditures: ESD: Lane:Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | expenditures, esd expenditures, lane esd expenditures 2014 |
| Created | 2014-12-16T17:05:47Z |
| Publication Date | 2014-12-29T05:59:03Z |

## Description

Summary of expenditures by Lane ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | esd            | ESD#           | number    | number      |
| Yes      | series tag     | esd_name       | ESD NAME       | text      | text        |
| Yes      | series tag     | fund_name      | FUND NAME      | text      | text        |
| Yes      | numeric metric | object         | OBJECT         | number    | number      |
| Yes      | series tag     | object_title   | OBJECT TITLE   | text      | text        |
| Yes      | series tag     | vendor_name    | VENDOR NAME    | text      | text        |
| No       |                | vendor_address | VENDOR ADDRESS | text      | text        |
| Yes      | series tag     | vendor_city    | VENDOR CITY    | text      | text        |
| Yes      | series tag     | vendor_state   | VENDOR STATE   | text      | text        |
| Yes      | series tag     | vendor_zip     | VENDOR ZIP     | text      | number      |
| Yes      | numeric metric | cash_expense   | CASH EXPENSE   | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = vendor_address
```

## Data Commands

```ls
series e:jnpy-s9uu d:2014-01-01T00:00:00.000Z t:vendor_city=SPRINGFIELD t:fund_name="GENERAL FUND" t:vendor_state=OR t:object_title=TRAVEL t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:vendor_zip=97477 t:vendor_name="MARIANNE OAKES" m:esd=2064 m:object=340 m:cash_expense=10

series e:jnpy-s9uu d:2014-01-01T00:00:00.000Z t:vendor_city=EUGENE t:fund_name="GENERAL FUND" t:vendor_state=OR t:object_title=GARBAGE t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:vendor_zip=97440 t:vendor_name="SANIPAC INC" m:esd=2064 m:object=328 m:cash_expense=25

series e:jnpy-s9uu d:2014-01-01T00:00:00.000Z t:vendor_city="CAROL STREAM" t:fund_name="MIGRANT EDUCATION" t:vendor_state=IL t:object_title=TELEPHONE t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:vendor_zip=60197 t:vendor_name="A T & T MOBILITY" m:esd=2064 m:object=351 m:cash_expense=69.68
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:object p:integer l:OBJECT t:dataTypeName=number

metric m:cash_expense p:double l:"CASH EXPENSE" t:dataTypeName=money

entity e:jnpy-s9uu l:"Expenditures: ESD: Lane:Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/jnpy-s9uu

property e:jnpy-s9uu t:meta.view v:id=jnpy-s9uu v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Lane:Fiscal Year 2014"

property e:jnpy-s9uu t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:jnpy-s9uu t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                        | fund_name         | object | object_title             | vendor_name                | vendor_address | vendor_city  | vendor_state | vendor_zip | cash_expense       | 
| ==== | =============================== | ================= | ====== | ======================== | ========================== | ============== | ============ | ============ | ========== | ================== | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | GENERAL FUND      | 340    | TRAVEL                   | MARIANNE OAKES             |                | SPRINGFIELD  | OR           | 97477      | 10                 | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | GENERAL FUND      | 328    | GARBAGE                  | SANIPAC INC                | P O BOX 10928  | EUGENE       | OR           | 97440      | 25                 | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | MIGRANT EDUCATION | 351    | TELEPHONE                | A T & T MOBILITY           | P O BOX 6463   | CAROL STREAM | IL           | 60197      | 69.680000000000007 | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | GENERAL FUND      | 389    | NON-INSTR PROF TECH SERV | "I LOVE U GUYS" FOUNDATION | P.O. BOX 1230  | BAILEY       | CO           | 80421      | 2757               | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | GENERAL FUND      | 351    | TELEPHONE                | A T & T - ATLANTA          | PO BOX 105068  | ATLANTA      | GA           | 30348      | 35.83              | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | GENERAL FUND      | 351    | TELEPHONE                | A T & T - ATLANTA          | PO BOX 105068  | ATLANTA      | GA           | 30348      | 41.07              | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | GENERAL FUND      | 351    | TELEPHONE                | A T & T - ATLANTA          | PO BOX 105068  | ATLANTA      | GA           | 30348      | 41.07              | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | GENERAL FUND      | 351    | TELEPHONE                | A T & T - ATLANTA          | PO BOX 105068  | ATLANTA      | GA           | 30348      | 41.45              | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | GENERAL FUND      | 351    | TELEPHONE                | A T & T - ATLANTA          | PO BOX 105068  | ATLANTA      | GA           | 30348      | 41.63              | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | GENERAL FUND      | 351    | TELEPHONE                | A T & T - ATLANTA          | PO BOX 105068  | ATLANTA      | GA           | 30348      | 41.63              | 
```