# Expense All Funds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expense-all-funds) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/am45-6syq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/am45-6syq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/am45-6syq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | am45-6syq |
| Name | Expense All Funds |
| Attribution | Mayor?s Office of Management & Budget (OMB) |
| Category | City Government |
| Tags | expense, fund, budget, fiscal, finance, year, agency, actual, omb, plan, future |
| Created | 2015-08-06T21:51:22Z |
| Publication Date | 2017-02-08T17:06:44Z |

## Description

Expense All Funds($ IN THOUSANDS) FY 2002 - FY 2016 are actuals; FY 2017 - FY 2021 plan data as of the January 2017 Financial Plan

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | agn            | AGN            | text      | text        |
| Yes      | series tag     | agency_name    | AGENCY NAME    | text      | text        |
| Yes      | numeric metric | fy_2002_actual | FY 2002 Actual | number    | number      |
| Yes      | numeric metric | fy_2003_actual | FY 2003 Actual | number    | number      |
| Yes      | numeric metric | fy_2004_actual | FY 2004 Actual | number    | number      |
| Yes      | numeric metric | fy_2005_actual | FY 2005 Actual | number    | number      |
| Yes      | numeric metric | fy_2006_actual | FY 2006 Actual | number    | number      |
| Yes      | numeric metric | fy_2007_actual | FY 2007 Actual | number    | number      |
| Yes      | numeric metric | fy_2008_actual | FY 2008 Actual | number    | number      |
| Yes      | numeric metric | fy_2009_actual | FY 2009 Actual | number    | number      |
| Yes      | numeric metric | fy_2010_actual | FY 2010 Actual | number    | number      |
| Yes      | numeric metric | fy_2011_actual | FY 2011 Actual | number    | number      |
| Yes      | numeric metric | fy_2012_actual | FY 2012 Actual | number    | number      |
| Yes      | numeric metric | fy_2013_actual | FY 2013 Actual | number    | number      |
| Yes      | numeric metric | fy_2014_actual | FY 2014 Actual | number    | number      |
| Yes      | numeric metric | fy_2015_actual | FY 2015 Actual | number    | number      |
| Yes      | numeric metric | fy_2016_actual | FY 2016 Actual | number    | number      |
| Yes      | numeric metric | fy_2017_plan   | FY 2017 Plan   | number    | number      |
| Yes      | numeric metric | fy_2018_plan   | FY 2018 Plan   | number    | number      |
| Yes      | numeric metric | fy_2019_plan   | FY 2019 Plan   | number    | number      |
| Yes      | numeric metric | fy_2020_plan   | FY 2020 Plan   | number    | number      |
| Yes      | numeric metric | fy_2021_plan   | FY 2021 Plan   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:am45-6syq d:2017-02-02T18:13:54.000Z t:agn=002 t:agency_name=Mayoralty m:fy_2002_actual=109673 m:fy_2013_actual=93177 m:fy_2018_plan=140029 m:fy_2020_plan=134197 m:fy_2009_actual=90933 m:fy_2010_actual=95503 m:fy_2005_actual=75306 m:fy_2012_actual=93346 m:fy_2021_plan=122101 m:fy_2015_actual=101722 m:fy_2007_actual=85666 m:fy_2019_plan=138209 m:fy_2008_actual=89377 m:fy_2006_actual=79102 m:fy_2003_actual=94449 m:fy_2017_plan=137161 m:fy_2004_actual=72939 m:fy_2014_actual=95787 m:fy_2016_actual=109533 m:fy_2011_actual=94884

series e:am45-6syq d:2017-02-02T18:13:54.000Z t:agn=003 t:agency_name="Board of Elections" m:fy_2002_actual=67482 m:fy_2013_actual=107473 m:fy_2018_plan=98616 m:fy_2020_plan=96370 m:fy_2009_actual=81054 m:fy_2010_actual=95706 m:fy_2005_actual=59788 m:fy_2012_actual=109839 m:fy_2021_plan=94176 m:fy_2015_actual=106755 m:fy_2007_actual=71748 m:fy_2019_plan=94919 m:fy_2008_actual=80676 m:fy_2006_actual=63297 m:fy_2003_actual=55630 m:fy_2017_plan=132424 m:fy_2004_actual=68059 m:fy_2014_actual=116163 m:fy_2016_actual=116672 m:fy_2011_actual=102874

series e:am45-6syq d:2017-02-02T18:13:54.000Z t:agn=004 t:agency_name="Campaign Finance Board" m:fy_2002_actual=48500 m:fy_2013_actual=9691 m:fy_2018_plan=14014 m:fy_2020_plan=14015 m:fy_2009_actual=8658 m:fy_2010_actual=44320 m:fy_2005_actual=5357 m:fy_2012_actual=9645 m:fy_2021_plan=14015 m:fy_2015_actual=10647 m:fy_2007_actual=6576 m:fy_2019_plan=14015 m:fy_2008_actual=6497 m:fy_2006_actual=38692 m:fy_2003_actual=7245 m:fy_2017_plan=16205 m:fy_2004_actual=14196 m:fy_2014_actual=53531 m:fy_2016_actual=7886 m:fy_2011_actual=11279
```

## Meta Commands

```ls
metric m:fy_2002_actual p:integer l:"FY 2002 Actual" t:dataTypeName=number

metric m:fy_2003_actual p:integer l:"FY 2003 Actual" t:dataTypeName=number

metric m:fy_2004_actual p:integer l:"FY 2004 Actual" t:dataTypeName=number

metric m:fy_2005_actual p:integer l:"FY 2005 Actual" t:dataTypeName=number

