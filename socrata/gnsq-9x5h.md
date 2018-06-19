# Arterial Streets of San Francisco

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arterial-streets-of-san-francisco-zipped-shapefile-format) |
| Metadata | [Link](https://data.sfgov.org/api/views/gnsq-9x5h) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/gnsq-9x5h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/gnsq-9x5h/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | gnsq-9x5h |
| Name | Arterial Streets of San Francisco |
| Category | Geographic Locations and Boundaries |
| Tags | public works |
| Created | 2016-07-28T23:37:24Z |
| Publication Date | 2016-08-19T21:34:10Z |

## Description

Arterial Streets of San Francisco, as designated by DPW staff. This is a view of the STCLINES layer and the TBL_STCLINES_ARTERIAL attribute data.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | cnn         | cnn        | number    | number      |
| Yes      | series tag     | layer       | layer      | text      | text        |
| Yes      | series tag     | streetname  | streetname | text      | text        |
| Yes      | series tag     | geometry    | geometry   | line      | line        |
| Yes      | series tag     | multigeom   | multigeom  | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gnsq-9x5h d:2017-04-15T15:22:06.000Z t:multigeom=false t:layer=STREETS t:geometry="LINESTRING (-122.39738553878267 37.7825535929401, -122.39684142736164 37.78211912156441)" t:streetname="3RD ST" m:cnn=172000

series e:gnsq-9x5h d:2017-04-15T15:22:06.000Z t:multigeom=false t:layer=STREETS t:geometry="LINESTRING (-122.39684142736164 37.78211912156441, -122.39637951914675 37.78175028375868)" t:streetname="3RD ST" m:cnn=173000

series e:gnsq-9x5h d:2017-04-15T15:22:06.000Z t:multigeom=false t:layer=STREETS t:geometry="LINESTRING (-122.39637951914675 37.78175028375868, -122.395843499031 37.78132125715609)" t:streetname="3RD ST" m:cnn=174000
```

## Meta Commands

```ls
metric m:cnn p:long l:cnn t:dataTypeName=number

entity e:gnsq-9x5h l:"Arterial Streets of San Francisco" t:url=https://data.sfgov.org/api/views/gnsq-9x5h

property e:gnsq-9x5h t:meta.view v:id=gnsq-9x5h v:category="Geographic Locations and Boundaries" v:averageRating=0 v:name="Arterial Streets of San Francisco"

property e:gnsq-9x5h t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:gnsq-9x5h t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:gnsq-9x5h t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | cnn      | layer   | streetname | geometry                                                                                   | multigeom | 
| =========== | ======== | ======= | ========== | ========================================================================================== | ========= | 
| 1492269726  | 172000.0 | STREETS | 3RD ST     | LINESTRING (-122.39738553878267 37.7825535929401, -122.39684142736164 37.78211912156441)   | false     | 
| 1492269726  | 173000.0 | STREETS | 3RD ST     | LINESTRING (-122.39684142736164 37.78211912156441, -122.39637951914675 37.78175028375868)  | false     | 
| 1492269726  | 174000.0 | STREETS | 3RD ST     | LINESTRING (-122.39637951914675 37.78175028375868, -122.395843499031 37.78132125715609)    | false     | 
| 1492269726  | 175000.0 | STREETS | 3RD ST     | LINESTRING (-122.395843499031 37.78132125715609, -122.39551775271012 37.78106214069288)    | false     | 
| 1492269726  | 176000.0 | STREETS | 3RD ST     | LINESTRING (-122.39551775271012 37.78106214069288, -122.39506495187591 37.78070056031112)  | false     | 
| 1492269726  | 177000.0 | STREETS | 3RD ST     | LINESTRING (-122.39506495187591 37.78070056031112, -122.39463146334731 37.780354394924)    | false     | 
| 1492269726  | 178000.0 | STREETS | 3RD ST     | LINESTRING (-122.39463146334731 37.780354394924, -122.39430003733213 37.78008973028664)    | false     | 
| 1492269726  | 179000.0 | STREETS | 3RD ST     | LINESTRING (-122.39430003733213 37.78008973028664, -122.39274978677028 37.77885171751994)  | false     | 
| 1492269726  | 180000.0 | STREETS | 3RD ST     | LINESTRING (-122.39274978677028 37.77885171751994, -122.39184052529684 37.778125697523656) | false     | 
| 1492269726  | 181000.0 | STREETS | 3RD ST     | LINESTRING (-122.39184052529684 37.778125697523656, -122.391121418858 37.77755327717929)   | false     | 
```