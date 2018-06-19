# BSS - Pavement Preservation YTD 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bss-pavement-preservation-ytd-2014-63536) |
| Metadata | [Link](https://data.lacity.org/api/views/h63n-bpd9) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/h63n-bpd9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/h63n-bpd9/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | h63n-bpd9 |
| Name | BSS - Pavement Preservation YTD 2014 |
| Created | 2014-05-30T21:54:24Z |
| Publication Date | 2014-05-30T22:00:03Z |

## Description

Progress towards achieving 240 centerline miles in 2014

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | time           | date                       | Date                       | calendar_date | calendar_date |
| No       |                | date_name                  | Date Name                  | text          | text          |
| Yes      | numeric metric | ytd_percent_complete       | YTD Percent Complete       | percent       | percent       |
| Yes      | numeric metric | planned_trajectory         | Planned Trajectory         | percent       | percent       |
| Yes      | numeric metric | deviation                  | Deviation                  | percent       | percent       |
| Yes      | numeric metric | centerline_miles_completed | Centerline Miles Completed | number        | number        |
| Yes      | numeric metric | target                     | Target                     | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_name
```

## Data Commands

```ls
series e:h63n-bpd9 d:2013-12-31T00:00:00.000Z m:ytd_percent_complete=47 m:deviation=-3 m:target=123 m:centerline_miles_completed=115 m:planned_trajectory=50

series e:h63n-bpd9 d:2014-01-31T00:00:00.000Z m:ytd_percent_complete=54 m:deviation=-4 m:target=142 m:centerline_miles_completed=132 m:planned_trajectory=58

series e:h63n-bpd9 d:2014-02-28T00:00:00.000Z m:ytd_percent_complete=63 m:deviation=-4 m:target=164 m:centerline_miles_completed=154 m:planned_trajectory=67
```

## Meta Commands

```ls
metric m:ytd_percent_complete p:integer l:"YTD Percent Complete" t:dataTypeName=percent

metric m:planned_trajectory p:integer l:"Planned Trajectory" t:dataTypeName=percent

metric m:deviation p:integer l:Deviation t:dataTypeName=percent

metric m:centerline_miles_completed p:integer l:"Centerline Miles Completed" t:dataTypeName=number

metric m:target p:integer l:Target t:dataTypeName=number

entity e:h63n-bpd9 l:"BSS - Pavement Preservation YTD 2014" t:url=https://data.lacity.org/api/views/h63n-bpd9

property e:h63n-bpd9 t:meta.view v:id=h63n-bpd9 v:averageRating=0 v:name="BSS - Pavement Preservation YTD 2014"

property e:h63n-bpd9 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:h63n-bpd9 t:meta.view.owner v:id=df4s-jhab v:profileImageUrlMedium=/api/users/df4s-jhab/profile_images/THUMB v:profileImageUrlLarge=/api/users/df4s-jhab/profile_images/LARGE v:screenName="Public Works: Street Services OpenData" v:profileImageUrlSmall=/api/users/df4s-jhab/profile_images/TINY v:displayName="Public Works: Street Services OpenData"

property e:h63n-bpd9 t:meta.view.tableauthor v:id=df4s-jhab v:profileImageUrlMedium=/api/users/df4s-jhab/profile_images/THUMB v:profileImageUrlLarge=/api/users/df4s-jhab/profile_images/LARGE v:screenName="Public Works: Street Services OpenData" v:profileImageUrlSmall=/api/users/df4s-jhab/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Street Services OpenData"
```

## Top Records

```ls
| date                | date_name | ytd_percent_complete | planned_trajectory | deviation | centerline_miles_completed | target | 
| =================== | ========= | ==================== | ================== | ========= | ========================== | ====== | 
| 2013-12-31T00:00:00 | Dec       | 47                   | 50                 | -3        | 115                        | 123    | 
| 2014-01-31T00:00:00 | Jan       | 54                   | 58                 | -4        | 132                        | 142    | 
| 2014-02-28T00:00:00 | Feb       | 63                   | 67                 | -4        | 154                        | 164    | 
| 2014-03-31T00:00:00 | Mar       | 74                   | 75                 | -1        | 181                        | 184    | 
| 2014-04-30T00:00:00 | Apr       | 87                   | 83                 | 4         | 212                        | 203    | 
| 2014-05-31T00:00:00 | May       |                      | 92                 |           |                            | 225    | 
| 2014-06-30T00:00:00 | Jun       |                      | 100                |           |                            | 245    | 
```