# Active Construction Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-construction-projects) |
| Metadata | [Link](https://data.ny.gov/api/views/ekci-x6aq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ekci-x6aq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ekci-x6aq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ekci-x6aq |
| Name | Active Construction Projects |
| Attribution | DASNY (Dormitory Authority State of New York) |
| Category | Economic Development |
| Tags | nys county, nys clients, nys institutions, project budget, construction start date, construction complete date |
| Created | 2014-11-04T22:16:37Z |
| Publication Date | 2016-07-19T22:01:03Z |

## Description

Report includes a snapshot of active projects where DASNYdelivers some level of project management oversight.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                                     | Data Type     | Render Type   |
| ======== | ============== | ============================ | ======================================== | ============= | ============= |
| Yes      | time           | snapshotdate                 | Snapshot Date                            | calendar_date | calendar_date |
| Yes      | series tag     | institution                  | Institution                              | text          | text          |
| Yes      | numeric metric | projectid                    | Project ID                               | number        | number        |
| Yes      | series tag     | description                  | Description                              | text          | text          |
| Yes      | series tag     | county                       | County                                   | text          | text          |
| Yes      | numeric metric | project_budget               | Project Budget                           | money         | money         |
| No       |                | construction_start_date      | Construction Start Date                  | text          | text          |
| No       |                | construction_completion_date | Construction Completion Date (Estimated) | text          | text          |
| Yes      | series tag     | architect                    | Architect                                | text          | text          |
| Yes      | series tag     | construction_manager         | Construction Manager                     | text          | text          |
```

## Time Field

```ls
Value = snapshotdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = construction_completion_date,construction_start_date
```

## Data Commands

```ls
series e:ekci-x6aq d:2016-04-16T00:00:00.000Z t:architect="Robert A.M. Stern Architects LLP" t:county=Bronx t:description="North Instructional Building" t:construction_manager="Robert A.M. Stern Architects" t:institution="Bronx Community College" m:projectid=2384209999 m:project_budget=102300000

series e:ekci-x6aq d:2016-04-16T00:00:00.000Z t:county="New York" t:description="NAC Central Chiller Upgrade" t:institution="City College of New York" m:projectid=2437609999 m:project_budget=33795658

series e:ekci-x6aq d:2016-04-16T00:00:00.000Z t:architect="Genesys Engineering P.C." t:county="New York" t:description="Upgrade Mechanical Systems" t:institution="City College of New York" m:projectid=2521709999 m:project_budget=62337829
```

## Meta Commands

```ls
metric m:projectid p:long l:"Project ID" d:"Unique ID assigned to each DASNY construction project." t:dataTypeName=number

metric m:project_budget p:double l:"Project Budget" d:"The current estimate for the entire construction project." t:dataTypeName=money

entity e:ekci-x6aq l:"Active Construction Projects" t:attribution="DASNY (Dormitory Authority State of New York)" t:url=https://data.ny.gov/api/views/ekci-x6aq

property e:ekci-x6aq t:meta.view v:id=ekci-x6aq v:category="Economic Development" v:averageRating=0 v:name="Active Construction Projects" v:attribution="DASNY (Dormitory Authority State of New York)"

property e:ekci-x6aq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ekci-x6aq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ekci-x6aq t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| snapshotdate        | institution                     | projectid  | description                          | county   | project_budget | construction_start_date | construction_completion_date | architect                          | construction_manager                | 
| =================== | =============================== | ========== | ==================================== | ======== | ============== | ======================= | ============================ | ================================== | =================================== | 
| 2016-04-16T00:00:00 | Bronx Community College         | 2384209999 | North Instructional Building         | Bronx    | 102300000.00   | 4/1/2009                | 07/01/2016                   | Robert A.M. Stern Architects LLP   | Robert A.M. Stern Architects        | 
| 2016-04-16T00:00:00 | City College of New York        | 2437609999 | NAC Central Chiller Upgrade          | New York | 33795658.00    | 11/1/2004               | 07/01/2016                   |                                    |                                     | 
| 2016-04-16T00:00:00 | City College of New York        | 2521709999 | Upgrade Mechanical Systems           | New York | 62337829.00    | 7/1/2005                | 12/1/2017                    | Genesys Engineering P.C.           |                                     | 
| 2016-04-16T00:00:00 | Bernard Fineson DDSO            | 2530009999 | Construction of New Campus Buildings | Queens   | 110764556.00   | 2/1/2006                | 06/01/2016                   | Werfel & Associates                | LiRo Program and Construction Mgmt. | 
| 2016-04-16T00:00:00 | Gouverneur Hospital             | 2548909999 | Major Modernization Project          | New York | 246799994.00   | 5/1/2008                | 12/01/2016                   | The Hillier Group Architecture, NY | Hunter Roberts Construction Group   | 
| 2016-04-16T00:00:00 | Bronx Civil/Civil Supreme Court | 2589409999 | Interior Renovations                 | Bronx    | 38883998.00    | 7/1/2009                | 08/01/2016                   | Mitchell/Giurgola Architects       | LiRo Program and Construction Mgmt. | 
| 2016-04-16T00:00:00 | Bronx Family/ Criminal Court    | 2589509999 | Interior Renovations                 | Bronx    | 60491350.00    | 3/1/2011                | 07/01/2016                   | Ehrenkrantz Eckstut & Kuhn         | STV Construction, Inc.              | 
| 2016-04-16T00:00:00 | City College of New York        | 2609709999 | NAC Central Plant, Phase 2           | New York | 25000000.00    | 10/1/2012               | 08/01/2016                   | DMJM+Harris Inc.                   |                                     | 
| 2016-04-16T00:00:00 | OCA Training Academy            | 2621309999 | Training Facility - Kings County     | Kings    | 51999999.00    | 4/1/2012                | 03/01/2017                   | Mitchell/Giurgola Architects LLP   | Gilbane Building Company            | 
| 2016-04-16T00:00:00 | Herbert H. Lehman College       | 2623809999 | Utilities Plant Expansion Phase 1    | Bronx    | 44791000.00    | 9/1/2014                | 10/01/2016                   | DMJM+Harris Inc.                   |                                     | 
```