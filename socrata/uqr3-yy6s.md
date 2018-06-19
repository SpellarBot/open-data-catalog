# County Regions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-regions-f17b3) |
| Metadata | [Link](https://data.mo.gov/api/views/uqr3-yy6s) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/uqr3-yy6s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/uqr3-yy6s/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | uqr3-yy6s |
| Name | County Regions |
| Created | 2014-04-16T20:48:32Z |
| Publication Date | 2014-05-19T21:47:54Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | polycode    | polyCode   | text      | text        |
| Yes      | series tag  | county      | county     | text      | text        |
| Yes      | series tag  | region      | region     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uqr3-yy6s d:2014-04-16T13:48:35.000Z t:region=NW t:county=Atchison t:polycode=MO-03 m:row_number.uqr3-yy6s=1

series e:uqr3-yy6s d:2014-04-16T13:48:35.000Z t:region=NW t:county=Nodaway t:polycode=MO-4A m:row_number.uqr3-yy6s=2

series e:uqr3-yy6s d:2014-04-16T13:48:35.000Z t:region=NW t:county=Worth t:polycode=MO-71 m:row_number.uqr3-yy6s=3
```

## Meta Commands

```ls
metric m:row_number.uqr3-yy6s p:long l:"Row Number"

entity e:uqr3-yy6s l:"County Regions" t:url=https://data.mo.gov/api/views/uqr3-yy6s

property e:uqr3-yy6s t:meta.view v:id=uqr3-yy6s v:averageRating=0 v:name="County Regions"

property e:uqr3-yy6s t:meta.view.owner v:id=xfqs-bcyn v:screenName=whitwo v:displayName=whitwo

property e:uqr3-yy6s t:meta.view.tableauthor v:id=xfqs-bcyn v:screenName=whitwo v:roleName=editor v:displayName=whitwo
```

## Top Records

```ls
| :updated_at | polycode | county   | region | 
| =========== | ======== | ======== | ====== | 
| 1397656115  | MO-03    | Atchison | NW     | 
| 1397656115  | MO-4A    | Nodaway  | NW     | 
| 1397656115  | MO-71    | Worth    | NW     | 
| 1397656115  | MO-29    | Harrison | NW     | 
| 1397656115  | MO-26    | Gentry   | NW     | 
| 1397656115  | MO-2C    | Holt     | NW     | 
| 1397656115  | MO-02    | Andrew   | NW     | 
| 1397656115  | MO-20    | DeKalb   | NW     | 
| 1397656115  | MO-1F    | Daviess  | NW     | 
| 1397656115  | MO-0B    | Buchanan | NW     | 
```