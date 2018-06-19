# iZone School List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/izone-school-list-c1f1a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cr93-x2xf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cr93-x2xf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cr93-x2xf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cr93-x2xf |
| Name | iZone School List |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | izone school list |
| Created | 2013-03-22T19:07:18Z |
| Publication Date | 2013-03-22T19:57:34Z |

## Description

The iZone is the NYC Department of Education's initiative to strategically develop and scale innovative 21st century school and classroom models that increase student achievement. The iZone consists of a dedicated community of schools that design and build the learning experience around the needs,  motivations and strengths of each student in order to prepare them for success in college and career.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | dbn         | DBN        | text      | text        |
| Yes      | series tag  | school      | School     | text      | text        |
| Yes      | series tag  | initiative  | Initiative | text      | text        |
| Yes      | series tag  | cohort      | Cohort     | text      | text        |
| Yes      | series tag  | principal   | Principal  | text      | text        |
| Yes      | series tag  | email       | Email      | text      | text        |
| Yes      | series tag  | phone       | Phone      | text      | text        |
| No       |             | address     | Address    | text      | text        |
| Yes      | series tag  | coach       | Coach      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:cr93-x2xf d:2013-03-22T12:15:08.000Z t:cohort=2 t:phone=212-460-8467 t:school="East Side Community School" t:principal="Mark Federman" t:email=mfederm@schools.nyc.gov t:dbn=01M450 t:coach="Al Sylvia" t:initiative=iLearn360 m:row_number.cr93-x2xf=1

series e:cr93-x2xf d:2013-03-22T12:15:08.000Z t:phone="(212) 677-8900" t:school="Forsyth Satellite Academy" t:principal="Ingrid Roberts Haynes" t:email=IRobert4@schools.nyc.gov t:dbn=01M458 t:coach="Alex Jimenez" t:initiative=iLearnNYC m:row_number.cr93-x2xf=2

series e:cr93-x2xf d:2013-03-22T12:15:08.000Z t:phone="(212) 473-8152" t:school="Marta Valle High School" t:principal="Mimi Fortunato" t:email=MFortun@schools.nyc.gov t:dbn=01M509 t:coach="Richard Haynes" t:initiative=iLearnNYC m:row_number.cr93-x2xf=3
```

## Meta Commands

```ls
metric m:row_number.cr93-x2xf p:long l:"Row Number"

entity e:cr93-x2xf l:"iZone School List" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/cr93-x2xf

property e:cr93-x2xf t:meta.view v:id=cr93-x2xf v:category=Education v:averageRating=0 v:name="iZone School List" v:attribution="Department of Education (DOE)"

property e:cr93-x2xf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cr93-x2xf t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | dbn    | school                                  | initiative           | cohort | principal             | email                    | phone          | address                                        | coach                                | 
| =========== | ====== | ======================================= | ==================== | ====== | ===================== | ======================== | ============== | ============================================== | ==================================== | 
| 1363954508  | 01M450 | East Side Community School              | iLearn360            | 2      | Mark Federman         | mfederm@schools.nyc.gov  | 212-460-8467   | 420 E. 12 Street Manhattan NY 10009            | Al Sylvia                            | 
| 1363954508  | 01M458 | Forsyth Satellite Academy               | iLearnNYC            |        | Ingrid Roberts Haynes | IRobert4@schools.nyc.gov | (212) 677-8900 | 198 Forsyth St, New York, NY 10002             | Alex Jimenez                         | 
| 1363954508  | 01M509 | Marta Valle High School                 | iLearnNYC            |        | Mimi Fortunato        | MFortun@schools.nyc.gov  | (212) 473-8152 | 45 Stanton St, New York, NY 10002              | Richard Haynes                       | 
| 1363954508  | 01M515 | Lower East Side Preparatory High School | iLearnNYC            |        | MARTHA POLIN          | MPolin@schools.nyc.gov   | (212) 505-6366 | 145 Stanton St, New York, NY 10002             | Alex Jimenez                         | 
| 1363954508  | 01M650 | Cascades High School                    | iLearn360            |        | PAUL ROTONDO          | PRotond@schools.nyc.gov  | (646) 654-1261 | 198 Forsyth St, Manhattan, NY 10002            | Richard Haynes                       | 
| 1363954508  | 01M839 | Tompkins Square Middle School           | iLearn360            | 1      | Sonhando Estwick      | sestwic@schools.nyc.gov  | 212-995-1430   | 600 E. 6 Street Manhattan NY 10009             | Jennifer Rygalski                    | 
| 1363954508  | 02M289 | I.S. 289                                | iLearnNYC, iLearn360 |        | Ellen Foote           | efoote@schools.nyc.gov   | (212) 571-9268 |  201 Warren St, New York, NY 10282             | Vasilia Lambrides and Valrie Edwards | 
| 1363954508  | 02M296 | High School of Hospitality Management   | iLearnNYC            |        | MATTHEW CORALLO       | MCorall@schools.nyc.gov  | (212) 586-0963 | 525 W 50th St, New York, NY 10019              | Joe Iacono                           | 
| 1363954508  | 02M374 | Gramercy Arts High School               | iLearn360 Cohort 1   |        | DENISE DICARLO        | DDiCarl@schools.nyc.gov  | (212) 253-7076 | 40 Irving Pl, New York, NY 10003               | Natalie Cosby                        | 
| 1363954508  | 02M376 | NYC iSchool                             | iLearnNYC, iLearn360 |        | Isora Bailey          | ibailey@schools.nyc.gov  | (917) 237-7300 | 131 Avenue of the Americas, New York, NY 10012 | Eileen Marks, Jennifer Rygalski      | 
```