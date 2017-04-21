# Managing for Results - Department of Budget & Management (DBM)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/managing-for-results-department-of-budget-management-dbm) |
| Metadata | [Link](https://data.maryland.gov/api/views/fw4a-f33r) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/fw4a-f33r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/fw4a-f33r/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | fw4a-f33r |
| Name | Managing for Results - Department of Budget & Management (DBM) |
| Attribution | Department of Budget and Management (DBM) |
| Category | Budget |
| Tags | managing for results, mfr, department of budget and management, dbm, budget, workforce, debt, capital budget, retention |
| Created | 2016-04-01T20:01:23Z |
| Publication Date | 2016-04-01T20:05:53Z |

## Description

This dataset contains data from the Department of Budget and Management as part of the Managing for Results (MFR) program. DBM collects these data for each state agency. This dataset contains DBM's own MFR data specifically. Additional datasets are available on the Open Data Portal for DBM's MFR data on other state agencies.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | year        | Year       | text      | text        |
| Yes      | numeric metric | m101        | M101       | percent   | percent     |
| Yes      | numeric metric | m102        | M102       | percent   | percent     |
| Yes      | numeric metric | m103        | M103       | percent   | percent     |
| Yes      | numeric metric | m104        | M104       | percent   | percent     |
| Yes      | numeric metric | m105        | M105       | percent   | percent     |
| Yes      | numeric metric | m106        | M106       | percent   | percent     |
| Yes      | numeric metric | m107        | M107       | percent   | percent     |
| Yes      | numeric metric | m108        | M108       | percent   | percent     |
| Yes      | numeric metric | m109        | M109       | percent   | percent     |
| Yes      | numeric metric | m110        | M110       | percent   | percent     |
| Yes      | numeric metric | m111        | M111       | percent   | percent     |
| Yes      | numeric metric | m112        | M112       | percent   | percent     |
| Yes      | numeric metric | m201        | M201       | money     | money       |
| Yes      | numeric metric | m202        | M202       | percent   | percent     |
| Yes      | numeric metric | m203        | M203       | percent   | percent     |
| Yes      | numeric metric | m301        | M301       | percent   | percent     |
| Yes      | numeric metric | m302        | M302       | money     | money       |
| Yes      | numeric metric | m303        | M303       | money     | money       |
| Yes      | numeric metric | m401        | M401       | number    | number      |
| Yes      | numeric metric | m402        | M402       | percent   | percent     |
| Yes      | numeric metric | m403        | M403       | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fw4a-f33r d:2016-04-01T13:01:28.000Z t:year="2011 Act." m:m101=50 m:m103=89 m:m303=0.17 m:m102=88 m:m302=0.16 m:m105=83 m:m301=81 m:m104=98 m:m403=82 m:m107=99 m:m111=70 m:m402=86 m:m106=10 m:m112=100 m:m201=7086705 m:m401=133.39 m:m109=55 m:m110=67 m:m108=62

series e:fw4a-f33r d:2016-04-01T13:01:28.000Z t:year="2012 Act." m:m101=48 m:m103=91 m:m303=0.16 m:m102=88 m:m302=0.16 m:m301=86 m:m104=98 m:m403=89 m:m107=94 m:m111=63 m:m402=94 m:m106=7 m:m112=100 m:m201=8187638 m:m401=128.04 m:m109=58 m:m110=67 m:m108=53

series e:fw4a-f33r d:2016-04-01T13:01:28.000Z t:year="2013 Act." m:m101=38 m:m103=91 m:m303=0.15 m:m102=89 m:m302=0.14 m:m105=88 m:m301=82 m:m104=98 m:m403=84 m:m107=87 m:m111=69 m:m402=90 m:m106=15 m:m112=100 m:m201=5798710 m:m401=125.36 m:m109=61 m:m110=64 m:m108=55
```

## Meta Commands

```ls
metric m:m101 p:integer l:M101 t:dataTypeName=percent

metric m:m102 p:integer l:M102 t:dataTypeName=percent

metric m:m103 p:integer l:M103 t:dataTypeName=percent

metric m:m104 p:integer l:M104 t:dataTypeName=percent

metric m:m105 p:integer l:M105 t:dataTypeName=percent

metric m:m106 p:integer l:M106 t:dataTypeName=percent

metric m:m107 p:integer l:M107 t:dataTypeName=percent

metric m:m108 p:integer l:M108 t:dataTypeName=percent

metric m:m109 p:integer l:M109 t:dataTypeName=percent

metric m:m110 p:integer l:M110 t:dataTypeName=percent

metric m:m111 p:integer l:M111 t:dataTypeName=percent

metric m:m112 p:integer l:M112 t:dataTypeName=percent

metric m:m201 p:integer l:M201 t:dataTypeName=money

metric m:m202 p:integer l:M202 t:dataTypeName=percent

metric m:m203 p:integer l:M203 t:dataTypeName=percent

metric m:m301 p:integer l:M301 t:dataTypeName=percent

metric m:m302 p:double l:M302 t:dataTypeName=money

metric m:m303 p:double l:M303 t:dataTypeName=money

metric m:m401 p:double l:M401 t:dataTypeName=number

metric m:m402 p:integer l:M402 t:dataTypeName=percent

metric m:m403 p:integer l:M403 t:dataTypeName=percent

entity e:fw4a-f33r l:"Managing for Results - Department of Budget & Management (DBM)" t:attribution="Department of Budget and Management (DBM)" t:url=https://data.maryland.gov/api/views/fw4a-f33r

property e:fw4a-f33r t:meta.view v:id=fw4a-f33r v:category=Budget v:attributionLink=http://dbm.maryland.gov/pages/default.aspx v:averageRating=0 v:name="Managing for Results - Department of Budget & Management (DBM)" v:attribution="Department of Budget and Management (DBM)"

property e:fw4a-f33r t:meta.view.license v:name="Public Domain"

property e:fw4a-f33r t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:fw4a-f33r t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | year      | m101 | m102 | m103 | m104 | m105 | m106 | m107 | m108 | m109 | m110 | m111 | m112 | m201    | m202 | m203 | m301 | m302 | m303 | m401   | m402 | m403 | 
| =========== | ========= | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ======= | ==== | ==== | ==== | ==== | ==== | ====== | ==== | ==== | 
| 1459515688  | 2011 Act. | 50   | 88   | 89   | 98   | 83   | 10   | 99   | 62   | 55   | 67   | 70   | 100  | 7086705 |      |      | 81   | 0.16 | 0.17 | 133.39 | 86   | 82   | 
| 1459515688  | 2012 Act. | 48   | 88   | 91   | 98   |      | 7    | 94   | 53   | 58   | 67   | 63   | 100  | 8187638 |      |      | 86   | 0.16 | 0.16 | 128.04 | 94   | 89   | 
| 1459515688  | 2013 Act. | 38   | 89   | 91   | 98   | 88   | 15   | 87   | 55   | 61   | 64   | 69   | 100  | 5798710 |      |      | 82   | 0.14 | 0.15 | 125.36 | 90   | 84   | 
| 1459515688  | 2014 Act. | 38   | 81   | 90   | 98   | 85   | 16   | 96   | 54   | 64   | 84   | 64   | 100  | 5519901 |      |      | 78   | 0.12 | 0.13 | 126.06 | 77   | 82   | 
| 1459515688  | 2015 Act. | 45   | 90   | 90   | 94   |      | 15   | 94   | 61   | 69   | 82   | 67   | 100  | 4851628 | 27   | 30   | 75   |      |      | 135.49 | 82   | 94   | 
| 1459515688  | 2016 Est. | 50   | 90   | 91   | 96   | 86   | 15   | 90   | 55   | 69   | 82   | 68   | 100  | 2295000 | 29   | 32   | 80   |      |      | 136    | 82   | 89   | 
| 1459515688  | 2017 Est. | 50   | 90   | 91   | 96   | 87   | 15   | 90   | 55   | 69   | 82   | 68   | 100  | 6482000 | 30   | 33   | 80   |      |      | 136    | 90   | 90   | 
```