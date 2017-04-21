# Hartford: Capital Project List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hartford-capital-project-list) |
| Metadata | [Link](https://data.hartford.gov/api/views/ixee-zwvt) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/ixee-zwvt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/ixee-zwvt/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | ixee-zwvt |
| Name | Hartford: Capital Project List |
| Attribution | City of Hartford |
| Category | Financial |
| Created | 2015-01-09T15:28:54Z |
| Publication Date | 2015-08-28T18:21:24Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | project_id          | Project ID          | text      | text        |
| Yes      | series tag  | project_name        | Project Name        | text      | text        |
| No       |             | address             | Address             | text      | text        |
| Yes      | series tag  | project_description | Project Description | text      | text        |
| Yes      | series tag  | current_phase       | Current Phase       | text      | text        |
| Yes      | series tag  | current_phase_type  | Current Phase Type  | text      | text        |
| Yes      | series tag  | project_details_url | Project Details URL | text      | text        |
| Yes      | series tag  | regions             | Regions             | text      | text        |
| No       |             | latitude            | Latitude            | number    | number      |
| No       |             | longitude           | Longitude           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:ixee-zwvt d:2015-08-27T12:35:07.000Z t:project_name="Renovation to Milner School" t:project_id=Q1307 t:project_description="Complete renovation" m:row_number.ixee-zwvt=1

series e:ixee-zwvt d:2015-08-27T12:35:07.000Z t:project_name="John E. Rogers" t:project_id=D1648 t:project_description="Development of African American Cultural Center" m:row_number.ixee-zwvt=2

series e:ixee-zwvt d:2015-08-27T12:35:07.000Z t:project_name="Renovation of Fire Station #11" t:project_id=W1402 t:project_description="Complete renovation" m:row_number.ixee-zwvt=3
```

## Meta Commands

```ls
metric m:row_number.ixee-zwvt p:long l:"Row Number"

entity e:ixee-zwvt l:"Hartford: Capital Project List" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/ixee-zwvt

property e:ixee-zwvt t:meta.view v:id=ixee-zwvt v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Hartford: Capital Project List" v:attribution="City of Hartford"

property e:ixee-zwvt t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ixee-zwvt t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:ixee-zwvt t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| :updated_at | project_id | project_name                                               | address             | project_description                                                          | current_phase | current_phase_type | project_details_url | regions | latitude           | longitude           | 
| =========== | ========== | ========================================================== | =================== | ============================================================================ | ============= | ================== | =================== | ======= | ================== | =================== | 
| 1440678907  | Q1307      | Renovation to Milner School                                | 104 Vine St         | Complete renovation                                                          |               |                    |                     |         | 41.782643999999998 | -72.687591999999995 | 
| 1440678907  | D1648      | John E. Rogers                                             | 1240 Albany Ave     | Development of African American Cultural Center                              |               |                    |                     |         | 41.782387999999997 | -72.696759999999998 | 
| 1440678907  | W1402      | Renovation of Fire Station #11                             | 150 Sisson Ave      | Complete renovation                                                          |               |                    |                     |         | 41.762830000000001 | -72.706816000000003 | 
| 1440678907  | Q9263      | Renovation to Burns School                                 | 195 Putnam St       | Complete renovation                                                          |               |                    |                     |         | 41.760933000000001 | -72.691204999999997 | 
| 1440678907  | Q1602      | Renovation of Martin Luther King School                    | 25 Ridgefield St    | Complete renovation                                                          |               |                    |                     |         | 41.786785000000002 | -72.695881          | 
| 1440678907  | W1301      | Citywide Radio System Improvements                         | 253 High St         | Upgrade the Citys mobile and portable radios                                 |               |                    |                     |         | 41.772392000000004 | -72.678116000000003 | 
| 1440678907  | D1381      | Document Conversion                                        | 260 Constitution PL | Create searchable database of Licensing, Permitting and Inspection documents |               |                    |                     |         | 41.767698000000003 | -72.670755999999997 | 
| 1440678907  | Q9995      | Truck Wash at Public Works Complex                         | 40 Jennings Rd      | Design and contruction of new truck wash                                     |               |                    |                     |         | 41.787309999999998 | -72.654365999999996 | 
| 1440678907  | W1623      | Public Safety-Police Emergency Response Apparatus Facility | 40 Jennings Rd      | Construction of garage building and security house                           |               |                    |                     |         | 41.787309999999998 | -72.654365999999996 | 
| 1440678907  | W1403      | Fire Training Facility                                     | 40 Jennings Rd      | Complete renovation of burn building                                         |               |                    |                     |         | 41.787309999999998 | -72.654365999999996 | 
```