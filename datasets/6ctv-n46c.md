# City Council Legislative Items

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-council-legislative-items) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6ctv-n46c) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6ctv-n46c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6ctv-n46c/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6ctv-n46c |
| Name | City Council Legislative Items |
| Attribution | New York City Council (NYCC) |
| Category | City Government |
| Tags | city council legislative items |
| Created | 2015-02-17T18:38:29Z |
| Publication Date | 2015-02-17T18:39:42Z |

## Description

This list contains information on the legislative items introduced and enacted by the Council

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | series tag  | file         | File #       | text          | text          |
| Yes      | series tag  | law_number   | Law Number   | text          | text          |
| Yes      | series tag  | type         | Type         | text          | text          |
| Yes      | series tag  | status       | Status       | text          | text          |
| Yes      | time        | final_action | Final Action | calendar_date | calendar_date |
| Yes      | series tag  | title        | Title        | text          | text          |
```

## Time Field

```ls
Value = final_action
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6ctv-n46c d:2015-02-17T10:38:32.000Z t:title="Oversight - Culturally Competent Afterschool Programs: Exploring how culturally and linguistically competent afterschool programs benefit youth." t:status=Committee t:file=T2015-2283 t:type=Oversight m:row_number.6ctv-n46c=1

series e:6ctv-n46c d:2015-02-17T10:38:32.000Z t:title="Oversight - Examining DFTA?s Senior Center RFP Process and Criteria for Subcontracted Senior Center Services." t:status=Committee t:file=T2015-2278 t:type=Oversight m:row_number.6ctv-n46c=2

series e:6ctv-n46c d:2015-02-17T10:38:32.000Z t:title="Application No. 20155203 HKM (N 150158 HKM) pursuant to Section 3020 of the New York City Charter, concerning the designation by the Landmarks Preservation Commission regarding the Mills Hotel No. 3, 485 Seventh Avenue (Block 812, Lot 1) (Designation List No. 475, LP-2424). Borough of Manhattan, Community Board 5, Council District 3, as a landmark." t:status=Committee t:file="LU 0168-2014" t:type="Land Use Application" m:row_number.6ctv-n46c=3
```

## Meta Commands

```ls
metric m:row_number.6ctv-n46c p:long l:"Row Number"

entity e:6ctv-n46c l:"City Council Legislative Items" t:attribution="New York City Council (NYCC)" t:url=https://data.cityofnewyork.us/api/views/6ctv-n46c

property e:6ctv-n46c t:meta.view v:id=6ctv-n46c v:category="City Government" v:averageRating=0 v:name="City Council Legislative Items" v:attribution="New York City Council (NYCC)"

property e:6ctv-n46c t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6ctv-n46c t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| file          | law_number | type                 | status    | final_action | title                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 
| ============= | ========== | ==================== | ========= | ============ | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | 
| T2015-2283    |            | Oversight            | Committee |              | Oversight - Culturally Competent Afterschool Programs: Exploring how culturally and linguistically competent afterschool programs benefit youth.                                                                                                                                                                                                                                                                                                                  | 
| T2015-2278    |            | Oversight            | Committee |              | Oversight - Examining DFTA?s Senior Center RFP Process and Criteria for Subcontracted Senior Center Services.                                                                                                                                                                                                                                                                                                                                                     | 
| LU 0168-2014  |            | Land Use Application | Committee |              | Application No. 20155203 HKM (N 150158 HKM) pursuant to Section 3020 of the New York City Charter, concerning the designation by the Landmarks Preservation Commission regarding the Mills Hotel No. 3, 485 Seventh Avenue (Block 812, Lot 1) (Designation List No. 475, LP-2424). Borough of Manhattan, Community Board 5, Council District 3, as a landmark.                                                                                                    | 
| LU 0167-2014  |            | Land Use Application | Committee |              | Application No. 20155204 HKM (N 150157 HKM), pursuant to Section 3020 of the New York City Charter, concerning the designation by the Landmarks Preservation Commission regarding the First German Baptist Church, 334 East 14th Street (Block 455, Lot 24, in part) (Designation List 475, LP-2475) Borough of Manhattan, Community Board 3, Council District 2, as a landmark.                                                                                  | 
| LU 0166-2014  |            | Land Use Application | Committee |              | Application No. 20155174 HKK (N 150124 HKK), pursuant to Section 3020 of the New York City Charter, concerning the designation by the Landmarks Preservation Commission of the Doering Bohack House, 1090 Green Avenue (Block 3924, Lot 1) (Designation List 474, LP-2548), Borough of Brooklyn, Community Board 4, Council District 34, as a landmark.                                                                                                           | 
| LU 0165-2014  |            | Land Use Application | Committee |              | Application No. C 150101 ZMM, submitted by the Department of City Planning pursuant to Sections 197-c and 201 of the New York City Charter for an amendment to the Zoning Map, Section No. 8b, to expand the Special West Chelsea District, Borough of Manhattan, Community Board 4, Council District 3.                                                                                                                                                          | 
| LU 0164-2014  |            | Land Use Application | Committee |              | Application No. N 150102 ZRM submitted by the Department of City Planning pursuant to Section 201 of the New York City Charter, for an amendment of the Zoning Resolution relating to Article IX, Chapter 8 (Special West Chelsea District) to expand the Special District and Article I, Chapter 4 (Sidewalk Caf? Regulations) to allow unenclosed sidewalk cafes in areas of the Special District, Borough of Manhattan, Community Board 4, Council District 3. | 
| Int 0606-2014 |            | Introduction         | Committee |              | A Local Law to amend the administrative code of the city of New York, in relation to requiring the New York Police Department to issue quarterly reports on the use of force and its relationship to quality of life offenses.                                                                                                                                                                                                                                    | 
| Int 0605-2014 |            | Introduction         | Committee |              | A Local Law to amend the administrative code of the city of New York, in relation to requiring the police department to post quarterly reports on its website relating to the use of ?seat belt holds? and ?chokeholds.?                                                                                                                                                                                                                                          | 
| Int 0603-2014 |            | Introduction         | Committee |              | A Local Law to amend the administrative code of the city of New York, in relation to increasing civil penalties for leaving the scene of an incident without reporting.                                                                                                                                                                                                                                                                                           | 
```