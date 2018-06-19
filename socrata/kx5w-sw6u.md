# Austin Energy Web App Users By Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-energy-web-app-users-by-month) |
| Metadata | [Link](https://data.austintexas.gov/api/views/kx5w-sw6u) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/kx5w-sw6u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/kx5w-sw6u/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | kx5w-sw6u |
| Name | Austin Energy Web App Users By Month |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | app, austin energy, austin energy web app, application |
| Created | 2016-08-05T16:52:07Z |
| Publication Date | 2016-08-08T11:50:22Z |

## Description

Austin Energy?s free, interactive web app allows customers to monitor their daily energy usage, view their bill history, and see a future forecast of their energy bill cost. They can also set alerts to warn them of an upcoming rate tier change.

Austin Energy Web App users can also download Green Button Data which can help them better understand their energy usage and take action towards savings. This data set shows the number of web app users by month.

Learn more about the app at http://powersaver.austinenergy.com/wps/portal/psp/residential/learn/free-home-energy-management-options/alerts-and-tips-help-you-manage-your-energy-costs

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                  | Data Type     | Render Type   |
| ======== | ============== | ================= | ===================== | ============= | ============= |
| Yes      | time           | date              | Date                  | calendar_date | calendar_date |
| Yes      | numeric metric | users             | Total number of users | number        | number        |
| Yes      | numeric metric | residential_accts | Residential users     | number        | number        |
| Yes      | numeric metric | commercial_accts  | Commercial users      | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:kx5w-sw6u d:2013-09-01T00:00:00.000Z m:users=28 m:residential_accts=27 m:commercial_accts=7

series e:kx5w-sw6u d:2013-10-01T00:00:00.000Z m:users=139 m:residential_accts=124 m:commercial_accts=12

series e:kx5w-sw6u d:2013-11-01T00:00:00.000Z m:users=819 m:residential_accts=766 m:commercial_accts=43
```

## Meta Commands

```ls
metric m:users p:integer l:"Total number of users" t:dataTypeName=number

metric m:residential_accts p:integer l:"Residential users" t:dataTypeName=number

metric m:commercial_accts p:integer l:"Commercial users" t:dataTypeName=number

entity e:kx5w-sw6u l:"Austin Energy Web App Users By Month" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/kx5w-sw6u

property e:kx5w-sw6u t:meta.view v:id=kx5w-sw6u v:category=Utility v:averageRating=0 v:name="Austin Energy Web App Users By Month" v:attribution="Austin Energy"

property e:kx5w-sw6u t:meta.view.license v:name="Public Domain"

property e:kx5w-sw6u t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:kx5w-sw6u t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```

## Top Records

```ls
| date                | users | residential_accts | commercial_accts | 
| =================== | ===== | ================= | ================ | 
| 2013-09-01T00:00:00 | 28    | 27                | 7                | 
| 2013-10-01T00:00:00 | 139   | 124               | 12               | 
| 2013-11-01T00:00:00 | 819   | 766               | 43               | 
| 2013-12-01T00:00:00 | 1377  | 1300              | 78               | 
| 2014-01-01T00:00:00 | 2169  | 2077              | 113              | 
| 2014-02-01T00:00:00 | 2645  | 2554              | 134              | 
| 2014-03-01T00:00:00 | 3835  | 3628              | 617              | 
| 2014-04-01T00:00:00 | 4286  | 4072              | 635              | 
| 2014-05-01T00:00:00 | 4745  | 4521              | 665              | 
| 2014-06-01T00:00:00 | 5426  | 5187              | 862              | 
```