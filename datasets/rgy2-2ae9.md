# Libraries - 2011 Holds Placed by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2011-holds-placed-by-location-dae10) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/rgy2-2ae9) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/rgy2-2ae9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/rgy2-2ae9/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | rgy2-2ae9 |
| Name | Libraries - 2011 Holds Placed by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, holds |
| Created | 2011-09-15T22:39:19Z |
| Publication Date | 2012-06-22T13:32:44Z |

## Description

Patrons may place holds on desired materials either online or by contacting any CPL location. The Chicago Public Library opened four new locations in 2011: Greater Grand Crossing (4/23/11); Dunning (5/6/11); Daley, Richard M.-W Humboldt (7/8/11) and Little Village (10/3/11). Edgewater closed 6/16/11 for construction of a new branch; a bookmobile for holds pickup and returns opened 6/24/11. Altgeld closed for extended periods in July and August for air conditioning installation. Back of the Yards closed permanently 8/22/11 due to repeated flooding. All locations were closed February 2-February 3 due to weather. In addition, many locations experienced sporadic closures in summer 2011 due to weather-related issues.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | location   | LOCATION  | text      | text        |
| No       |                | address    | ADDRESS   | text      | text        |
| Yes      | series tag     | city       | CITY      | text      | text        |
| Yes      | series tag     | april      | ZIP CODE  | text      | number      |
| Yes      | numeric metric | january    | JANUARY   | number    | number      |
| Yes      | numeric metric | february   | FEBRUARY  | number    | number      |
| Yes      | numeric metric | march      | MARCH     | number    | number      |
| Yes      | numeric metric | april_2    | APRIL     | number    | number      |
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
series e:rgy2-2ae9 d:2011-01-01T00:00:00.000Z t:april=60625 t:location="Albany Park" t:city=CHICAGO m:december=267 m:may=200 m:november=233 m:march=227 m:february=139 m:june=264 m:april_2=178 m:january=169 m:ytd=2641 m:august=186 m:july=263 m:october=282 m:september=233

series e:rgy2-2ae9 d:2011-01-01T00:00:00.000Z t:april=60827 t:location=Altgeld t:city=CHICAGO m:december=25 m:may=32 m:november=22 m:march=27 m:february=17 m:june=15 m:april_2=12 m:january=15 m:ytd=229 m:august=7 m:july=18 m:october=22 m:september=17

series e:rgy2-2ae9 d:2011-01-01T00:00:00.000Z t:april=60632 t:location="Archer Heights" t:city=CHICAGO m:december=90 m:may=107 m:november=123 m:march=86 m:february=57 m:june=99 m:april_2=156 m:january=76 m:ytd=1159 m:august=88 m:july=86 m:october=113 m:september=78
```

## Meta Commands

```ls
metric m:january p:integer l:JANUARY t:dataTypeName=number

metric m:february p:integer l:FEBRUARY t:dataTypeName=number

metric m:march p:integer l:MARCH t:dataTypeName=number

metric m:april_2 p:integer l:APRIL t:dataTypeName=number

metric m:may p:integer l:MAY t:dataTypeName=number

metric m:june p:integer l:JUNE t:dataTypeName=number

metric m:july p:integer l:JULY t:dataTypeName=number

metric m:august p:integer l:AUGUST t:dataTypeName=number

metric m:september p:integer l:SEPTEMBER t:dataTypeName=number

metric m:october p:integer l:OCTOBER t:dataTypeName=number

metric m:november p:integer l:NOVEMBER t:dataTypeName=number

metric m:december p:integer l:DECEMBER t:dataTypeName=number

metric m:ytd p:integer l:YTD t:dataTypeName=number

entity e:rgy2-2ae9 l:"Libraries - 2011 Holds Placed by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/rgy2-2ae9

property e:rgy2-2ae9 t:meta.view v:id=rgy2-2ae9 v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2011 Holds Placed by Location" v:attribution="Chicago Public Library"

property e:rgy2-2ae9 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:rgy2-2ae9 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| location          | address                     | city    | april | january | february | march | april_2 | may | june | july | august | september | october | november | december | ytd  | 
| ================= | =========================== | ======= | ===== | ======= | ======== | ===== | ======= | === | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ==== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 169     | 139      | 227   | 178     | 200 | 264  | 263  | 186    | 233       | 282     | 233      | 267      | 2641 | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 15      | 17       | 27    | 12      | 32  | 15   | 18   | 7      | 17        | 22      | 22       | 25       | 229  | 
| Archer Heights    | 5055 S. Archer Avenue       | CHICAGO | 60632 | 76      | 57       | 86    | 156     | 107 | 99   | 86   | 88     | 78        | 113     | 123      | 90       | 1159 | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644 | 25      | 9        | 5     | 29      | 27  | 19   | 19   | 18     | 22        | 16      | 22       | 24       | 235  | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634 | 163     | 135      | 282   | 247     | 207 | 177  | 182  | 186    | 231       | 178     | 151      | 158      | 2297 | 
| Avalon            | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 185     | 129      | 248   | 223     | 260 | 256  | 322  | 300    | 373       | 373     | 238      | 242      | 3149 | 
| Back of the Yards | 4650 S. Damen Avenue        | CHICAGO | 60609 | 63      | 50       | 101   | 67      | 87  | 60   | 43   | 0      | 1         | 0       | 0        | 0        | 472  | 
| Beverly           | 1962 W. 95th Street         | CHICAGO | 60643 | 280     | 164      | 243   | 222     | 175 | 254  | 297  | 257    | 217       | 226     | 221      | 164      | 2720 | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640 | 299     | 222      | 275   | 277     | 323 | 372  | 449  | 407    | 437       | 422     | 380      | 491      | 4354 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 153     | 95       | 157   | 106     | 109 | 116  | 174  | 148    | 152       | 144     | 144      | 95       | 1593 | 
```