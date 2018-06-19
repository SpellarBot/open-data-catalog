# TIF Funding Sources and Uses by TIF, Fiscal Year, and Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tif-funding-sources-and-uses-by-tif-fiscal-year-and-type-a3f3c) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/pner-h2in) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/pner-h2in/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/pner-h2in/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | pner-h2in |
| Name | TIF Funding Sources and Uses by TIF, Fiscal Year, and Type |
| Attribution | City of Chicago - Office of Budget and Management |
| Category | Community & Economic Development |
| Tags | tif, revenues, expenditures |
| Created | 2012-06-21T15:39:49Z |
| Publication Date | 2015-09-29T16:36:16Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name         | Data Type | Render Type |
| ======== | ============== | =========== | ============ | ========= | =========== |
| No       | time           | :updated_at | updated_at   | meta_data | meta_data   |
| No       |                | fy          | Fiscal Year  | number    | number      |
| Yes      | series tag     | tif_number  | TIF Number   | text      | text        |
| Yes      | series tag     | tifnamel    | TIF District | text      | text        |
| Yes      | series tag     | type        | Type         | text      | text        |
| Yes      | series tag     | afa_group   | Activity     | text      | text        |
| Yes      | numeric metric | amount      | Amount       | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fy
```

## Data Commands

```ls
series e:pner-h2in d:2015-09-29T09:33:58.000Z t:tifnamel=105th/Vincennes t:type=Revenues t:afa_group="Tax revenue" t:tif_number=T-111 m:amount=0

series e:pner-h2in d:2015-09-29T09:33:58.000Z t:tifnamel=105th/Vincennes t:type=Revenues t:afa_group="Tax revenue" t:tif_number=T-111 m:amount=175776

series e:pner-h2in d:2015-09-29T09:33:58.000Z t:tifnamel=105th/Vincennes t:type=Revenues t:afa_group="Tax revenue" t:tif_number=T-111 m:amount=130723
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:pner-h2in l:"TIF Funding Sources and Uses by TIF, Fiscal Year, and Type" t:attribution="City of Chicago - Office of Budget and Management" t:url=https://data.cityofchicago.org/api/views/pner-h2in

property e:pner-h2in t:meta.view v:id=pner-h2in v:category="Community & Economic Development" v:averageRating=0 v:name="TIF Funding Sources and Uses by TIF, Fiscal Year, and Type" v:attribution="City of Chicago - Office of Budget and Management"

property e:pner-h2in t:meta.view.owner v:id=7ek2-d4pb v:screenName="David Miller" v:displayName="David Miller"

property e:pner-h2in t:meta.view.tableauthor v:id=7ek2-d4pb v:screenName="David Miller" v:roleName=editor v:displayName="David Miller"
```

## Top Records

```ls
| :updated_at | fy   | tif_number | tifnamel        | type     | afa_group   | amount    | 
| =========== | ==== | ========== | =============== | ======== | =========== | ========= | 
| 1443519238  | 2002 | T-111      | 105th/Vincennes | Revenues | Tax revenue | 0.00      | 
| 1443519238  | 2009 | T-111      | 105th/Vincennes | Revenues | Tax revenue | 175776.00 | 
| 1443519238  | 2006 | T-111      | 105th/Vincennes | Revenues | Tax revenue | 130723.00 | 
| 1443519238  | 2001 | T-111      | 105th/Vincennes | Revenues | Tax revenue | 0.00      | 
| 1443519238  | 2007 | T-111      | 105th/Vincennes | Revenues | Tax revenue | 169551.00 | 
| 1443519238  | 2004 | T-111      | 105th/Vincennes | Revenues | Tax revenue | 28035.00  | 
| 1443519238  | 2005 | T-111      | 105th/Vincennes | Revenues | Tax revenue | 141074.00 | 
| 1443519238  | 2003 | T-111      | 105th/Vincennes | Revenues | Tax revenue | 8566.00   | 
| 1443519238  | 2008 | T-111      | 105th/Vincennes | Revenues | Tax revenue | 234905.00 | 
| 1443519238  | 2012 | T-111      | 105th/Vincennes | Revenues | Tax revenue | 352585.00 | 
```