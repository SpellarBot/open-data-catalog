# Total HASA Cases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-hasa-cases) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/j7wp-ax4x) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/j7wp-ax4x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/j7wp-ax4x/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | j7wp-ax4x |
| Name | Total HASA Cases |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Created | 2016-02-01T17:48:18Z |
| Publication Date | 2016-11-04T14:10:14Z |

## Description

Total number of HASA cases.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | time           | month      | Month      | text      | text        |
| Yes      | numeric metric | hasa_cases | HASA Cases | number    | number      |
```

## Time Field

```ls
Value = month
Format & Zone = MMM-yy
```

## Data Commands

```ls
series e:j7wp-ax4x d:2007-01-01T00:00:00.000Z m:hasa_cases=30309

series e:j7wp-ax4x d:2007-02-01T00:00:00.000Z m:hasa_cases=30237

series e:j7wp-ax4x d:2007-03-01T00:00:00.000Z m:hasa_cases=30333
```

## Meta Commands

```ls
metric m:hasa_cases p:integer l:"HASA Cases" t:dataTypeName=number

entity e:j7wp-ax4x l:"Total HASA Cases" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/j7wp-ax4x

property e:j7wp-ax4x t:meta.view v:id=j7wp-ax4x v:category="Social Services" v:averageRating=0 v:name="Total HASA Cases" v:attribution="Human Resources Administration (HRA)"

property e:j7wp-ax4x t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:j7wp-ax4x t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| month  | hasa_cases | 
| ====== | ========== | 
| Jan-07 | 30309      | 
| Feb-07 | 30237      | 
| Mar-07 | 30333      | 
| Apr-07 | 30293      | 
| May-07 | 30304      | 
| Jun-07 | 30259      | 
| Jul-07 | 30279      | 
| Aug-07 | 30395      | 
| Sep-07 | 30245      | 
| Oct-07 | 30412      | 
```