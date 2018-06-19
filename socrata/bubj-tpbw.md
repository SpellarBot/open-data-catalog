# DBEDT Hawaii State Agencies Electricity Consumption And Cost FY05- FY10

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-state-agencies-electricity-consumption-and-cost-fy05-fy10-fbdac) |
| Metadata | [Link](https://data.hawaii.gov/api/views/bubj-tpbw) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/bubj-tpbw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/bubj-tpbw/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | bubj-tpbw |
| Name | DBEDT Hawaii State Agencies Electricity Consumption And Cost FY05- FY10 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | electricity, energy |
| Created | 2012-08-28T20:23:04Z |
| Publication Date | 2012-08-29T01:31:40Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | x_values             | X Values             | text      | text        |
| Yes      | numeric metric | electricity_consumed | Electricity Consumed | number    | number      |
| Yes      | numeric metric | cost_of_electricity  | Cost of Electricity  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bubj-tpbw d:2012-08-28T13:23:06.000Z t:x_values=FY05 m:cost_of_electricity=104838864 m:electricity_consumed=678185677

series e:bubj-tpbw d:2012-08-28T13:23:06.000Z t:x_values=FY06 m:cost_of_electricity=129950063 m:electricity_consumed=694545300

series e:bubj-tpbw d:2012-08-28T13:23:06.000Z t:x_values=FY07 m:cost_of_electricity=133915937 m:electricity_consumed=702501532
```

## Meta Commands

```ls
metric m:electricity_consumed p:integer l:"Electricity Consumed" t:dataTypeName=number

metric m:cost_of_electricity p:integer l:"Cost of Electricity" t:dataTypeName=number

entity e:bubj-tpbw l:"DBEDT Hawaii State Agencies Electricity Consumption And Cost FY05- FY10" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/bubj-tpbw

property e:bubj-tpbw t:meta.view v:id=bubj-tpbw v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii State Agencies Electricity Consumption And Cost FY05- FY10" v:attribution="Department of Economic Development and Tourism"

property e:bubj-tpbw t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:bubj-tpbw t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:bubj-tpbw t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| :updated_at | x_values | electricity_consumed | cost_of_electricity | 
| =========== | ======== | ==================== | =================== | 
| 1346160186  | FY05     | 678185677            | 104838864           | 
| 1346160186  | FY06     | 694545300            | 129950063           | 
| 1346160186  | FY07     | 702501532            | 133915937           | 
| 1346160186  | FY08     | 701719061            | 163139046           | 
| 1346160186  | FY09     | 661566196            | 165124825           | 
| 1346160186  | FY10     | 643310297            | 145175672           | 
```