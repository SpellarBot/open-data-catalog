# Maryland Historical and Projected Household Population,1970-2040

## Dataset

* [Dataset URL](https://data.maryland.gov/api/views/fbii-ubkr/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/maryland-historical-and-projected-household-population1970-2040-09833)
* [Metadata URL](https://data.maryland.gov/api/views/fbii-ubkr)
* Id = fbii-ubkr
* Name = Maryland Historical and Projected Household Population,1970-2040
* Attribution = Maryland Department of Planning
* [Attribution Link](http://planning.maryland.gov/msdc/S3_Projection.shtml)
* Category = Planning
* Tags = [household, population, projections, historical, planning, mdp]
* Created = 2014-09-02T20:26:05Z
* Publication Date = 2014-09-02T20:29:18Z
* Rows Updated = 2014-09-02T20:26:18Z

## Description

Household Population Projections for Maryland and the jurisdictions - historical household population 1970-2010; projections out to 2040.
Projections prepared by the Maryland Department of Planning, July 2014

## Columns

```ls
| Name             | Field Name      | Data Type | Render Type | Schema Type    | Included | 
| ================ | =============== | ========= | =========== | ============== | ======== | 
| updated_at       | :updated_at     | meta_data | meta_data   | time           | No       | 
| Year             | year            | text      | text        | series tag     | Yes      | 
| Census, 1970     | census_1970     | number    | number      | numeric metric | Yes      | 
| Census, 1980     | census_1980     | number    | number      | numeric metric | Yes      | 
| Census, 1990     | census_1990     | number    | number      | numeric metric | Yes      | 
| Census, 2000     | census_2000     | number    | number      | numeric metric | Yes      | 
| Census, 2010     | census_2010     | number    | number      | numeric metric | Yes      | 
| Projection, 2015 | projection_2015 | number    | number      | numeric metric | Yes      | 
| Projection, 2020 | projection_2020 | number    | number      | numeric metric | Yes      | 
| Projection, 2025 | projection_2025 | number    | number      | numeric metric | Yes      | 
| Projection, 2030 | projection_2030 | number    | number      | numeric metric | Yes      | 
| Projection, 2035 | projection_2035 | number    | number      | numeric metric | Yes      | 
| Projection, 2040 | projection_2040 | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:fbii-ubkr d:2014-09-02T13:26:09.000Z t:year=MARYLAND m:projection_2020=6071714 m:projection_2035=6584079 m:census_1980=4122547 m:census_2000=5162430 m:census_1990=4666897 m:census_2010=5635177 m:projection_2040=6700425 m:projection_2030=6444321 m:projection_2025=6269826 m:projection_2015=5864129 m:census_1970=3817618

series e:fbii-ubkr d:2014-09-02T13:26:09.000Z t:year="Allegany County" m:projection_2020=66626 m:projection_2035=67877 m:census_1980=77926 m:census_2000=68772 m:census_1990=71895 m:census_2010=67163 m:projection_2040=67877 m:projection_2030=67811 m:projection_2025=67171 m:projection_2015=66425 m:census_1970=82222

series e:fbii-ubkr d:2014-09-02T13:26:09.000Z t:year="Anne Arundel County" m:projection_2020=564900 m:projection_2035=601190 m:census_1980=357451 m:census_2000=473666 m:census_1990=411893 m:census_2010=523523 m:projection_2040=610152 m:projection_2030=590414 m:projection_2025=577971 m:projection_2015=544952 m:census_1970=280151
```

## Meta Commands

```ls
metric m:census_1970 p:integer l:"Census, 1970" t:dataTypeName=number

metric m:census_1980 p:integer l:"Census, 1980" t:dataTypeName=number

metric m:census_1990 p:integer l:"Census, 1990" t:dataTypeName=number

metric m:census_2000 p:integer l:"Census, 2000" t:dataTypeName=number

metric m:census_2010 p:integer l:"Census, 2010" t:dataTypeName=number

metric m:projection_2015 p:integer l:"Projection, 2015" t:dataTypeName=number

metric m:projection_2020 p:integer l:"Projection, 2020" t:dataTypeName=number

metric m:projection_2025 p:integer l:"Projection, 2025" t:dataTypeName=number

metric m:projection_2030 p:integer l:"Projection, 2030" t:dataTypeName=number

metric m:projection_2035 p:integer l:"Projection, 2035" t:dataTypeName=number

metric m:projection_2040 p:integer l:"Projection, 2040" t:dataTypeName=number

entity e:fbii-ubkr l:"Maryland Historical and Projected Household Population,1970-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/fbii-ubkr

property e:fbii-ubkr t:meta.view d:2017-03-07T23:54:39.689Z v:id=fbii-ubkr v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Historical and Projected Household Population,1970-2040" v:attribution="Maryland Department of Planning"

property e:fbii-ubkr t:meta.view.owner d:2017-03-07T23:54:39.689Z v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP

property e:fbii-ubkr t:meta.view.tableauthor d:2017-03-07T23:54:39.689Z v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```