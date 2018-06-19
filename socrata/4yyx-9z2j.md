# Department of Information Technology- Performance Dashboard- Major IT Development Projects (Annual)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-information-technology-performance-dashboard-major-it-development-projects-a) |
| Metadata | [Link](https://data.maryland.gov/api/views/4yyx-9z2j) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/4yyx-9z2j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/4yyx-9z2j/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 4yyx-9z2j |
| Name | Department of Information Technology- Performance Dashboard- Major IT Development Projects (Annual) |
| Attribution | Department of Information Technology |
| Tags | department of information technology major it, project, doit, development |
| Created | 2016-06-27T13:14:42Z |
| Publication Date | 2016-10-07T18:25:42Z |

## Description

This dataset identfies the number of major IT development projects for the Department of Information Technology on an annual basis.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | time           | date                          | Date                          | calendar_date | calendar_date |
| Yes      | series tag     | fiscal_year                   | Fiscal Year                   | text          | text          |
| Yes      | numeric metric | major_it_development_projects | Major IT Development Projects | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:4yyx-9z2j d:2014-06-30T00:00:00.000Z t:fiscal_year=FY2014 m:major_it_development_projects=35

series e:4yyx-9z2j d:2015-06-30T00:00:00.000Z t:fiscal_year=FY2015 m:major_it_development_projects=29

series e:4yyx-9z2j d:2016-06-30T00:00:00.000Z t:fiscal_year=FY2016 m:major_it_development_projects=31
```

## Meta Commands

```ls
metric m:major_it_development_projects p:integer l:"Major IT Development Projects" d:"The number of major IT development projects on an annual basis." t:dataTypeName=number

entity e:4yyx-9z2j l:"Department of Information Technology- Performance Dashboard- Major IT Development Projects (Annual)" t:attribution="Department of Information Technology" t:url=https://data.maryland.gov/api/views/4yyx-9z2j

property e:4yyx-9z2j t:meta.view v:id=4yyx-9z2j v:attributionLink=http://doit.maryland.gov/Pages/default.aspx v:averageRating=0 v:name="Department of Information Technology- Performance Dashboard- Major IT Development Projects (Annual)" v:attribution="Department of Information Technology"

property e:4yyx-9z2j t:meta.view.owner v:id=iunp-cgkw v:screenName="Karen Poplewski" v:displayName="Karen Poplewski"

property e:4yyx-9z2j t:meta.view.tableauthor v:id=iunp-cgkw v:screenName="Karen Poplewski" v:roleName=editor v:displayName="Karen Poplewski"
```

## Top Records

```ls
| date                | fiscal_year | major_it_development_projects | 
| =================== | =========== | ============================= | 
| 2014-06-30T00:00:00 | FY2014      | 35                            | 
| 2015-06-30T00:00:00 | FY2015      | 29                            | 
| 2016-06-30T00:00:00 | FY2016      | 31                            | 
```