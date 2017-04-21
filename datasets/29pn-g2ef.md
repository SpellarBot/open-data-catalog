# State Virtual Server Growth

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-virtual-server-growth-a2477) |
| Metadata | [Link](https://data.mo.gov/api/views/29pn-g2ef) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/29pn-g2ef/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/29pn-g2ef/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 29pn-g2ef |
| Name | State Virtual Server Growth |
| Attribution | ITSD |
| Category | Information Technology |
| Tags | sdc, servers, information technology |
| Created | 2013-02-08T15:15:15Z |
| Publication Date | 2013-03-12T19:06:44Z |

## Description

In effort to increase efficiencies and reduce hardware costs, the State of Missouri has adopted virtualized servers to service agency IT infrastructure and computing needs.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type     | Render Type   |
| ======== | ============== | ================== | ==================== | ============= | ============= |
| Yes      | time           | month_year         | Month/Year           | calendar_date | calendar_date |
| Yes      | numeric metric | of_virtual_servers | # of Virtual Servers | number        | number        |
```

## Time Field

```ls
Value = month_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:29pn-g2ef d:2009-03-01T00:00:00.000Z m:of_virtual_servers=310

series e:29pn-g2ef d:2009-04-01T00:00:00.000Z m:of_virtual_servers=324

series e:29pn-g2ef d:2009-05-01T00:00:00.000Z m:of_virtual_servers=342
```

## Meta Commands

```ls
metric m:of_virtual_servers p:integer l:"# of Virtual Servers" t:dataTypeName=number

entity e:29pn-g2ef l:"State Virtual Server Growth" t:attribution=ITSD t:url=https://data.mo.gov/api/views/29pn-g2ef

property e:29pn-g2ef t:meta.view v:id=29pn-g2ef v:category="Information Technology" v:averageRating=0 v:name="State Virtual Server Growth" v:attribution=ITSD

property e:29pn-g2ef t:meta.view.owner v:id=348k-4yz7 v:screenName="State of Missouri" v:displayName="State of Missouri"

property e:29pn-g2ef t:meta.view.tableauthor v:id=348k-4yz7 v:screenName="State of Missouri" v:displayName="State of Missouri"
```

## Top Records

```ls
| month_year          | of_virtual_servers | 
| =================== | ================== | 
| 2009-03-01T00:00:00 | 310                | 
| 2009-04-01T00:00:00 | 324                | 
| 2009-05-01T00:00:00 | 342                | 
| 2009-06-01T00:00:00 | 358                | 
| 2009-07-01T00:00:00 | 364                | 
| 2009-08-01T00:00:00 | 379                | 
| 2009-09-01T00:00:00 | 404                | 
| 2009-10-01T00:00:00 | 431                | 
| 2009-11-01T00:00:00 | 443                | 
| 2009-12-01T00:00:00 | 454                | 
```