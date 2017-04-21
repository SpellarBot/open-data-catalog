# Expense City Funds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expense-city-funds) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kzk6-y58k) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kzk6-y58k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kzk6-y58k/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kzk6-y58k |
| Name | Expense City Funds |
| Attribution | Mayor's Office of Management and Budget (OMB) |
| Category | City Government |
| Tags | expense, fund, budget, fiscal, finance, year, agency, omb, plan, future, actual |
| Created | 2015-08-06T21:17:07Z |
| Publication Date | 2017-02-08T17:06:45Z |

## Description

Expense City Funds($ IN THOUSANDS) FY 2002 - FY 2016 are actuals; FY 2017 - FY 2021 plan data as of the January 2017 Financial Plan

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
series e:kzk6-y58k d:2017-02-02T18:14:14.000Z t:agn=002 t:agency_name=Mayoralty m:fy_2002_actual=67815 m:fy_2013_actual=60937 m:fy_2018_plan=97465 m:fy_2020_plan=94303 m:fy_2009_actual=66374 m:fy_2010_actual=67427 m:fy_2005_actual=56651 m:fy_2012_actual=61147 m:fy_2021_plan=94303 m:fy_2015_actual=69635 m:fy_2007_actual=63384 m:fy_2019_plan=98309 m:fy_2008_actual=63791 m:fy_2006_actual=59555 m:fy_2003_actual=50729 m:fy_2017_plan=94506 m:fy_2004_actual=54292 m:fy_2014_actual=66073 m:fy_2016_actual=70820 m:fy_2011_actual=63616

series e:kzk6-y58k d:2017-02-02T18:14:14.000Z t:agn=003 t:agency_name="Board of Elections" m:fy_2002_actual=67482 m:fy_2013_actual=101415 m:fy_2018_plan=98616 m:fy_2020_plan=96370 m:fy_2009_actual=80749 m:fy_2010_actual=95446 m:fy_2005_actual=59788 m:fy_2012_actual=109376 m:fy_2021_plan=94176 m:fy_2015_actual=106508 m:fy_2007_actual=71748 m:fy_2019_plan=94919 m:fy_2008_actual=80676 m:fy_2006_actual=63297 m:fy_2003_actual=47642 m:fy_2017_plan=130400 m:fy_2004_actual=68059 m:fy_2014_actual=115523 m:fy_2016_actual=116586 m:fy_2011_actual=101470

series e:kzk6-y58k d:2017-02-02T18:14:14.000Z t:agn=004 t:agency_name="Campaign Finance Board" m:fy_2002_actual=48478 m:fy_2013_actual=9691 m:fy_2018_plan=14014 m:fy_2020_plan=14015 m:fy_2009_actual=8658 m:fy_2010_actual=44320 m:fy_2005_actual=5357 m:fy_2012_actual=9645 m:fy_2021_plan=14015 m:fy_2015_actual=10647 m:fy_2007_actual=6576 m:fy_2019_plan=14015 m:fy_2008_actual=6497 m:fy_2006_actual=38692 m:fy_2003_actual=7245 m:fy_2017_plan=16205 m:fy_2004_actual=14196 m:fy_2014_actual=53476 m:fy_2016_actual=7886 m:fy_2011_actual=11279
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

entity e:kzk6-y58k l:"Expense City Funds" t:attribution="Mayor's Office of Management and Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/kzk6-y58k

property e:kzk6-y58k t:meta.view v:id=kzk6-y58k v:category="City Government" v:averageRating=0 v:name="Expense City Funds" v:attribution="Mayor's Office of Management and Budget (OMB)"

property e:kzk6-y58k t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kzk6-y58k t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agn | agency_name                    | fy_2002_actual | fy_2003_actual | fy_2004_actual | fy_2005_actual | fy_2006_actual | fy_2007_actual | fy_2008_actual | fy_2009_actual | fy_2010_actual | fy_2011_actual | fy_2012_actual | fy_2013_actual | fy_2014_actual | fy_2015_actual | fy_2016_actual | fy_2017_plan | fy_2018_plan | fy_2019_plan | fy_2020_plan | fy_2021_plan | 
| =========== | === | ============================== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============ | ============ | ============ | ============ | ============ | 
| 1486059254  | 002 | Mayoralty                      | 67815          | 50729          | 54292          | 56651          | 59555          | 63384          | 63791          | 66374          | 67427          | 63616          | 61147          | 60937          | 66073          | 69635          | 70820          | 94506        | 97465        | 98309        | 94303        | 94303        | 
| 1486059254  | 003 | Board of Elections             | 67482          | 47642          | 68059          | 59788          | 63297          | 71748          | 80676          | 80749          | 95446          | 101470         | 109376         | 101415         | 115523         | 106508         | 116586         | 130400       | 98616        | 94919        | 96370        | 94176        | 
| 1486059254  | 004 | Campaign Finance Board         | 48478          | 7245           | 14196          | 5357           | 38692          | 6576           | 6497           | 8658           | 44320          | 11279          | 9645           | 9691           | 53476          | 10647          | 7886           | 16205        | 14014        | 14015        | 14015        | 14015        | 
| 1486059254  | 008 | Office of the Actuary          | 3149           | 3277           | 3594           | 4116           | 4944           | 4539           | 5060           | 4689           | 4977           | 4997           | 5547           | 5704           | 5568           | 6247           | 6694           | 7190         | 7354         | 7354         | 7354         | 7354         | 
| 1486059254  | 010 | President,Borough of Manhattan | 5023           | 3778           | 3634           | 3889           | 4318           | 4462           | 5110           | 4979           | 4350           | 3612           | 4541           | 4430           | 4070           | 4425           | 4661           | 4839         | 4583         | 4583         | 4583         | 4583         | 
| 1486059254  | 011 | President,Borough of the Bronx | 6944           | 5283           | 4854           | 5199           | 5345           | 6180           | 6429           | 5192           | 4849           | 4841           | 4825           | 4854           | 4796           | 5172           | 5047           | 5781         | 5450         | 5450         | 5450         | 5450         | 
| 1486059254  | 012 | President,Borough of Brooklyn  | 5941           | 4857           | 4713           | 5053           | 5258           | 6049           | 7981           | 5618           | 5190           | 5150           | 5134           | 5086           | 4916           | 5421           | 5936           | 6324         | 5694         | 5694         | 5694         | 5694         | 
| 1486059254  | 013 | President,Borough of Queens    | 6042           | 4553           | 4505           | 4719           | 4831           | 5529           | 6620           | 4717           | 4588           | 4639           | 4587           | 4533           | 4931           | 4678           | 4981           | 5274         | 4743         | 4743         | 4743         | 4743         | 
| 1486059254  | 014 | President,Borough of S.I.      | 4742           | 3686           | 3602           | 3769           | 4018           | 4267           | 4679           | 3946           | 3871           | 3769           | 3859           | 3905           | 4130           | 3777           | 4048           | 4429         | 4243         | 4243         | 4243         | 4243         | 
| 1486059254  | 015 | Office of the Comptroller      | 54474          | 52230          | 50200          | 50290          | 53673          | 55102          | 56906          | 58646          | 55041          | 53504          | 55290          | 56386          | 64282          | 69988          | 70935          | 80791        | 81216        | 81220        | 81220        | 81220        | 
```