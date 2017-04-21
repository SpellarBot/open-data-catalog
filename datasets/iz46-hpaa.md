# Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 8 - Denver

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-drivers-and-front-seat-passengers-wearing-seat-belts-2012-region-8-denver) |
| Metadata | [Link](https://data.cdc.gov/api/views/iz46-hpaa) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/iz46-hpaa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/iz46-hpaa/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | iz46-hpaa |
| Name | Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 8 - Denver |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T17:18:16Z |
| Publication Date | 2016-09-14T12:41:50Z |

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
series e:iz46-hpaa d:2012-01-01T00:00:00.000Z t:state=Colorado m:2014=82 m:2012=81

series e:iz46-hpaa d:2012-01-01T00:00:00.000Z t:state=Montana m:2014=74 m:2012=76

series e:iz46-hpaa d:2012-01-01T00:00:00.000Z t:state="North Dakota" m:2014=81 m:2012=81
```

## Meta Commands

```ls
metric m:2012 p:integer l:2012 t:dataTypeName=percent

metric m:2014 p:integer l:2014 t:dataTypeName=percent

entity e:iz46-hpaa l:"Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 8 - Denver" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/iz46-hpaa

property e:iz46-hpaa t:meta.view v:id=iz46-hpaa v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 8 - Denver" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:iz46-hpaa t:meta.view.license v:name="Public Domain"

property e:iz46-hpaa t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:iz46-hpaa t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:iz46-hpaa t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | 2012 | 2014 | 
| ============= | ==== | ==== | 
| Colorado      | 81   | 82   | 
| Montana       | 76   | 74   | 
| North Dakota  | 81   | 81   | 
| South Dakota  | 67   | 69   | 
| Utah          | 82   | 83   | 
| Wyoming       | 77   | 79   | 
| United States | 86   | 87   | 
```