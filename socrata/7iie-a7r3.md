# Jackson Police Department Precincts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jackson-police-department-precincts) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/7iie-a7r3) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/7iie-a7r3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/7iie-a7r3/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | 7iie-a7r3 |
| Name | Jackson Police Department Precincts |
| Attribution | City of Jackson |
| Category | Public Safety |
| Tags | jpd, jackson police department, city of jackson, crime |
| Created | 2016-02-03T19:20:13Z |
| Publication Date | 2016-02-03T19:22:02Z |

## Description

This is a list of each police precinct and its location

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | precinct_office      | Precinct/Office      | text      | text        |
| Yes      | series tag  | phone                | Phone                | text      | text        |
| Yes      | series tag  | boundary_explanation | Boundary Explanation | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7iie-a7r3 d:2016-02-03T11:20:15.000Z t:phone="(601) 960-0002" t:precinct_office="PRECINCT TWO" t:boundary_explanation="Precinct 2 is located in West Jackson.  The boundaries are north to Fortification Street, east to the Pearl River, west to the Clinton City Limits and South to I-20.  Precinct 2 has a total of 24.6 square miles.  The population in Precinct 2 is estimated to be 64,285.  There are 13 beats in Precinct 2." m:row_number.7iie-a7r3=1

series e:7iie-a7r3 d:2016-02-03T11:20:15.000Z t:phone="(601) 960-1359" t:precinct_office=TRAFFIC t:boundary_explanation="The Traffic Division is tasked with the responsibility of enforcing all Federal, State and Local laws that pertain to the operation of motor vehicles on the City streets, Highways and Interstates within the City limits of Jackson, Mississippi.  It is the primary mission and duty of the Traffic Division to enhance and maintain the safety of all motorist who travel within the City of Jackson." m:row_number.7iie-a7r3=2

series e:7iie-a7r3 d:2016-02-03T11:20:15.000Z t:phone="(601) 960-1774" t:precinct_office="ANIMAL CONTROL" t:boundary_explanation="The Animal Control Unit is tasked with enforcing the Federal, State and Local (City) Ordinances that pertain to Animals and Livestock within the City limits of Jackson, Mississippi.  Animal Control was created to hold all irresponsible pet owners accountable while providing humane treatment and care for the animal until a suitable disposition is reached." m:row_number.7iie-a7r3=3
```

## Meta Commands

```ls
metric m:row_number.7iie-a7r3 p:long l:"Row Number"

entity e:7iie-a7r3 l:"Jackson Police Department Precincts" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/7iie-a7r3

property e:7iie-a7r3 t:meta.view v:id=7iie-a7r3 v:category="Public Safety" v:attributionLink="http://www.jacksonms.gov/index.aspx?NID=204" v:averageRating=0 v:name="Jackson Police Department Precincts" v:attribution="City of Jackson"

property e:7iie-a7r3 t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:7iie-a7r3 t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| :updated_at | precinct_office | phone                    | boundary_explanation                                                                                                                                                                                                                                                                                                                                                                                      | 
| =========== | =============== | ======================== | ========================================================================================================================================================================================================================================================================================================================================================================================================= | 
| 1454498415  | PRECINCT TWO    | (601) 960-0002           | Precinct 2 is located in West Jackson.  The boundaries are north to Fortification Street, east to the Pearl River, west to the Clinton City Limits and South to I-20.  Precinct 2 has a total of 24.6 square miles.  The population in Precinct 2 is estimated to be 64,285.  There are 13 beats in Precinct 2.                                                                                           | 
| 1454498415  | TRAFFIC         | (601) 960-1359           | The Traffic Division is tasked with the responsibility of enforcing all Federal, State and Local laws that pertain to the operation of motor vehicles on the City streets, Highways and Interstates within the City limits of Jackson, Mississippi.  It is the primary mission and duty of the Traffic Division to enhance and maintain the safety of all motorist who travel within the City of Jackson. | 
| 1454498415  | ANIMAL CONTROL  | (601) 960-1774           | The Animal Control Unit is tasked with enforcing the Federal, State and Local (City) Ordinances that pertain to Animals and Livestock within the City limits of Jackson, Mississippi.  Animal Control was created to hold all irresponsible pet owners accountable while providing humane treatment and care for the animal until a suitable disposition is reached.                                      | 
| 1454498423  | PRECINCT FOUR   | (601) 960-0004           | Precinct 4 is located in Northeast Jackson.  The boundaries are north to Ridgeland city limits, east to the Pearl River, west to the Illinois Central Railroad and south of Fortification Street.   Precinct 4 covers 22.13 miles.  The total population in Precinct 4 is estimated to be 45,406.  There are 10 Beats in Precinct 4.                                                                      | 
| 1454498423  | PRECINCT ONE    | (601) 960-0001           | Precinct 1 is located in South Jackson. The boundaries are north to I-20, east to the Pearl River, west to Clinton city limits, and south to Byram city limits.  The total population in Precinct 1 is estimated to be 70,000.  There are 10 Beats in Precinct 1.                                                                                                                                         | 
| 1454498423  | PRECINCT THREE  | (601) 960-0003           | Precinct 3 is located in Northwest Jackson.  The boundaries are north of Fortification Street, and the Kansas City Railroad line, west of State Street, east of Clinton city limits and south of Ridgeland city limits.  Precinct 3 covers 32.14 square miles.  The population in Precinct 3 is estimated to be 46,893.                                                                                   | 
```