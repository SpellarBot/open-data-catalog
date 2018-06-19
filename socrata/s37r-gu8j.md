# FY2015 Annual Report Safety Risk Levels

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-annual-report-safety-risk-levels) |
| Metadata | [Link](https://data.austintexas.gov/api/views/s37r-gu8j) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/s37r-gu8j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/s37r-gu8j/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | s37r-gu8j |
| Name | FY2015 Annual Report Safety Risk Levels |
| Category | Public Safety |
| Tags | atcems, fy2015, annual report, safety |
| Created | 2016-09-26T19:06:19Z |
| Publication Date | 2016-12-14T16:21:43Z |

## Description

** Static Data Set ** This table shows safety data for FY2015. It has been uploaded to support the ATCEMS FY2015 annual report. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | risk_level | Risk Level | text      | text        |
| Yes      | numeric metric | percent    | Percent    | percent   | percent     |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:s37r-gu8j d:2015-01-01T00:00:00.000Z t:risk_level="Low Risk" m:percent=51

series e:s37r-gu8j d:2015-01-01T00:00:00.000Z t:risk_level="Medium Risk" m:percent=36

series e:s37r-gu8j d:2015-01-01T00:00:00.000Z t:risk_level="High Risk" m:percent=13
```

## Meta Commands

```ls
metric m:percent p:integer l:Percent t:dataTypeName=percent

entity e:s37r-gu8j l:"FY2015 Annual Report Safety Risk Levels" t:url=https://data.austintexas.gov/api/views/s37r-gu8j

property e:s37r-gu8j t:meta.view v:id=s37r-gu8j v:category="Public Safety" v:averageRating=0 v:name="FY2015 Annual Report Safety Risk Levels"

property e:s37r-gu8j t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:s37r-gu8j t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| risk_level  | percent | 
| =========== | ======= | 
| Low Risk    | 51      | 
| Medium Risk | 36      | 
| High Risk   | 13      | 
```