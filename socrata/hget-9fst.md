# Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 2 - New York

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-drivers-and-front-seat-passengers-wearing-seat-belts-2012-region-2-new-york) |
| Metadata | [Link](https://data.cdc.gov/api/views/hget-9fst) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/hget-9fst/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/hget-9fst/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | hget-9fst |
| Name | Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 2 - New York |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T17:08:41Z |
| Publication Date | 2016-09-14T12:56:15Z |

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
series e:hget-9fst d:2012-01-01T00:00:00.000Z t:state="New Jersey" m:2014=88 m:2012=88

series e:hget-9fst d:2012-01-01T00:00:00.000Z t:state="New York" m:2014=91 m:2012=90

series e:hget-9fst d:2012-01-01T00:00:00.000Z t:state="United States" m:2014=87 m:2012=86
```

## Meta Commands

```ls
metric m:2012 p:integer l:2012 t:dataTypeName=percent

metric m:2014 p:integer l:2014 t:dataTypeName=percent

entity e:hget-9fst l:"Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 2 - New York" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/hget-9fst

property e:hget-9fst t:meta.view v:id=hget-9fst v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 2 - New York" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:hget-9fst t:meta.view.license v:name="Public Domain"

property e:hget-9fst t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:hget-9fst t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:hget-9fst t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | 2012 | 2014 | 
| ============= | ==== | ==== | 
| New Jersey    | 88   | 88   | 
| New York      | 90   | 91   | 
| United States | 86   | 87   | 
```