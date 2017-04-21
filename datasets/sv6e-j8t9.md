# Revenue Comps

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/revenue-comps-4fcd3) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sv6e-j8t9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sv6e-j8t9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sv6e-j8t9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sv6e-j8t9 |
| Name | Revenue Comps |
| Attribution | Times Square Alliance (TSA) |
| Category | City Government |
| Tags | times square alliance, times square, crossroads, crossroads of the world, nyc, new york city, new york, manhattan, theater, food, screens, pedestrian, entertainment, tourism |
| Created | 2011-10-31T17:48:46Z |
| Publication Date | 2013-06-26T17:12:12Z |

## Description

Revenue statistics for Times Square

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                 | Data Type | Render Type |
| ======== | ============== | =================== | ==================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | times_square        | TIMES SQUARE         | text      | text        |
| Yes      | series tag     | dimensions          | Dimensions           | text      | text        |
| Yes      | numeric metric | sq_ft               | Sq Ft                | number    | number      |
| Yes      | series tag     | dec                 | DEC                  | text      | text        |
| Yes      | series tag     | impressions         | Impressions          | text      | text        |
| Yes      | series tag     | pricing_model       | Pricing Model        | text      | text        |
| Yes      | series tag     | unit_all_one_month_ | Unit (All One Month) | text      | text        |
| Yes      | numeric metric | total_minutes       | Total Minutes        | number    | number      |
| Yes      | numeric metric | rate                | Rate                 | number    | number      |
| Yes      | series tag     | full_motion_video   | Full Motion Video    | text      | text        |
| Yes      | series tag     | onsite_audio        | Onsite Audio         | text      | text        |
| Yes      | series tag     | advance_interactive | Advance Interactive  | text      | text        |
| Yes      | numeric metric | cpm                 | CPM                  | number    | number      |
| Yes      | numeric metric | cost_per_minute     | Cost Per Minute      | money     | money       |
| Yes      | numeric metric | cost_per_sf         | Cost Per SF          | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sv6e-j8t9 d:2011-10-31T10:48:48.000Z t:impressions=n/a t:dec=1500000 t:pricing_model="Duration 1 month" t:times_square="American Eagle" t:unit_all_one_month_="2 minutes/hour (19 hrs/day)" t:full_motion_video=yes t:onsite_audio=no m:cpm=1.5466666667 m:cost_per_minute=61.05 m:rate=69600 m:sq_ft=15000 m:total_minutes=1140 m:cost_per_sf=4.63

series e:sv6e-j8t9 d:2011-10-31T10:48:48.000Z t:unit_all_one_month_="4 minutes/hour (19 hrs/day)" t:full_motion_video=yes t:onsite_audio=no m:cpm=2.88 m:cost_per_minute=56.84 m:rate=129600 m:total_minutes=2280 m:cost_per_sf=8.64

series e:sv6e-j8t9 d:2011-10-31T10:48:48.000Z t:unit_all_one_month_="6 minutes/hour (19 hrs/day)" t:full_motion_video=yes t:onsite_audio=no m:cpm=4 m:cost_per_minute=52.63 m:rate=180000 m:total_minutes=3420 m:cost_per_sf=12
```

## Meta Commands

```ls
metric m:sq_ft p:integer l:"Sq Ft" t:dataTypeName=number

metric m:total_minutes p:integer l:"Total Minutes" t:dataTypeName=number

metric m:rate p:integer l:Rate t:dataTypeName=number

metric m:cpm p:double l:CPM t:dataTypeName=number

metric m:cost_per_minute p:double l:"Cost Per Minute" t:dataTypeName=money

metric m:cost_per_sf p:double l:"Cost Per SF" t:dataTypeName=money

entity e:sv6e-j8t9 l:"Revenue Comps" t:attribution="Times Square Alliance (TSA)" t:url=https://data.cityofnewyork.us/api/views/sv6e-j8t9

property e:sv6e-j8t9 t:meta.view v:id=sv6e-j8t9 v:category="City Government" v:averageRating=0 v:name="Revenue Comps" v:attribution="Times Square Alliance (TSA)"

property e:sv6e-j8t9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sv6e-j8t9 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | times_square                       | dimensions             | sq_ft | dec     | impressions | pricing_model    | unit_all_one_month_                                             | total_minutes | rate   | full_motion_video | onsite_audio | advance_interactive | cpm          | cost_per_minute | cost_per_sf | 
| =========== | ================================== | ====================== | ===== | ======= | =========== | ================ | =============================================================== | ============= | ====== | ================= | ============ | =================== | ============ | =============== | =========== | 
| 1320058128  | American Eagle                     |                        | 15000 | 1500000 | n/a         | Duration 1 month | 2 minutes/hour (19 hrs/day)                                     | 1140          | 69600  | yes               | no           |                     | 1.5466666667 | 61.05           | 4.63        | 
| 1320058128  |                                    |                        |       |         |             |                  | 4 minutes/hour (19 hrs/day)                                     | 2280          | 129600 | yes               | no           |                     | 2.88         | 56.84           | 8.64        | 
| 1320058128  |                                    |                        |       |         |             |                  | 6 minutes/hour (19 hrs/day)                                     | 3420          | 180000 | yes               | no           |                     | 4            | 52.63           | 12          | 
| 1320058128  | Sony/Fox Screen (Times Square 1)   | 35 x 40                | 1400  | 1600000 | n/a         | Duration 1 month | 2 minutes/hour (18 hrs/day)                                     | 1080          | 22500  | yes               | no           | no                  | 0.46875      | 20.83           | 16.07       | 
| 1320058128  | ABC Supersign                      |                        | 4630  | 1600000 | n/a         | Duration 1 month | 2 minutes/hour (15 hrs/day)                                     | 900           | 53000  | yes               | no           | no                  | 1.1041666667 | 58.88           | 11.44       | 
| 1320058128  | Times Square 2                     |                        | 17754 | 1600000 | n/a         | Duration 1 month | 3 min/hour (19 hrs/day) plus blackout below                     | 1710          | 103250 | yes               | no           |                     | 2.1510416667 | 60.38           | 5.81        | 
| 1320058128  | Nasdaq                             | 120 x 84               | 10080 |         |             |                  | Blackout periods 9-10am and 3:30 - 4:30 pm plus no coverage NYE |               |        |                   |              |                     |              |                 |             | 
| 1320058128  | Reuters                            | 7 boards various sizes | 7674  |         |             |                  | 3 min/hour (19 hrs/day)                                         |               |        |                   |              |                     |              |                 |             | 
| 1320058128  | W Hotel (Broadway and 47th Street) | 30 x 40                | 1200  | 1600000 | n/a         | Duration 1 month | 4 min/hour x 19 Hours/day                                       | 2280          | 70000  | yes               | no           |                     | 1.4583333333 | 30.70           | 58.33       | 
| 1320058128  |                                    |                        |       |         |             |                  | 8 min/hour x 19 Hours/day                                       | 4560          | 125000 | yes               |              |                     | 2.6041666667 | 27.41           | 104.16      | 
```