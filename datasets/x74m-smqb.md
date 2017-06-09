# Libraries - 2013 Visitors by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2013-visitors-by-location-efe12) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/x74m-smqb) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/x74m-smqb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/x74m-smqb/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | x74m-smqb |
| Name | Libraries - 2013 Visitors by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, visitors |
| Created | 2013-04-11T17:41:50Z |
| Publication Date | 2014-01-15T22:24:21Z |

## Description

The Chicago Public Library has more than 70 locations. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Edgewater Branch reopened in a new, 2-story facility on 6/22/2013. Humboldt Park Branch closed 3/26/2012 for construction of a 5,000-square-foot addition; it reopened 2/9/2013. Albany Park Branch closed 9/22/2012 for construction of a new branch expected to open in 2014. Interim services are being provided in the Albany Park community. Gage Park Branch closed 2/22/2013-3/1/2013 for full carpet replacement and South Shore Branch was closed from 5/13/2013-6/29/2013 for repairs and renovation. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | location   | LOCATION  | text      | text        |
| No       |                | address    | ADDRESS   | text      | text        |
| Yes      | series tag     | city       | CITY      | text      | text        |
| Yes      | series tag     | zip        | ZIP       | text      | text        |
| Yes      | numeric metric | january    | JANUARY   | number    | number      |
| Yes      | numeric metric | february   | FEBRUARY  | number    | number      |
| Yes      | numeric metric | march      | MARCH     | number    | number      |
| Yes      | numeric metric | april      | APRIL     | number    | number      |
| Yes      | numeric metric | may        | MAY       | number    | number      |
| Yes      | numeric metric | june       | JUNE      | number    | number      |
| Yes      | numeric metric | july       | JULY      | number    | number      |
| Yes      | numeric metric | august     | AUGUST    | number    | number      |
| Yes      | numeric metric | september  | SEPTEMBER | number    | number      |
| Yes      | numeric metric | october    | OCTOBER   | number    | number      |
| Yes      | numeric metric | november   | NOVEMBER  | number    | number      |
| Yes      | numeric metric | december   | DECEMBER  | number    | number      |
| Yes      | numeric metric | ytd        | YTD       | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:x74m-smqb d:2013-01-01T00:00:00.000Z t:zip=60625 t:location="Albany Park" t:city=CHICAGO m:december=36 m:march=0 m:november=89 m:may=0 m:february=0 m:april=0 m:june=0 m:ytd=421 m:january=0 m:august=74 m:july=0 m:october=117 m:september=105

series e:x74m-smqb d:2013-01-01T00:00:00.000Z t:zip=60827 t:location=Altgeld t:city=CHICAGO m:december=4906 m:march=5301 m:november=5277 m:may=5176 m:february=4014 m:april=5668 m:june=5142 m:ytd=63052 m:january=5741 m:august=6104 m:july=5276 m:october=5228 m:september=5219

series e:x74m-smqb d:2013-01-01T00:00:00.000Z t:zip=60632 t:location="Archer Heights*" t:city=CHICAGO m:december=7382 m:march=9405 m:november=9448 m:may=8054 m:february=7994 m:april=9712 m:june=8470 m:ytd=110419 m:january=9744 m:august=9768 m:july=10180 m:october=10915 m:september=9347
```

## Meta Commands

```ls
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

entity e:x74m-smqb l:"Libraries - 2013 Visitors by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/x74m-smqb

property e:x74m-smqb t:meta.view d:2017-06-09T13:53:28.761Z v:id=x74m-smqb v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2013 Visitors by Location" v:attribution="Chicago Public Library"

property e:x74m-smqb t:meta.view.owner d:2017-06-09T13:53:28.761Z v:id=cmhs-sm84 v:screenName="Ebony Jones" v:displayName="Ebony Jones"

property e:x74m-smqb t:meta.view.tableauthor d:2017-06-09T13:53:28.761Z v:id=cmhs-sm84 v:screenName="Ebony Jones" v:roleName=editor v:displayName="Ebony Jones"
```

## Top Records

```ls
| location          | address                     | city    | zip   | january | february | march | april | may   | june  | july  | august | september | october | november | december | ytd    | 
| ================= | =========================== | ======= | ===== | ======= | ======== | ===== | ===== | ===== | ===== | ===== | ====== | ========= | ======= | ======== | ======== | ====== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 0       | 0        | 0     | 0     | 0     | 0     | 0     | 74     | 105       | 117     | 89       | 36       | 421    | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 5741    | 4014     | 5301  | 5668  | 5176  | 5142  | 5276  | 6104   | 5219      | 5228    | 5277     | 4906     | 63052  | 
| Archer Heights*   | 5055 S. Archer Avenue       | CHICAGO | 60632 | 9744    | 7994     | 9405  | 9712  | 8054  | 8470  | 10180 | 9768   | 9347      | 10915   | 9448     | 7382     | 110419 | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644 | 6977    | 5146     | 7208  | 8120  | 7495  | 8600  | 9219  | 7883   | 8052      | 7920    | 7429     | 5713     | 89762  | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634 | 10501   | 9760     | 10781 | 10977 | 10542 | 10172 | 12077 | 11090  | 10710     | 11275   | 10448    | 8064     | 126397 | 
| Avalon*           | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 10903   | 8801     | 9864  | 11433 | 11864 | 11495 | 12639 | 12746  | 11460     | 11817   | 5994     | 5034     | 124050 | 
| Back of the Yards | 2111 W. 47th Street         | CHICAGO | 60609 | 0       | 0        | 0     | 0     | 0     | 0     | 0     | 0      | 6273      | 6984    | 5860     | 4642     | 23759  | 
| Beverly*          | 1962 W. 95th Street         | CHICAGO | 60643 | 8380    | 6961     | 8314  | 8949  | 7719  | 8835  | 10792 | 9391   | 9071      | 10016   | 8073     | 6474     | 102975 | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640 | 14615   | 12971    | 15317 | 15310 | 15801 | 14648 | 16781 | 15559  | 13767     | 15129   | 13110    | 11998    | 175006 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 12761   | 9941     | 11334 | 11870 | 11166 | 12764 | 13032 | 11882  | 10636     | 12695   | 10725    | 10748    | 139554 | 
```