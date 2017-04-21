# Libraries - 2014 Circulation by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2014-circulation-by-location-4cd70) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/hr6z-8bf2) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/hr6z-8bf2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/hr6z-8bf2/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | hr6z-8bf2 |
| Name | Libraries - 2014 Circulation by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | performance metrics, libraries, circulation |
| Created | 2014-03-28T20:56:28Z |
| Publication Date | 2015-01-12T19:27:09Z |

## Description

Circulation figures include new checkouts as well as renewals. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 75 neighborhood branches. Albany Park Branch closed 9/22/2012 for construction of a new branch expected to open in Fall 2014. Interim services had been provided in the Albany Park community. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.

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
series e:hr6z-8bf2 d:2014-01-01T00:00:00.000Z t:zip=60625 t:location="Albany Park" t:city=CHICAGO m:december=11058 m:may=3 m:november=12544 m:march=7 m:april=40 m:february=0 m:june=0 m:january=35 m:ytd=50484 m:august=139 m:july=0 m:october=15251 m:september=11407

series e:hr6z-8bf2 d:2014-01-01T00:00:00.000Z t:zip=60827 t:location=Altgeld t:city=CHICAGO m:december=822 m:may=587 m:november=831 m:march=522 m:april=611 m:february=604 m:june=729 m:january=791 m:ytd=8509 m:august=742 m:july=743 m:october=751 m:september=776

series e:hr6z-8bf2 d:2014-01-01T00:00:00.000Z t:zip=60632 t:location="Archer Heights" t:city=CHICAGO m:december=6515 m:may=6509 m:november=6705 m:march=7986 m:april=8059 m:february=6682 m:june=6417 m:january=6695 m:ytd=85217 m:august=6664 m:july=7360 m:october=8327 m:september=7298
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

entity e:hr6z-8bf2 l:"Libraries - 2014 Circulation by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/hr6z-8bf2

property e:hr6z-8bf2 t:meta.view v:id=hr6z-8bf2 v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2014 Circulation by Location" v:attribution="Chicago Public Library"

property e:hr6z-8bf2 t:meta.view.owner v:id=cmhs-sm84 v:screenName="Ebony Jones" v:displayName="Ebony Jones"

property e:hr6z-8bf2 t:meta.view.tableauthor v:id=cmhs-sm84 v:screenName="Ebony Jones" v:roleName=editor v:displayName="Ebony Jones"
```

## Top Records

```ls
| location          | address                     | city    | zip   | january | february | march | april | may   | june  | july  | august | september | october | november | december | ytd    | 
| ================= | =========================== | ======= | ===== | ======= | ======== | ===== | ===== | ===== | ===== | ===== | ====== | ========= | ======= | ======== | ======== | ====== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 35      | 0        | 7     | 40    | 3     | 0     | 0     | 139    | 11407     | 15251   | 12544    | 11058    | 50484  | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 791     | 604      | 522   | 611   | 587   | 729   | 743   | 742    | 776       | 751     | 831      | 822      | 8509   | 
| Archer Heights    | 5055 S. Archer Avenue       | CHICAGO | 60632 | 6695    | 6682     | 7986  | 8059  | 6509  | 6417  | 7360  | 6664   | 7298      | 8327    | 6705     | 6515     | 85217  | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644 | 1472    | 1500     | 1601  | 2014  | 1794  | 2167  | 2280  | 2203   | 1918      | 2203    | 1965     | 2277     | 23394  | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634 | 10144   | 9554     | 11474 | 11294 | 10182 | 11213 | 12229 | 11093  | 10969     | 11502   | 9968     | 9034     | 128656 | 
| Avalon            | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 4377    | 3792     | 4388  | 4573  | 4817  | 5314  | 5397  | 4833   | 5149      | 5157    | 4774     | 4248     | 56819  | 
| Back of the Yards | 2111 W. 47th Street         | CHICAGO | 60609 | 3935    | 3675     | 4319  | 4544  | 4047  | 4813  | 6459  | 4775   | 4430      | 4735    | 4294     | 3751     | 53777  | 
| Beverly           | 1962 W. 95th Street         | CHICAGO | 60643 | 5558    | 5070     | 6277  | 6222  | 5228  | 6032  | 6808  | 5660   | 5284      | 5799    | 4969     | 4853     | 67760  | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640 | 9960    | 8737     | 10628 | 11312 | 11373 | 12069 | 12874 | 11918  | 11036     | 12133   | 10652    | 10502    | 133194 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 7975    | 7738     | 10162 | 10083 | 9475  | 10510 | 11359 | 10331  | 9538      | 9305    | 8549     | 7971     | 112996 | 
```