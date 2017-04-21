# Iowa Unemployment Insurance Claimants by Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-unemployment-insurance-claimants-by-gender) |
| Metadata | [Link](https://data.iowa.gov/api/views/t92x-wtrh) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/t92x-wtrh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/t92x-wtrh/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | t92x-wtrh |
| Name | Iowa Unemployment Insurance Claimants by Gender |
| Attribution | Iowa Workforce Development - Labor Market Information Division |
| Category | Economy |
| Tags | demographic, characheristics, unemployment insurance, claims, gender, sex |
| Created | 2016-08-17T14:19:00Z |
| Publication Date | 2016-09-16T12:56:06Z |

## Description

This dataset contains Iowa unemployment insurance claimants by gender based in the week of the 19th of each month. (ETA-203)

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | time           | month      | Month      | calendar_date | calendar_date |
| Yes      | numeric metric | total      | Total      | number        | number        |
| Yes      | numeric metric | male       | Male       | number        | number        |
| Yes      | numeric metric | female     | Female     | number        | number        |
| Yes      | numeric metric | gender_ina | Gender_INA | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:t92x-wtrh d:2000-01-31T00:00:00.000Z m:total=29553 m:female=7513 m:male=22040 m:gender_ina=0

series e:t92x-wtrh d:2000-02-29T00:00:00.000Z m:total=29995 m:female=7529 m:male=22466 m:gender_ina=0

series e:t92x-wtrh d:2000-03-31T00:00:00.000Z m:total=23906 m:female=7203 m:male=16703 m:gender_ina=0
```

## Meta Commands

```ls
metric m:total p:integer l:Total d:"Number of unemployment insurance claimants filing continued claims during the week of the 19th of each month." t:dataTypeName=number

metric m:male p:integer l:Male t:dataTypeName=number

metric m:female p:integer l:Female t:dataTypeName=number

metric m:gender_ina p:integer l:Gender_INA d:"Gender is not available" t:dataTypeName=number

entity e:t92x-wtrh l:"Iowa Unemployment Insurance Claimants by Gender" t:attribution="Iowa Workforce Development - Labor Market Information Division" t:url=https://data.iowa.gov/api/views/t92x-wtrh

property e:t92x-wtrh t:meta.view v:id=t92x-wtrh v:category=Economy v:averageRating=0 v:name="Iowa Unemployment Insurance Claimants by Gender" v:attribution="Iowa Workforce Development - Labor Market Information Division"

property e:t92x-wtrh t:meta.view.license v:name="Public Domain"

property e:t92x-wtrh t:meta.view.owner v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"

property e:t92x-wtrh t:meta.view.tableauthor v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"
```

## Top Records

```ls
| month               | total | male  | female | gender_ina | 
| =================== | ===== | ===== | ====== | ========== | 
| 2000-01-31T00:00:00 | 29553 | 22040 | 7513   | 0          | 
| 2000-02-29T00:00:00 | 29995 | 22466 | 7529   | 0          | 
| 2000-03-31T00:00:00 | 23906 | 16703 | 7203   | 0          | 
| 2000-04-30T00:00:00 | 16905 | 10298 | 6607   | 0          | 
| 2000-05-31T00:00:00 | 14323 | 7880  | 6443   | 0          | 
| 2000-06-30T00:00:00 | 15210 | 7740  | 7470   | 0          | 
| 2000-07-31T00:00:00 | 15897 | 7841  | 8056   | 0          | 
| 2000-08-31T00:00:00 | 14588 | 7058  | 7530   | 0          | 
| 2000-09-30T00:00:00 | 12420 | 6503  | 5917   | 0          | 
| 2000-10-31T00:00:00 | 12857 | 7055  | 5802   | 0          | 
```