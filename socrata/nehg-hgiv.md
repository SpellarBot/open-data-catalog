# Early Voting Locations - 2016 March 15 Presidential Primary Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/early-voting-locations-2016-march-15-presidential-primary-election) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/nehg-hgiv) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nehg-hgiv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nehg-hgiv/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | nehg-hgiv |
| Name | Early Voting Locations - 2016 March 15 Presidential Primary Election |
| Attribution | Cook County Clerk |
| Category | Finance & Administration |
| Tags | elections, voting, vote, early voting |
| Created | 2016-03-04T18:26:00Z |
| Publication Date | 2016-03-04T18:34:21Z |

## Description

This dataset details the hours and locations for early voting for those living in suburban Cook County for the March 15, 2016 Presidential Primary Election. For more information on Early Voting see http://www.cookcountyclerk.com/elections/earlyvoting/Pages/default.aspx .

## Columns

```ls
| Included | Schema Type    | Field Name    | Name            | Data Type | Render Type |
| ======== | ============== | ============= | =============== | ========= | =========== |
| Yes      | series tag     | location      | Location        | text      | text        |
| Yes      | series tag     | hours_weekday | Hours ? Weekday | text      | text        |
| Yes      | series tag     | hours_weekend | Hours ? Weekend | text      | text        |
| No       |                | address       | Address         | text      | text        |
| Yes      | series tag     | city          | City            | text      | text        |
| Yes      | series tag     | zip           | Zip             | text      | text        |
| Yes      | series tag     | phone         | Phone           | text      | text        |
| Yes      | numeric metric | lon           | Lon             | number    | number      |
| No       |                | lat           | Lat             | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address,lat
```

## Data Commands

```ls
series e:nehg-hgiv d:2016-01-01T00:00:00.000Z t:zip=60402 t:phone="(708) 788-2660" t:hours_weekday="9 am - 5 pm" t:location="Berwyn City Hall" t:hours_weekend="Saturday 9 am - 5 pm     Sunday not open" t:city=Berwyn m:lon=-87.7912701018

series e:nehg-hgiv d:2016-01-01T00:00:00.000Z t:zip=60010 t:phone="(847) 551-3000" t:hours_weekday="9 am - 5 pm" t:location="Barrington Hills Village Hall" t:hours_weekend="Saturday 9 am - 5 pm     Sunday not open" t:city="Barrington Hills" m:lon=-88.1813585014

series e:nehg-hgiv d:2016-01-01T00:00:00.000Z t:zip=60827 t:phone="(708) 385-0264" t:hours_weekday="9 am - 5 pm" t:location="Calumet Township Comm Center" t:hours_weekend="Saturday 9 am - 5 pm     Sunday not open" t:city="Calumet Park" m:lon=-87.6605632483
```

## Meta Commands

```ls
metric m:lon p:double l:Lon t:dataTypeName=number

entity e:nehg-hgiv l:"Early Voting Locations - 2016 March 15 Presidential Primary Election" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/nehg-hgiv

property e:nehg-hgiv t:meta.view v:id=nehg-hgiv v:category="Finance & Administration" v:attributionLink=http://www.cookcountyclerk.com v:averageRating=0 v:name="Early Voting Locations - 2016 March 15 Presidential Primary Election" v:attribution="Cook County Clerk"

property e:nehg-hgiv t:meta.view.license v:name="Public Domain"

property e:nehg-hgiv t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:nehg-hgiv t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| location                      | hours_weekday                                      | hours_weekend                           | address                | city             | zip   | phone          | lon            | lat           | 
| ============================= | ================================================== | ======================================= | ====================== | ================ | ===== | ============== | ============== | ============= | 
| Berwyn City Hall              | 9 am - 5 pm                                        | Saturday 9 am - 5 pm Sunday not open    | 6700 26th Street       | Berwyn           | 60402 | (708) 788-2660 | -87.7912701018 | 41.843036394  | 
| Barrington Hills Village Hall | 9 am - 5 pm                                        | Saturday 9 am - 5 pm Sunday not open    | 112 Algonquin Road     | Barrington Hills | 60010 | (847) 551-3000 | -88.1813585014 | 42.1132913894 | 
| Calumet Township Comm Center  | 9 am - 5 pm                                        | Saturday 9 am - 5 pm Sunday not open    | 12633 Ashland Avenue   | Calumet Park     | 60827 | (708) 385-0264 | -87.6605632483 | 41.6639808861 | 
| Lemont Township Hall          | 9 am - 5 pm                                        | Saturday 9 am - 5 pm Sunday not open    | 1115 Warner Avenue     | Lemont           | 60439 | (630)-257-2522 | -88.0015067772 | 41.6593926392 | 
| Cicero Public Safety Office   | 9 am - 5 pm(feb 29 - Mar 4) 9am-7pm(Mar 7 - 11,14) | Saturday 9 am - 5 pm Sunday 9 am - 3 pm | 5410 34th Street       | Cicero           | 60804 | (708) 656-3600 | -87.7597074564 | 41.8313074274 | 
| Centennial Park               | 9 am - 5 pm                                        | Saturday 9 am - 5 pm Sunday not open    | 2300 Old Glenview Road | Wilmette         | 60091 | (847) 256-9666 | -87.733018897  | 42.0696604559 | 
| Glenview Village Hall         | 9 am - 5 pm                                        | Saturday 9 am - 5 pm Sunday not open    | 2500 E Lake Avenue     | Glenview         | 60025 | (847) 904-4370 | -87.8225854359 | 42.0783113657 | 
| Norridge Village Hall         | 9 am - 5 pm                                        | Saturday 9 am - 5 pm Sunday not open    | 4000 N. Olcott Avenue  | Norridge         | 60706 | (708) 453-0800 | -87.8149076613 | 41.9528580614 | 
| Melrose Park Village Hall     | 9 am - 5 pm                                        | Saturday 9 am - 5 pm Sunday not open    | 1000 North 25th Avenue | Melrose Park     | 60160 | (708) 343-4000 | -87.8651242099 | 41.8965015731 | 
| Park Forest Village Hall      | 9 am - 5 pm                                        | Saturday 9 am - 5 pm Sunday not open    | 350 Victory Boulevard  | Park Forest      | 60466 | (708) 748-1112 | -87.6786859377 | 41.4799441538 | 
```