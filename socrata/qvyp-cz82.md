# Yearly Pond Values

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/yearly-pond-values) |
| Metadata | [Link](https://data.oregon.gov/api/views/qvyp-cz82) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/qvyp-cz82/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/qvyp-cz82/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | qvyp-cz82 |
| Name | Yearly Pond Values |
| Attribution | Oregon Department of Forestry |
| Category | Natural Resources |
| Tags | pond value, logs, log price, odf, oregon department of forestry |
| Created | 2015-05-31T23:02:56Z |
| Publication Date | 2015-06-11T04:51:13Z |

## Description

Log price information. Domestically processed logs (delivered to a mill; "Pond Value")

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       |                | year             | Year             | number    | number      |
| No       |                | quarter          | Quarter          | text      | text        |
| Yes      | series tag     | region           | Region           | text      | text        |
| Yes      | series tag     | species          | Species          | text      | text        |
| Yes      | series tag     | grade            | Grade            | text      | text        |
| Yes      | numeric metric | pond_value       | Pond value       | money     | money       |
| Yes      | series tag     | number_of_quotes | Number of quotes | text      | text        |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = year,quarter
```

## Data Commands

```ls
series e:qvyp-cz82 d:2015-01-01T00:00:00.000Z t:region="REGION 1 - NORTHWEST OREGON & WILLAMETTE" t:number_of_quotes=12 t:species="DOUGLAS FIR" t:grade=1P m:pond_value=615

series e:qvyp-cz82 d:2015-01-01T00:00:00.000Z t:region="REGION 1 - NORTHWEST OREGON & WILLAMETTE" t:number_of_quotes=12 t:species="DOUGLAS FIR" t:grade=2P m:pond_value=615

series e:qvyp-cz82 d:2015-01-01T00:00:00.000Z t:region="REGION 1 - NORTHWEST OREGON & WILLAMETTE" t:number_of_quotes=12 t:species="DOUGLAS FIR" t:grade="3P &Btr" m:pond_value=615
```

## Meta Commands

```ls
metric m:pond_value p:double l:"Pond value" t:dataTypeName=money

entity e:qvyp-cz82 l:"Yearly Pond Values" t:attribution="Oregon Department of Forestry" t:url=https://data.oregon.gov/api/views/qvyp-cz82

property e:qvyp-cz82 t:meta.view v:id=qvyp-cz82 v:category="Natural Resources" v:attributionLink=http://oregon.gov/ODF v:averageRating=0 v:name="Yearly Pond Values" v:attribution="Oregon Department of Forestry"

property e:qvyp-cz82 t:meta.view.owner v:id=tpuj-u6fw v:screenName="Katherine LeaMaster" v:displayName="Katherine LeaMaster"

property e:qvyp-cz82 t:meta.view.tableauthor v:id=tpuj-u6fw v:screenName="Katherine LeaMaster" v:roleName=editor v:displayName="Katherine LeaMaster"
```

## Top Records

```ls
| year | quarter          | region                                   | species     | grade   | pond_value | number_of_quotes | 
| ==== | ================ | ======================================== | =========== | ======= | ========== | ================ | 
| 2015 | 1ST QUARTER 2015 | REGION 1 - NORTHWEST OREGON & WILLAMETTE | DOUGLAS FIR | 1P      | 615.00     | 12               | 
| 2015 | 1ST QUARTER 2015 | REGION 1 - NORTHWEST OREGON & WILLAMETTE | DOUGLAS FIR | 2P      | 615.00     | 12               | 
| 2015 | 1ST QUARTER 2015 | REGION 1 - NORTHWEST OREGON & WILLAMETTE | DOUGLAS FIR | 3P &Btr | 615.00     | 12               | 
| 2015 | 1ST QUARTER 2015 | REGION 1 - NORTHWEST OREGON & WILLAMETTE | DOUGLAS FIR | SM      | 610.00     | 12               | 
| 2015 | 1ST QUARTER 2015 | REGION 1 - NORTHWEST OREGON & WILLAMETTE | DOUGLAS FIR | (5-7")  | 525.00     | 17               | 
| 2015 | 1ST QUARTER 2015 | REGION 1 - NORTHWEST OREGON & WILLAMETTE | DOUGLAS FIR | 4S      | 525.00     | 17               | 
| 2015 | 1ST QUARTER 2015 | REGION 1 - NORTHWEST OREGON & WILLAMETTE | DOUGLAS FIR | 3S      | 550.00     | 18               | 
| 2015 | 1ST QUARTER 2015 | REGION 1 - NORTHWEST OREGON & WILLAMETTE | DOUGLAS FIR | (8-11") | 575.00     | 18               | 
| 2015 | 1ST QUARTER 2015 | REGION 1 - NORTHWEST OREGON & WILLAMETTE | DOUGLAS FIR | 2S      | 595.00     | 20               | 
| 2015 | 1ST QUARTER 2015 | REGION 1 - NORTHWEST OREGON & WILLAMETTE | DOUGLAS FIR | SC      | 200.00     | 5 or less        | 
```