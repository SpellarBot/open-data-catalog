# Times Square Food & Beverage Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/times-square-food-beverage-locations-4a5ee) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kh2m-kcyz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kh2m-kcyz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kh2m-kcyz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kh2m-kcyz |
| Name | Times Square Food & Beverage Locations |
| Attribution | Times Square Alliance (TSA) |
| Category | Business |
| Tags | times square alliance, times square, crossroads, crossroads of the world, nyc, new york city, new york, manhattan, theater, food, screens, pedestrian, entertainment, tourism |
| Created | 2011-07-29T15:08:29Z |
| Publication Date | 2013-06-21T19:27:35Z |

## Description

Directory of food and beverage venues in the Times Square area

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | company_name    | Company Name    | text      | text        |
| Yes      | series tag  | subindustry     | Subindustry     | text      | text        |
| Yes      | series tag  | sub_subindustry | Sub Subindustry | text      | text        |
| Yes      | series tag  | phone           | Phone           | text      | text        |
| Yes      | series tag  | website         | Website         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kh2m-kcyz d:2011-07-29T08:08:30.000Z t:phone=212-239-0160 t:website=www.euorpacafe.com t:company_name="Europa Cafe" t:subindustry="Caf? / Deli" m:row_number.kh2m-kcyz=1

series e:kh2m-kcyz d:2011-07-29T08:08:30.000Z t:phone=2129561111 t:company_name="Ranch 1" t:subindustry="Quick Serve" t:sub_subindustry="Fast Food" m:row_number.kh2m-kcyz=2

series e:kh2m-kcyz d:2011-07-29T08:08:30.000Z t:phone="(212) 262-8282" t:website=http://www.sosaborella.com/ t:company_name="Sosa Borella" t:subindustry="Full Serve" t:sub_subindustry=Argentinian m:row_number.kh2m-kcyz=3
```

## Meta Commands

```ls
metric m:row_number.kh2m-kcyz p:long l:"Row Number"

entity e:kh2m-kcyz l:"Times Square Food & Beverage Locations" t:attribution="Times Square Alliance (TSA)" t:url=https://data.cityofnewyork.us/api/views/kh2m-kcyz

property e:kh2m-kcyz t:meta.view v:id=kh2m-kcyz v:category=Business v:averageRating=0 v:name="Times Square Food & Beverage Locations" v:attribution="Times Square Alliance (TSA)"

property e:kh2m-kcyz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kh2m-kcyz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | company_name                 | subindustry | sub_subindustry | phone          | website                     | 
| =========== | ============================ | =========== | =============== | ============== | =========================== | 
| 1311926910  | Europa Cafe                  | Caf? / Deli |                 | 212-239-0160   | www.euorpacafe.com          | 
| 1311926910  | Ranch 1                      | Quick Serve | Fast Food       | 2129561111     |                             | 
| 1311926910  | Sosa Borella                 | Full Serve  | Argentinian     | (212) 262-8282 | http://www.sosaborella.com/ | 
| 1311926910  | Mi Nidito (Cantina Mexicana) | Full Serve  | Mexican         | (212) 265-0022 |                             | 
| 1311926910  | Starbucks                    | Coffee      |                 | 2122467699     | www.starbucks.com           | 
| 1311926910  | China Gourmet                | Full Serve  | Chinese         | (212) 246-8181 |                             | 
| 1311926910  | Rino Trattoria               | Full Serve  | Italian         | (212) 307-0666 | www.rinotrattoria.com       | 
| 1311926910  | Laxmi Corp. Newsstand        | Caf? / Deli |                 |                |                             | 
| 1311926910  | Caffe Cielo                  | Full Serve  | Italian         | 212 246-9555   |                             | 
| 1311926910  | Cosmic Diner                 | Full Serve  | Diner           | 212 333-5888   |                             | 
```