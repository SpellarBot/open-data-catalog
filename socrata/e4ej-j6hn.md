# Directory of Parks Disability Accessibility Facilities and Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-parks-disability-accessibility-facilities-and-programs-db816) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/e4ej-j6hn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/e4ej-j6hn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/e4ej-j6hn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | e4ej-j6hn |
| Name | Directory of Parks Disability Accessibility Facilities and Programs |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Recreation |
| Tags | jobs and economic mobility, park, parks, nature, recreation, disability, disabled, accessible, handicap, handicap able, healthy living |
| Created | 2011-10-08T19:42:35Z |
| Publication Date | 2013-06-26T17:19:19Z |

## Description

Recreational facilities in New York City Department of Parks & Recreation properties that are accessible to the disabled.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | location    | Location   | text      | text        |
| Yes      | series tag  | type        | Type       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:e4ej-j6hn d:2011-10-08T12:42:40.000Z t:location="Arthur Avenue & East Tremont Avenue" t:name="Tremont Park" t:type="Bocce Courts" m:row_number.e4ej-j6hn=1

series e:e4ej-j6hn d:2011-10-08T12:42:40.000Z t:location="Corner of Balcom Avenue and Dewey Avenue" t:name="Ferry Point Park" t:type="Basketball Courts" m:row_number.e4ej-j6hn=2

series e:e4ej-j6hn d:2011-10-08T12:42:40.000Z t:location="E 153 St. & Grand Concourse" t:name="Franz Sigel Park" t:type="Basketball Courts" m:row_number.e4ej-j6hn=3
```

## Meta Commands

```ls
metric m:row_number.e4ej-j6hn p:long l:"Row Number"

entity e:e4ej-j6hn l:"Directory of Parks Disability Accessibility Facilities and Programs" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/e4ej-j6hn

property e:e4ej-j6hn t:meta.view v:id=e4ej-j6hn v:category=Recreation v:averageRating=100 v:name="Directory of Parks Disability Accessibility Facilities and Programs" v:attribution="Department of Parks and Recreation (DPR)"

property e:e4ej-j6hn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:e4ej-j6hn t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | name                | location                                           | type              | 
| =========== | =================== | ================================================== | ================= | 
| 1318077760  | Tremont Park        | Arthur Avenue & East Tremont Avenue                | Bocce Courts      | 
| 1318077760  | Ferry Point Park    | Corner of Balcom Avenue and Dewey Avenue           | Basketball Courts | 
| 1318077760  | Franz Sigel Park    | E 153 St. & Grand Concourse                        | Basketball Courts | 
| 1318077760  | Gun Hill Playground | Holland Ave. & Magenta St.                         | Basketball Courts | 
| 1318077760  | Macombs             | E 158th St. & Ruppert Plaza                        | Basketball Courts | 
| 1318077760  | Sound View Park     | Bronx River & Lafayette Aves.                      | Basketball Courts | 
| 1318077760  | St. James Park      | E 193 St. & Jerome Ave.                            | Basketball Courts | 
| 1318077760  | Alex Lindower Park  | Mill & Strickland Aves.                            | Basketball Courts | 
| 1318077760  | Bensonhurst Park    | Gravesend Bay, 21 Ave., Cropsey Ave. and Bay Pkwy. | Basketball Courts | 
| 1318077760  | Dyker Beach Park    | Shore Pkwy., 86 St. and 7 to 14 Aves.              | Basketball Courts | 
```