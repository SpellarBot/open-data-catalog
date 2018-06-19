# Selected Trend Table from Health, United States, 2011. Vaccination coverage among children 19 - 35 months of age for selected diseases, by race, Hispanic origin, poverty level, and location of resi...

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/selected-trend-table-from-health-united-states-2011-vaccination-coverage-among-children-19) |
| Metadata | [Link](https://data.cdc.gov/api/views/nkri-ptxd) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/nkri-ptxd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/nkri-ptxd/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | nkri-ptxd |
| Name | Selected Trend Table from Health, United States, 2011. Vaccination coverage among children 19 - 35 months of age for selected diseases, by race, Hispanic origin, poverty level, and location of resi... |
| Attribution | Health, United States |
| Category | Health Statistics |
| Tags | hus, vaccination, children |
| Created | 2013-07-29T20:22:45Z |
| Publication Date | 2013-08-14T19:34:58Z |

## Description

Health, United States is an annual report on trends in health statistics, find more information at http://www.cdc.gov/nchs/hus.htm.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | year             | Year             | number    | number      |
| Yes      | series tag     | vaccination      | Vaccination      | text      | text        |
| Yes      | numeric metric | vaccination_flag | Vaccination flag | number    | number      |
| Yes      | series tag     | category         | Category         | text      | text        |
| Yes      | numeric metric | category_flag    | Category flag    | number    | number      |
| Yes      | series tag     | group            | Group            | text      | text        |
| Yes      | numeric metric | group_flag       | Group flag       | number    | number      |
| Yes      | numeric metric | estimate         | Estimate         | number    | number      |
| No       |                | estimate_flag    | Estimate flag    | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = estimate_flag
```

## Data Commands

```ls
series e:nkri-ptxd d:2009-01-01T00:00:00.000Z t:category="Race and Hispanic origin" t:group=All t:vaccination="Combined series (4:3:1:4:3:1:4)" m:vaccination_flag=4 m:category_flag=1 m:estimate=44

series e:nkri-ptxd d:2007-01-01T00:00:00.000Z t:category="Race and Hispanic origin" t:group=All t:vaccination="Combined series (4:3:1:3:3:1:4)" m:vaccination_flag=5 m:category_flag=1 m:estimate=67

series e:nkri-ptxd d:2008-01-01T00:00:00.000Z t:category="Race and Hispanic origin" t:group=All t:vaccination="Combined series (4:3:1:3:3:1:4)" m:vaccination_flag=5 m:category_flag=1 m:estimate=68
```

## Meta Commands

```ls
metric m:vaccination_flag p:integer l:"Vaccination flag" t:dataTypeName=number

metric m:category_flag p:integer l:"Category flag" t:dataTypeName=number

metric m:group_flag p:integer l:"Group flag" t:dataTypeName=number

metric m:estimate p:float l:Estimate t:dataTypeName=number

entity e:nkri-ptxd l:"Selected Trend Table from Health, United States, 2011. Vaccination coverage among children 19 - 35 months of age for selected diseases, by race, Hispanic origin, poverty level, and location of residence in metropolitan statistical area: United States, sel" t:attribution="Health, United States" t:url=https://data.cdc.gov/api/views/nkri-ptxd

property e:nkri-ptxd t:meta.view v:id=nkri-ptxd v:category="Health Statistics" v:attributionLink=http://www.cdc.gov/nchs/hus.htm v:averageRating=0 v:name="Selected Trend Table from Health, United States, 2011. Vaccination coverage among children 19 - 35 months of age for selected diseases, by race, Hispanic origin, poverty level, and location of residence in metropolitan statistical area: United States, sel" v:attribution="Health, United States"

property e:nkri-ptxd t:meta.view.owner v:id=vr5q-rutf v:screenName=SFranco v:displayName=SFranco

property e:nkri-ptxd t:meta.view.tableauthor v:id=vr5q-rutf v:screenName=SFranco v:roleName=editor v:displayName=SFranco

property e:nkri-ptxd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| year | vaccination                     | vaccination_flag | category                 | category_flag | group | group_flag | estimate | estimate_flag | 
| ==== | =============================== | ================ | ======================== | ============= | ===== | ========== | ======== | ============= | 
| 2009 | Combined series (4:3:1:4:3:1:4) | 4                | Race and Hispanic origin | 1             | All   |            | 44.0     |               | 
| 2007 | Combined series (4:3:1:3:3:1:4) | 5                | Race and Hispanic origin | 1             | All   |            | 67.0     |               | 
| 2008 | Combined series (4:3:1:3:3:1:4) | 5                | Race and Hispanic origin | 1             | All   |            | 68.0     |               | 
| 2009 | Combined series (4:3:1:3:3:1:4) | 5                | Race and Hispanic origin | 1             | All   |            | 64.0     |               | 
| 2002 | Combined series (4:3:1:3:3:1)   | 6                | Race and Hispanic origin | 1             | All   |            | 66.0     |               | 
| 2003 | Combined series (4:3:1:3:3:1)   | 6                | Race and Hispanic origin | 1             | All   |            | 73.0     |               | 
| 2004 | Combined series (4:3:1:3:3:1)   | 6                | Race and Hispanic origin | 1             | All   |            | 76.0     |               | 
| 2005 | Combined series (4:3:1:3:3:1)   | 6                | Race and Hispanic origin | 1             | All   |            | 76.0     |               | 
| 2006 | Combined series (4:3:1:3:3:1)   | 6                | Race and Hispanic origin | 1             | All   |            | 77.0     |               | 
| 2007 | Combined series (4:3:1:3:3:1)   | 6                | Race and Hispanic origin | 1             | All   |            | 77.0     |               | 
```