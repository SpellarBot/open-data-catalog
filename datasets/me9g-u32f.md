# FY2015 Annual Report DMO Contacts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-annual-report-dmo-contacts) |
| Metadata | [Link](https://data.austintexas.gov/api/views/me9g-u32f) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/me9g-u32f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/me9g-u32f/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | me9g-u32f |
| Name | FY2015 Annual Report DMO Contacts |
| Tags | atcems, fy2015, annual report, dmo, operations data |
| Created | 2016-09-23T16:00:54Z |
| Publication Date | 2016-09-23T16:04:19Z |

## Description

** Static Data Set ** This table shows Designated Medical Officer (DMO) crew contacts for the past four fiscal years. It has been uploaded to support the ATCEMS FY2015 annual report. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name          | Data Type | Render Type |
| ======== | ============== | ============ | ============= | ========= | =========== |
| Yes      | series tag     | fy_id        | FY_ID         | text      | number      |
| Yes      | series tag     | fiscal_year  | Fiscal_Year   | text      | text        |
| Yes      | numeric metric | dmo_contacts | Crew Contacts | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:me9g-u32f d:2015-01-01T00:00:00.000Z t:fiscal_year=FY2012 t:fy_id=2012 m:dmo_contacts=126

series e:me9g-u32f d:2015-01-01T00:00:00.000Z t:fiscal_year=FY2013 t:fy_id=2013 m:dmo_contacts=516

series e:me9g-u32f d:2015-01-01T00:00:00.000Z t:fiscal_year=FY2014 t:fy_id=2014 m:dmo_contacts=796
```

## Meta Commands

```ls
metric m:dmo_contacts p:integer l:"Crew Contacts" t:dataTypeName=number

entity e:me9g-u32f l:"FY2015 Annual Report DMO Contacts" t:url=https://data.austintexas.gov/api/views/me9g-u32f

property e:me9g-u32f t:meta.view v:id=me9g-u32f v:averageRating=0 v:name="FY2015 Annual Report DMO Contacts"

property e:me9g-u32f t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:me9g-u32f t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| fy_id | fiscal_year | dmo_contacts | 
| ===== | =========== | ============ | 
| 2012  | FY2012      | 126          | 
| 2013  | FY2013      | 516          | 
| 2014  | FY2014      | 796          | 
| 2015  | FY2015      | 786          | 
```