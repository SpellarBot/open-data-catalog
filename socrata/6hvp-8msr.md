# 2013 Small Cities Applicants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-small-cities-applicants) |
| Metadata | [Link](https://data.ct.gov/api/views/6hvp-8msr) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/6hvp-8msr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/6hvp-8msr/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 6hvp-8msr |
| Name | 2013 Small Cities Applicants |
| Category | Housing and Development |
| Tags | cdbg, community, development, block grant |
| Created | 2014-05-21T19:21:39Z |
| Publication Date | 2014-05-21T19:23:32Z |

## Description

These are the approved applicants funded under the Federal Small Cities Community Development Block Grant (SC-CDBG) for 2013.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | town       | Town      | text      | text        |
| Yes      | series tag     | activity   | Activity  | text      | text        |
| Yes      | numeric metric | request    | $ Request | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6hvp-8msr d:2013-01-01T00:00:00.000Z t:town=Canterbury t:activity="Housing Rehabilitation" m:request=400000

series e:6hvp-8msr d:2013-01-01T00:00:00.000Z t:town=Ashford t:activity="Housing Rehabilitation" m:request=400000

series e:6hvp-8msr d:2013-01-01T00:00:00.000Z t:town=Torrington t:activity="Housing Rehabilitation" m:request=400000
```

## Meta Commands

```ls
metric m:request p:integer l:"$ Request" t:dataTypeName=money

entity e:6hvp-8msr l:"2013 Small Cities Applicants" t:url=https://data.ct.gov/api/views/6hvp-8msr

property e:6hvp-8msr t:meta.view v:id=6hvp-8msr v:category="Housing and Development" v:averageRating=0 v:name="2013 Small Cities Applicants"

property e:6hvp-8msr t:meta.view.owner v:id=bdhz-s7cj v:screenName="Dimple Desai" v:displayName="Dimple Desai"

property e:6hvp-8msr t:meta.view.tableauthor v:id=bdhz-s7cj v:screenName="Dimple Desai" v:roleName=editor v:displayName="Dimple Desai"
```

## Top Records

```ls
| town         | activity                     | request | 
| ============ | ============================ | ======= | 
| Canterbury   | Housing Rehabilitation       | 400000  | 
| Ashford      | Housing Rehabilitation       | 400000  | 
| Torrington   | Housing Rehabilitation       | 400000  | 
| Windham      | Housing Rehabilitation       | 400000  | 
| Vernon       | Housing Rehabilitation       | 400000  | 
| Plainfield   | Housing Rehabilitation       | 400000  | 
| Hampton      | Housing Rehabilitation       | 450000  | 
| Lebanon      | Housing Rehabilitation       | 400000  | 
| Southbury    | Housing Rehabilitation       | 400000  | 
| East Hampton | Public Housing Modernization | 800000  | 
```