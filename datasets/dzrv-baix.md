# Elected officials

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/elected-officials) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/dzrv-baix) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/dzrv-baix/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/dzrv-baix/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | dzrv-baix |
| Name | Elected officials |
| Attribution | King County Archives |
| Category | Operations |
| Created | 2016-03-17T23:25:44Z |
| Publication Date | 2016-04-15T17:07:11Z |

## Description

All elected officials in the history of King County

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | elected_official | Elected official | text      | text        |
| Yes      | series tag  | position         | Position         | text      | text        |
| Yes      | time        | start_year       | Start year       | number    | number      |
| No       |             | end_year         | End year         | number    | number      |
```

## Time Field

```ls
Value = start_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = end_year
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:dzrv-baix l:"Elected officials" t:attribution="King County Archives" t:url=https://data.kingcounty.gov/api/views/dzrv-baix

property e:dzrv-baix t:meta.view v:id=dzrv-baix v:category=Operations v:attributionLink=http://kingcounty.gov/depts/records-licensing/archives/ v:averageRating=0 v:name="Elected officials" v:attribution="King County Archives"

property e:dzrv-baix t:meta.view.license v:name="Public Domain"

property e:dzrv-baix t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:dzrv-baix t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| elected_official       | position           | start_year | end_year | 
| ====================== | ================== | ========== | ======== | 
| Boyle, Charles E.      | 3rd District Judge | 1888       | 1888     | 
| Burke, Thomas          | 3rd District Judge | 1888       | 1889     | 
| Chenoweth, Francis A.  | 3rd District Judge | 1855       | 1855     | 
| Chenoweth, Francis A.  | 3rd District Judge | 1856       | 1856     | 
| Darwin, Charles B.     | 3rd District Judge | 1866       | 1868     | 
| Dennison, Benjamin F.  | 3rd District Judge | 1868       | 1869     | 
| Greene, Roger S.       | 3rd District Judge | 1879       | 1887     | 
| Hanford, Cornelius H.  | 3rd District Judge | 1889       | 1889     | 
| Hewitt, Christopher C. | 3rd District Judge | 1864       | 1864     | 
| Hewitt, Christopher C. | 3rd District Judge | 1865       | 1865     | 
```