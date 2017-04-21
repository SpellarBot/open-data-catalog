# Csv Pop Cnt

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/csv-pop-cnt) |
| Metadata | [Link](https://data.ct.gov/api/views/bcjq-rnid) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/bcjq-rnid/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/bcjq-rnid/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | bcjq-rnid |
| Name | Csv Pop Cnt |
| Created | 2015-08-12T19:03:02Z |
| Publication Date | 2015-08-12T19:03:32Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | date        | date        | text      | text        |
| Yes      | numeric metric | unsentenced | unsentenced | number    | number      |
```

## Time Field

```ls
Value = date
Format & Zone = MM/dd/yyyy
```

## Data Commands

```ls
series e:bcjq-rnid d:2015-07-21T00:00:00.000Z m:unsentenced=3318

series e:bcjq-rnid d:2015-07-21T00:00:00.000Z m:unsentenced=3333

series e:bcjq-rnid d:2015-07-22T00:00:00.000Z m:unsentenced=3319
```

## Meta Commands

```ls
metric m:unsentenced p:integer l:unsentenced t:dataTypeName=number

entity e:bcjq-rnid l:"Csv Pop Cnt" t:url=https://data.ct.gov/api/views/bcjq-rnid

property e:bcjq-rnid t:meta.view v:id=bcjq-rnid v:averageRating=0 v:name="Csv Pop Cnt"

property e:bcjq-rnid t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:bcjq-rnid t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| date       | unsentenced | 
| ========== | =========== | 
| 7/21/2015  | 3318        | 
| 07/21/2015 | 3333        | 
| 07/22/2015 | 3319        | 
```