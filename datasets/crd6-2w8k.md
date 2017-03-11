# Certified Green Buildings (2005 - Present)

## Dataset

* [Dataset URL](https://data.nola.gov/api/views/crd6-2w8k/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/certified-green-buildings-2005-present)
* Id = crd6-2w8k
* Name = Certified Green Buildings (2005 - Present)
* Attribution = U.S. Green Building Council
* Attribution Link = http://www.usgbc.org/projects
* Category = Housing, Land Use, and Blight
* Created = 2015-04-28T21:51:33Z
* Publication Date = 2016-01-25T20:53:46Z
* Rows Updated = 2016-01-25T20:51:43Z

## Description

This data comes from the U.S. Environmental Protection Agency and is reported annually beginning in 2003. It includes data for New Orleans and several benchmark cities, including: Atlanta, Baton Rouge, Louisville, Memphis, Miami, Nashville, Oklahoma City, Raleigh, and Tampa.

## Columns

```ls
| Name           | Field Name     | Data Type     | Render Type   | Schema Type    | Included | 
| ============== | ============== | ============= | ============= | ============== | ======== | 
| RowID          | rowid          | text          | text          | series tag     | Yes      | 
| Date           | date           | calendar_date | calendar_date | time           | Yes      | 
| Year           | year           | number        | number        |                | No       | 
| City           | city           | text          | text          | series tag     | Yes      | 
| State          | state          | text          | text          | series tag     | Yes      | 
| Indicator      | indicator      | text          | text          | series tag     | Yes      | 
| IndicatorValue | indicatorvalue | number        | number        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = year
Annotation Fields = 
```

## Data Commands

```ls
series e:crd6-2w8k d:2005-01-01T00:00:00.000Z t:indicator="Total number of certified green buildings" t:state=LA t:rowid="New Orleans2005" t:city="New Orleans" m:indicatorvalue=0

series e:crd6-2w8k d:2005-01-01T00:00:00.000Z t:indicator="Total number of certified green buildings" t:state=OK t:rowid="Oklahoma City2005" t:city="Oklahoma City" m:indicatorvalue=0

series e:crd6-2w8k d:2005-01-01T00:00:00.000Z t:indicator="Total number of certified green buildings" t:state=FL t:rowid=Tampa2005 t:city=Tampa m:indicatorvalue=0
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:crd6-2w8k l:"Certified Green Buildings (2005 - Present)" t:attribution="U.S. Green Building Council" t:url=https://data.nola.gov/api/views/crd6-2w8k

property e:crd6-2w8k t:meta.view d:2017-03-03T14:23:27.892Z v:id=crd6-2w8k v:category="Housing, Land Use, and Blight" v:attributionLink=http://www.usgbc.org/projects v:averageRating=0 v:name="Certified Green Buildings (2005 - Present)" v:attribution="U.S. Green Building Council"

property e:crd6-2w8k t:meta.view.owner d:2017-03-03T14:23:27.892Z v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:crd6-2w8k t:meta.view.tableauthor d:2017-03-03T14:23:27.892Z v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:crd6-2w8k t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:23:27.892Z v:Contact_Email=data@nola.gov
```