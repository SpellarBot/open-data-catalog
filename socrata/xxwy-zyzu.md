# Libraries - 2011 Visitors by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2011-visitors-by-location-fb1eb) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/xxwy-zyzu) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/xxwy-zyzu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/xxwy-zyzu/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | xxwy-zyzu |
| Name | Libraries - 2011 Visitors by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, visitors |
| Created | 2011-09-15T22:48:10Z |
| Publication Date | 2012-05-03T20:45:31Z |

## Description

The Chicago Public Library opened four new locations in 2011: Greater Grand Crossing (4/23/11); Dunning (5/6/11); Daley, Richard M.-W Humboldt (7/8/11) and Little Village (10/3/11). Edgewater closed 6/16/11 for construction of a new branch; a bookmobile for holds pickup and returns opened 6/24/11. Altgeld closed for extended periods in July and August for air conditioning installation. Back of the Yards closed permanently 8/22/11 due to repeated flooding. All locations were closed February 2-February 3 due to weather. In addition, many locations experienced sporadic closures in summer 2011 due to weather-related issues. Visits to Water Works are not counted due to its location in the Chicago Visitor Information Center.
Asterisk (*) after location name indicates that count does not reflect the total building visitor count due to location of traffic counter. Community room and program traffic are not included in totals.

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
series e:xxwy-zyzu d:2011-01-01T00:00:00.000Z t:zip_code=60625 t:location="Albany Park" t:city=CHICAGO m:december=9609 m:may=8271 m:november=9377 m:march=9050 m:april=9300 m:february=10500 m:june=10984 m:january=9604 m:ytd=117425 m:august=11078 m:july=9986 m:october=10213 m:september=9453

series e:xxwy-zyzu d:2011-01-01T00:00:00.000Z t:zip_code=60827 t:location=Altgeld t:city=CHICAGO m:december=5079 m:may=4494 m:november=5698 m:march=5207 m:april=5201 m:february=3899 m:june=5760 m:january=5809 m:ytd=58657 m:august=2414 m:july=3653 m:october=6891 m:september=4552

series e:xxwy-zyzu d:2011-01-01T00:00:00.000Z t:zip_code=60632 t:location="Archer Heights*" t:city=CHICAGO m:december=9054 m:may=9365 m:november=10011 m:march=11342 m:april=11114 m:february=9394 m:june=11247 m:january=9829 m:ytd=124653 m:august=11231 m:july=10329 m:october=11364 m:september=10373
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

entity e:xxwy-zyzu l:"Libraries - 2011 Visitors by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/xxwy-zyzu

property e:xxwy-zyzu t:meta.view v:id=xxwy-zyzu v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2011 Visitors by Location" v:attribution="Chicago Public Library"

property e:xxwy-zyzu t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:xxwy-zyzu t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| location          | address                     | city    | zip_code | january | february | march | april | may   | june  | july  | august | september | october | november | december | ytd    | 
| ================= | =========================== | ======= | ======== | ======= | ======== | ===== | ===== | ===== | ===== | ===== | ====== | ========= | ======= | ======== | ======== | ====== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625    | 9604    | 10500    | 9050  | 9300  | 8271  | 10984 | 9986  | 11078  | 9453      | 10213   | 9377     | 9609     | 117425 | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827    | 5809    | 3899     | 5207  | 5201  | 4494  | 5760  | 3653  | 2414   | 4552      | 6891    | 5698     | 5079     | 58657  | 
| Archer Heights*   | 5055 S. Archer Avenue       | CHICAGO | 60632    | 9829    | 9394     | 11342 | 11114 | 9365  | 11247 | 10329 | 11231  | 10373     | 11364   | 10011    | 9054     | 124653 | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644    | 6713    | 6250     | 7054  | 9139  | 8857  | 9586  | 8352  | 10359  | 9151      | 10016   | 8461     | 8368     | 102306 | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634    | 11556   | 9904     | 13214 | 13064 | 10969 | 12587 | 12596 | 13638  | 12542     | 13286   | 11868    | 10628    | 145852 | 
| Avalon*           | 8148 S. Stony Island Avenue | CHICAGO | 60617    | 16074   | 15046    | 14825 | 12685 | 10150 | 14235 | 12205 | 10245  | 10864     | 13085   | 11005    | 9943     | 150362 | 
| Back of the Yards | 4650 S. Damen Avenue        | CHICAGO | 60609    | 5895    | 6263     | 8204  | 8504  | 7475  | 6597  | 7910  |        | 0         | 0       | 0        | 0        | 50848  | 
| Beverly*          | 1962 W. 95th Street         | CHICAGO | 60643    | 9504    | 7135     | 10271 | 9508  | 8815  | 10869 | 11346 | 11310  | 10350     | 11098   | 10121    | 8622     | 118949 | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640    | 11848   | 10814    | 14679 | 15324 | 14672 | 17351 | 16600 | 19362  | 17892     | 17309   | 16175    | 14907    | 186933 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615    | 11535   | 9206     | 13436 | 12622 | 11417 | 13877 | 13343 | 14054  | 13241     | 14234   | 12876    | 12756    | 152597 | 
```