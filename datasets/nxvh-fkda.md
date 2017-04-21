# Grier Partnership Part B - Demographic Projection Report - Enrollment Projections - New York City Public Schools

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grier-partnership-part-b-demographic-projection-report-enrollment-projections-new-york-cit-8b3a5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nxvh-fkda) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nxvh-fkda/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nxvh-fkda/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nxvh-fkda |
| Name | Grier Partnership Part B - Demographic Projection Report - Enrollment Projections - New York City Public Schools |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | school, construction, authority, sca, education, enrollment, forecast |
| Created | 2013-07-02T19:01:07Z |
| Publication Date | 2013-11-18T15:12:44Z |

## Description

Demographic projections performed by the Grier Partnership for elementary and middle school level students.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | district_or_borough | District or Borough | text      | text        |
| Yes      | series tag     | grade               | Grade               | text      | text        |
| Yes      | numeric metric | year_2008           | Year 2011           | number    | number      |
| Yes      | numeric metric | year_2009           | Year 2012           | number    | number      |
| Yes      | numeric metric | year_2010           | Year 2013           | number    | number      |
| Yes      | numeric metric | year_2011           | Year 2014           | number    | number      |
| Yes      | numeric metric | year_2012           | Year 2015           | number    | number      |
| Yes      | numeric metric | year_2013           | Year 2016           | number    | number      |
| Yes      | numeric metric | year_2014           | Year 2017           | number    | number      |
| Yes      | numeric metric | year_2015           | Year 2018           | number    | number      |
| Yes      | numeric metric | year_2016           | Year 2019           | number    | number      |
| Yes      | numeric metric | year_2017           | Year 2020           | number    | number      |
| Yes      | numeric metric | year_2018           | Year 2021           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nxvh-fkda d:2013-11-15T13:35:09.000Z t:district_or_borough=31 t:grade="Special Ed" m:year_2010=5957 m:year_2008=5231 m:year_2009=5587 m:year_2015=7250 m:year_2016=7290 m:year_2017=7320 m:year_2018=7327 m:year_2011=6315 m:year_2012=6649 m:year_2013=6867 m:year_2014=7057

series e:nxvh-fkda d:2013-11-15T13:35:09.000Z t:district_or_borough=NYC t:grade=Pre-K m:year_2010=56654 m:year_2008=56874 m:year_2009=57074 m:year_2015=56273 m:year_2016=56417 m:year_2017=56561 m:year_2018=56706 m:year_2011=55688 m:year_2012=55832 m:year_2013=55977 m:year_2014=56127

series e:nxvh-fkda d:2013-11-15T13:35:09.000Z t:district_or_borough=NYC t:grade=K m:year_2010=69723 m:year_2008=68537 m:year_2009=70319 m:year_2015=68681 m:year_2016=68913 m:year_2017=69147 m:year_2018=69381 m:year_2011=69180 m:year_2012=67978 m:year_2013=68212 m:year_2014=68443
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

entity e:nxvh-fkda l:"Grier Partnership Part B - Demographic Projection Report - Enrollment Projections - New York City Public Schools" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/nxvh-fkda

property e:nxvh-fkda t:meta.view v:id=nxvh-fkda v:category=Education v:attributionLink=http://www.nycsca.org/Community/CapitalPlanManagementReportsData/Demographics/2009-2018GrierPartnershipReport.pdf v:averageRating=0 v:name="Grier Partnership Part B - Demographic Projection Report - Enrollment Projections - New York City Public Schools" v:attribution="School Construction Authority (SCA)"

property e:nxvh-fkda t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nxvh-fkda t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district_or_borough | grade      | year_2008 | year_2009 | year_2010 | year_2011 | year_2012 | year_2013 | year_2014 | year_2015 | year_2016 | year_2017 | year_2018 | 
| =========== | =================== | ========== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | 
| 1384522509  | 31                  | Special Ed | 5231      | 5587      | 5957      | 6315      | 6649      | 6867      | 7057      | 7250      | 7290      | 7320      | 7327      | 
| 1384522509  | NYC                 | Pre-K      | 56874     | 57074     | 56654     | 55688     | 55832     | 55977     | 56127     | 56273     | 56417     | 56561     | 56706     | 
| 1384522509  | NYC                 | K          | 68537     | 70319     | 69723     | 69180     | 67978     | 68212     | 68443     | 68681     | 68913     | 69147     | 69381     | 
| 1384522509  | NYC                 | 1          | 68946     | 71362     | 73244     | 72609     | 72078     | 70794     | 71043     | 71289     | 71542     | 71788     | 72036     | 
| 1384522509  | NYC                 | 2          | 66277     | 66369     | 68747     | 70624     | 70004     | 69503     | 68265     | 68523     | 68778     | 69040     | 69295     | 
| 1384522509  | NYC                 | 3          | 64808     | 64897     | 65007     | 67353     | 69245     | 68641     | 68161     | 66965     | 67237     | 67505     | 67781     | 
| 1384522509  | NYC                 | 4          | 62504     | 63693     | 63839     | 63933     | 66287     | 68174     | 67570     | 67101     | 65941     | 66220     | 66495     | 
| 1384522509  | NYC                 | 5          | 61139     | 60838     | 62053     | 62313     | 62426     | 64797     | 66723     | 66140     | 65702     | 64584     | 64892     | 
| 1384522509  | NYC                 | 6          | 62335     | 61150     | 60803     | 62035     | 62385     | 62451     | 64866     | 66752     | 66171     | 65745     | 64600     | 
| 1384522509  | NYC                 | 7          | 60696     | 62532     | 61347     | 61021     | 62305     | 62703     | 62786     | 65282     | 67218     | 66667     | 66260     | 
```