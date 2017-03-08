# Budget - FTE

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/4zfx-f2ts/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/budget-fte-ab7fd)
* [Metadata URL](https://data.sfgov.org/api/views/4zfx-f2ts)
* Id = 4zfx-f2ts
* Name = Budget - FTE
* Attribution = SF Controller's Office
* [Attribution Link](http://openbook.sfgov.org)
* Category = City Management and Ethics
* Tags = [budget, fte, staffing, sfopenbook, open book, openbook]
* Created = 2014-06-16T21:46:43Z
* Publication Date = 2016-05-05T20:06:55Z
* Rows Updated = 2016-08-08T21:09:58Z

## Description

The San Francisco Controller's Office maintains a database of budgetary staffing data that appears in summarized form in each Annual Salary Ordinance (ASO). This data is presented on the Budget report hosted at http://openbook.sfgov.org, and is also available in this dataset in CSV format. New data is added on an annual basis when the ASO is published for each new fiscal year. Data is available from fiscal year 2010 forward.

## Columns

```ls
| Name                    | Field Name              | Data Type | Render Type | Schema Type    | Included | 
| ======================= | ======================= | ========= | =========== | ============== | ======== | 
| Fiscal Year             | fiscal_year             | number    | number      | time           | Yes      | 
| Related Gov't Units     | related_gov_t_units     | text      | text        | series tag     | Yes      | 
| Organization Group Code | organization_group_code | text      | text        | series tag     | Yes      | 
| Organization Group      | organization_group      | text      | text        | series tag     | Yes      | 
| Department Code         | department_code         | text      | text        | series tag     | Yes      | 
| Department              | department              | text      | text        | series tag     | Yes      | 
| Program Code            | program_code            | text      | text        | series tag     | Yes      | 
| Program                 | program                 | text      | text        | series tag     | Yes      | 
| Character Code          | character_code          | text      | text        | series tag     | Yes      | 
| Character               | character               | text      | text        | series tag     | Yes      | 
| Object Code             | object_code             | text      | text        | series tag     | Yes      | 
| Object                  | object                  | text      | text        | series tag     | Yes      | 
| Sub-object Code         | sub_object_code         | text      | text        | series tag     | Yes      | 
| Sub-object              | sub_object              | text      | text        | series tag     | Yes      | 
| Fund Type Code          | fund_type_code          | text      | text        | series tag     | Yes      | 
| Fund Type               | fund_type               | text      | text        | series tag     | Yes      | 
| Fund Code               | fund_code               | text      | text        | series tag     | Yes      | 
| Fund                    | fund                    | text      | text        | series tag     | Yes      | 
| Fund Category Code      | fund_category_code      | text      | text        | series tag     | Yes      | 
| Fund Category           | fund_category           | text      | text        | series tag     | Yes      | 
| Job Family Code         | job_family_code         | text      | text        | series tag     | Yes      | 
| Job Family              | job_family              | text      | text        | series tag     | Yes      | 
| Job Code                | job_code                | text      | text        | series tag     | Yes      | 
| Job                     | job                     | text      | text        | series tag     | Yes      | 
| FTE                     | fte                     | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:4zfx-f2ts d:2015-01-01T00:00:00.000Z t:organization_group="Public Protection" t:fund_code=1GAGF t:fund_type="General Fund" t:program_code=ACB t:department=Police t:job_family=Management t:job_family_code=0900 t:sub_object=Misc-Regular t:job="Manager I" t:object="Permanent Salaries-Misc" t:object_code=001 t:fund_type_code=1G t:character=Salaries t:job_code=0922 t:character_code=001 t:fund_category_code=1 t:program=Investigations t:sub_object_code=00101 t:fund_category=Operating t:department_code=POL t:fund="General Fund" t:organization_group_code=01 t:related_gov_t_units=No m:fte=1

series e:4zfx-f2ts d:2017-01-01T00:00:00.000Z t:organization_group="Culture & Recreation" t:fund_code=1GAGF t:fund_type="General Fund" t:program_code=ECU t:department="Recreation and Park Commission" t:job_family=Management t:job_family_code=0900 t:sub_object=Misc-Regular t:job="Manager I" t:object="Permanent Salaries-Misc" t:object_code=001 t:fund_type_code=1G t:character=Salaries t:job_code=0922 t:character_code=001 t:fund_category_code=1 t:program=Recreation t:sub_object_code=00101 t:fund_category=Operating t:department_code=REC t:fund="General Fund" t:organization_group_code=05 t:related_gov_t_units=No m:fte=1

series e:4zfx-f2ts d:2012-01-01T00:00:00.000Z t:organization_group="Public Works, Transportation & Commerce" t:fund_code=5TAAA t:fund_type="PUC Hetch Hetchy Funds" t:program_code=BDA t:department="PUC Hetch Hetchy" t:job_family="Budget, Admn & Stats Analysis" t:job_family_code=1800 t:sub_object=Misc-Regular t:job="Senior Administrative Analyst" t:object="Permanent Salaries-Misc" t:object_code=001 t:fund_type_code=5T t:character=Salaries t:job_code=1823 t:character_code=001 t:fund_category_code=1 t:program=Administration t:sub_object_code=00101 t:fund_category=Operating t:department_code=HHP t:fund="Hetch Hetchy Operating Fund" t:organization_group_code=02 t:related_gov_t_units=No m:fte=1
```

## Meta Commands

```ls
metric m:fte l:FTE d:"Staffing level is represented by ""Full Time Equivalent (FTE)"". One FTE equals one or more employees who together work 40 hours per week. For instance, an employee who works 40 hours per week is counted as one FTE, and two part-time employees who each work 20 hours per week are also counted as one FTE. Overtime hours are excluded from this calculation. FTE is relative to the time period. Annual FTEs are based on 2080, 2088 or 2096 hours per year depending on how week days and leap day affect a particular year." t:dataTypeName=number

entity e:4zfx-f2ts l:"Budget - FTE" t:attribution="SF Controller's Office" t:url=https://data.sfgov.org/api/views/4zfx-f2ts

property e:4zfx-f2ts t:meta.view d:2017-03-08T00:17:34.411Z v:id=4zfx-f2ts v:category="City Management and Ethics" v:attributionLink=http://openbook.sfgov.org v:averageRating=0 v:name="Budget - FTE" v:attribution="SF Controller's Office"

property e:4zfx-f2ts t:meta.view.license d:2017-03-08T00:17:34.411Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:4zfx-f2ts t:meta.view.owner d:2017-03-08T00:17:34.411Z v:id=9ufn-6bwh v:screenName="Jeff Pera" v:roleName=editor v:displayName="Jeff Pera"

property e:4zfx-f2ts t:meta.view.tableauthor d:2017-03-08T00:17:34.411Z v:id=9ufn-6bwh v:screenName="Jeff Pera" v:roleName=editor v:displayName="Jeff Pera"
```