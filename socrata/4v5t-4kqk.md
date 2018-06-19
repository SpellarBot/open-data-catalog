# Missouri Monthly Unemployment Claims By Sex

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-monthly-unemployment-claims-by-sex-f5cb6) |
| Metadata | [Link](https://data.mo.gov/api/views/4v5t-4kqk) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/4v5t-4kqk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/4v5t-4kqk/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 4v5t-4kqk |
| Name | Missouri Monthly Unemployment Claims By Sex |
| Category | Labor |
| Tags | unemployment, labor, employment |
| Created | 2012-08-30T14:34:28Z |
| Publication Date | 2017-04-10T13:01:02Z |

## Description

Demographic data of Missouri Unemployment claims by sex

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type     | Render Type   |
| ======== | ============== | ========== | ========= | ============= | ============= |
| Yes      | series tag     | record_id  | Record ID | text          | text          |
| Yes      | time           | date       | Date      | calendar_date | calendar_date |
| Yes      | numeric metric | ina        | INA       | number        | number        |
| Yes      | numeric metric | female     | FEMALE    | number        | number        |
| Yes      | numeric metric | male       | MALE      | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:4v5t-4kqk d:2011-08-01T00:00:00.000Z t:record_id=08012011 m:female=32985 m:ina=51 m:male=29028

series e:4v5t-4kqk d:2011-07-01T00:00:00.000Z t:record_id=07012011 m:female=35518 m:ina=38 m:male=31265

series e:4v5t-4kqk d:2011-09-01T00:00:00.000Z t:record_id=09012011 m:female=26319 m:ina=57 m:male=27105
```

## Meta Commands

```ls
metric m:ina p:integer l:INA d:"Information Not Available" t:dataTypeName=number

metric m:female p:integer l:FEMALE t:dataTypeName=number

metric m:male p:integer l:MALE t:dataTypeName=number

entity e:4v5t-4kqk l:"Missouri Monthly Unemployment Claims By Sex" t:url=https://data.mo.gov/api/views/4v5t-4kqk

property e:4v5t-4kqk t:meta.view v:id=4v5t-4kqk v:category=Labor v:averageRating=0 v:name="Missouri Monthly Unemployment Claims By Sex"

property e:4v5t-4kqk t:meta.view.owner v:id=8xqn-4t42 v:profileImageUrlMedium=/api/users/8xqn-4t42/profile_images/THUMB v:profileImageUrlLarge=/api/users/8xqn-4t42/profile_images/LARGE v:screenName="Rodney Distler" v:profileImageUrlSmall=/api/users/8xqn-4t42/profile_images/TINY v:displayName="Rodney Distler"

property e:4v5t-4kqk t:meta.view.tableauthor v:id=8xqn-4t42 v:profileImageUrlMedium=/api/users/8xqn-4t42/profile_images/THUMB v:profileImageUrlLarge=/api/users/8xqn-4t42/profile_images/LARGE v:screenName="Rodney Distler" v:profileImageUrlSmall=/api/users/8xqn-4t42/profile_images/TINY v:roleName=publisher v:displayName="Rodney Distler"
```

## Top Records

```ls
| record_id | date                | ina | female | male  | 
| ========= | =================== | === | ====== | ===== | 
| 08012011  | 2011-08-01T00:00:00 | 51  | 32985  | 29028 | 
| 07012011  | 2011-07-01T00:00:00 | 38  | 35518  | 31265 | 
| 09012011  | 2011-09-01T00:00:00 | 57  | 26319  | 27105 | 
| 02012012  | 2012-02-01T00:00:00 | 65  | 24066  | 39834 | 
| 10012011  | 2011-10-01T00:00:00 | 55  | 24269  | 26030 | 
| 11012011  | 2011-11-01T00:00:00 | 73  | 26456  | 31807 | 
| 12012011  | 2011-12-01T00:00:00 | 70  | 23336  | 34519 | 
| 01012012  | 2012-01-01T00:00:00 | 78  | 26504  | 41399 | 
| 03012012  | 2012-03-01T00:00:00 | 72  | 22685  | 32888 | 
| 06012012  | 2012-06-01T00:00:00 | 57  | 25860  | 24243 | 
```