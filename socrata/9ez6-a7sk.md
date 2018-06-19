# Salary ESD Wallowa Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-esd-wallowa-fiscal-year-2012-265a8) |
| Metadata | [Link](https://data.oregon.gov/api/views/9ez6-a7sk) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/9ez6-a7sk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/9ez6-a7sk/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 9ez6-a7sk |
| Name | Salary ESD Wallowa Fiscal Year 2012 |
| Attribution | Region 18 ESD |
| Category | Education |
| Tags | salary, esd, wallowa, region 18, 2012 |
| Created | 2012-11-28T23:11:55Z |
| Publication Date | 2012-11-28T23:14:19Z |

## Description

Salary ESD Wallowa Fiscal Year 2012

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | esd            | ESD #          | text      | text        |
| Yes      | series tag     | esd_name       | ESD NAME       | text      | text        |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | series tag     | full_part_time | FULL/PART TIME | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9ez6-a7sk d:2012-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:service_type=Unrepresented t:classification="Spec Ed. Teacher" t:esd="ESD #18" t:full_part_time="Full Time" m:annual_salary=48973

series e:9ez6-a7sk d:2012-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:service_type=Unrepresented t:classification="Executive Secretary" t:esd="ESD #18" t:full_part_time="3/4 time" m:annual_salary=19548

series e:9ez6-a7sk d:2012-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:service_type=Unrepresented t:classification="Spec. Ed. Aide" t:esd="ESD #18" t:full_part_time="3/4 Time" m:annual_salary=14612.63
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:9ez6-a7sk l:"Salary  ESD  Wallowa  Fiscal Year 2012" t:attribution="Region 18 ESD" t:url=https://data.oregon.gov/api/views/9ez6-a7sk

property e:9ez6-a7sk t:meta.view v:id=9ez6-a7sk v:category=Education v:averageRating=0 v:name="Salary  ESD  Wallowa  Fiscal Year 2012" v:attribution="Region 18 ESD"

property e:9ez6-a7sk t:meta.view.license v:name="Public Domain"

property e:9ez6-a7sk t:meta.view.owner v:id=ku36-3r9m v:screenName="Wallowa ESD Region 18" v:displayName="Wallowa ESD Region 18"

property e:9ez6-a7sk t:meta.view.tableauthor v:id=ku36-3r9m v:screenName="Wallowa ESD Region 18" v:roleName=editor v:displayName="Wallowa ESD Region 18"
```

## Top Records

```ls
| esd     | esd_name           | classification      | service_type  | full_part_time | annual_salary | 
| ======= | ================== | =================== | ============= | ============== | ============= | 
| ESD #18 | Wallowa County ESD | Spec Ed. Teacher    | Unrepresented | Full Time      | 48973.00      | 
| ESD #18 | Wallowa County ESD | Executive Secretary | Unrepresented | 3/4 time       | 19548.00      | 
| ESD #18 | Wallowa County ESD | Spec. Ed. Aide      | Unrepresented | 3/4 Time       | 14612.63      | 
| ESD #18 | Wallowa County ESD | Spec. Ed. Aide      | Unrepresented | 3/4 Time       | 15275.25      | 
| ESD #18 | Wallowa County ESD | Spec. Ed. Aide      | Unrepresented | 3/4 Time       | 14612.63      | 
| ESD #18 | Wallowa County ESD | EI Teacher          | Unrepresented | 3/4 Time       | 50148.00      | 
| ESD #18 | Wallowa County ESD | Spec Ed. Teacher    | Unrepresented | Full Time      | 59775.00      | 
| ESD #18 | Wallowa County ESD | Deputy Clerk        | Unrepresented | Full Time      | 40415.20      | 
| ESD #18 | Wallowa County ESD | Spec Ed. Teacher    | Unrepresented | Full Time      | 59775.00      | 
| ESD #18 | Wallowa County ESD | Speech Pathologist  | Unrepresented | Full Time      | 64305.00      | 
```