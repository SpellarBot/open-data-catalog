# Office of the President -- Commission on Women's Issues--2011 Summary of Activity, by Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/office-of-the-president-commission-on-womens-issues-2011-summary-of-activity-by-month-d5403) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/qt2z-ui8z) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/qt2z-ui8z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/qt2z-ui8z/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | qt2z-ui8z |
| Name | Office of the President -- Commission on Women's Issues--2011 Summary of Activity, by Month |
| Attribution | Cook County Commission on Women's Issues |
| Category | Finance & Administration |
| Created | 2011-09-07T17:04:00Z |
| Publication Date | 2014-10-09T21:38:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type | Render Type |
| ======== | ============== | ================== | ==================== | ========= | =========== |
| Yes      | series tag     | month              | Month                | text      | text        |
| Yes      | numeric metric | outreach_workshops | Outreach & Workshops | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qt2z-ui8z d:2011-01-01T00:00:00.000Z t:month=DEC m:outreach_workshops=0

series e:qt2z-ui8z d:2011-01-01T00:00:00.000Z t:month=JAN m:outreach_workshops=0

series e:qt2z-ui8z d:2011-01-01T00:00:00.000Z t:month=FEB m:outreach_workshops=1
```

## Meta Commands

```ls
metric m:outreach_workshops p:integer l:"Outreach & Workshops" d:"The number of special events sponsored by the Commission on Womens' Issues in 2011" t:dataTypeName=number

entity e:qt2z-ui8z l:"Office of the President -- Commission on Women's Issues--2011 Summary of Activity, by Month" t:attribution="Cook County Commission on Women's Issues" t:url=https://datacatalog.cookcountyil.gov/api/views/qt2z-ui8z

property e:qt2z-ui8z t:meta.view v:id=qt2z-ui8z v:category="Finance & Administration" v:averageRating=0 v:name="Office of the President -- Commission on Women's Issues--2011 Summary of Activity, by Month" v:attribution="Cook County Commission on Women's Issues"

property e:qt2z-ui8z t:meta.view.license v:name="Public Domain"

property e:qt2z-ui8z t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:qt2z-ui8z t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month | outreach_workshops | 
| ===== | ================== | 
| DEC   | 0                  | 
| JAN   | 0                  | 
| FEB   | 1                  | 
| MAR   | 1                  | 
| APR   | 2                  | 
| MAY   | 2                  | 
| JUN   | 1                  | 
```