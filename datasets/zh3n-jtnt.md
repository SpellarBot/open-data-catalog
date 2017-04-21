# Libraries - 2012 Visitors by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2012-visitors-by-location-c46af) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/zh3n-jtnt) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/zh3n-jtnt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/zh3n-jtnt/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | zh3n-jtnt |
| Name | Libraries - 2012 Visitors by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, visitors |
| Created | 2012-02-21T17:31:04Z |
| Publication Date | 2013-04-11T16:38:28Z |

## Description

The Chicago Public Library has more than 70 locations.   In January all branch locations were closed on Monday, January 9, Monday, January 23 and Monday, January 30. Beginning in February, all branch locations restored partial Monday hours, from 2 p.m. to 6 p.m. On June 18, all branch locations restored full Monday hours. Edgewater closed 6/16/11 for construction of a new branch scheduled to open in mid-2013. The library?s bookmobile opened 6/24/11 for Edgewater holds pickup and returns. Douglass closed for 10 days in February for roof repairs. Humboldt Park closed 3/26/12 for facility improvements and expansion. Lincoln Park closed for four days in August for replacement of the air conditioning system. Many locations experienced sporadic closures in summer 2012 due to air conditioning issues and area power outages. Albany Park closed 9/22/12 for construction of a new branch and will remain closed until 2014. Brighton Park, Jefferson Park and Portage Cragin were closed 11/26/12-12/7/12 for replacement of their HVAC systems.
	
* Count does not reflect the total building visitor count due to location of traffic counter. Community room and program traffic are not included in totals.

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
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:zh3n-jtnt d:2012-01-01T00:00:00.000Z t:zip=60625 t:location="Albany Park" t:city=CHICAGO m:december=0 m:may=9185 m:november=0 m:march=10024 m:april=9166 m:february=8268 m:june=9515 m:january=7946 m:ytd=78485 m:august=9742 m:july=10298 m:october=0 m:september=4341

series e:zh3n-jtnt d:2012-01-01T00:00:00.000Z t:zip=60827 t:location=Altgeld t:city=CHICAGO m:december=4997 m:may=4172 m:november=6318 m:march=4520 m:april=4665 m:february=4108 m:june=4746 m:january=4196 m:ytd=62058 m:august=6170 m:july=5037 m:october=6944 m:september=6185

series e:zh3n-jtnt d:2012-01-01T00:00:00.000Z t:zip=60632 t:location="Archer Heights*" t:city=CHICAGO m:december=8864 m:may=9556 m:november=10596 m:march=9107 m:april=8938 m:february=8466 m:june=9046 m:january=8817 m:ytd=120173 m:august=12661 m:july=11715 m:october=11896 m:september=10511
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

entity e:zh3n-jtnt l:"Libraries - 2012 Visitors by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/zh3n-jtnt

property e:zh3n-jtnt t:meta.view v:id=zh3n-jtnt v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2012 Visitors by Location" v:attribution="Chicago Public Library"

property e:zh3n-jtnt t:meta.view.owner v:id=jitu-w2pw v:screenName=GPeck v:displayName=GPeck

property e:zh3n-jtnt t:meta.view.tableauthor v:id=jitu-w2pw v:screenName=GPeck v:roleName=editor v:displayName=GPeck
```

## Top Records

```ls
| location        | address                     | city    | zip   | january | february | march | april | may   | june  | july  | august | september | october | november | december | ytd    | 
| =============== | =========================== | ======= | ===== | ======= | ======== | ===== | ===== | ===== | ===== | ===== | ====== | ========= | ======= | ======== | ======== | ====== | 
| Albany Park     | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 7946    | 8268     | 10024 | 9166  | 9185  | 9515  | 10298 | 9742   | 4341      | 0       | 0        | 0        | 78485  | 
| Altgeld         | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 4196    | 4108     | 4520  | 4665  | 4172  | 4746  | 5037  | 6170   | 6185      | 6944    | 6318     | 4997     | 62058  | 
| Archer Heights* | 5055 S. Archer Avenue       | CHICAGO | 60632 | 8817    | 8466     | 9107  | 8938  | 9556  | 9046  | 11715 | 12661  | 10511     | 11896   | 10596    | 8864     | 120173 | 
| Austin          | 5615 W. Race Avenue         | CHICAGO | 60644 | 7210    | 7797     | 8602  | 8383  | 7891  | 7739  | 9702  | 10971  | 9649      | 9644    | 8004     | 7500     | 103092 | 
| Austin-Irving   | 6100 W. Irving Park Road    | CHICAGO | 60634 | 10076   | 10788    | 11895 | 11660 | 10365 | 11179 | 11558 | 11985  | 11568     | 12326   | 10505    | 10059    | 133964 | 
| Avalon*         | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 9723    | 9702     | 9848  | 10589 | 9262  | 10580 | 11480 | 12495  | 12194     | 13361   | 10653    | 9431     | 129318 | 
| Beverly*        | 1962 W. 95th Street         | CHICAGO | 60643 | 7605    | 8228     | 9315  | 8560  | 7946  | 9676  | 9975  | 9975   | 9212      | 10175   | 8427     | 7177     | 106271 | 
| Bezazian        | 1226 W. Ainslie Street      | CHICAGO | 60640 | 13400   | 13368    | 16213 | 14499 | 15607 | 15653 | 17866 | 17875  | 15162     | 17015   | 15409    | 13011    | 185078 | 
| Blackstone      | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 11691   | 12135    | 13566 | 11936 | 11521 | 13942 | 14495 | 14465  | 14315     | 15362   | 12447    | 14006    | 159881 | 
| Brainerd*       | 1350 W. 89th Street         | CHICAGO | 60620 | 3946    | 4393     | 4382  | 4303  | 4423  | 4775  | 4839  | 6075   | 5132      | 6919    | 5412     | 4766     | 59365  | 
```