# Schools Participating in Statewide Algebra Challenge

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/schools-participating-in-statewide-algebra-challenge-829ed) |
| Metadata | [Link](https://data.wa.gov/api/views/bbfi-8qfv) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/bbfi-8qfv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/bbfi-8qfv/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | bbfi-8qfv |
| Name | Schools Participating in Statewide Algebra Challenge |
| Attribution | Center for Games Science - UW |
| Category | Education |
| Tags | broadband, education |
| Created | 2013-05-30T17:50:50Z |
| Publication Date | 2013-05-30T20:35:38Z |

## Description

We believe that Washington State classrooms in grades K-12 can complete 250,000 algebra equations in one week, even if they have never been exposed to algebra before! Join the challenge and your classroom will receive sponsored access to the school-adapted algebra learning game DragonBox along with teacher support tools and resources.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | county             | County             | text      | text        |
| Yes      | series tag     | school             | School             | text      | text        |
| Yes      | numeric metric | grade              | Grade              | number    | number      |
| Yes      | numeric metric | number_of_students | Number of Students | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bbfi-8qfv d:2013-05-30T10:50:52.000Z t:school="South Whidbey Elementary-" t:county=Island m:number_of_students=24 m:grade=3

series e:bbfi-8qfv d:2013-05-30T10:50:52.000Z t:school="South Whidbey High" t:county=Island m:number_of_students=60 m:grade=9

series e:bbfi-8qfv d:2013-05-30T10:50:52.000Z t:school="Ballard High" t:county=King m:number_of_students=100 m:grade=9
```

## Meta Commands

```ls
metric m:grade p:integer l:Grade t:dataTypeName=number

metric m:number_of_students p:integer l:"Number of Students" t:dataTypeName=number

entity e:bbfi-8qfv l:"Schools Participating in Statewide Algebra Challenge" t:attribution="Center for Games Science - UW" t:url=https://data.wa.gov/api/views/bbfi-8qfv

property e:bbfi-8qfv t:meta.view v:id=bbfi-8qfv v:category=Education v:attributionLink=http://algebrachallenge.org v:averageRating=0 v:name="Schools Participating in Statewide Algebra Challenge" v:attribution="Center for Games Science - UW"

property e:bbfi-8qfv t:meta.view.license v:name="Public Domain"

property e:bbfi-8qfv t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:bbfi-8qfv t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | county | school                               | grade | number_of_students | 
| =========== | ====== | ==================================== | ===== | ================== | 
| 1369911052  | Island | South Whidbey Elementary-            | 3     | 24                 | 
| 1369911052  | Island | South Whidbey High                   | 9     | 60                 | 
| 1369911052  | King   | Ballard High                         | 9     | 100                | 
| 1369911052  | King   | CLIP                                 | 11    | 15                 | 
| 1369911052  | King   | Grand Reidge Elementary              | 4     | 27                 | 
| 1369911052  | Kitsap | Eagle Harbor High                    | 9     | 30                 | 
| 1369911052  | Kitsap | Sonoji Sakai Intermediate            | 5     | 48                 | 
| 1369911052  | Kitsap | Capt Johnstn Blakely Elem -2 classes | 3     | 48                 | 
| 1369911052  | Kitsap | Woodward Middle                      | 7     | 99                 | 
| 1369911052  | Kitsap | Capt Charles Wilkes                  | 3     | 25                 | 
```