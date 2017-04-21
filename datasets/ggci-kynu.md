# Street Sweeping Schedule - 2015 - May-November

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-sweeping-schedule-2015-may-november) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ggci-kynu) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ggci-kynu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ggci-kynu/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ggci-kynu |
| Name | Street Sweeping Schedule - 2015 - May-November |
| Attribution | City of Chicago |
| Category | Sanitation |
| Tags | street cleaning, schedule, 2015, parking restrictions |
| Created | 2015-05-07T16:59:09Z |
| Publication Date | 2015-06-18T17:15:09Z |

## Description

Street sweeping schedule by Ward and Ward section number. To find your Ward section, visit https://data.cityofchicago.org/d/2cgx-fb86. For more information about the City's Street Sweeping program, go to http://bit.ly/H2PHUP. Because the City of Chicago ward map will change on May 18, 2015, this dataset begins on that date. The dataset for April and the first half of May is https://data.cityofchicago.org/d/waad-z968.

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
series e:ggci-kynu d:2015-01-01T00:00:00.000Z t:ward=01 t:ward_section_concatenated=0101 t:dates=2,3 t:month_name=JUNE t:month_number=6 t:section=01 m:row_number.ggci-kynu=1

series e:ggci-kynu d:2015-01-01T00:00:00.000Z t:ward=01 t:ward_section_concatenated=0101 t:dates=1,7 t:month_name=JULY t:month_number=7 t:section=01 m:row_number.ggci-kynu=2

series e:ggci-kynu d:2015-01-01T00:00:00.000Z t:ward=01 t:ward_section_concatenated=0101 t:dates=4,5 t:month_name=AUGUST t:month_number=8 t:section=01 m:row_number.ggci-kynu=3
```

## Meta Commands

```ls
metric m:row_number.ggci-kynu p:long l:"Row Number"

entity e:ggci-kynu l:"Street Sweeping Schedule - 2015 - May-November" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ggci-kynu

property e:ggci-kynu t:meta.view v:id=ggci-kynu v:category=Sanitation v:attributionLink=http://www.cityofchicago.org/city/en/depts/streets/provdrs/streets_san/svcs/street_sweeping.html v:averageRating=0 v:name="Street Sweeping Schedule - 2015 - May-November" v:attribution="City of Chicago"

property e:ggci-kynu t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:ggci-kynu t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| ward_section_concatenated | ward | section | month_name | month_number | dates | 
| ========================= | ==== | ======= | ========== | ============ | ===== | 
| 0101                      | 01   | 01      | JUNE       | 6            | 2,3   | 
| 0101                      | 01   | 01      | JULY       | 7            | 1,7   | 
| 0101                      | 01   | 01      | AUGUST     | 8            | 4,5   | 
| 0101                      | 01   | 01      | SEPTEMBER  | 9            | 1,2   | 
| 0101                      | 01   | 01      | OCTOBER    | 10           | 6,7   | 
| 0101                      | 01   | 01      | NOVEMBER   | 11           | 3,4   | 
| 0102                      | 01   | 02      | JUNE       | 6            | 4,5   | 
| 0102                      | 01   | 02      | JULY       | 7            | 2,3   | 
| 0102                      | 01   | 02      | AUGUST     | 8            | 6,7   | 
| 0102                      | 01   | 02      | SEPTEMBER  | 9            | 3,4   | 
```