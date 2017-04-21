# 2014 ELECTION

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-election) |
| Metadata | [Link](https://data.ct.gov/api/views/udtt-rx7n) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/udtt-rx7n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/udtt-rx7n/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | udtt-rx7n |
| Name | 2014 ELECTION |
| Category | Government |
| Tags | election |
| Created | 2014-12-16T15:50:02Z |
| Publication Date | 2015-07-14T21:23:20Z |

## Description

2014 ELECTION STAMFORD

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | office_name_of_candidate | OFFICE/Name of Candidate | text      | text        |
| Yes      | series tag     | party                    | Party                    | text      | text        |
| Yes      | numeric metric | dist_1                   | Dist 1                   | number    | number      |
| Yes      | numeric metric | dist_2                   | Dist 2                   | number    | number      |
| Yes      | numeric metric | dist_3                   | Dist 3                   | number    | number      |
| Yes      | numeric metric | dist_4                   | Dist 4                   | number    | number      |
| Yes      | numeric metric | dist_5                   | Dist 5                   | number    | number      |
| Yes      | numeric metric | dist_6                   | Dist 6                   | number    | number      |
| Yes      | numeric metric | dist_7                   | Dist 7                   | number    | number      |
| Yes      | numeric metric | dist_8                   | Dist 8                   | number    | number      |
| Yes      | numeric metric | dist_9                   | Dist 9                   | number    | number      |
| Yes      | numeric metric | dist_10                  | Dist 10                  | number    | number      |
| Yes      | numeric metric | dist_11                  | Dist 11                  | number    | number      |
| Yes      | numeric metric | dist_12                  | Dist 12                  | number    | number      |
| Yes      | numeric metric | dist_13                  | Dist 13                  | number    | number      |
| Yes      | numeric metric | dist_14                  | Dist 14                  | number    | number      |
| Yes      | numeric metric | dist_15                  | Dist 15                  | number    | number      |
| Yes      | numeric metric | dist_16                  | Dist 16                  | number    | number      |
| Yes      | numeric metric | dist_17                  | Dist 17                  | number    | number      |
| Yes      | numeric metric | dist_18                  | Dist 18                  | number    | number      |
| Yes      | numeric metric | dist_19                  | Dist 19                  | number    | number      |
| Yes      | numeric metric | dist_20                  | Dist 20                  | number    | number      |
| Yes      | numeric metric | dist_21                  | Dist 21                  | number    | number      |
| Yes      | numeric metric | dist_22                  | Dist 22                  | number    | number      |
| Yes      | numeric metric | total                    | Total                    | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:udtt-rx7n d:2014-01-01T00:00:00.000Z t:office_name_of_candidate="Machine/Polling Place" m:dist_17=931 m:dist_16=568 m:dist_15=635 m:dist_14=820 m:dist_13=675 m:dist_22=453 m:dist_12=291 m:dist_21=1033 m:dist_11=217 m:dist_10=218 m:dist_20=355 m:dist_9=343 m:dist_5=399 m:dist_6=473 m:dist_7=189 m:dist_8=47 m:dist_1=783 m:dist_2=299 m:dist_3=505 m:dist_4=327 m:dist_18=612 m:dist_19=899

series e:udtt-rx7n d:2014-01-01T00:00:00.000Z t:office_name_of_candidate=Absentee m:dist_17=55 m:dist_16=36 m:dist_15=22 m:dist_14=35 m:dist_13=35 m:dist_22=28 m:dist_12=34 m:dist_21=71 m:dist_11=37 m:dist_10=14 m:dist_20=20 m:dist_9=18 m:dist_5=24 m:dist_6=41 m:dist_7=23 m:dist_8=1 m:dist_1=58 m:dist_2=15 m:dist_3=25 m:dist_4=33 m:dist_18=33 m:dist_19=59

series e:udtt-rx7n d:2014-01-01T00:00:00.000Z t:office_name_of_candidate=Total m:dist_17=986 m:total=11789 m:dist_16=604 m:dist_15=657 m:dist_14=855 m:dist_13=710 m:dist_22=481 m:dist_12=325 m:dist_21=1104 m:dist_11=254 m:dist_10=232 m:dist_20=375 m:dist_9=361 m:dist_5=423 m:dist_6=514 m:dist_7=212 m:dist_8=48 m:dist_1=841 m:dist_2=314 m:dist_3=530 m:dist_4=360 m:dist_18=645 m:dist_19=958
```

## Meta Commands

```ls
metric m:dist_1 p:integer l:"Dist 1" t:dataTypeName=number

metric m:dist_2 p:integer l:"Dist 2" t:dataTypeName=number

metric m:dist_3 p:integer l:"Dist 3" t:dataTypeName=number

metric m:dist_4 p:integer l:"Dist 4" t:dataTypeName=number

metric m:dist_5 p:integer l:"Dist 5" t:dataTypeName=number

metric m:dist_6 p:integer l:"Dist 6" t:dataTypeName=number

metric m:dist_7 p:integer l:"Dist 7" t:dataTypeName=number

metric m:dist_8 p:integer l:"Dist 8" t:dataTypeName=number

metric m:dist_9 p:integer l:"Dist 9" t:dataTypeName=number

metric m:dist_10 p:integer l:"Dist 10" t:dataTypeName=number

metric m:dist_11 p:integer l:"Dist 11" t:dataTypeName=number

metric m:dist_12 p:integer l:"Dist 12" t:dataTypeName=number

metric m:dist_13 p:integer l:"Dist 13" t:dataTypeName=number

metric m:dist_14 p:integer l:"Dist 14" t:dataTypeName=number

metric m:dist_15 p:integer l:"Dist 15" t:dataTypeName=number

metric m:dist_16 p:integer l:"Dist 16" t:dataTypeName=number

metric m:dist_17 p:integer l:"Dist 17" t:dataTypeName=number

metric m:dist_18 p:integer l:"Dist 18" t:dataTypeName=number

metric m:dist_19 p:integer l:"Dist 19" t:dataTypeName=number

metric m:dist_20 p:integer l:"Dist 20" t:dataTypeName=number

metric m:dist_21 p:integer l:"Dist 21" t:dataTypeName=number

metric m:dist_22 p:integer l:"Dist 22" t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:udtt-rx7n l:"2014 ELECTION" t:url=https://data.ct.gov/api/views/udtt-rx7n

property e:udtt-rx7n t:meta.view v:id=udtt-rx7n v:category=Government v:averageRating=0 v:name="2014 ELECTION"

property e:udtt-rx7n t:meta.view.owner v:id=d2jw-b5qp v:screenName="City of Stamford" v:displayName="City of Stamford"

property e:udtt-rx7n t:meta.view.tableauthor v:id=d2jw-b5qp v:screenName="City of Stamford" v:roleName=publisher v:displayName="City of Stamford"
```

## Top Records

```ls
| office_name_of_candidate | party | dist_1 | dist_2 | dist_3 | dist_4 | dist_5 | dist_6 | dist_7 | dist_8 | dist_9 | dist_10 | dist_11 | dist_12 | dist_13 | dist_14 | dist_15 | dist_16 | dist_17 | dist_18 | dist_19 | dist_20 | dist_21 | dist_22 | total | 
| ======================== | ===== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ===== | 
| Machine/Polling Place    |       | 783    | 299    | 505    | 327    | 399    | 473    | 189    | 47     | 343    | 218     | 217     | 291     | 675     | 820     | 635     | 568     | 931     | 612     | 899     | 355     | 1033    | 453     |       | 
| Absentee                 |       | 58     | 15     | 25     | 33     | 24     | 41     | 23     | 1      | 18     | 14      | 37      | 34      | 35      | 35      | 22      | 36      | 55      | 33      | 59      | 20      | 71      | 28      |       | 
| Total                    |       | 841    | 314    | 530    | 360    | 423    | 514    | 212    | 48     | 361    | 232     | 254     | 325     | 710     | 855     | 657     | 604     | 986     | 645     | 958     | 375     | 1104    | 481     | 11789 | 
| Malloy/Wyman             | Dem   |        |        |        |        |        |        |        |        |        |         |         |         |         |         |         |         |         |         |         |         |         |         |       | 
| Machine/Polling Place    |       | 1119   | 635    | 624    | 539    | 830    | 1125   | 370    | 101    | 1094   | 1002    | 426     | 376     | 783     | 1023    | 873     | 618     | 827     | 625     | 758     | 350     | 1148    | 467     |       | 
| Absentee                 |       | 53     | 35     | 29     | 63     | 31     | 80     | 44     | 7      | 67     | 62      | 57      | 21      | 49      | 57      | 36      | 43      | 78      | 47      | 67      | 38      | 96      | 16      |       | 
| Total                    |       | 1172   | 670    | 653    | 602    | 861    | 1205   | 414    | 108    | 1161   | 1064    | 483     | 397     | 832     | 1080    | 909     | 661     | 905     | 672     | 825     | 388     | 1244    | 483     | 16789 | 
| Malloy/Wyman             | WFP   |        |        |        |        |        |        |        |        |        |         |         |         |         |         |         |         |         |         |         |         |         |         |       | 
| Machine/Polling Place    |       | 33     | 22     | 20     | 32     | 31     | 31     | 11     | 3      | 45     | 32      | 10      | 12      | 36      | 57      | 42      | 26      | 12      | 30      | 19      | 6       | 31      | 17      |       | 
| Absentee                 |       | 4      | 1      | 0      | 0      | 3      | 4      | 0      | 0      | 5      | 0       | 2       | 0       | 3       | 1       | 0       | 0       | 1       | 1       | 1       | 2       | 5       | 0       |       | 
```