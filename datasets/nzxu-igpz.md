# Maryland Funding FY10 Payments Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-funding-fy10-payments-data-7193d) |
| Metadata | [Link](https://data.maryland.gov/api/views/nzxu-igpz) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/nzxu-igpz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/nzxu-igpz/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | nzxu-igpz |
| Name | Maryland Funding FY10 Payments Data |
| Attribution | Maryland Department of Budget and Management; Maryland Department of Information Technology |
| Category | Budget |
| Tags | spending, budget, vendor, payments |
| Created | 2013-01-18T17:37:29Z |
| Publication Date | 2014-08-22T15:54:09Z |

## Description

Summary information of payments to vendors that received $25,000 or more in a respective fiscal year as available on spending.dbm.maryland.gov website.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | text        |
| Yes      | series tag     | agency_name | Agency Name | text      | text        |
| Yes      | series tag     | vendor_name | Vendor Name | text      | text        |
| Yes      | series tag     | vendor_zip  | Vendor Zip  | text      | text        |
| Yes      | numeric metric | amount      | Amount      | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nzxu-igpz d:2010-01-01T00:00:00.000Z t:vendor_zip=20735 t:agency_name="STATE HIGHWAY ADMIN" t:vendor_name="M & M TRUCKING LLC" m:amount=34917.5

series e:nzxu-igpz d:2010-01-01T00:00:00.000Z t:vendor_zip=60122 t:agency_name="MILITARY DEPARTMENT" t:vendor_name=GALLS m:amount=4486.27

series e:nzxu-igpz d:2010-01-01T00:00:00.000Z t:vendor_zip=68103 t:agency_name="STATE HIGHWAY ADMIN" t:vendor_name="TELVENT DTN" m:amount=94994.13
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:nzxu-igpz l:"Maryland Funding FY10 Payments Data" t:attribution="Maryland Department of Budget and Management; Maryland Department of Information Technology" t:url=https://data.maryland.gov/api/views/nzxu-igpz

property e:nzxu-igpz t:meta.view v:id=nzxu-igpz v:category=Budget v:attributionLink=http://www.spending.dbm.maryland.gov v:averageRating=0 v:name="Maryland Funding FY10 Payments Data" v:attribution="Maryland Department of Budget and Management; Maryland Department of Information Technology"

property e:nzxu-igpz t:meta.view.license v:name="Public Domain"

property e:nzxu-igpz t:meta.view.owner v:id=kkuv-jqse v:screenName="Teri Greene" v:displayName="Teri Greene"

property e:nzxu-igpz t:meta.view.tableauthor v:id=kkuv-jqse v:screenName="Teri Greene" v:roleName=editor v:displayName="Teri Greene"
```

## Top Records

```ls
| year | agency_name                   | vendor_name                 | vendor_zip | amount     | 
| ==== | ============================= | =========================== | ========== | ========== | 
| 2010 | STATE HIGHWAY ADMIN           | M & M TRUCKING LLC          | 20735      | 34917.5    | 
| 2010 | MILITARY DEPARTMENT           | GALLS                       | 60122      | 4486.27    | 
| 2010 | STATE HIGHWAY ADMIN           | TELVENT DTN                 | 68103      | 94994.13   | 
| 2010 | DEPARTMENT OF HUMAN RESOURCES | MARITA PETERS               | 21701      | 5415.39    | 
| 2010 | STATE HIGHWAY ADMIN           | METRO GROUND COVERS         | 20871      | 70400      | 
| 2010 | MD DEPARTMENT OF PLANNING     | FREDERICK COMMUNITY COLLEGE | 21702      | 9100       | 
| 2010 | STATE TREASURER'S OFFICE      | DOURON INC                  | 21117      | 498.3      | 
| 2010 | STATE HIGHWAY ADMIN           | HARBEL INC                  | 21501      | 1248393.07 | 
| 2010 | MARYLAND DEPT. OF AGING       | UPPER SHORE AGING INC       | 21620      | 1510056.25 | 
| 2010 | DEPARTMENT OF HUMAN RESOURCES | THRESHOLD SERVICES INC      | 20910      | 189        | 
```