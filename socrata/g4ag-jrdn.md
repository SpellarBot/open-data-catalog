# Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), 2012 & 2014, Region 2 - New York

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-adults-who-report-driving-after-drinking-too-much-in-the-past-30-days-2012-r-00654) |
| Metadata | [Link](https://data.cdc.gov/api/views/g4ag-jrdn) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/g4ag-jrdn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/g4ag-jrdn/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | g4ag-jrdn |
| Name | Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), 2012 & 2014, Region 2 - New York |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T16:23:14Z |
| Publication Date | 2016-09-14T13:32:23Z |

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
series e:g4ag-jrdn d:2012-01-01T00:00:00.000Z t:state="New Jersey" m:2014=1.4 m:prevalence=1.5

series e:g4ag-jrdn d:2012-01-01T00:00:00.000Z t:state="New York" m:2014=1 m:prevalence=1.4

series e:g4ag-jrdn d:2012-01-01T00:00:00.000Z t:state="United States" m:2014=1.7 m:prevalence=1.9
```

## Meta Commands

```ls
metric m:prevalence p:float l:2012 t:dataTypeName=percent

metric m:2014 p:float l:2014 t:dataTypeName=percent

entity e:g4ag-jrdn l:"Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), 2012 & 2014, Region 2 - New York" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/g4ag-jrdn

property e:g4ag-jrdn t:meta.view v:id=g4ag-jrdn v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), 2012 & 2014, Region 2 - New York" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:g4ag-jrdn t:meta.view.license v:name="Public Domain"

property e:g4ag-jrdn t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:g4ag-jrdn t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:g4ag-jrdn t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | prevalence | 2014 | 
| ============= | ========== | ==== | 
| New Jersey    | 1.5        | 1.4  | 
| New York      | 1.4        | 1    | 
| United States | 1.9        | 1.7  | 
```