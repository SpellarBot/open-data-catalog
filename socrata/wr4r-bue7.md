# Fair Student Funding Budget Detail 1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fair-student-funding-budget-detail-1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wr4r-bue7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wr4r-bue7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wr4r-bue7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wr4r-bue7 |
| Name | Fair Student Funding Budget Detail 1 |
| Attribution | Department of Education (DOE) |
| Category | City Government |
| Created | 2015-10-19T18:50:29Z |
| Publication Date | 2015-10-19T18:58:20Z |

## Description

Fair Student Funding Budget Detail FY 2015 - Part I This detail data contains has one row for each school for each of the weights that comprise the Fair Student Funding Formula (Grade Weight, Need Weights, and Portfolio Weights).
Click Here for further information- http://schools.nyc.gov/offices/d_chanc_oper/budget/dbor/allocationmemo/fy14_15/Fair_School_Funding_FY2015.html

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                      | Data Type | Render Type |
| ======== | ============== | ====================================== | ========================================= | ========= | =========== |
| Yes      | time           | fiscal_year                            | Fiscal_Year                               | number    | text        |
| Yes      | series tag     | location                               | Location                                  | text      | text        |
| Yes      | numeric metric | print_order                            | Print_Order                               | number    | number      |
| Yes      | series tag     | attribute_reference                    | Attribute_Reference                       | text      | text        |
| Yes      | series tag     | attribute_category                     | Attribute_Category                        | text      | text        |
| Yes      | series tag     | need_name                              | Need_Name                                 | text      | text        |
| Yes      | series tag     | category                               | Category                                  | text      | text        |
| Yes      | series tag     | sub_category                           | Sub_Category                              | text      | text        |
| Yes      | numeric metric | column_l_fy15_weight                   | Column L: FY15 Weight                     | number    | number      |
| Yes      | numeric metric | column_m_fy15_per_capita_no_ats_growth | Column M: FY15 Per Capita (no ATS growth) | money     | money       |
| Yes      | numeric metric | column_n_fy14_actual_registers         | Column N: FY14 Actual Registers           | number    | number      |
| Yes      | numeric metric | column_o_projected_register            | Column O: Projected Register              | number    | number      |
| Yes      | numeric metric | column_p_projected_formula             | Column P: Projected Formula               | money     | money       |
| Yes      | numeric metric | column_q_register_change               | Column Q: Register Change                 | number    | number      |
| Yes      | numeric metric | column_r_register_dollar_change        | Column R: Register Dollar Change          | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wr4r-bue7 d:2015-01-01T00:00:00.000Z t:attribute_category="Grade Weights" t:need_name=NA t:sub_category=NA t:location=Q184 t:attribute_reference=ATTRIBUTE_01 t:category=K-5 m:column_l_fy15_weight=1 m:column_o_projected_register=462 m:column_q_register_change=-8 m:column_r_register_dollar_change=-32980.37 m:column_m_fy15_per_capita_no_ats_growth=4122.55 m:print_order=2 m:column_p_projected_formula=1904616.09 m:column_n_fy14_actual_registers=470

series e:wr4r-bue7 d:2015-01-01T00:00:00.000Z t:attribute_category="Grade Weights" t:need_name=NA t:sub_category=NA t:location=Q214 t:attribute_reference=ATTRIBUTE_01 t:category=K-5 m:column_l_fy15_weight=1 m:column_o_projected_register=490 m:column_q_register_change=51 m:column_r_register_dollar_change=210249.83 m:column_m_fy15_per_capita_no_ats_growth=4122.55 m:print_order=2 m:column_p_projected_formula=2020047.37 m:column_n_fy14_actual_registers=439

series e:wr4r-bue7 d:2015-01-01T00:00:00.000Z t:attribute_category="Grade Weights" t:need_name=NA t:sub_category=NA t:location=Q209 t:attribute_reference=ATTRIBUTE_01 t:category=K-5 m:column_l_fy15_weight=1 m:column_o_projected_register=596 m:column_q_register_change=-20 m:column_r_register_dollar_change=-82450.91 m:column_m_fy15_per_capita_no_ats_growth=4122.55 m:print_order=2 m:column_p_projected_formula=2457037.2 m:column_n_fy14_actual_registers=616
```

## Meta Commands

```ls
metric m:print_order p:integer l:Print_Order t:dataTypeName=number

