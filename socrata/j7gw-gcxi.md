# Directory Of Awarded Construction Contracts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-awarded-construction-contracts-5943b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/j7gw-gcxi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/j7gw-gcxi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/j7gw-gcxi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | j7gw-gcxi |
| Name | Directory Of Awarded Construction Contracts |
| Attribution | Department of Design and Construction (DDC) |
| Category | Housing & Development |
| Tags | department of design and construction, ddc, firm |
| Created | 2013-03-06T13:00:16Z |
| Publication Date | 2013-06-21T20:48:33Z |

## Description

This table displays the construction contracts that Department of Design and Construction has recently awarded to selected firms along with its value.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name           | Data Type | Render Type |
| ======== | ============== | ============= | ============== | ========= | =========== |
| No       | time           | :updated_at   | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | pin           | PIN            | text      | text        |
| Yes      | series tag     | description   | DESCRIPTION    | text      | text        |
| Yes      | series tag     | selected_firm | SELECTED FIRM  | text      | text        |
| Yes      | numeric metric | value         | $Value         | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:j7gw-gcxi d:2013-03-06T05:00:17.000Z t:pin=8502013PD0002C t:description="NYPD FIRE SUPPRESSION SYSTEM INSTALLATIONS AT EXISTING FUELING STATIONS AT 23 PRECINCTS - MANHATTAN, BRONX, BROOKLYN AND QUEENS" t:selected_firm="GEMSTAR CONSTRUCTION CORP" m:value=2798960

series e:j7gw-gcxi d:2013-03-06T05:00:17.000Z t:pin=8502012SE0030C t:description="RECONSTRUCTION OF COLLAPSED OR OTHERWISE DEFECTIVE STORM, SANITARY OR COMBINED VITRIFIED CLAY PIPE SEWERS IN VARIOUS LOCATIONS - BOROUGH OF QUEENS" t:selected_firm="MASPETH SUPPLY CO, LLC" m:value=5728442.71

series e:j7gw-gcxi d:2013-03-06T05:00:17.000Z t:pin=8502013HW0002C t:description="RECONSTRUCTION OF ASTOR PLACE/COOPER SQUARE - BOROUGH OF MANHATTAN" t:selected_firm="TRIUMPH CONSTRUCTION CORP." m:value=15754866.59
```

## Meta Commands

```ls
metric m:value p:double l:$Value t:dataTypeName=money

entity e:j7gw-gcxi l:"Directory Of Awarded Construction Contracts" t:attribution="Department of Design and Construction (DDC)" t:url=https://data.cityofnewyork.us/api/views/j7gw-gcxi

property e:j7gw-gcxi t:meta.view v:id=j7gw-gcxi v:category="Housing & Development" v:attributionLink=http://ddcftp.nyc.gov/inet/html/contrawd.asp v:averageRating=0 v:name="Directory Of Awarded Construction Contracts" v:attribution="Department of Design and Construction (DDC)"

property e:j7gw-gcxi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:j7gw-gcxi t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | pin            | description                                                                                                                                        | selected_firm                   | value       | 
| =========== | ============== | ================================================================================================================================================== | =============================== | =========== | 
| 1362546017  | 8502013PD0002C | NYPD FIRE SUPPRESSION SYSTEM INSTALLATIONS AT EXISTING FUELING STATIONS AT 23 PRECINCTS - MANHATTAN, BRONX, BROOKLYN AND QUEENS                    | GEMSTAR CONSTRUCTION CORP       | 2798960.00  | 
| 1362546017  | 8502012SE0030C | RECONSTRUCTION OF COLLAPSED OR OTHERWISE DEFECTIVE STORM, SANITARY OR COMBINED VITRIFIED CLAY PIPE SEWERS IN VARIOUS LOCATIONS - BOROUGH OF QUEENS | MASPETH SUPPLY CO, LLC          | 5728442.71  | 
| 1362546017  | 8502013HW0002C | RECONSTRUCTION OF ASTOR PLACE/COOPER SQUARE - BOROUGH OF MANHATTAN                                                                                 | TRIUMPH CONSTRUCTION CORP.      | 15754866.59 | 
| 1362546017  | 8502012SE0022C | RECONSTRUCTION OF COLLAPSED OR OTHERWISE DEFECTIVE STORM, SANITARY AND COMBINED SEWERS, ETC. ON AN EMERGENCY BASIS - CITYWIDE                      | DELANEY ASSOCIATES, LP          | 16500000.00 | 
| 1362546017  | 8502013TA0004F | RECONSTRUCTION OF TIMES AND DUFFY SQUARES - BOROUGH OF MANHATTAN                                                                                   | NEW YORK CITY TRANSIT AUTHORITY | 914000.00   | 
| 1362546017  | 8502012HW0049P | RESIDENT ENGINEERING INSPECTION SERVICES FOR THE RECONSTRUCTION OF TIMES SQUARE AREA                                                               | LIRO ENGINEERS, INC.            | 6550154.00  | 
| 1362546017  | 8502012RQ0004P | REQUIREMENTS CONTRACT FOR TOPOGRAPHICAL SURVEYING SERVICES FOR VARIOUS INFRASTRUCTURE PROJECTS, BOROUGH OF MANHATTAN                               | NAIK CONSULTING GROUP, P.C.     | 1500000.00  | 
| 1362546017  | 8502009VP0014Y | HOLDING CODE FOR ARCH & ENGINEERING REQUIREMENT CONTRACTS                                                                                          | GRAY ORGANSCHI ARCHITECTURE     | 4000000.00  | 
| 1362546017  | 8502013TR0002C | WEST 59TH STREET MARINE TRANSFER STATION SCALES AND INTERSECTION REPAIR, PROJECT 1 - BOROUGH OF MANHATTAN                                          | WEEKS MARINE, INC.              | 11050000.00 | 
```