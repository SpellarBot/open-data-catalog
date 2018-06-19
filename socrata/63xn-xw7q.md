# Grocery Store Access (2010)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grocery-store-access-2010) |
| Metadata | [Link](https://data.nola.gov/api/views/63xn-xw7q) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/63xn-xw7q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/63xn-xw7q/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | 63xn-xw7q |
| Name | Grocery Store Access (2010) |
| Attribution | U.S. Department of Agriculture, Food Environment Atlas |
| Category | Health, Education, and Social Services |
| Created | 2015-04-28T18:17:02Z |
| Publication Date | 2015-08-26T20:40:08Z |

## Description

This data includes the percentage of the population that is low grocery store access in Orleans Parish and other counties, including: Davidson County (TN), East Baton Rouge Parish (LA), Fulton County (GA), Hillsborough County (FL), Jefferson County (KY), Miami-Dade County (FL), Oklahoma County (OK), Shelby County (TN), and Wake County (NC).

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | number        |
| Yes      | series tag     | county_parish  | County-Parish  | text          | text          |
| Yes      | series tag     | state          | State          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
| Yes      | series tag     | indicator      | Indicator      | text          | text          |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | percent       | percent       |
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
series e:63xn-xw7q d:2010-01-01T00:00:00.000Z t:indicator="Percent of population with low access to a grocery store" t:county_parish="Davidson County" t:state=TN t:rowid=1 m:indicatorvalue=25

series e:63xn-xw7q d:2010-01-01T00:00:00.000Z t:indicator="Percent of population with low access to a grocery store" t:county_parish="East Baton Rouge Parish" t:state=LA t:rowid=2 m:indicatorvalue=28

series e:63xn-xw7q d:2010-01-01T00:00:00.000Z t:indicator="Percent of population with low access to a grocery store" t:county_parish="Fulton County" t:state=GA t:rowid=3 m:indicatorvalue=22
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=percent

entity e:63xn-xw7q l:"Grocery Store Access (2010)" t:attribution="U.S. Department of Agriculture, Food Environment Atlas" t:url=https://data.nola.gov/api/views/63xn-xw7q

property e:63xn-xw7q t:meta.view v:id=63xn-xw7q v:category="Health, Education, and Social Services" v:attributionLink=http://www.ers.usda.gov/data-products/food-environment-atlas/go-to-the-atlas v:averageRating=0 v:name="Grocery Store Access (2010)" v:attribution="U.S. Department of Agriculture, Food Environment Atlas"

property e:63xn-xw7q t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:63xn-xw7q t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:63xn-xw7q t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid | county_parish           | state | date                | year | indicator                                                | indicatorvalue | 
| ===== | ======================= | ===== | =================== | ==== | ======================================================== | ============== | 
| 1     | Davidson County         | TN    | 2010-01-01T00:00:00 | 2010 | Percent of population with low access to a grocery store | 25             | 
| 2     | East Baton Rouge Parish | LA    | 2010-01-01T00:00:00 | 2010 | Percent of population with low access to a grocery store | 28             | 
| 3     | Fulton County           | GA    | 2010-01-01T00:00:00 | 2010 | Percent of population with low access to a grocery store | 22             | 
| 4     | Hillsborough County     | FL    | 2010-01-01T00:00:00 | 2010 | Percent of population with low access to a grocery store | 25             | 
| 5     | Jefferson County        | KY    | 2010-01-01T00:00:00 | 2010 | Percent of population with low access to a grocery store | 18             | 
| 6     | Miami-Dade County       | FL    | 2010-01-01T00:00:00 | 2010 | Percent of population with low access to a grocery store | 6              | 
| 7     | Oklahoma County         | OK    | 2010-01-01T00:00:00 | 2010 | Percent of population with low access to a grocery store | 25             | 
| 8     | Orleans Parish          | LA    | 2010-01-01T00:00:00 | 2010 | Percent of population with low access to a grocery store | 25             | 
| 9     | Shelby County           | TN    | 2010-01-01T00:00:00 | 2010 | Percent of population with low access to a grocery store | 27             | 
| 10    | Wake County             | NC    | 2010-01-01T00:00:00 | 2010 | Percent of population with low access to a grocery store | 19             | 
```