# Multipurpose Senior Center Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/multipurpose-senior-center-locations-3915f) |
| Metadata | [Link](https://data.lacity.org/api/views/qf8m-dzta) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/qf8m-dzta/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/qf8m-dzta/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | qf8m-dzta |
| Name | Multipurpose Senior Center Locations |
| Attribution | Department of Aging |
| Category | A Prosperous City |
| Tags | senior citizen, service, meals, transportation, assistance, mpc, multipurpose center |
| Created | 2014-05-30T17:59:38Z |
| Publication Date | 2014-05-30T19:52:51Z |

## Description

Location of Multipurpose Senior Centers in the City of Los Angeles

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | numeric metric | index                 | Index                 | number    | number      |
| Yes      | series tag     | senior_center_name    | Senior Center Name    | text      | text        |
| No       |                | senior_center_address | Senior Center Address | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = senior_center_address
```

## Data Commands

```ls
series e:qf8m-dzta d:2014-05-30T10:59:41.000Z t:senior_center_name="Int'l Institute of LA Multipurpose Senior Ctr" m:index=1

series e:qf8m-dzta d:2014-05-30T10:59:41.000Z t:senior_center_name="ONEgeneration Senior Enrichment Ctr" m:index=4

series e:qf8m-dzta d:2014-05-30T10:59:41.000Z t:senior_center_name="West Adams Multipurpose Senior Ctr" m:index=6
```

## Meta Commands

```ls
metric m:index p:integer l:Index t:dataTypeName=number

entity e:qf8m-dzta l:"Multipurpose Senior Center Locations" t:attribution="Department of Aging" t:url=https://data.lacity.org/api/views/qf8m-dzta

property e:qf8m-dzta t:meta.view v:id=qf8m-dzta v:category="A Prosperous City" v:averageRating=0 v:name="Multipurpose Senior Center Locations" v:attribution="Department of Aging"

property e:qf8m-dzta t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qf8m-dzta t:meta.view.owner v:id=hhg6-ygkh v:profileImageUrlMedium=/api/users/hhg6-ygkh/profile_images/THUMB v:profileImageUrlLarge=/api/users/hhg6-ygkh/profile_images/LARGE v:screenName="Aging OpenData" v:profileImageUrlSmall=/api/users/hhg6-ygkh/profile_images/TINY v:displayName="Aging OpenData"

property e:qf8m-dzta t:meta.view.tableauthor v:id=hhg6-ygkh v:profileImageUrlMedium=/api/users/hhg6-ygkh/profile_images/THUMB v:profileImageUrlLarge=/api/users/hhg6-ygkh/profile_images/LARGE v:screenName="Aging OpenData" v:profileImageUrlSmall=/api/users/hhg6-ygkh/profile_images/TINY v:roleName=publisher v:displayName="Aging OpenData"
```

## Top Records

```ls
| :updated_at | index | senior_center_name                            | senior_center_address                        | 
| =========== | ===== | ============================================= | ============================================ | 
| 1401447581  | 1     | Int'l Institute of LA Multipurpose Senior Ctr | 435 S. Boyle Ave, Los Angeles, CA 90033      | 
| 1401447581  | 4     | ONEgeneration Senior Enrichment Ctr           | 18255 Victory Blvd., Reseda, CA 91335        | 
| 1401447581  | 6     | West Adams Multipurpose Senior Ctr            | 2528 West Blvd., Los Angeles, CA 90016       | 
| 1401447581  | 7     | Alicia Broadus-Duncan Multipurpose Senior Ctr | 11300 Glenoaks Blvd., Pacoima, CA 91331      | 
| 1401447581  | 9     | Southeast Valley Multipurpose Senior Ctr      | 5056 Van Nuys Blvd., Sherman Oaks, CA 91403  | 
| 1401447581  | 11    | James Wood Memorial Community Center (SRO)    | 400 E. 5th St., Los Angeles, CA 90013        | 
| 1401447581  | 12    | Hollywood Multipurpose Senior Center          | 1745 N. Gramercy Pl., Hollywood, CA 90028    | 
| 1401447581  | 14    | Bradley Multipurpose Senior Ctr               | 10957 S. Central Ave., Los Angeles, CA 90059 | 
| 1401447581  | 15    | Theresa Lindsay Multipurpose Senior Ctr       | 429 E. 42nd Pl., Los Angeles, CA 90011       | 
| 1401447581  | 16    | Wilmington Jaycees Foundation Inc.            | 1371 N. Eubank Ave., Wilmington, CA 90744    | 
```