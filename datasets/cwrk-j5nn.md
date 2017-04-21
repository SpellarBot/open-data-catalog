# Estimated Gasoline Sales: Beginning 1995

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/estimated-gasoline-sales-thousands-of-gallons-beginning-1995) |
| Metadata | [Link](https://data.ny.gov/api/views/cwrk-j5nn) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cwrk-j5nn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cwrk-j5nn/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cwrk-j5nn |
| Name | Estimated Gasoline Sales: Beginning 1995 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | gasoline, gasoline consumption by county, gas sales |
| Created | 2013-03-04T22:10:52Z |
| Publication Date | 2016-11-04T22:08:38Z |

## Description

Estimated gasoline sales data is derived from New York StateDepartment of Taxation and Finance data on gasoline sales andgasoline sales tax collections. Gasoline sales data is estimated for eachcounty with the exception that individual county data for New YorkCity is not available. Data is weighted for regional price differencesand differing county tax rates.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                                  | Data Type | Render Type |
| ======== | ============== | =============== | ===================================== | ========= | =========== |
| Yes      | time           | year            | Year                                  | number    | number      |
| Yes      | series tag     | county          | County                                | text      | text        |
| Yes      | numeric metric | estimated_sales | Estimated Sales, Thousands of Gallons | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cwrk-j5nn d:2014-01-01T00:00:00.000Z t:county=Albany m:estimated_sales=133346

series e:cwrk-j5nn d:2014-01-01T00:00:00.000Z t:county=Allegany m:estimated_sales=14710

series e:cwrk-j5nn d:2014-01-01T00:00:00.000Z t:county=Broome m:estimated_sales=100444
```

## Meta Commands

```ls
metric m:estimated_sales p:integer l:"Estimated Sales, Thousands of Gallons" d:"Estimated sales of gasoline in thousands of gallons" t:dataTypeName=number

entity e:cwrk-j5nn l:"Estimated Gasoline Sales: Beginning 1995" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/cwrk-j5nn

property e:cwrk-j5nn t:meta.view v:id=cwrk-j5nn v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Prices-Data-and-Reports/Energy-Statistics-and-Weather-Data/Energy-Statistics.aspx v:averageRating=0 v:name="Estimated Gasoline Sales: Beginning 1995" v:attribution="New York State Energy Research and Development Authority"

property e:cwrk-j5nn t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cwrk-j5nn t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cwrk-j5nn t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | county      | estimated_sales | 
| ==== | =========== | =============== | 
| 2014 | Albany      | 133346          | 
| 2014 | Allegany    | 14710           | 
| 2014 | Broome      | 100444          | 
| 2014 | Cattaraugus | 23038           | 
| 2014 | Cayuga      | 35070           | 
| 2014 | Chautauqua  | 35898           | 
| 2014 | Chemung     | 32281           | 
| 2014 | Chenango    | 20906           | 
| 2014 | Clinton     | 45376           | 
| 2014 | Columbia    | 35291           | 
```