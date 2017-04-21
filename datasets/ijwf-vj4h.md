# Recreation Spring Open Gym Activities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recreation-spring-open-gym-activities) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/ijwf-vj4h) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/ijwf-vj4h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/ijwf-vj4h/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | ijwf-vj4h |
| Name | Recreation Spring Open Gym Activities |
| Attribution | Montgomery County, MD |
| Category | Community/Recreation |
| Tags | badminton, basketball, volleyball, gym, tiny tots, pickle ball, ping pong |
| Created | 2016-05-24T21:33:56Z |
| Publication Date | 2016-06-01T13:15:36Z |

## Description

Montgomery County Recreatoin Spring Gym Activities

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | activity          | Activity          | text      | text        |
| Yes      | series tag  | recreation_center | Recreation Center | text      | text        |
| No       |             | address           | Address           | text      | text        |
| Yes      | series tag  | phone_number      | Phone Number      | text      | text        |
| Yes      | series tag  | age_requirements  | Age Requirements  | text      | text        |
| No       |             | days_of_week      | Days of Week      | text      | text        |
| Yes      | series tag  | times             | Times             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,days_of_week
```

## Data Commands

```ls
series e:ijwf-vj4h d:2016-05-25T08:21:07.000Z t:phone_number=240-777-8088 t:recreation_center="Wisconson Place" t:times=12:00PM-3:00PM t:age_requirements=Family t:activity=Basketball m:row_number.ijwf-vj4h=1

series e:ijwf-vj4h d:2016-05-25T08:21:07.000Z t:phone_number=240-777-6960 t:recreation_center=Potomac t:times="12:00PM=1:30PM" t:age_requirements="Seniors 55+" t:activity=Basketball m:row_number.ijwf-vj4h=2

series e:ijwf-vj4h d:2016-05-25T08:21:07.000Z t:phone_number=240-777-6820 t:recreation_center="Mid County" t:times=12:00PM-2:00PM t:age_requirements="Seniors 55+" t:activity=Volleyball m:row_number.ijwf-vj4h=3
```

## Meta Commands

```ls
metric m:row_number.ijwf-vj4h p:long l:"Row Number"

entity e:ijwf-vj4h l:"Recreation Spring Open Gym Activities" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/ijwf-vj4h

property e:ijwf-vj4h t:meta.view v:id=ijwf-vj4h v:category=Community/Recreation v:averageRating=0 v:name="Recreation Spring Open Gym Activities" v:attribution="Montgomery County, MD"

property e:ijwf-vj4h t:meta.view.license v:name="Public Domain"

property e:ijwf-vj4h t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:ijwf-vj4h t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| :updated_at | activity   | recreation_center | address                                    | phone_number | age_requirements | days_of_week     | times          | 
| =========== | ========== | ================= | ========================================== | ============ | ================ | ================ | ============== | 
| 1464164467  | Basketball | Wisconson Place   | 5311 Friendship Boulevard, Chevy Chase MD  | 240-777-8088 | Family           | Saturday         | 12:00PM-3:00PM | 
| 1464164467  | Basketball | Potomac           | 11315 falls Road, Potomac MD               | 240-777-6960 | Seniors 55+      | Wednesday        | 12:00PM=1:30PM | 
| 1464164467  | Volleyball | Mid County        | 2004 Queensguard Road, Silver Spring MD    | 240-777-6820 | Seniors 55+      | Friday           | 12:00PM-2:00PM | 
| 1464164467  | Volleyball | Germantown        | 18905 Kingsview Drive, Germantown MD       | 240-777-8095 | Adult 18+        | Wednesday        | 6:00PM-8:45PM  | 
| 1464164467  | Basketball | East County       | 3310 Gateshead Manor Way, Silver Spring MD | 240-777-8090 | Adult 18+        | Monday-Thursday  | 11:30AM-1:30PM | 
| 1464164467  | Basketball | Praisner          | 14906 Old Columbia Pike, Burtonsville MD   | 240-777-4970 | Adult 18+        | Monday-Wednesday | 6:30PM-8:50PM  | 
| 1464164467  | Basketball | Lawton            | 4301 Willow Lane, Chevy Chase MD           | 240-777-6855 | Adult 18+        | Saturday         | 3:00PM-5:00PM  | 
| 1464164467  | Basketball | Mid County        | 2004 Queensguard Road, Silver Spring MD    | 240-777-6820 | Youth 17 & Under | Monday-Thursday  | 2:30PM-6:00PM  | 
| 1464164467  | Basketball | Plum Gar          | 19561 Scenery Drive, Germantown MD         | 240-777-4919 | Adult 18+        | Friday           | 1:00PM-2:30PM  | 
| 1464164467  | Basketball | Germantown        | 18905 Kingsview Drive, Germantown MD       | 240-777-8095 | Youth-MS&HS      | Friday           | 3:00PM-4:45PM  | 
```