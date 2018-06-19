# Carshare Onstreet

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/carshare-onstreet) |
| Metadata | [Link](https://data.sfgov.org/api/views/5cbv-8bw2) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/5cbv-8bw2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/5cbv-8bw2/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 5cbv-8bw2 |
| Name | Carshare Onstreet |
| Category | Transportation |
| Tags | car sharing |
| Created | 2016-03-01T21:53:37Z |
| Publication Date | 2016-04-07T18:53:04Z |

## Description

This dataset  was first created as part of the SFMTA On Street Car Share Pilot Program (approved by the MTA Board in July 2013) to illustrate the location of implemented and planned (various stages) spaces throughout the city.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | space_id              | Space ID              | text      | text        |
| Yes      | series tag     | carshare_organization | Carshare Organization | text      | text        |
| No       |                | address_range         | Address Range         | text      | text        |
| Yes      | series tag     | street                | Street                | text      | text        |
| No       |                | address               | Address               | text      | text        |
| Yes      | series tag     | approval_status       | Approval Status       | text      | text        |
| Yes      | time           | operational_date      | Operational Date      | date      | date        |
| Yes      | series tag     | intersection          | Intersection          | text      | text        |
| Yes      | series tag     | cnn_segment_id        | CNN Segment ID        | text      | number      |
| Yes      | series tag     | cnn_intersection_id   | CNN Intersection ID   | text      | number      |
| Yes      | series tag     | pod_type              | Pod Type              | text      | text        |
| Yes      | series tag     | zipcode               | Zipcode               | text      | number      |
| Yes      | series tag     | neighborhood          | Neighborhood          | text      | text        |
| Yes      | numeric metric | price_zone            | Price Zone            | number    | number      |
| Yes      | series tag     | supervisor_district   | Supervisor District   | text      | text        |
```

## Time Field

```ls
Value = operational_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_range,address
```

## Data Commands

```ls
series e:5cbv-8bw2 d:2015-01-08T00:00:00.000Z t:cnn_intersection_id=24076000 t:intersection="Capp St & 23rd St" t:cnn_segment_id=3679000 t:carshare_organization="City CarShare" t:street="CAPP ST" t:approval_status=approved t:zipcode=94110 t:neighborhood=Mission t:space_id=C010 t:supervisor_district=9 t:pod_type=Double m:price_zone=1

series e:5cbv-8bw2 d:2015-01-29T00:00:00.000Z t:cnn_intersection_id=20236000 t:intersection="Evans Ave & Newhall St" t:cnn_segment_id=5333101 t:carshare_organization=Zipcar t:street="EVANS AVE" t:approval_status=approved t:zipcode=94124 t:neighborhood="India Basin" t:space_id=Z020 t:supervisor_district=10 t:pod_type=Double m:price_zone=3

series e:5cbv-8bw2 d:2014-12-03T00:00:00.000Z t:cnn_intersection_id=27384000 t:intersection="25th Ave & Noriega St" t:cnn_segment_id=1386000 t:carshare_organization=Zipcar t:street="25TH AVE" t:approval_status=approved t:zipcode=94122 t:neighborhood="Outer Sunset" t:space_id=Z007 t:supervisor_district=4 t:pod_type=Double m:price_zone=3
```

## Meta Commands

```ls
metric m:price_zone p:integer l:"Price Zone" t:dataTypeName=number

entity e:5cbv-8bw2 l:"Carshare Onstreet" t:url=https://data.sfgov.org/api/views/5cbv-8bw2

property e:5cbv-8bw2 t:meta.view v:id=5cbv-8bw2 v:category=Transportation v:averageRating=0 v:name="Carshare Onstreet"

property e:5cbv-8bw2 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:5cbv-8bw2 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:5cbv-8bw2 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| space_id | carshare_organization | address_range | street     | address         | approval_status | operational_date | intersection             | cnn_segment_id | cnn_intersection_id | pod_type | zipcode | neighborhood    | price_zone | supervisor_district | 
| ======== | ===================== | ============= | ========== | =============== | =============== | ================ | ======================== | ============== | =================== | ======== | ======= | =============== | ========== | =================== | 
| C010     | City CarShare         | 700 - 799     | CAPP ST    | 780 Capp St     | approved        | 1420675200       | Capp St & 23rd St        | 3679000        | 24076000            | Double   | 94110   | Mission         | 1          | 9                   | 
| Z020     | Zipcar                | 1500 - 1578   | EVANS AVE  | 1530 Evans Ave  | approved        | 1422489600       | Evans Ave & Newhall St   | 5333101        | 20236000            | Double   | 94124   | India Basin     | 3          | 10                  | 
| Z007     | Zipcar                | 1700 - 1799   | 25TH AVE   | 1779 25th Ave   | approved        | 1417564800       | 25th Ave & Noriega St    | 1386000        | 27384000            | Double   | 94122   | Outer Sunset    | 3          | 4                   | 
| C043     | City CarShare         | 2451 - 2499   | CLAY ST    | 2490 Clay St    | approved        | 1317340800       | Clay St & Fillmore St    | 4111000        | 26648000            | Double   | 94115   | Pacific Heights | 1          | 2                   | 
| C069     | City CarShare         | 700 - 799     | ULLOA ST   | 786 Ulloa St    | approved        | 1439164800       | Ulloa St & Claremont Ave | 12783000       | 22875000            | Single   | 94127   | Laguna Honda    | 2          | 7                   | 
| Z153     | Zipcar                |               |            | 207 Brannan St  | approved        | 1435017600       | Brannan St & Delancey St | 3072000        | 23600000            | Double   | 94107   | South Beach     | 1          | 6                   | 
| Z126     | Zipcar                | 1600 - 1699   | REVERE AVE | 1620 Revere Ave | approved        | 1422489600       | Revere Ave & 3rd St      | 10978000       | 20498000            | Double   | 94124   | Bayview         | 3          | 10                  | 
| C054     | City CarShare         | 2301 - 2499   | 03RD ST    | 2475 3rd St     | approved        | 1433721600       | 3rd St & 22nd St         | 190201         | 23555000            | Double   | 94107   | Dogpatch        | 1          | 10                  | 
| C109     | City CarShare         | 1 - 99        | HENRY ST   | 3 Henry St      | approved        | 1420675200       | Henry St & Sanchez St    | 6880000        | 25976000            | Double   | 94114   | Duboce Triangle | 1          | 8                   | 
| G144     | Getaround             | 300 - 399     | SANCHEZ ST | 300 Sanchez St  | approved        | 1418515200       | Sanchez St & 16th St     | 11512000       | 25797000            | Single   | 94114   | Mission Dolores | 1          | 8                   | 
```