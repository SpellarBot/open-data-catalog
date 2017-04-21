# Commission on Human Rights - 2011 Monthly Summary on Human Rights

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commission-on-human-rights-2011-monthly-summary-on-human-rights-85e35) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/cf62-jpr3) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cf62-jpr3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cf62-jpr3/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | cf62-jpr3 |
| Name | Commission on Human Rights - 2011 Monthly Summary on Human Rights |
| Attribution | Cook County Commission on Human Rights |
| Category | Finance & Administration |
| Created | 2011-10-14T18:46:45Z |
| Publication Date | 2014-10-09T22:18:02Z |

## Description

Updated 11/1/2011. Human Rights Monthly Activities on New Complaints Filed,  Investigations Closed, Other Closures, Training Seminars, Employees Trained,  Inquiries, Commission Hearings and Conciliations and Inquiries.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | activity   | Activity   | text      | text        |
| Yes      | numeric metric | dec        | DEC        | number    | number      |
| Yes      | numeric metric | jan        | JAN        | number    | number      |
| Yes      | numeric metric | feb        | FEB        | number    | number      |
| Yes      | numeric metric | mar        | MAR        | number    | number      |
| Yes      | numeric metric | apr        | APR        | number    | number      |
| Yes      | numeric metric | may        | MAY        | number    | number      |
| Yes      | numeric metric | jun        | JUN        | number    | number      |
| Yes      | numeric metric | jul        | JUL        | number    | number      |
| Yes      | numeric metric | aug        | AUG        | number    | number      |
| Yes      | numeric metric | sep        | SEP        | number    | number      |
| Yes      | numeric metric | oct        | OCT        | number    | number      |
| Yes      | numeric metric | nov        | NOV        | number    | number      |
| Yes      | numeric metric | ytd_totals | YTD Totals | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cf62-jpr3 d:2011-01-01T00:00:00.000Z t:activity="HR New Complaints Filed" m:may=3 m:apr=5 m:dec=2 m:feb=1 m:jul=4 m:sep=8 m:jun=2 m:jan=9 m:mar=4 m:aug=3 m:ytd_totals=41

series e:cf62-jpr3 d:2011-01-01T00:00:00.000Z t:activity="Investigations Closed" m:may=3 m:apr=5 m:dec=11 m:feb=6 m:jul=3 m:sep=7 m:jun=6 m:jan=11 m:mar=8 m:aug=2 m:ytd_totals=62

series e:cf62-jpr3 d:2011-01-01T00:00:00.000Z t:activity="Other Closures" m:may=0 m:apr=0 m:dec=1 m:feb=0 m:jul=0 m:sep=0 m:jun=1 m:jan=0 m:mar=0 m:aug=1 m:ytd_totals=3
```

## Meta Commands

```ls
metric m:dec p:integer l:DEC t:dataTypeName=number

metric m:jan p:integer l:JAN t:dataTypeName=number

metric m:feb p:integer l:FEB t:dataTypeName=number

metric m:mar p:integer l:MAR t:dataTypeName=number

metric m:apr p:integer l:APR t:dataTypeName=number

metric m:may p:integer l:MAY t:dataTypeName=number

metric m:jun p:integer l:JUN t:dataTypeName=number

metric m:jul p:integer l:JUL t:dataTypeName=number

metric m:aug p:integer l:AUG t:dataTypeName=number

metric m:sep p:integer l:SEP t:dataTypeName=number

metric m:oct p:long l:OCT t:dataTypeName=number

metric m:nov p:long l:NOV t:dataTypeName=number

metric m:ytd_totals p:integer l:"YTD Totals" t:dataTypeName=number

entity e:cf62-jpr3 l:"Commission on Human Rights - 2011 Monthly Summary on Human Rights" t:attribution="Cook County Commission on Human Rights" t:url=https://datacatalog.cookcountyil.gov/api/views/cf62-jpr3

property e:cf62-jpr3 t:meta.view v:id=cf62-jpr3 v:category="Finance & Administration" v:averageRating=0 v:name="Commission on Human Rights - 2011 Monthly Summary on Human Rights" v:attribution="Cook County Commission on Human Rights"

property e:cf62-jpr3 t:meta.view.license v:name="Public Domain"

property e:cf62-jpr3 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:cf62-jpr3 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| activity                              | dec | jan | feb | mar | apr | may | jun | jul | aug | sep | oct | nov | ytd_totals | 
| ===================================== | === | === | === | === | === | === | === | === | === | === | === | === | ========== | 
| HR New Complaints Filed               | 2   | 9   | 1   | 4   | 5   | 3   | 2   | 4   | 3   | 8   |     |     | 41         | 
| Investigations Closed                 | 11  | 11  | 6   | 8   | 5   | 3   | 6   | 3   | 2   | 7   |     |     | 62         | 
| Other Closures                        | 1   | 0   | 0   | 0   | 0   | 0   | 1   | 0   | 1   | 0   |     |     | 3          | 
| Training Seminars                     |     | 1   | 2   | 1   | 3   | 0   | 4   | 0   | 1   | 4   |     |     | 16         | 
| Employees Trained                     | 0   | 22  | 26  | 27  | 346 | 0   | 550 | 0   | 30  | 140 |     |     | 1141       | 
| Commission Hearings and Conciliations | 1   | 1   | 0   | 2   | 0   | 0   | 2   | 0   | 2   | 0   |     |     | 8          | 
| Inquiries                             | 39  | 34  | 28  | 31  | 48  | 34  | 29  | 38  | 47  | 37  |     |     | 365        | 
```