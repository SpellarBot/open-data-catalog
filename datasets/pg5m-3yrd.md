# Health-based Drinking Water Violations (2003 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-based-drinking-water-violations-2003-present) |
| Metadata | [Link](https://data.nola.gov/api/views/pg5m-3yrd) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/pg5m-3yrd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/pg5m-3yrd/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | pg5m-3yrd |
| Name | Health-based Drinking Water Violations (2003 - Present) |
| Attribution | U.S. Environmental Protection Agency (EPA), Enforcement & Compliance History Online (ECHO) |
| Category | Environment |
| Created | 2015-04-29T19:17:36Z |
| Publication Date | 2016-01-25T18:44:29Z |

## Description

This data comes from the U.S. Environmental Protection Agency and is reported annually beginning in 2003. It includes data for New Orleans and several benchmark cities, including: Atlanta, Baton Rouge, Louisville, Memphis, Miami, Nashville, Oklahoma City, Raleigh, and Tampa.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | series tag     | indicator      | Indicator      | text          | text          |
| Yes      | series tag     | city           | City           | text          | text          |
| Yes      | series tag     | state          | State          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
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
series e:pg5m-3yrd d:2003-01-01T00:00:00.000Z t:indicator="Number of health-based drinking water violations" t:state=LA t:rowid="New Orleans2003" t:city="New Orleans" m:indicatorvalue=0

series e:pg5m-3yrd d:2003-01-01T00:00:00.000Z t:indicator="Number of health-based drinking water violations" t:state=OK t:rowid="Oklahoma City2003" t:city="Oklahoma City" m:indicatorvalue=0

series e:pg5m-3yrd d:2003-01-01T00:00:00.000Z t:indicator="Number of health-based drinking water violations" t:state=FL t:rowid=Tampa2003 t:city=Tampa m:indicatorvalue=0
```

## Meta Commands

```ls
metric m:indicatorvalue p:double l:IndicatorValue t:dataTypeName=number

entity e:pg5m-3yrd l:"Health-based Drinking Water Violations (2003 - Present)" t:attribution="U.S. Environmental Protection Agency (EPA), Enforcement & Compliance History Online (ECHO)" t:url=https://data.nola.gov/api/views/pg5m-3yrd

property e:pg5m-3yrd t:meta.view v:id=pg5m-3yrd v:category=Environment v:attributionLink=http://www.epa.gov/enviro/facts/sdwis/search.html v:averageRating=0 v:name="Health-based Drinking Water Violations (2003 - Present)" v:attribution="U.S. Environmental Protection Agency (EPA), Enforcement & Compliance History Online (ECHO)"

property e:pg5m-3yrd t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:pg5m-3yrd t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:pg5m-3yrd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid             | indicator                                        | city          | state | date                | year | indicatorvalue | 
| ================= | ================================================ | ============= | ===== | =================== | ==== | ============== | 
| New Orleans2003   | Number of health-based drinking water violations | New Orleans   | LA    | 2003-01-01T00:00:00 | 2003 | 0              | 
| Oklahoma City2003 | Number of health-based drinking water violations | Oklahoma City | OK    | 2003-01-01T00:00:00 | 2003 | 0              | 
| Tampa2003         | Number of health-based drinking water violations | Tampa         | FL    | 2003-01-01T00:00:00 | 2003 | 0              | 
| Miami2003         | Number of health-based drinking water violations | Miami         | FL    | 2003-01-01T00:00:00 | 2003 | 0              | 
| Memphis2003       | Number of health-based drinking water violations | Memphis       | TN    | 2003-01-01T00:00:00 | 2003 | 0              | 
| Louisville2003    | Number of health-based drinking water violations | Louisville    | KY    | 2003-01-01T00:00:00 | 2003 | 0              | 
| Nashville2003     | Number of health-based drinking water violations | Nashville     | TN    | 2003-01-01T00:00:00 | 2003 | 0              | 
| Raleigh2003       | Number of health-based drinking water violations | Raleigh       | NC    | 2003-01-01T00:00:00 | 2003 | 0              | 
| Atlanta2003       | Number of health-based drinking water violations | Atlanta       | GA    | 2003-01-01T00:00:00 | 2003 | 0              | 
| Baton Rouge2003   | Number of health-based drinking water violations | Baton Rouge   | LA    | 2003-01-01T00:00:00 | 2003 | 0              | 
```