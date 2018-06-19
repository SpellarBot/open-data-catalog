# Local Area Unemployment Statistics: Beginning 1976

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-area-unemployment-statistics-beginning-1976) |
| Metadata | [Link](https://data.ny.gov/api/views/5hyu-bdh8) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/5hyu-bdh8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/5hyu-bdh8/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 5hyu-bdh8 |
| Name | Local Area Unemployment Statistics: Beginning 1976 |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | labor force, employed, unemployed, unemployment rate |
| Created | 2013-02-15T19:41:33Z |
| Publication Date | 2017-04-20T22:26:06Z |

## Description

The Local Area Unemployment Statistics program estimates labor force statistics (labor force, employed, unemployment, unemployment rate) for New York State civilian labor force aged 16 and up. Areas covered include, New York State, New York City, Balance of State, Metropolitan Statistical Areas, Counties, Labor Market Regions, Workforce Investment Board Areas, and cities and towns with populations of 25,000 or more. Data are not seasonally adjusted. Civilian labor force data do not include military, prison inmate, or other institutional populations.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | area              | Area              | text      | text        |
| No       |                | year              | Year              | number    | number      |
| No       |                | month             | Month             | number    | number      |
| Yes      | numeric metric | laborforce        | Labor Force       | number    | number      |
| Yes      | numeric metric | employed          | Employed          | number    | number      |
| Yes      | numeric metric | unemployed        | Unemployed        | number    | number      |
| Yes      | numeric metric | unemployment_rate | Unemployment Rate | percent   | percent     |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:5hyu-bdh8 d:2017-01-01T00:00:00.000Z t:area="New York State" m:unemployed=469900 m:laborforce=9498800 m:unemployment_rate=4.9 m:employed=9028900

series e:5hyu-bdh8 d:2017-02-01T00:00:00.000Z t:area="New York State" m:unemployed=481700 m:laborforce=9558000 m:unemployment_rate=5 m:employed=9076300

series e:5hyu-bdh8 d:2017-03-01T00:00:00.000Z t:area="New York State" m:unemployed=420400 m:laborforce=9616600 m:unemployment_rate=4.4 m:employed=9196300
```

## Meta Commands

```ls
metric m:laborforce p:long l:"Labor Force" d:"Employed plus Unemployed" t:dataTypeName=number

metric m:employed p:long l:Employed t:dataTypeName=number

metric m:unemployed p:long l:Unemployed t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate" t:dataTypeName=percent

entity e:5hyu-bdh8 l:"Local Area Unemployment Statistics: Beginning 1976" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/5hyu-bdh8

property e:5hyu-bdh8 t:meta.view v:id=5hyu-bdh8 v:category="Economic Development" v:attributionLink=http://www.labor.ny.gov/stats/LSLAUS.shtm v:averageRating=0 v:name="Local Area Unemployment Statistics: Beginning 1976" v:attribution="New York State Department of Labor"

property e:5hyu-bdh8 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:5hyu-bdh8 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:5hyu-bdh8 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| area           | year | month | laborforce | employed | unemployed | unemployment_rate | 
| ============== | ==== | ===== | ========== | ======== | ========== | ================= | 
| New York State | 2017 | 1     | 9498800    | 9028900  | 469900     | 4.9               | 
| New York State | 2017 | 2     | 9558000    | 9076300  | 481700     | 5                 | 
| New York State | 2017 | 3     | 9616600    | 9196300  | 420400     | 4.4               | 
| New York State | 2016 | 1     | 9575600    | 9065700  | 509900     | 5.3               | 
| New York State | 2016 | 2     | 9638900    | 9127100  | 511800     | 5.3               | 
| New York State | 2016 | 3     | 9650200    | 9161600  | 488600     | 5.1               | 
| New York State | 2016 | 4     | 9577000    | 9137600  | 439400     | 4.6               | 
| New York State | 2016 | 5     | 9566700    | 9152000  | 414700     | 4.3               | 
| New York State | 2016 | 6     | 9644700    | 9189200  | 455400     | 4.7               | 
| New York State | 2016 | 7     | 9696800    | 9208800  | 488000     | 5                 | 
```