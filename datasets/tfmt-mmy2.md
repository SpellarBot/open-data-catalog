# Libraries - 2011 Circulation by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2011-circulation-by-location-79bde) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/tfmt-mmy2) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/tfmt-mmy2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/tfmt-mmy2/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | tfmt-mmy2 |
| Name | Libraries - 2011 Circulation by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | performance metrics, libraries, circulation |
| Created | 2011-09-15T22:17:01Z |
| Publication Date | 2012-06-22T13:30:25Z |

## Description

Circulation figures include new checkouts as well as renewals. The Chicago Public Library opened four new locations in 2011: Greater Grand Crossing (4/23/11); Dunning (5/6/11); Daley, Richard M.-W Humboldt (7/8/11) and Little Village (10/3/11). Edgewater closed 6/16/11 for construction of a new branch; a bookmobile for holds pickup and returns opened 6/24/11. Altgeld closed for extended periods in July and August for air conditioning installation. Back of the Yards closed permanently 8/22/11 due to repeated flooding. All locations were closed February 2-February 3 due to weather. In addition, many locations experienced sporadic closures in summer 2011 due to weather-related issues.

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
series e:tfmt-mmy2 d:2011-01-01T00:00:00.000Z t:zip_code=60625 t:location="Albany Park" t:city=CHICAGO m:december=9934 m:may=8865 m:november=10567 m:march=9702 m:april=9344 m:february=7023 m:june=11650 m:january=8427 m:ytd=120059 m:august=11306 m:july=11778 m:october=10997 m:september=10466

series e:tfmt-mmy2 d:2011-01-01T00:00:00.000Z t:zip_code=60827 t:location=Altgeld t:city=CHICAGO m:december=692 m:may=816 m:november=787 m:march=854 m:april=804 m:february=708 m:june=870 m:january=1258 m:ytd=9611 m:august=480 m:july=713 m:october=927 m:september=702

series e:tfmt-mmy2 d:2011-01-01T00:00:00.000Z t:zip_code=60632 t:location="Archer Heights" t:city=CHICAGO m:december=7865 m:may=7472 m:november=8809 m:march=9329 m:april=9124 m:february=6899 m:june=8314 m:january=8104 m:ytd=101951 m:august=9177 m:july=8116 m:october=9709 m:september=9033
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

entity e:tfmt-mmy2 l:"Libraries - 2011 Circulation by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/tfmt-mmy2

property e:tfmt-mmy2 t:meta.view v:id=tfmt-mmy2 v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2011 Circulation by Location" v:attribution="Chicago Public Library"

property e:tfmt-mmy2 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:tfmt-mmy2 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| location          | address                     | city    | zip_code | january | february | march | april | may   | june  | july  | august | september | october | november | december | ytd    | 
| ================= | =========================== | ======= | ======== | ======= | ======== | ===== | ===== | ===== | ===== | ===== | ====== | ========= | ======= | ======== | ======== | ====== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625    | 8427    | 7023     | 9702  | 9344  | 8865  | 11650 | 11778 | 11306  | 10466     | 10997   | 10567    | 9934     | 120059 | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827    | 1258    | 708      | 854   | 804   | 816   | 870   | 713   | 480    | 702       | 927     | 787      | 692      | 9611   | 
| Archer Heights    | 5055 S. Archer Avenue       | CHICAGO | 60632    | 8104    | 6899     | 9329  | 9124  | 7472  | 8314  | 8116  | 9177   | 9033      | 9709    | 8809     | 7865     | 101951 | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644    | 1755    | 1316     | 1942  | 2200  | 2133  | 2359  | 2080  | 2405   | 2417      | 2571    | 2233     | 2116     | 25527  | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634    | 12593   | 11791    | 14807 | 14382 | 11754 | 14402 | 14605 | 15164  | 14306     | 15357   | 14069    | 12404    | 165634 | 
| Avalon            | 8148 S. Stony Island Avenue | CHICAGO | 60617    | 5664    | 4367     | 5937  | 5980  | 5596  | 6286  | 6184  | 6933   | 6574      | 6955    | 6113     | 5295     | 71884  | 
| Back of the Yards | 4650 S. Damen Avenue        | CHICAGO | 60609    | 5485    | 5171     | 6024  | 6592  | 5170  | 4033  | 4832  | 3129   | 34        | 0       | 0        | 0        | 40470  | 
| Beverly           | 1962 W. 95th Street         | CHICAGO | 60643    | 8049    | 7473     | 9239  | 9449  | 8299  | 10053 | 10086 | 9595   | 8439      | 9610    | 8749     | 7578     | 106619 | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640    | 8875    | 7424     | 10887 | 11298 | 11739 | 15133 | 17067 | 18348  | 15412     | 15517   | 14860    | 15243    | 161803 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615    | 9351    | 7938     | 10687 | 10760 | 9879  | 11639 | 11133 | 12428  | 11102     | 11781   | 11179    | 11005    | 128882 | 
```