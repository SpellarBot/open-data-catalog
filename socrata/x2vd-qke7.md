# Street Sweeping Schedule - 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-sweeping-schedule-2016) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/x2vd-qke7) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/x2vd-qke7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/x2vd-qke7/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | x2vd-qke7 |
| Name | Street Sweeping Schedule - 2016 |
| Attribution | City of Chicago |
| Category | Sanitation |
| Tags | street cleaning, schedule, 2016, parking restrictions |
| Created | 2016-03-16T20:07:27Z |
| Publication Date | 2016-10-25T14:21:50Z |

## Description

Street sweeping schedule by Ward and Ward section number. To find your Ward section, visit https://data.cityofchicago.org/d/icje-4fmy. For more information about the City's Street Sweeping program, go to http://bit.ly/H2PHUP.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                        | Data Type | Render Type |
| ======== | =========== | ========================= | =========================== | ========= | =========== |
| Yes      | series tag  | ward_section_concatenated | WARD SECTION (CONCATENATED) | text      | text        |
| Yes      | series tag  | ward                      | WARD                        | text      | text        |
| Yes      | series tag  | section                   | SECTION                     | text      | text        |
| Yes      | series tag  | month_name                | MONTH NAME                  | text      | text        |
| Yes      | series tag  | month_number              | MONTH NUMBER                | text      | number      |
| Yes      | series tag  | dates                     | DATES                       | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x2vd-qke7 d:2016-01-01T00:00:00.000Z t:ward=01 t:ward_section_concatenated=0101 t:dates=5,6 t:month_name=APRIL t:month_number=4 t:section=01 m:row_number.x2vd-qke7=1

series e:x2vd-qke7 d:2016-01-01T00:00:00.000Z t:ward=01 t:ward_section_concatenated=0101 t:dates=3,4 t:month_name=MAY t:month_number=5 t:section=01 m:row_number.x2vd-qke7=2

series e:x2vd-qke7 d:2016-01-01T00:00:00.000Z t:ward=01 t:ward_section_concatenated=0101 t:dates=1,7 t:month_name=JUNE t:month_number=6 t:section=01 m:row_number.x2vd-qke7=3
```

## Meta Commands

```ls
metric m:row_number.x2vd-qke7 p:long l:"Row Number"

entity e:x2vd-qke7 l:"Street Sweeping Schedule - 2016" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/x2vd-qke7

property e:x2vd-qke7 t:meta.view v:id=x2vd-qke7 v:category=Sanitation v:attributionLink=http://www.cityofchicago.org/city/en/depts/streets/provdrs/streets_san/svcs/street_sweeping.html v:averageRating=0 v:name="Street Sweeping Schedule - 2016" v:attribution="City of Chicago"

property e:x2vd-qke7 t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:x2vd-qke7 t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| ward_section_concatenated | ward | section | month_name | month_number | dates | 
| ========================= | ==== | ======= | ========== | ============ | ===== | 
| 0101                      | 01   | 01      | APRIL      | 4            | 5,6   | 
| 0101                      | 01   | 01      | MAY        | 5            | 3,4   | 
| 0101                      | 01   | 01      | JUNE       | 6            | 1,7   | 
| 0101                      | 01   | 01      | JULY       | 7            | 5,6   | 
| 0101                      | 01   | 01      | AUGUST     | 8            | 2,3   | 
| 0101                      | 01   | 01      | SEPTEMBER  | 9            | 6,7   | 
| 0101                      | 01   | 01      | OCTOBER    | 10           | 4,5   | 
| 0101                      | 01   | 01      | NOVEMBER   | 11           | 1,2   | 
| 0102                      | 01   | 02      | APRIL      | 4            | 1,7   | 
| 0102                      | 01   | 02      | MAY        | 5            | 5,6   | 
```