# Conservation Districts (as listed in Article 11 of the San Francisco Planning Code)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/conservation-districts-as-listed-in-article-11-of-the-san-francisco-planning-code) |
| Metadata | [Link](https://data.sfgov.org/api/views/wfz6-yn2b) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wfz6-yn2b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wfz6-yn2b/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wfz6-yn2b |
| Name | Conservation Districts (as listed in Article 11 of the San Francisco Planning Code) |
| Category | Geographic Locations and Boundaries |
| Tags | planning, conservation districts, article 11, shapefile, gis, preservation |
| Created | 2016-07-28T21:31:07Z |
| Publication Date | 2016-08-19T21:35:59Z |

## Description

Conservation Districts as defined and listed in Article 11 of the San Francisco Planning Code (http://planningcode.sfplanning.org). Data are in zipped GIS shapefile format.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | apn         | apn        | text      | text        |
| Yes      | series tag     | article11   | article11  | text      | text        |
| Yes      | series tag     | casenumber  | casenumber | text      | text        |
| Yes      | series tag     | datelisted  | datelisted | text      | text        |
| Yes      | series tag     | filepath    | filepath   | text      | text        |
| Yes      | series tag     | highstnum   | highstnum  | text      | text        |
| No       |                | id          | id         | text      | number      |
| Yes      | series tag     | lowstnum    | lowstnum   | text      | text        |
| Yes      | series tag     | name        | name       | text      | text        |
| Yes      | series tag     | pos         | pos        | text      | text        |
| Yes      | numeric metric | shape_area  | shape_area | number    | number      |
| Yes      | numeric metric | shape_leng  | shape_leng | number    | number      |
| Yes      | series tag     | stname      | stname     | text      | text        |
| Yes      | series tag     | sttype      | sttype     | text      | text        |
| Yes      | series tag     | surveyname  | surveyname | text      | text        |
| No       |                | geometry    | geometry   | polygon   | polygon     |
| Yes      | series tag     | multigeom   | multigeom  | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,geometry
```

## Data Commands

```ls
series e:wfz6-yn2b d:2016-08-19T04:00:48.000Z t:lowstnum=155 t:article11=I t:datelisted=1899-12-30 t:name="PACIFIC COAST STOCK EXCHANGE TOWER" t:multigeom=false t:sttype=ST t:highstnum=155 t:stname=SANSOME t:apn=0268001A m:shape_area=6428.16796054 m:shape_leng=396.941319635

series e:wfz6-yn2b d:2016-08-19T04:00:48.000Z t:lowstnum=220 t:article11=I t:datelisted=1899-12-30 t:name="MILLS BUILDING & TOWER" t:multigeom=false t:sttype=ST t:highstnum=232 t:stname=MONTGOMERY t:apn=0268006 m:shape_area=6868.07299007 m:shape_leng=374.722718286

series e:wfz6-yn2b d:2016-08-19T04:00:48.000Z t:lowstnum=407 t:article11=I t:datelisted=1899-12-30 t:multigeom=false t:sttype=ST t:highstnum=407 t:stname=SANSOME t:apn=0228003 m:shape_area=3917.16747961 m:shape_leng=348.790947718
```

## Meta Commands

```ls
metric m:shape_area p:long l:shape_area t:dataTypeName=number

metric m:shape_leng p:long l:shape_leng t:dataTypeName=number

entity e:wfz6-yn2b l:"Conservation Districts (as listed in Article 11 of the San Francisco Planning Code)" t:url=https://data.sfgov.org/api/views/wfz6-yn2b

property e:wfz6-yn2b t:meta.view v:id=wfz6-yn2b v:category="Geographic Locations and Boundaries" v:averageRating=0 v:name="Conservation Districts (as listed in Article 11 of the San Francisco Planning Code)"

property e:wfz6-yn2b t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wfz6-yn2b t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:wfz6-yn2b t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | apn      | article11 | casenumber | datelisted | filepath | highstnum | id | lowstnum | name                               | pos | shape_area    | shape_leng    | stname     | sttype | surveyname | geometry                                                                                                                                                                                                                                                                                                                                                                  | multigeom | 
| =========== | ======== | ========= | ========== | ========== | ======== | ========= | == | ======== | ================================== | === | ============= | ============= | ========== | ====== | ========== | ========================================================================================================================================================================================================================================================================================================================================================================= | ========= | 
| 1471579248  | 0268001A | I         |            | 1899-12-30 |          | 155       | 0  | 155      | PACIFIC COAST STOCK EXCHANGE TOWER |     | 6428.16796054 | 396.941319635 | SANSOME    | ST     |            | POLYGON ((-122.40126000210256 37.7915894712726, -122.4014306945175 37.791566941779045, -122.40149897122747 37.791557929916124, -122.40152191104175 37.79166932727707, -122.40098351913736 37.791737945255235, -122.40096079796183 37.791627605004074, -122.40119166309674 37.791598181193784, -122.40126000210256 37.7915894712726))                                      | false     | 
| 1471579248  | 0268006  | I         |            | 1899-12-30 |          | 232       | 0  | 220      | MILLS BUILDING & TOWER             |     | 6868.07299007 | 374.722718286 | MONTGOMERY | ST     |            | POLYGON ((-122.40135410381825 37.79119501866661, -122.4014306945175 37.791566941779045, -122.40126000210256 37.7915894712726, -122.40118325666421 37.79121679444313, -122.40135410381825 37.79119501866661))                                                                                                                                                              | false     | 
| 1471579248  | 0228003  | I         |            | 1899-12-30 |          | 407       | 0  | 407      |                                    |     | 3917.16747961 | 348.790947718 | SANSOME    | ST     |            | POLYGON ((-122.40179197661382 37.79399352238969, -122.40184835838231 37.79398633700425, -122.40188157025875 37.79414760471245, -122.40185630096539 37.79415082495673, -122.4017708746421 37.79416171322463, -122.40148896614544 37.794197640578396, -122.40147231456025 37.79411678301252, -122.40180853640632 37.79407393169372, -122.40179197661382 37.79399352238969)) | false     | 
| 1471579248  | 0228002  | IV        |            | 1899-12-30 |          | 415       | 0  | 415      | YOKOHAMA SPECIE BANK               |     | 4950.00668727 | 285.000755293 | SANSOME    | ST     |            | POLYGON ((-122.4017708746421 37.79416171322463, -122.40180436526997 37.79432433457677, -122.4015224573766 37.79436026469368, -122.40148896614544 37.794197640578396, -122.4017708746421 37.79416171322463))                                                                                                                                                               | false     | 
| 1471579248  | 0326002  | IV        |            | 1899-12-30 |          | 161       | 0  | 151      | HOTEL HERBERT                      |     | 5882.29126307 | 347.751457895 | POWELL     | ST     |            | POLYGON ((-122.40853158690258 37.78607195156983, -122.4085566164539 37.78619671232845, -122.40811943838347 37.78625106592967, -122.40809441068326 37.786126305061146, -122.40853158690258 37.78607195156983))                                                                                                                                                             | false     | 
| 1471579248  | 0326004  | IV        |            | 1899-12-30 |          | 111       | 0  | 111      | BERNSTEIN'S FISH GROTTO            |     | 8742.29849712 | 374.001620161 | POWELL     | ST     |            | POLYGON ((-122.4083259913039 37.78564752929679, -122.40837686376258 37.785901118427006, -122.40805720867914 37.78594085974144, -122.40800633612646 37.78568726959267, -122.4083259913039 37.78564752929679))                                                                                                                                                              | false     | 
| 1471579248  | 0228029  | I         |            | 1899-12-30 |          | 552       | 0  | 552      | BANK OF ITALY                      |     | 1660.39573704 | 170.693433132 | MONTGOMERY | ST     |            | POLYGON ((-122.4027133645043 37.79447481104127, -122.40281587616549 37.79446174573881, -122.40284676975344 37.79461174131323, -122.40274426317025 37.794624835395744, -122.4027133645043 37.79447481104127))                                                                                                                                                              | false     | 
| 1471579248  | 0267001  | I         |            | 1899-12-30 |          | 99        | 0  | 99       | DONAHUE BUILDING                   |     | 4468.44627167 | 286.661378118 | BATTERY    | ST     |            | POLYGON ((-122.40019405637365 37.79210622313964, -122.39986089991464 37.7921486799516, -122.39983532227872 37.792024462736975, -122.40016847819507 37.79198200599631, -122.40019405637365 37.79210622313964))                                                                                                                                                             | false     | 
| 1471579248  | 0307009  | I         |            | 1899-12-30 |          | 432       | 0  | 432      | FIRST CONGREGATIONAL CHURCH        |     | 15454.5887193 | 500.171347556 | MASON      | ST     |            | POLYGON ((-122.40954561807236 37.788052139656806, -122.40946832197434 37.787676751015816, -122.40984962355381 37.787627925380555, -122.40992675058926 37.78800333456815, -122.40954561807236 37.788052139656806))                                                                                                                                                         | false     | 
| 1471579248  | 0308001  | I         |            | 1899-12-30 |          | 0         | 0  | 0        | UNION SQUARE                       |     | 113243.647496 | 1373.59221298 |            |        |            | POLYGON ((-122.40812734938889 37.78746930960263, -122.40828081369902 37.78821467141974, -122.40687198885156 37.7883930568126, -122.40672169293481 37.78764729430323, -122.40812734938889 37.78746930960263))                                                                                                                                                              | false     | 
```