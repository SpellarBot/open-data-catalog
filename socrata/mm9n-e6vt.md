# 311 Closure Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-closure-rates) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/mm9n-e6vt) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/mm9n-e6vt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/mm9n-e6vt/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | mm9n-e6vt |
| Name | 311 Closure Rates |
| Attribution | City of Jackson - 311 |
| Tags | 311 |
| Created | 2016-03-14T13:09:40Z |
| Publication Date | 2016-04-11T14:26:11Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | division_department | Division/Department | text          | text          |
| Yes      | numeric metric | calls_closed        | Calls Closed        | number        | number        |
| Yes      | numeric metric | calls_received      | Calls Received      | number        | number        |
| Yes      | numeric metric | closure_rate        | Closure Rate        | percent       | percent       |
| Yes      | time           | as_of_date          | As of Date:         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = as_of_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:mm9n-e6vt d:2016-04-09T00:00:00.000Z t:division_department=311 m:calls_closed=156 m:calls_received=120 m:closure_rate=130

series e:mm9n-e6vt d:2016-04-01T00:00:00.000Z t:division_department="Bridges & Drainage" m:calls_closed=401 m:calls_received=647 m:closure_rate=61.98

series e:mm9n-e6vt d:2016-04-11T00:00:00.000Z t:division_department="Care & Maintenance" m:calls_closed=691 m:calls_received=694 m:closure_rate=99.57
```

## Meta Commands

```ls
metric m:calls_closed p:integer l:"Calls Closed" t:dataTypeName=number

metric m:calls_received p:integer l:"Calls Received" t:dataTypeName=number

metric m:closure_rate p:double l:"Closure Rate" t:dataTypeName=percent

entity e:mm9n-e6vt l:"311 Closure Rates" t:attribution="City of Jackson - 311" t:url=https://data.jacksonms.gov/api/views/mm9n-e6vt

property e:mm9n-e6vt t:meta.view v:id=mm9n-e6vt v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="311 Closure Rates" v:attribution="City of Jackson - 311"

property e:mm9n-e6vt t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:mm9n-e6vt t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| division_department                                                                         | calls_closed | calls_received | closure_rate | as_of_date          | 
| =========================================================================================== | ============ | ============== | ============ | =================== | 
| 311                                                                                         | 156          | 120            | 130          | 2016-04-09T00:00:00 | 
| Bridges & Drainage                                                                          | 401          | 647            | 61.98        | 2016-04-01T00:00:00 | 
| Care & Maintenance                                                                          | 691          | 694            | 99.57        | 2016-04-11T00:00:00 | 
| Code Services                                                                               | 23           | 6              | 383          | 2016-04-02T00:00:00 | 
| Community Improvement                                                                       | 138          | 121            | 114          | 2016-04-12T00:00:00 | 
| Engineering                                                                                 | 0            | 4              | 0            | 2016-04-01T00:00:00 | 
| Fire                                                                                        | 6            | 1              | 600          | 2016-04-04T00:00:00 | 
| Human & Cultural                                                                            | 0            | 0              | 100          | 2016-04-02T00:00:00 | 
| Infrastructure Management                                                                   | 33           | 47             | 70           | 2016-04-04T00:00:00 | 
| JATRAN                                                                                      | 34           | 33             | 103          | 2016-04-05T00:00:00 | 
```