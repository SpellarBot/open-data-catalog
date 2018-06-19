# Gym Activities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/gym-activities) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/3n2i-j4wu) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/3n2i-j4wu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/3n2i-j4wu/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 3n2i-j4wu |
| Name | Gym Activities |
| Attribution | Department of Recreation |
| Category | Community/Recreation |
| Tags | recreation, gym, activities |
| Created | 2016-09-22T10:03:23Z |
| Publication Date | 2016-10-17T13:49:39Z |

## Description

Department of Recreation Seasonal Open gym Activities. Updated quarterly

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | season      | Season     | text      | text        |
| Yes      | series tag  | category    | Category   | text      | text        |
| Yes      | series tag  | facility    | Facility   | text      | text        |
| Yes      | series tag  | age_group   | Age Group  | text      | text        |
| Yes      | series tag  | day         | Day        | text      | text        |
| Yes      | series tag  | times       | Times      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3n2i-j4wu d:2016-09-22T10:03:26.000Z t:category=Badminton t:facility="Bauer Drive Community Center" t:season="Fall 2016" t:times="6:00pm - 9:45pm" t:age_group="18 & Up" t:day=Tuesday m:row_number.3n2i-j4wu=1

series e:3n2i-j4wu d:2016-09-22T10:03:26.000Z t:category=Basketball t:facility="Bauer Drive Community Center" t:season="Fall 2016" t:times="2:30pm - 5:45pm" t:age_group="Ages 12 - 17" t:day="Monday - Thursday" m:row_number.3n2i-j4wu=2

series e:3n2i-j4wu d:2016-09-22T10:03:26.000Z t:category=Basketball t:facility="Bauer Drive Community Center" t:season="Fall 2016" t:times="8:15pm - 9:45pm" t:age_group="18 & Up" t:day=Thursday m:row_number.3n2i-j4wu=3
```

## Meta Commands

```ls
metric m:row_number.3n2i-j4wu p:long l:"Row Number"

entity e:3n2i-j4wu l:"Gym Activities" t:attribution="Department of Recreation" t:url=https://data.montgomerycountymd.gov/api/views/3n2i-j4wu

property e:3n2i-j4wu t:meta.view v:id=3n2i-j4wu v:category=Community/Recreation v:averageRating=0 v:name="Gym Activities" v:attribution="Department of Recreation"

property e:3n2i-j4wu t:meta.view.owner v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:displayName=Brian

property e:3n2i-j4wu t:meta.view.tableauthor v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:roleName=editor v:displayName=Brian
```

## Top Records

```ls
| :updated_at | season    | category     | facility                     | age_group    | day                | times             | 
| =========== | ========= | ============ | ============================ | ============ | ================== | ================= | 
| 1474538606  | Fall 2016 | Badminton    | Bauer Drive Community Center | 18 & Up      | Tuesday            | 6:00pm - 9:45pm   | 
| 1474538606  | Fall 2016 | Basketball   | Bauer Drive Community Center | Ages 12 - 17 | Monday - Thursday  | 2:30pm - 5:45pm   | 
| 1474538606  | Fall 2016 | Basketball   | Bauer Drive Community Center | 18 & Up      | Thursday           | 8:15pm - 9:45pm   | 
| 1474538606  | Fall 2016 | Basketball   | Bauer Drive Community Center | 55 & Up      | Tuesday & Thursday | 9:00am - 12:00pm  | 
| 1474538606  | Fall 2016 | Basketball   | Bauer Drive Community Center | All Ages     | Saturday           | 2:30pm - 3:45pm   | 
| 1474538606  | Fall 2016 | Microflyers  | Bauer Drive Community Center | 18 & Up      | Wednesday          | 12:30pm - 2:30pm  | 
| 1474538606  | Fall 2016 | Pickleball   | Bauer Drive Community Center | 55 & Up      | Monday             | 12:30pm - 2:15pm  | 
| 1474538606  | Fall 2016 | Table Tennis | Bauer Drive Community Center | 18 & Up      | Tuesday & Thursday | 8:30pm - 9:45pm   | 
| 1474538606  | Fall 2016 | Volleyball   | Bauer Drive Community Center | 18 & Up      | Wednesday          | 8:15pm - 9:45pm   | 
| 1474538606  | Fall 2016 | Volleyball   | Bauer Drive Community Center | 55 & Up      | Monday & Wednesday | 10:30am - 12:30pm | 
```