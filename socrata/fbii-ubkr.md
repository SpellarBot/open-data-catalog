# Maryland Historical and Projected Household Population,1970-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-historical-and-projected-household-population1970-2040-09833) |
| Metadata | [Link](https://data.maryland.gov/api/views/fbii-ubkr) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/fbii-ubkr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/fbii-ubkr/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | fbii-ubkr |
| Name | Maryland Historical and Projected Household Population,1970-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | household, population, projections, historical, planning, mdp |
| Created | 2014-09-02T20:26:05Z |
| Publication Date | 2014-09-02T20:29:18Z |

## Description

Household Population Projections for Maryland and the jurisdictions - historical household population 1970-2010; projections out to 2040.
Projections prepared by the Maryland Department of Planning, July 2014

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| Yes      | series tag     | year            | Year             | text      | text        |
| Yes      | numeric metric | census_1970     | Census, 1970     | number    | number      |
| Yes      | numeric metric | census_1980     | Census, 1980     | number    | number      |
| Yes      | numeric metric | census_1990     | Census, 1990     | number    | number      |
| Yes      | numeric metric | census_2000     | Census, 2000     | number    | number      |
| Yes      | numeric metric | census_2010     | Census, 2010     | number    | number      |
| Yes      | numeric metric | projection_2015 | Projection, 2015 | number    | number      |
| Yes      | numeric metric | projection_2020 | Projection, 2020 | number    | number      |
| Yes      | numeric metric | projection_2025 | Projection, 2025 | number    | number      |
| Yes      | numeric metric | projection_2030 | Projection, 2030 | number    | number      |
| Yes      | numeric metric | projection_2035 | Projection, 2035 | number    | number      |
| Yes      | numeric metric | projection_2040 | Projection, 2040 | number    | number      |
```

## Time Field

```ls
Value = 1970
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fbii-ubkr d:1970-01-01T00:00:00.000Z t:year=MARYLAND m:projection_2040=6700425 m:projection_2030=6444321 m:census_2010=5635177 m:projection_2020=6071714 m:projection_2015=5864129 m:census_1990=4666897 m:projection_2035=6584079 m:census_1970=3817618 m:census_2000=5162430 m:projection_2025=6269826 m:census_1980=4122547

series e:fbii-ubkr d:1970-01-01T00:00:00.000Z t:year="Allegany County" m:projection_2040=67877 m:projection_2030=67811 m:census_2010=67163 m:projection_2020=66626 m:projection_2015=66425 m:census_1990=71895 m:projection_2035=67877 m:census_1970=82222 m:census_2000=68772 m:projection_2025=67171 m:census_1980=77926

series e:fbii-ubkr d:1970-01-01T00:00:00.000Z t:year="Anne Arundel County" m:projection_2040=610152 m:projection_2030=590414 m:census_2010=523523 m:projection_2020=564900 m:projection_2015=544952 m:census_1990=411893 m:projection_2035=601190 m:census_1970=280151 m:census_2000=473666 m:projection_2025=577971 m:census_1980=357451
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

property e:fbii-ubkr t:meta.view d:2017-09-25T07:28:57.762Z v:averageRating=0 v:name="Maryland Historical and Projected Household Population,1970-2040" v:attribution="Maryland Department of Planning" v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:id=fbii-ubkr v:category=Planning

property e:fbii-ubkr t:meta.view.owner d:2017-09-25T07:28:57.762Z v:displayName=MDP v:lastNotificationSeenAt=1495028713 v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:id=85mq-rt9c v:screenName=MDP v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB

property e:fbii-ubkr t:meta.view.tableauthor d:2017-09-25T07:28:57.762Z v:displayName=MDP v:lastNotificationSeenAt=1495028713 v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:roleName=editor v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:id=85mq-rt9c v:screenName=MDP v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB
```

## Top Records

```ls
| year                | census_1970 | census_1980 | census_1990 | census_2000 | census_2010 | projection_2015 | projection_2020 | projection_2025 | projection_2030 | projection_2035 | projection_2040 | 
| =================== | =========== | =========== | =========== | =========== | =========== | =============== | =============== | =============== | =============== | =============== | =============== | 
| MARYLAND            | 3817618     | 4122547     | 4666897     | 5162430     | 5635177     | 5864129         | 6071714         | 6269826         | 6444321         | 6584079         | 6700425         | 
| Allegany County     | 82222       | 77926       | 71895       | 68772       | 67163       | 66425           | 66626           | 67171           | 67811           | 67877           | 67877           | 
| Anne Arundel County | 280151      | 357451      | 411893      | 473666      | 523523      | 544952          | 564900          | 577971          | 590414          | 601190          | 610152          | 
| Baltimore City      | 887479      | 769954      | 715292      | 625401      | 595762      | 598491          | 606679          | 615607          | 622057          | 625731          | 628117          | 
| Baltimore County    | 607282      | 642354      | 678424      | 736652      | 784248      | 810666          | 825306          | 834825          | 839240          | 845112          | 854694          | 
| Calvert County      | 20478       | 34441       | 51089       | 73982       | 88087       | 90953           | 94835           | 97502           | 99235           | 99949           | 100201          | 
| Caroline County     | 19479       | 22870       | 26552       | 29319       | 32624       | 33455           | 35586           | 37750           | 39905           | 42147           | 44286           | 
| Carroll County      | 63960       | 92514       | 120457      | 147316      | 163815      | 165142          | 172360          | 175727          | 179255          | 181871          | 184882          | 
| Cecil County        | 49176       | 58382       | 69483       | 84730       | 99557       | 101951          | 106806          | 115305          | 123037          | 130426          | 136939          | 
| Charles County      | 47188       | 72166       | 99973       | 119177      | 145146      | 155566          | 172663          | 188768          | 200018          | 209873          | 218118          | 
```