# MDA Animal Control Facilities with 2014Renewals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mda-animal-control-facilities-with-2014renewals-e3096) |
| Metadata | [Link](https://data.maryland.gov/api/views/i5tt-hvfv) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/i5tt-hvfv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/i5tt-hvfv/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | i5tt-hvfv |
| Name | MDA Animal Control Facilities with 2014Renewals |
| Attribution | MD Department of Agriculture |
| Category | Agriculture |
| Tags | animal, shelter, pets, dog, cat |
| Created | 2013-01-17T14:14:18Z |
| Publication Date | 2013-08-12T14:36:53Z |

## Description

This dataset shows all MDA animal control facilities and shelters which are due for license renewal in 2014.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| Yes      | time        | renewal_year       | RENEWAL YEAR       | number    | number      |
| Yes      | series tag  | facility_name      | FACILITY NAME      | text      | text        |
| Yes      | series tag  | county             | COUNTY             | text      | text        |
| Yes      | series tag  | phone_number       | PHONE NUMBER       | phone     | phone       |
| Yes      | series tag  | fax_number         | FAX NUMBER         | phone     | phone       |
| Yes      | series tag  | hours_of_operation | HOURS OF OPERATION | text      | text        |
```

## Time Field

```ls
Value = renewal_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:i5tt-hvfv l:"MDA Animal Control Facilities with 2014Renewals" t:attribution="MD Department of Agriculture" t:url=https://data.maryland.gov/api/views/i5tt-hvfv

property e:i5tt-hvfv t:meta.view v:id=i5tt-hvfv v:category=Agriculture v:attributionLink=http://www.mda.state.md.us v:averageRating=0 v:name="MDA Animal Control Facilities with 2014Renewals" v:attribution="MD Department of Agriculture"

property e:i5tt-hvfv t:meta.view.owner v:id=tpc4-inqc v:screenName="Lisa Stollof" v:displayName="Lisa Stollof"

property e:i5tt-hvfv t:meta.view.tableauthor v:id=tpc4-inqc v:screenName="Lisa Stollof" v:roleName=editor v:displayName="Lisa Stollof"
```

## Top Records

```ls
| renewal_year | facility_name                                 | county         | phone_number       | fax_number         | hours_of_operation                                                                    | 
| ============ | ============================================= | ============== | ================== | ================== | ===================================================================================== | 
| 2014         | BALTIMORE CITY ANIMAL RESCUE & CARE SHELTER   | BALTIMORE CITY | [4103964695, null] | [4107836266, null] | Mon. - Fri. 8:30am - 6:30pm. Sat & Sun 8:30am - 4:30pm.                               | 
| 2014         | CAROLINE COUNTY HUMANE SOCIETY, INC.          | CAROLINE       | [4108201600, null] | [4108201110, null] | Mon-Fri. 8:30 - 4:30pm. Sat. 10am - 3pm.                                              | 
| 2014         | HUMANE SOCIETY OF BALTIMORE COUNTY            | BALTIMORE CO.  | [4108338848, null] | [4108334481, null] | Sun. - Monday 9am - 6pm                                                               | 
| 2014         | DORCHESTER CO SHERIFF'S OFFICE C/O ANIMAL CON | DORCHESTER     | [4102283083, null] | [4102211467, null] | Mon. - Sat., 8am to 4:00pm                                                            | 
| 2014         | ALLEGANY COUNTY ANIMAL CONTROL & SHELTER      | ALLEGANY       | [3017775930, null] | [3017772168, null] | Monday - Friday 8am - 4pm. After hours "EMERGENCY ONLY".                              | 
| 2014         | ANNE ARUNDEL COUNTY ANIMAL CONTROL            | ANNE ARUNDEL   | [4102228900, null] | [4102228925, null] | 10:00am - 3:00pm                                                                      | 
| 2014         | HUMANE SOCIETY OF WASHINGTON COUNTY           | WASHINGTON     | [3017332060, null] | [3017330248, null] | 9:00 a.m. - 6:00 p.m. Seven days a week                                               | 
| 2014         | HUMANE SOCIETY OF CARROLL COUNTY, INC.        | CARROLL        | [4108484810, null] | [4108759736, null] | MON - FRI 8am - 4pm. SAT 9am - 12pm.                                                  | 
| 2014         | FREDERICK COUNTY ANIMAL CONTROL DIVISION      | FREDERICK      | [3016001546, null] | [3016001547, null] | MON, TUES, FRI 8am-5pm. WED & THURS. 8am-8pm & SAT 9AM - 4PM.                         | 
| 2014         | DEFENDERS OF ANIMAL RIGHTS, INC.              | BALTIMORE CO.  | [4105271466, null] | [4105271775, null] | Monday - Friday 8am - 4pm. Saturday 8am - 1pm & Sun 8am - Ipm (closed to the public). | 
```