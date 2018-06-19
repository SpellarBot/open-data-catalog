# Additional Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/additional-revenue) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hii3-dcun) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hii3-dcun/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hii3-dcun/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hii3-dcun |
| Name | Additional Revenue |
| Attribution | Mayor?s Office of Management & Budget (OMB) |
| Category | City Government |
| Tags | revenue, omb, fiscal, financial, plan, future, tax, aid, intergovernment, actual, intergovernmental, disallow, grant, capital, ifa, restrict, unrestricted, year |
| Created | 2015-08-06T21:32:39Z |
| Publication Date | 2017-02-08T17:06:48Z |

## Description

Additional Revenue ($ IN MILLIONS) FY 2002 - FY 2016 are actuals; FY 2017 - FY 2021 plan data as of the January 2017 Financial Plan

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | category       | Category       | text      | text        |
| Yes      | series tag     | subcategory    | Subcategory    | text      | text        |
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
series e:hii3-dcun d:2017-02-02T18:17:29.000Z t:category=Taxes t:subcategory="Real Property Tax" m:fy_2002_actual=8761 m:fy_2013_actual=18970 m:fy_2018_plan=25629 m:fy_2020_plan=28618 m:fy_2009_actual=14487 m:fy_2010_actual=16369 m:fy_2005_actual=11616 m:fy_2012_actual=18158 m:fy_2021_plan=29929 m:fy_2015_actual=21518 m:fy_2007_actual=13123 m:fy_2019_plan=27292 m:fy_2008_actual=13204 m:fy_2006_actual=12636 m:fy_2003_actual=10063 m:fy_2017_plan=24196 m:fy_2004_actual=11582 m:fy_2014_actual=20202 m:fy_2016_actual=22974 m:fy_2011_actual=17086

series e:hii3-dcun d:2017-02-02T18:17:29.000Z t:category=Taxes t:subcategory="Personal Income Tax" m:fy_2002_actual=4990 m:fy_2013_actual=9778 m:fy_2018_plan=11493 m:fy_2020_plan=12496 m:fy_2009_actual=7627 m:fy_2010_actual=7576 m:fy_2005_actual=7135 m:fy_2012_actual=8531 m:fy_2021_plan=13007 m:fy_2015_actual=11264 m:fy_2007_actual=8618 m:fy_2019_plan=11890 m:fy_2008_actual=9861 m:fy_2006_actual=8007 m:fy_2003_actual=5000 m:fy_2017_plan=11155 m:fy_2004_actual=6093 m:fy_2014_actual=10152 m:fy_2016_actual=10733 m:fy_2011_actual=8138

series e:hii3-dcun d:2017-02-02T18:17:29.000Z t:category=Taxes t:subcategory="Business Taxes" m:fy_2002_actual=2440 m:fy_2013_actual=5857 m:fy_2018_plan=6045 m:fy_2020_plan=6392 m:fy_2009_actual=5204 m:fy_2010_actual=4505 m:fy_2005_actual=3711 m:fy_2012_actual=5362 m:fy_2021_plan=6596 m:fy_2015_actual=6049 m:fy_2007_actual=6013 m:fy_2019_plan=6247 m:fy_2008_actual=5412 m:fy_2006_actual=4343 m:fy_2003_actual=2282 m:fy_2017_plan=5938 m:fy_2004_actual=2863 m:fy_2014_actual=5875 m:fy_2016_actual=5662 m:fy_2011_actual=5299
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

entity e:hii3-dcun l:"Additional Revenue" t:attribution="Mayor?s Office of Management & Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/hii3-dcun

property e:hii3-dcun t:meta.view v:id=hii3-dcun v:category="City Government" v:averageRating=0 v:name="Additional Revenue" v:attribution="Mayor?s Office of Management & Budget (OMB)"

property e:hii3-dcun t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hii3-dcun t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | category              | subcategory         | fy_2002_actual | fy_2003_actual | fy_2004_actual | fy_2005_actual | fy_2006_actual | fy_2007_actual | fy_2008_actual | fy_2009_actual | fy_2010_actual | fy_2011_actual | fy_2012_actual | fy_2013_actual | fy_2014_actual | fy_2015_actual | fy_2016_actual | fy_2017_plan | fy_2018_plan | fy_2019_plan | fy_2020_plan | fy_2021_plan | 
| =========== | ===================== | =================== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============ | ============ | ============ | ============ | ============ | 
| 1486059449  | Taxes                 | Real Property Tax   | 8761           | 10063          | 11582          | 11616          | 12636          | 13123          | 13204          | 14487          | 16369          | 17086          | 18158          | 18970          | 20202          | 21518          | 22974          | 24196        | 25629        | 27292        | 28618        | 29929        | 
| 1486059449  | Taxes                 | Personal Income Tax | 4990           | 5000           | 6093           | 7135           | 8007           | 8618           | 9861           | 7627           | 7576           | 8138           | 8531           | 9778           | 10152          | 11264          | 10733          | 11155        | 11493        | 11890        | 12496        | 13007        | 
| 1486059449  | Taxes                 | Business Taxes      | 2440           | 2282           | 2863           | 3711           | 4343           | 6013           | 5412           | 5204           | 4505           | 5299           | 5362           | 5857           | 5875           | 6049           | 5662           | 5938         | 6045         | 6247         | 6392         | 6596         | 
| 1486059449  | Taxes                 | Sales Tax           | 3360           | 3535           | 4018           | 4355           | 4418           | 4619           | 4868           | 4594           | 5059           | 5586           | 5812           | 6132           | 6494           | 6742           | 6911           | 7044         | 7564         | 7910         | 8289         | 8592         | 
| 1486059449  | Taxes                 | Other Taxes         | 2618           | 3017           | 3718           | 4546           | 5157           | 6154           | 5420           | 4099           | 3692           | 4241           | 4248           | 4985           | 5652           | 6368           | 7341           | 6550         | 6304         | 6386         | 6623         | 6734         | 
| 1486059449  | Miscellaneous Revenue | Licenses            | 47             | 46             | 45             | 47             | 50             | 46             | 53             | 49             | 56             | 57             | 64             | 65             | 80             | 81             | 91             | 95           | 67           | 67           | 71           | 66           | 
| 1486059449  | Miscellaneous Revenue | Permits             | 95             | 99             | 107            | 122            | 136            | 147            | 161            | 152            | 140            | 160            | 190            | 204            | 233            | 277            | 286            | 275          | 229          | 226          | 224          | 224          | 
| 1486059449  | Miscellaneous Revenue | Franchises          | 214            | 212            | 223            | 226            | 231            | 278            | 289            | 292            | 291            | 307            | 329            | 324            | 335            | 344            | 352            | 362          | 349          | 347          | 348          | 350          | 
| 1486059449  | Miscellaneous Revenue | Charges             | 461            | 501            | 592            | 614            | 606            | 613            | 638            | 687            | 746            | 776            | 850            | 872            | 951            | 974            | 1001           | 996          | 977          | 980          | 980          | 980          | 
| 1486059449  | Miscellaneous Revenue | Water & Sewer       | 858            | 846            | 885            | 899            | 990            | 1064           | 1202           | 1284           | 1540           | 1295           | 1373           | 1361           | 1491           | 1439           | 1297           | 1407         | 1361         | 1347         | 1336         | 1337         | 
```