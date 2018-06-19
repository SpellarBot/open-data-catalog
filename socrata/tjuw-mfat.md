# NYC Budget Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-budget-revenue) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tjuw-mfat) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tjuw-mfat/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tjuw-mfat/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tjuw-mfat |
| Name | NYC Budget Revenue |
| Category | City Government |
| Tags | budget, open data, office of management and budget (omb) |
| Created | 2015-07-21T20:38:21Z |
| Publication Date | 2015-07-21T20:43:48Z |

## Description

NYC Budget Revenue

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | category       | Category       | text      | text        |
| Yes      | series tag  | fy_2002_actual | FY 2002 Actual | text      | text        |
| Yes      | series tag  | fy_2003_actual | FY 2003 Actual | text      | text        |
| Yes      | series tag  | fy_2004_actual | FY 2004 Actual | text      | text        |
| Yes      | series tag  | fy_2005_actual | FY 2005 Actual | text      | text        |
| Yes      | series tag  | fy_2006_actual | FY 2006 Actual | text      | text        |
| Yes      | series tag  | fy_2007_actual | FY 2007 Actual | text      | text        |
| Yes      | series tag  | fy_2008_actual | FY 2008 Actual | text      | text        |
| Yes      | series tag  | fy_2009_actual | FY 2009 Actual | text      | text        |
| Yes      | series tag  | fy_2010_actual | FY 2010 Actual | text      | text        |
| Yes      | series tag  | fy_2011_actual | FY 2011 Actual | text      | text        |
| Yes      | series tag  | fy_2012_actual | FY 2012 Actual | text      | text        |
| Yes      | series tag  | fy_2013_actual | FY 2013 Actual | text      | text        |
| Yes      | series tag  | fy_2014_actual | FY 2014 Actual | text      | text        |
| Yes      | series tag  | fy_2015_plan   | FY 2015 Plan   | text      | text        |
| Yes      | series tag  | fy_2016_plan   | FY 2016 Plan   | text      | text        |
| Yes      | series tag  | fy_2017_plan   | FY 2017 Plan   | text      | text        |
| Yes      | series tag  | fy_2018_plan   | FY 2018 Plan   | text      | text        |
| Yes      | series tag  | fy_2019_plan   | FY 2019 Plan   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tjuw-mfat d:2015-07-21T13:38:40.000Z t:fy_2002_actual="* 8,761" t:fy_2013_actual="* 18,970" t:fy_2018_plan="* 24,705" t:fy_2015_plan="* 21,471" t:fy_2016_plan="* 22,589" t:fy_2009_actual="* 14,487" t:fy_2010_actual="* 16,369" t:fy_2005_actual="* 11,616" t:fy_2012_actual="* 18,158" t:category="Real Property Tax" t:fy_2007_actual="* 13,123" t:fy_2019_plan="* 25,769" t:fy_2017_plan="* 23,697" t:fy_2003_actual="* 10,063" t:fy_2006_actual="* 12,636" t:fy_2008_actual="* 13,204" t:fy_2014_actual="* 20,202" t:fy_2004_actual="* 11,582" t:fy_2011_actual="* 17,086" m:row_number.tjuw-mfat=1

series e:tjuw-mfat d:2015-07-21T13:38:40.000Z t:fy_2002_actual="* 4,990" t:fy_2013_actual="* 9,778" t:fy_2018_plan="* 11,439" t:fy_2015_plan="* 11,148" t:fy_2016_plan="* 11,154" t:fy_2009_actual="* 7,627" t:fy_2010_actual="* 7,576" t:fy_2005_actual="* 7,135" t:fy_2012_actual="* 8,531" t:category="Personal Income Tax" t:fy_2007_actual="* 8,618" t:fy_2019_plan="* 11,780" t:fy_2017_plan="* 11,203" t:fy_2003_actual="* 5,000" t:fy_2006_actual="* 8,007" t:fy_2008_actual="* 9,861" t:fy_2014_actual="* 10,152" t:fy_2004_actual="* 6,093" t:fy_2011_actual="* 8,138" m:row_number.tjuw-mfat=2

series e:tjuw-mfat d:2015-07-21T13:38:40.000Z t:fy_2002_actual="* 2,440" t:fy_2013_actual="* 5,857" t:fy_2018_plan="* 6,560" t:fy_2015_plan="* 6,083" t:fy_2016_plan="* 6,134" t:fy_2009_actual="* 5,204" t:fy_2010_actual="* 4,505" t:fy_2005_actual="* 3,711" t:fy_2012_actual="* 5,362" t:category="Business Taxes" t:fy_2007_actual="* 6,013" t:fy_2019_plan="* 6,791" t:fy_2017_plan="* 6,369" t:fy_2003_actual="* 2,282" t:fy_2006_actual="* 4,343" t:fy_2008_actual="* 5,412" t:fy_2014_actual="* 5,875" t:fy_2004_actual="* 2,863" t:fy_2011_actual="* 5,299" m:row_number.tjuw-mfat=3
```

## Meta Commands

```ls
metric m:row_number.tjuw-mfat p:long l:"Row Number"

