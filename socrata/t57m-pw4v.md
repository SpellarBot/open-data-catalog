# Commercial Vehicle Safety Division- Lane Inspection

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commercial-vehicle-safety-division-lane-inspection) |
| Metadata | [Link](https://data.ct.gov/api/views/t57m-pw4v) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/t57m-pw4v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/t57m-pw4v/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | t57m-pw4v |
| Name | Commercial Vehicle Safety Division- Lane Inspection |
| Attribution | Department of Motor Vehicles |
| Category | Transportation |
| Tags | dmv |
| Created | 2014-10-29T20:02:50Z |
| Publication Date | 2014-10-29T20:05:17Z |

## Description

Type of Lane Inspections performed at Wethersfield and Hamden inspection Lane During January through August 2014

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | type_of_inspections | Type of Inspections | text      | text        |
| Yes      | numeric metric | wethersfield        | Wethersfield        | number    | number      |
| Yes      | numeric metric | hamden              | Hamden              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:t57m-pw4v d:2014-10-29T13:02:53.000Z t:type_of_inspections="VIN Verification" m:wethersfield=246 m:hamden=235

series e:t57m-pw4v d:2014-10-29T13:02:53.000Z t:type_of_inspections=Salvage m:wethersfield=1014 m:hamden=287

series e:t57m-pw4v d:2014-10-29T13:02:53.000Z t:type_of_inspections="Warning Ticket" m:wethersfield=149 m:hamden=129
```

## Meta Commands

```ls
metric m:wethersfield p:integer l:Wethersfield t:dataTypeName=number

metric m:hamden p:integer l:Hamden t:dataTypeName=number

entity e:t57m-pw4v l:"Commercial Vehicle Safety Division- Lane Inspection" t:attribution="Department of Motor Vehicles" t:url=https://data.ct.gov/api/views/t57m-pw4v

property e:t57m-pw4v t:meta.view v:id=t57m-pw4v v:category=Transportation v:averageRating=0 v:name="Commercial Vehicle Safety Division- Lane Inspection" v:attribution="Department of Motor Vehicles"

property e:t57m-pw4v t:meta.view.owner v:id=fd5k-6njr v:screenName=APatel v:displayName=APatel

property e:t57m-pw4v t:meta.view.tableauthor v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel
```

## Top Records

```ls
| :updated_at | type_of_inspections | wethersfield | hamden | 
| =========== | =================== | ============ | ====== | 
| 1414587773  | VIN Verification    | 246          | 235    | 
| 1414587773  | Salvage             | 1014         | 287    | 
| 1414587773  | Warning Ticket      | 149          | 129    | 
| 1414587773  | Re-Inspection       | 1363         | 564    | 
| 1414587773  | Misc.(STV,)         | 1053         | 276    | 
| 1414587773  | Window Tint         | 151          | 93     | 
| 1414587773  | VIN Assignment      | 361          | 109    | 
| 1414587773  | Ambulance           | 219          | 96     | 
| 1414587773  | Homemade Trailer    | 408          | 91     | 
| 1414587773  | Taxi                | 81           | 69     | 
```