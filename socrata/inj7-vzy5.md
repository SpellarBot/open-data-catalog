# Membership by County, Status, and Membership Group

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/membership-by-county-status-and-membership-group-fiscal-year-2015) |
| Metadata | [Link](https://data.iowa.gov/api/views/inj7-vzy5) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/inj7-vzy5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/inj7-vzy5/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | inj7-vzy5 |
| Name | Membership by County, Status, and Membership Group |
| Attribution | Iowa Public Employees' Retirement System |
| Category | Government |
| Tags | ipers |
| Created | 2016-12-30T23:08:43Z |
| Publication Date | 2017-03-14T20:44:36Z |

## Description

Membership groups
?	Regular: Most IPERS members are Regular members, or those who are not working in a sheriff/deputy or protection occupation job.
?	Special service: A small minority of IPERS members are Special service members, or those who work as sheriffs/deputies or in a protection occupation (jailers, police and firefighters, and others in public safety positions).

Membership statuses
?	Active: Currently working in an IPERS-covered job and contributing to IPERS.
?	Inactive: No longer working in an IPERS-covered job, but still retains IPERS membership and a wage/service record with IPERS.
?	Retired: Currently receiving monthly IPERS benefits. Includes members who are receiving monthly IPERS benefits while working in an IPERS-covered job (retired reemployed).

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | fiscal_year      | FISCAL_YEAR      | number    | number      |
| Yes      | series tag     | fips_county_code | FIPS_COUNTY_CODE | text      | text        |
| Yes      | series tag     | county_name      | COUNTY_NAME      | text      | text        |
| Yes      | series tag     | statename        | STATENAME        | text      | text        |
| Yes      | series tag     | membership_group | MEMBERSHIP_GROUP | text      | text        |
| Yes      | series tag     | member_status    | MEMBER_STATUS    | text      | text        |
| Yes      | numeric metric | members          | MEMBERS          | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:inj7-vzy5 d:2015-01-01T00:00:00.000Z t:membership_group=REGULAR t:fips_county_code=02290 t:statename=Alaska t:member_status=INACTIVE t:county_name="YUKON KOYUKUK" m:members=1

series e:inj7-vzy5 d:2015-01-01T00:00:00.000Z t:membership_group=REGULAR t:fips_county_code=01011 t:statename=Alabama t:member_status=INACTIVE t:county_name=BULLOCK m:members=1

series e:inj7-vzy5 d:2015-01-01T00:00:00.000Z t:membership_group=REGULAR t:fips_county_code=01053 t:statename=Alabama t:member_status=RETIRED t:county_name=ESCAMBIA m:members=1
```

## Meta Commands

```ls
metric m:members p:integer l:MEMBERS t:dataTypeName=number

entity e:inj7-vzy5 l:"Membership by County, Status, and Membership Group" t:attribution="Iowa Public Employees' Retirement System" t:url=https://data.iowa.gov/api/views/inj7-vzy5

property e:inj7-vzy5 t:meta.view v:id=inj7-vzy5 v:category=Government v:averageRating=0 v:name="Membership by County, Status, and Membership Group" v:attribution="Iowa Public Employees' Retirement System"

property e:inj7-vzy5 t:meta.view.license v:name="Public Domain"

property e:inj7-vzy5 t:meta.view.owner v:id=3qea-rfi2 v:profileImageUrlMedium=/api/users/3qea-rfi2/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qea-rfi2/profile_images/LARGE v:screenName="Iowa Public Employees' Retirement System" v:profileImageUrlSmall=/api/users/3qea-rfi2/profile_images/TINY v:displayName="Iowa Public Employees' Retirement System"

property e:inj7-vzy5 t:meta.view.tableauthor v:id=3qea-rfi2 v:profileImageUrlMedium=/api/users/3qea-rfi2/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qea-rfi2/profile_images/LARGE v:screenName="Iowa Public Employees' Retirement System" v:profileImageUrlSmall=/api/users/3qea-rfi2/profile_images/TINY v:roleName=editor v:displayName="Iowa Public Employees' Retirement System"
```

## Top Records

```ls
| fiscal_year | fips_county_code | county_name   | statename | membership_group | member_status | members | 
| =========== | ================ | ============= | ========= | ================ | ============= | ======= | 
| 2015        | 02290            | YUKON KOYUKUK | Alaska    | REGULAR          | INACTIVE      | 1       | 
| 2015        | 01011            | BULLOCK       | Alabama   | REGULAR          | INACTIVE      | 1       | 
| 2015        | 01053            | ESCAMBIA      | Alabama   | REGULAR          | RETIRED       | 1       | 
| 2015        | 01069            | HOUSTON       | Alabama   | REGULAR          | RETIRED       | 2       | 
| 2015        | 01077            | LAUDERDALE    | Alabama   | REGULAR          | RETIRED       | 1       | 
| 2015        | 01097            | MOBILE        | Alabama   | REGULAR          | INACTIVE      | 1       | 
| 2015        | 01097            | MOBILE        | Alabama   | REGULAR          | RETIRED       | 3       | 
| 2015        | 01099            | MONROE        | Alabama   | REGULAR          | INACTIVE      | 1       | 
| 2015        | 01103            | MORGAN        | Alabama   | REGULAR          | RETIRED       | 3       | 
| 2015        | 01113            | RUSSELL       | Alabama   | REGULAR          | INACTIVE      | 2       | 
```