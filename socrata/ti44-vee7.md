# Libraries - 2013 Circulation by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2013-circulation-by-location-7dd09) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ti44-vee7) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ti44-vee7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ti44-vee7/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ti44-vee7 |
| Name | Libraries - 2013 Circulation by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | performance metrics, libraries, circulation |
| Created | 2013-04-11T18:06:06Z |
| Publication Date | 2014-01-15T22:19:13Z |

## Description

Circulation figures include new checkouts as well as renewals. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Edgewater Branch reopened in a new, 2-story facility on 6/22/2013. Humboldt Park Branch closed 3/26/2012 for construction of a 5,000-square-foot addition; it reopened 2/9/2013. Albany Park Branch closed 9/22/2012 for construction of a new branch expected to open in 2014. Interim services are being provided in the Albany Park community. Gage Park Branch closed 2/22/2013-3/1/2013 for full carpet replacement and South Shore Branch was closed from 5/13/2013-6/29/2013 for repairs and renovation. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.

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
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:ti44-vee7 d:2013-01-01T00:00:00.000Z t:zip=60625 t:location="Albany Park" t:city=CHICAGO m:december=94 m:may=0 m:november=159 m:march=0 m:april=0 m:february=0 m:june=0 m:january=0 m:ytd=572 m:august=74 m:july=0 m:october=126 m:september=119

series e:ti44-vee7 d:2013-01-01T00:00:00.000Z t:zip=60827 t:location=Altgeld t:city=CHICAGO m:december=891 m:may=675 m:november=797 m:march=754 m:april=620 m:february=722 m:june=614 m:january=871 m:ytd=9518 m:august=816 m:july=873 m:october=993 m:september=892

series e:ti44-vee7 d:2013-01-01T00:00:00.000Z t:zip=60632 t:location="Archer Heights" t:city=CHICAGO m:december=6899 m:may=7270 m:november=8300 m:march=8630 m:april=7910 m:february=7676 m:june=6774 m:january=8747 m:ytd=93854 m:august=7154 m:july=8164 m:october=8791 m:september=7539
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

entity e:ti44-vee7 l:"Libraries - 2013 Circulation by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/ti44-vee7

property e:ti44-vee7 t:meta.view v:id=ti44-vee7 v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2013 Circulation by Location" v:attribution="Chicago Public Library"

property e:ti44-vee7 t:meta.view.owner v:id=cmhs-sm84 v:screenName="Ebony Jones" v:displayName="Ebony Jones"

property e:ti44-vee7 t:meta.view.tableauthor v:id=cmhs-sm84 v:screenName="Ebony Jones" v:roleName=editor v:displayName="Ebony Jones"
```

## Top Records

```ls
| location          | address                     | city    | zip   | january | february | march | april | may   | june  | july  | august | september | october | november | december | ytd    | 
| ================= | =========================== | ======= | ===== | ======= | ======== | ===== | ===== | ===== | ===== | ===== | ====== | ========= | ======= | ======== | ======== | ====== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 0       | 0        | 0     | 0     | 0     | 0     | 0     | 74     | 119       | 126     | 159      | 94       | 572    | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 871     | 722      | 754   | 620   | 675   | 614   | 873   | 816    | 892       | 993     | 797      | 891      | 9518   | 
| Archer Heights    | 5055 S. Archer Avenue       | CHICAGO | 60632 | 8747    | 7676     | 8630  | 7910  | 7270  | 6774  | 8164  | 7154   | 7539      | 8791    | 8300     | 6899     | 93854  | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644 | 2038    | 1744     | 1865  | 2100  | 1718  | 1926  | 2300  | 1734   | 1990      | 2205    | 1777     | 1550     | 22947  | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634 | 12945   | 11684    | 13635 | 12639 | 11645 | 11793 | 14335 | 12022  | 11679     | 12298   | 12604    | 9664     | 146943 | 
| Avalon            | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 4962    | 4488     | 4856  | 4912  | 5129  | 5360  | 5718  | 5066   | 4672      | 5105    | 4827     | 3620     | 58715  | 
| Back of the Yards | 2111 W. 47th Street         | CHICAGO | 60609 | 0       | 0        | 0     | 0     | 0     | 0     | 0     | 588    | 5207      | 5660    | 5077     | 4169     | 20701  | 
| Beverly           | 1962 W. 95th Street         | CHICAGO | 60643 | 6771    | 6004     | 7191  | 6921  | 6127  | 7436  | 8502  | 7246   | 6306      | 6951    | 6531     | 5056     | 81042  | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640 | 13614   | 11636    | 14450 | 14738 | 14729 | 14875 | 14676 | 13230  | 11514     | 12018   | 11493    | 9871     | 156844 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 10873   | 9516     | 11640 | 11046 | 11059 | 11303 | 12408 | 11680  | 10291     | 10851   | 10723    | 8352     | 129742 | 
```