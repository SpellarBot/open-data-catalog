# Libraries - 2013 Computer Sessions by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2013-computer-sessions-by-location-1a05c) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/qrxi-q28n) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/qrxi-q28n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/qrxi-q28n/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | qrxi-q28n |
| Name | Libraries - 2013 Computer Sessions by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, technology, computer sessions |
| Created | 2013-03-13T20:14:53Z |
| Publication Date | 2014-01-15T22:39:37Z |

## Description

The Chicago Public Library offers one-hour computer sessions and 15-minute computer sessions. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Edgewater Branch reopened in a new, 2-story facility on 6/22/2013. Humboldt Park Branch closed 3/26/2012 for construction of a 5,000-square-foot addition; it reopened 2/9/2013. Albany Park Branch closed 9/22/2012 for construction of a new branch expected to open in 2014. Interim services are being provided in the Albany Park community. Gage Park Branch closed 2/22/2013-3/1/2013 for full carpet replacement and South Shore Branch was closed from 5/13/2013-6/29/2013 for repairs and renovation. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | location   | LOCATION  | text      | text        |
| No       |                | address    | ADDRESS   | text      | text        |
| Yes      | series tag     | city       | CITY      | text      | text        |
| Yes      | series tag     | zip        | ZIP       | text      | number      |
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
series e:qrxi-q28n d:2013-01-01T00:00:00.000Z t:zip=60625 t:location="Albany Park" t:city=CHICAGO m:december=0 m:march=0 m:november=0 m:may=0 m:february=0 m:april=0 m:june=0 m:ytd=0 m:january=0 m:august=0 m:july=0 m:october=0 m:september=0

series e:qrxi-q28n d:2013-01-01T00:00:00.000Z t:zip=60827 t:location=Altgeld t:city=CHICAGO m:december=2643 m:march=2923 m:november=2984 m:may=2461 m:february=2591 m:april=3060 m:june=2448 m:ytd=34407 m:january=3489 m:august=3319 m:july=2883 m:october=2893 m:september=2713

series e:qrxi-q28n d:2013-01-01T00:00:00.000Z t:zip=60632 t:location="Archer Heights" t:city=CHICAGO m:december=1728 m:march=1945 m:november=2163 m:may=1768 m:february=1759 m:april=1965 m:june=1816 m:ytd=24018 m:january=2147 m:august=2134 m:july=2065 m:october=2346 m:september=2182
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

entity e:qrxi-q28n l:"Libraries - 2013 Computer Sessions by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/qrxi-q28n

property e:qrxi-q28n t:meta.view d:2017-06-09T13:57:15.328Z v:id=qrxi-q28n v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2013 Computer Sessions by Location" v:attribution="Chicago Public Library"

property e:qrxi-q28n t:meta.view.owner d:2017-06-09T13:57:15.328Z v:id=cmhs-sm84 v:screenName="Ebony Jones" v:displayName="Ebony Jones"

property e:qrxi-q28n t:meta.view.tableauthor d:2017-06-09T13:57:15.328Z v:id=cmhs-sm84 v:screenName="Ebony Jones" v:roleName=editor v:displayName="Ebony Jones"
```

## Top Records

```ls
| location          | address                     | city    | zip   | january | february | march | april | may  | june | july | august | september | october | november | december | ytd   | 
| ================= | =========================== | ======= | ===== | ======= | ======== | ===== | ===== | ==== | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ===== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 0       | 0        | 0     | 0     | 0    | 0    | 0    | 0      | 0         | 0       | 0        | 0        | 0     | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 3489    | 2591     | 2923  | 3060  | 2461 | 2448 | 2883 | 3319   | 2713      | 2893    | 2984     | 2643     | 34407 | 
| Archer Heights    | 5055 S. Archer Avenue       | CHICAGO | 60632 | 2147    | 1759     | 1945  | 1965  | 1768 | 1816 | 2065 | 2134   | 2182      | 2346    | 2163     | 1728     | 24018 | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644 | 2388    | 1806     | 2094  | 2132  | 1928 | 2143 | 2620 | 2249   | 2165      | 2498    | 2033     | 1983     | 26039 | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634 | 2101    | 1751     | 1905  | 1956  | 1931 | 1748 | 1977 | 1999   | 2083      | 2267    | 2023     | 1580     | 23321 | 
| Avalon            | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 4228    | 3379     | 3731  | 3804  | 3914 | 4150 | 4661 | 4538   | 3923      | 4163    | 3662     | 3206     | 47359 | 
| Back of the Yards | 2111 W. 47th Street         | CHICAGO | 60609 | 0       | 0        | 0     | 0     | 0    | 0    | 0    | 100    | 1443      | 2198    | 2118     | 1732     | 7591  | 
| Beverly           | 1962 W. 95th Street         | CHICAGO | 60643 | 2798    | 2253     | 2668  | 2945  | 2767 | 2765 | 3078 | 3139   | 2692      | 2884    | 2472     | 2040     | 32501 | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640 | 2757    | 2335     | 2711  | 2718  | 2729 | 2690 | 2818 | 3088   | 2655      | 2998    | 2742     | 2649     | 32890 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 2770    | 2269     | 2510  | 2600  | 2493 | 2498 | 2826 | 3068   | 2671      | 3064    | 2820     | 2547     | 32136 | 
```