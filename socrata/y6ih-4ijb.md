# FDNY Fire Rule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fdny-fire-rule-3131d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/y6ih-4ijb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/y6ih-4ijb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/y6ih-4ijb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | y6ih-4ijb |
| Name | FDNY Fire Rule |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fdny, fire department, safety, fire safety, fire department rule |
| Created | 2013-01-23T20:17:16Z |
| Publication Date | 2013-01-23T21:28:39Z |

## Description

RULES OF THE FIRE DEPARTMENT OF THE CITY OF NEW YORK (TITLE 3 OF THE RULES OF THE CITY OF NEW YORK)

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                             | Data Type | Render Type |
| ======== | =========== | ================================ | ================================ | ========= | =========== |
| No       | time        | :updated_at                      | updated_at                       | meta_data | meta_data   |
| Yes      | series tag  | chapter_number                   | Chapter Number                   | text      | text        |
| Yes      | series tag  | chapter_name                     | Chapter Name                     | text      | text        |
| Yes      | series tag  | fire_department_rule_number      | Fire Department Rule Number      | text      | text        |
| Yes      | series tag  | fire_department_rule_description | Fire Department Rule Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:y6ih-4ijb d:2013-01-23T13:28:28.000Z t:fire_department_rule_number=?101 t:chapter_number="Chapter 1" t:chapter_name=ADMINISTRATION t:fire_department_rule_description=Reserved m:row_number.y6ih-4ijb=1

series e:y6ih-4ijb d:2013-01-23T13:28:28.000Z t:fire_department_rule_number=?102-01 t:chapter_number="Chapter 1" t:chapter_name=ADMINISTRATION t:fire_department_rule_description="Pre-Existing Facilities and Conditions" m:row_number.y6ih-4ijb=2

series e:y6ih-4ijb d:2013-01-23T13:28:28.000Z t:fire_department_rule_number=?103 t:chapter_number="Chapter 1" t:chapter_name=ADMINISTRATION t:fire_department_rule_description=Reserved m:row_number.y6ih-4ijb=3
```

## Meta Commands

```ls
metric m:row_number.y6ih-4ijb p:long l:"Row Number"

entity e:y6ih-4ijb l:"FDNY Fire Rule" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/y6ih-4ijb

property e:y6ih-4ijb t:meta.view v:id=y6ih-4ijb v:category="Public Safety" v:attributionLink=http://www.nyc.gov/html/fdny/pdf/rules/rules_compilation_4th.pdf v:averageRating=0 v:name="FDNY Fire Rule" v:attribution="Fire Department of New York City (FDNY)"

property e:y6ih-4ijb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:y6ih-4ijb t:meta.view.tableauthor v:id=syvn-4vgv v:screenName="Sudhir Vasudeva" v:displayName="Sudhir Vasudeva"
```

## Top Records

```ls
| :updated_at | chapter_number | chapter_name   | fire_department_rule_number | fire_department_rule_description                                            | 
| =========== | ============== | ============== | =========================== | =========================================================================== | 
| 1358947708  | Chapter 1      | ADMINISTRATION | ?101                        | Reserved                                                                    | 
| 1358947708  | Chapter 1      | ADMINISTRATION | ?102-01                     | Pre-Existing Facilities and Conditions                                      | 
| 1358947708  | Chapter 1      | ADMINISTRATION | ?103                        | Reserved                                                                    | 
| 1358947708  | Chapter 1      | ADMINISTRATION | ?104-01                     | Appeals                                                                     | 
| 1358947708  | Chapter 1      | ADMINISTRATION | ?104-02                     | Professional Certification of Fire Alarm System Installations               | 
| 1358947708  | Chapter 1      | ADMINISTRATION | ?104-03                     | Disposal of Contraband Materials                                            | 
| 1358947708  | Chapter 1      | ADMINISTRATION | ?104-04                     | Modification of Rules                                                       | 
| 1358947708  | Chapter 1      | ADMINISTRATION | ?105-01                     | Approval of Fire Alarm System Installations                                 | 
| 1358947708  | Chapter 1      | ADMINISTRATION | ?106-108                    | Reserved                                                                    | 
| 1358947708  | Chapter 1      | ADMINISTRATION | ?109-01                     | Notice of Violation, Certification of Correction and Stipulation Procedures | 
```