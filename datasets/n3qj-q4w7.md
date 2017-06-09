# Food Insecurity Rates (2009 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/food-insecurity-rates-2009-present) |
| Metadata | [Link](https://data.nola.gov/api/views/n3qj-q4w7) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/n3qj-q4w7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/n3qj-q4w7/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | n3qj-q4w7 |
| Name | Food Insecurity Rates (2009 - Present) |
| Attribution | Feeding America, Map the Meal Gap |
| Category | Health, Education, and Social Services |
| Created | 2015-04-28T17:36:53Z |
| Publication Date | 2015-11-03T21:59:01Z |

## Description

This data includes the percentage of the population that is food insecure in Orleans Parish and other counties, including: Davidson County (TN), East Baton Rouge Parish (LA), Fulton County (GA), Hillsborough County (FL), Jefferson County (KY), Miami-Dade County (FL), Oklahoma County (OK), Shelby County (TN), and Wake County (NC). The data is available annually beginning in 2009.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
| Yes      | series tag     | location       | Location       | text          | text          |
| Yes      | series tag     | indicator      | IndicatorName  | text          | text          |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:n3qj-q4w7 d:2009-01-01T00:00:00.000Z t:indicator="Percent of population that is food insecure" t:location="Orleans Parish, LA" t:rowid="Orleans Parish, LAPercent of population that is food insecure 2009" m:indicatorvalue=19

series e:n3qj-q4w7 d:2009-01-01T00:00:00.000Z t:indicator="Percent of population that is food insecure" t:location="Davidson County, TN" t:rowid="Davidson County, TNPercent of population that is food insecure 2009" m:indicatorvalue=16

series e:n3qj-q4w7 d:2009-01-01T00:00:00.000Z t:indicator="Percent of population that is food insecure" t:location="East Baton Rouge Parish, LA" t:rowid="East Baton Rouge Parish, LAPercent of population that is food insecure 2009" m:indicatorvalue=15
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:n3qj-q4w7 l:"Food Insecurity Rates (2009 - Present)" t:attribution="Feeding America, Map the Meal Gap" t:url=https://data.nola.gov/api/views/n3qj-q4w7

property e:n3qj-q4w7 t:meta.view d:2017-06-09T13:59:23.423Z v:id=n3qj-q4w7 v:category="Health, Education, and Social Services" v:attributionLink=http://feedingamerica.org/hunger-in-america/hunger-studies/map-the-meal-gap.aspx v:averageRating=0 v:name="Food Insecurity Rates (2009 - Present)" v:attribution="Feeding America, Map the Meal Gap"

property e:n3qj-q4w7 t:meta.view.owner d:2017-06-09T13:59:23.423Z v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:n3qj-q4w7 t:meta.view.tableauthor d:2017-06-09T13:59:23.423Z v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:n3qj-q4w7 t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:59:23.423Z v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                                       | date                | year | location                    | indicator                                   | indicatorvalue | 
| =========================================================================== | =================== | ==== | =========================== | =========================================== | ============== | 
| Orleans Parish, LAPercent of population that is food insecure 2009          | 2009-01-01T00:00:00 | 2009 | Orleans Parish, LA          | Percent of population that is food insecure | 19             | 
| Davidson County, TNPercent of population that is food insecure 2009         | 2009-01-01T00:00:00 | 2009 | Davidson County, TN         | Percent of population that is food insecure | 16             | 
| East Baton Rouge Parish, LAPercent of population that is food insecure 2009 | 2009-01-01T00:00:00 | 2009 | East Baton Rouge Parish, LA | Percent of population that is food insecure | 15             | 
| Fulton County, GAPercent of population that is food insecure 2009           | 2009-01-01T00:00:00 | 2009 | Fulton County, GA           | Percent of population that is food insecure | 19             | 
| Hillsborough County, FLPercent of population that is food insecure 2009     | 2009-01-01T00:00:00 | 2009 | Hillsborough County, FL     | Percent of population that is food insecure | 17             | 
| Jefferson County, KYPercent of population that is food insecure 2009        | 2009-01-01T00:00:00 | 2009 | Jefferson County, KY        | Percent of population that is food insecure | 17             | 
| Miami-Dade County, FLPercent of population that is food insecure 2009       | 2009-01-01T00:00:00 | 2009 | Miami-Dade County, FL       | Percent of population that is food insecure | 18             | 
| Oklahoma County, OKPercent of population that is food insecure 2009         | 2009-01-01T00:00:00 | 2009 | Oklahoma County, OK         | Percent of population that is food insecure | 17             | 
| Shelby County, TNPercent of population that is food insecure 2009           | 2009-01-01T00:00:00 | 2009 | Shelby County, TN           | Percent of population that is food insecure | 20             | 
| Wake County, NCPercent of population that is food insecure 2009             | 2009-01-01T00:00:00 | 2009 | Wake County, NC             | Percent of population that is food insecure | 14             | 
```