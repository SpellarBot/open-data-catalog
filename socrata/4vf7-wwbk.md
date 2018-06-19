# Capital Commitments City Funds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-city-funds) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4vf7-wwbk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4vf7-wwbk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4vf7-wwbk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4vf7-wwbk |
| Name | Capital Commitments City Funds |
| Attribution | Mayor?s Office of Management & Budget (OMB) |
| Category | City Government |
| Tags | nyc capital city funds, omb, capital, commitment, actual, fiscal, finance, plan, year, fund |
| Created | 2015-08-06T21:06:17Z |
| Publication Date | 2017-02-08T17:06:51Z |

## Description

Capital Commitments City Funds($ IN MILLIONS) FY 2002 - FY 2016 are actuals; FY 2017 - FY 2020 plan data as of the January 2017 Financial Plan

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
series e:4vf7-wwbk d:2017-02-02T18:21:25.000Z t:agency=Aging m:fy_2002_actual=8 m:fy_2013_actual=4 m:fy_2018_plan=13 m:fy_2020_plan=6 m:fy_2009_actual=-1 m:fy_2010_actual=4 m:fy_2005_actual=5 m:fy_2012_actual=4 m:fy_2015_actual=2 m:fy_2007_actual=5 m:fy_2019_plan=12 m:fy_2008_actual=4 m:fy_2006_actual=3 m:fy_2003_actual=5 m:fy_2017_plan=19 m:fy_2004_actual=2 m:fy_2014_actual=6 m:fy_2016_actual=1 m:fy_2011_actual=1

series e:4vf7-wwbk d:2017-02-02T18:21:25.000Z t:agency="Waterway Bridges" m:fy_2002_actual=46 m:fy_2013_actual=174 m:fy_2018_plan=501 m:fy_2020_plan=0 m:fy_2009_actual=103 m:fy_2010_actual=336 m:fy_2005_actual=3 m:fy_2012_actual=-39 m:fy_2015_actual=74 m:fy_2007_actual=108 m:fy_2019_plan=251 m:fy_2008_actual=352 m:fy_2006_actual=14 m:fy_2003_actual=181 m:fy_2017_plan=189 m:fy_2004_actual=215 m:fy_2014_actual=25 m:fy_2016_actual=112 m:fy_2011_actual=37

series e:4vf7-wwbk d:2017-02-02T18:21:25.000Z t:agency=Correction m:fy_2002_actual=31 m:fy_2013_actual=104 m:fy_2018_plan=990 m:fy_2020_plan=78 m:fy_2009_actual=40 m:fy_2010_actual=68 m:fy_2005_actual=50 m:fy_2012_actual=95 m:fy_2015_actual=153 m:fy_2007_actual=44 m:fy_2019_plan=482 m:fy_2008_actual=6 m:fy_2006_actual=92 m:fy_2003_actual=110 m:fy_2017_plan=506 m:fy_2004_actual=30 m:fy_2014_actual=114 m:fy_2016_actual=79 m:fy_2011_actual=69
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

entity e:4vf7-wwbk l:"Capital Commitments City Funds" t:attribution="Mayor?s Office of Management & Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/4vf7-wwbk

property e:4vf7-wwbk t:meta.view v:id=4vf7-wwbk v:category="City Government" v:averageRating=0 v:name="Capital Commitments City Funds" v:attribution="Mayor?s Office of Management & Budget (OMB)"

property e:4vf7-wwbk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4vf7-wwbk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency               | fy_2002_actual | fy_2003_actual | fy_2004_actual | fy_2005_actual | fy_2006_actual | fy_2007_actual | fy_2008_actual | fy_2009_actual | fy_2010_actual | fy_2011_actual | fy_2012_actual | fy_2013_actual | fy_2014_actual | fy_2015_actual | fy_2016_actual | fy_2017_plan | fy_2018_plan | fy_2019_plan | fy_2020_plan | 
| =========== | ==================== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============ | ============ | ============ | ============ | 
| 1486059685  | Aging                | 8              | 5              | 2              | 5              | 3              | 5              | 4              | -1             | 4              | 1              | 4              | 4              | 6              | 2              | 1              | 19           | 13           | 12           | 6            | 
| 1486059685  | Waterway Bridges     | 46             | 181            | 215            | 3              | 14             | 108            | 352            | 103            | 336            | 37             | -39            | 174            | 25             | 74             | 112            | 189          | 501          | 251          | 0            | 
| 1486059685  | Correction           | 31             | 110            | 30             | 50             | 92             | 44             | 6              | 40             | 68             | 69             | 95             | 104            | 114            | 153            | 79             | 506          | 990          | 482          | 78           | 
| 1486059685  | Children's Services  | 25             | 13             | 10             | 4              | 1              | 23             | 6              | 8              | 5              | 7              | 13             | 9              | 8              | 4              | 10             | 102          | 96           | 75           | 12           | 
| 1486059685  | Courts               | 191            | 86             | 103            | 129            | 142            | 159            | 540            | 11             | 77             | 97             | 63             | 17             | 123            | 10             | 36             | 206          | 354          | 157          | 233          | 
| 1486059685  | DoITT                | 34             | 63             | 40             | 110            | 85             | 228            | 224            | 231            | 745            | 252            | 131            | 107            | 245            | 94             | 167            | 229          | 134          | 103          | 47           | 
| 1486059685  | Education            | 1337           | 890            | 571            | 2188           | 1411           | 1143           | 1127           | 991            | 1123           | 953            | 1263           | 1282           | 1040           | 1546           | 2455           | 3343         | 2483         | 2705         | 2166         | 
| 1486059685  | Economic Development | 190            | 237            | 206            | 207            | 154            | 134            | 380            | 300            | 399            | 143            | 205            | 272            | 255            | 152            | 168            | 1058         | 782          | 545          | 495          | 
| 1486059685  | Fire                 | 149            | 81             | 66             | 93             | 108            | 116            | 121            | 71             | 120            | 90             | 83             | 143            | 52             | 70             | 144            | 243          | 204          | 95           | 109          | 
| 1486059685  | Ferries and Aviation | 117            | 46             | 19             | -8             | 15             | 24             | 13             | 8              | 16             | 5              | 5              | 11             | 22             | 27             | 10             | 164          | 40           | 119          | 35           | 
```