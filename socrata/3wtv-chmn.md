# AGR-EAB Compliant Vendors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/agr-eab-compliant-vendors-143d4) |
| Metadata | [Link](https://data.illinois.gov/api/views/3wtv-chmn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/3wtv-chmn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/3wtv-chmn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 3wtv-chmn |
| Name | AGR-EAB Compliant Vendors |
| Category | Environment |
| Tags | emerald ash borer, eab |
| Created | 2012-02-03T16:23:19Z |
| Publication Date | 2012-02-03T18:51:17Z |

## Description

Emerald Ash Borer Complaint Vendors

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | compliance_number | Compliance Number | text      | text        |
| Yes      | series tag  | company_name      | Company Name      | text      | text        |
| Yes      | series tag  | telephone         | Telephone         | text      | text        |
| Yes      | series tag  | county            | County            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3wtv-chmn d:2012-02-03T09:19:25.000Z t:county=Cook t:company_name="Angelo's Landscaping" t:compliance_number=031-096 m:row_number.3wtv-chmn=1

series e:3wtv-chmn d:2012-02-03T09:19:28.000Z t:county=Will t:company_name="J. Brtis Landscape Co" t:compliance_number=197-126 t:telephone=815-806-4900 m:row_number.3wtv-chmn=2

series e:3wtv-chmn d:2012-02-03T09:19:28.000Z t:county=Cook t:company_name="J.F. Campion Tree Care" t:compliance_number=031-085 t:telephone=847-345-7507 m:row_number.3wtv-chmn=3
```

## Meta Commands

```ls
metric m:row_number.3wtv-chmn p:long l:"Row Number"

entity e:3wtv-chmn l:"AGR-EAB Compliant Vendors" t:url=https://data.illinois.gov/api/views/3wtv-chmn

property e:3wtv-chmn t:meta.view v:id=3wtv-chmn v:category=Environment v:averageRating=0 v:name="AGR-EAB Compliant Vendors"

property e:3wtv-chmn t:meta.view.owner v:id=zuaf-d327 v:screenName=mknepler v:displayName=mknepler

property e:3wtv-chmn t:meta.view.tableauthor v:id=zuaf-d327 v:screenName=mknepler v:roleName=publisher v:displayName=mknepler
```

## Top Records

```ls
| :updated_at | compliance_number | company_name                    | telephone    | county    | 
| =========== | ================= | =============================== | ============ | ========= | 
| 1328260765  | 031-096           | Angelo's Landscaping            |              | Cook      | 
| 1328260768  | 197-126           | J. Brtis Landscape Co           | 815-806-4900 | Will      | 
| 1328260768  | 031-085           | J.F. Campion Tree Care          | 847-345-7507 | Cook      | 
| 1328260770  | 926-002           | TruGreen                        | 616-534-1700 |           | 
| 1328260770  | 043-101           | Village of Bartlett             |              | Dupage    | 
| 1328260770  | 031-148           | Village of Hanover Park         | 630-372-4462 | Cook      | 
| 1328260802  | 195-002           | Younger's Tree Care             | 815-548-9402 | Whiteside | 
| 1328260802  | 037-004           | Hub Tures & Sons Nursery Inc.   | 815-784-2286 | Dekalb    | 
| 1328260802  | 197-060           | Lockport Township Park District | 815-838-5016 | Will      | 
| 1328260802  | 031-055           | Apex Landscaping Inc.           | 847-827-0050 | Cook      | 
```