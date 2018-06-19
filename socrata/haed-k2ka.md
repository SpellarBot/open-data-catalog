# Occupant and Alcohol-Impaired Driving Deaths in States, 2005-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/occupant-and-alcohol-impaired-driving-deaths-in-states-2003-2012-c0a84) |
| Metadata | [Link](https://data.cdc.gov/api/views/haed-k2ka) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/haed-k2ka/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/haed-k2ka/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | haed-k2ka |
| Name | Occupant and Alcohol-Impaired Driving Deaths in States, 2005-2014 |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-15T15:03:24Z |
| Publication Date | 2016-09-26T19:11:57Z |

## Description

Alcohol-Impaired Driving Fatalities 2005-2014; All persons killed in crashes involving a driver with BAC >= .08 g/dL. Occupant Fatalities 2005-2014; All occupants killed where body type = 1-79. Source: National Highway Traffic Safety Administration's (NHTSA) Fatality Analysis Reporting System (FARS), 2005-2013 Final Reports and 2014 Annual Report File

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| Yes      | series tag     | state_not_geocoded              | State                           | text      | text        |
| Yes      | numeric metric | alcohol_impaired_driving_deaths | Alcohol-Impaired Driving Deaths | number    | number      |
| Yes      | numeric metric | occupant_deaths                 | Occupant Deaths                 | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:haed-k2ka d:2005-01-01T00:00:00.000Z t:state_not_geocoded=AL m:alcohol_impaired_driving_deaths=2997 m:occupant_deaths=7754

series e:haed-k2ka d:2005-01-01T00:00:00.000Z t:state_not_geocoded=CA m:alcohol_impaired_driving_deaths=9791 m:occupant_deaths=20733

series e:haed-k2ka d:2005-01-01T00:00:00.000Z t:state_not_geocoded=MA m:alcohol_impaired_driving_deaths=1309 m:occupant_deaths=2465
```

## Meta Commands

```ls
metric m:alcohol_impaired_driving_deaths p:integer l:"Alcohol-Impaired Driving Deaths" d:"Alcohol-Impaired Driving Fatalities 2003-2012; All persons killed in crashes involving a driver with BAC >= .08 g/dL." t:dataTypeName=number

metric m:occupant_deaths p:integer l:"Occupant Deaths" d:"Occupant Fatalities 2003-2012; All occupants killed where body type = 1-79." t:dataTypeName=number

entity e:haed-k2ka l:"Occupant and Alcohol-Impaired Driving Deaths in States, 2005-2014" t:attribution="CDC  National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/haed-k2ka

property e:haed-k2ka t:meta.view v:id=haed-k2ka v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Occupant and Alcohol-Impaired Driving Deaths in States, 2005-2014" v:attribution="CDC  National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:haed-k2ka t:meta.view.license v:name="Public Domain"

property e:haed-k2ka t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:haed-k2ka t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:haed-k2ka t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| state_not_geocoded | alcohol_impaired_driving_deaths | occupant_deaths | 
| ================== | =============================== | =============== | 
| AL                 | 2997                            | 7754            | 
| CA                 | 9791                            | 20733           | 
| MA                 | 1309                            | 2465            | 
| OR                 | 1129                            | 2735            | 
| NH                 | 386                             | 853             | 
| NM                 | 1166                            | 2766            | 
| WA                 | 1799                            | 3542            | 
| MS                 | 2367                            | 6100            | 
| DC                 | 96                              | 130             | 
| MI                 | 2710                            | 6699            | 
```