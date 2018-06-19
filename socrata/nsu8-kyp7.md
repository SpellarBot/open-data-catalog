# CEPS Organization Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ceps-organization-information-76a06) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nsu8-kyp7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nsu8-kyp7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nsu8-kyp7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nsu8-kyp7 |
| Name | CEPS Organization Information |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, law, borough, contact, address, ceps, program |
| Created | 2013-02-12T17:23:39Z |
| Publication Date | 2013-06-21T20:05:02Z |

## Description

Details of Organization Providing (CEPS) Community Education Pathway to Success program

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | organization        | Organization        | text      | text        |
| Yes      | series tag  | neighborhood_served | Neighborhood Served | text      | text        |
| No       |             | site_address        | Site Address        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = site_address
```

## Data Commands

```ls
series e:nsu8-kyp7 d:2013-02-12T09:24:11.000Z t:organization="Settlement Housing Fund - DREAMS/Youth Build" t:neighborhood_served=Brownsville m:row_number.nsu8-kyp7=1

series e:nsu8-kyp7 d:2013-02-12T09:24:11.000Z t:organization="Settlement Housing Fund - DREAMS/Youth Build" t:neighborhood_served=Brownsville m:row_number.nsu8-kyp7=2

series e:nsu8-kyp7 d:2013-02-12T09:24:11.000Z t:organization="Brooklyn Public Library" t:neighborhood_served="East New York" m:row_number.nsu8-kyp7=3
```

## Meta Commands

```ls
metric m:row_number.nsu8-kyp7 p:long l:"Row Number"

entity e:nsu8-kyp7 l:"CEPS Organization Information" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/nsu8-kyp7

property e:nsu8-kyp7 t:meta.view v:id=nsu8-kyp7 v:category="City Government" v:attributionLink=http://www.nyc.gov/html/prob/html/young_men/ceps.shtml v:averageRating=0 v:name="CEPS Organization Information" v:attribution="Department of Probation (DOP)"

property e:nsu8-kyp7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nsu8-kyp7 t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | organization                                     | neighborhood_served | site_address                                   | 
| =========== | ================================================ | =================== | ============================================== | 
| 1360661051  | Settlement Housing Fund - DREAMS/Youth Build     | Brownsville         | 1615 St. John's Place, Brooklyn, NY 11233      | 
| 1360661051  | Settlement Housing Fund - DREAMS/Youth Build     | Brownsville         | 1604 St. John's Place, Brooklyn, NY 11233      | 
| 1360661051  | Brooklyn Public Library                          | East New York       | 665 New Lots Avenue, Brooklyn, NY 11207        | 
| 1360661051  | Union Settlement Association, Inc                | Harlem              | 1775 Third Avenue, New York, NY 10029          | 
| 1360661051  | The Fortune Society                              | Harlem              | 625 West 140th Street, New York, NY 10040      | 
| 1360661051  | Queens Library                                   | Jamaica             | 91-14 Merrick Boulevard, Jamaica, NY 11432     | 
| 1360661051  | Queens Library                                   | Jamaica             | 108-41 Guy Brewer Boulevard, Jamaica, NY 11433 | 
| 1360661051  | Federation Employment and Guidance Services, Inc | South Bronx         | 412-424 East 147th St, 4th Fl, Bronx, NY 10455 | 
| 1360661051  | East Side House, Inc                             | South Bronx         | 201 St. Ann's Avenue, Bronx, NY 10454          | 
| 1360661051  | East Side House, Inc                             | South Bronx         | 337 Alexander Avenue, Bronx, NY 10454          | 
```