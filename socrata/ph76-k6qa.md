# Drinking Fountains

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/drinking-fountains) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ph76-k6qa) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ph76-k6qa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ph76-k6qa/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ph76-k6qa |
| Name | Drinking Fountains |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Environment |
| Tags | parks, fountains, water, dpr, drinking |
| Created | 2016-08-23T21:25:36Z |
| Publication Date | 2016-08-23T21:31:32Z |

## Description

This data contains the record of drinking fountain counts in NYC Parks sites. Drinking fountain counts are observed and recorded during park inspections at the site level. A site is a discreet area that is inspected/maintained, that may be equivalent to an entire small property, or a subdivision of a larger property. This data release includes drinking fountain counts from inspections through 8/3/16.

To obtain spatial data for each property refer to the Parks Properties data also posted on the Open Data Portal. Since that data set contains spatial information at the park property level, drinking fountain data will have to be aggregated to the park property level (Property Number) as well.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | property_name      | Property Name      | text      | text        |
| Yes      | series tag     | property_number    | Property Number    | text      | text        |
| Yes      | series tag     | site_name          | Site Name          | text      | text        |
| Yes      | series tag     | site_id            | Site ID            | text      | text        |
| Yes      | series tag     | borough            | Borough            | text      | text        |
| Yes      | series tag     | community_board    | Community Board    | text      | text        |
| Yes      | numeric metric | drinking_fountains | Drinking Fountains | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ph76-k6qa d:2016-08-23T21:25:47.000Z t:property_number=B001 t:property_name="AMERICAN PLAYGROUND" t:site_id=B001 t:borough=B t:community_board=301 t:site_name="American Playground" m:drinking_fountains=1

series e:ph76-k6qa d:2016-08-23T21:25:47.000Z t:property_number=B002 t:property_name="AMERSFORT PARK" t:site_id=B002 t:borough=B t:community_board=318 t:site_name="Amersfort Park" m:drinking_fountains=2

series e:ph76-k6qa d:2016-08-23T21:25:47.000Z t:property_number=B007 t:property_name="BENSONHURST PARK" t:site_id=B007 t:borough=B t:community_board=311 t:site_name="Bensonhurst Park" m:drinking_fountains=5
```

## Meta Commands

```ls
metric m:drinking_fountains p:integer l:"Drinking Fountains" t:dataTypeName=number

entity e:ph76-k6qa l:"Drinking Fountains" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/ph76-k6qa

property e:ph76-k6qa t:meta.view v:id=ph76-k6qa v:category=Environment v:averageRating=0 v:name="Drinking Fountains" v:attribution="Department of Parks and Recreation (DPR)"

property e:ph76-k6qa t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ph76-k6qa t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | property_name                  | property_number | site_name                      | site_id | borough | community_board | drinking_fountains | 
| =========== | ============================== | =============== | ============================== | ======= | ======= | =============== | ================== | 
| 1471987547  | AMERICAN PLAYGROUND            | B001            | American Playground            | B001    | B       | 301             | 1                  | 
| 1471987547  | AMERSFORT PARK                 | B002            | Amersfort Park                 | B002    | B       | 318             | 2                  | 
| 1471987547  | BENSONHURST PARK               | B007            | Bensonhurst Park               | B007    | B       | 311             | 5                  | 
| 1471987547  | BENSONHURST PARK               | B007            | Bensonhurst Park               | B007-01 | B       | 311             | 1                  | 
| 1471987547  | BETSY HEAD PARK                | B008            | Betsy Head Park                | B008    | B       | 316             | 3                  | 
| 1471987547  | BETSY HEAD MEMORIAL PLAYGROUND | B008            | Betsy Head Memorial Playground | B008-03 | B       | 316             | 4                  | 
| 1471987547  | BROWER PARK                    | B012            | Brower Park                    | B012    | B       | 308             | 1                  | 
| 1471987547  | BROWER PARK                    | B012            | Brower Park                    | B012-03 | B       | 308             | 1                  | 
| 1471987547  | MARIA HERNANDEZ PARK           | B016            | Maria Hernandez Park           | B016    | B       | 304             | 4                  | 
| 1471987547  | MARIA HERNANDEZ PARK           | B016            | Maria Hernandez Park           | B016-01 | B       | 304             | 1                  | 
```