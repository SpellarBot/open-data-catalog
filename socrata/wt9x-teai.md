# ISAC FY12 FAFSA's Filed by School

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/isac-fy12-fafsas-filed-by-school-75710) |
| Metadata | [Link](https://data.illinois.gov/api/views/wt9x-teai) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wt9x-teai/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wt9x-teai/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wt9x-teai |
| Name | ISAC FY12 FAFSA's Filed by School |
| Attribution | ISAC |
| Category | Reference |
| Tags | fafsa, education, scholarship, school, college, isac |
| Created | 2011-09-02T14:22:45Z |
| Publication Date | 2011-09-02T14:22:45Z |

## Description

This data is current as of August 25th 2011.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | region      | REGION      | text      | number      |
| Yes      | series tag     | county      | COUNTY      | text      | text        |
| Yes      | series tag     | district    | DISTRICT    | text      | text        |
| Yes      | series tag     | high_school | HIGH SCHOOL | text      | text        |
| Yes      | series tag     | city        | CITY        | text      | text        |
| Yes      | numeric metric | fafsas_1    | #FAFSAS     | number    | number      |
| Yes      | numeric metric | fafsas_2    | %FAFSAS     | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wt9x-teai d:2011-09-02T07:22:46.000Z t:region=1 t:county=Adams t:high_school="Seymour High School" t:district=001 t:city=Payson m:fafsas_1=21 m:fafsas_2=60

series e:wt9x-teai d:2011-09-02T07:22:46.000Z t:region=1 t:county=Adams t:high_school="Liberty High School" t:district=002 t:city=Liberty m:fafsas_1=25 m:fafsas_2=56

series e:wt9x-teai d:2011-09-02T07:22:46.000Z t:region=1 t:county=Adams t:high_school="Central HS - Camp Point" t:district=003 t:city="Camp Point" m:fafsas_1=49 m:fafsas_2=73
```

## Meta Commands

```ls
metric m:fafsas_1 p:integer l:#FAFSAS t:dataTypeName=number

metric m:fafsas_2 p:integer l:%FAFSAS t:dataTypeName=percent

entity e:wt9x-teai l:"ISAC FY12 FAFSA's Filed by School" t:attribution=ISAC t:url=https://data.illinois.gov/api/views/wt9x-teai

property e:wt9x-teai t:meta.view v:id=wt9x-teai v:category=Reference v:attributionLink=http://www.collegeillinois.org/home/fafsa/index.html#hs v:averageRating=0 v:name="ISAC FY12 FAFSA's Filed by School" v:attribution=ISAC

property e:wt9x-teai t:meta.view.owner v:id=cypd-qxk7 v:screenName="Ramnath Cidambi" v:displayName="Ramnath Cidambi"

property e:wt9x-teai t:meta.view.tableauthor v:id=cypd-qxk7 v:screenName="Ramnath Cidambi" v:roleName=publisher v:displayName="Ramnath Cidambi"
```

## Top Records

```ls
| :updated_at | region | county | district | high_school                   | city          | fafsas_1 | fafsas_2 | 
| =========== | ====== | ====== | ======== | ============================= | ============= | ======== | ======== | 
| 1314948166  | 1      | Adams  | 001      | Seymour High School           | Payson        | 21       | 60       | 
| 1314948166  | 1      | Adams  | 002      | Liberty High School           | Liberty       | 25       | 56       | 
| 1314948166  | 1      | Adams  | 003      | Central HS - Camp Point       | Camp Point    | 49       | 73       | 
| 1314948166  | 1      | Adams  | 004      | Unity High School - Mendon    | Mendon        | 30       | 68       | 
| 1314948166  | 1      | Adams  | 172      | Quincy Sr High School         | Quincy        | 267      | 58       | 
| 1314948166  | 1      | Adams  | 012Y     | Quincy Notre Dame High School | Quincy        | 62       | 74       | 
| 1314948166  | 1      | Pike   | 003      | Pleasant Hill High School     | Pleasant Hill | 16       | 64       | 
| 1314948166  | 1      | Pike   | 004      | Griggsville-Perry High School | Griggsville   | 17       | 68       | 
| 1314948166  | 1      | Pike   | 010      | Pittsfield High School        | Pittsfield    | 59       | 66       | 
| 1314948166  | 1      | Pike   | 012      | Western High School           | Barry         | 27       | 64       | 
```