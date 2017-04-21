# Libraries - 2011 Computer Sessions by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2011-computer-sessions-by-location-7322f) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/6uah-qehh) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/6uah-qehh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/6uah-qehh/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 6uah-qehh |
| Name | Libraries - 2011 Computer Sessions by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, technology, computer sessions |
| Created | 2011-09-15T22:25:42Z |
| Publication Date | 2012-01-18T03:19:09Z |

## Description

The Chicago Public Library offers one-hour computer sessions and 15-minute computer sessions. The Chicago Public Library opened four new locations in 2011: Greater Grand Crossing (4/23/11); Dunning (5/6/11); Daley, Richard M.-W Humboldt (7/8/11) and Little Village (10/3/11). Edgewater closed 6/16/11 for construction of a new branch; a bookmobile for holds pickup and returns opened 6/24/11. Altgeld closed for extended periods in July and August for air conditioning installation. Back of the Yards closed permanently 8/22/11 due to repeated flooding. All locations were closed February 2-February 3 due to weather. In addition, many locations experienced sporadic closures in summer 2011 due to weather-related issues.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | location   | LOCATION  | text      | text        |
| No       |                | address    | ADDRESS   | text      | text        |
| Yes      | series tag     | city       | CITY      | text      | text        |
| Yes      | series tag     | zip_code   | ZIP CODE  | text      | number      |
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
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:6uah-qehh d:2011-01-01T00:00:00.000Z t:zip_code=60625 t:location="Albany Park" t:city=CHICAGO m:december=1594 m:may=1683 m:november=1729 m:march=1735 m:april=1841 m:february=1296 m:june=2138 m:january=1666 m:ytd=21966 m:august=2434 m:july=2267 m:october=1837 m:september=1746

series e:6uah-qehh d:2011-01-01T00:00:00.000Z t:zip_code=60827 t:location=Altgeld t:city=CHICAGO m:december=3171 m:may=2509 m:november=3460 m:march=2286 m:april=2647 m:february=1895 m:june=2928 m:january=3036 m:ytd=31782 m:august=1345 m:july=1970 m:october=3713 m:september=2822

series e:6uah-qehh d:2011-01-01T00:00:00.000Z t:zip_code=60632 t:location="Archer Heights" t:city=CHICAGO m:december=1843 m:may=1979 m:november=2138 m:march=2332 m:april=2265 m:february=1712 m:june=2287 m:january=2069 m:ytd=25321 m:august=2365 m:july=1930 m:october=2260 m:september=2141
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

entity e:6uah-qehh l:"Libraries - 2011 Computer Sessions by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/6uah-qehh

property e:6uah-qehh t:meta.view v:id=6uah-qehh v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2011 Computer Sessions by Location" v:attribution="Chicago Public Library"

property e:6uah-qehh t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:6uah-qehh t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| location          | address                     | city    | zip_code | january | february | march | april | may  | june | july | august | september | october | november | december | ytd   | 
| ================= | =========================== | ======= | ======== | ======= | ======== | ===== | ===== | ==== | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ===== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625    | 1666    | 1296     | 1735  | 1841  | 1683 | 2138 | 2267 | 2434   | 1746      | 1837    | 1729     | 1594     | 21966 | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827    | 3036    | 1895     | 2286  | 2647  | 2509 | 2928 | 1970 | 1345   | 2822      | 3713    | 3460     | 3171     | 31782 | 
| Archer Heights    | 5055 S. Archer Avenue       | CHICAGO | 60632    | 2069    | 1712     | 2332  | 2265  | 1979 | 2287 | 1930 | 2365   | 2141      | 2260    | 2138     | 1843     | 25321 | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644    | 2879    | 2141     | 2796  | 2897  | 2704 | 3055 | 2515 | 3080   | 2842      | 2995    | 2752     | 2551     | 33207 | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634    | 2442    | 2801     | 4403  | 4503  | 3728 | 2554 | 2397 | 2647   | 2464      | 2552    | 2425     | 2177     | 35093 | 
| Avalon            | 8148 S. Stony Island Avenue | CHICAGO | 60617    | 4090    | 2945     | 4267  | 4279  | 4006 | 4292 | 4461 | 5109   | 4697      | 5071    | 4464     | 4090     | 51771 | 
| Back of the Yards | 4650 S. Damen Avenue        | CHICAGO | 60609    | 2217    | 1647     | 2304  | 2426  | 2135 | 1524 | 2117 | 1732   | 0         | 0       | 0        | 0        | 16102 | 
| Beverly           | 1962 W. 95th Street         | CHICAGO | 60643    | 2595    | 2063     | 2941  | 2887  | 2752 | 2833 | 2967 | 3416   | 3072      | 3206    | 2985     | 2717     | 34434 | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640    | 2104    | 1710     | 2519  | 2539  | 2429 | 2947 | 2801 | 3101   | 2674      | 2802    | 2572     | 2287     | 30485 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615    | 2623    | 1972     | 2788  | 2859  | 2670 | 3169 | 2755 | 3366   | 2839      | 3123    | 2986     | 2647     | 33797 | 
```