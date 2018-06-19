# Budget - FTE

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-fte-ab7fd) |
| Metadata | [Link](https://data.sfgov.org/api/views/4zfx-f2ts) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/4zfx-f2ts/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/4zfx-f2ts/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 4zfx-f2ts |
| Name | Budget - FTE |
| Attribution | SF Controller's Office |
| Category | City Management and Ethics |
| Tags | budget, fte, staffing, sfopenbook, open book, openbook |
| Created | 2014-06-16T21:46:43Z |
| Publication Date | 2016-05-05T20:06:55Z |

## Description

The San Francisco Controller's Office maintains a database of budgetary staffing data that appears in summarized form in each Annual Salary Ordinance (ASO). This data is presented on the Budget report hosted at http://openbook.sfgov.org, and is also available in this dataset in CSV format. New data is added on an annual basis when the ASO is published for each new fiscal year. Data is available from fiscal year 2010 forward.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year             | Fiscal Year             | number    | number      |
| Yes      | series tag     | related_gov_t_units     | Related Gov't Units     | text      | text        |
| Yes      | series tag     | organization_group_code | Organization Group Code | text      | text        |
| Yes      | series tag     | organization_group      | Organization Group      | text      | text        |
| Yes      | series tag     | department_code         | Department Code         | text      | text        |
| Yes      | series tag     | department              | Department              | text      | text        |
| Yes      | series tag     | program_code            | Program Code            | text      | text        |
| Yes      | series tag     | program                 | Program                 | text      | text        |
| Yes      | series tag     | character_code          | Character Code          | text      | text        |
| Yes      | series tag     | character               | Character               | text      | text        |
| Yes      | series tag     | object_code             | Object Code             | text      | text        |
| Yes      | series tag     | object                  | Object                  | text      | text        |
| Yes      | series tag     | sub_object_code         | Sub-object Code         | text      | text        |
| Yes      | series tag     | sub_object              | Sub-object              | text      | text        |
| Yes      | series tag     | fund_type_code          | Fund Type Code          | text      | text        |
| Yes      | series tag     | fund_type               | Fund Type               | text      | text        |
| Yes      | series tag     | fund_code               | Fund Code               | text      | text        |
| Yes      | series tag     | fund                    | Fund                    | text      | text        |
| Yes      | series tag     | fund_category_code      | Fund Category Code      | text      | text        |
| Yes      | series tag     | fund_category           | Fund Category           | text      | text        |
| Yes      | series tag     | job_family_code         | Job Family Code         | text      | text        |
| Yes      | series tag     | job_family              | Job Family              | text      | text        |
| Yes      | series tag     | job_code                | Job Code                | text      | text        |
| Yes      | series tag     | job                     | Job                     | text      | text        |
| Yes      | numeric metric | fte                     | FTE                     | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4zfx-f2ts d:2015-01-01T00:00:00.000Z t:department_code=POL t:fund_type_code=1G t:character_code=001 t:fund_type="General Fund" t:organization_group="Public Protection" t:job_family_code=0900 t:fund_category_code=1 t:program=Investigations t:fund_code=1GAGF t:related_gov_t_units=No t:character=Salaries t:program_code=ACB t:sub_object_code=00101 t:fund="General Fund" t:sub_object=Misc-Regular t:job_family=Management t:organization_group_code=01 t:object_code=001 t:fund_category=Operating t:job_code=0922 t:department=Police t:job="Manager I" t:object="Permanent Salaries-Misc" m:fte=1

series e:4zfx-f2ts d:2017-01-01T00:00:00.000Z t:department_code=REC t:fund_type_code=1G t:character_code=001 t:fund_type="General Fund" t:organization_group="Culture & Recreation" t:job_family_code=0900 t:fund_category_code=1 t:program=Recreation t:fund_code=1GAGF t:related_gov_t_units=No t:character=Salaries t:program_code=ECU t:sub_object_code=00101 t:fund="General Fund" t:sub_object=Misc-Regular t:job_family=Management t:organization_group_code=05 t:object_code=001 t:fund_category=Operating t:job_code=0922 t:department="Recreation and Park Commission" t:job="Manager I" t:object="Permanent Salaries-Misc" m:fte=1

series e:4zfx-f2ts d:2012-01-01T00:00:00.000Z t:department_code=HHP t:fund_type_code=5T t:character_code=001 t:fund_type="PUC Hetch Hetchy Funds" t:organization_group="Public Works, Transportation & Commerce" t:job_family_code=1800 t:fund_category_code=1 t:program=Administration t:fund_code=5TAAA t:related_gov_t_units=No t:character=Salaries t:program_code=BDA t:sub_object_code=00101 t:fund="Hetch Hetchy Operating Fund" t:sub_object=Misc-Regular t:job_family="Budget, Admn & Stats Analysis" t:organization_group_code=02 t:object_code=001 t:fund_category=Operating t:job_code=1823 t:department="PUC Hetch Hetchy" t:job="Senior Administrative Analyst" t:object="Permanent Salaries-Misc" m:fte=1
```

## Meta Commands

```ls
metric m:fte p:double l:FTE d:"Staffing level is represented by ""Full Time Equivalent (FTE)"". One FTE equals one or more employees who together work 40 hours per week. For instance, an employee who works 40 hours per week is counted as one FTE, and two part-time employees who each work 20 hours per week are also counted as one FTE. Overtime hours are excluded from this calculation. FTE is relative to the time period. Annual FTEs are based on 2080, 2088 or 2096 hours per year depending on how week days and leap day affect a particular year." t:dataTypeName=number

entity e:4zfx-f2ts l:"Budget - FTE" t:attribution="SF Controller's Office" t:url=https://data.sfgov.org/api/views/4zfx-f2ts

property e:4zfx-f2ts t:meta.view d:2017-09-25T07:31:46.477Z v:averageRating=0 v:name="Budget - FTE" v:attribution="SF Controller's Office" v:attributionLink=http://openbook.sfgov.org v:id=4zfx-f2ts v:category="City Management and Ethics"

property e:4zfx-f2ts t:meta.view.license d:2017-09-25T07:31:46.477Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:4zfx-f2ts t:meta.view.owner d:2017-09-25T07:31:46.477Z v:displayName="Alex Levitsky" v:id=9ufn-6bwh v:screenName="Alex Levitsky"

property e:4zfx-f2ts t:meta.view.tableauthor d:2017-09-25T07:31:46.477Z v:displayName="Alex Levitsky" v:roleName=editor v:id=9ufn-6bwh v:screenName="Alex Levitsky"
```

## Top Records

```ls
| fiscal_year | related_gov_t_units | organization_group_code | organization_group                      | department_code | department                      | program_code | program                                  | character_code | character | object_code | object                    | sub_object_code | sub_object     | fund_type_code | fund_type                             | fund_code | fund                            | fund_category_code | fund_category        | job_family_code | job_family                     | job_code | job                               | fte   | 
| =========== | =================== | ======================= | ======================================= | =============== | =============================== | ============ | ======================================== | ============== | ========= | =========== | ========================= | =============== | ============== | ============== | ===================================== | ========= | =============================== | ================== | ==================== | =============== | ============================== | ======== | ================================= | ===== | 
| 2015        | No                  | 01                      | Public Protection                       | POL             | Police                          | ACB          | Investigations                           | 001            | Salaries  | 001         | Permanent Salaries-Misc   | 00101           | Misc-Regular   | 1G             | General Fund                          | 1GAGF     | General Fund                    | 1                  | Operating            | 0900            | Management                     | 0922     | Manager I                         | 1     | 
| 2017        | No                  | 05                      | Culture & Recreation                    | REC             | Recreation and Park Commission  | ECU          | Recreation                               | 001            | Salaries  | 001         | Permanent Salaries-Misc   | 00101           | Misc-Regular   | 1G             | General Fund                          | 1GAGF     | General Fund                    | 1                  | Operating            | 0900            | Management                     | 0922     | Manager I                         | 1     | 
| 2012        | No                  | 02                      | Public Works, Transportation & Commerce | HHP             | PUC Hetch Hetchy                | BDA          | Administration                           | 001            | Salaries  | 001         | Permanent Salaries-Misc   | 00101           | Misc-Regular   | 5T             | PUC Hetch Hetchy Funds                | 5TAAA     | Hetch Hetchy Operating Fund     | 1                  | Operating            | 1800            | Budget, Admn & Stats Analysis  | 1823     | Senior Administrative Analyst     | 1     | 
| 2013        | No                  | 06                      | General Administration & Finance        | MYR             | Mayor                           | FEA          | City Administration                      | 001            | Salaries  | 001         | Permanent Salaries-Misc   | 00101           | Misc-Regular   | 1G             | General Fund                          | 1GAGF     | General Fund                    | 1                  | Operating            | 0900            | Management                     | 0885     | Mayoral Staff V                   | 1     | 
| 2013        | No                  | 06                      | General Administration & Finance        | TTX             | Treasurer/Tax Collector         | FCN          | Property Tax/Licensing                   | 001            | Salaries  | 001         | Permanent Salaries-Misc   | 00101           | Misc-Regular   | 1G             | General Fund                          | 1GAGF     | General Fund                    | 1                  | Operating            | 0000            | Turnover Allowance/Adjustment  | 9993M    | Attrition Savings - Miscellaneous | -2.77 | 
| 2014        | No                  | 02                      | Public Works, Transportation & Commerce | MTA             | Municipal Transportation Agency | BE3          | Security, Safety, Training & Enforcement | 001            | Salaries  | 001         | Permanent Salaries-Misc   | 00101           | Misc-Regular   | 5M             | MTA Municipal Railway Funds           | 5MAAA     | Muni Operating Fund             | 1                  | Operating            | 9100            | Street Transit                 | 9520     | Trans Safety Specialist           | 15    | 
| 2012        | No                  | 02                      | Public Works, Transportation & Commerce | MTA             | Municipal Transportation Agency | BE3          | Security, Safety, Training & Enforcement | 001            | Salaries  | 001         | Permanent Salaries-Misc   | 00101           | Misc-Regular   | 5M             | MTA Municipal Railway Funds           | 5MAAA     | Muni Operating Fund             | 1                  | Operating            | 6100            | Health & Sanitation Inspection | 6130     | Safety Analyst                    | 2     | 
| 2012        | No                  | 02                      | Public Works, Transportation & Commerce | MTA             | Municipal Transportation Agency | BEN          | Rail & Bus Services                      | 001            | Salaries  | 001         | Permanent Salaries-Misc   | 00101           | Misc-Regular   | 5M             | MTA Municipal Railway Funds           | 5MAAA     | Muni Operating Fund             | 1                  | Operating            | 1400            | Clerical, Secretarial & Steno  | 1424     | Clerk Typist                      | 3     | 
| 2013        | No                  | 04                      | Community Health                        | DPH             | Public Health                   | D1F          | SFGH - Acute Care - Forensics            | 001            | Salaries  | 004         | Permanent Salaries-Nurses | 00401           | Nurses-Regular | 5H             | General Hospital Medical Center Funds | 5HAAA     | General Hopsital Operating Fund | 1                  | Operating            | 2300            | Nursing                        | 2320     | Registered Nurse                  | 7.3   | 
| 2011        | No                  | 05                      | Culture & Recreation                    | REC             | Recreation and Park Commission  | EIA          | Rec & Park Administration                | 001            | Salaries  | 001         | Permanent Salaries-Misc   | 00101           | Misc-Regular   | 1G             | General Fund                          | 1GOHF     | Overhead Fund                   | 5                  | Work Orders/Overhead | 1000            | Information Systems            | 1022     | IS Administrator 2                | 2     | 
```