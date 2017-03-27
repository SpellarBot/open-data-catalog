# Traffic Analysis Zones

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-analysis-zones-8dc6c) |
| Metadata | [Link](https://data.sfgov.org/api/views/j4sj-j2nf) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/j4sj-j2nf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/j4sj-j2nf/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | j4sj-j2nf |
| Name | Traffic Analysis Zones |
| Category | Geographic Locations and Boundaries |
| Tags | planning, taz, census, traffic, analysis, gis, shapefile |
| Created | 2016-07-26T18:30:09Z |
| Publication Date | 2016-08-19T21:41:29Z |

## Description

A traffic analysis zone (TAZ) is the unit of geography most commonly used in conventional transportation planning models. The size of a zone varies, but for a typical metropolitan planning software, a zone of under 3000 people is common. The cartographic boundary files are simplified representations of selected geographic areas from the Census Bureau’s MAF/TIGER geographic database. These boundary files are specifically designed for small scale thematic mapping.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | area        | area       | number    | number      |
| Yes      | series tag     | county      | county     | text      | text        |
| Yes      | series tag     | lsad        | lsad       | text      | text        |
| Yes      | series tag     | lsad_trans  | lsad_trans | text      | text        |
| Yes      | series tag     | name        | name       | text      | text        |
| Yes      | numeric metric | perimeter   | perimeter  | number    | number      |
| Yes      | series tag     | state       | state      | text      | text        |
| Yes      | series tag     | taz         | taz        | text      | text        |
| Yes      | numeric metric | tz06_d00_   | tz06_d00_  | number    | number      |
| Yes      | numeric metric | tz06_d00_i  | tz06_d00_i | number    | number      |
| No       |                | geometry    | geometry   | polygon   | polygon     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = geometry
```

## Data Commands

```ls
series e:j4sj-j2nf d:2016-07-26T18:30:18.000Z t:taz=706 t:county=007 t:name=706 t:state=06 m:area=0.0179622866015006 m:tz06_d00_=2 m:perimeter=0.932156624884747 m:tz06_d00_i=2

series e:j4sj-j2nf d:2016-07-26T18:30:18.000Z t:taz=708 t:county=007 t:name=708 t:state=06 m:area=0.0324499727644987 m:tz06_d00_=3 m:perimeter=1.05920246907166 m:tz06_d00_i=3

series e:j4sj-j2nf d:2016-07-26T18:30:18.000Z t:taz=704 t:county=007 t:name=704 t:state=06 m:area=0.0242911759453004 m:tz06_d00_=4 m:perimeter=0.941563538203072 m:tz06_d00_i=4
```

## Meta Commands

```ls
metric m:area p:long l:area t:dataTypeName=number

metric m:perimeter p:long l:perimeter t:dataTypeName=number

metric m:tz06_d00_ p:long l:tz06_d00_ t:dataTypeName=number

metric m:tz06_d00_i p:long l:tz06_d00_i t:dataTypeName=number

entity e:j4sj-j2nf l:"Traffic Analysis Zones" t:url=https://data.sfgov.org/api/views/j4sj-j2nf

property e:j4sj-j2nf t:meta.view v:id=j4sj-j2nf v:category="Geographic Locations and Boundaries" v:averageRating=0 v:name="Traffic Analysis Zones"

property e:j4sj-j2nf t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:j4sj-j2nf t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:j4sj-j2nf t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```