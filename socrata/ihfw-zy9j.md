# School Demographics and Accountability Snapshot 2006-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-demographics-and-accountability-snapshot-2006-2012-c1960) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ihfw-zy9j) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ihfw-zy9j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ihfw-zy9j/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ihfw-zy9j |
| Name | School Demographics and Accountability Snapshot 2006-2012 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | demographic, accountability, school, lifelong learning |
| Created | 2013-02-21T05:15:19Z |
| Publication Date | 2013-02-21T05:16:34Z |

## Description

Annual school accounts of NYC public school student populations served by grade, special programs, ethnicity, gender and Title I funded programs. 

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | dbn               | DBN               | text      | text        |
| Yes      | series tag     | name              | Name              | text      | text        |
| Yes      | numeric metric | schoolyear        | schoolyear        | number    | text        |
| Yes      | series tag     | fl_percent        | fl_percent        | text      | text        |
| Yes      | numeric metric | frl_percent       | frl_percent       | number    | text        |
| Yes      | numeric metric | total_enrollment  | total_enrollment  | number    | text        |
| Yes      | series tag     | prek              | prek              | text      | text        |
| No       |                | k                 | k                 | text      | text        |
| Yes      | series tag     | grade1            | grade1            | text      | text        |
| Yes      | series tag     | grade2            | grade2            | text      | text        |
| Yes      | series tag     | grade3            | grade3            | text      | text        |
| Yes      | series tag     | grade4            | grade4            | text      | text        |
| Yes      | series tag     | grade5            | grade5            | text      | text        |
| Yes      | series tag     | grade6            | grade6            | text      | text        |
| Yes      | series tag     | grade7            | grade7            | text      | text        |
| Yes      | series tag     | grade8            | grade8            | text      | text        |
| Yes      | series tag     | grade9            | grade9            | text      | text        |
| Yes      | series tag     | grade10           | grade10           | text      | text        |
| Yes      | series tag     | grade11           | grade11           | text      | text        |
| Yes      | series tag     | grade12           | grade12           | text      | text        |
| Yes      | series tag     | ell_num           | ell_num           | text      | text        |
| Yes      | numeric metric | ell_percent       | ell_percent       | number    | text        |
| Yes      | numeric metric | sped_num          | sped_num          | number    | text        |
| Yes      | numeric metric | sped_percent      | sped_percent      | number    | text        |
| Yes      | series tag     | ctt_num           | ctt_num           | text      | text        |
| Yes      | series tag     | selfcontained_num | selfcontained_num | text      | text        |
| Yes      | numeric metric | asian_num         | asian_num         | number    | text        |
| Yes      | numeric metric | asian_per         | asian_per         | number    | text        |
| Yes      | numeric metric | black_num         | black_num         | number    | text        |
| Yes      | numeric metric | black_per         | black_per         | number    | text        |
| Yes      | numeric metric | hispanic_num      | hispanic_num      | number    | text        |
| Yes      | numeric metric | hispanic_per      | hispanic_per      | number    | text        |
| Yes      | numeric metric | white_num         | white_num         | number    | text        |
| Yes      | numeric metric | white_per         | white_per         | number    | text        |
| Yes      | numeric metric | male_num          | male_num          | number    | text        |
| Yes      | numeric metric | male_per          | male_per          | number    | text        |
| Yes      | numeric metric | female_num        | female_num        | number    | text        |
| Yes      | numeric metric | female_per        | female_per        | number    | text        |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = k
```

## Data Commands

```ls
series e:ihfw-zy9j d:2006-01-01T00:00:00.000Z t:ell_num=36 t:selfcontained_num=9 t:dbn=01M015 t:prek=15 t:name="P.S. 015 ROBERTO CLEMENTE" t:grade3=38 t:grade4=52 t:ctt_num=25 t:grade5=29 t:grade6=38 t:grade1=40 t:grade2=33 t:fl_percent=89.4 m:sped_num=57 m:asian_per=3.6 m:black_num=74 m:hispanic_per=67.3 m:ell_percent=12.8 m:hispanic_num=189 m:female_num=123 m:white_per=1.8 m:male_num=158 m:schoolyear=20052006 m:total_enrollment=281 m:black_per=26.3 m:white_num=5 m:asian_num=10 m:female_per=43.8 m:male_per=56.2 m:sped_percent=20.3

