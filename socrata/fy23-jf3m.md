# Insurance Companies Authorized For Surety

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/insurance-companies-authorized-for-surety-a1b3e) |
| Metadata | [Link](https://data.iowa.gov/api/views/fy23-jf3m) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/fy23-jf3m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/fy23-jf3m/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | fy23-jf3m |
| Name | Insurance Companies Authorized For Surety |
| Category | Government |
| Tags | surety |
| Created | 2017-01-30T20:18:02Z |
| Publication Date | 2017-01-30T20:19:50Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | iowa_company_number | Iowa Company Number | text      | number      |
| Yes      | series tag  | naic_number         | NAIC Number         | text      | text        |
| Yes      | series tag  | phone               | Phone               | text      | text        |
| Yes      | series tag  | company_name        | Company Name        | text      | text        |
| No       |             | address             | Address             | text      | text        |
| Yes      | series tag  | city                | City                | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | zip                 | ZIP                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:fy23-jf3m d:2017-01-30T20:18:04.000Z t:zip=19803 t:phone=800-245-2425 t:company_name="21st Century Centennial Insurance Company" t:state=DE t:iowa_company_number=2093 t:naic_number=34789 t:city=Wilmington m:row_number.fy23-jf3m=1

series e:fy23-jf3m d:2017-01-30T20:18:04.000Z t:zip=19803 t:phone=800-245-2425 t:company_name="21st Century Indemnity Insurance Company" t:state=DE t:iowa_company_number=2648 t:naic_number=43974 t:city=Wilmington m:row_number.fy23-jf3m=2

series e:fy23-jf3m d:2017-01-30T20:18:04.000Z t:zip=19803 t:phone=800-245-2425 t:company_name="21st Century National Insurance Company" t:state=DE t:iowa_company_number=2711 t:naic_number=36587 t:city=Wilmington m:row_number.fy23-jf3m=3
```

## Meta Commands

```ls
metric m:row_number.fy23-jf3m p:long l:"Row Number"

entity e:fy23-jf3m l:"Insurance Companies Authorized For Surety" t:url=https://data.iowa.gov/api/views/fy23-jf3m

property e:fy23-jf3m t:meta.view v:id=fy23-jf3m v:category=Government v:averageRating=0 v:name="Insurance Companies Authorized For Surety"

property e:fy23-jf3m t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:fy23-jf3m t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| :updated_at | iowa_company_number | naic_number | phone        | company_name                                 | address                                  | city       | state | zip        | 
| =========== | =================== | =========== | ============ | ============================================ | ======================================== | ========== | ===== | ========== | 
| 1485807484  | 2093                | 34789       | 800-245-2425 | 21st Century Centennial Insurance Company    | 21st Century Plaza, 3 Beaver Valley Road | Wilmington | DE    | 19803      | 
| 1485807484  | 2648                | 43974       | 800-245-2425 | 21st Century Indemnity Insurance Company     | 21st Century Plaza, 3 Beaver Valley Road | Wilmington | DE    | 19803      | 
| 1485807484  | 2711                | 36587       | 800-245-2425 | 21st Century National Insurance Company      | 21st Century Plaza, 3 Beaver Valley Road | Wilmington | DE    | 19803      | 
| 1485807484  | 1962                | 32220       | 800-245-2425 | 21st Century North America Insurance Company | 21st Century Plaza, 3 Beaver Valley Road | Wilmington | DE    | 19803      | 
| 1485807484  | 1434                | 23795       | 800-245-2425 | 21st Century Pacific Insurance Company       | 21st Century Plaza, 3 Beaver Valley Road | Wilmington | DE    | 19803-1115 | 
| 1485807484  | 745                 | 20796       | 800-245-2425 | 21st Century Premier Insurance Company       | 21st Century Plaza, 3 Beaver Valley Road | Wilmington | DE    | 19803      | 
| 1485807484  | 1931                | 23833       | 800-245-2425 | 21st Century Security Insurance Company      | 21st Century Plaza, 3 Beaver Valley Road | Wilmington | DE    | 19803      | 
| 1485807484  | 2994                | 12304       | 866-206-5851 | Accident Fund General Insurance Company      | PO Box 40790                             | Lansing    | MI    | 48901-7990 | 
| 1485807484  | 2870                | 10166       | 866-206-5851 | Accident Fund Insurance Company of America   | PO Box 40790                             | Lansing    | MI    | 48901-7990 | 
| 1485807484  | 2995                | 12305       | 866-206-5851 | Accident Fund National Insurance Company     | PO Box 40790                             | Lansing    | MI    | 48901-7990 | 
```