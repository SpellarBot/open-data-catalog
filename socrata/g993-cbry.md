# iZone PLS School List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/izone-pls-school-list-3ec45) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/g993-cbry) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/g993-cbry/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/g993-cbry/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | g993-cbry |
| Name | iZone PLS School List |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | izone, pls, school |
| Created | 2013-03-22T19:07:21Z |
| Publication Date | 2013-03-22T19:17:03Z |

## Description

The iZone is the NYC Department of Education's initiative to strategically develop and scale innovative 21st century school and classroom models that increase student achievement. The iZone consists of a dedicated community of schools that design and build the learning experience around the needs,  motivations and strengths of each student in order to prepare them for success in college and career.  PLS was a Personalized Learning Systems pilot undertaken in elementaryschools where schools had access to adaptive learning software such as Time to Know, CompassLearning Odyssey and Pearson SuccessMaker, web-based programs that assist teachers in managing and differentiating instruction in ELA and Math.

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                          | Data Type | Render Type |
| ======== | =========== | ============================= | ============================= | ========= | =========== |
| No       | time        | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | series tag  | school_name                   | School Name                   | text      | text        |
| Yes      | series tag  | 12_13_initative               | 12-13 Initative               | text      | text        |
| Yes      | series tag  | location_category_description | Location Category Description | text      | text        |
| Yes      | series tag  | borough                       | Borough                       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:g993-cbry d:2013-03-22T12:16:40.000Z t:location_category_description="Junior High-Intermediate-Middle" t:school_name="Bronx Middle School of Academic and Career Technology" t:borough=Bronx t:12_13_initative=InnovateNYC m:row_number.g993-cbry=1

series e:g993-cbry d:2013-03-22T12:16:40.000Z t:location_category_description=Elementary t:school_name="P.S. 005 Port Morris" t:borough=Bronx t:12_13_initative=InnovateNYC m:row_number.g993-cbry=2

series e:g993-cbry d:2013-03-22T12:16:40.000Z t:location_category_description=Elementary t:school_name="P.S. 016 John J. Driscoll" t:borough="Staten Island" t:12_13_initative=InnovateNYC m:row_number.g993-cbry=3
```

## Meta Commands

```ls
metric m:row_number.g993-cbry p:long l:"Row Number"

entity e:g993-cbry l:"iZone PLS School List" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/g993-cbry

property e:g993-cbry t:meta.view v:id=g993-cbry v:category=Education v:averageRating=0 v:name="iZone PLS School List" v:attribution="Department of Education (DOE)"

property e:g993-cbry t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:g993-cbry t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | school_name                                           | 12_13_initative | location_category_description   | borough       | 
| =========== | ===================================================== | =============== | =============================== | ============= | 
| 1363954600  | Bronx Middle School of Academic and Career Technology | InnovateNYC     | Junior High-Intermediate-Middle | Bronx         | 
| 1363954600  | P.S. 005 Port Morris                                  | InnovateNYC     | Elementary                      | Bronx         | 
| 1363954600  | P.S. 016 John J. Driscoll                             | InnovateNYC     | Elementary                      | Staten Island | 
| 1363954600  | P.S. 020 Clinton Hill                                 | InnovateNYC     | Elementary                      | Brooklyn      | 
| 1363954600  | P.S. 025 Eubie Blake School                           | InnovateNYC     | Elementary                      | Brooklyn      | 
| 1363954600  | P.S. 030 Westerleigh                                  | InnovateNYC     | Elementary                      | Staten Island | 
| 1363954600  | P.S. 056 Harry Eichler                                | InnovateNYC     | Elementary                      | Queens        | 
| 1363954600  | P.S. 057 Crescent                                     | InnovateNYC     | Elementary                      | Bronx         | 
| 1363954600  | P.S. 069 The New Vision School                        | InnovateNYC     | Elementary                      | Bronx         | 
| 1363954600  | P.S. 076 A. Philip Randolph                           | InnovateNYC     | Elementary                      | Manhattan     | 
```