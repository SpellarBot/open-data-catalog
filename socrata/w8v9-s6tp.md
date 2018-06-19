# Contracts: ESD: InterMountain: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-intermountain-fiscal-year-2013-72060) |
| Metadata | [Link](https://data.oregon.gov/api/views/w8v9-s6tp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/w8v9-s6tp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/w8v9-s6tp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | w8v9-s6tp |
| Name | Contracts: ESD: InterMountain: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, esd, inter mountain, fiscal year 2013 |
| Created | 2013-10-31T18:13:40Z |
| Publication Date | 2013-10-31T18:23:19Z |

## Description

Contracts for InterMountain ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| Yes      | numeric metric | esd                                      | ESD #                                    | number    | number      |
| Yes      | series tag     | esd_name                                 | ESD NAME                                 | text      | text        |
| Yes      | series tag     | award_number                             | AWARD NUMBER                             | text      | text        |
| Yes      | series tag     | award_title                              | AWARD TITLE                              | text      | text        |
| Yes      | series tag     | award_type                               | AWARD TYPE                               | text      | text        |
| Yes      | series tag     | type_of_contract_subcontract             | TYPE OF CONTRACT/SUBCONTRACT             | text      | text        |
| Yes      | series tag     | contractor_information                   | CONTRACTOR INFORMATION                   | text      | text        |
| No       |                | contractor_address                       | CONTRACTOR ADDRESS                       | text      | text        |
| Yes      | series tag     | contrator_city                           | CONTRATOR CITY                           | text      | text        |
| Yes      | series tag     | contractor_state                         | CONTRACTOR STATE                         | text      | text        |
| No       |                | original_start_amendment_expiration_date | ORIGINAL START/AMENDMENT/EXPIRATION DATE | text      | text        |
| Yes      | series tag     | original_award_value                     | ORIGINAL AWARD VALUE                     | text      | text        |
| Yes      | numeric metric | amendment_value                          | AMENDMENT VALUE                          | number    | number      |
| Yes      | series tag     | total_award_value                        | TOTAL AWARD VALUE                        | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contractor_address,original_start_amendment_expiration_date
```

## Data Commands

```ls
series e:w8v9-s6tp d:2013-01-01T00:00:00.000Z t:esd_name="InterMountain ESD" t:type_of_contract_subcontract=Material t:total_award_value=21.58/mo. t:award_type="Price Agreement" t:award_title="IR1023IF Copier 7143" t:contractor_information=Canon t:original_award_value=$21.58/mo m:esd=2200

series e:w8v9-s6tp d:2013-01-01T00:00:00.000Z t:esd_name="InterMountain ESD" t:contrator_city=Pendleton t:contractor_state=OR t:type_of_contract_subcontract="Personal Services" t:total_award_value=$40/hour t:award_type="Personal Services" t:award_title="Artist in Residence" t:contractor_information="Pendleton Center for the Arts" t:original_award_value=$40/hour m:esd=2200

series e:w8v9-s6tp d:2013-01-01T00:00:00.000Z t:esd_name="InterMountain ESD" t:contrator_city=Enterprise t:contractor_state=OR t:type_of_contract_subcontract=Professional t:total_award_value=$70/hour t:award_type="Trade Services" t:award_title="Physical Therapy" t:contractor_information="Wallowa County Health District" t:original_award_value=$70/hour m:esd=2200
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:amendment_value p:float l:"AMENDMENT VALUE" t:dataTypeName=number

entity e:w8v9-s6tp l:"Contracts: ESD: InterMountain: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/w8v9-s6tp

property e:w8v9-s6tp t:meta.view v:id=w8v9-s6tp v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: InterMountain: Fiscal Year 2013"

property e:w8v9-s6tp t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:w8v9-s6tp t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name          | award_number | award_title                 | award_type        | type_of_contract_subcontract | contractor_information         | contractor_address              | contrator_city | contractor_state | original_start_amendment_expiration_date | original_award_value | amendment_value | total_award_value | 
| ==== | ================= | ============ | =========================== | ================= | ============================ | ============================== | =============================== | ============== | ================ | ======================================== | ==================== | =============== | ================= | 
| 2200 | InterMountain ESD |              | IR1023IF Copier 7143        | Price Agreement   | Material                     | Canon                          |                                 |                |                  | 1/10/2008 1/10/2013                      | $21.58/mo            |                 | 21.58/mo.         | 
| 2200 | InterMountain ESD |              | Artist in Residence         | Personal Services | Personal Services            | Pendleton Center for the Arts  | 214 North Main                  | Pendleton      | OR               | 2/4/2013 6/14/2013                       | $40/hour             |                 | $40/hour          | 
| 2200 | InterMountain ESD |              | Physical Therapy            | Trade Services    | Professional                 | Wallowa County Health District | 601 Medical Parkway             | Enterprise     | OR               | 6/19/2012 6/30/2013                      | $70/hour             |                 | $70/hour          | 
| 2200 | InterMountain ESD |              | TA4500                      | Price Agreement   | Material                     | Kyocera                        | 14101 Alton Parkway             | Irvine         | CA               | 8/16/2012 8/16/2017                      | $140.25/mo           |                 | $140.25/mo        | 
| 2200 | InterMountain ESD |              | BizHUB282 Copier 3822 Lease | Price Agreement   | Material                     | De Lage Landen Public Finance  | 1111 Eagle School Road          | Wayne          | PA               | 11/23/2010 11/23/2013                    | $150.19/mo           |                 | $150.19/mo        | 
| 2200 | InterMountain ESD |              | ASP Program                 | Personal Services | Personal Services            | North Powder SD                | PO Box 10                       | North Powder   | OR               | 11/26/2012 6/30/2013                     | Up to $41,244        |                 | Up to $41,244     | 
| 2200 | InterMountain ESD |              | Facility Lease              | Price Agreement   | Professional                 | Union County                   | 1108 K Avenue                   | La Grande      | OR               | 6/14/2011 6/30/2016                      | $9,153.48            |                 | $9,153.48         | 
| 2200 | InterMountain ESD |              | BizHUB362 Copier 3349 Lease | Price Agreement   | Material                     | De Lage Landen Public Finance  | 1111 Eagle School Road          | Wayne          | PA               | 11/23/2010 11/23/2013                    | $170.79/mo           |                 | $170.79/mo        | 
| 2200 | InterMountain ESD |              | Web-hosted Policies         | Price Agreement   | Professional                 | OSBA                           | 1201 Court Street NE, Suite 400 | Salem          | OR               | 7/1/2012 6/30/2013                       | $995.00              |                 | $995.00           | 
| 2200 | InterMountain ESD | 1452327      | BizHUB423 Copier 5837 Lease | Price Agreement   | Material                     | De Lage Landen Public Finance  | 1111 Eagle School Road          | Wayne          | PA               | 3/11/2011 3/11/2016                      | $100.37/mo           |                 | $100.37/mo        | 
```