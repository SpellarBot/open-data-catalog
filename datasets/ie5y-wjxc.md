# Contracts: ESD: Malheur: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-malheur-fiscal-year-2014-93c3f) |
| Metadata | [Link](https://data.oregon.gov/api/views/ie5y-wjxc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ie5y-wjxc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ie5y-wjxc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ie5y-wjxc |
| Name | Contracts: ESD: Malheur: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | contracts, malheur esd contracts, malheur contracts, malheur educational service district |
| Created | 2014-12-15T08:19:52Z |
| Publication Date | 2014-12-29T05:57:14Z |

## Description

Contracts for Malheur Educational Service District for Fiscal Year 2014.

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
| Yes      | numeric metric | total_award_value                             | TOTAL AWARD VALUE                             | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = original_state_amendment_date_expiration_date
```

## Data Commands

```ls
series e:ie5y-wjxc d:2014-01-01T00:00:00.000Z t:esd_name="Malheur ESD Rgn 14" t:award_type="Personal Services" t:award_title=Audiologist t:contractor_information="Elks Hearing & Balance Center" m:amendment_value=0 m:total_award_value=6800 m:esd=2106 m:original_award_value=6800

series e:ie5y-wjxc d:2014-01-01T00:00:00.000Z t:esd_name="Malheur ESD Rgn 14" t:award_type="Personal Services" t:award_title="Custodial Services" t:contractor_information="H&S Services" m:amendment_value=0 m:total_award_value=6720 m:esd=2106 m:original_award_value=6720

series e:ie5y-wjxc d:2014-01-01T00:00:00.000Z t:esd_name="Malheur ESD Rgn 14" t:award_type="Personal Services" t:award_title="Custodial Services" t:contractor_information=Quick-n-Clean m:amendment_value=0 m:total_award_value=3256 m:esd=2016 m:original_award_value=3256
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:original_award_value p:double l:"ORIGINAL AWARD VALUE" t:dataTypeName=money

metric m:amendment_value p:double l:"AMENDMENT VALUE" t:dataTypeName=money

metric m:total_award_value p:double l:"TOTAL AWARD VALUE" t:dataTypeName=money

entity e:ie5y-wjxc l:"Contracts: ESD: Malheur: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/ie5y-wjxc

property e:ie5y-wjxc t:meta.view v:id=ie5y-wjxc v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Malheur: Fiscal Year 2014"

property e:ie5y-wjxc t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ie5y-wjxc t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name           | award_number_w_amendments | award_title                      | award_type                           | contractor_information        | original_state_amendment_date_expiration_date | original_award_value | amendment_value | total_award_value | 
| ==== | ================== | ========================= | ================================ | ==================================== | ============================= | ============================================= | ==================== | =============== | ================= | 
| 2106 | Malheur ESD Rgn 14 |                           | Audiologist                      | Personal Services                    | Elks Hearing & Balance Center | 8/1/2010 - 5/23/14                            | 6800.00              | 0.00            | 6800.00           | 
| 2106 | Malheur ESD Rgn 14 |                           | Custodial Services               | Personal Services                    | H&S Services                  | 7/1/2013 - 2/28/2014                          | 6720.00              | 0.00            | 6720.00           | 
| 2016 | Malheur ESD Rgn 14 |                           | Custodial Services               | Personal Services                    | Quick-n-Clean                 | 3/1/2014 - 6/30/2014                          | 3256.00              | 0.00            | 3256.00           | 
| 2106 | Malheur ESD Rgn 14 |                           | E-Rate Schools & Libraries Div   | Intergovernmental Services Agreement | InterMountain ESD             | 7/1/2013 - 6/30/2014                          | 0.00                 | 0.00            | 0.00              | 
| 2106 | Malheur ESD Rgn 14 |                           | Financial Software Support-OSAS  | Intergovernmental Services Agreement | South Coast ESD               | 7/1/2013 - 6/30/2014                          | 1500.00              | 0.00            | 1500.00           | 
| 2106 | Malheur ESD Rgn 14 |                           | IDEA Consortium                  | Interagency Agreement                | Vale SD 84                    | 7/1/2013 - 6/30/2014                          | 50000.00             | 0.00            | 50000.00          | 
| 2106 | Malheur ESD Rgn 14 |                           | Legal Services                   | Intergovernmental Services Agreement | High Dessert ESD              | 7/1/2011 - in effect until changed            | 4500.00              | 0.00            | 4500.00           | 
| 2106 | Malheur ESD Rgn 14 |                           | Physical Therapy Services        | Personal Services                    | Oakes, Jean                   | 8/16/2013 - 5/29/2014                         | 40000.00             | 0.00            | 40000.00          | 
| 2106 | Malheur ESD Rgn 14 |                           | Physical Therapy Services-Summer | Personal Services                    | Oakes, Jean                   | 6/4/2013 - 8/10/2013                          | 4800.00              | 0.00            | 4800.00           | 
| 2106 | Malheur ESD Rgn 14 |                           | Regional Program                 | Intergovernmental Services Agreement | InterMountain ESD             | 7/1/2013- 6/30/2014                           | 170074.20            | 0.00            | 170074.20         | 
```