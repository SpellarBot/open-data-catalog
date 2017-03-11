# Libraries - 2013 Holds Placed by Location

## Dataset

* [Dataset URL](https://data.cityofchicago.org/api/views/dgeh-7h9y/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/libraries-2013-holds-placed-by-location-aafc4)
* Id = dgeh-7h9y
* Name = Libraries - 2013 Holds Placed by Location
* Attribution = Chicago Public Library
* Attribution Link = http://chipublib.org
* Category = Education
* Tags = [libraries, holds]
* Created = 2013-03-13T15:42:19Z
* Publication Date = 2014-01-16T19:07:43Z
* Rows Updated = 2014-01-16T19:07:39Z

## Description

Patrons may place holds on desired materials either online or by contacting any CPL location. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Edgewater Branch reopened in a new, 2-story facility on 6/22/2013. Humboldt Park Branch closed 3/26/2012 for construction of a 5,000-square-foot addition; it reopened 2/9/2013. Albany Park Branch closed 9/22/2012 for construction of a new branch expected to open in 2014. Interim services are being provided in the Albany Park community. Gage Park Branch closed 2/22/2013-3/1/2013 for full carpet replacement and South Shore Branch was closed from 5/13/2013-6/29/2013 for repairs and renovation. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.

## Columns

```ls
| Name       | Field Name  | Data Type | Render Type | Schema Type    | Included | 
| ========== | =========== | ========= | =========== | ============== | ======== | 
| updated_at | :updated_at | meta_data | meta_data   | time           | Yes      | 
| LOCATION   | location    | text      | text        | series tag     | Yes      | 
| ADDRESS    | address     | text      | text        |                | No       | 
| CITY       | city        | text      | text        | series tag     | Yes      | 
| ZIP        | zip         | number    | text        | numeric metric | Yes      | 
| JANUARY    | january     | number    | number      | numeric metric | Yes      | 
| FEBRUARY   | february    | number    | number      | numeric metric | Yes      | 
| MARCH      | march       | number    | number      | numeric metric | Yes      | 
| APRIL      | april       | number    | number      | numeric metric | Yes      | 
| MAY        | may         | number    | number      | numeric metric | Yes      | 
| JUNE       | june        | number    | number      | numeric metric | Yes      | 
| JULY       | july        | number    | number      | numeric metric | Yes      | 
| AUGUST     | august      | number    | number      | numeric metric | Yes      | 
| SEPTEMBER  | september   | number    | number      | numeric metric | Yes      | 
| OCTOBER    | october     | number    | number      | numeric metric | Yes      | 
| NOVEMBER   | november    | number    | number      | numeric metric | Yes      | 
| DECEMBER   | december    | number    | number      | numeric metric | Yes      | 
| YTD        | ytd         | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = address
Annotation Fields = 
```

## Data Commands

```ls
series e:dgeh-7h9y d:2014-01-16T09:00:36.000Z t:location="Albany Park" t:city=CHICAGO m:zip=60625 m:may=0 m:november=18 m:april=0 m:june=0 m:december=4 m:march=0 m:february=0 m:january=0 m:ytd=63 m:august=7 m:july=0 m:october=26 m:september=8

series e:dgeh-7h9y d:2014-01-16T09:00:36.000Z t:location=Altgeld t:city=CHICAGO m:zip=60827 m:may=7 m:november=11 m:april=8 m:june=16 m:december=23 m:march=14 m:february=12 m:january=17 m:ytd=152 m:august=12 m:july=9 m:october=12 m:september=11

series e:dgeh-7h9y d:2014-01-16T09:00:36.000Z t:location="Archer Heights" t:city=CHICAGO m:zip=60632 m:may=90 m:november=73 m:april=110 m:june=85 m:december=110 m:march=85 m:february=92 m:january=110 m:ytd=1128 m:august=116 m:july=114 m:october=83 m:september=60
```

## Meta Commands

```ls
metric m:zip p:integer l:ZIP t:dataTypeName=number

metric m:january p:integer l:JANUARY t:dataTypeName=number

metric m:february p:integer l:FEBRUARY t:dataTypeName=number

metric m:march p:integer l:MARCH t:dataTypeName=number

metric m:april p:integer l:APRIL t:dataTypeName=number

metric m:may p:integer l:MAY t:dataTypeName=number

metric m:june p:integer l:JUNE t:dataTypeName=number

metric m:july p:integer l:JULY t:dataTypeName=number

metric m:august p:integer l:AUGUST t:dataTypeName=number

metric m:september p:integer l:SEPTEMBER t:dataTypeName=number

metric m:october p:integer l:OCTOBER t:dataTypeName=number

metric m:november p:integer l:NOVEMBER t:dataTypeName=number

metric m:december p:integer l:DECEMBER t:dataTypeName=number

metric m:ytd p:integer l:YTD t:dataTypeName=number

entity e:dgeh-7h9y l:"Libraries - 2013 Holds Placed by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/dgeh-7h9y

property e:dgeh-7h9y t:meta.view d:2017-03-03T14:27:31.198Z v:id=dgeh-7h9y v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2013 Holds Placed by Location" v:attribution="Chicago Public Library"

property e:dgeh-7h9y t:meta.view.owner d:2017-03-03T14:27:31.198Z v:id=cmhs-sm84 v:screenName="Ebony Jones" v:roleName=editor v:displayName="Ebony Jones"

property e:dgeh-7h9y t:meta.view.tableauthor d:2017-03-03T14:27:31.198Z v:id=cmhs-sm84 v:screenName="Ebony Jones" v:roleName=editor v:displayName="Ebony Jones"
```