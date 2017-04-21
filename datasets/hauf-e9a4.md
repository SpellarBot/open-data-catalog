# Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 3 - Philadelphia

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-drivers-and-front-seat-passengers-wearing-seat-belts-2012-region-3-philadelp) |
| Metadata | [Link](https://data.cdc.gov/api/views/hauf-e9a4) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/hauf-e9a4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/hauf-e9a4/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | hauf-e9a4 |
| Name | Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 3 - Philadelphia |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T17:10:07Z |
| Publication Date | 2016-09-14T12:52:17Z |

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
series e:hauf-e9a4 d:2012-01-01T00:00:00.000Z t:state=Delaware m:2014=92 m:2012=88

series e:hauf-e9a4 d:2012-01-01T00:00:00.000Z t:state="District of Columbia" m:2014=93 m:2012=92

series e:hauf-e9a4 d:2012-01-01T00:00:00.000Z t:state=Maryland m:2014=92 m:2012=91
```

## Meta Commands

```ls
metric m:2012 p:integer l:2012 t:dataTypeName=percent

metric m:2014 p:integer l:2014 t:dataTypeName=percent

entity e:hauf-e9a4 l:"Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 3 - Philadelphia" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/hauf-e9a4

property e:hauf-e9a4 t:meta.view v:id=hauf-e9a4 v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 3 - Philadelphia" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:hauf-e9a4 t:meta.view.license v:name="Public Domain"

property e:hauf-e9a4 t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:hauf-e9a4 t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:hauf-e9a4 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state                | 2012 | 2014 | 
| ==================== | ==== | ==== | 
| Delaware             | 88   | 92   | 
| District of Columbia | 92   | 93   | 
| Maryland             | 91   | 92   | 
| Pennsylvania         | 84   | 84   | 
| Virginia             | 78   | 77   | 
| West Virginia        | 84   | 88   | 
| United States        | 86   | 87   | 
```