metric m:fy_2006_actual p:integer l:"FY 2006 Actual" t:dataTypeName=number

metric m:fy_2007_actual p:integer l:"FY 2007 Actual" t:dataTypeName=number

metric m:fy_2008_actual p:integer l:"FY 2008 Actual" t:dataTypeName=number

metric m:fy_2009_actual p:integer l:"FY 2009 Actual" t:dataTypeName=number

metric m:fy_2010_actual p:integer l:"FY 2010 Actual" t:dataTypeName=number

metric m:fy_2011_actual p:integer l:"FY 2011 Actual" t:dataTypeName=number

metric m:fy_2012_actual p:integer l:"FY 2012 Actual" t:dataTypeName=number

metric m:fy_2013_actual p:integer l:"FY 2013 Actual" t:dataTypeName=number

metric m:fy_2014_actual p:integer l:"FY 2014 Actual" t:dataTypeName=number

metric m:fy_2015_actual p:integer l:"FY 2015 Actual" t:dataTypeName=number

metric m:fy_2016_actual p:integer l:"FY 2016 Actual" t:dataTypeName=number

metric m:fy_2017_plan p:integer l:"FY 2017 Plan" t:dataTypeName=number

metric m:fy_2018_plan p:integer l:"FY 2018 Plan" t:dataTypeName=number

metric m:fy_2019_plan p:integer l:"FY 2019 Plan" t:dataTypeName=number

metric m:fy_2020_plan p:integer l:"FY 2020 Plan" t:dataTypeName=number

metric m:fy_2021_plan p:integer l:"FY 2021 Plan" t:dataTypeName=number

entity e:am45-6syq l:"Expense All Funds" t:attribution="Mayor?s Office of Management & Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/am45-6syq

property e:am45-6syq t:meta.view v:id=am45-6syq v:category="City Government" v:averageRating=0 v:name="Expense All Funds" v:attribution="Mayor?s Office of Management & Budget (OMB)"

property e:am45-6syq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:am45-6syq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agn | agency_name                    | fy_2002_actual | fy_2003_actual | fy_2004_actual | fy_2005_actual | fy_2006_actual | fy_2007_actual | fy_2008_actual | fy_2009_actual | fy_2010_actual | fy_2011_actual | fy_2012_actual | fy_2013_actual | fy_2014_actual | fy_2015_actual | fy_2016_actual | fy_2017_plan | fy_2018_plan | fy_2019_plan | fy_2020_plan | fy_2021_plan | 
| =========== | === | ============================== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============ | ============ | ============ | ============ | ============ | 
| 1486059234  | 002 | Mayoralty                      | 109673         | 94449          | 72939          | 75306          | 79102          | 85666          | 89377          | 90933          | 95503          | 94884          | 93346          | 93177          | 95787          | 101722         | 109533         | 137161       | 140029       | 138209       | 134197       | 122101       | 
| 1486059234  | 003 | Board of Elections             | 67482          | 55630          | 68059          | 59788          | 63297          | 71748          | 80676          | 81054          | 95706          | 102874         | 109839         | 107473         | 116163         | 106755         | 116672         | 132424       | 98616        | 94919        | 96370        | 94176        | 
| 1486059234  | 004 | Campaign Finance Board         | 48500          | 7245           | 14196          | 5357           | 38692          | 6576           | 6497           | 8658           | 44320          | 11279          | 9645           | 9691           | 53531          | 10647          | 7886           | 16205        | 14014        | 14015        | 14015        | 14015        | 
| 1486059234  | 008 | Office of the Actuary          | 3149           | 3277           | 3594           | 4116           | 4944           | 4539           | 5060           | 4689           | 4977           | 4997           | 5547           | 5704           | 5568           | 6247           | 6694           | 7190         | 7354         | 7354         | 7354         | 7354         | 
| 1486059234  | 010 | President,Borough of Manhattan | 5027           | 3862           | 3723           | 3889           | 4318           | 4694           | 5822           | 4996           | 4699           | 4353           | 4541           | 4430           | 4070           | 4425           | 4661           | 4839         | 4583         | 4583         | 4583         | 4583         | 
| 1486059234  | 011 | President,Borough of the Bronx | 6944           | 5358           | 5079           | 5343           | 5614           | 6359           | 6926           | 5566           | 4894           | 4861           | 4868           | 4982           | 4901           | 5287           | 5064           | 5799         | 5450         | 5450         | 5450         | 5450         | 
| 1486059234  | 012 | President,Borough of Brooklyn  | 6090           | 5083           | 4839           | 5136           | 5436           | 6072           | 8088           | 5652           | 5300           | 5374           | 5140           | 5210           | 5089           | 5856           | 6369           | 6399         | 5694         | 5694         | 5694         | 5694         | 
| 1486059234  | 013 | President,Borough of Queens    | 6290           | 4823           | 4817           | 4889           | 4947           | 5529           | 6660           | 4717           | 4596           | 4701           | 4587           | 4602           | 4985           | 4755           | 5094           | 5326         | 4743         | 4743         | 4743         | 4743         | 
| 1486059234  | 014 | President,Borough of S.I.      | 4788           | 3709           | 3770           | 3921           | 4018           | 4267           | 4717           | 3986           | 3875           | 3769           | 3859           | 3905           | 4130           | 3777           | 4048           | 4429         | 4243         | 4243         | 4243         | 4243         | 
| 1486059234  | 015 | Office of the Comptroller      | 57602          | 54970          | 55546          | 56616          | 61335          | 63101          | 65762          | 67892          | 67657          | 67138          | 70885          | 73220          | 80738          | 86477          | 90370          | 105062       | 105631       | 105637       | 105637       | 105637       | 
```