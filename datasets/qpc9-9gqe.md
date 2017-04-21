# Libraries - 2014 Holds Placed by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2014-holds-placed-by-location-b8698) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/qpc9-9gqe) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/qpc9-9gqe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/qpc9-9gqe/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | qpc9-9gqe |
| Name | Libraries - 2014 Holds Placed by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, holds |
| Created | 2014-06-10T16:38:25Z |
| Publication Date | 2015-01-12T19:36:17Z |

## Description

Patrons may place holds on desired materials either online or by contacting any CPL location. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 75 neighborhood branches. Albany Park Branch closed 9/22/2012 for construction of a new branch expected to open in Fall 2014. Interim services had been provided in the Albany Park community. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | location   | LOCATION  | text      | text        |
| No       |                | address    | ADDRESS   | text      | text        |
| Yes      | series tag     | city       | CITY      | text      | text        |
| Yes      | series tag     | zip_code   | ZIP CODE  | text      | text        |
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
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:qpc9-9gqe d:2014-01-01T00:00:00.000Z t:zip_code=60625 t:location="Albany Park" t:city=CHICAGO m:december=83 m:may=0 m:november=164 m:march=0 m:april=0 m:february=0 m:june=0 m:january=1 m:ytd=469 m:august=0 m:july=0 m:october=144 m:september=77

series e:qpc9-9gqe d:2014-01-01T00:00:00.000Z t:zip_code=60827 t:location=Altgeld t:city=CHICAGO m:december=23 m:may=8 m:november=38 m:march=13 m:april=6 m:february=10 m:june=24 m:january=6 m:ytd=211 m:august=18 m:july=19 m:october=23 m:september=23

series e:qpc9-9gqe d:2014-01-01T00:00:00.000Z t:zip_code=60632 t:location="Archer Heights" t:city=CHICAGO m:december=78 m:may=117 m:november=95 m:march=149 m:april=128 m:february=99 m:june=97 m:january=102 m:ytd=1412 m:august=138 m:july=131 m:october=144 m:september=134
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

metric m:ytd p:long l:YTD t:dataTypeName=number

entity e:qpc9-9gqe l:"Libraries - 2014 Holds Placed by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/qpc9-9gqe

property e:qpc9-9gqe t:meta.view v:id=qpc9-9gqe v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2014 Holds Placed by Location" v:attribution="Chicago Public Library"

property e:qpc9-9gqe t:meta.view.owner v:id=cmhs-sm84 v:screenName="Ebony Jones" v:displayName="Ebony Jones"

property e:qpc9-9gqe t:meta.view.tableauthor v:id=cmhs-sm84 v:screenName="Ebony Jones" v:roleName=editor v:displayName="Ebony Jones"
```

## Top Records

```ls
| location          | address                     | city    | zip_code | january | february | march | april | may | june | july | august | september | october | november | december | ytd  | 
| ================= | =========================== | ======= | ======== | ======= | ======== | ===== | ===== | === | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ==== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625    | 1       | 0        | 0     | 0     | 0   | 0    | 0    | 0      | 77        | 144     | 164      | 83       | 469  | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827    | 6       | 10       | 13    | 6     | 8   | 24   | 19   | 18     | 23        | 23      | 38       | 23       | 211  | 
| Archer Heights    | 5055 S. Archer Avenue       | CHICAGO | 60632    | 102     | 99       | 149   | 128   | 117 | 97   | 131  | 138    | 134       | 144     | 95       | 78       | 1412 | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644    | 15      | 18       | 32    | 42    | 37  | 52   | 57   | 29     | 42        | 44      | 27       | 40       | 435  | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634    | 114     | 71       | 150   | 176   | 132 | 202  | 214  | 235    | 178       | 181     | 203      | 192      | 2048 | 
| Avalon            | 8148 S. Stony Island Avenue | CHICAGO | 60617    | 121     | 135      | 178   | 223   | 172 | 161  | 145  | 221    | 166       | 195     | 164      | 115      | 1996 | 
| Back of the Yards | 2111 W. 47th Street         | CHICAGO | 60609    | 32      | 42       | 33    | 42    | 28  | 49   | 67   | 96     | 64        | 108     | 72       | 61       | 694  | 
| Beverly           | 1962 W. 95th Street         | CHICAGO | 60643    | 205     | 169      | 200   | 199   | 184 | 164  | 199  | 161    | 203       | 201     | 160      | 146      | 2191 | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640    | 220     | 251      | 215   | 337   | 299 | 249  | 356  | 357    | 328       | 382     | 282      | 358      | 3634 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615    | 154     | 103      | 126   | 142   | 153 | 193  | 205  | 129    | 164       | 206     | 163      | 131      | 1869 | 
```