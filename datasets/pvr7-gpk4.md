# Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), 2012 & 2014, Region 7 - Kansas City

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-adults-who-report-driving-after-drinking-too-much-in-the-past-30-days-2012-r-023a6) |
| Metadata | [Link](https://data.cdc.gov/api/views/pvr7-gpk4) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/pvr7-gpk4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/pvr7-gpk4/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | pvr7-gpk4 |
| Name | Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), 2012 & 2014, Region 7 - Kansas City |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T16:30:54Z |
| Publication Date | 2016-09-14T13:21:23Z |

## Description

Source: Behavioral Risk Factor Surveillance System (BRFSS), 2012, 2014.

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | series tag     | state      | State | text      | text        |
| Yes      | numeric metric | prevalence | 2012  | percent   | percent     |
| Yes      | numeric metric | 2014       | 2014  | percent   | percent     |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pvr7-gpk4 d:2012-01-01T00:00:00.000Z t:state=Iowa m:2014=2.8 m:prevalence=3.1

series e:pvr7-gpk4 d:2012-01-01T00:00:00.000Z t:state=Kansas m:2014=1.4 m:prevalence=2.1

series e:pvr7-gpk4 d:2012-01-01T00:00:00.000Z t:state=Missouri m:2014=1.3 m:prevalence=1.8
```

## Meta Commands

```ls
metric m:prevalence p:float l:2012 t:dataTypeName=percent

metric m:2014 p:float l:2014 t:dataTypeName=percent

entity e:pvr7-gpk4 l:"Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days),  2012 & 2014, Region 7 - Kansas City" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/pvr7-gpk4

property e:pvr7-gpk4 t:meta.view v:id=pvr7-gpk4 v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days),  2012 & 2014, Region 7 - Kansas City" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:pvr7-gpk4 t:meta.view.license v:name="Public Domain"

property e:pvr7-gpk4 t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:pvr7-gpk4 t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:pvr7-gpk4 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | prevalence | 2014 | 
| ============= | ========== | ==== | 
| Iowa          | 3.1        | 2.8  | 
| Kansas        | 2.1        | 1.4  | 
| Missouri      | 1.8        | 1.3  | 
| United States | 1.9        | 1.7  | 
| Nebraska      | 3.4        | 2.5  | 
```