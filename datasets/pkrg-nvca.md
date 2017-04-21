# Number of Law Enforcement Personnel by Department 2010-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-law-enforcement-personnel-by-department-2010-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/pkrg-nvca) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/pkrg-nvca/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/pkrg-nvca/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | pkrg-nvca |
| Name | Number of Law Enforcement Personnel by Department 2010-2012 |
| Attribution | Department of Emergency Services and Public Protection |
| Category | Public Safety |
| Tags | police, personnel, public safety |
| Created | 2015-01-13T20:42:17Z |
| Publication Date | 2015-01-13T20:45:31Z |

## Description

The number of sworn and civilian law enforcement personnel employed by police deprtments in Connecticut for years 2010 through 2012.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | time           | year                        | Year                         | number    | number      |
| Yes      | series tag     | department                  | Department                   | text      | text        |
| Yes      | series tag     | county                      | County                       | text      | text        |
| Yes      | numeric metric | pop_of_jurisdaiction        | Pop of Jurisdaiction         | number    | number      |
| Yes      | numeric metric | employee_rate_per_1_000_pop | Employee Rate Per 1,000 Pop. | number    | number      |
| Yes      | numeric metric | total_personnel             | Total Personnel              | number    | number      |
| Yes      | numeric metric | sworn_male                  | Sworn Male                   | number    | number      |
| Yes      | numeric metric | sworn_female                | Sworn Female                 | number    | number      |
| Yes      | numeric metric | civilian_male               | Civilian Male                | number    | number      |
| Yes      | numeric metric | civilian_female             | Civilian Female              | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pkrg-nvca d:2012-01-01T00:00:00.000Z t:department="STATE POLICE" m:civilian_male=223 m:sworn_male=1004 m:total_personnel=1591 m:civilian_female=280 m:employee_rate_per_1_000_pop=2.94 m:sworn_female=84 m:pop_of_jurisdaiction=541161

series e:pkrg-nvca d:2012-01-01T00:00:00.000Z t:county=NH t:department=ANSONIA m:civilian_male=2 m:sworn_male=43 m:total_personnel=54 m:civilian_female=6 m:employee_rate_per_1_000_pop=2.8 m:sworn_female=3 m:pop_of_jurisdaiction=19271

series e:pkrg-nvca d:2012-01-01T00:00:00.000Z t:county=Hart t:department=AVON m:civilian_male=1 m:sworn_male=22 m:total_personnel=39 m:civilian_female=6 m:employee_rate_per_1_000_pop=2.15 m:sworn_female=10 m:pop_of_jurisdaiction=18162
```

## Meta Commands

```ls
metric m:pop_of_jurisdaiction p:integer l:"Pop of Jurisdaiction" t:dataTypeName=number

metric m:employee_rate_per_1_000_pop p:float l:"Employee Rate Per 1,000 Pop." t:dataTypeName=number

metric m:total_personnel p:integer l:"Total Personnel" t:dataTypeName=number

metric m:sworn_male p:integer l:"Sworn Male" t:dataTypeName=number

metric m:sworn_female p:integer l:"Sworn Female" t:dataTypeName=number

metric m:civilian_male p:integer l:"Civilian Male" t:dataTypeName=number

metric m:civilian_female p:integer l:"Civilian Female" t:dataTypeName=number

entity e:pkrg-nvca l:"Number of Law Enforcement Personnel by Department 2010-2012" t:attribution="Department of Emergency Services and Public Protection" t:url=https://data.ct.gov/api/views/pkrg-nvca

property e:pkrg-nvca t:meta.view v:id=pkrg-nvca v:category="Public Safety" v:attributionLink=http://www.ct.gov/despp v:averageRating=0 v:name="Number of Law Enforcement Personnel by Department 2010-2012" v:attribution="Department of Emergency Services and Public Protection"

property e:pkrg-nvca t:meta.view.license v:name="Public Domain"

property e:pkrg-nvca t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:pkrg-nvca t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| year | department   | county | pop_of_jurisdaiction | employee_rate_per_1_000_pop | total_personnel | sworn_male | sworn_female | civilian_male | civilian_female | 
| ==== | ============ | ====== | ==================== | =========================== | =============== | ========== | ============ | ============= | =============== | 
| 2012 | STATE POLICE |        | 541161               | 2.94                        | 1591            | 1004       | 84           | 223           | 280             | 
| 2012 | ANSONIA      | NH     | 19271                | 2.80                        | 54              | 43         | 3            | 2             | 6               | 
| 2012 | AVON         | Hart   | 18162                | 2.15                        | 39              | 22         | 10           | 1             | 6               | 
| 2012 | BERLIN       | Hart   | 19935                | 2.81                        | 56              | 37         | 4            | 6             | 9               | 
| 2012 | BETHEL       | Fair   | 18822                | 2.50                        | 47              | 32         | 3            | 5             | 7               | 
| 2012 | BLOOMFIELD   | Hart   | 20557                | 2.53                        | 52              | 36         | 5            | 6             | 5               | 
| 2012 | BRANFORD     | NH     | 28055                | 2.14                        | 60              | 44         | 3            | 8             | 5               | 
| 2012 | BRIDGEPORT   | Fair   | 146030               | 3.11                        | 454             | 368        | 46           | 18            | 22              | 
| 2012 | BRISTOL      | Hart   | 60688                | 0.95                        | 138             | 108        | 6            | 12            | 12              | 
| 2012 | BROOKFIELD   | Fair   | 16662                | 2.46                        | 41              | 30         | 1            | 6             | 4               | 
```