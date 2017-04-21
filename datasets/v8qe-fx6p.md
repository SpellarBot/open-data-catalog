# Times Square Hotels

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/times-square-hotels-64da0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/v8qe-fx6p) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/v8qe-fx6p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/v8qe-fx6p/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | v8qe-fx6p |
| Name | Times Square Hotels |
| Attribution | Times Square Alliance (TSA) |
| Category | Business |
| Tags | times square alliance, times square, crossroads, crossroads of the world, nyc, new york city, new york, manhattan, theater, food, screens, pedestrian, entertainment, tourism |
| Created | 2011-07-26T20:42:05Z |
| Publication Date | 2013-06-21T19:27:56Z |

## Description

Directory of hotels in the Times Square area Update schedule: As required

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | company_name | Company Name | text      | text        |
| Yes      | series tag  | phone        | Phone        | text      | text        |
| Yes      | series tag  | website      | Website      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:v8qe-fx6p d:2011-07-26T13:42:05.000Z t:phone="(212) 768-4400" t:website=http://www.millenniumhotelnyc.com/ t:company_name="Millennium Hotel" m:row_number.v8qe-fx6p=1

series e:v8qe-fx6p d:2011-07-26T13:42:05.000Z t:phone="(212) 246-8800" t:website=http://www.bestwestern.com t:company_name="Best Western President Hotel" m:row_number.v8qe-fx6p=2

series e:v8qe-fx6p d:2011-07-26T13:42:05.000Z t:phone="(212) 315-0100" t:website=www.novotel.com t:company_name=Novotel m:row_number.v8qe-fx6p=3
```

## Meta Commands

```ls
metric m:row_number.v8qe-fx6p p:long l:"Row Number"

entity e:v8qe-fx6p l:"Times Square Hotels" t:attribution="Times Square Alliance (TSA)" t:url=https://data.cityofnewyork.us/api/views/v8qe-fx6p

property e:v8qe-fx6p t:meta.view v:id=v8qe-fx6p v:category=Business v:averageRating=0 v:name="Times Square Hotels" v:attribution="Times Square Alliance (TSA)"

property e:v8qe-fx6p t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:v8qe-fx6p t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | company_name                 | phone          | website                                          | 
| =========== | ============================ | ============== | ================================================ | 
| 1311687725  | Millennium Hotel             | (212) 768-4400 | http://www.millenniumhotelnyc.com/               | 
| 1311687725  | Best Western President Hotel | (212) 246-8800 | http://www.bestwestern.com                       | 
| 1311687725  | Novotel                      | (212) 315-0100 | www.novotel.com                                  | 
| 1311687725  | Dream Hotel                  | (212) 247-2000 | http://www.dreamny.com/                          | 
| 1311687725  | W Hotel                      | (212) 930-7400 | http://www.starwoodhotels.com/whotels/index.html | 
| 1311687725  | Doubletree Guest Suites      | 2127191600     | www.nycdoubletreehotels.com                      | 
| 1311687725  | Stay Hotel                   | (212) 768-3700 |                                                  | 
| 1311687725  | Hotel 41 At Times Square     | (212) 703-8600 |                                                  | 
| 1311687725  | Time Hotel, The              | (877) 846-3692 | http://www.thetimeny.com/                        | 
| 1311687725  | Hilton Times Square          | (212) 642-2510 |                                                  | 
```