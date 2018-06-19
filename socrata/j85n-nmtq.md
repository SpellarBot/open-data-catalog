# Managing for Results - State Department of Assessments and Taxation (SDAT)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/managing-for-results-state-department-of-assessments-and-taxation-sdat) |
| Metadata | [Link](https://data.maryland.gov/api/views/j85n-nmtq) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/j85n-nmtq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/j85n-nmtq/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | j85n-nmtq |
| Name | Managing for Results - State Department of Assessments and Taxation (SDAT) |
| Attribution | Department of Budget and Management (DBM) |
| Category | Business and Economy |
| Tags | managing for results, mfr, department of budget and management, dbm, state department of assessments and taxation, sdat, taxation, assessments, tax, property, properties, real estate, income tax, ... |
| Created | 2016-05-06T19:53:16Z |
| Publication Date | 2016-05-06T20:20:03Z |

## Description

This dataset contains data from the Department of Budget and Management as part of the Managing for Results (MFR) program. DBM collects these data for each state agency. The MFR data are published to the Open Data Portal by the Department of Information Technology (DoIT).

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | year        | Year       | text      | text        |
| Yes      | numeric metric | m101        | M101       | number    | number      |
| Yes      | numeric metric | m102        | M102       | number    | number      |
| Yes      | numeric metric | m103        | M103       | number    | number      |
| Yes      | numeric metric | m104        | M104       | number    | number      |
| Yes      | numeric metric | m105        | M105       | number    | number      |
| Yes      | numeric metric | m106        | M106       | number    | number      |
| Yes      | numeric metric | m107        | M107       | number    | number      |
| Yes      | numeric metric | m108        | M108       | percent   | percent     |
| Yes      | numeric metric | m201        | M201       | number    | number      |
| Yes      | numeric metric | m202        | M202       | number    | number      |
| Yes      | numeric metric | m203        | M203       | number    | number      |
| Yes      | numeric metric | m204        | M204       | number    | number      |
| Yes      | numeric metric | m205        | M205       | number    | number      |
| Yes      | numeric metric | m206        | M206       | money     | money       |
| Yes      | numeric metric | m301        | M301       | number    | number      |
| Yes      | numeric metric | m302        | M302       | number    | number      |
| Yes      | numeric metric | m303        | M303       | number    | number      |
| Yes      | numeric metric | m401        | M401       | number    | number      |
| Yes      | numeric metric | m402        | M402       | number    | number      |
| Yes      | numeric metric | m403        | M403       | number    | number      |
| Yes      | numeric metric | m404        | M404       | money     | money       |
| Yes      | numeric metric | m405        | M405       | number    | number      |
| Yes      | numeric metric | m406        | M406       | number    | number      |
| Yes      | numeric metric | m407        | M407       | money     | money       |
| Yes      | numeric metric | m501        | M501       | number    | number      |
| Yes      | numeric metric | m502        | M502       | percent   | percent     |
| Yes      | numeric metric | m503        | M503       | number    | number      |
| Yes      | numeric metric | m504        | M504       | percent   | percent     |
| Yes      | numeric metric | m505        | M505       | number    | number      |
| Yes      | numeric metric | m506        | M506       | percent   | percent     |
| Yes      | numeric metric | m507        | M507       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:j85n-nmtq d:2016-05-06T13:03:58.000Z t:year="2011 Act." m:m204=236000 m:m101=2176747 m:m203=9935 m:m303=2474.7 m:m206=3141 m:m103=90 m:m302=15193631 m:m205=132 m:m102=688.07 m:m404=1091 m:m301=854 m:m105=113626 m:m403=55.6 m:m104=287176 m:m402=50950 m:m107=346 m:m202=25 m:m106=13000 m:m201=145496 m:m108=91.2 m:m407=291 m:m406=2.4 m:m405=8388

series e:j85n-nmtq d:2016-05-06T13:03:58.000Z t:year="2012 Act." m:m204=242958 m:m101=2181619 m:m203=10068 m:m303=3125.5 m:m206=84631 m:m103=93.1 m:m302=16929681 m:m205=127 m:m102=654.38 m:m404=1190 m:m301=987 m:m105=118606 m:m403=62.6 m:m104=302955 m:m402=52594 m:m107=338 m:m202=25 m:m106=12700 m:m201=133122 m:m108=90 m:m407=321 m:m406=2.7 m:m405=8316

series e:j85n-nmtq d:2016-05-06T13:03:58.000Z t:year="2013 Act." m:m204=252093 m:m101=2190675 m:m203=10289 m:m303=2446.5 m:m206=43718 m:m103=91.3 m:m302=17046551 m:m205=123 m:m102=650.06 m:m404=1177 m:m301=808 m:m105=115841 m:m403=62.6 m:m104=307102 m:m402=53196 m:m107=327 m:m202=25 m:m106=12292 m:m201=158231 m:m108=84.4 m:m407=242 m:m406=2 m:m405=8249
```

## Meta Commands

```ls
metric m:m101 p:integer l:M101 t:dataTypeName=number

metric m:m102 p:float l:M102 t:dataTypeName=number

metric m:m103 p:double l:M103 t:dataTypeName=number

metric m:m104 p:integer l:M104 t:dataTypeName=number

metric m:m105 p:integer l:M105 t:dataTypeName=number

metric m:m106 p:integer l:M106 t:dataTypeName=number

metric m:m107 p:integer l:M107 t:dataTypeName=number

metric m:m108 p:float l:M108 t:dataTypeName=percent

metric m:m201 p:integer l:M201 t:dataTypeName=number

metric m:m202 p:integer l:M202 t:dataTypeName=number

metric m:m203 p:integer l:M203 t:dataTypeName=number

metric m:m204 p:integer l:M204 t:dataTypeName=number

metric m:m205 p:integer l:M205 t:dataTypeName=number

metric m:m206 p:integer l:M206 t:dataTypeName=money

metric m:m301 p:integer l:M301 t:dataTypeName=number

metric m:m302 p:integer l:M302 t:dataTypeName=number

metric m:m303 p:float l:M303 t:dataTypeName=number

metric m:m401 p:integer l:M401 t:dataTypeName=number

metric m:m402 p:integer l:M402 t:dataTypeName=number

metric m:m403 p:float l:M403 t:dataTypeName=number

metric m:m404 p:double l:M404 t:dataTypeName=money

metric m:m405 p:integer l:M405 t:dataTypeName=number

metric m:m406 p:float l:M406 t:dataTypeName=number

metric m:m407 p:integer l:M407 t:dataTypeName=money

metric m:m501 p:integer l:M501 t:dataTypeName=number

metric m:m502 p:float l:M502 t:dataTypeName=percent

metric m:m503 p:integer l:M503 t:dataTypeName=number

metric m:m504 p:float l:M504 t:dataTypeName=percent

metric m:m505 p:integer l:M505 t:dataTypeName=number

metric m:m506 p:float l:M506 t:dataTypeName=percent

metric m:m507 p:float l:M507 t:dataTypeName=number

entity e:j85n-nmtq l:"Managing for Results - State Department of Assessments and Taxation (SDAT)" t:attribution="Department of Budget and Management (DBM)" t:url=https://data.maryland.gov/api/views/j85n-nmtq

property e:j85n-nmtq t:meta.view v:id=j85n-nmtq v:category="Business and Economy" v:attributionLink=http://dbm.maryland.gov/pages/default.aspx v:averageRating=0 v:name="Managing for Results - State Department of Assessments and Taxation (SDAT)" v:attribution="Department of Budget and Management (DBM)"

property e:j85n-nmtq t:meta.view.license v:name="Public Domain"

property e:j85n-nmtq t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:j85n-nmtq t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | year      | m101    | m102   | m103 | m104   | m105   | m106  | m107 | m108 | m201   | m202 | m203  | m204   | m205 | m206  | m301 | m302     | m303   | m401  | m402  | m403 | m404   | m405 | m406 | m407 | m501  | m502 | m503  | m504 | m505  | m506 | m507 | 
| =========== | ========= | ======= | ====== | ==== | ====== | ====== | ===== | ==== | ==== | ====== | ==== | ===== | ====== | ==== | ===== | ==== | ======== | ====== | ===== | ===== | ==== | ====== | ==== | ==== | ==== | ===== | ==== | ===== | ==== | ===== | ==== | ==== | 
| 1462539838  | 2011 Act. | 2176747 | 688.07 | 90   | 287176 | 113626 | 13000 | 346  | 91.2 | 145496 | 25   | 9935  | 236000 | 132  | 3141  | 854  | 15193631 | 2474.7 |       | 50950 | 55.6 | 1091.0 | 8388 | 2.4  | 291  |       |      |       |      |       |      |      | 
| 1462539838  | 2012 Act. | 2181619 | 654.38 | 93.1 | 302955 | 118606 | 12700 | 338  | 90.0 | 133122 | 25   | 10068 | 242958 | 127  | 84631 | 987  | 16929681 | 3125.5 |       | 52594 | 62.6 | 1190.0 | 8316 | 2.7  | 321  |       |      |       |      |       |      |      | 
| 1462539838  | 2013 Act. | 2190675 | 650.06 | 91.3 | 307102 | 115841 | 12292 | 327  | 84.4 | 158231 | 25   | 10289 | 252093 | 123  | 43718 | 808  | 17046551 | 2446.5 |       | 53196 | 62.6 | 1177.0 | 8249 | 2.0  | 242  |       |      |       |      |       |      |      | 
| 1462539838  | 2015 Act. | 2221358 | 675.50 | 93   | 311000 | 121000 | 12000 | 322  | 85.0 | 162278 | 25   | 10805 | 297732 | 136  | 54848 | 785  | 13467195 | 2503.0 | 64951 | 48713 | 59.5 | 1221.0 | 7838 | 2.4  | 306  | 85000 | 30.0 | 46000 | 89.1 | 90376 | 78.2 | 57.2 | 
| 1462539838  | 2016 Est. | 2230000 | 680.00 | 95   | 313000 | 123000 | 12000 | 323  | 85.0 | 165000 | 25   | 10531 | 262238 | 138  | 40000 | 816  | 16300000 | 2998.0 | 68199 | 53800 | 61.6 | 1171.0 | 8942 | 2.7  | 302  | 85000 | 40.0 | 47000 | 90.0 | 90000 | 85.0 | 40   | 
| 1462539838  | 2017 Est. | 2235000 | 690.00 | 95   | 315000 | 125000 | 12000 | 324  | 85.0 | 165000 | 25   | 10343 | 257551 | 140  | 40000 | 788  | 19686423 | 2837.0 | 71609 | 55855 | 63.3 | 1205.0 | 7700 | 1.9  | 247  | 87000 | 50.0 | 49000 | 90.0 | 90000 | 90.0 | 35   | 
| 1462540319  | 2014 Act. | 2214221 | 660.61 | 92.3 | 309000 | 119000 | 8635  | 318  | 79.5 | 149164 | 25   | 10619 | 262297 | 139  | 27425 | 788  | 13691411 | 2173.2 | 68517 | 50872 | 61.6 | 1218.0 | 8112 | 2.4  | 296  | 81414 | 22.5 | 43839 | 86.8 | 95181 |      | 46.9 | 
```