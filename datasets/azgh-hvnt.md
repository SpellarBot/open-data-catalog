# Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), 2012 & 2014, Region 4 - Atlanta

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-adults-who-report-driving-after-drinking-too-much-in-the-past-30-days-2012-r-3b532) |
| Metadata | [Link](https://data.cdc.gov/api/views/azgh-hvnt) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/azgh-hvnt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/azgh-hvnt/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | azgh-hvnt |
| Name | Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), 2012 & 2014, Region 4 - Atlanta |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T16:26:49Z |
| Publication Date | 2016-09-14T13:28:39Z |

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
series e:azgh-hvnt d:2012-01-01T00:00:00.000Z t:state=Alabama m:2014=1.3 m:prevalence=1.7

series e:azgh-hvnt d:2012-01-01T00:00:00.000Z t:state=Florida m:2014=1.7 m:prevalence=2.1

series e:azgh-hvnt d:2012-01-01T00:00:00.000Z t:state=Georgia m:2014=0.7 m:prevalence=1.4
```

## Meta Commands

```ls
metric m:prevalence p:float l:2012 t:dataTypeName=percent

metric m:2014 p:float l:2014 t:dataTypeName=percent

entity e:azgh-hvnt l:"Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days),  2012 & 2014, Region 4 - Atlanta" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/azgh-hvnt

property e:azgh-hvnt t:meta.view v:id=azgh-hvnt v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days),  2012 & 2014, Region 4 - Atlanta" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:azgh-hvnt t:meta.view.license v:name="Public Domain"

property e:azgh-hvnt t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:azgh-hvnt t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:azgh-hvnt t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state          | prevalence | 2014 | 
| ============== | ========== | ==== | 
| Alabama        | 1.7        | 1.3  | 
| Florida        | 2.1        | 1.7  | 
| Georgia        | 1.4        | 0.7  | 
| Kentucky       | 1.5        | 1.4  | 
| Mississippi    | 1.2        | 1.6  | 
| North Carolina | 1.4        | 1.2  | 
| South Carolina | 1.6        | 1.6  | 
| Tennessee      | 1.1        | 1.1  | 
| United States  | 1.9        | 1.7  | 
```