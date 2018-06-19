# Garbage Collection Routes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/garbage-collection-routes) |
| Metadata | [Link](https://data.ct.gov/api/views/ie23-wrng) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ie23-wrng/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ie23-wrng/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ie23-wrng |
| Name | Garbage Collection Routes |
| Category | Government |
| Tags | garbage collection |
| Created | 2015-07-16T14:52:41Z |
| Publication Date | 2015-07-16T14:55:35Z |

## Description

Garbage Collection Routes

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | street_name | Street Name | text      | text        |
| Yes      | series tag  | garbage     | GARBAGE     | text      | text        |
| Yes      | series tag  | range       | RANGE       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ie23-wrng d:2015-07-16T07:52:46.000Z t:street_name="DUNN AVE EXT" t:garbage=FRIDAY m:row_number.ie23-wrng=1

series e:ie23-wrng d:2015-07-16T07:52:46.000Z t:street_name="ROLLING WOOD DR" t:garbage=THURSDAY m:row_number.ie23-wrng=2

series e:ie23-wrng d:2015-07-16T07:52:46.000Z t:street_name="ABEL AVE" t:garbage=WEDNESDAY m:row_number.ie23-wrng=3
```

## Meta Commands

```ls
metric m:row_number.ie23-wrng p:long l:"Row Number"

entity e:ie23-wrng l:"Garbage Collection Routes" t:url=https://data.ct.gov/api/views/ie23-wrng

property e:ie23-wrng t:meta.view v:id=ie23-wrng v:category=Government v:averageRating=0 v:name="Garbage Collection Routes"

property e:ie23-wrng t:meta.view.owner v:id=d2jw-b5qp v:screenName="City of Stamford" v:displayName="City of Stamford"

property e:ie23-wrng t:meta.view.tableauthor v:id=d2jw-b5qp v:screenName="City of Stamford" v:roleName=publisher v:displayName="City of Stamford"
```

## Top Records

```ls
| :updated_at | street_name     | garbage           | range | 
| =========== | =============== | ================= | ===== | 
| 1437033166  | DUNN AVE EXT    | FRIDAY            |       | 
| 1437033166  | ROLLING WOOD DR | THURSDAY          |       | 
| 1437033166  | ABEL AVE        | WEDNESDAY         |       | 
| 1437033166  | ABERDEEN ST     | TUESDAY,FRIDAY    |       | 
| 1437033166  | ACOSTA ST       | TUESDAY           |       | 
| 1437033166  | ACRE VIEW DR    | NO GARBAGE PICKUP |       | 
| 1437033166  | ADAMS AVE       | TUESDAY,FRIDAY    |       | 
| 1437033166  | AKBAR RD        | NO GARBAGE PICKUP |       | 
| 1437033166  | ALBERT PL       | THURSDAY          |       | 
| 1437033166  | ALBIN RD        | MONDAY            |       | 
```