# Local Area Unemployment Statistics (LAUS), Seasonally Adjusted Data: Beginning 1976

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-area-unemployment-statistics-laus-seasonally-adjusted-data-beginning-1976) |
| Metadata | [Link](https://data.ny.gov/api/views/dh9m-5v4d) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dh9m-5v4d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dh9m-5v4d/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dh9m-5v4d |
| Name | Local Area Unemployment Statistics (LAUS), Seasonally Adjusted Data: Beginning 1976 |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | labor force, employed, unemployed, unemployment rate, seasonally adjusted |
| Created | 2014-10-15T20:27:54Z |
| Publication Date | 2017-04-20T22:04:15Z |

## Description

The Local Area Unemployment Statistics program estimates labor force statistics (labor force, employed, unemployment, unemployment rate) for New York State civilian labor force aged 16 and up. Seasonally adjusted estimates are provided for New York State, New York City, Balance of State.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | area              | Area              | text      | text        |
| No       |                | year              | Year              | number    | number      |
| No       |                | month             | Month             | number    | number      |
| Yes      | numeric metric | labor_force       | Labor Force       | number    | number      |
| Yes      | numeric metric | employed          | Employed          | number    | number      |
| Yes      | numeric metric | unemployed        | Unemployed        | number    | number      |
| Yes      | numeric metric | unemployment_rate | Unemployment Rate | number    | number      |
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
series e:dh9m-5v4d d:2017-01-01T00:00:00.000Z t:area="New York State" m:unemployed=435700 m:unemployment_rate=4.6 m:labor_force=9523000 m:employed=9087400

series e:dh9m-5v4d d:2017-02-01T00:00:00.000Z t:area="New York State" m:unemployed=423500 m:unemployment_rate=4.4 m:labor_force=9552900 m:employed=9129400

series e:dh9m-5v4d d:2017-03-01T00:00:00.000Z t:area="New York State" m:unemployed=409100 m:unemployment_rate=4.3 m:labor_force=9604800 m:employed=9195800
```

## Meta Commands

```ls
metric m:labor_force p:long l:"Labor Force" d:"Resident employment plus resident unemployment" t:dataTypeName=number

metric m:employed p:long l:Employed d:"Resident employment" t:dataTypeName=number

metric m:unemployed p:long l:Unemployed d:"Resident unemployment" t:dataTypeName=number

metric m:unemployment_rate p:long l:"Unemployment Rate" d:"Unemployment rate (percent) resident unemployment divided by resident labor force" t:dataTypeName=number

entity e:dh9m-5v4d l:"Local Area Unemployment Statistics (LAUS), Seasonally Adjusted Data: Beginning 1976" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/dh9m-5v4d

property e:dh9m-5v4d t:meta.view v:id=dh9m-5v4d v:category="Economic Development" v:attributionLink=http://www.labor.ny.gov/stats/LSLAUS.shtm v:averageRating=0 v:name="Local Area Unemployment Statistics (LAUS), Seasonally Adjusted Data: Beginning 1976" v:attribution="New York State Department of Labor"

property e:dh9m-5v4d t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dh9m-5v4d t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:dh9m-5v4d t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| area           | year | month | labor_force | employed | unemployed | unemployment_rate | 
| ============== | ==== | ===== | =========== | ======== | ========== | ================= | 
| New York State | 2017 | 1     | 9523000     | 9087400  | 435700     | 4.6               | 
| New York State | 2017 | 2     | 9552900     | 9129400  | 423500     | 4.4               | 
| New York State | 2017 | 3     | 9604800     | 9195800  | 409100     | 4.3               | 
| New York State | 2016 | 1     | 9563500     | 9095600  | 467900     | 4.9               | 
| New York State | 2016 | 2     | 9560700     | 9096100  | 464700     | 4.9               | 
| New York State | 2016 | 3     | 9552000     | 9090700  | 461300     | 4.8               | 
| New York State | 2016 | 4     | 9541700     | 9082000  | 459700     | 4.8               | 
| New York State | 2016 | 5     | 9534600     | 9073500  | 461200     | 4.8               | 
| New York State | 2016 | 6     | 9532800     | 9067700  | 465100     | 4.9               | 
| New York State | 2016 | 7     | 9534400     | 9065300  | 469100     | 4.9               | 
```