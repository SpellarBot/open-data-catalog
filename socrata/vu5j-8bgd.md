# Superior Court Records from microfiche

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/superior-court-records-from-microfiche-54ff5) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/vu5j-8bgd) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/vu5j-8bgd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/vu5j-8bgd/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | vu5j-8bgd |
| Name | Superior Court Records from microfiche |
| Attribution | Department of Judicial Administration (King County Superior Court Clerk) |
| Category | Records |
| Tags | civil, criminal, domestic general defendant, general paintiff, probate, microfiche, superior court, download |
| Created | 2013-12-06T23:06:01Z |
| Publication Date | 2016-07-22T17:47:59Z |

## Description

Index and download location for King County Superior Court civil, criminal, domestic general defendant, general paintiff, and probate records from microfiche

## Columns

```ls
| Included | Schema Type    | Field Name      | Name              | Data Type | Render Type |
| ======== | ============== | =============== | ================= | ========= | =========== |
| No       | time           | :updated_at     | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | type            | Type              | text      | text        |
| Yes      | series tag     | years           | Years             | text      | text        |
| Yes      | series tag     | name_in_index   | Indexes           | url       | url         |
| Yes      | numeric metric | file_size_in_mb | File size (in MB) | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vu5j-8bgd d:2016-03-08T13:04:06.000Z t:years="1968 through 1971" t:type="Domestic record" t:name_in_index=http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_1_aa_az.pdf m:file_size_in_mb=52

series e:vu5j-8bgd d:2016-03-08T13:04:06.000Z t:years="1968 through 1971" t:type="Domestic record" t:name_in_index=http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_2_24_baa_biz.pdf m:file_size_in_mb=53

series e:vu5j-8bgd d:2016-03-08T13:04:06.000Z t:years="1968 through 1971" t:type="Domestic record" t:name_in_index=http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_2a_ba_bat.pdf m:file_size_in_mb=10
```

## Meta Commands

```ls
metric m:file_size_in_mb p:integer l:"File size (in MB)" t:dataTypeName=number

entity e:vu5j-8bgd l:"Superior Court Records from microfiche" t:attribution="Department of Judicial Administration (King County Superior Court Clerk)" t:url=https://data.kingcounty.gov/api/views/vu5j-8bgd

property e:vu5j-8bgd t:meta.view v:id=vu5j-8bgd v:category=Records v:attributionLink=http://www.kingcounty.gov/courts/Clerk v:averageRating=0 v:name="Superior Court Records from microfiche" v:attribution="Department of Judicial Administration (King County Superior Court Clerk)"

property e:vu5j-8bgd t:meta.view.license v:name="Public Domain"

property e:vu5j-8bgd t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:vu5j-8bgd t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | type            | years             | name_in_index                                                                                                                                          | file_size_in_mb | 
| =========== | =============== | ================= | ====================================================================================================================================================== | =============== | 
| 1457442246  | Domestic record | 1968 through 1971 | [http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_1_aa_az.pdf, AA_AZ]         | 52              | 
| 1457442246  | Domestic record | 1968 through 1971 | [http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_2_24_baa_biz.pdf, BAA_BIZ]  | 53              | 
| 1457442246  | Domestic record | 1968 through 1971 | [http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_2a_ba_bat.pdf, BA_BAT]      | 10              | 
| 1457442246  | Domestic record | 1968 through 1971 | [http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_2b_bat_bee.pdf, BAT_BEE]    | 9               | 
| 1457442246  | Domestic record | 1968 through 1971 | [http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_2c_bee_ber.pdf, BEE_BER]    | 9               | 
| 1457442246  | Domestic record | 1968 through 1971 | [http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_2d_ber_bis.pdf, BER_BIS]    | 9               | 
| 1457442246  | Domestic record | 1968 through 1971 | [http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_3_bj_buq.pdf, BJ_BUQ]       | 45              | 
| 1457442246  | Domestic record | 1968 through 1971 | [http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_4_by_clark.pdf, BY_CLARK]   | 44              | 
| 1457442246  | Domestic record | 1968 through 1971 | [http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_5_clark_dak.pdf, CLARK_DAK] | 46              | 
| 1457442246  | Domestic record | 1968 through 1971 | [http://www.kingcounty.gov/~/media/courts/Clerk/microfiche/Domestic_Indexes_-_QCd/Domestic_1968-1971/Domestic_1968_1971_Pg_6_daa_dz.pdf, DAA_DZ]       | 46              | 
```