metric m:column_l_fy15_weight p:double l:"Column L: FY15 Weight" t:dataTypeName=number

metric m:column_m_fy15_per_capita_no_ats_growth p:double l:"Column M: FY15 Per Capita (no ATS growth)" t:dataTypeName=money

metric m:column_n_fy14_actual_registers p:integer l:"Column N: FY14 Actual Registers" t:dataTypeName=number

metric m:column_o_projected_register p:integer l:"Column O: Projected Register" t:dataTypeName=number

metric m:column_p_projected_formula p:double l:"Column P: Projected Formula" t:dataTypeName=money

metric m:column_q_register_change p:double l:"Column Q: Register Change" t:dataTypeName=number

metric m:column_r_register_dollar_change p:double l:"Column R: Register Dollar Change" t:dataTypeName=money

entity e:wr4r-bue7 l:"Fair Student Funding Budget Detail 1" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/wr4r-bue7

property e:wr4r-bue7 t:meta.view d:2017-09-25T07:25:35.111Z v:averageRating=0 v:name="Fair Student Funding Budget Detail 1" v:attribution="Department of Education (DOE)" v:id=wr4r-bue7 v:category="City Government"

property e:wr4r-bue7 t:meta.view.owner d:2017-09-25T07:25:35.111Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:wr4r-bue7 t:meta.view.tableauthor d:2017-09-25T07:25:35.111Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| fiscal_year | location | print_order | attribute_reference | attribute_category | need_name | category | sub_category | column_l_fy15_weight | column_m_fy15_per_capita_no_ats_growth | column_n_fy14_actual_registers | column_o_projected_register | column_p_projected_formula | column_q_register_change | column_r_register_dollar_change | 
| =========== | ======== | =========== | =================== | ================== | ========= | ======== | ============ | ==================== | ====================================== | ============================== | =========================== | ========================== | ======================== | =============================== | 
| 2015        | Q184     | 2           | ATTRIBUTE_01        | Grade Weights      | NA        | K-5      | NA           | 1                    | 4122.55                                | 470                            | 462                         | 1904616.09                 | -8                       | -32980.37                       | 
| 2015        | Q214     | 2           | ATTRIBUTE_01        | Grade Weights      | NA        | K-5      | NA           | 1                    | 4122.55                                | 439                            | 490                         | 2020047.37                 | 51                       | 210249.83                       | 
| 2015        | Q209     | 2           | ATTRIBUTE_01        | Grade Weights      | NA        | K-5      | NA           | 1                    | 4122.55                                | 616                            | 596                         | 2457037.20                 | -20                      | -82450.91                       | 
| 2015        | Q201     | 2           | ATTRIBUTE_01        | Grade Weights      | NA        | K-5      | NA           | 1                    | 4122.55                                | 431                            | 436                         | 1797429.90                 | 5                        | 20612.73                        | 
| 2015        | Q200     | 2           | ATTRIBUTE_01        | Grade Weights      | NA        | K-5      | NA           | 1                    | 4122.55                                | 260                            | 266                         | 1096597.14                 | 6                        | 24735.27                        | 
| 2015        | Q194     | 2           | ATTRIBUTE_01        | Grade Weights      | NA        | K-5      | NA           | 1                    | 4122.55                                | 0                              | 0                           | 0.00                       | 0                        | 0.00                            | 
| 2015        | Q193     | 2           | ATTRIBUTE_01        | Grade Weights      | NA        | K-5      | NA           | 1                    | 4122.55                                | 448                            | 470                         | 1937596.45                 | 22                       | 90696.00                        | 
| 2015        | Q129     | 2           | ATTRIBUTE_01        | Grade Weights      | NA        | K-5      | NA           | 1                    | 4122.55                                | 997                            | 1004                        | 4139035.83                 | 7                        | 28857.82                        | 
| 2015        | Q185     | 2           | ATTRIBUTE_01        | Grade Weights      | NA        | K-5      | NA           | 1                    | 4122.55                                | 0                              | 0                           | 0.00                       | 0                        | 0.00                            | 
| 2015        | Q240     | 2           | ATTRIBUTE_01        | Grade Weights      | NA        | K-5      | NA           | 1                    | 4122.55                                | 0                              | 0                           | 0.00                       | 0                        | 0.00                            | 
```