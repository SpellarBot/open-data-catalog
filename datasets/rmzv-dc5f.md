# Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, All States

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-drivers-and-front-seat-passengers-wearing-seat-belts-2012-all-states) |
| Metadata | [Link](https://data.cdc.gov/api/views/rmzv-dc5f) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/rmzv-dc5f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/rmzv-dc5f/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | rmzv-dc5f |
| Name | Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, All States |
| Attribution | National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-15T18:51:38Z |
| Publication Date | 2016-09-26T19:20:56Z |

## Description

Source for 2012 national data: National Occupant Protection Use Survey (NOPUS), 2012. Source for 2012 state data: State Observational Survey of Seat Belt Use, 2012. Source for 2014 national data: National Highway Traffic Safety Administration's (NHTSA) National Occupant Protection Use Survey (NOPUS), 2014. Source for 2014 state data: National Highway Traffic Safety Administration's (NHTSA) State Observation of Seat Belt Use, 2014

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
series e:rmzv-dc5f d:2012-01-01T00:00:00.000Z t:state=Connecticut m:2014=85 m:2012=87

series e:rmzv-dc5f d:2012-01-01T00:00:00.000Z t:state=Maine m:2014=85 m:2012=84

series e:rmzv-dc5f d:2012-01-01T00:00:00.000Z t:state="District of Columbia" m:2014=93 m:2012=92
```

## Meta Commands

```ls
metric m:2012 p:integer l:2012 t:dataTypeName=percent

metric m:2014 p:integer l:2014 t:dataTypeName=percent

entity e:rmzv-dc5f l:"Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, All States" t:attribution="National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/rmzv-dc5f

property e:rmzv-dc5f t:meta.view v:id=rmzv-dc5f v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety v:averageRating=0 v:name="Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, All States" v:attribution="National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:rmzv-dc5f t:meta.view.license v:name="Public Domain"

property e:rmzv-dc5f t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:rmzv-dc5f t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:rmzv-dc5f t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state                | 2012 | 2014 | 
| ==================== | ==== | ==== | 
| Connecticut          | 87   | 85   | 
| Maine                | 84   | 85   | 
| District of Columbia | 92   | 93   | 
| Florida              | 87   | 89   | 
| Minnesota            | 94   | 95   | 
| Missouri             | 79   | 79   | 
| Oklahoma             | 84   | 86   | 
| West Virginia        | 84   | 88   | 
| Massachusetts        | 73   | 77   | 
| Utah                 | 82   | 83   | 
```