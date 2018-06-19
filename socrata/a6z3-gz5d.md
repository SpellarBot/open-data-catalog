# 2013 Proposed Budget, Capital Improvement Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-proposed-budget-capital-improvement-projects-27c3e) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/a6z3-gz5d) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/a6z3-gz5d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/a6z3-gz5d/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | a6z3-gz5d |
| Name | 2013 Proposed Budget, Capital Improvement Projects |
| Attribution | King County Executive |
| Category | Budget |
| Tags | budget, 2013, budget2013 |
| Created | 2012-09-23T16:19:10Z |
| Publication Date | 2012-09-23T16:45:52Z |

## Description

King County budget proposed September 2012 by Executive for 2013, Capital Improvement Project expenditures. See http://www.kingcounty.gov/budget for more.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | extract        | Extract        | text      | text        |
| Yes      | series tag     | subfund_number | SubFund Number | text      | text        |
| Yes      | series tag     | subfund_name   | SubFund Name   | text      | text        |
| Yes      | series tag     | fund_number    | Fund Number    | text      | text        |
| Yes      | series tag     | fund_name      | Fund Name      | text      | text        |
| Yes      | numeric metric | fy13           | FY13           | money     | money       |
| Yes      | numeric metric | fy14           | FY14           | money     | money       |
| Yes      | numeric metric | fy15           | FY15           | money     | money       |
| Yes      | numeric metric | fy16           | FY16           | money     | money       |
| Yes      | numeric metric | fy17           | FY17           | money     | money       |
| Yes      | numeric metric | fy18           | FY18           | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:a6z3-gz5d d:2013-01-01T00:00:00.000Z t:fund_name="Pks FMD Auditor Cpo (1039583)" t:fund_number=1039583 t:subfund_name="FMD-Parks,Rec,Open Space" t:subfund_number=000003160 t:extract="Annual CIP not flexible budgeting" m:fy13=1189

series e:a6z3-gz5d d:2013-01-01T00:00:00.000Z t:fund_name="Pks FMD Regionl Trail Surface (1039610)" t:fund_number=1039610 t:subfund_name="FMD-Parks,Rec,Open Space" t:subfund_number=000003160 t:extract="Annual CIP not flexible budgeting" m:fy13=346282

series e:a6z3-gz5d d:2013-01-01T00:00:00.000Z t:fund_name="Pks M:Parks Facility Rehab (1039611)" t:fund_number=1039611 t:subfund_name="FMD-Parks,Rec,Open Space" t:subfund_number=000003160 t:extract="Annual CIP not flexible budgeting" m:fy13=223277
```

## Meta Commands

```ls
metric m:fy13 p:double l:FY13 t:dataTypeName=money

metric m:fy14 p:double l:FY14 t:dataTypeName=money

metric m:fy15 p:integer l:FY15 t:dataTypeName=money

metric m:fy16 p:integer l:FY16 t:dataTypeName=money

metric m:fy17 p:double l:FY17 t:dataTypeName=money

metric m:fy18 p:double l:FY18 t:dataTypeName=money

entity e:a6z3-gz5d l:"2013 Proposed Budget, Capital Improvement Projects" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/a6z3-gz5d

property e:a6z3-gz5d t:meta.view v:id=a6z3-gz5d v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="2013 Proposed Budget, Capital Improvement Projects" v:attribution="King County Executive"

property e:a6z3-gz5d t:meta.view.license v:name="Public Domain"

property e:a6z3-gz5d t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:a6z3-gz5d t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| extract                           | subfund_number | subfund_name             | fund_number | fund_name                                | fy13   | fy14  | fy15 | fy16 | fy17 | fy18 | 
| ================================= | ============== | ======================== | =========== | ======================================== | ====== | ===== | ==== | ==== | ==== | ==== | 
| Annual CIP not flexible budgeting | 000003160      | FMD-Parks,Rec,Open Space | 1039583     | Pks FMD Auditor Cpo (1039583)            | 1189   |       |      |      |      |      | 
| Annual CIP not flexible budgeting | 000003160      | FMD-Parks,Rec,Open Space | 1039610     | Pks FMD Regionl Trail Surface (1039610)  | 346282 |       |      |      |      |      | 
| Annual CIP not flexible budgeting | 000003160      | FMD-Parks,Rec,Open Space | 1039611     | Pks M:Parks Facility Rehab (1039611)     | 223277 |       |      |      |      |      | 
| Annual CIP not flexible budgeting | 000003160      | FMD-Parks,Rec,Open Space | 1039614     | Pks FMD Greenbridge Hope 6 (1039614)     | 129905 |       |      |      |      |      | 
| Annual CIP not flexible budgeting | 000003160      | FMD-Parks,Rec,Open Space | 1039827     | Pks FMD Fund 3160 Cntral Rates (1039827) | 54664  | 28869 |      |      |      |      | 
| Annual CIP not flexible budgeting | 000003160      | FMD-Parks,Rec,Open Space | 1039848     | Pks FMD Assoc Dlvp/ Partner Pm (1039848) | 300000 |       |      |      |      |      | 
| Annual CIP not flexible budgeting | 000003160      | FMD-Parks,Rec,Open Space | 1039850     | Pks FMD Parks Litigation Proj (1039850)  | 43536  | 45708 |      |      |      |      | 
| Annual CIP not flexible budgeting | 000003160      | FMD-Parks,Rec,Open Space | 1039868     | Pks FMD Regional Trails Plan (1039868)   | 244732 |       |      |      |      |      | 
| Annual CIP not flexible budgeting | 000003160      | FMD-Parks,Rec,Open Space | 1046210     | Pks FMD Parks Prjt Imple Staff (1046210) | 515722 |       |      |      |      |      | 
| Annual CIP not flexible budgeting | 000003160      | FMD-Parks,Rec,Open Space | 1046211     | Pks FMD Parks Joint Dev Plan (1046211)   | 321394 |       |      |      |      |      | 
```