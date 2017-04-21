# Table 19: Hazardous Waste Generated

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-19-hazardous-waste-generated-eecb9) |
| Metadata | [Link](https://data.hawaii.gov/api/views/h44e-tzy6) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/h44e-tzy6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/h44e-tzy6/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | h44e-tzy6 |
| Name | Table 19: Hazardous Waste Generated |
| Attribution | DOH |
| Category | Health |
| Tags | hazardous, waste, generated |
| Created | 2012-08-01T00:27:30Z |
| Publication Date | 2012-08-01T00:28:58Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                             | Data Type | Render Type |
| ======== | ============== | ============================== | ================================ | ========= | =========== |
| No       |                | _                              | #                                | number    | number      |
| Yes      | time           | calendar_year                  | Calendar Year                    | number    | text        |
| Yes      | numeric metric | hazardous_waste_generated_tons | Hazardous Waste Generated (Tons) | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:h44e-tzy6 d:2001-01-01T00:00:00.000Z m:hazardous_waste_generated_tons=781

series e:h44e-tzy6 d:2003-01-01T00:00:00.000Z m:hazardous_waste_generated_tons=1139

series e:h44e-tzy6 d:2005-01-01T00:00:00.000Z m:hazardous_waste_generated_tons=1458
```

## Meta Commands

```ls
metric m:hazardous_waste_generated_tons p:integer l:"Hazardous Waste Generated (Tons)" t:dataTypeName=number

entity e:h44e-tzy6 l:"Table 19: Hazardous Waste Generated" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/h44e-tzy6

property e:h44e-tzy6 t:meta.view v:id=h44e-tzy6 v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 19: Hazardous Waste Generated" v:attribution=DOH

property e:h44e-tzy6 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:h44e-tzy6 t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:h44e-tzy6 t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| _ | calendar_year | hazardous_waste_generated_tons | 
| = | ============= | ============================== | 
| 1 | 2001          | 781                            | 
| 3 | 2003          | 1139                           | 
| 5 | 2005          | 1458                           | 
| 7 | 2007          | 1224                           | 
| 9 | 2009          | 987                            | 
```