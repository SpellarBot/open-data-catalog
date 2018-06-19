# Contracts: ESD: Malheur: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-malheur-fiscal-year-2013-161b4) |
| Metadata | [Link](https://data.oregon.gov/api/views/en2b-yqq5) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/en2b-yqq5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/en2b-yqq5/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | en2b-yqq5 |
| Name | Contracts: ESD: Malheur: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, malheur esd contracts, malheur contracts, malheur educational service district |
| Created | 2013-12-23T15:13:36Z |
| Publication Date | 2013-12-23T15:16:52Z |

## Description

Contracts for Malheur Educational Service District for Fiscal Year 2013.

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                          | Data Type | Render Type |
| ======== | ============== | ============================================= | ============================================= | ========= | =========== |
| Yes      | numeric metric | esd                                           | ESD #                                         | number    | number      |
| Yes      | series tag     | esd_name                                      | ESD NAME                                      | text      | text        |
| Yes      | series tag     | award_number_w_amendments                     | AWARD NUMBER W/AMENDMENTS                     | text      | text        |
| Yes      | series tag     | award_title                                   | AWARD TITLE                                   | text      | text        |
| Yes      | series tag     | award_type                                    | AWARD TYPE                                    | text      | text        |
| Yes      | series tag     | contractor_information                        | CONTRACTOR INFORMATION                        | text      | text        |
| No       |                | original_state_amendment_date_expiration_date | ORIGINAL STATE/AMENDMENT DATE/EXPIRATION DATE | text      | text        |
| Yes      | numeric metric | original_award_value                          | ORIGINAL AWARD VALUE                          | money     | money       |
| Yes      | numeric metric | amendment_value                               | AMENDMENT VALUE                               | money     | money       |
| Yes      | numeric metric | total_award_value_a_amendments                | TOTAL AWARD VALUE A/ AMENDMENTS               | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = original_state_amendment_date_expiration_date
```

## Data Commands

```ls
series e:en2b-yqq5 d:2013-01-01T00:00:00.000Z t:esd_name="Malheur ESD Rgn 14" t:award_type="Personal Services" t:award_title="Custodial Services" t:contractor_information="H&S Services" m:total_award_value_a_amendments=13200 m:amendment_value=0 m:esd=2106 m:original_award_value=13200

series e:en2b-yqq5 d:2013-01-01T00:00:00.000Z t:esd_name="Malheur ESD Rgn 14" t:award_type="Personal Services" t:award_title="Custodial Services" t:contractor_information="TC Rau" m:total_award_value_a_amendments=2250 m:amendment_value=0 m:esd=2106 m:original_award_value=2250

series e:en2b-yqq5 d:2013-01-01T00:00:00.000Z t:esd_name="Malheur ESD Rgn 14" t:award_type="Intergovernmental Services Agreement" t:award_title="E-Rate Schools & Libraries Div" t:contractor_information="InterMountain ESD" m:total_award_value_a_amendments=0 m:amendment_value=0 m:esd=2106 m:original_award_value=0
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:original_award_value p:double l:"ORIGINAL AWARD VALUE" t:dataTypeName=money

metric m:amendment_value p:double l:"AMENDMENT VALUE" t:dataTypeName=money

metric m:total_award_value_a_amendments p:double l:"TOTAL AWARD VALUE A/ AMENDMENTS" t:dataTypeName=money

entity e:en2b-yqq5 l:"Contracts: ESD: Malheur: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/en2b-yqq5

property e:en2b-yqq5 t:meta.view v:id=en2b-yqq5 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Malheur: Fiscal Year 2013"

property e:en2b-yqq5 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:en2b-yqq5 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name           | award_number_w_amendments | award_title                      | award_type                           | contractor_information | original_state_amendment_date_expiration_date | original_award_value | amendment_value | total_award_value_a_amendments | 
| ==== | ================== | ========================= | ================================ | ==================================== | ====================== | ============================================= | ==================== | =============== | ============================== | 
| 2106 | Malheur ESD Rgn 14 |                           | Custodial Services               | Personal Services                    | H&S Services           | 10/1/2008 - until changed                     | 13200.00             | 0.00            | 13200.00                       | 
| 2106 | Malheur ESD Rgn 14 |                           | Custodial Services               | Personal Services                    | TC Rau                 | 7/1/13-until changed                          | 2250.00              | 0.00            | 2250.00                        | 
| 2106 | Malheur ESD Rgn 14 |                           | E-Rate Schools & Libraries Div   | Intergovernmental Services Agreement | InterMountain ESD      | 7/1/2013 - 6/30/2016                          | 0.00                 | 0.00            | 0.00                           | 
| 2106 | Malheur ESD Rgn 14 |                           | Financial Software Support-OSAS  | Intergovernmental Services Agreement | South Coast ESD        | 7/1/2013 - 6/30/2014                          | 1500.00              | 0.00            | 1500.00                        | 
| 2106 | Malheur ESD Rgn 14 |                           | IDEA Consortium                  | Interagency Agreement                | Vale SD 84             | 7/1/2013 - 6/30/2014                          | 50000.00             | 0.00            | 50000.00                       | 
| 2106 | Malheur ESD Rgn 14 |                           | Legal Services                   | Intergovernmental Services Agreement | High Dessert ESD       | 7/1/2011 - in effect until changed            | 4500.00              | 0.00            | 4500.00                        | 
| 2106 | Malheur ESD Rgn 14 |                           | Physical Therapy Services        | Personal Services                    | Oakes, Jean            | 8/16/2013 - 5/29/2014                         | 40000.00             | 0.00            | 43776.00                       | 
| 2106 | Malheur ESD Rgn 14 |                           | Physical Therapy Services-Summer | Personal Services                    | Oakes, Jean            | 6/4/2013 - 8/10/2013                          | 4800.00              | 0.00            | 5600.00                        | 
| 2106 | Malheur ESD Rgn 14 |                           | Regional Program                 | Intergovernmental Services Agreement | InterMountain ESD      | 7/1/2013 - 6/30/2015                          | 180930.00            | 0.00            | 180930.00                      | 
| 2106 | Malheur ESD Rgn 14 |                           | Rental Space                     | Lease Agreement                      | Nyssa SD 26            | 6/1/2013 - 06/30/2014                         | 1500.00              | 0.00            | 1500.00                        | 
```