series e:ihfw-zy9j d:2006-01-01T00:00:00.000Z t:prek=15 t:dbn=01M015 t:name="P.S. 015 ROBERTO CLEMENTE" t:grade3=34 t:ctt_num=19 t:grade4=42 t:grade5=46 t:grade1=39 t:selfcontained_num=15 t:ell_num=38 t:grade2=38 t:fl_percent=89.4 m:sped_num=55 m:asian_per=7.4 m:black_num=68 m:hispanic_per=63 m:ell_percent=15.6 m:hispanic_num=153 m:female_num=103 m:white_per=1.6 m:male_num=140 m:schoolyear=20062007 m:total_enrollment=243 m:black_per=28 m:white_num=4 m:asian_num=18 m:female_per=42.4 m:male_per=57.6 m:sped_percent=22.6

series e:ihfw-zy9j d:2006-01-01T00:00:00.000Z t:prek=18 t:dbn=01M015 t:name="P.S. 015 ROBERTO CLEMENTE" t:grade3=38 t:ctt_num=20 t:grade4=47 t:grade5=40 t:grade1=39 t:selfcontained_num=14 t:ell_num=52 t:grade2=36 t:fl_percent=89.4 m:sped_num=60 m:asian_per=6.1 m:black_num=77 m:hispanic_per=60.2 m:ell_percent=19.9 m:hispanic_num=157 m:female_num=118 m:white_per=2.7 m:male_num=143 m:schoolyear=20072008 m:total_enrollment=261 m:black_per=29.5 m:white_num=7 m:asian_num=16 m:female_per=45.2 m:male_per=54.8 m:sped_percent=23
```

## Meta Commands

```ls
metric m:schoolyear p:integer l:schoolyear t:dataTypeName=number

metric m:frl_percent p:float l:frl_percent t:dataTypeName=number

metric m:total_enrollment p:integer l:total_enrollment t:dataTypeName=number

metric m:ell_percent p:float l:ell_percent t:dataTypeName=number

metric m:sped_num p:integer l:sped_num t:dataTypeName=number

metric m:sped_percent p:float l:sped_percent t:dataTypeName=number

metric m:asian_num p:integer l:asian_num t:dataTypeName=number

metric m:asian_per p:float l:asian_per t:dataTypeName=number

metric m:black_num p:integer l:black_num t:dataTypeName=number

metric m:black_per p:float l:black_per t:dataTypeName=number

metric m:hispanic_num p:integer l:hispanic_num t:dataTypeName=number

metric m:hispanic_per p:float l:hispanic_per t:dataTypeName=number

metric m:white_num p:integer l:white_num t:dataTypeName=number

metric m:white_per p:float l:white_per t:dataTypeName=number

metric m:male_num p:integer l:male_num t:dataTypeName=number

metric m:male_per p:float l:male_per t:dataTypeName=number

metric m:female_num p:integer l:female_num t:dataTypeName=number

metric m:female_per p:float l:female_per t:dataTypeName=number

entity e:ihfw-zy9j l:"School Demographics and Accountability Snapshot 2006-2012" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ihfw-zy9j

property e:ihfw-zy9j t:meta.view v:id=ihfw-zy9j v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/F318E6F9-5787-403E-8ABD-139656D7A06E/0/DemographicSnapshot2012Public.xlsx v:averageRating=0 v:name="School Demographics and Accountability Snapshot 2006-2012" v:attribution="Department of Education (DOE)"

