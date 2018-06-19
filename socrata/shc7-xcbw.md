# Quarterly Census of Employment and Wages Annual Data: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/quarterly-census-of-employment-and-wages-annual-data-beginning-2000) |
| Metadata | [Link](https://data.ny.gov/api/views/shc7-xcbw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/shc7-xcbw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/shc7-xcbw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | shc7-xcbw |
| Name | Quarterly Census of Employment and Wages Annual Data: Beginning 2000 |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | employment, payroll, labor statistics, industry |
| Created | 2013-02-15T16:49:29Z |
| Publication Date | 2016-06-20T23:04:37Z |

## Description

The Quarterly Census of Employment and Wages (QCEW) program (also known as ES-202) collects employment and wage data from employers covered by New York State's Unemployment Insurance (UI) Law. This program is a cooperative program with the U.S. Bureau of Labor Statistics. QCEW data encompass approximately 97 percent of New York's nonfarm employment, providing a virtual census of employees and their wages as well as the most complete universe of employment and wage data, by industry, at the State, regional and county levels. "Covered" employment refers broadly to both private-sector employees as well as state, county, and municipal government employees insured under the New York State Unemployment Insurance (UI) Act. Federal employees are insured under separate laws, but are considered covered for the purposes of the program. Employee categories not covered by UI include some agricultural workers, railroad workers, private household workers, student workers, the self-employed, and unpaid family workers. QCEW data are similar to monthly Current Employment Statistics (CES) data in that they reflect jobs by place of work; therefore, if a person holds two jobs, he or she is counted twice. However, since the QCEW program, by definition, only measures employment covered by unemployment insurance laws, its totals will not be the same as CES employment totals due to the employee categories excluded by UI.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | area_type             | Area Type             | text      | text        |
| Yes      | series tag     | area                  | Area                  | text      | text        |
| Yes      | numeric metric | naics                 | NAICS                 | number    | number      |
| Yes      | series tag     | naics_title           | NAICS Title           | text      | text        |
| Yes      | time           | year                  | Year                  | number    | number      |
| Yes      | numeric metric | establishments        | Establishments        | number    | number      |
| Yes      | numeric metric | average_employment    | Average Employment    | number    | number      |
| Yes      | numeric metric | total_wage            | Total Wage            | money     | money       |
| Yes      | numeric metric | annual_average_salary | Annual Average Salary | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:shc7-xcbw d:2015-01-01T00:00:00.000Z t:area_type=State t:naics_title="Agriculture, Forestry, Fishing & Hunting" t:area="New York State" m:naics=11 m:total_wage=841845054 m:average_employment=25687 m:establishments=2582 m:annual_average_salary=32773

series e:shc7-xcbw d:2015-01-01T00:00:00.000Z t:area_type=State t:naics_title="Crop Production" t:area="New York State" m:naics=111 m:total_wage=360023965 m:average_employment=12155 m:establishments=1125 m:annual_average_salary=29619

series e:shc7-xcbw d:2015-01-01T00:00:00.000Z t:area_type=State t:naics_title="Animal Production" t:area="New York State" m:naics=112 m:total_wage=353942945 m:average_employment=10191 m:establishments=826 m:annual_average_salary=34731
```

## Meta Commands

```ls
metric m:naics p:integer l:NAICS d:"Industrial classification data are classified in accordance with the 2002 North American Industry Classification System (NAICS), which recently replaced the long-standing Standard Industrial Classification (SIC) system." t:dataTypeName=number

metric m:establishments p:integer l:Establishments d:"All employers subject to UI laws." t:dataTypeName=number

metric m:average_employment p:integer l:"Average Employment" d:"Annual Average Employment is the arithmetic mean of the employment reported for all 12 months of the year." t:dataTypeName=number

metric m:total_wage p:long l:"Total Wage" d:"Total wages cover all wages and salaries paid to individuals in insured employment." t:dataTypeName=money

metric m:annual_average_salary p:integer l:"Annual Average Salary" d:"Anual average salary is the sum of the wages for the four quarters of the year (Total Wage) divided by the annual average employment, (Average Employment)." t:dataTypeName=money

entity e:shc7-xcbw l:"Quarterly Census of Employment and Wages Annual Data: Beginning 2000" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/shc7-xcbw

property e:shc7-xcbw t:meta.view v:id=shc7-xcbw v:category="Economic Development" v:attributionLink=http://www.labor.state.ny.us/stats/LSQCEW.shtm v:averageRating=0 v:name="Quarterly Census of Employment and Wages Annual Data: Beginning 2000" v:attribution="New York State Department of Labor"

property e:shc7-xcbw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:shc7-xcbw t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:shc7-xcbw t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| area_type | area           | naics | naics_title                              | year | establishments | average_employment | total_wage | annual_average_salary | 
| ========= | ============== | ===== | ======================================== | ==== | ============== | ================== | ========== | ===================== | 
| State     | New York State | 11    | Agriculture, Forestry, Fishing & Hunting | 2015 | 2582           | 25687              | 841845054  | 32773                 | 
| State     | New York State | 111   | Crop Production                          | 2015 | 1125           | 12155              | 360023965  | 29619                 | 
| State     | New York State | 112   | Animal Production                        | 2015 | 826            | 10191              | 353942945  | 34731                 | 
| State     | New York State | 113   | Forestry and Logging                     | 2015 | 189            | 659                | 25944733   | 39370                 | 
| State     | New York State | 114   | Fishing, Hunting and Trapping            | 2015 | 46             | 108                | 3676260    | 34039                 | 
| State     | New York State | 115   | Agriculture & Forestry Support Activity  | 2015 | 397            | 2574               | 98257151   | 38173                 | 
| State     | New York State | 21    | Mining                                   | 2015 | 367            | 4640               | 301891298  | 65063                 | 
| State     | New York State | 211   | Oil and Gas Extraction                   | 2015 | 33             | 452                | 42551863   | 94141                 | 
| State     | New York State | 212   | Mining (except Oil and Gas)              | 2015 | 259            | 3787               | 231542873  | 61142                 | 
| State     | New York State | 213   | Support Activities for Mining            | 2015 | 75             | 401                | 27796562   | 69318                 | 
```