# WA State Barriers 10-31-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wa-state-barriers-10-31-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/jszx-mdmf) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/jszx-mdmf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/jszx-mdmf/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | jszx-mdmf |
| Name | WA State Barriers 10-31-2016 |
| Created | 2016-10-31T21:22:52Z |
| Publication Date | 2016-10-31T21:31:38Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | condition     | Condition     | text      | text        |
| Yes      | numeric metric | of_barriers_1 | # of Barriers | number    | text        |
| Yes      | numeric metric | of_barriers_2 | % of Barriers | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jszx-mdmf d:2016-01-01T00:00:00.000Z t:condition="Barriers Corrected" m:of_barriers_2=16 m:of_barriers_1=6500

series e:jszx-mdmf d:2016-01-01T00:00:00.000Z t:condition="Barriers Not Yet Corrected" m:of_barriers_2=84 m:of_barriers_1=33500
```

## Meta Commands

```ls
metric m:of_barriers_1 p:integer l:"# of Barriers" t:dataTypeName=number

metric m:of_barriers_2 p:integer l:"% of Barriers" t:dataTypeName=number

entity e:jszx-mdmf l:"WA State Barriers 10-31-2016" t:url=https://data.wa.gov/api/views/jszx-mdmf

property e:jszx-mdmf t:meta.view v:id=jszx-mdmf v:averageRating=0 v:name="WA State Barriers 10-31-2016"

property e:jszx-mdmf t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:jszx-mdmf t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| condition                  | of_barriers_1 | of_barriers_2 | 
| ========================== | ============= | ============= | 
| Barriers Corrected         | 6500          | 16            | 
| Barriers Not Yet Corrected | 33500         | 84            | 
```