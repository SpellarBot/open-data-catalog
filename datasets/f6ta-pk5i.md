# Law Enforement Personnel 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/law-enforement-personnel-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/f6ta-pk5i) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/f6ta-pk5i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/f6ta-pk5i/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | f6ta-pk5i |
| Name | Law Enforement Personnel 2015 |
| Attribution | Department of Emergency Service and Public Protection |
| Category | Public Safety |
| Tags | law enforcement, presonnel, police, ucr |
| Created | 2016-12-30T15:11:14Z |
| Publication Date | 2016-12-30T15:13:50Z |

## Description

The Uniform Crime Reporting (UCR) Program defines law enforcement officers as individuals who ordinarily carry a firearm and a badge, have full arrest powers, and are paid from governmental funds set aside specifically for sworn law enforcement representatives.


Data collection

?Each year, law enforcement agencies across the United States report to the UCR Program the total number of sworn law enforcement officers and civilians in their agencies as of October 31.
?Civilian employees include personnel such as clerks, radio dispatchers, meter attendants, stenographers, jailers, correctional officers, and mechanics provided that they are full-time employees of the agency.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | department                  | Department                   | text      | text        |
| Yes      | series tag     | county                      | County                       | text      | text        |
| Yes      | numeric metric | population                  | Population                   | number    | number      |
| Yes      | numeric metric | employee_rate_per_1_000_pop | Employee Rate Per 1,000 Pop. | number    | number      |
| Yes      | numeric metric | total_employees             | Total Employees              | number    | number      |
| Yes      | numeric metric | sworn_male                  | Sworn Male                   | number    | number      |
| Yes      | numeric metric | sworn_female                | Sworn Female                 | number    | number      |
| Yes      | numeric metric | civilian_male               | Civilian Male                | number    | number      |
| Yes      | numeric metric | cvivilian_female            | Cvivilian Female             | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:f6ta-pk5i d:2015-01-01T00:00:00.000Z t:department="STATE POLICE" m:civilian_male=225 m:sworn_male=1038 m:cvivilian_female=299 m:total_employees=1658 m:employee_rate_per_1_000_pop=3.15 m:sworn_female=96 m:population=526902

series e:f6ta-pk5i d:2015-01-01T00:00:00.000Z t:county="New Haven" t:department=ANSONIA m:civilian_male=2 m:sworn_male=43 m:cvivilian_female=5 m:total_employees=53 m:employee_rate_per_1_000_pop=2.81 m:sworn_female=3 m:population=18887

series e:f6ta-pk5i d:2015-01-01T00:00:00.000Z t:county=Hartford t:department=AVON m:civilian_male=1 m:sworn_male=26 m:cvivilian_female=8 m:total_employees=41 m:employee_rate_per_1_000_pop=2.22 m:sworn_female=6 m:population=18485
```

## Meta Commands

```ls
metric m:population p:integer l:Population t:dataTypeName=number

metric m:employee_rate_per_1_000_pop p:float l:"Employee Rate Per 1,000 Pop." t:dataTypeName=number

metric m:total_employees p:integer l:"Total Employees" t:dataTypeName=number

metric m:sworn_male p:integer l:"Sworn Male" t:dataTypeName=number

metric m:sworn_female p:integer l:"Sworn Female" t:dataTypeName=number

metric m:civilian_male p:integer l:"Civilian Male" t:dataTypeName=number

metric m:cvivilian_female p:integer l:"Cvivilian Female" t:dataTypeName=number

entity e:f6ta-pk5i l:"Law Enforement Personnel 2015" t:attribution="Department of Emergency Service and Public Protection" t:url=https://data.ct.gov/api/views/f6ta-pk5i

property e:f6ta-pk5i t:meta.view v:id=f6ta-pk5i v:category="Public Safety" v:attributionLink=http://www.ct.gov/despp v:averageRating=0 v:name="Law Enforement Personnel 2015" v:attribution="Department of Emergency Service and Public Protection"

property e:f6ta-pk5i t:meta.view.license v:name="Public Domain"

property e:f6ta-pk5i t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:f6ta-pk5i t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| department   | county    | population | employee_rate_per_1_000_pop | total_employees | sworn_male | sworn_female | civilian_male | cvivilian_female | 
| ============ | ========= | ========== | =========================== | =============== | ========== | ============ | ============= | ================ | 
| STATE POLICE |           | 526902     | 3.15                        | 1658            | 1038       | 96           | 225           | 299              | 
| ANSONIA      | New Haven | 18887      | 2.81                        | 53              | 43         | 3            | 2             | 5                | 
| AVON         | Hartford  | 18485      | 2.22                        | 41              | 26         | 6            | 1             | 8                | 
| BERLIN       | Hartford  | 20793      | 2.60                        | 54              | 37         | 4            | 6             | 7                | 
| BETHEL       | Fairfield | 19560      | 2.40                        | 47              | 32         | 3            | 6             | 6                | 
| BLOOMFIELD   | Hartford  | 20901      | 2.82                        | 59              | 39         | 8            | 3             | 9                | 
| BRANFORD     | New Haven | 28274      | 2.19                        | 62              | 44         | 4            | 8             | 6                | 
| BRIDGEPORT   | Fairfield | 148313     | 2.75                        | 408             | 316        | 40           | 23            | 29               | 
| BRISTOL      | Hartford  | 60593      | 2.39                        | 145             | 115        | 4            | 15            | 11               | 
| BROOKFIELD   | Fairfield | 17202      | 2.50                        | 43              | 32         | 1            | 6             | 4                | 
```