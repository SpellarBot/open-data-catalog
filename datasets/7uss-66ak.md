# Iowa Unemployment Insurance Claimants by Age

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-unemployment-insurance-claimants-by-age) |
| Metadata | [Link](https://data.iowa.gov/api/views/7uss-66ak) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/7uss-66ak/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/7uss-66ak/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 7uss-66ak |
| Name | Iowa Unemployment Insurance Claimants by Age |
| Attribution | Iowa Workforce Development - Labor Market Information Division |
| Category | Economy |
| Tags | demographic, characheristics, unemployment insurance, claims, age |
| Created | 2016-04-20T15:26:07Z |
| Publication Date | 2016-09-16T12:59:04Z |

## Description

This dataset contains Iowa unemployment insurance claimants by age group based in the week of the 19th of each month. (ETA-203)

## Columns

```ls
| Included | Schema Type    | Field Name      | Name      | Data Type     | Render Type   |
| ======== | ============== | =============== | ========= | ============= | ============= |
| Yes      | time           | month_ending    | Month     | calendar_date | calendar_date |
| Yes      | numeric metric | total           | Total     | number        | number        |
| Yes      | numeric metric | age_under_22    | Under 22  | number        | number        |
| Yes      | numeric metric | age_22_24       | 22-24     | number        | number        |
| Yes      | numeric metric | age_25_34       | 25-34     | number        | number        |
| Yes      | numeric metric | age_35_44       | 35-44     | number        | number        |
| Yes      | numeric metric | age_45_54       | 45-54     | number        | number        |
| Yes      | numeric metric | age_55_59       | 55-59     | number        | number        |
| Yes      | numeric metric | age_60_64       | 60-64     | number        | number        |
| Yes      | numeric metric | age_65_and_over | 65 & over | number        | number        |
| Yes      | numeric metric | age_ina         | INA       | number        | number        |
```

## Time Field

```ls
Value = month_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7uss-66ak d:2000-01-31T00:00:00.000Z m:total=29553 m:age_25_34=7280 m:age_ina=3 m:age_35_44=8660 m:age_55_59=1949 m:age_60_64=1370 m:age_65_and_over=758 m:age_under_22=1158 m:age_45_54=6324 m:age_22_24=2051

series e:7uss-66ak d:2000-02-29T00:00:00.000Z m:total=29995 m:age_25_34=7349 m:age_ina=5 m:age_35_44=8890 m:age_55_59=1928 m:age_60_64=1312 m:age_65_and_over=740 m:age_under_22=1238 m:age_45_54=6422 m:age_22_24=2111

series e:7uss-66ak d:2000-03-31T00:00:00.000Z m:total=23906 m:age_25_34=5510 m:age_ina=5 m:age_35_44=7199 m:age_55_59=1653 m:age_60_64=1114 m:age_65_and_over=625 m:age_under_22=821 m:age_45_54=5514 m:age_22_24=1465
```

## Meta Commands

```ls
metric m:total p:integer l:Total d:"Number of unemployment insurance claimants filing continued claims during the week of the 19th of each month" t:dataTypeName=number

metric m:age_under_22 p:integer l:"Under 22" t:dataTypeName=number

metric m:age_22_24 p:integer l:22-24 t:dataTypeName=number

metric m:age_25_34 p:integer l:25-34 t:dataTypeName=number

metric m:age_35_44 p:integer l:35-44 t:dataTypeName=number

metric m:age_45_54 p:integer l:45-54 t:dataTypeName=number

metric m:age_55_59 p:integer l:55-59 t:dataTypeName=number

metric m:age_60_64 p:integer l:60-64 t:dataTypeName=number

metric m:age_65_and_over p:integer l:"65 & over" t:dataTypeName=number

metric m:age_ina p:integer l:INA d:"Information not available" t:dataTypeName=number

entity e:7uss-66ak l:"Iowa Unemployment Insurance Claimants by Age" t:attribution="Iowa Workforce Development - Labor Market Information Division" t:url=https://data.iowa.gov/api/views/7uss-66ak

property e:7uss-66ak t:meta.view v:id=7uss-66ak v:category=Economy v:averageRating=0 v:name="Iowa Unemployment Insurance Claimants by Age" v:attribution="Iowa Workforce Development - Labor Market Information Division"

property e:7uss-66ak t:meta.view.license v:name="Public Domain"

property e:7uss-66ak t:meta.view.owner v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"

property e:7uss-66ak t:meta.view.tableauthor v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"
```

## Top Records

```ls
| month_ending        | total | age_under_22 | age_22_24 | age_25_34 | age_35_44 | age_45_54 | age_55_59 | age_60_64 | age_65_and_over | age_ina | 
| =================== | ===== | ============ | ========= | ========= | ========= | ========= | ========= | ========= | =============== | ======= | 
| 2000-01-31T00:00:00 | 29553 | 1158         | 2051      | 7280      | 8660      | 6324      | 1949      | 1370      | 758             | 3       | 
| 2000-02-29T00:00:00 | 29995 | 1238         | 2111      | 7349      | 8890      | 6422      | 1928      | 1312      | 740             | 5       | 
| 2000-03-31T00:00:00 | 23906 | 821          | 1465      | 5510      | 7199      | 5514      | 1653      | 1114      | 625             | 5       | 
| 2000-04-30T00:00:00 | 16905 | 608          | 980       | 3862      | 5120      | 4036      | 1119      | 776       | 398             | 6       | 
| 2000-05-31T00:00:00 | 14323 | 428          | 741       | 3219      | 4459      | 3488      | 982       | 671       | 332             | 3       | 
| 2000-06-30T00:00:00 | 15210 | 455          | 744       | 3469      | 4605      | 3692      | 1082      | 768       | 392             | 3       | 
| 2000-07-31T00:00:00 | 15897 | 474          | 809       | 3545      | 4714      | 3887      | 1222      | 842       | 401             | 3       | 
| 2000-08-31T00:00:00 | 14588 | 464          | 690       | 3196      | 4366      | 3604      | 1110      | 782       | 375             | 1       | 
| 2000-09-30T00:00:00 | 12420 | 445          | 632       | 2775      | 3728      | 3003      | 916       | 637       | 282             | 2       | 
| 2000-10-31T00:00:00 | 12857 | 510          | 676       | 2807      | 3731      | 3223      | 960       | 653       | 296             | 1       | 
```