# NYC City Hall Library Catalog

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-city-hall-library-catalog-90dc1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gysc-yn4h) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gysc-yn4h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gysc-yn4h/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gysc-yn4h |
| Name | NYC City Hall Library Catalog |
| Attribution | Department of Records and Information Services (RECORDS) |
| Category | Recreation |
| Tags | library, catalog, catalogue, report, study, studies, depository, records, publication |
| Created | 2011-10-08T22:47:14Z |
| Publication Date | 2013-06-21T20:26:33Z |

## Description

The City Hall Library is New York City's official depository for all agency published reports and studies. More info can be found at http://nyc.gov/html/records/html/about/chlibrary.shtml

## Columns

```ls
| Included | Schema Type | Field Name                                                                                                                               | Name                                                                                                                                     | Data Type | Render Type |
| ======== | =========== | ======================================================================================================================================== | ======================================================================================================================================== | ========= | =========== |
| No       | time        | :updated_at                                                                                                                              | updated_at                                                                                                                               | meta_data | meta_data   |
| No       |             | corporate_name_subordinate_unit_title_remainder_of_title_remainder_of_title_page_date_of_publication_geographic_name_general_subdivision | Corporate Name#Subordinate Unit#Title#Remainder Of Title#Remainder OF Title Page#Date Of Publication#Geographic Name#General Subdivision | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = corporate_name_subordinate_unit_title_remainder_of_title_remainder_of_title_page_date_of_publication_geographic_name_general_subdivision
```

## Data Commands

```ls
series e:gysc-yn4h d:2011-10-08T15:47:15.000Z m:row_number.gysc-yn4h=1

series e:gysc-yn4h d:2011-10-08T15:47:15.000Z m:row_number.gysc-yn4h=2

series e:gysc-yn4h d:2011-10-08T15:47:15.000Z m:row_number.gysc-yn4h=3
```

## Meta Commands

```ls
metric m:row_number.gysc-yn4h p:long l:"Row Number"

entity e:gysc-yn4h l:"NYC City Hall Library Catalog" t:attribution="Department of Records and Information Services (RECORDS)" t:url=https://data.cityofnewyork.us/api/views/gysc-yn4h

property e:gysc-yn4h t:meta.view v:id=gysc-yn4h v:category=Recreation v:averageRating=0 v:name="NYC City Hall Library Catalog" v:attribution="Department of Records and Information Services (RECORDS)"

property e:gysc-yn4h t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gysc-yn4h t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | corporate_name_subordinate_unit_title_remainder_of_title_remainder_of_title_page_date_of_publication_geographic_name_general_subdivision                                                                                                                                                                      | 
| =========== | ============================================================================================================================================================================================================================================================================================================= | 
| 1318088835  | New York City.#Laws, etc.#The charter of the City of New York :#with notes thereon, also a treatise on the powers and duties of the Mayor, Aldermen and Assistant Aldermen /#prepared at the request of the Common Council, by James Kent.#1851.##                                                            | 
| 1318088835  | New York City.#Laws, etc.#The charter of the City of New York :#with notes thereon, also a treatise on the powers and duties of the Mayor, Aldermen and Assistant Aldermen /#prepared at the request of the Common Council, by James Kent.#1854.##                                                            | 
| 1318088835  | New York City.#Laws, etc.#An act to reduce several laws :#relative particularly to the City of New York, into one act, passed April 9, 1813.##1813.##                                                                                                                                                         | 
| 1318088835  | New York City.#Laws, etc.#Journal of the convention in relation, to the Charter of the City of New York :#begun and held at the City Hall, in the City of New York, on the sixth day of July, 1846.##1846.##                                                                                                  | 
| 1318088835  | New York City.#Laws, etc.#An act to reorganize the local government of the City of New York :#passed April 30, 1873, as amended; with an appendix containing the supplementary acts ...##1873.##                                                                                                              | 
| 1318088835  | New York State.#Laws, etc.#An act to consolidate into one act and to declare the special and local laws affecting public interest in the City of New York :#being Chapter 410 of the Laws of 1882, with supplementary act, Chapter 276, Laws of 1883.##1883.##                                                | 
| 1318088835  | New York City.#Laws, etc.#The Greater New York Charter, constituting Chapter 378 of the Laws of 1897 :#also the supplementary acts and constitutional amendments, with explanatory preface /#by Andrew H. Green.#1897.##                                                                                      | 
| 1318088835  | ##The Greater New York Charter :#submitted to the legislature of the State of New York on February 20, 1897, by the commission appointed & pursuant to Chapter 488 of the Laws of 1896.####                                                                                                                   | 
| 1318088835  | New York City.#Laws, etc.#The New York City Consolidation Act, as in force in 1891 ... and all laws relating to New York City, passed since January 1, 1882 :#together with an appendix of the Royal English Colonial Charters of New York City.##1891.##                                                     | 
| 1318088835  | New York City.#Laws, etc.#The Greater New York Charter as enacted in 1897 :#with notes indicating the derivatory statutes and references to judicial decisions relating thereto, together with appendixes ... and the English colonial charters /#by Mark Ash.#c1897.#New York (N.Y.)#Politics and government | 
```