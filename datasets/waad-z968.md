# Street Sweeping Schedule - 2015 - April-May

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-sweeping-schedule-2015-april-may) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/waad-z968) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/waad-z968/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/waad-z968/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | waad-z968 |
| Name | Street Sweeping Schedule - 2015 - April-May |
| Attribution | City of Chicago |
| Category | Sanitation |
| Tags | street cleaning, schedule, 2015, parking restrictions |
| Created | 2015-03-25T15:24:56Z |
| Publication Date | 2015-05-14T15:38:09Z |

## Description

Street sweeping schedule by Ward and Ward section number. To find your Ward section, visit https://data.cityofchicago.org/id/4qtf-5nmn. For more information about the City's Street Sweeping program, go to http://bit.ly/H2PHUP. Because the City of Chicago ward map will change on May 18, 2015, this dataset will be updated or supplemented with an additional dataset to cover the remainder of 2015 (through November).

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
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:waad-z968 d:2015-01-01T00:00:00.000Z t:ward=01 t:ward_section_concatenated=0101 t:dates=1,7 t:month_name=APRIL t:month_number=4 t:section=01 m:row_number.waad-z968=1

series e:waad-z968 d:2015-01-01T00:00:00.000Z t:ward=01 t:ward_section_concatenated=0101 t:dates=5,6 t:month_name=MAY t:month_number=5 t:section=01 m:row_number.waad-z968=2

series e:waad-z968 d:2015-01-01T00:00:00.000Z t:ward=01 t:ward_section_concatenated=0102 t:dates=2,3 t:month_name=APRIL t:month_number=4 t:section=02 m:row_number.waad-z968=3
```

## Meta Commands

```ls
metric m:row_number.waad-z968 p:long l:"Row Number"

entity e:waad-z968 l:"Street Sweeping Schedule - 2015 - April-May" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/waad-z968

property e:waad-z968 t:meta.view v:id=waad-z968 v:category=Sanitation v:attributionLink=http://www.cityofchicago.org/city/en/depts/streets/provdrs/streets_san/svcs/street_sweeping.html v:averageRating=0 v:name="Street Sweeping Schedule - 2015 - April-May" v:attribution="City of Chicago"

property e:waad-z968 t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:waad-z968 t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| ward_section_concatenated | ward | section | month_name | month_number | dates | 
| ========================= | ==== | ======= | ========== | ============ | ===== | 
| 0101                      | 01   | 01      | APRIL      | 4            | 1,7   | 
| 0101                      | 01   | 01      | MAY        | 5            | 5,6   | 
| 0102                      | 01   | 02      | APRIL      | 4            | 2,3   | 
| 0102                      | 01   | 02      | MAY        | 5            | 1,7   | 
| 0103                      | 01   | 03      | APRIL      | 4            | 8,14  | 
| 0103                      | 01   | 03      | MAY        | 5            | 12,13 | 
| 0104                      | 01   | 04      | APRIL      | 4            | 9,10  | 
| 0104                      | 01   | 04      | MAY        | 5            | 8,14  | 
| 0105                      | 01   | 05      | APRIL      | 4            | 15,21 | 
| 0106                      | 01   | 06      | APRIL      | 4            | 16,17 | 
```