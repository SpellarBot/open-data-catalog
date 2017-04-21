# Advanced Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/advanced-projects) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yiqb-mq9h) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yiqb-mq9h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yiqb-mq9h/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yiqb-mq9h |
| Name | Advanced Projects |
| Attribution | NYC School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, constructions, projects |
| Created | 2016-05-31T21:48:23Z |
| Publication Date | 2016-05-31T21:52:22Z |

## Description

Projects Advanced.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | district         | District         | text      | number      |
| Yes      | series tag  | building_id      | Building ID      | text      | text        |
| Yes      | series tag  | school           | School           | text      | text        |
| Yes      | series tag  | borough          | Borough          | text      | text        |
| Yes      | series tag  | program_category | Program Category | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yiqb-mq9h d:2016-05-31T14:48:33.000Z t:school="P.S. 116" t:building_id=M116 t:program_category="Boiler Conversion" t:borough=M t:district=2 m:row_number.yiqb-mq9h=1

series e:yiqb-mq9h d:2016-05-31T14:48:33.000Z t:school="P.S. 116" t:building_id=M116 t:program_category="Climate Control" t:borough=M t:district=2 m:row_number.yiqb-mq9h=2

series e:yiqb-mq9h d:2016-05-31T14:48:33.000Z t:school="P.S. 198" t:building_id=M198 t:program_category="Boiler Conversion" t:borough=M t:district=2 m:row_number.yiqb-mq9h=3
```

## Meta Commands

```ls
metric m:row_number.yiqb-mq9h p:long l:"Row Number"

entity e:yiqb-mq9h l:"Advanced Projects" t:attribution="NYC School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/yiqb-mq9h

property e:yiqb-mq9h t:meta.view v:id=yiqb-mq9h v:category=Education v:averageRating=0 v:name="Advanced Projects" v:attribution="NYC School Construction Authority (SCA)"

property e:yiqb-mq9h t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yiqb-mq9h t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district | building_id | school                   | borough | program_category      | 
| =========== | ======== | =========== | ======================== | ======= | ===================== | 
| 1464706113  | 2        | M116        | P.S. 116                 | M       | Boiler Conversion     | 
| 1464706113  | 2        | M116        | P.S. 116                 | M       | Climate Control       | 
| 1464706113  | 2        | M198        | P.S. 198                 | M       | Boiler Conversion     | 
| 1464706113  | 2        | M198        | P.S. 198                 | M       | Climate Control       | 
| 1464706113  | 5        | M125        | P.S. 125                 | M       | PA System             | 
| 1464706113  | 7        | X161        | P.S. 161                 | X       | Heating Plant Upgrade | 
| 1464706113  | 10       | X026        | P.S. 396                 | X       | Boiler Conversion     | 
| 1464706113  | 10       | X026        | P.S. 396                 | X       | Climate Control       | 
| 1464706113  | 10       | X832        | P.S. 32 MINISCHOOL       | X       | Ventilation           | 
| 1464706113  | 12       | X129        | I.S. 129 (PAIRED W P234) | X       | Kitchen Areas         | 
```