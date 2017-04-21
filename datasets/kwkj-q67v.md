# Bsk-secondary-indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bsk-secondary-indicators) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/kwkj-q67v) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/kwkj-q67v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/kwkj-q67v/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | kwkj-q67v |
| Name | Bsk-secondary-indicators |
| Created | 2016-10-20T20:46:34Z |
| Publication Date | 2017-04-17T16:11:49Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                 | Data Type | Render Type |
| ======== | =========== | =================== | ==================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | investment_area     | Investment Area      | text      | text        |
| Yes      | series tag  | headline_indicator  | Headline Indicator   | text      | text        |
| Yes      | series tag  | secondary_indicator | Secondary Indicator  | text      | text        |
| Yes      | series tag  | headline_url        | Headline URL         | url       | url         |
| Yes      | series tag  | secondary_url       | Secondary URL        | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kwkj-q67v d:2017-03-06T22:07:27.000Z t:secondary_indicator="Youth and family homelessness" t:headline_indicator="Chronic absenteeism" t:headline_url=http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/chronic-absenteeism.aspx t:investment_area="Youth and Family Homeless Prevention" m:row_number.kwkj-q67v=1

series e:kwkj-q67v d:2017-03-06T22:07:27.000Z t:secondary_indicator="Youth and family homelessness" t:headline_indicator="Education and employment" t:headline_url=http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/education-employment.aspx t:investment_area="Youth and Family Homeless Prevention" m:row_number.kwkj-q67v=2

series e:kwkj-q67v d:2017-03-07T16:20:35.000Z t:secondary_indicator="Pediatrician knowledge of community resources" t:headline_indicator="Abuse and neglect" t:headline_url=http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/abuse-neglect.aspx t:investment_area=Prenatal?5 m:row_number.kwkj-q67v=3
```

## Meta Commands

```ls
metric m:row_number.kwkj-q67v p:long l:"Row Number"

entity e:kwkj-q67v l:Bsk-secondary-indicators t:url=https://data.kingcounty.gov/api/views/kwkj-q67v

property e:kwkj-q67v t:meta.view v:id=kwkj-q67v v:averageRating=0 v:name=Bsk-secondary-indicators

property e:kwkj-q67v t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:kwkj-q67v t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | investment_area                      | headline_indicator        | secondary_indicator                           | headline_url                                                                                                                                              | secondary_url | 
| =========== | ==================================== | ========================= | ============================================= | ========================================================================================================================================================= | ============= | 
| 1488838047  | Youth and Family Homeless Prevention | Chronic absenteeism       | Youth and family homelessness                 | [http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/chronic-absenteeism.aspx, null]   | [null, null]  | 
| 1488838047  | Youth and Family Homeless Prevention | Education and employment  | Youth and family homelessness                 | [http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/education-employment.aspx, null]  | [null, null]  | 
| 1488903635  | Prenatal?5                           | Abuse and neglect         | Pediatrician knowledge of community resources | [http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/abuse-neglect.aspx, null]         | [null, null]  | 
| 1488903637  | Prenatal?5                           | Abuse and neglect         | Quality relationships                         | [http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/abuse-neglect.aspx, null]         | [null, null]  | 
| 1488903638  | Prenatal?5                           | Abuse and neglect         | Receive health and developmental screening    | [http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/abuse-neglect.aspx, null]         | [null, null]  | 
| 1488903638  | Prenatal?5                           | Abuse and neglect         | Family supports                               | [http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/abuse-neglect.aspx, null]         | [null, null]  | 
| 1488903639  | Prenatal?5                           | Abuse and neglect         | Parent knowledge of child development         | [http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/abuse-neglect.aspx, null]         | [null, null]  | 
| 1488903643  | Prenatal?5                           | Flourishing and resilient | Receive recommended developmental services    | [http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/flourishing-resilient.aspx, null] | [null, null]  | 
| 1488903644  | Prenatal?5                           | Flourishing and resilient | Quality child care                            | [http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/flourishing-resilient.aspx, null] | [null, null]  | 
| 1488903647  | Prenatal?5                           | Flourishing and resilient | Parent knowledge of child development         | [http://www.kingcounty.gov/elected/executive/constantine/initiatives/best-starts-for-kids/dashboards/primary-indicators/flourishing-resilient.aspx, null] | [null, null]  | 
```