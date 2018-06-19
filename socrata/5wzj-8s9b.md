# City College of San Francisco Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-college-of-san-francisco-facilities-6ce3f) |
| Metadata | [Link](https://data.sfgov.org/api/views/5wzj-8s9b) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/5wzj-8s9b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/5wzj-8s9b/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 5wzj-8s9b |
| Name | City College of San Francisco Facilities |
| Category | Geographic Locations and Boundaries |
| Tags | city college, community college board |
| Created | 2013-12-18T18:30:01Z |
| Publication Date | 2013-12-23T22:01:51Z |

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | facilities     | Facilities     | text      | text        |
| Yes      | series tag  | telephone      | Telephone      | phone     | phone       |
| Yes      | series tag  | street_address | Street Address | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | state          | State          | text      | text        |
| Yes      | series tag  | zip            | Zip            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5wzj-8s9b d:2013-12-23T11:41:16.000Z t:zip=94103 t:state=CA t:street_address="31/33 Gough Street" t:city="San Francisco" t:facilities="Gough Street" m:row_number.5wzj-8s9b=1

series e:5wzj-8s9b d:2013-12-23T11:41:16.000Z t:zip=94109 t:phone_number=415-561-1880 t:state=CA t:street_address="750 Eddy Street" t:city="San Francisco" t:facilities="Civic Center" m:row_number.5wzj-8s9b=2

series e:5wzj-8s9b d:2013-12-23T11:41:16.000Z t:zip=94112 t:phone_number=415-239-3000 t:state=CA t:street_address="50 Phelan Avenue" t:city="San Francisco" t:facilities=Ocean m:row_number.5wzj-8s9b=3
```

## Meta Commands

```ls
metric m:row_number.5wzj-8s9b p:long l:"Row Number"

entity e:5wzj-8s9b l:"City College of San Francisco Facilities" t:url=https://data.sfgov.org/api/views/5wzj-8s9b

property e:5wzj-8s9b t:meta.view v:id=5wzj-8s9b v:category="Geographic Locations and Boundaries" v:attributionLink=http://www.ccsf.edu/NEW/en/our-campuses.html v:averageRating=0 v:name="City College of San Francisco Facilities"

property e:5wzj-8s9b t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:5wzj-8s9b t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:5wzj-8s9b t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | facilities            | telephone            | street_address                                             | city                | state | zip   | 
| =========== | ===================== | ==================== | ========================================================== | =================== | ===== | ===== | 
| 1387798876  | Gough Street          | [null, null]         | 31/33 Gough Street                                         | San Francisco       | CA    | 94103 | 
| 1387798876  | Civic Center          | [415-561-1880, null] | 750 Eddy Street                                            | San Francisco       | CA    | 94109 | 
| 1387798876  | Ocean                 | [415-239-3000, null] | 50 Phelan Avenue                                           | San Francisco       | CA    | 94112 | 
| 1387798876  | Evans                 | [415-550-4440, null] | 1400 Evans Avenue                                          | San Francisco       | CA    | 94124 | 
| 1387798876  | Fort Mason            | [415-561-1840, null] | Laguna Street & Marina Boulevard, Building B               | San Francisco       | CA    | 94123 | 
| 1387798876  | Mission               | [415-920-6000, null] | 1125 Valencia Street                                       | San Francisco       | CA    | 94110 | 
| 1387798876  | Airport               | [650-821-0220, null] | SF International Airport, North Access Road, Building 928  | South San Francisco | CA    | 94128 | 
| 1387798876  | Downtown              | [415-267-6500, null] | 88 4th Street                                              | San Francisco       | CA    | 94103 | 
| 1387798876  | Castro                | [415-621-5499, null] | 450 Castro Street                                          | San Francisco       | CA    | 94114 | 
| 1387798876  | Chinatown/North Beach | [415-395-8600, null] | 808 Kearny Street                                          | San Francisco       | CA    | 94108 | 
```