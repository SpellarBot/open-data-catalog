# Capital Commitments All Funds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-all-funds) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8fnh-fcum) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8fnh-fcum/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8fnh-fcum/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8fnh-fcum |
| Name | Capital Commitments All Funds |
| Attribution | Mayor?s Office of Management & Budget (OMB) |
| Category | City Government |
| Tags | capital, commitment, fiscal, actual, finance, omb, plan, fund, year |
| Created | 2015-08-06T21:46:47Z |
| Publication Date | 2017-02-08T17:06:49Z |

## Description

Capital Commitments All Funds($ IN MILLIONS) FY 2002 - FY 2016 are actuals; FY 2017 - FY 2020 plan data as of the January 2017 Financial Plan

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | agency         | AGENCY         | text      | text        |
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
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8fnh-fcum d:2017-02-02T18:19:00.000Z t:agency=Aging m:fy_2002_actual=8 m:fy_2013_actual=4 m:fy_2018_plan=13 m:fy_2020_plan=6 m:fy_2009_actual=-1 m:fy_2010_actual=4 m:fy_2005_actual=5 m:fy_2012_actual=4 m:fy_2015_actual=2 m:fy_2007_actual=5 m:fy_2019_plan=12 m:fy_2008_actual=4 m:fy_2006_actual=3 m:fy_2003_actual=5 m:fy_2017_plan=19 m:fy_2004_actual=2 m:fy_2014_actual=6 m:fy_2016_actual=1 m:fy_2011_actual=1

series e:8fnh-fcum d:2017-02-02T18:19:00.000Z t:agency="Waterway Bridges" m:fy_2002_actual=35 m:fy_2013_actual=179 m:fy_2018_plan=512 m:fy_2020_plan=0 m:fy_2009_actual=103 m:fy_2010_actual=687 m:fy_2005_actual=175 m:fy_2012_actual=33 m:fy_2015_actual=111 m:fy_2007_actual=112 m:fy_2019_plan=251 m:fy_2008_actual=691 m:fy_2006_actual=37 m:fy_2003_actual=236 m:fy_2017_plan=189 m:fy_2004_actual=360 m:fy_2014_actual=25 m:fy_2016_actual=147 m:fy_2011_actual=37

series e:8fnh-fcum d:2017-02-02T18:19:00.000Z t:agency=Correction m:fy_2002_actual=32 m:fy_2013_actual=104 m:fy_2018_plan=990 m:fy_2020_plan=78 m:fy_2009_actual=40 m:fy_2010_actual=68 m:fy_2005_actual=50 m:fy_2012_actual=95 m:fy_2015_actual=154 m:fy_2007_actual=44 m:fy_2019_plan=482 m:fy_2008_actual=6 m:fy_2006_actual=92 m:fy_2003_actual=110 m:fy_2017_plan=580 m:fy_2004_actual=30 m:fy_2014_actual=125 m:fy_2016_actual=81 m:fy_2011_actual=69
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

entity e:8fnh-fcum l:"Capital Commitments All Funds" t:attribution="Mayor?s Office of Management & Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/8fnh-fcum

property e:8fnh-fcum t:meta.view v:id=8fnh-fcum v:category="City Government" v:averageRating=0 v:name="Capital Commitments All Funds" v:attribution="Mayor?s Office of Management & Budget (OMB)"

property e:8fnh-fcum t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8fnh-fcum t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency               | fy_2002_actual | fy_2003_actual | fy_2004_actual | fy_2005_actual | fy_2006_actual | fy_2007_actual | fy_2008_actual | fy_2009_actual | fy_2010_actual | fy_2011_actual | fy_2012_actual | fy_2013_actual | fy_2014_actual | fy_2015_actual | fy_2016_actual | fy_2017_plan | fy_2018_plan | fy_2019_plan | fy_2020_plan | 
| =========== | ==================== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============ | ============ | ============ | ============ | 
| 1486059540  | Aging                | 8              | 5              | 2              | 5              | 3              | 5              | 4              | -1             | 4              | 1              | 4              | 4              | 6              | 2              | 1              | 19           | 13           | 12           | 6            | 
| 1486059540  | Waterway Bridges     | 35             | 236            | 360            | 175            | 37             | 112            | 691            | 103            | 687            | 37             | 33             | 179            | 25             | 111            | 147            | 189          | 512          | 251          | 0            | 
| 1486059540  | Correction           | 32             | 110            | 30             | 50             | 92             | 44             | 6              | 40             | 68             | 69             | 95             | 104            | 125            | 154            | 81             | 580          | 990          | 482          | 78           | 
| 1486059540  | Children's Services  | 29             | 13             | 10             | 4              | 1              | 23             | 6              | 8              | 6              | 8              | 13             | 11             | 10             | 6              | 10             | 120          | 103          | 78           | 14           | 
| 1486059540  | Courts               | 192            | 96             | 105            | 132            | 142            | 159            | 540            | 11             | 77             | 97             | 63             | 17             | 123            | 10             | 47             | 213          | 359          | 157          | 233          | 
| 1486059540  | DoITT                | 34             | 71             | 40             | 110            | 112            | 231            | 224            | 240            | 743            | 255            | 131            | 107            | 245            | 94             | 167            | 229          | 134          | 103          | 47           | 
| 1486059540  | Education            | 1340           | 963            | 593            | 2188           | 1990           | 3216           | 3205           | 2656           | 2265           | 1787           | 2481           | 2345           | 2060           | 2884           | 2504           | 3845         | 3155         | 2900         | 2166         | 
| 1486059540  | Economic Development | 193            | 255            | 221            | 215            | 168            | 175            | 398            | 373            | 461            | 190            | 244            | 282            | 278            | 163            | 185            | 1257         | 822          | 574          | 579          | 
| 1486059540  | Fire                 | 149            | 99             | 69             | 93             | 121            | 119            | 153            | 71             | 136            | 94             | 87             | 157            | 63             | 71             | 133            | 288          | 306          | 95           | 109          | 
| 1486059540  | Ferries and Aviation | 156            | 53             | 51             | 69             | 31             | 31             | 20             | 10             | 26             | 20             | 4              | 29             | 35             | 32             | 19             | 368          | 117          | 139          | 44           | 
```