property e:ihfw-zy9j t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ihfw-zy9j t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | name                      | schoolyear | fl_percent | frl_percent | total_enrollment | prek | k  | grade1 | grade2 | grade3 | grade4 | grade5 | grade6 | grade7 | grade8 | grade9 | grade10 | grade11 | grade12 | ell_num | ell_percent | sped_num | sped_percent | ctt_num | selfcontained_num | asian_num | asian_per | black_num | black_per | hispanic_num | hispanic_per | white_num | white_per | male_num | male_per | female_num | female_per | 
| ====== | ========================= | ========== | ========== | =========== | ================ | ==== | == | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ======= | =========== | ======== | ============ | ======= | ================= | ========= | ========= | ========= | ========= | ============ | ============ | ========= | ========= | ======== | ======== | ========== | ========== | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 20052006   | 89.4       |             | 281              | 15   | 36 | 40     | 33     | 38     | 52     | 29     | 38     |        |        |        |         |         |         | 36      | 12.8        | 57       | 20.3         | 25      | 9                 | 10        | 3.6       | 74        | 26.3      | 189          | 67.3         | 5         | 1.8       | 158      | 56.2     | 123        | 43.8       | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 20062007   | 89.4       |             | 243              | 15   | 29 | 39     | 38     | 34     | 42     | 46     |        |        |        |        |         |         |         | 38      | 15.6        | 55       | 22.6         | 19      | 15                | 18        | 7.4       | 68        | 28        | 153          | 63           | 4         | 1.6       | 140      | 57.6     | 103        | 42.4       | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 20072008   | 89.4       |             | 261              | 18   | 43 | 39     | 36     | 38     | 47     | 40     |        |        |        |        |         |         |         | 52      | 19.9        | 60       | 23           | 20      | 14                | 16        | 6.1       | 77        | 29.5      | 157          | 60.2         | 7         | 2.7       | 143      | 54.8     | 118        | 45.2       | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 20082009   | 89.4       |             | 252              | 17   | 37 | 44     | 32     | 34     | 39     | 49     |        |        |        |        |         |         |         | 48      | 19          | 62       | 24.6         | 21      | 17                | 16        | 6.3       | 75        | 29.8      | 149          | 59.1         | 7         | 2.8       | 149      | 59.1     | 103        | 40.9       | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 20092010   |            | 96.5        | 208              | 16   | 40 | 28     | 32     | 30     | 24     | 38     |        |        |        |        |         |         |         | 40      | 19.2        | 46       | 22.1         | 14      | 14                | 16        | 7.7       | 67        | 32.2      | 118          | 56.7         | 6         | 2.9       | 124      | 59.6     | 84         | 40.4       | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 20102011   |            | 96.5        | 203              | 13   | 37 | 35     | 33     | 30     | 30     | 25     |        |        |        |        |         |         |         | 30      | 14.8        | 46       | 22.7         | 21      | 9                 | 13        | 6.4       | 75        | 36.9      | 110          | 54.2         | 4         | 2         | 113      | 55.7     | 90         | 44.3       | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 20112012   |            | 89.4        | 189              | 13   | 31 | 35     | 28     | 25     | 28     | 29     |        |        |        |        |         |         |         | 20      | 10.6        | 40       | 21.2         | 23      | 7                 | 12        | 6.3       | 63        | 33.3      | 109          | 57.7         | 4         | 2.1       | 97       | 51.3     | 92         | 48.7       | 
| 01M019 | P.S. 019 ASHER LEVY       | 20052006   | 61.5       |             | 402              | 15   | 43 | 55     | 53     | 68     | 59     | 64     | 45     |        |        |        |         |         |         | 37      | 9.2         | 93       | 23.1         | 7       | 37                | 40        | 10        | 103       | 25.6      | 207          | 51.5         | 39        | 9.7       | 214      | 53.2     | 188        | 46.8       | 
| 01M019 | P.S. 019 ASHER LEVY       | 20062007   | 61.5       |             | 312              | 13   | 37 | 45     | 52     | 47     | 61     | 57     |        |        |        |        |         |         |         | 30      | 9.6         | 72       | 23.1         | 13      | 22                | 30        | 9.6       | 70        | 22.4      | 172          | 55.1         | 19        | 6.1       | 157      | 50.3     | 155        | 49.7       | 
| 01M019 | P.S. 019 ASHER LEVY       | 20072008   | 61.5       |             | 338              | 28   | 48 | 46     | 47     | 53     | 48     | 68     |        |        |        |        |         |         |         | 40      | 11.8        | 75       | 22.2         | 12      | 19                | 42        | 12.4      | 72        | 21.3      | 186          | 55           | 22        | 6.5       | 162      | 47.9     | 176        | 52.1       | 
```