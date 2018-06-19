# Project Reads Scores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/project-reads-scores) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/97iy-g8hk) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/97iy-g8hk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/97iy-g8hk/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | 97iy-g8hk |
| Name | Project Reads Scores |
| Attribution | City of Jackson Human and Cultural Services |
| Category | Schools and Education |
| Created | 2016-08-16T20:47:29Z |
| Publication Date | 2016-09-22T22:45:06Z |

## Description

This data looks at the scores of all project reads participants in the City of Jackson's early childhood care facilities.  This data is updated each time a test is given to our young learners.  Project Reads focuses on ensuring that the City is taking a hands on approach to promote literacy in our childcare facilities.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | time           | test_year         | Test Year         | calendar_date | calendar_date |
| Yes      | series tag     | test_type         | Test Type         | text          | text          |
| Yes      | series tag     | test_site         | Test Site         | text          | text          |
| Yes      | series tag     | student_id        | Student ID        | text          | text          |
| Yes      | numeric metric | pre_test_score    | Pre-Test Score    | number        | number        |
| Yes      | numeric metric | pre_test          | Pre-Test (%)      | percent       | percent       |
| Yes      | numeric metric | post_test_score   | Post-Test Score   | number        | number        |
| Yes      | numeric metric | post_test         | Post-Test (%)     | percent       | percent       |
| Yes      | numeric metric | percentage_change | Percentage Change | percent       | percent       |
| Yes      | numeric metric | unit_1_score      | Unit 1 Score      | number        | number        |
| Yes      | numeric metric | unit_1            | Unit 1 (%)        | percent       | percent       |
| Yes      | numeric metric | unit_2_score      | Unit 2 Score      | number        | number        |
| Yes      | numeric metric | unit_2            | Unit 2 (%)        | percent       | percent       |
| Yes      | numeric metric | unit_3_score      | Unit 3 Score      | number        | number        |
| Yes      | numeric metric | unit_3            | Unit 3 (%)        | percent       | percent       |
| Yes      | numeric metric | unit_4_score      | Unit 4 Score      | number        | number        |
| Yes      | numeric metric | unit_4            | Unit 4 (%)        | percent       | percent       |
| Yes      | numeric metric | unit_5_6_score    | Unit 5/6 Score    | number        | number        |
| Yes      | numeric metric | unit_5_6          | Unit 5/6 (%)      | percent       | percent       |
| Yes      | numeric metric | unit_7_score      | Unit 7 Score      | number        | number        |
| Yes      | numeric metric | unit_7            | Unit 7 (%)        | percent       | percent       |
| Yes      | numeric metric | unit_8_score      | Unit 8 Score      | number        | number        |
| Yes      | numeric metric | unit_8            | Unit 8 (%)        | percent       | percent       |
| Yes      | numeric metric | total_score       | Total Score       | number        | number        |
| Yes      | numeric metric | total_correct     | Total (%) Correct | percent       | percent       |
```

## Time Field

```ls
Value = test_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:97iy-g8hk d:2016-06-01T00:00:00.000Z t:student_id="Virden 1" t:test_site=VIRDEN t:test_type="YEAR END" m:post_test=61 m:unit_1=12 m:unit_2=16 m:percentage_change=32 m:unit_7_score=22 m:total_correct=41 m:total_score=207 m:unit_5_6=37 m:unit_2_score=4 m:unit_3=24 m:unit_8_score=18 m:unit_4=27 m:unit_7=63 m:unit_8=60 m:pre_test=29 m:unit_3_score=6 m:post_test_score=92 m:pre_test_score=43 m:unit_5_6_score=11 m:unit_4_score=8 m:unit_1_score=3

series e:97iy-g8hk d:2016-06-01T00:00:00.000Z t:student_id="Virden 2" t:test_site=VIRDEN t:test_type="YEAR END" m:post_test=69 m:unit_1=20 m:unit_2=20 m:percentage_change=38 m:unit_7_score=20 m:total_correct=45 m:total_score=224 m:unit_5_6=37 m:unit_2_score=5 m:unit_3=24 m:unit_8_score=19 m:unit_4=27 m:unit_7=57 m:unit_8=63 m:pre_test=31 m:unit_3_score=6 m:post_test_score=104 m:pre_test_score=46 m:unit_5_6_score=11 m:unit_4_score=8 m:unit_1_score=5

series e:97iy-g8hk d:2016-06-01T00:00:00.000Z t:student_id="Virden 3" t:test_site=VIRDEN t:test_type="YEAR END" m:post_test=50 m:unit_1=16 m:unit_2=16 m:percentage_change=24 m:unit_7_score=19 m:total_correct=39 m:total_score=193 m:unit_5_6=53 m:unit_2_score=4 m:unit_3=24 m:unit_8_score=21 m:unit_4=30 m:unit_7=54 m:unit_8=70 m:pre_test=26 m:unit_3_score=6 m:post_test_score=75 m:pre_test_score=39 m:unit_5_6_score=16 m:unit_4_score=9 m:unit_1_score=4
```

## Meta Commands

```ls
metric m:pre_test_score p:integer l:"Pre-Test Score" d:"Phonics Assessment 1 Pre-Test" t:dataTypeName=number

metric m:pre_test p:integer l:"Pre-Test (%)" d:"Phonics Assessment 1 Pre-test percentage correct score" t:dataTypeName=percent

metric m:post_test_score p:integer l:"Post-Test Score" d:"Phonics Assessment 1 Post-test score" t:dataTypeName=number

metric m:post_test p:integer l:"Post-Test (%)" d:"Phonics Assessment 1 Post-test percentage correct score" t:dataTypeName=percent

metric m:percentage_change p:integer l:"Percentage Change" d:"Percentage increase or decrease in score" t:dataTypeName=percent

