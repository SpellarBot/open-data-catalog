# Libraries - 2011 Holds Filled by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2011-holds-filled-by-location-7ea81) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ngxm-jbc3) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ngxm-jbc3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ngxm-jbc3/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ngxm-jbc3 |
| Name | Libraries - 2011 Holds Filled by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, holds |
| Created | 2011-09-15T22:35:00Z |
| Publication Date | 2012-01-17T16:20:25Z |

## Description

Materials pulled to fulfill patron holds. The Chicago Public Library opened four new locations in 2011: Greater Grand Crossing (4/23/11); Dunning (5/6/11); Daley, Richard M.-W Humboldt (7/8/11) and Little Village (10/3/11). Edgewater closed 6/16/11 for construction of a new branch; a bookmobile for holds pickup and returns opened 6/24/11. Altgeld closed for extended periods in July and August for air conditioning installation. Back of the Yards closed permanently 8/22/11 due to repeated flooding. All locations were closed February 2-February 3 due to weather. In addition, many locations experienced sporadic closures in summer 2011 due to weather-related issues.

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
series e:ngxm-jbc3 d:2011-01-01T00:00:00.000Z t:zip_code=60625 t:location="Albany Park" t:city=CHICAGO m:december=2608 m:may=2101 m:november=2774 m:march=2723 m:april=2395 m:february=2081 m:june=2626 m:january=2107 m:ytd=30675 m:august=2913 m:july=2881 m:october=2611 m:september=2855

series e:ngxm-jbc3 d:2011-01-01T00:00:00.000Z t:zip_code=60827 t:location=Altgeld t:city=CHICAGO m:december=627 m:may=673 m:november=697 m:march=728 m:april=642 m:february=626 m:june=660 m:january=889 m:ytd=7975 m:august=363 m:july=599 m:october=726 m:september=745

series e:ngxm-jbc3 d:2011-01-01T00:00:00.000Z t:zip_code=60632 t:location="Archer Heights" t:city=CHICAGO m:december=1868 m:may=1823 m:november=1985 m:march=2104 m:april=1877 m:february=1638 m:june=1880 m:january=1567 m:ytd=22838 m:august=2149 m:july=1864 m:october=1975 m:september=2108
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

entity e:ngxm-jbc3 l:"Libraries - 2011 Holds Filled by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/ngxm-jbc3

property e:ngxm-jbc3 t:meta.view v:id=ngxm-jbc3 v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2011 Holds Filled by Location" v:attribution="Chicago Public Library"

property e:ngxm-jbc3 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:ngxm-jbc3 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| location          | address                     | city    | zip_code | january | february | march | april | may  | june | july | august | september | october | november | december | ytd   | 
| ================= | =========================== | ======= | ======== | ======= | ======== | ===== | ===== | ==== | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ===== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625    | 2107    | 2081     | 2723  | 2395  | 2101 | 2626 | 2881 | 2913   | 2855      | 2611    | 2774     | 2608     | 30675 | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827    | 889     | 626      | 728   | 642   | 673  | 660  | 599  | 363    | 745       | 726     | 697      | 627      | 7975  | 
| Archer Heights    | 5055 S. Archer Avenue       | CHICAGO | 60632    | 1567    | 1638     | 2104  | 1877  | 1823 | 1880 | 1864 | 2149   | 2108      | 1975    | 1985     | 1868     | 22838 | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644    | 730     | 737      | 949   | 866   | 946  | 922  | 991  | 1029   | 1109      | 1167    | 1078     | 994      | 11518 | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634    | 2955    | 3190     | 3656  | 3509  | 3321 | 3480 | 3689 | 4060   | 4081      | 3816    | 3691     | 3585     | 43033 | 
| Avalon            | 8148 S. Stony Island Avenue | CHICAGO | 60617    | 1590    | 1513     | 2075  | 1766  | 1920 | 1816 | 1773 | 2169   | 2127      | 2055    | 1972     | 1898     | 22674 | 
| Back of the Yards | 4650 S. Damen Avenue        | CHICAGO | 60609    | 1002    | 922      | 1215  | 1075  | 1053 | 877  | 1059 | 27     | 28        | 0       | 0        | 0        | 7258  | 
| Beverly           | 1962 W. 95th Street         | CHICAGO | 60643    | 2788    | 3020     | 3292  | 2826  | 2775 | 2817 | 2919 | 3471   | 3117      | 3188    | 3013     | 2580     | 35806 | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640    | 3685    | 3477     | 4641  | 4027  | 3954 | 4727 | 5273 | 5888   | 5788      | 5795    | 5411     | 5610     | 58276 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615    | 3365    | 3167     | 3915  | 3423  | 3300 | 3401 | 3570 | 4331   | 3904      | 4061    | 4036     | 3917     | 44390 | 
```