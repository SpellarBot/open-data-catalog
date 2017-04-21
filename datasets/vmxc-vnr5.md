# Commission on Women's Issues--2011 Summary of Workshops and Attendees by Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commission-on-womens-issues-2011-summary-of-workshops-and-attendees-by-month-d2533) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/vmxc-vnr5) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/vmxc-vnr5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/vmxc-vnr5/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | vmxc-vnr5 |
| Name | Commission on Women's Issues--2011 Summary of Workshops and Attendees by Month |
| Attribution | Cook County Commission on Women's Issues |
| Category | Finance & Administration |
| Created | 2011-10-14T19:39:51Z |
| Publication Date | 2014-10-09T22:14:18Z |

## Description

This File contains information on Women's Outreach and Workshops. Plus the Number of Attendees that were present for each workshop

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
series e:vmxc-vnr5 d:2011-01-01T00:00:00.000Z t:activity="Outreach & Workshops" m:may=2 m:apr=2 m:dec=0 m:oct=0 m:feb=1 m:nov=0 m:jul=0 m:sep=1 m:jun=1 m:jan=0 m:mar=1 m:aug=1 m:ytd_totals=9

series e:vmxc-vnr5 d:2011-01-01T00:00:00.000Z t:activity="Number of Attendees" m:may=75 m:apr=100 m:dec=0 m:oct=0 m:feb=75 m:nov=0 m:jul=0 m:sep=200 m:jun=50 m:jan=0 m:mar=100 m:aug=100 m:ytd_totals=700
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

metric m:oct p:integer l:OCT t:dataTypeName=number

metric m:nov p:integer l:NOV t:dataTypeName=number

metric m:ytd_totals p:integer l:"YTD Totals" t:dataTypeName=number

entity e:vmxc-vnr5 l:"Commission on Women's Issues--2011 Summary of  Workshops and Attendees by Month" t:attribution="Cook County Commission on Women's Issues" t:url=https://datacatalog.cookcountyil.gov/api/views/vmxc-vnr5

property e:vmxc-vnr5 t:meta.view v:id=vmxc-vnr5 v:category="Finance & Administration" v:averageRating=0 v:name="Commission on Women's Issues--2011 Summary of  Workshops and Attendees by Month" v:attribution="Cook County Commission on Women's Issues"

property e:vmxc-vnr5 t:meta.view.license v:name="Public Domain"

property e:vmxc-vnr5 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:vmxc-vnr5 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| activity             | dec | jan | feb | mar | apr | may | jun | jul | aug | sep | oct | nov | ytd_totals | 
| ==================== | === | === | === | === | === | === | === | === | === | === | === | === | ========== | 
| Outreach & Workshops | 0   | 0   | 1   | 1   | 2   | 2   | 1   | 0   | 1   | 1   | 0   | 0   | 9          | 
| Number of Attendees  | 0   | 0   | 75  | 100 | 100 | 75  | 50  | 0   | 100 | 200 | 0   | 0   | 700        | 
```