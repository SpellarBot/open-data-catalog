# Unemployment Compensation Fund Status - Contribution Rate Distribution

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-compensation-fund-status-contribution-rate-distribution) |
| Metadata | [Link](https://data.iowa.gov/api/views/88ph-pwv8) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/88ph-pwv8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/88ph-pwv8/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 88ph-pwv8 |
| Name | Unemployment Compensation Fund Status - Contribution Rate Distribution |
| Attribution | Iowa Workforce Development - Labor Market Information Division |
| Category | Economy |
| Tags | unemployment insurance, ui contribution rates |
| Created | 2015-05-06T14:46:34Z |
| Publication Date | 2016-12-06T16:08:57Z |

## Description

Contains UI contribution rate data for private employers.  This includes experienced rated employers and firms receiving a new employer rate.  This data is summarized in the "Status Report on the Iowa Unemployment Compensation Trust Fund" report.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name    | Data Type | Render Type |
| ======== | ============== | ================= | ======= | ========= | =========== |
| Yes      | time           | rate_year         | Year    | number    | number      |
| Yes      | numeric metric | table             | Table   | number    | number      |
| Yes      | series tag     | type              | Type    | text      | text        |
| Yes      | numeric metric | contribution_rate | Rate    | percent   | percent     |
| Yes      | numeric metric | firms             | Firms   | number    | number      |
| Yes      | numeric metric | percent           | Percent | percent   | percent     |
```

## Time Field

```ls
Value = rate_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:88ph-pwv8 d:2017-01-01T00:00:00.000Z t:type=Exp m:contribution_rate=0 m:percent=47.5 m:firms=35668 m:table=6

series e:88ph-pwv8 d:2017-01-01T00:00:00.000Z t:type=Exp m:contribution_rate=0.1 m:percent=1.2 m:firms=932 m:table=6

series e:88ph-pwv8 d:2017-01-01T00:00:00.000Z t:type=Exp m:contribution_rate=0.2 m:percent=1.4 m:firms=1076 m:table=6
```

## Meta Commands

```ls
metric m:table p:integer l:Table d:"Contribution Rate Table - The contribution rate table triggered for the reference year. Iowa Code has eight rate tables. Rate tables are triggered based on the relative trust fund strength. The average contribution rate ranges from about 3.5 percent in table 1 to about 0.9 percent in table 8." t:dataTypeName=number

metric m:contribution_rate p:float l:Rate d:"Employer Contribution Rate - Contribution rates in Iowa can range from 0.0% to 9.0% depending on each individual employer?s benefit experience and the rate table in effect." t:dataTypeName=percent

metric m:firms p:integer l:Firms d:"Number of firms in each rate type and contribution rate group." t:dataTypeName=number

metric m:percent p:float l:Percent d:"Percent of firms in each rate type and contribution rate group during the reference year.." t:dataTypeName=percent

entity e:88ph-pwv8 l:"Unemployment Compensation Fund Status - Contribution Rate Distribution" t:attribution="Iowa Workforce Development - Labor Market Information Division" t:url=https://data.iowa.gov/api/views/88ph-pwv8

property e:88ph-pwv8 t:meta.view v:id=88ph-pwv8 v:category=Economy v:attributionLink=https://www.iowaworkforcedevelopment.gov/sites/search.iowaworkforcedevelopment.gov/files/unemploymentcomp_trustfund_statusreport_1.pdf v:averageRating=0 v:name="Unemployment Compensation Fund Status - Contribution Rate Distribution" v:attribution="Iowa Workforce Development - Labor Market Information Division"

property e:88ph-pwv8 t:meta.view.owner v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"

property e:88ph-pwv8 t:meta.view.tableauthor v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"
```

## Top Records

```ls
| rate_year | table | type | contribution_rate | firms | percent | 
| ========= | ===== | ==== | ================= | ===== | ======= | 
| 2017      | 6     | Exp  | 0.0               | 35668 | 47.5    | 
| 2017      | 6     | Exp  | 0.1               | 932   | 1.2     | 
| 2017      | 6     | Exp  | 0.2               | 1076  | 1.4     | 
| 2017      | 6     | Exp  | 0.3               | 1023  | 1.4     | 
| 2017      | 6     | Exp  | 0.4               | 862   | 1.1     | 
| 2017      | 6     | Exp  | 0.5               | 774   | 1.0     | 
| 2017      | 6     | Exp  | 0.6               | 1612  | 2.1     | 
| 2017      | 6     | Exp  | 0.7               | 713   | 0.9     | 
| 2017      | 6     | Exp  | 0.9               | 726   | 1.0     | 
| 2017      | 6     | Exp  | 1.1               | 800   | 1.1     | 
```