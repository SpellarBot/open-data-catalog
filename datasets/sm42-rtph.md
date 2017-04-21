# Libraries - 2014 Computer Sessions by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2014-computer-sessions-by-location-c94e0) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/sm42-rtph) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/sm42-rtph/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/sm42-rtph/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | sm42-rtph |
| Name | Libraries - 2014 Computer Sessions by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, technology, computer sessions |
| Created | 2014-03-28T19:34:06Z |
| Publication Date | 2015-03-27T15:51:06Z |

## Description

The Chicago Public Library offers one-hour computer sessions and 15-minute computer sessions. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Edgewater Branch reopened in a new, 2-story facility on 6/22/2013. Humboldt Park Branch closed 3/26/2012 for construction of a 5,000-square-foot addition; it reopened 2/9/2013. Albany Park Branch closed 9/22/2012 for construction of a new branch expected to open in 2014. Interim services are being provided in the Albany Park community. Gage Park Branch closed 2/22/2013-3/1/2013 for full carpet replacement and South Shore Branch was closed from 5/13/2013-6/29/2013 for repairs and renovation. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.

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
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:sm42-rtph d:2014-01-01T00:00:00.000Z t:zip=60625 t:location="Albany Park" t:city=CHICAGO m:december=2443 m:may=0 m:november=2653 m:march=0 m:april=0 m:february=0 m:june=0 m:january=0 m:ytd=9546 m:august=0 m:july=0 m:october=2838 m:september=1612

series e:sm42-rtph d:2014-01-01T00:00:00.000Z t:zip=60827 t:location=Altgeld t:city=CHICAGO m:december=2659 m:may=2292 m:november=2743 m:march=2237 m:april=2457 m:february=2227 m:june=2800 m:january=2560 m:ytd=31304 m:august=2761 m:july=3012 m:october=2843 m:september=2713

series e:sm42-rtph d:2014-01-01T00:00:00.000Z t:zip=60632 t:location="Archer Heights" t:city=CHICAGO m:december=2020 m:may=2072 m:november=2238 m:march=1958 m:april=2215 m:february=1594 m:june=2108 m:january=1612 m:ytd=24949 m:august=2145 m:july=2256 m:october=2586 m:september=2145
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

entity e:sm42-rtph l:"Libraries - 2014 Computer Sessions by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/sm42-rtph

property e:sm42-rtph t:meta.view v:id=sm42-rtph v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2014 Computer Sessions by Location" v:attribution="Chicago Public Library"

property e:sm42-rtph t:meta.view.owner v:id=cmhs-sm84 v:screenName="Ebony Jones" v:displayName="Ebony Jones"

property e:sm42-rtph t:meta.view.tableauthor v:id=cmhs-sm84 v:screenName="Ebony Jones" v:roleName=editor v:displayName="Ebony Jones"
```

## Top Records

```ls
| location          | address                     | city    | zip   | january | february | march | april | may  | june | july | august | september | october | november | december | ytd   | 
| ================= | =========================== | ======= | ===== | ======= | ======== | ===== | ===== | ==== | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ===== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 0       | 0        | 0     | 0     | 0    | 0    | 0    | 0      | 1612      | 2838    | 2653     | 2443     | 9546  | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 2560    | 2227     | 2237  | 2457  | 2292 | 2800 | 3012 | 2761   | 2713      | 2843    | 2743     | 2659     | 31304 | 
| Archer Heights    | 5055 S. Archer Avenue       | CHICAGO | 60632 | 1612    | 1594     | 1958  | 2215  | 2072 | 2108 | 2256 | 2145   | 2145      | 2586    | 2238     | 2020     | 24949 | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644 | 1878    | 1544     | 1883  | 2130  | 1894 | 2198 | 2662 | 2451   | 2316      | 2480    | 1923     | 1945     | 25304 | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634 | 1539    | 1505     | 1842  | 1895  | 1811 | 1808 | 1848 | 1888   | 1830      | 2059    | 1735     | 1749     | 21509 | 
| Avalon            | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 3486    | 2971     | 3620  | 4051  | 3811 | 4359 | 1496 | 3916   | 4562      | 4502    | 3755     | 3732     | 44261 | 
| Back of the Yards | 2111 W. 47th Street         | CHICAGO | 60609 | 1638    | 1496     | 1828  | 2198  | 2105 | 1934 | 2425 | 2905   | 2470      | 2743    | 2742     | 2387     | 26871 | 
| Beverly           | 1962 W. 95th Street         | CHICAGO | 60643 | 2174    | 2136     | 2423  | 2691  | 2374 | 2608 | 2684 | 2721   | 2728      | 3169    | 2354     | 2423     | 30485 | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640 | 2824    | 2333     | 2630  | 2968  | 2743 | 2993 | 3223 | 3549   | 3429      | 3518    | 3223     | 3321     | 36754 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 2247    | 2098     | 2529  | 2871  | 2667 | 2727 | 3287 | 3139   | 3070      | 2889    | 2510     | 2651     | 32685 | 
```