# View Bid Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/view-bid-results-9e367) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ym3h-nmfi) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ym3h-nmfi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ym3h-nmfi/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ym3h-nmfi |
| Name | View Bid Results |
| Created | 2014-12-01T22:07:46Z |
| Publication Date | 2015-01-08T20:58:35Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type     | Render Type   |
| ======== | =========== | =========== | ========== | ============= | ============= |
| No       | time        | :updated_at | updated_at | meta_data     | meta_data     |
| No       |             | bid_open    | Bid Open   | calendar_date | calendar_date |
| Yes      | series tag  | project     | Project    | text          | text          |
| Yes      | series tag  | job         | Job#       | text          | text          |
| Yes      | series tag  | results     | Results    | url           | url           |
| Yes      | series tag  | sublisting  | Sublisting | url           | url           |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = bid_open
```

## Data Commands

```ls
series e:ym3h-nmfi d:2015-01-08T12:58:06.000Z t:project="STATE CAPITOL BUILDING - 5TH FLOOR EXTERIOR WALL REPLACEMENT & EXTERIOR REPAIRS" t:results=http://pwd.hawaii.gov/wp-content/uploads/2014/12/141218_0758a.pdf t:sublisting=http://pwd.hawaii.gov/wp-content/uploads/2014/12/141218_0758b.pdf t:job=12-10-0758 m:row_number.ym3h-nmfi=1

series e:ym3h-nmfi d:2015-01-08T12:58:06.000Z t:project="MAUI VETERANS CEMETERY - EXPANSION AND IMPROVEMENTS" t:results=http://pwd.hawaii.gov/wp-content/uploads/2014/12/141120_7509a.pdf t:sublisting=http://pwd.hawaii.gov/wp-content/uploads/2014/12/141120_7509b.pdf t:job=15-14-7509 m:row_number.ym3h-nmfi=2

series e:ym3h-nmfi d:2015-01-08T12:58:06.000Z t:project="MARITIME WIRELESS NETWORK SYSTEM - KAUNAKAKAI HARBOR, NETWORK INFRASTRUCTURE" t:results=http://pwd.hawaii.gov/wp-content/uploads/2014/12/141113_7588a.pdf t:sublisting=http://pwd.hawaii.gov/wp-content/uploads/2014/12/141113_7588b.pdf t:job=25-14-7588 m:row_number.ym3h-nmfi=3
```

## Meta Commands

```ls
metric m:row_number.ym3h-nmfi p:long l:"Row Number"

entity e:ym3h-nmfi l:"View Bid Results" t:url=https://data.hawaii.gov/api/views/ym3h-nmfi

property e:ym3h-nmfi t:meta.view v:id=ym3h-nmfi v:averageRating=0 v:name="View Bid Results"

property e:ym3h-nmfi t:meta.view.owner v:id=ck4w-i5dk v:profileImageUrlMedium=/api/users/ck4w-i5dk/profile_images/THUMB v:profileImageUrlLarge=/api/users/ck4w-i5dk/profile_images/LARGE v:screenName=sojiri v:profileImageUrlSmall=/api/users/ck4w-i5dk/profile_images/TINY v:displayName=sojiri

property e:ym3h-nmfi t:meta.view.tableauthor v:id=ck4w-i5dk v:profileImageUrlMedium=/api/users/ck4w-i5dk/profile_images/THUMB v:profileImageUrlLarge=/api/users/ck4w-i5dk/profile_images/LARGE v:screenName=sojiri v:profileImageUrlSmall=/api/users/ck4w-i5dk/profile_images/TINY v:roleName=publisher v:displayName=sojiri
```

## Top Records

```ls
| :updated_at | bid_open | project                                                                         | job        | results                                                                   | sublisting                                                                | 
| =========== | ======== | =============================================================================== | ========== | ========================================================================= | ========================================================================= | 
| 1420721886  |          | STATE CAPITOL BUILDING - 5TH FLOOR EXTERIOR WALL REPLACEMENT & EXTERIOR REPAIRS | 12-10-0758 | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/141218_0758a.pdf, null] | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/141218_0758b.pdf, null] | 
| 1420721886  |          | MAUI VETERANS CEMETERY - EXPANSION AND IMPROVEMENTS                             | 15-14-7509 | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/141120_7509a.pdf, null] | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/141120_7509b.pdf, null] | 
| 1420721886  |          | MARITIME WIRELESS NETWORK SYSTEM - KAUNAKAKAI HARBOR, NETWORK INFRASTRUCTURE    | 25-14-7588 | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/141113_7588a.pdf, null] | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/141113_7588b.pdf, null] | 
| 1420721886  |          | KEAHOLE KONA INTERNATIONAL AIRPORT - IMPROVEMENTS TO BLIND VENDOR FACILITIES    | 21-33-7532 | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140710_7532a.pdf, null] | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140710_7532b.pdf, null] | 
| 1420721886  |          | HAWAII STATE HOSPITAL - ROADWAY IMPROVEMENTS, PHASE II                          | 12-20-2666 | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140626_2666a.pdf, null] | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140626_2666b.pdf, null] | 
| 1420721886  |          | HAWAII STATE HOSPITAL - SYSTEM-WIDE EMERGENCY GENERATORS                        | 12-20-2662 | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140626_2662a.pdf, null] | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140626_2662b.pdf, null] | 
| 1420721886  |          | KING KALAKAUA, HOOPONO, & STATE CAPITOL BUILDINGS - BLIND VENDOR FACILITY IMPS  | 22-33-7521 | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140626_7521a.pdf, null] | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140626_7521b.pdf, null] | 
| 1420721886  |          | WAIMANO RIDGE, ULUAKUPU - INTERIOR RENOVATION & MECHANICAL SYSTEM IMPROVEMENTS  | 12-20-2661 | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140626_2661a.pdf, null] | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140626_2661b.pdf, null] | 
| 1420721886  |          | ALOHA STADIUM - HEALTH AND SAFETY IMPROVEMENTS, PHASE 3                         | 12-10-0736 | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140620_0736a.pdf, null] | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140620_0736b.pdf, null] | 
| 1420721886  |          | KAAHUMANU HALE - ROOF AND LANAI UPGRADES AND IMPROVEMENTS                       | 12-21-7491 | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140620_7491a.pdf, null] | [http://pwd.hawaii.gov/wp-content/uploads/2014/12/140620_7491b.pdf, null] | 
```