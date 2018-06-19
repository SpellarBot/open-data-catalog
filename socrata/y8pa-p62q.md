# Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 7 - Kansas City

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-drivers-and-front-seat-passengers-wearing-seat-belts-2012-region-7-kansas-ci) |
| Metadata | [Link](https://data.cdc.gov/api/views/y8pa-p62q) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/y8pa-p62q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/y8pa-p62q/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | y8pa-p62q |
| Name | Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 7 - Kansas City |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T17:17:08Z |
| Publication Date | 2016-09-14T12:43:27Z |

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
series e:y8pa-p62q d:2012-01-01T00:00:00.000Z t:state=Iowa m:2014=93 m:2012=92

series e:y8pa-p62q d:2012-01-01T00:00:00.000Z t:state=Kansas m:2014=86 m:2012=80

series e:y8pa-p62q d:2012-01-01T00:00:00.000Z t:state=Missouri m:2014=79 m:2012=79
```

## Meta Commands

```ls
metric m:2012 p:integer l:2012 t:dataTypeName=percent

metric m:2014 p:integer l:2014 t:dataTypeName=percent

entity e:y8pa-p62q l:"Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 7 - Kansas City" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/y8pa-p62q

property e:y8pa-p62q t:meta.view v:id=y8pa-p62q v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Percentage of Drivers and Front Seat Passengers Wearing Seat Belts, 2012 & 2014, Region 7 - Kansas City" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:y8pa-p62q t:meta.view.license v:name="Public Domain"

property e:y8pa-p62q t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:y8pa-p62q t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:y8pa-p62q t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state         | 2012 | 2014 | 
| ============= | ==== | ==== | 
| Iowa          | 92   | 93   | 
| Kansas        | 80   | 86   | 
| Missouri      | 79   | 79   | 
| Nebraska      | 79   | 79   | 
| United States | 86   | 87   | 
```