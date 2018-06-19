# Cash Assistance Heads Of Household By Engagement (16-24 years old)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cash-assistance-heads-of-household-by-engagement-16-24-years-old-22e74) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6ayi-u3p7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6ayi-u3p7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6ayi-u3p7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6ayi-u3p7 |
| Name | Cash Assistance Heads Of Household By Engagement (16-24 years old) |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | cash assistance head's of household by engagement (16-24years old) |
| Created | 2013-05-21T11:43:16Z |
| Publication Date | 2016-05-23T19:01:08Z |

## Description

Statistics on heads of a household receiving cash assistance between 16 and 24 years old by engagement category.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                   | Data Type | Render Type |
| ======== | ============== | =================== | ====================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at             | meta_data | meta_data   |
| Yes      | series tag     | engagement_category | ENGAGEMENT CATEGORY    | text      | text        |
| Yes      | numeric metric | 16_17_years         | 16-17 Years            | number    | number      |
| Yes      | numeric metric | of_total_16_17_yrs  | % of Total (16-17 yrs) | percent   | percent     |
| Yes      | numeric metric | 18_20_years         | 18-20 Years            | number    | number      |
| Yes      | numeric metric | of_total_18_20_yrs  | % of Total (18-20 yrs) | percent   | percent     |
| Yes      | numeric metric | 21_24_years         | 21-24 Years            | number    | number      |
| Yes      | numeric metric | of_total_21_24_yrs  | % of Total (21-24 yrs) | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6ayi-u3p7 d:2016-05-23T12:00:19.000Z t:engagement_category="ACTIVE SINGLE ISSUE CASES" m:16_17_years=3 m:of_total_16_17_yrs=3.61 m:18_20_years=70 m:of_total_21_24_yrs=3.17 m:of_total_18_20_yrs=3.2 m:21_24_years=299

series e:6ayi-u3p7 d:2016-05-23T12:00:19.000Z t:engagement_category="AGE 60 OR OVER" m:16_17_years=0 m:of_total_16_17_yrs=0 m:18_20_years=0 m:of_total_21_24_yrs=0.01 m:of_total_18_20_yrs=0 m:21_24_years=1

series e:6ayi-u3p7 d:2016-05-23T12:00:19.000Z t:engagement_category="ASSIGNED JOB SEARCH" m:16_17_years=0 m:of_total_16_17_yrs=0 m:18_20_years=70 m:of_total_21_24_yrs=6.36 m:of_total_18_20_yrs=3.2 m:21_24_years=599
```

## Meta Commands

```ls
metric m:16_17_years p:integer l:"16-17 Years" t:dataTypeName=number

metric m:of_total_16_17_yrs p:float l:"% of Total (16-17 yrs)" t:dataTypeName=percent

metric m:18_20_years p:integer l:"18-20 Years" t:dataTypeName=number

metric m:of_total_18_20_yrs p:float l:"% of Total (18-20 yrs)" t:dataTypeName=percent

metric m:21_24_years p:integer l:"21-24 Years" t:dataTypeName=number

metric m:of_total_21_24_yrs p:float l:"% of Total (21-24 yrs)" t:dataTypeName=percent

entity e:6ayi-u3p7 l:"Cash Assistance Heads Of Household By Engagement (16-24 years old)" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/6ayi-u3p7

property e:6ayi-u3p7 t:meta.view v:id=6ayi-u3p7 v:category="Social Services" v:averageRating=0 v:name="Cash Assistance Heads Of Household By Engagement (16-24 years old)" v:attribution="Human Resources Administration (HRA)"

property e:6ayi-u3p7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6ayi-u3p7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | engagement_category           | 16_17_years | of_total_16_17_yrs | 18_20_years | of_total_18_20_yrs | 21_24_years | of_total_21_24_yrs | 
| =========== | ============================= | =========== | ================== | =========== | ================== | =========== | ================== | 
| 1464004819  | ACTIVE SINGLE ISSUE CASES     | 3           | 3.61               | 70          | 3.20               | 299         | 3.17               | 
| 1464004819  | AGE 60 OR OVER                | 0           | 0.00               | 0           | 0.00               | 1           | 0.01               | 
| 1464004819  | ASSIGNED JOB SEARCH           | 0           | 0.00               | 70          | 3.20               | 599         | 6.36               | 
| 1464004819  | AWAITING CONCILIATION SCHED.  | 0           | 0.00               | 3           | 0.14               | 21          | 0.22               | 
| 1464004819  | CALL-IN APPOINTMENT SCHEDULED | 1           | 1.20               | 436         | 19.92              | 1489        | 15.81              | 
| 1464004819  | CHILD UNDER 3 MONTHS          | 0           | 0.00               | 16          | 0.73               | 65          | 0.69               | 
| 1464004819  | CONCILIATION/CONFERENCE       | 0           | 0.00               | 128         | 5.85               | 614         | 6.52               | 
| 1464004819  | DASIS CASES                   | 0           | 0.00               | 61          | 2.79               | 519         | 5.51               | 
| 1464004819  | EDUCATION/TRAINING            | 0           | 0.00               | 422         | 19.28              | 630         | 6.69               | 
| 1464004819  | ELIGIBILITY CALL-IN APPT SCHD | 1           | 1.20               | 7           | 0.32               | 14          | 0.15               | 
```