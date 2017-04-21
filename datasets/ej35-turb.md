# Quarterly Census of Employment and Wages (QCEW) Historical Annual Data: 1975 - 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/quarterly-census-of-employment-and-wages-qcew-historical-annual-data-1975-2000) |
| Metadata | [Link](https://data.ny.gov/api/views/ej35-turb) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ej35-turb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ej35-turb/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ej35-turb |
| Name | Quarterly Census of Employment and Wages (QCEW) Historical Annual Data: 1975 - 2000 |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | employment, payroll, labor statistics, industry, sic, wages |
| Created | 2014-08-29T20:44:37Z |
| Publication Date | 2014-10-06T20:56:08Z |

## Description

The Quarterly Census of Employment and Wages (QCEW) program (also known as ES-202) collects employment and wage data from employers covered by New York State's Unemployment Insurance (UI) Law. This program is a cooperative program with the U.S. Bureau of Labor Statistics. QCEW data encompass approximately 97 percent of New York's nonfarm employment, providing a virtual census of employees and their wages as well as the most complete universe of employment and wage data, by industry, at the State, regional and county levels. "Covered" employment refers broadly to both private-sector employees as well as state, county, and municipal government employees insured under the New York State Unemployment Insurance (UI) Act. Federal employees are insured under separate laws, but are considered covered for the purposes of the program. Employee categories not covered by UI include some agricultural workers, railroad workers, private household workers, student workers, the self-employed, and unpaid family workers. QCEW data are similar to monthly Current Employment Statistics (CES) data in that they reflect jobs by place of work; therefore, if a person holds two jobs, he or she is counted twice. However, since the QCEW program, by definition, only measures employment covered by unemployment insurance laws, its totals will not be the same as CES employment totals due to the employee categories excluded by UI. Industry level data from  1975 to 2000 is reflective of the Standard Industrial Classification (SIC) codes.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | state_fips           | State FIPS           | text      | number      |
| Yes      | series tag     | county_fips          | County FIPS          | text      | text        |
| Yes      | series tag     | county               | County Name          | text      | text        |
| Yes      | series tag     | industry             | Industry             | text      | text        |
| Yes      | series tag     | industry_title       | Industry Title       | text      | text        |
| Yes      | time           | year                 | Year                 | number    | number      |
| Yes      | numeric metric | reporting_units      | Reporting Units      | number    | number      |
| Yes      | numeric metric | average_employment   | Average Employment   | number    | number      |
| Yes      | numeric metric | average_annual_wages | Average Annual Wages | number    | number      |
| Yes      | numeric metric | total_wages          | Total Wages          | number    | number      |
| Yes      | numeric metric | average_weekly_wages | Average Weekly Wages | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ej35-turb d:1975-01-01T00:00:00.000Z t:county_fips=000 t:county="Statewide Total" t:industry_title="All Industries" t:industry=00 t:state_fips=36 m:average_annual_wages=11252 m:average_weekly_wages=216.38 m:average_employment=5837283 m:total_wages=65679632451 m:reporting_units=399591

series e:ej35-turb d:1976-01-01T00:00:00.000Z t:county_fips=000 t:county="Statewide Total" t:industry_title="All Industries" t:industry=00 t:state_fips=36 m:average_annual_wages=11918 m:average_weekly_wages=229.19 m:average_employment=5842021 m:total_wages=69624487626 m:reporting_units=401534

series e:ej35-turb d:1977-01-01T00:00:00.000Z t:county_fips=000 t:county="Statewide Total" t:industry_title="All Industries" t:industry=00 t:state_fips=36 m:average_annual_wages=12619 m:average_weekly_wages=242.68 m:average_employment=5918521 m:total_wages=74687237156 m:reporting_units=402698
```

## Meta Commands

```ls
metric m:reporting_units p:integer l:"Reporting Units" d:"The reporting unit is the economic unit for which data are submitted on the employer's unemployment insurance contribution report, or on a multiple worksite report. The reporting unit is often (though not always) synonymous with the terms ""worksite"" and ""establishment.""" t:dataTypeName=number

metric m:average_employment p:integer l:"Average Employment" d:"The average employment is the summed monthly employment, as reported in the ES-202/QCEW, divided by 12." t:dataTypeName=number

metric m:average_annual_wages p:integer l:"Average Annual Wages" d:"The average wage is the average yearly wage paid to the employees of all the reporting units for the industry division and county as reported in the ES-202/QCEW. It is computed by dividing the total wages for the year by the average monthly employment." t:dataTypeName=number

metric m:total_wages p:long l:"Total Wages" d:"Total wages is the sum of all remunerations reported by all the reporting units in the ES-202/QCEW for the year." t:dataTypeName=number

metric m:average_weekly_wages p:float l:"Average Weekly Wages" d:"The average weekly wage is computed by dividing the total wages for the year by the average monthly employment, and then dividing the result by 52." t:dataTypeName=number

entity e:ej35-turb l:"Quarterly Census of Employment and Wages (QCEW) Historical Annual Data: 1975 - 2000" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/ej35-turb

property e:ej35-turb t:meta.view v:id=ej35-turb v:category="Economic Development" v:attributionLink=http://labor.ny.gov/stats/employ/historical_qcew.shtm v:averageRating=0 v:name="Quarterly Census of Employment and Wages (QCEW) Historical Annual Data: 1975 - 2000" v:attribution="New York State Department of Labor"

property e:ej35-turb t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ej35-turb t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ej35-turb t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| state_fips | county_fips | county          | industry | industry_title | year | reporting_units | average_employment | average_annual_wages | total_wages  | average_weekly_wages | 
| ========== | =========== | =============== | ======== | ============== | ==== | =============== | ================== | ==================== | ============ | ==================== | 
| 36         | 000         | Statewide Total | 00       | All Industries | 1975 | 399591          | 5837283            | 11252                | 65679632451  | 216.38               | 
| 36         | 000         | Statewide Total | 00       | All Industries | 1976 | 401534          | 5842021            | 11918                | 69624487626  | 229.19               | 
| 36         | 000         | Statewide Total | 00       | All Industries | 1977 | 402698          | 5918521            | 12619                | 74687237156  | 242.68               | 
| 36         | 000         | Statewide Total | 00       | All Industries | 1978 | 409056          | 6947626            | 13404                | 93129229209  | 257.78               | 
| 36         | 000         | Statewide Total | 00       | All Industries | 1979 | 413911          | 7100842            | 14326                | 101723121739 | 275.49               | 
| 36         | 000         | Statewide Total | 00       | All Industries | 1980 | 416304          | 7113414            | 15685                | 111575198153 | 301.64               | 
| 36         | 000         | Statewide Total | 00       | All Industries | 1981 | 411634          | 7191680            | 17131                | 123199329443 | 329.44               | 
| 36         | 000         | Statewide Total | 00       | All Industries | 1982 | 412190          | 7161186            | 18533                | 132719248113 | 356.41               | 
| 36         | 000         | Statewide Total | 00       | All Industries | 1983 | 417579          | 7214082            | 19675                | 141936528397 | 378.36               | 
| 36         | 000         | Statewide Total | 00       | All Industries | 1984 | 427362          | 7467957            | 20751                | 154970347559 | 399.06               | 
```