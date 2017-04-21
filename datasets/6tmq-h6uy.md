# Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 1 - Boston

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-drivers-and-front-seat-passengers-wearing-seat-belts-2012-region-1-boston-bad46) |
| Metadata | [Link](https://data.cdc.gov/api/views/6tmq-h6uy) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/6tmq-h6uy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/6tmq-h6uy/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 6tmq-h6uy |
| Name | Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 1 - Boston |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T17:07:26Z |
| Publication Date | 2016-09-14T12:58:06Z |

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
series e:6tmq-h6uy d:2012-01-01T00:00:00.000Z t:state=Connecticut m:2014=85 m:2012=87

series e:6tmq-h6uy d:2012-01-01T00:00:00.000Z t:state=Maine m:2014=85 m:2012=84

series e:6tmq-h6uy d:2012-01-01T00:00:00.000Z t:state=Massachusetts m:2014=77 m:2012=73
```

## Meta Commands

```ls
metric m:2012 p:integer l:2012 t:dataTypeName=percent

metric m:2014 p:integer l:2014 t:dataTypeName=percent

entity e:6tmq-h6uy l:"Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 1 - Boston" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/6tmq-h6uy

property e:6tmq-h6uy t:meta.view v:id=6tmq-h6uy v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 1 - Boston" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:6tmq-h6uy t:meta.view.license v:name="Public Domain"

property e:6tmq-h6uy t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:6tmq-h6uy t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:6tmq-h6uy t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | 2012 | 2014 | 
| ============= | ==== | ==== | 
| Connecticut   | 87   | 85   | 
| Maine         | 84   | 85   | 
| Massachusetts | 73   | 77   | 
| New Hampshire | 69   | 70   | 
| Rhode Island  | 78   | 87   | 
| Vermont       | 84   | 84   | 
| United States | 86   | 87   | 
```