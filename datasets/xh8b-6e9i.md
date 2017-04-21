# Precinct and District

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/precinct-and-district-6694c) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/xh8b-6e9i) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/xh8b-6e9i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/xh8b-6e9i/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | xh8b-6e9i |
| Name | Precinct and District |
| Category | Election operations |
| Tags | precicncts, districts, elctions, kingcounty, voter |
| Created | 2012-09-07T16:16:49Z |
| Publication Date | 2012-09-07T16:21:55Z |

## Description

Combined Precincts Districts for King County Elections

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | precinct_id | precinct_id | text      | number      |
| Yes      | series tag  | district_id | district_id | text      | number      |
| Yes      | series tag  | timestamp   | timestamp   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xh8b-6e9i d:2012-09-07T09:16:51.000Z t:timestamp=000000000A1AC52D t:precinct_id=4 t:district_id=8 m:row_number.xh8b-6e9i=1

series e:xh8b-6e9i d:2012-09-07T09:16:51.000Z t:timestamp=000000001E68EB26 t:precinct_id=4 t:district_id=18 m:row_number.xh8b-6e9i=2

series e:xh8b-6e9i d:2012-09-07T09:16:51.000Z t:timestamp=00000000065DC99D t:precinct_id=4 t:district_id=36 m:row_number.xh8b-6e9i=3
```

## Meta Commands

```ls
metric m:row_number.xh8b-6e9i p:long l:"Row Number"

entity e:xh8b-6e9i l:"Precinct and District" t:url=https://data.kingcounty.gov/api/views/xh8b-6e9i

property e:xh8b-6e9i t:meta.view v:id=xh8b-6e9i v:category="Election operations" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="Precinct and District"

property e:xh8b-6e9i t:meta.view.owner v:id=bkmh-fhfb v:screenName="Asera Khatun" v:displayName="Asera Khatun"

property e:xh8b-6e9i t:meta.view.tableauthor v:id=bkmh-fhfb v:screenName="Asera Khatun" v:roleName=publisher v:displayName="Asera Khatun"
```

## Top Records

```ls
| :updated_at | precinct_id | district_id | timestamp        | 
| =========== | =========== | =========== | ================ | 
| 1347009411  | 4           | 8           | 000000000A1AC52D | 
| 1347009411  | 4           | 18          | 000000001E68EB26 | 
| 1347009411  | 4           | 36          | 00000000065DC99D | 
| 1347009411  | 4           | 93          | 00000000065E089C | 
| 1347009411  | 4           | 96          | 00000000065DAD9B | 
| 1347009411  | 4           | 111         | 00000000065DF8BC | 
| 1347009411  | 4           | 126         | 00000000065E089D | 
| 1347009411  | 4           | 132         | 00000000065DD546 | 
| 1347009411  | 4           | 2810        | 0000000007797CB8 | 
| 1347009411  | 4           | 2822        | 000000000E35FBFF | 
```