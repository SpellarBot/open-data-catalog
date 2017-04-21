# Geo Chart Test Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/geo-chart-test-data-51d8e) |
| Metadata | [Link](https://data.mo.gov/api/views/a8ec-ftm4) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/a8ec-ftm4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/a8ec-ftm4/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | a8ec-ftm4 |
| Name | Geo Chart Test Data |
| Created | 2014-05-07T13:50:56Z |
| Publication Date | 2014-05-07T13:51:19Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | polycode    | polyCode   | text      | text        |
| Yes      | series tag     | county      | county     | text      | text        |
| Yes      | series tag     | region      | region     | text      | text        |
| Yes      | series tag     | color       | color      | text      | text        |
| Yes      | series tag     | val1        | val1       | text      | text        |
| Yes      | numeric metric | val2        | val2       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a8ec-ftm4 d:2014-05-07T06:51:00.000Z t:region="North West" t:color=#FFBCBB t:county=Atchison t:val1=adsf t:polycode=MO-03 m:val2=123

series e:a8ec-ftm4 d:2014-05-07T06:51:00.000Z t:region="North West" t:color=#FFBCBB t:county=Nodaway t:val1=adsf t:polycode=MO-4A m:val2=56657

series e:a8ec-ftm4 d:2014-05-07T06:51:00.000Z t:region="North West" t:color=#FFBCBB t:county=Worth t:val1=qer t:polycode=MO-71 m:val2=7898
```

## Meta Commands

```ls
metric m:val2 p:integer l:val2 t:dataTypeName=number

entity e:a8ec-ftm4 l:"Geo Chart Test Data" t:url=https://data.mo.gov/api/views/a8ec-ftm4

property e:a8ec-ftm4 t:meta.view v:id=a8ec-ftm4 v:averageRating=0 v:name="Geo Chart Test Data"

property e:a8ec-ftm4 t:meta.view.owner v:id=xfqs-bcyn v:screenName=whitwo v:displayName=whitwo

property e:a8ec-ftm4 t:meta.view.tableauthor v:id=xfqs-bcyn v:screenName=whitwo v:roleName=editor v:displayName=whitwo
```

## Top Records

```ls
| :updated_at | polycode | county   | region     | color   | val1 | val2  | 
| =========== | ======== | ======== | ========== | ======= | ==== | ===== | 
| 1399445460  | MO-03    | Atchison | North West | #FFBCBB | adsf | 123   | 
| 1399445460  | MO-4A    | Nodaway  | North West | #FFBCBB | adsf | 56657 | 
| 1399445460  | MO-71    | Worth    | North West | #FFBCBB | qer  | 7898  | 
| 1399445460  | MO-29    | Harrison | North West | #FFBCBB | tgjh | 76546 | 
| 1399445460  | MO-26    | Gentry   | North West | #FFBCBB | qewr | 23    | 
| 1399445460  | MO-2C    | Holt     | North West | #FFBCBB | fhjy | 34    | 
| 1399445460  | MO-02    | Andrew   | North West | #FFBCBB | rtyu | 5645  | 
| 1399445460  | MO-20    | DeKalb   | North West | #FFBCBB | tyu  | 4557  | 
| 1399445460  | MO-1F    | Daviess  | North West | #FFBCBB | ghj  | 689   | 
| 1399445460  | MO-0B    | Buchanan | North West | #FFBCBB | fgh  | 56332 | 
```