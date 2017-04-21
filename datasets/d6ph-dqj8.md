# Grier Partnership Part C - Demographic Projection Report - Enrollment Projections - New York City Public Schools

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grier-partnership-part-c-demographic-projection-report-enrollment-projections-new-york-cit-67c65) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/d6ph-dqj8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/d6ph-dqj8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/d6ph-dqj8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | d6ph-dqj8 |
| Name | Grier Partnership Part C - Demographic Projection Report - Enrollment Projections - New York City Public Schools |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | school, construction, authority, sca, education, enrollment, forecast |
| Created | 2013-07-02T19:01:07Z |
| Publication Date | 2013-11-18T15:15:03Z |

## Description

Demographic projections performed by the Grier Partnership for high school level students.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | borough     | Borough    | text      | text        |
| Yes      | series tag     | grade       | Grade      | text      | text        |
| Yes      | numeric metric | year_2008   | Year 2011  | number    | number      |
| Yes      | numeric metric | year_2009   | Year 2012  | number    | number      |
| Yes      | numeric metric | year_2010   | Year 2013  | number    | number      |
| Yes      | numeric metric | year_2011   | Year 2014  | number    | number      |
| Yes      | numeric metric | year_2012   | Year 2015  | number    | number      |
| Yes      | numeric metric | year_2013   | Year 2016  | number    | number      |
| Yes      | numeric metric | year_2014   | Year 2017  | number    | number      |
| Yes      | numeric metric | year_2015   | Year 2018  | number    | number      |
| Yes      | numeric metric | year_2016   | Year 2019  | number    | number      |
| Yes      | numeric metric | year_2017   | Year 2020  | number    | number      |
| Yes      | numeric metric | year_2018   | Year 2021  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:d6ph-dqj8 d:2013-11-15T13:35:47.000Z t:grade=9 t:borough=MANHATTAN m:year_2010=15105 m:year_2008=16018 m:year_2009=15478 m:year_2015=15364 m:year_2016=15321 m:year_2017=15777 m:year_2018=16048 m:year_2011=15367 m:year_2012=14894 m:year_2013=14500 m:year_2014=14907

series e:d6ph-dqj8 d:2013-11-15T13:35:47.000Z t:grade=10 t:borough=MANHATTAN m:year_2010=14768 m:year_2008=16143 m:year_2009=15257 m:year_2015=14418 m:year_2016=14880 m:year_2017=14873 m:year_2018=15358 m:year_2011=14439 m:year_2012=14740 m:year_2013=14294 m:year_2014=13965

series e:d6ph-dqj8 d:2013-11-15T13:35:47.000Z t:grade=11 t:borough=MANHATTAN m:year_2010=12147 m:year_2008=13435 m:year_2009=12802 m:year_2015=11345 m:year_2016=11768 m:year_2017=12228 m:year_2018=12250 m:year_2011=11813 m:year_2012=11581 m:year_2013=11864 m:year_2014=11550
```

## Meta Commands

```ls
metric m:year_2008 p:integer l:"Year 2011" d:"The 2011 data for each grade and district" t:dataTypeName=number

metric m:year_2009 p:integer l:"Year 2012" d:"The 2012 data for each grade and district" t:dataTypeName=number

metric m:year_2010 p:integer l:"Year 2013" d:"The 2013 data for each grade and district" t:dataTypeName=number

metric m:year_2011 p:integer l:"Year 2014" d:"The 2014 data for each grade and district" t:dataTypeName=number

metric m:year_2012 p:integer l:"Year 2015" d:"The 2015 data for each grade and district" t:dataTypeName=number

metric m:year_2013 p:integer l:"Year 2016" d:"The 2016 data for each grade and district" t:dataTypeName=number

metric m:year_2014 p:integer l:"Year 2017" d:"The 2017 data for each grade and district" t:dataTypeName=number

metric m:year_2015 p:integer l:"Year 2018" d:"The 2018 data for each grade and district" t:dataTypeName=number

metric m:year_2016 p:integer l:"Year 2019" d:"The 2019 data for each grade and district" t:dataTypeName=number

metric m:year_2017 p:integer l:"Year 2020" d:"The 2020 data for each grade and district" t:dataTypeName=number

metric m:year_2018 p:integer l:"Year 2021" d:"The 2021 data for each grade and district" t:dataTypeName=number

entity e:d6ph-dqj8 l:"Grier Partnership Part C - Demographic Projection Report - Enrollment Projections - New York City Public Schools" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/d6ph-dqj8

property e:d6ph-dqj8 t:meta.view v:id=d6ph-dqj8 v:category=Education v:averageRating=0 v:name="Grier Partnership Part C - Demographic Projection Report - Enrollment Projections - New York City Public Schools" v:attribution="School Construction Authority (SCA)"

property e:d6ph-dqj8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:d6ph-dqj8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough   | grade       | year_2008 | year_2009 | year_2010 | year_2011 | year_2012 | year_2013 | year_2014 | year_2015 | year_2016 | year_2017 | year_2018 | 
| =========== | ========= | =========== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | 
| 1384522547  | MANHATTAN | 9           | 16018     | 15478     | 15105     | 15367     | 14894     | 14500     | 14907     | 15364     | 15321     | 15777     | 16048     | 
| 1384522547  | MANHATTAN | 10          | 16143     | 15257     | 14768     | 14439     | 14740     | 14294     | 13965     | 14418     | 14880     | 14873     | 15358     | 
| 1384522547  | MANHATTAN | 11          | 13435     | 12802     | 12147     | 11813     | 11581     | 11864     | 11550     | 11345     | 11768     | 12228     | 12250     | 
| 1384522547  | MANHATTAN | 12          | 11932     | 12080     | 11526     | 10950     | 10662     | 10461     | 10729     | 10453     | 10284     | 10683     | 11118     | 
| 1384522547  | MANHATTAN | Spec Ed     | 4829      | 5058      | 5214      | 5420      | 5692      | 5983      | 6333      | 6831      | 7314      | 7484      | 7590      | 
| 1384522547  | MANHATTAN | GED (16-20) | 1453      | 1453      | 1453      | 1453      | 1453      | 1453      | 1453      | 1453      | 1453      | 1453      | 1453      | 
| 1384522547  | MANHATTAN | GED (21+)   | 14        | 14        | 14        | 14        | 14        | 14        | 14        | 14        | 14        | 14        | 14        | 
| 1384522547  | BRONX     | 9           | 15529     | 15230     | 15229     | 15668     | 15485     | 14952     | 15398     | 15252     | 15555     | 16487     | 16880     | 
| 1384522547  | BRONX     | 10          | 14350     | 14290     | 14022     | 14021     | 14442     | 14275     | 13787     | 14205     | 14082     | 14368     | 15249     | 
| 1384522547  | BRONX     | 11          | 11162     | 10252     | 10216     | 10034     | 10027     | 10367     | 10247     | 9906      | 10217     | 10151     | 10372     | 
```