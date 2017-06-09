# Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), All States, 2012 & 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-adults-who-report-driving-after-drinking-too-much-in-the-past-30-days-all-st-b4f3b) |
| Metadata | [Link](https://data.cdc.gov/api/views/s9bp-7k3m) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/s9bp-7k3m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/s9bp-7k3m/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | s9bp-7k3m |
| Name | Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), All States, 2012 & 2014 |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-15T19:21:36Z |
| Publication Date | 2016-09-26T19:25:08Z |

## Description

Source: Behavioral Risk Factor Surveillance System (BRFSS), 2012 & 2014.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| Yes      | series tag     | state           | State            | text      | text        |
| Yes      | numeric metric | prevalence_2012 | Prevalence, 2012 | number    | number      |
| Yes      | numeric metric | prevalence_2014 | Prevalence, 2014 | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:s9bp-7k3m d:2012-01-01T00:00:00.000Z t:state="United States" m:prevalence_2014=1.7 m:prevalence_2012=1.9

series e:s9bp-7k3m d:2012-01-01T00:00:00.000Z t:state=Arizona m:prevalence_2014=1.6 m:prevalence_2012=1.7

series e:s9bp-7k3m d:2012-01-01T00:00:00.000Z t:state=Georgia m:prevalence_2014=0.7 m:prevalence_2012=1.4
```

## Meta Commands

```ls
metric m:prevalence_2012 p:float l:"Prevalence, 2012" t:dataTypeName=number

metric m:prevalence_2014 p:float l:"Prevalence, 2014" t:dataTypeName=number

entity e:s9bp-7k3m l:"Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), All States, 2012 & 2014" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/s9bp-7k3m

property e:s9bp-7k3m t:meta.view d:2017-06-09T13:52:22.326Z v:id=s9bp-7k3m v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety v:averageRating=0 v:name="Percentage of Adults Who Report Driving After Drinking Too Much (in the past 30 days), All States, 2012 & 2014" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:s9bp-7k3m t:meta.view.license d:2017-06-09T13:52:22.326Z v:name="Public Domain"

property e:s9bp-7k3m t:meta.view.owner d:2017-06-09T13:52:22.326Z v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:s9bp-7k3m t:meta.view.tableauthor d:2017-06-09T13:52:22.326Z v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:s9bp-7k3m t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:52:22.326Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | prevalence_2012 | prevalence_2014 | 
| ============= | =============== | =============== | 
| United States | 1.9             | 1.7             | 
| Arizona       | 1.7             | 1.6             | 
| Georgia       | 1.4             | 0.7             | 
| California    | 1.8             | 1.9             | 
| Minnesota     | 2.4             | 1.9             | 
| Oregon        | 1.4             | 1.6             | 
| Connecticut   | 2.1             | 1.9             | 
| Missouri      | 1.8             | 1.3             | 
| New York      | 1.4             | 1.0             | 
| Virginia      | 1.4             | 1.5             | 
```