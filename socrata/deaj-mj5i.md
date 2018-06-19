# Table 11: Total Underground Injection Control (UIC) Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-11-total-underground-injection-control-uic-permits-bd015) |
| Metadata | [Link](https://data.hawaii.gov/api/views/deaj-mj5i) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/deaj-mj5i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/deaj-mj5i/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | deaj-mj5i |
| Name | Table 11: Total Underground Injection Control (UIC) Permits |
| Attribution | DOH |
| Category | Health |
| Tags | underground, injection, control |
| Created | 2012-07-31T23:55:08Z |
| Publication Date | 2012-07-31T23:59:27Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                           | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================== | ========= | =========== |
| No       |                | _                                            | #                                              | number    | number      |
| Yes      | time           | calendar_year                                | Calendar Year*                                 | number    | text        |
| Yes      | numeric metric | total_uic_permits                            | Total UIC Permits                              | number    | number      |
| Yes      | numeric metric | total_expired_permits                        | Total Expired Permits                          | number    | number      |
| Yes      | numeric metric | percent_of_total_with_current_permits        | Percent of Total with Current Permits          | percent   | percent     |
| Yes      | numeric metric | percent_of_current_sewage_industrial_permits | Percent of Current Sewage & Industrial Permits | percent   | percent     |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:deaj-mj5i d:2006-01-01T00:00:00.000Z m:total_uic_permits=714 m:percent_of_total_with_current_permits=50 m:total_expired_permits=358 m:percent_of_current_sewage_industrial_permits=55.5

series e:deaj-mj5i d:2007-01-01T00:00:00.000Z m:total_uic_permits=768 m:percent_of_total_with_current_permits=47 m:total_expired_permits=364 m:percent_of_current_sewage_industrial_permits=59.7

series e:deaj-mj5i d:2008-01-01T00:00:00.000Z m:total_uic_permits=796 m:percent_of_total_with_current_permits=48 m:total_expired_permits=379 m:percent_of_current_sewage_industrial_permits=59.6
```

## Meta Commands

```ls
metric m:total_uic_permits p:integer l:"Total UIC Permits" t:dataTypeName=number

metric m:total_expired_permits p:integer l:"Total Expired Permits" t:dataTypeName=number

metric m:percent_of_total_with_current_permits p:integer l:"Percent of Total with Current Permits" t:dataTypeName=percent

metric m:percent_of_current_sewage_industrial_permits p:float l:"Percent of Current Sewage & Industrial Permits" t:dataTypeName=percent

entity e:deaj-mj5i l:"Table 11: Total Underground Injection Control (UIC) Permits" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/deaj-mj5i

property e:deaj-mj5i t:meta.view v:id=deaj-mj5i v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 11: Total Underground Injection Control (UIC) Permits" v:attribution=DOH

property e:deaj-mj5i t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:deaj-mj5i t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:deaj-mj5i t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| _ | calendar_year | total_uic_permits | total_expired_permits | percent_of_total_with_current_permits | percent_of_current_sewage_industrial_permits | 
| = | ============= | ================= | ===================== | ===================================== | ============================================ | 
| 1 | 2006          | 714               | 358                   | 50                                    | 55.5                                         | 
| 2 | 2007          | 768               | 364                   | 47                                    | 59.7                                         | 
| 4 | 2008          | 796               | 379                   | 48                                    | 59.6                                         | 
|   |               |                   |                       |                                       |                                              | 
|   |               |                   |                       |                                       |                                              | 
| 5 | 2009          | 818               | 374                   | 46                                    | 63                                           | 
| 6 | 2010          | 857               | 385                   | 45                                    | 66.9                                         | 
```