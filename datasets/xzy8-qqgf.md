# Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by Statistical Forecasting

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/demographic-projection-report-enrollment-projections-new-york-city-public-schools-prepared-04658) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xzy8-qqgf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xzy8-qqgf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xzy8-qqgf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xzy8-qqgf |
| Name | Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by Statistical Forecasting |
| Attribution | School Construction Authority (SCA) |
| Category | Housing & Development |
| Tags | school, construction, authority, sca, demographic projection, statistical forecasting, lifelong learning |
| Created | 2013-03-06T15:19:49Z |
| Publication Date | 2013-06-21T20:47:55Z |

## Description

The SCA?s comprehensive capital planning process includes developing and analyzing quality data, creating and updating the Department of Education?s Five-Year Capital Plans, and monitoring projects through completion. The SCA prioritizes capital projects to best meet the capacity and building improvements needs throughout the City.  Additionally, the SCA assures that the Capital Plan aligns with New York State and City Department of Education mandates, academic initiatives, and budgetary resources.  This is one of the most current published reports.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | borough_or_district | Borough or District | text      | text        |
| Yes      | series tag     | data_type           | Data Type           | text      | text        |
| Yes      | time           | year                | Year                | text      | text        |
| No       |                | pk                  | PK                  | text      | text        |
| No       |                | k                   | K                   | text      | text        |
| No       |                | _1                  | 1                   | text      | text        |
| No       |                | _2                  | 2                   | text      | text        |
| No       |                | _3                  | 3                   | text      | text        |
| No       |                | _4                  | 4                   | text      | text        |
| No       |                | _5                  | 5                   | text      | text        |
| No       |                | _6                  | 6                   | text      | text        |
| No       |                | _7                  | 7                   | text      | text        |
| No       |                | _8                  | 8                   | text      | text        |
| No       |                | _9                  | 9                   | text      | text        |
| Yes      | series tag     | _10                 | 10                  | text      | text        |
| Yes      | series tag     | _11                 | 11                  | text      | text        |
| Yes      | series tag     | _12                 | 12                  | text      | text        |
| Yes      | series tag     | ged                 | GED                 | text      | text        |
| Yes      | numeric metric | se1                 | SE1                 | number    | text        |
| Yes      | numeric metric | total               | Total               | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = pk,k,_1,_2,_3,_4,_5,_6,_7,_8,_9
```

## Data Commands

```ls
series e:xzy8-qqgf d:2008-09-01T00:00:00.000Z t:ged=9034 t:_11=59782 t:data_type=Historical t:_10=82089 t:borough_or_district=NYC t:_12=53846 m:total=1024498 m:se1=102954

series e:xzy8-qqgf d:2009-10-01T00:00:00.000Z t:ged=8477 t:_11=58095 t:data_type=Projected t:_10=78015 t:borough_or_district=NYC t:_12=55662 m:total=1014349 m:se1=107408

series e:xzy8-qqgf d:2010-11-01T00:00:00.000Z t:ged=8477 t:_11=55427 t:data_type=Projected t:_10=77355 t:borough_or_district=NYC t:_12=54060 m:total=1005556 m:se1=112215
```

## Meta Commands

```ls
metric m:se1 p:integer l:SE1 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:xzy8-qqgf l:"Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by Statistical Forecasting" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/xzy8-qqgf

property e:xzy8-qqgf t:meta.view v:id=xzy8-qqgf v:category="Housing & Development" v:averageRating=0 v:name="Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by Statistical Forecasting" v:attribution="School Construction Authority (SCA)"

property e:xzy8-qqgf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xzy8-qqgf t:meta.view.tableauthor v:id=ci6y-i73t v:screenName="Harish Pathria" v:displayName="Harish Pathria"
```

## Top Records

```ls
| borough_or_district | data_type  | year    | pk    | k     | _1    | _2    | _3    | _4    | _5    | _6    | _7    | _8    | _9    | _10   | _11   | _12   | ged  | se1    | total   | 
| =================== | ========== | ======= | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ==== | ====== | ======= | 
| NYC                 | Historical | 2008-09 | 54038 | 62563 | 68010 | 65958 | 64413 | 62364 | 61771 | 61560 | 63107 | 65508 | 87501 | 82089 | 59782 | 53846 | 9034 | 102954 | 1024498 | 
| NYC                 | Projected  | 2009-10 | 52879 | 62298 | 68827 | 65343 | 63239 | 62492 | 60713 | 59889 | 62162 | 62174 | 86676 | 78015 | 58095 | 55662 | 8477 | 107408 | 1014349 | 
| NYC                 | Projected  | 2010-11 | 54104 | 61435 | 68581 | 66183 | 62703 | 61371 | 60883 | 58857 | 60487 | 61247 | 82171 | 77355 | 55427 | 54060 | 8477 | 112215 | 1005556 | 
| NYC                 | Projected  | 2011-12 | 55619 | 62943 | 67592 | 65944 | 63556 | 60900 | 59824 | 58975 | 59472 | 59629 | 80839 | 73531 | 54964 | 51587 | 8477 | 116958 | 1000810 | 
| NYC                 | Projected  | 2012-13 | 55819 | 64751 | 69196 | 64983 | 63326 | 61758 | 59431 | 57956 | 59590 | 58668 | 78563 | 72337 | 52432 | 51156 | 8477 | 121753 | 1000196 | 
| NYC                 | Projected  | 2013-14 | 56016 | 64997 | 71119 | 66553 | 62404 | 61530 | 60298 | 57550 | 58559 | 58838 | 77042 | 70332 | 51587 | 48801 | 8477 | 126578 | 1000681 | 
| NYC                 | Projected  | 2014-15 | 56222 | 65237 | 71393 | 68440 | 63949 | 60635 | 60101 | 58443 | 58198 | 57824 | 77001 | 69114 | 50226 | 48004 | 8477 | 131451 | 1004715 | 
| NYC                 | Projected  | 2015-16 | 56357 | 65473 | 71660 | 68700 | 65823 | 62170 | 59225 | 58241 | 59101 | 57507 | 75781 | 69286 | 49456 | 46718 | 8477 | 136365 | 1010340 | 
| NYC                 | Projected  | 2016-17 | 56585 | 65648 | 71923 | 68954 | 66069 | 64019 | 60781 | 57376 | 58915 | 58443 | 75209 | 68076 | 49902 | 46007 | 8477 | 141325 | 1017709 | 
| NYC                 | Projected  | 2017-18 | 56809 | 65923 | 72117 | 69208 | 66313 | 64254 | 62636 | 58900 | 58030 | 58247 | 76191 | 67703 | 48868 | 46428 | 8477 | 146330 | 1026434 | 
```