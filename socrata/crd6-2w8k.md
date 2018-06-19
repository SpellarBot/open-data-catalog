# Certified Green Buildings (2005 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/certified-green-buildings-2005-present) |
| Metadata | [Link](https://data.nola.gov/api/views/crd6-2w8k) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/crd6-2w8k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/crd6-2w8k/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | crd6-2w8k |
| Name | Certified Green Buildings (2005 - Present) |
| Attribution | U.S. Green Building Council |
| Category | Housing, Land Use, and Blight |
| Created | 2015-04-28T21:51:33Z |
| Publication Date | 2016-01-25T20:53:46Z |

## Description

This data comes from the U.S. Environmental Protection Agency and is reported annually beginning in 2003. It includes data for New Orleans and several benchmark cities, including: Atlanta, Baton Rouge, Louisville, Memphis, Miami, Nashville, Oklahoma City, Raleigh, and Tampa.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
| Yes      | series tag     | city           | City           | text          | text          |
| Yes      | series tag     | state          | State          | text          | text          |
| Yes      | series tag     | indicator      | Indicator      | text          | text          |
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
series e:crd6-2w8k d:2005-01-01T00:00:00.000Z t:indicator="Total number of certified green buildings" t:city="New Orleans" t:state=LA t:rowid="New Orleans2005" m:indicatorvalue=0

series e:crd6-2w8k d:2005-01-01T00:00:00.000Z t:indicator="Total number of certified green buildings" t:city="Oklahoma City" t:state=OK t:rowid="Oklahoma City2005" m:indicatorvalue=0

series e:crd6-2w8k d:2005-01-01T00:00:00.000Z t:indicator="Total number of certified green buildings" t:city=Tampa t:state=FL t:rowid=Tampa2005 m:indicatorvalue=0
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:crd6-2w8k l:"Certified Green Buildings (2005 - Present)" t:attribution="U.S. Green Building Council" t:url=https://data.nola.gov/api/views/crd6-2w8k

property e:crd6-2w8k t:meta.view d:2017-09-25T07:28:33.323Z v:averageRating=0 v:name="Certified Green Buildings (2005 - Present)" v:attribution="U.S. Green Building Council" v:attributionLink=http://www.usgbc.org/projects v:id=crd6-2w8k v:category="Housing, Land Use, and Blight"

property e:crd6-2w8k t:meta.view.owner d:2017-09-25T07:28:33.323Z v:displayName=mschigoda v:id=ii98-542e v:screenName=mschigoda

property e:crd6-2w8k t:meta.view.tableauthor d:2017-09-25T07:28:33.323Z v:displayName=mschigoda v:roleName=publisher v:id=ii98-542e v:screenName=mschigoda

property e:crd6-2w8k t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:28:33.323Z v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid             | date                | year | city          | state | indicator                                 | indicatorvalue | 
| ================= | =================== | ==== | ============= | ===== | ========================================= | ============== | 
| New Orleans2005   | 2005-01-01T00:00:00 | 2005 | New Orleans   | LA    | Total number of certified green buildings | 0              | 
| Oklahoma City2005 | 2005-01-01T00:00:00 | 2005 | Oklahoma City | OK    | Total number of certified green buildings | 0              | 
| Tampa2005         | 2005-01-01T00:00:00 | 2005 | Tampa         | FL    | Total number of certified green buildings | 0              | 
| Miami2005         | 2005-01-01T00:00:00 | 2005 | Miami         | FL    | Total number of certified green buildings | 0              | 
| Memphis2005       | 2005-01-01T00:00:00 | 2005 | Memphis       | TN    | Total number of certified green buildings | 0              | 
| Louisville2005    | 2005-01-01T00:00:00 | 2005 | Louisville    | KY    | Total number of certified green buildings | 0              | 
| Nashville2005     | 2005-01-01T00:00:00 | 2005 | Nashville     | TN    | Total number of certified green buildings | 1              | 
| Raleigh2005       | 2005-01-01T00:00:00 | 2005 | Raleigh       | NC    | Total number of certified green buildings | 0              | 
| Atlanta2005       | 2005-01-01T00:00:00 | 2005 | Atlanta       | GA    | Total number of certified green buildings | 13             | 
| Baton Rouge2005   | 2005-01-01T00:00:00 | 2005 | Baton Rouge   | LA    | Total number of certified green buildings | 0              | 
```