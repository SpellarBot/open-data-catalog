# Fair Student Funding Budget Detail 1

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/wr4r-bue7/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/fair-student-funding-budget-detail-1)
* Id = wr4r-bue7
* Name = Fair Student Funding Budget Detail 1
* Attribution = Department of Education (DOE)
* Category = City Government
* Created = 2015-10-19T18:50:29Z
* Publication Date = 2015-10-19T18:58:20Z
* Rows Updated = 2015-10-19T18:51:51Z

## Description

Fair Student Funding Budget Detail FY 2015 - Part I This detail data contains has one row for each school for each of the weights that comprise the Fair Student Funding Formula (Grade Weight, Need Weights, and Portfolio Weights).
Click Here for further information- http://schools.nyc.gov/offices/d_chanc_oper/budget/dbor/allocationmemo/fy14_15/Fair_School_Funding_FY2015.html

## Columns

```ls
| Name                                      | Field Name                             | Data Type | Render Type | Schema Type    | Included | 
| ========================================= | ====================================== | ========= | =========== | ============== | ======== | 
| Fiscal_Year                               | fiscal_year                            | number    | text        | time           | Yes      | 
| Location                                  | location                               | text      | text        | series tag     | Yes      | 
| Print_Order                               | print_order                            | number    | number      | numeric metric | Yes      | 
| Attribute_Reference                       | attribute_reference                    | text      | text        | series tag     | Yes      | 
| Attribute_Category                        | attribute_category                     | text      | text        | series tag     | Yes      | 
| Need_Name                                 | need_name                              | text      | text        | series tag     | Yes      | 
| Category                                  | category                               | text      | text        | series tag     | Yes      | 
| Sub_Category                              | sub_category                           | text      | text        | series tag     | Yes      | 
| Column L: FY15 Weight                     | column_l_fy15_weight                   | number    | number      | numeric metric | Yes      | 
| Column M: FY15 Per Capita (no ATS growth) | column_m_fy15_per_capita_no_ats_growth | money     | money       | numeric metric | Yes      | 
| Column N: FY14 Actual Registers           | column_n_fy14_actual_registers         | number    | number      | numeric metric | Yes      | 
| Column O: Projected Register              | column_o_projected_register            | number    | number      | numeric metric | Yes      | 
| Column P: Projected Formula               | column_p_projected_formula             | money     | money       | numeric metric | Yes      | 
| Column Q: Register Change                 | column_q_register_change               | number    | number      | numeric metric | Yes      | 
| Column R: Register Dollar Change          | column_r_register_dollar_change        | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:wr4r-bue7 d:2015-01-01T00:00:00.000Z t:category=K-5 t:attribute_category="Grade Weights" t:location=Q184 t:attribute_reference=ATTRIBUTE_01 t:sub_category=NA t:need_name=NA m:column_r_register_dollar_change=-32980.37 m:column_o_projected_register=462 m:column_l_fy15_weight=1 m:column_m_fy15_per_capita_no_ats_growth=4122.55 m:column_p_projected_formula=1904616.09 m:column_q_register_change=-8 m:column_n_fy14_actual_registers=470 m:print_order=2

series e:wr4r-bue7 d:2015-01-01T00:00:00.000Z t:category=K-5 t:attribute_category="Grade Weights" t:location=Q214 t:attribute_reference=ATTRIBUTE_01 t:sub_category=NA t:need_name=NA m:column_r_register_dollar_change=210249.83 m:column_o_projected_register=490 m:column_l_fy15_weight=1 m:column_m_fy15_per_capita_no_ats_growth=4122.55 m:column_p_projected_formula=2020047.37 m:column_q_register_change=51 m:column_n_fy14_actual_registers=439 m:print_order=2

series e:wr4r-bue7 d:2015-01-01T00:00:00.000Z t:category=K-5 t:attribute_category="Grade Weights" t:location=Q209 t:attribute_reference=ATTRIBUTE_01 t:sub_category=NA t:need_name=NA m:column_r_register_dollar_change=-82450.91 m:column_o_projected_register=596 m:column_l_fy15_weight=1 m:column_m_fy15_per_capita_no_ats_growth=4122.55 m:column_p_projected_formula=2457037.2 m:column_q_register_change=-20 m:column_n_fy14_actual_registers=616 m:print_order=2
```

## Meta Commands

```ls
metric m:print_order p:integer l:Print_Order t:dataTypeName=number

metric m:column_l_fy15_weight l:"Column L: FY15 Weight" t:dataTypeName=number

metric m:column_n_fy14_actual_registers p:integer l:"Column N: FY14 Actual Registers" t:dataTypeName=number

metric m:column_o_projected_register p:integer l:"Column O: Projected Register" t:dataTypeName=number

metric m:column_q_register_change l:"Column Q: Register Change" t:dataTypeName=number

entity e:wr4r-bue7 l:"Fair Student Funding Budget Detail 1" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/wr4r-bue7

property e:wr4r-bue7 t:meta.view d:2017-03-03T14:03:48.563Z v:id=wr4r-bue7 v:category="City Government" v:averageRating=0 v:name="Fair Student Funding Budget Detail 1" v:attribution="Department of Education (DOE)"

property e:wr4r-bue7 t:meta.view.owner d:2017-03-03T14:03:48.563Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:wr4r-bue7 t:meta.view.tableauthor d:2017-03-03T14:03:48.563Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```