# FDNY Important Phone Numbers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fdny-important-phone-numbers-1004b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kjmq-hfaa) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kjmq-hfaa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kjmq-hfaa/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kjmq-hfaa |
| Name | FDNY Important Phone Numbers |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fdny, fire department, safety, fire safety, fdny phone numbers |
| Created | 2013-01-31T20:42:17Z |
| Publication Date | 2013-02-04T19:33:53Z |

## Description

FDNY Important Phone Numbers

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | department   | Department   | text      | text        |
| Yes      | series tag  | phone_number | Phone Number | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kjmq-hfaa d:2013-01-31T12:42:19.000Z t:phone_number=911 t:department="In an emergency" m:row_number.kjmq-hfaa=1

series e:kjmq-hfaa d:2013-01-31T12:42:19.000Z t:phone_number=311 t:department="For general Citywide Information" m:row_number.kjmq-hfaa=2

series e:kjmq-hfaa d:2013-01-31T12:42:19.000Z t:phone_number=718-999-2000 t:department="Fire Department General Number" m:row_number.kjmq-hfaa=3
```

## Meta Commands

```ls
metric m:row_number.kjmq-hfaa p:long l:"Row Number"

entity e:kjmq-hfaa l:"FDNY Important Phone Numbers" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/kjmq-hfaa

property e:kjmq-hfaa t:meta.view v:id=kjmq-hfaa v:category="Public Safety" v:attributionLink=http://www.nyc.gov/html/fdny/html/general/phonenum.shtml v:averageRating=0 v:name="FDNY Important Phone Numbers" v:attribution="Fire Department of New York City (FDNY)"

property e:kjmq-hfaa t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kjmq-hfaa t:meta.view.tableauthor v:id=syvn-4vgv v:screenName="Sudhir Vasudeva" v:displayName="Sudhir Vasudeva"
```

## Top Records

```ls
| :updated_at | department                         | phone_number      | 
| =========== | ================================== | ================= | 
| 1359636139  | In an emergency                    | 911               | 
| 1359636139  | For general Citywide Information   | 311               | 
| 1359636139  | Fire Department General Number     | 718-999-2000      | 
| 1359636139  | Fire Department Recruitment        | 718-999-FDNY      | 
| 1359636139  | Community Affairs                  | 718-999-1438      | 
| 1359636139  | EMS Command                        | 718-999-2770/1753 | 
| 1359636139  | Human Resources Information Center | 718-999-2164      | 
| 1359636139  | Summer Intern Program              | 718-999-2181      | 
| 1359636139  | Fire Cadet General Info            | 718-999-1468      | 
| 1359636139  | Office of the Counsel              | 718-999-2040      | 
```