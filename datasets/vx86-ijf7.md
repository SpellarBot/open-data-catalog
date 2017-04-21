# Contracts: ESD: North Central: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-north-central-fiscal-year-2013-6dfac) |
| Metadata | [Link](https://data.oregon.gov/api/views/vx86-ijf7) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vx86-ijf7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vx86-ijf7/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vx86-ijf7 |
| Name | Contracts: ESD: North Central: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, esd, north central, fiscal year 2013 |
| Created | 2013-10-31T20:03:34Z |
| Publication Date | 2013-10-31T20:09:04Z |

## Description

Contracts for North Central ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | numeric metric | esd                    | ESD#                   | number    | number      |
| Yes      | series tag     | esd_name               | ESD NAME               | text      | text        |
| No       |                | _                      | #                      | text      | text        |
| Yes      | series tag     | award_title            | AWARD TITLE            | text      | text        |
| Yes      | series tag     | award_type             | AWARD TYPE             | text      | text        |
| Yes      | series tag     | type_of_contract       | TYPE OF CONTRACT       | text      | text        |
| Yes      | series tag     | contractor_information | CONTRACTOR INFORMATION | text      | text        |
| No       |                | contractor_address     | CONTRACTOR ADDRESS     | text      | text        |
| Yes      | series tag     | contractor_city        | CONTRACTOR CITY        | text      | text        |
| Yes      | series tag     | contractor_state       | CONTRACTOR STATE       | text      | text        |
| Yes      | series tag     | contractor_zip         | CONTRACTOR ZIP         | text      | number      |
| No       |                | contract_date          | CONTRACT DATE          | text      | text        |
| Yes      | series tag     | original_amt           | ORIGINAL AMT           | text      | text        |
| Yes      | numeric metric | amendment              | AMENDMENT              | number    | text        |
| Yes      | numeric metric | total_value            | TOTAL VALUE            | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _,contractor_address,contract_date
```

## Data Commands

```ls
series e:vx86-ijf7 d:2013-01-01T00:00:00.000Z t:esd_name="North Central ESD" t:type_of_contract=Material t:contractor_state=Or t:contractor_city=Fossil t:award_type="Three year contract" t:award_title="Bandwidth Services Agreement" t:contractor_information="Frontier TeleNet" t:contractor_zip=97830 t:original_amt=153090 m:amendment=130410 m:esd=2004 m:total_value=283500

series e:vx86-ijf7 d:2013-01-01T00:00:00.000Z t:esd_name="North Central ESD" t:type_of_contract=Professional t:contractor_state=OR t:contractor_city=Portland t:award_type="Multi Year Contract" t:award_title="Maintenance & Service Contract" t:contractor_information=TRANE t:contractor_zip=97224 t:original_amt=21815 m:esd=2004 m:total_value=21815

series e:vx86-ijf7 d:2013-01-01T00:00:00.000Z t:esd_name="North Central ESD" t:type_of_contract=Personal t:contractor_state=OR t:contractor_city=Condon t:award_type="One year contract" t:award_title="Personal Services Consulting" t:contractor_information="Rob E Myers" t:contractor_zip=97823 t:original_amt=24996 m:esd=2004 m:total_value=24996
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:amendment p:integer l:AMENDMENT t:dataTypeName=number

metric m:total_value p:double l:"TOTAL VALUE" t:dataTypeName=number

entity e:vx86-ijf7 l:"Contracts: ESD: North Central: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/vx86-ijf7

property e:vx86-ijf7 t:meta.view v:id=vx86-ijf7 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: North Central: Fiscal Year 2013"

property e:vx86-ijf7 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:vx86-ijf7 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name          | _ | award_title                    | award_type          | type_of_contract | contractor_information      | contractor_address          | contractor_city | contractor_state | contractor_zip | contract_date       | original_amt   | amendment | total_value | 
| ==== | ================= | = | ============================== | =================== | ================ | =========================== | =========================== | =============== | ================ | ============== | =================== | ============== | ========= | =========== | 
| 2004 | North Central ESD |   | Bandwidth Services Agreement   | Three year contract | Material         | Frontier TeleNet            | PO Box 171                  | Fossil          | Or               | 97830          | 7/1/10 - 6/30/2013  | 153090         | 130410    | 283500      | 
| 2004 | North Central ESD |   | Maintenance & Service Contract | Multi Year Contract | Professional     | TRANE                       | 7257 SW Kable Lane          | Portland        | OR               | 97224          | 10/01/11 - 09/30/16 | 21815          |           | 21815       | 
| 2004 | North Central ESD |   | Personal Services Consulting   | One year contract   | Personal         | Rob E Myers                 | PO Box 616                  | Condon          | OR               | 97823          | 7/1/12 - 6/30/13    | 24996          |           | 24996       | 
| 2004 | North Central ESD |   | Audit Contract                 | One year contract   | Professional     | Oster Professional Group    | 101 NE First Avenue         | John Day        | Or               | 97845          | 7/1/12 - 6/30/13    | 8520           |           | 8520        | 
| 2004 | North Central ESD |   | OT/PT Services                 | One year contract   | Professional     | Kidsense, Inc.              | 315 Oak Street, Suite 200   | Hood River      | Or               | 97031          | 7/1/12 - 6/30/13    | $70 per hr     |           | 32027       | 
| 2004 | North Central ESD |   | Business Information System    | Price Agreement     | Professional     | Linn Benton Lincoln ESD     | 905 4th Avenue SE           | Albany          | OR               | 97321          | 7/1/12 - 6/30/13    | 16130          |           | 16130       | 
| 2004 | North Central ESD |   | Barracuda Web Filter           | Price Agreement     | Material         | CIPHAUS                     | 13504 NE 84th Suite 103-251 | Vancouver       | WA               | 98682          | 2/1/2012 - 2/1/15   | 18094          |           | 18094       | 
| 2004 | North Central ESD |   | Sophos End User License        | Price Agreement     | Material         | Trebron Company             | 5506 35th Avenue N.E.       | Seattle         | WA               | 98105          | 9/4/08 - 9/24-13    | 18667          |           | 18667       | 
| 2004 | North Central ESD |   | Special Education Management   | Multi Year Contract | Material         | Computer Automation Systems | PO Box 265                  | Lowell          | AR               | 72745          | 7/1/09 - 6/30/14    | 7385           |           | 7385        | 
| 2004 | North Central ESD |   | Copier Maintenance Agreement   | Multi Year Contract | Professional     | Bohn's Printing Inc.        | 308 Union Street            | The Dalles      | OR               | 97058          | 3/31/12 - 3/31/13   | .0103 per copy |           | 385.48      | 
```