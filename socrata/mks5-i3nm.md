# Total Annual Skills Training Completions by Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-annual-skills-training-completions-by-type-35374) |
| Metadata | [Link](https://data.maryland.gov/api/views/mks5-i3nm) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/mks5-i3nm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/mks5-i3nm/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | mks5-i3nm |
| Name | Total Annual Skills Training Completions by Type |
| Attribution | Department of Labor Licensing and Regulation (DLLR) |
| Category | Education |
| Tags | skills, education, dllr, workforce, deletion nominated |
| Created | 2012-09-07T19:06:57Z |
| Publication Date | 2014-09-08T14:36:29Z |

## Description

DLLR tracks these key metrics of completion of skills training programs and reports them to the Governor's Office.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================== | ========= | =========== |
| No       | time           | :updated_at                               | updated_at                                 | meta_data | meta_data   |
| Yes      | series tag     | type                                      | Type                                       | text      | text        |
| Yes      | numeric metric | skills_training_annual_completions_fy2011 | Skills Training Annual Completions: FY2011 | number    | number      |
| Yes      | numeric metric | skills_training_annual_completions_fy2012 | Skills Training Annual Completions: FY2012 | number    | number      |
| Yes      | numeric metric | skills_training_annual_completions_fy2013 | Skills Training Annual Completions: FY2013 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mks5-i3nm d:2012-09-07T12:06:58.000Z t:type="Workers Trained with MBW Funds" m:skills_training_annual_completions_fy2011=3587

series e:mks5-i3nm d:2014-04-09T10:15:56.000Z t:type="Associate's Degrees Awarded by Community Colleges" m:skills_training_annual_completions_fy2011=12637 m:skills_training_annual_completions_fy2012=13852 m:skills_training_annual_completions_fy2013=14269

series e:mks5-i3nm d:2014-04-09T10:16:03.000Z t:type="For-Credit Certificates Awarded by Community Colleges" m:skills_training_annual_completions_fy2011=3337 m:skills_training_annual_completions_fy2012=3536 m:skills_training_annual_completions_fy2013=4670
```

## Meta Commands

```ls
metric m:skills_training_annual_completions_fy2011 p:integer l:"Skills Training Annual Completions: FY2011" t:dataTypeName=number

metric m:skills_training_annual_completions_fy2012 p:integer l:"Skills Training Annual Completions: FY2012" t:dataTypeName=number

metric m:skills_training_annual_completions_fy2013 p:integer l:"Skills Training Annual Completions: FY2013" t:dataTypeName=number

entity e:mks5-i3nm l:"Total Annual Skills Training Completions by Type" t:attribution="Department of Labor Licensing and Regulation (DLLR)" t:url=https://data.maryland.gov/api/views/mks5-i3nm

property e:mks5-i3nm t:meta.view v:id=mks5-i3nm v:category=Education v:attributionLink=http://www.dllr.state.md.us/ v:averageRating=0 v:name="Total Annual Skills Training Completions by Type" v:attribution="Department of Labor Licensing and Regulation (DLLR)"

property e:mks5-i3nm t:meta.view.license v:name="Public Domain"

property e:mks5-i3nm t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:mks5-i3nm t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | type                                                      | skills_training_annual_completions_fy2011 | skills_training_annual_completions_fy2012 | skills_training_annual_completions_fy2013 | 
| =========== | ========================================================= | ========================================= | ========================================= | ========================================= | 
| 1347019618  | Workers Trained with MBW Funds                            | 3587                                      |                                           |                                           | 
| 1397038556  | Associate's Degrees Awarded by Community Colleges         | 12637                                     | 13852                                     | 14269                                     | 
| 1397038563  | For-Credit Certificates Awarded by Community Colleges     | 3337                                      | 3536                                      | 4670                                      | 
| 1397038570  | Private Career School Completions                         | 12712                                     | 14688                                     | 11125                                     | 
| 1397038577  | WIA Occupational Training Program Completions             | 2323                                      | 3178                                      | 2673                                      | 
| 1397038581  | Graduates of Registered Apprenticeships                   | 1457                                      | 1095                                      | 1078                                      | 
| 1397038588  | CTE Graduates with College Credit, Credential or License  | 4001                                      | 4680                                      | 5028                                      | 
| 1397038591  | Occupational Certificates Awarded to Inmates              | 850                                       | 786                                       | 875                                       | 
| 1397038597  | TANF Customers Who Complete Occupational Skills Training. | 311                                       | 859                                       | 2209                                      | 
| 1397038603  | Workforce Training Center Graduates                       | 160                                       | 176                                       | 172                                       | 
```