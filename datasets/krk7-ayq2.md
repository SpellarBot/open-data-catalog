# Posted Street Sweeping Routes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/posted-street-sweeping-routes-0bac8) |
| Metadata | [Link](https://data.lacity.org/api/views/krk7-ayq2) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/krk7-ayq2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/krk7-ayq2/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | krk7-ayq2 |
| Name | Posted Street Sweeping Routes |
| Attribution | Bureau of Street Services |
| Category | A Livable and Sustainable City |
| Tags | street, services, sweeping, routes, route, cd, council, district, maintenance, area, boundary, boundaries, parking |
| Created | 2014-05-08T17:28:06Z |
| Publication Date | 2014-05-28T23:05:34Z |

## Description

Motor sweeping program: route #s, boundaries and times for posted routes only. Maps are available as downloadable PDFs under the Attachments section of the About tab.

## Columns

```ls
| Included | Schema Type | Field Name  | Name             | Data Type | Render Type |
| ======== | =========== | =========== | ================ | ========= | =========== |
| No       | time        | :updated_at | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | route_no    | Route No         | text      | text        |
| No       |             | cd          | Council District | text      | text        |
| No       |             | time_start  | Time Start       | text      | text        |
| No       |             | time_end    | Time End         | text      | text        |
| Yes      | series tag  | boundaries  | Boundaries       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = cd,time_start,time_end
```

## Data Commands

```ls
series e:krk7-ayq2 d:2014-05-28T15:31:48.000Z t:boundaries="Chandler Bl. to Ventura Fwy / Colfax Av. to Laurel Cyn. Bl." t:route_no="* 17P100" m:row_number.krk7-ayq2=1

series e:krk7-ayq2 d:2014-05-28T15:31:48.000Z t:boundaries="Chandler Bl. to Ventura Fwy / Colfax Av. to Laurel Cyn. Bl." t:route_no=*17P100 m:row_number.krk7-ayq2=2

series e:krk7-ayq2 d:2014-05-28T15:31:48.000Z t:boundaries="La Brea Ave to Arlington Ave- Santa Monica Fwy to Adams Blvd" t:route_no="10P136 Th" m:row_number.krk7-ayq2=3
```

## Meta Commands

```ls
metric m:row_number.krk7-ayq2 p:long l:"Row Number"

entity e:krk7-ayq2 l:"Posted Street Sweeping Routes" t:attribution="Bureau of Street Services" t:url=https://data.lacity.org/api/views/krk7-ayq2

property e:krk7-ayq2 t:meta.view v:id=krk7-ayq2 v:category="A Livable and Sustainable City" v:averageRating=60 v:name="Posted Street Sweeping Routes" v:attribution="Bureau of Street Services"

property e:krk7-ayq2 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:krk7-ayq2 t:meta.view.owner v:id=awhe-qmys v:screenName=CJ v:displayName=CJ

property e:krk7-ayq2 t:meta.view.tableauthor v:id=awhe-qmys v:screenName=CJ v:displayName=CJ
```

## Top Records

```ls
| :updated_at | route_no  | cd | time_start | time_end | boundaries                                                    | 
| =========== | ========= | == | ========== | ======== | ============================================================= | 
| 1401291108  | * 17P100  | 2  | 10:00 AM   | 12:00 PM | Chandler Bl. to Ventura Fwy / Colfax Av. to Laurel Cyn. Bl.   | 
| 1401291108  | *17P100   | 2  | 10:00 AM   | 12:00 PM | Chandler Bl. to Ventura Fwy / Colfax Av. to Laurel Cyn. Bl.   | 
| 1401291108  | 10P136 Th | 10 | 8:00 AM    | 10:00 AM | La Brea Ave to Arlington Ave- Santa Monica Fwy to Adams Blvd  | 
| 1401291108  | 10P136 W  | 10 | 8:00 AM    | 10:00 AM | La Brea Ave to Arlington Ave -Santa Monica Fwy to Adams Blvd  | 
| 1401291108  | 10P137 M  | 10 | 9:00 AM    | 11:00 AM | Adams Blvd to Jefferson Blvd - La Cienega Blvd to Hauser Blvd | 
| 1401291108  | 10P137 Tu | 10 | 9:00 AM    | 11:00 AM | Adams Blvd to Jefferson Blvd - La Cienega Blvd to Hauser Blvd | 
| 1401291108  | 10P138 M  | 10 | 10:00 AM   | 12:00 PM | Adams Blvd to Jefferson Blvd - Hauser Blvd to La Brea Ave     | 
| 1401291108  | 10P138 Tu | 10 | 10:00 AM   | 12:00 PM | Adams Blvd to Jefferson Blvd - Hauser Blvd to La Brea Ave     | 
| 1401291108  | 10P139 M  | 10 | 12:00 PM   | 2:00 PM  | Jefferson Blvd to Coliseum St- Hauser Ave to Holdrege Ave     | 
| 1401291108  | 10P139 Tu | 10 | 12:00 PM   | 2:00 PM  | Jefferson Blvd to Coliseum St- Hauser Ave to Holdrege Ave     | 
```