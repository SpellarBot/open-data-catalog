# Quarterly Census of Employment and Wages Quarterly Data: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/quarterly-census-of-employment-and-wages-quarterly-data-beginning-2000) |
| Metadata | [Link](https://data.ny.gov/api/views/cwsm-2ns3) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cwsm-2ns3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cwsm-2ns3/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cwsm-2ns3 |
| Name | Quarterly Census of Employment and Wages Quarterly Data: Beginning 2000 |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | employment, payroll, labor statistics, industry |
| Created | 2013-02-15T16:30:00Z |
| Publication Date | 2017-03-13T23:40:36Z |

## Description

The Quarterly Census of Employment and Wages (QCEW) program (also known as ES-202) collects employment and wage data from employers covered by New York State's Unemployment Insurance (UI) Law. This program is a cooperative program with the U.S. Bureau of Labor Statistics. QCEW data encompass approximately 97 percent of New York's nonfarm employment, providing a virtual census of employees and their wages as well as the most complete universe of employment and wage data, by industry, at the State, regional and county levels. "Covered" employment refers broadly to both private-sector employees as well as state, county, and municipal government employees insured under the New York State Unemployment Insurance (UI) Act. Federal employees are insured under separate laws, but are considered covered for the purposes of the program. Employee categories not covered by UI include some agricultural workers, railroad workers, private household workers, student workers, the self-employed, and unpaid family workers. QCEW data are similar to monthly Current Employment Statistics (CES) data in that they reflect jobs by place of work; therefore, if a person holds two jobs, he or she is counted twice. However, since the QCEW program, by definition, only measures employment covered by unemployment insurance laws, its totals will not be the same as CES employment totals due to the employee categories excluded by UI.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | area_type          | Area Type          | text      | text        |
| Yes      | series tag     | area               | Area               | text      | text        |
| No       |                | year               | Year               | number    | number      |
| No       |                | quarter            | Quarter            | number    | number      |
| Yes      | numeric metric | naics              | NAICS              | number    | number      |
| Yes      | series tag     | naics_title        | NAICS Title        | text      | text        |
| Yes      | numeric metric | establishments     | Establishments     | number    | number      |
| Yes      | numeric metric | month_1_employment | Month 1 Employment | number    | number      |
| Yes      | numeric metric | month_2_employment | Month 2 Employment | number    | number      |
| Yes      | numeric metric | month_3_employment | Month 3 Employment | number    | number      |
| Yes      | numeric metric | total_wage         | Total Wage         | money     | money       |
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
series e:cwsm-2ns3 d:2016-01-01T00:00:00.000Z t:area_type=State t:naics_title="Total, All Industries" t:area="New York State" m:month_1_employment=8935830 m:naics=0 m:month_3_employment=9040495 m:total_wage=169934242250 m:establishments=629941 m:month_2_employment=8979018

series e:cwsm-2ns3 d:2016-01-01T00:00:00.000Z t:area_type=County t:naics_title="Total, All Industries" t:area="Albany County" m:month_1_employment=228237 m:naics=0 m:month_3_employment=230411 m:total_wage=3042809373 m:establishments=10263 m:month_2_employment=229771

series e:cwsm-2ns3 d:2016-01-01T00:00:00.000Z t:area_type=County t:naics_title="Total, All Industries" t:area="Allegany County" m:month_1_employment=13168 m:naics=0 m:month_3_employment=13720 m:total_wage=121826836 m:establishments=939 m:month_2_employment=13697
```

## Meta Commands

```ls
metric m:naics p:integer l:NAICS d:"Industrial classification data are classified in accordance with the 2002 North American Industry Classification System (NAICS), which recently replaced the long-standing Standard Industrial Classification (SIC) system." t:dataTypeName=number

metric m:establishments p:integer l:Establishments d:"All employers subject to UI laws" t:dataTypeName=number

metric m:month_1_employment p:integer l:"Month 1 Employment" d:"Monthly employment figures representing the number of people either working during or receiving pay for the payroll period." t:dataTypeName=number

metric m:month_2_employment p:integer l:"Month 2 Employment" d:"Monthly employment figures representing the number of people either working during or receiving pay for the payroll period." t:dataTypeName=number

metric m:month_3_employment p:integer l:"Month 3 Employment" d:"Monthly employment figures representing the number of people either working during or receiving pay for the payroll period." t:dataTypeName=number

metric m:total_wage p:long l:"Total Wage" d:"Total wages cover all wages and salaries paid to individuals in insured employment." t:dataTypeName=money

entity e:cwsm-2ns3 l:"Quarterly Census of Employment and Wages Quarterly Data: Beginning 2000" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/cwsm-2ns3

property e:cwsm-2ns3 t:meta.view v:id=cwsm-2ns3 v:category="Economic Development" v:attributionLink=http://www.labor.state.ny.us/stats/LSQCEW.shtm v:averageRating=0 v:name="Quarterly Census of Employment and Wages Quarterly Data: Beginning 2000" v:attribution="New York State Department of Labor"

property e:cwsm-2ns3 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cwsm-2ns3 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cwsm-2ns3 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| area_type | area               | year | quarter | naics | naics_title           | establishments | month_1_employment | month_2_employment | month_3_employment | total_wage   | 
| ========= | ================== | ==== | ======= | ===== | ===================== | ============== | ================== | ================== | ================== | ============ | 
| State     | New York State     | 2016 | 1       | 0     | Total, All Industries | 629941         | 8935830            | 8979018            | 9040495            | 169934242250 | 
| County    | Albany County      | 2016 | 1       | 0     | Total, All Industries | 10263          | 228237             | 229771             | 230411             | 3042809373   | 
| County    | Allegany County    | 2016 | 1       | 0     | Total, All Industries | 939            | 13168              | 13697              | 13720              | 121826836    | 
| County    | Bronx County       | 2016 | 1       | 0     | Total, All Industries | 18365          | 294749             | 296252             | 299473             | 3564369970   | 
| County    | Broome County      | 2016 | 1       | 0     | Total, All Industries | 4523           | 84205              | 85613              | 86054              | 841984078    | 
| County    | Cattaraugus County | 2016 | 1       | 0     | Total, All Industries | 1820           | 29818              | 30196              | 29979              | 273668991    | 
| County    | Cayuga County      | 2016 | 1       | 0     | Total, All Industries | 1782           | 25109              | 25208              | 25458              | 259513244    | 
| County    | Chautauqua County  | 2016 | 1       | 0     | Total, All Industries | 3201           | 47808              | 48430              | 48933              | 439435181    | 
| County    | Chemung County     | 2016 | 1       | 0     | Total, All Industries | 1962           | 35486              | 35233              | 35249              | 392978722    | 
| County    | Chenango County    | 2016 | 1       | 0     | Total, All Industries | 1090           | 17416              | 17443              | 17593              | 190740821    | 
```