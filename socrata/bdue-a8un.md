# Prioritization Log

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/prioritization-log) |
| Metadata | [Link](https://data.oregon.gov/api/views/bdue-a8un) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/bdue-a8un/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/bdue-a8un/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | bdue-a8un |
| Name | Prioritization Log |
| Created | 2016-10-13T16:55:35Z |
| Publication Date | 2016-10-13T20:27:22Z |

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type      | Render Type    |
| ======== | =========== | ============ | ============ | ============== | ============== |
| No       | time        | :updated_at  | updated_at   | meta_data      | meta_data      |
| No       |             | q1           | Q1           | drop_down_list | drop_down_list |
| No       |             | q2           | Q2           | drop_down_list | drop_down_list |
| No       |             | q3           | Q3           | drop_down_list | drop_down_list |
| No       |             | q4           | Q4           | drop_down_list | drop_down_list |
| No       |             | q5           | Q5           | drop_down_list | drop_down_list |
| Yes      | series tag  | project_name | Project Name | text           | text           |
| Yes      | series tag  | required     | Required     | drop_down_list | drop_down_list |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = q1,q2,q3,q4,q5
```

## Data Commands

```ls
series e:bdue-a8un d:2016-10-13T18:23:49.000Z t:project_name="Rapid Application Deployment" t:required=23qh-p2qj m:row_number.bdue-a8un=1

series e:bdue-a8un d:2016-10-13T18:23:59.000Z t:project_name="Open Government" t:required=23qh-p2qj m:row_number.bdue-a8un=2

series e:bdue-a8un d:2016-10-13T18:32:30.000Z t:project_name="Mars Landing" t:required=hq2x-m5fa m:row_number.bdue-a8un=3
```

## Meta Commands

```ls
metric m:row_number.bdue-a8un p:long l:"Row Number"

entity e:bdue-a8un l:"Prioritization Log" t:url=https://data.oregon.gov/api/views/bdue-a8un

property e:bdue-a8un t:meta.view v:id=bdue-a8un v:averageRating=0 v:name="Prioritization Log"

property e:bdue-a8un t:meta.view.owner v:id=yr5y-ep82 v:profileImageUrlMedium=/api/users/yr5y-ep82/profile_images/THUMB v:profileImageUrlLarge=/api/users/yr5y-ep82/profile_images/LARGE v:screenName="Jason Rood" v:profileImageUrlSmall=/api/users/yr5y-ep82/profile_images/TINY v:displayName="Jason Rood"

property e:bdue-a8un t:meta.view.tableauthor v:id=yr5y-ep82 v:profileImageUrlMedium=/api/users/yr5y-ep82/profile_images/THUMB v:profileImageUrlLarge=/api/users/yr5y-ep82/profile_images/LARGE v:screenName="Jason Rood" v:profileImageUrlSmall=/api/users/yr5y-ep82/profile_images/TINY v:roleName=publisher v:displayName="Jason Rood"
```

## Top Records

```ls
| :updated_at | q1        | q2        | q3        | q4        | q5        | project_name                 | required  | 
| =========== | ========= | ========= | ========= | ========= | ========= | ============================ | ========= | 
| 1476383029  | vqt7-gnys | n5eg-k8jv | qrpx-i2rx | utq7-virf | y739-dteu | Rapid Application Deployment | 23qh-p2qj | 
| 1476383039  | zi8d-keyd | ux9p-5ynb | 3eq5-xxnj | uvge-cjwd | qyxb-pv5a | Open Government              | 23qh-p2qj | 
| 1476383550  | jvea-2shg | u77d-fdnr | wj82-4sqv | uvge-cjwd | y739-dteu | Mars Landing                 | hq2x-m5fa | 
| 1476383564  | vqt7-gnys | ux9p-5ynb | qrpx-i2rx | utq7-virf | qyxb-pv5a | Traffic Monitoring           | hq2x-m5fa | 
| 1476383593  | vqt7-gnys | u77d-fdnr | wj82-4sqv | uvge-cjwd | awgj-4mea | Cloud                        | 23qh-p2qj | 
| 1476383858  | jvea-2shg | u77d-fdnr | yddj-774m | 2s2c-dpa7 | awgj-4mea | OSCIO Mascot                 | 23qh-p2qj | 
| 1476390346  | vqt7-gnys | qhym-ksp5 | wj82-4sqv | utq7-virf | qyxb-pv5a | Government Bingo             | 23qh-p2qj | 
| 1476390356  | bham-d3ue | ikti-p5qm | qrpx-i2rx | utq7-virf | qyxb-pv5a | Business Intellegence        | 23qh-p2qj | 
| 1476390438  | vqt7-gnys | ikti-p5qm | qrpx-i2rx | gda6-kw5v | awgj-4mea | IT Asset Management          | 23qh-p2qj | 
```