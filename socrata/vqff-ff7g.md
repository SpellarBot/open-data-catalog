# Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 4 - Atlanta

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-drivers-and-front-seat-passengers-wearing-seat-belts-2012-region-4-atlanta-3261d) |
| Metadata | [Link](https://data.cdc.gov/api/views/vqff-ff7g) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/vqff-ff7g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/vqff-ff7g/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | vqff-ff7g |
| Name | Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 4 - Atlanta |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T17:11:22Z |
| Publication Date | 2016-09-14T12:49:57Z |

## Description

Source for 2012 national data: National Occupant Protection Use Survey (NOPUS), 2012. Source for 2014 national data: National Occupant Protection Use Survey (NOPUS), 2014.  Source for 2012 state data: State Observational Survey of Seat Belt Use, 2012. Source for 2014 state data: Seat Belt Use in 2014- Use Rates in the States and Territories

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | series tag     | state      | State | text      | text        |
| Yes      | numeric metric | 2012       | 2012  | percent   | percent     |
| Yes      | numeric metric | 2014       | 2014  | percent   | percent     |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vqff-ff7g d:2012-01-01T00:00:00.000Z t:state=Alabama m:2014=96 m:2012=90

series e:vqff-ff7g d:2012-01-01T00:00:00.000Z t:state=Florida m:2014=89 m:2012=87

series e:vqff-ff7g d:2012-01-01T00:00:00.000Z t:state=Georgia m:2014=97 m:2012=92
```

## Meta Commands

```ls
metric m:2012 p:integer l:2012 t:dataTypeName=percent

metric m:2014 p:integer l:2014 t:dataTypeName=percent

entity e:vqff-ff7g l:"Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 4 - Atlanta" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/vqff-ff7g

property e:vqff-ff7g t:meta.view v:id=vqff-ff7g v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 4 - Atlanta" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:vqff-ff7g t:meta.view.license v:name="Public Domain"

property e:vqff-ff7g t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:vqff-ff7g t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:vqff-ff7g t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state          | 2012 | 2014 | 
| ============== | ==== | ==== | 
| Alabama        | 90   | 96   | 
| Florida        | 87   | 89   | 
| Georgia        | 92   | 97   | 
| Kentucky       | 84   | 86   | 
| Mississippi    | 83   | 78   | 
| North Carolina | 88   | 91   | 
| South Carolina | 91   | 90   | 
| Tennessee      | 84   | 88   | 
| United States  | 86   | 87   | 
```