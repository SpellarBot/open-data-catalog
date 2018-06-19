# STEM STATUS MAJORS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/stem-status-majors-30b2f) |
| Metadata | [Link](https://data.wa.gov/api/views/sesd-j7am) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/sesd-j7am/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/sesd-j7am/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | sesd-j7am |
| Name | STEM STATUS MAJORS |
| Created | 2014-07-21T18:34:11Z |
| Publication Date | 2014-07-23T21:49:27Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | numeric metric | academic_year               | Academic Year               | number    | text        |
| Yes      | numeric metric | cip                         | CIP                         | number    | number      |
| Yes      | series tag     | description_for_6_digit_cip | Description for 6 digit CIP | text      | text        |
| Yes      | series tag     | description_for_4_digit_cip | Description for 4 digit CIP | text      | text        |
| Yes      | series tag     | description_for_2_digit_cip | Description for 2 digit CIP | text      | text        |
| Yes      | series tag     | stem                        | STEM                        | checkbox  | checkbox    |
| Yes      | series tag     | high_demand                 | High Demand                 | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sesd-j7am d:2014-07-21T11:34:14.000Z t:high_demand=true t:stem=true t:description_for_4_digit_cip="Plant Sciences" t:description_for_6_digit_cip="Plant Sciences, Other" t:description_for_2_digit_cip="Agriculture, Agriculture Operations, and Related Sciences" m:academic_year=201213 m:cip=11199

series e:sesd-j7am d:2014-07-21T11:34:14.000Z t:high_demand=true t:stem=true t:description_for_4_digit_cip="Engineering, General" t:description_for_6_digit_cip=Pre-Engineering t:description_for_2_digit_cip=Engineering m:academic_year=201213 m:cip=140102

series e:sesd-j7am d:2014-07-21T11:34:14.000Z t:high_demand=true t:stem=true t:description_for_4_digit_cip="Agricultural Public Services" t:description_for_6_digit_cip="Agricultural and Extension Education Services" t:description_for_2_digit_cip="Agriculture, Agriculture Operations, and Related Sciences" m:academic_year=201213 m:cip=10801
```

## Meta Commands

```ls
metric m:academic_year p:integer l:"Academic Year" t:dataTypeName=number

metric m:cip p:integer l:CIP t:dataTypeName=number

entity e:sesd-j7am l:"STEM STATUS MAJORS" t:url=https://data.wa.gov/api/views/sesd-j7am

property e:sesd-j7am t:meta.view v:id=sesd-j7am v:attributionLink=http://www.ofm.wa.gov/hied/dashboard/glossary.html v:averageRating=0 v:name="STEM STATUS MAJORS"

property e:sesd-j7am t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:sesd-j7am t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | academic_year | cip    | description_for_6_digit_cip                   | description_for_4_digit_cip  | description_for_2_digit_cip                               | stem | high_demand | 
| =========== | ============= | ====== | ============================================= | ============================ | ========================================================= | ==== | =========== | 
| 1405942454  | 201213        | 11199  | Plant Sciences, Other                         | Plant Sciences               | Agriculture, Agriculture Operations, and Related Sciences | true | true        | 
| 1405942454  | 201213        | 140102 | Pre-Engineering                               | Engineering, General         | Engineering                                               | true | true        | 
| 1405942454  | 201213        | 10801  | Agricultural and Extension Education Services | Agricultural Public Services | Agriculture, Agriculture Operations, and Related Sciences | true | true        | 
| 1405942454  | 201213        | 10901  | Animal Sciences, General                      | Animal Sciences              | Agriculture, Agriculture Operations, and Related Sciences | true | true        | 
| 1405942454  | 201213        | 10902  | Agricultural Animal Breeding                  | Animal Sciences              | Agriculture, Agriculture Operations, and Related Sciences | true | true        | 
| 1405942454  | 201213        | 10903  | Animal Health                                 | Animal Sciences              | Agriculture, Agriculture Operations, and Related Sciences | true | true        | 
| 1405942454  | 201213        | 10904  | Animal Nutrition                              | Animal Sciences              | Agriculture, Agriculture Operations, and Related Sciences | true | true        | 
| 1405942454  | 201213        | 10905  | Dairy Science                                 | Animal Sciences              | Agriculture, Agriculture Operations, and Related Sciences | true | true        | 
| 1405942454  | 201213        | 10906  | Livestock Management                          | Animal Sciences              | Agriculture, Agriculture Operations, and Related Sciences | true | true        | 
| 1405942454  | 201213        | 10907  | Poultry Science                               | Animal Sciences              | Agriculture, Agriculture Operations, and Related Sciences | true | true        | 
```