metric m:unit_1_score p:integer l:"Unit 1 Score" t:dataTypeName=number

metric m:unit_1 p:integer l:"Unit 1 (%)" t:dataTypeName=percent

metric m:unit_2_score p:integer l:"Unit 2 Score" t:dataTypeName=number

metric m:unit_2 p:integer l:"Unit 2 (%)" t:dataTypeName=percent

metric m:unit_3_score p:integer l:"Unit 3 Score" t:dataTypeName=number

metric m:unit_3 p:integer l:"Unit 3 (%)" t:dataTypeName=percent

metric m:unit_4_score p:integer l:"Unit 4 Score" t:dataTypeName=number

metric m:unit_4 p:integer l:"Unit 4 (%)" t:dataTypeName=percent

metric m:unit_5_6_score p:integer l:"Unit 5/6 Score" t:dataTypeName=number

metric m:unit_5_6 p:integer l:"Unit 5/6 (%)" t:dataTypeName=percent

metric m:unit_7_score p:integer l:"Unit 7 Score" t:dataTypeName=number

metric m:unit_7 p:integer l:"Unit 7 (%)" t:dataTypeName=percent

metric m:unit_8_score p:integer l:"Unit 8 Score" t:dataTypeName=number

metric m:unit_8 p:integer l:"Unit 8 (%)" t:dataTypeName=percent

metric m:total_score p:integer l:"Total Score" t:dataTypeName=number

metric m:total_correct p:integer l:"Total (%) Correct" t:dataTypeName=percent

entity e:97iy-g8hk l:"Project Reads Scores" t:attribution="City of Jackson Human and Cultural Services" t:url=https://data.jacksonms.gov/api/views/97iy-g8hk

property e:97iy-g8hk t:meta.view v:id=97iy-g8hk v:category="Schools and Education" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Project Reads Scores" v:attribution="City of Jackson Human and Cultural Services"

property e:97iy-g8hk t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:97iy-g8hk t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| test_year           | test_type | test_site | student_id | pre_test_score | pre_test | post_test_score | post_test | percentage_change | unit_1_score | unit_1 | unit_2_score | unit_2 | unit_3_score | unit_3 | unit_4_score | unit_4 | unit_5_6_score | unit_5_6 | unit_7_score | unit_7 | unit_8_score | unit_8 | total_score | total_correct | 
| =================== | ========= | ========= | ========== | ============== | ======== | =============== | ========= | ================= | ============ | ====== | ============ | ====== | ============ | ====== | ============ | ====== | ============== | ======== | ============ | ====== | ============ | ====== | =========== | ============= | 
| 2016-06-01T00:00:00 | YEAR END  | VIRDEN    | Virden 1   | 43             | 29       | 92              | 61        | 32                | 3            | 12     | 4            | 16     | 6            | 24     | 8            | 27     | 11             | 37       | 22           | 63     | 18           | 60     | 207         | 41            | 
| 2016-06-01T00:00:00 | YEAR END  | VIRDEN    | Virden 2   | 46             | 31       | 104             | 69        | 38                | 5            | 20     | 5            | 20     | 6            | 24     | 8            | 27     | 11             | 37       | 20           | 57     | 19           | 63     | 224         | 45            | 
| 2016-06-01T00:00:00 | YEAR END  | VIRDEN    | Virden 3   | 39             | 26       | 75              | 50        | 24                | 4            | 16     | 4            | 16     | 6            | 24     | 9            | 30     | 16             | 53       | 19           | 54     | 21           | 70     | 193         | 39            | 
| 2016-06-01T00:00:00 | YEAR END  | VIRDEN    | Virden 4   | 35             | 23       | 115             | 77        | 54                | 4            | 16     | 4            | 16     | 6            | 24     | 10           | 33     | 13             | 43       | 18           | 51     | 18           | 60     | 223         | 45            | 
| 2016-06-01T00:00:00 | YEAR END  | VIRDEN    | Virden 5   | 46             | 31       | 85              | 57        | 26                | 2            | 8      | 5            | 20     | 6            | 24     | 7            | 23     | 12             | 40       | 19           | 54     | 16           | 53     | 198         | 40            | 
| 2016-06-01T00:00:00 | YEAR END  | VIRDEN    | Virden 6   | 35             | 23       | 91              | 61        | 38                | 5            | 20     | 5            | 20     | 7            | 28     | 7            | 23     | 18             | 60       | 23           | 66     | 19           | 63     | 210         | 42            | 
| 2016-06-01T00:00:00 | YEAR END  | VIRDEN    | Virden 7   | 40             | 27       | 96              | 64        | 37                | 5            | 20     | 5            | 20     | 6            | 24     | 7            | 23     | 11             | 37       | 21           | 60     | 20           | 67     | 211         | 42            | 
| 2016-06-01T00:00:00 | YEAR END  | VIRDEN    | Virden 8   | 39             | 26       | 74              | 49        | 23                | 4            | 16     | 5            | 20     | 5            | 20     | 8            | 27     | 12             | 40       | 16           | 46     | 17           | 57     | 180         | 36            | 
| 2016-06-01T00:00:00 | YEAR END  | VIRDEN    | Virden 9   | 40             | 27       | 90              | 60        | 33                | 6            | 24     | 4            | 16     | 5            | 20     | 8            | 27     | 15             | 50       | 18           | 51     | 20           | 67     | 206         | 41            | 
| 2016-06-01T00:00:00 | YEAR END  | VIRDEN    | Virden 10  | 45             | 30       | 86              | 57        | 27                | 4            | 16     | 5            | 20     | 5            | 20     | 7            | 23     | 14             | 47       | 21           | 60     | 19           | 63     | 206         | 41            | 
```