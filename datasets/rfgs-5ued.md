# Statewide WQ

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-wq-4fca1) |
| Metadata | [Link](https://data.wa.gov/api/views/rfgs-5ued) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/rfgs-5ued/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/rfgs-5ued/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | rfgs-5ued |
| Name | Statewide WQ |
| Created | 2012-12-03T22:22:50Z |
| Publication Date | 2012-12-04T16:37:10Z |

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| No       | time        | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | region                  | Region                  | text      | text        |
| Yes      | series tag  | water_quality_condition | Water Quality Condition | text      | text        |
| No       |             | _                       | Percent of Sites        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:rfgs-5ued d:2012-12-04T08:37:01.000Z t:region=Statewide t:water_quality_condition="Sites w/ improving WQ" m:row_number.rfgs-5ued=1

series e:rfgs-5ued d:2012-12-04T08:37:01.000Z t:region=Statewide t:water_quality_condition="Sites w/ decreasing WQ" m:row_number.rfgs-5ued=2

series e:rfgs-5ued d:2012-12-04T08:37:01.000Z t:region=Statewide t:water_quality_condition="Sites w/ unchanged WQ" m:row_number.rfgs-5ued=3
```

## Meta Commands

```ls
metric m:row_number.rfgs-5ued p:long l:"Row Number"

entity e:rfgs-5ued l:"Statewide WQ" t:url=https://data.wa.gov/api/views/rfgs-5ued

property e:rfgs-5ued t:meta.view v:id=rfgs-5ued v:averageRating=0 v:name="Statewide WQ"

property e:rfgs-5ued t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:rfgs-5ued t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | region    | water_quality_condition | _  | 
| =========== | ========= | ======================= | == | 
| 1354610221  | Statewide | Sites w/ improving WQ   | 35 | 
| 1354610221  | Statewide | Sites w/ decreasing WQ  | 5  | 
| 1354610221  | Statewide | Sites w/ unchanged WQ   | 60 | 
```