entity e:tjuw-mfat l:"NYC Budget Revenue" t:url=https://data.cityofnewyork.us/api/views/tjuw-mfat

property e:tjuw-mfat t:meta.view v:id=tjuw-mfat v:category="City Government" v:averageRating=0 v:name="NYC Budget Revenue"

property e:tjuw-mfat t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tjuw-mfat t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | category                           | fy_2002_actual | fy_2003_actual | fy_2004_actual | fy_2005_actual | fy_2006_actual | fy_2007_actual | fy_2008_actual | fy_2009_actual | fy_2010_actual | fy_2011_actual | fy_2012_actual | fy_2013_actual | fy_2014_actual | fy_2015_plan | fy_2016_plan | fy_2017_plan | fy_2018_plan | fy_2019_plan | 
| =========== | ================================== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============== | ============ | ============ | ============ | ============ | ============ | 
| 1437485920  | Real Property Tax                  | * 8,761        | * 10,063       | * 11,582       | * 11,616       | * 12,636       | * 13,123       | * 13,204       | * 14,487       | * 16,369       | * 17,086       | * 18,158       | * 18,970       | * 20,202       | * 21,471     | * 22,589     | * 23,697     | * 24,705     | * 25,769     | 
| 1437485920  | Personal Income Tax                | * 4,990        | * 5,000        | * 6,093        | * 7,135        | * 8,007        | * 8,618        | * 9,861        | * 7,627        | * 7,576        | * 8,138        | * 8,531        | * 9,778        | * 10,152       | * 11,148     | * 11,154     | * 11,203     | * 11,439     | * 11,780     | 
| 1437485920  | Business Taxes                     | * 2,440        | * 2,282        | * 2,863        | * 3,711        | * 4,343        | * 6,013        | * 5,412        | * 5,204        | * 4,505        | * 5,299        | * 5,362        | * 5,857        | * 5,875        | * 6,083      | * 6,134      | * 6,369      | * 6,560      | * 6,791      | 
| 1437485920  | Sales Tax                          | * 3,360        | * 3,535        | * 4,018        | * 4,355        | * 4,418        | * 4,619        | * 4,868        | * 4,594        | * 5,059        | * 5,586        | * 5,812        | * 6,132        | * 6,494        | * 6,756      | * 7,026      | * 7,320      | * 7,617      | * 7,886      | 
| 1437485920  | Other Taxes                        | * 2,618        | * 3,017        | * 3,718        | * 4,546        | * 5,157        | * 6,154        | * 5,420        | * 4,099        | * 3,692        | * 4,241        | * 4,248        | * 4,985        | * 5,652        | * 6,289      | * 5,316      | * 5,615      | * 5,753      | * 5,874      | 
| 1437485920  | Miscellaneous Revenues             | * 3,739        | * 4,648        | * 3,370        | * 5,074        | * 3,862        | * 4,243        | * 5,044        | * 4,627        | * 4,690        | * 4,388        | * 5,247        | * 4,657        | * 5,622        | * 6,306      | * 4,770      | * 4,921      | * 5,011      | * 5,075      | 
| 1437485920  | Unrestricted Intergovernmental Aid | * 666          | * 1,443        | * 963          | * 603          | * 494          | * 35           | * 242          | * 327          | * (18)         | * 39           | * 25           | 0.0            | * 1            | 0.0          | 0.0          | 0.0          | 0.0          | 0.0          | 
| 1437485920  | Disallowance of Categorical Grants | 0.0            | * (47)         | * (27)         | * (87)         | * (542)        | * (103)        | * (114)        | 0.0            | 0.0            | * (112)        | * 166          | * (59)         | * (18)         | * (15)       | * (15)       | * (15)       | * (15)       | * (15)       | 
| 1437485920  | Federal Categorical Grants         | * 6,097        | * 5,618        | * 5,415        | * 6,654        | * 5,243        | * 5,471        | * 5,692        | * 5,941        | * 7,716        | * 7,877        | * 7,178        | * 8,620        | * 6,962        | * 8,448      | * 7,146      | * 6,878      | * 6,475      | * 6,375      | 
| 1437485920  | State Categorical Grants           | * 8,030        | * 8,317        | * 8,454        | * 8,823        | * 9,586        | * 10,185       | * 11,421       | * 12,124       | * 11,645       | * 11,255       | * 11,114       | * 11,027       | * 10,916       | * 12,575     | * 12,977     | * 13,349     | * 13,755     | * 14,083     | 
```