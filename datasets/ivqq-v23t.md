# Top 10 Source Countries Of International Students in the US 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/top-10-source-countries-of-international-students-in-the-us-2013-44dd7) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ivqq-v23t) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ivqq-v23t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ivqq-v23t/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ivqq-v23t |
| Name | Top 10 Source Countries Of International Students in the US 2013 |
| Attribution | Business Economic Development and Tourism |
| Created | 2014-01-04T00:06:38Z |
| Publication Date | 2014-01-04T00:22:17Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name            | Data Type | Render Type |
| ======== | ============== | ============== | =============== | ========= | =========== |
| Yes      | series tag     | country        | Country         | text      | text        |
| Yes      | numeric metric | no_of_students | No. of Students | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ivqq-v23t d:2013-01-01T00:00:00.000Z t:country=China m:no_of_students=235597

series e:ivqq-v23t d:2013-01-01T00:00:00.000Z t:country=India m:no_of_students=96754

series e:ivqq-v23t d:2013-01-01T00:00:00.000Z t:country="South Korea" m:no_of_students=70627
```

## Meta Commands

```ls
metric m:no_of_students p:integer l:"No. of Students" t:dataTypeName=number

entity e:ivqq-v23t l:"Top 10 Source Countries Of International Students in the US 2013" t:attribution="Business Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/ivqq-v23t

property e:ivqq-v23t t:meta.view v:id=ivqq-v23t v:averageRating=0 v:name="Top 10 Source Countries Of International Students in the US 2013" v:attribution="Business Economic Development and Tourism"

property e:ivqq-v23t t:meta.view.owner v:id=ev7f-hkyq v:screenName=Nathan v:displayName=Nathan

property e:ivqq-v23t t:meta.view.tableauthor v:id=ev7f-hkyq v:screenName=Nathan v:roleName=editor v:displayName=Nathan
```

## Top Records

```ls
| country      | no_of_students | 
| ============ | ============== | 
| China        | 235597         | 
| India        | 96754          | 
| South Korea  | 70627          | 
| Saudi Arabia | 44566          | 
| Canada       | 27357          | 
| Taiwan       | 21867          | 
| Japan        | 19568          | 
| Vietnam      | 16098          | 
| Mexico       | 14199          | 
| Turkey       | 11278          | 
```