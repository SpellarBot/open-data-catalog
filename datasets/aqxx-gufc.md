# E- ZPass Usage Statistics: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/e-zpass-usage-statistics-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/aqxx-gufc) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/aqxx-gufc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/aqxx-gufc/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | aqxx-gufc |
| Name | E- ZPass Usage Statistics: Beginning 2008 |
| Attribution | NYS Thruway Authority |
| Category | Transportation |
| Tags | transportation, nys thruway, thruway, highway, interstate, e-zpass, vehicle classification |
| Created | 2014-04-22T16:36:58Z |
| Publication Date | 2017-01-10T18:10:36Z |

## Description

This data set contains the number and percentage of vehicles that used E-ZPass or Cash by year by plaza on the NYS Thruway beginning in 2008.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | time           | year                                  | Year                                  | number    | number      |
| Yes      | series tag     | entry_plaza                           | Entry Plaza                           | text      | text        |
| Yes      | series tag     | exit_plaza                            | Exit Plaza                            | text      | text        |
| Yes      | numeric metric | number_of_vehicles_that_used_cash     | Number of Vehicles that used Cash     | number    | number      |
| Yes      | numeric metric | number_of_vehicles_that_used_e_zpass  | Number of Vehicles that used E-ZPass  | number    | number      |
| Yes      | series tag     | percent_of_vehicles_that_used_cash    | Percent of Vehicles that used Cash    | text      | text        |
| Yes      | series tag     | percent_of_vehicles_that_used_e_zpass | Percent of Vehicles that used E-ZPass | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:aqxx-gufc d:2012-01-01T00:00:00.000Z t:exit_plaza=15 t:entry_plaza=15 t:percent_of_vehicles_that_used_e_zpass=92% t:percent_of_vehicles_that_used_cash=8% m:number_of_vehicles_that_used_cash=425 m:number_of_vehicles_that_used_e_zpass=4976

series e:aqxx-gufc d:2012-01-01T00:00:00.000Z t:exit_plaza=16 t:entry_plaza=15 t:percent_of_vehicles_that_used_e_zpass=83% t:percent_of_vehicles_that_used_cash=17% m:number_of_vehicles_that_used_cash=1381 m:number_of_vehicles_that_used_e_zpass=6568

series e:aqxx-gufc d:2012-01-01T00:00:00.000Z t:exit_plaza=17 t:entry_plaza=15 t:percent_of_vehicles_that_used_e_zpass=76% t:percent_of_vehicles_that_used_cash=24% m:number_of_vehicles_that_used_cash=693486 m:number_of_vehicles_that_used_e_zpass=2147724
```

## Meta Commands

```ls
metric m:number_of_vehicles_that_used_cash p:integer l:"Number of Vehicles that used Cash" d:"Number of vehicles that entered at the entry plaza and exited at the exit plaza during the year who paid with cash" t:dataTypeName=number

metric m:number_of_vehicles_that_used_e_zpass p:integer l:"Number of Vehicles that used E-ZPass" d:"Number of vehicles that entered at the entry plaza and exited at the exit plaza during the year who paid with E-ZPass" t:dataTypeName=number

entity e:aqxx-gufc l:"E- ZPass Usage Statistics: Beginning 2008" t:attribution="NYS Thruway Authority" t:url=https://data.ny.gov/api/views/aqxx-gufc

property e:aqxx-gufc t:meta.view v:id=aqxx-gufc v:category=Transportation v:averageRating=0 v:name="E- ZPass Usage Statistics: Beginning 2008" v:attribution="NYS Thruway Authority"

property e:aqxx-gufc t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:aqxx-gufc t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:aqxx-gufc t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | entry_plaza | exit_plaza | number_of_vehicles_that_used_cash | number_of_vehicles_that_used_e_zpass | percent_of_vehicles_that_used_cash | percent_of_vehicles_that_used_e_zpass | 
| ==== | =========== | ========== | ================================= | ==================================== | ================================== | ===================================== | 
| 2012 | 15          | 15         | 425                               | 4976                                 | 8%                                 | 92%                                   | 
| 2012 | 15          | 16         | 1381                              | 6568                                 | 17%                                | 83%                                   | 
| 2012 | 15          | 17         | 693486                            | 2147724                              | 24%                                | 76%                                   | 
| 2012 | 15          | 18         | 122952                            | 496919                               | 20%                                | 80%                                   | 
| 2012 | 15          | 19         | 144656                            | 513820                               | 22%                                | 78%                                   | 
| 2012 | 15          | 20         | 51920                             | 193540                               | 21%                                | 79%                                   | 
| 2012 | 15          | 21         | 58506                             | 213156                               | 22%                                | 78%                                   | 
| 2012 | 15          | 21B        | 18194                             | 40580                                | 31%                                | 69%                                   | 
| 2012 | 15          | 22         | 5872                              | 28645                                | 17%                                | 83%                                   | 
| 2012 | 15          | 23         | 204210                            | 556938                               | 27%                                | 73%                                   | 
```