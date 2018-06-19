# Unemployment Insurance Average Duration: Beginning 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-insurance-average-duration-beginning-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/qkrk-6v78) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/qkrk-6v78/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/qkrk-6v78/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | qkrk-6v78 |
| Name | Unemployment Insurance Average Duration: Beginning 2002 |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | unemployment, insurance, benefits, beneficiaries |
| Created | 2015-11-02T23:06:35Z |
| Publication Date | 2017-04-17T22:09:00Z |

## Description

This dataset contains, by region and county, for each month from January 2002 to present, the number of New York State unemployment insurance average duration.

Average Duration is the average number of unemployment insurance weeks beneficiaries receive within their benefit year.

Data include only Regular Unemployment  Insurance(UI) excluding Unemployment Compensation for Federal Employees (UCFE), Unemployment Compensation for Ex-Service Members (UCX), Shared Work (SW), Self Employment Assistance Program (SEAP), 599.2 training, and federal extension programs.

Data are provided for the10 labor market regions, and 62 counties.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       |                | year             | Year             | number    | number      |
| No       |                | month            | Month            | number    | number      |
| Yes      | series tag     | region           | Region           | text      | text        |
| Yes      | series tag     | county           | County           | text      | text        |
| Yes      | numeric metric | average_duration | Average Duration | number    | number      |
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
series e:qkrk-6v78 d:2002-01-01T00:00:00.000Z t:region=Capital t:county="Capital Region" m:average_duration=14.5

series e:qkrk-6v78 d:2002-01-01T00:00:00.000Z t:region=Capital t:county=Albany m:average_duration=15.1

series e:qkrk-6v78 d:2002-01-01T00:00:00.000Z t:region=Capital t:county=Columbia m:average_duration=13.8
```

## Meta Commands

```ls
metric m:average_duration p:float l:"Average Duration" d:"Average number of unemployment insurance weeks beneficiaries receives within their benefit year by county" t:dataTypeName=number

entity e:qkrk-6v78 l:"Unemployment Insurance Average Duration: Beginning 2002" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/qkrk-6v78

property e:qkrk-6v78 t:meta.view v:id=qkrk-6v78 v:category="Economic Development" v:attributionLink=http://www.labor.ny.gov/stats/UI/Unemployment-Insurance-Data.shtm v:averageRating=0 v:name="Unemployment Insurance Average Duration: Beginning 2002" v:attribution="New York State Department of Labor"

property e:qkrk-6v78 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:qkrk-6v78 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | month | region           | county                  | average_duration | 
| ==== | ===== | ================ | ======================= | ================ | 
| 2002 | 1     | Capital          | Capital Region          | 14.5             | 
| 2002 | 1     | Capital          | Albany                  | 15.1             | 
| 2002 | 1     | Capital          | Columbia                | 13.8             | 
| 2002 | 1     | Capital          | Greene                  | 15.2             | 
| 2002 | 1     | Capital          | Rensselaer              | 14.1             | 
| 2002 | 1     | Capital          | Saratoga                | 14.8             | 
| 2002 | 1     | Capital          | Schenectady             | 14.2             | 
| 2002 | 1     | Capital          | Warren                  | 14.5             | 
| 2002 | 1     | Capital          | Washington              | 13.3             | 
| 2002 | 1     | Central New York | Central New York Region | 14.7             | 
```