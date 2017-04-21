# Winter 2017 Open Gym Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/winter-2017-open-gym-schedule) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/4z6a-8zhq) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/4z6a-8zhq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/4z6a-8zhq/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 4z6a-8zhq |
| Name | Winter 2017 Open Gym Schedule |
| Category | Community/Recreation |
| Tags | gym, recreation |
| Created | 2017-01-17T10:41:38Z |
| Publication Date | 2017-01-17T10:55:00Z |

## Description

Open gym activities winter schedule

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type | Render Type |
| ======== | =========== | ========== | ========= | ========= | =========== |
| Yes      | series tag  | category   | Category  | text      | text        |
| Yes      | series tag  | facility   | Facility  | text      | text        |
| Yes      | series tag  | age_group  | Age Group | text      | text        |
| Yes      | series tag  | day        | Day       | text      | text        |
| Yes      | series tag  | times      | Times     | text      | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4z6a-8zhq d:2017-01-01T00:00:00.000Z t:category=Badminton t:facility="Bauer Drive Community Center" t:times="6:00pm - 9:45pm" t:age_group="18 & Up" t:day=Tuesday m:row_number.4z6a-8zhq=1

series e:4z6a-8zhq d:2017-01-01T00:00:00.000Z t:category=Basketball t:facility="Bauer Drive Community Center" t:times="2:30pm - 5:45pm" t:age_group="Ages 12 - 17" t:day="Monday - Thursday" m:row_number.4z6a-8zhq=2

series e:4z6a-8zhq d:2017-01-01T00:00:00.000Z t:category=Basketball t:facility="Bauer Drive Community Center" t:times="8:15pm - 9:45pm" t:age_group="18 & Up" t:day=Thursday m:row_number.4z6a-8zhq=3
```

## Meta Commands

```ls
metric m:row_number.4z6a-8zhq p:long l:"Row Number"

entity e:4z6a-8zhq l:"Winter 2017 Open Gym Schedule" t:url=https://data.montgomerycountymd.gov/api/views/4z6a-8zhq

property e:4z6a-8zhq t:meta.view v:id=4z6a-8zhq v:category=Community/Recreation v:averageRating=0 v:name="Winter 2017 Open Gym Schedule"

property e:4z6a-8zhq t:meta.view.owner v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:displayName=Brian

property e:4z6a-8zhq t:meta.view.tableauthor v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:roleName=editor v:displayName=Brian
```

## Top Records

```ls
| category         | facility                     | age_group    | day                | times             | 
| ================ | ============================ | ============ | ================== | ================= | 
| Badminton        | Bauer Drive Community Center | 18 & Up      | Tuesday            | 6:00pm - 9:45pm   | 
| Basketball       | Bauer Drive Community Center | Ages 12 - 17 | Monday - Thursday  | 2:30pm - 5:45pm   | 
| Basketball       | Bauer Drive Community Center | 18 & Up      | Thursday           | 8:15pm - 9:45pm   | 
| Basketball       | Bauer Drive Community Center | 55 & Up      | Tuesday & Thursday | 9:00am - 12:00pm  | 
| Ultimate Frisbee | Bauer Drive Community Center | 18 & Up      | Thursday           | 6:00pm - 8:00pm   | 
| Microflyers      | Bauer Drive Community Center | 18 & Up      | Wednesday          | 12:30pm - 2:30pm  | 
| Pickleball       | Bauer Drive Community Center | 55 & Up      | Monday             | 12:30pm - 2:15pm  | 
| Table Tennis     | Bauer Drive Community Center | 18 & Up      | Tuesday & Thursday | 8:30pm - 9:45pm   | 
| Volleyball       | Bauer Drive Community Center | 18 & Up      | Wednesday          | 8:15pm - 9:45pm   | 
| Volleyball       | Bauer Drive Community Center | 55 & Up      | Monday & Wednesday | 10:30am - 12:30pm | 
```