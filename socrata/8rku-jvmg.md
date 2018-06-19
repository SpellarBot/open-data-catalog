# Final Harvest -- ESA Compliance 01042013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/final-harvest-esa-compliance-01042013-b2bfd) |
| Metadata | [Link](https://data.wa.gov/api/views/8rku-jvmg) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/8rku-jvmg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/8rku-jvmg/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 8rku-jvmg |
| Name | Final Harvest -- ESA Compliance 01042013 |
| Created | 2012-12-07T11:30:45Z |
| Publication Date | 2013-01-04T22:09:02Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | esu             | ESU             | text      | text        |
| Yes      | series tag     | category        | Category        | text      | text        |
| Yes      | numeric metric | of_years        | % of Years      | number    | number      |
| Yes      | series tag     | number_of_years | Number of Years | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8rku-jvmg d:2013-01-04T14:07:58.000Z t:category="Years Within ESA Limit" t:esu="Snake River Spring/Summer Chinook" t:number_of_years="14 of 16 years (1995 - 2010)" m:of_years=88

series e:8rku-jvmg d:2013-01-04T14:07:58.000Z t:category="Years Outside ESA Limit" t:esu="Snake River Spring/Summer Chinook" t:number_of_years="14 of 16 years (1995 - 2010)" m:of_years=12

series e:8rku-jvmg d:2013-01-04T14:07:58.000Z t:category="Years Within ESA Limit" t:esu="Snake River Fall Chinook" t:number_of_years="10 of 11 years (2000 - 2010)" m:of_years=91
```

## Meta Commands

```ls
metric m:of_years p:integer l:"% of Years" t:dataTypeName=number

entity e:8rku-jvmg l:"Final Harvest -- ESA Compliance 01042013" t:url=https://data.wa.gov/api/views/8rku-jvmg

property e:8rku-jvmg t:meta.view v:id=8rku-jvmg v:averageRating=0 v:name="Final Harvest -- ESA Compliance 01042013"

property e:8rku-jvmg t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:8rku-jvmg t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | esu                                | category                | of_years | number_of_years              | 
| =========== | ================================== | ======================= | ======== | ============================ | 
| 1357308478  | Snake River Spring/Summer Chinook  | Years Within ESA Limit  | 88       | 14 of 16 years (1995 - 2010) | 
| 1357308478  | Snake River Spring/Summer Chinook  | Years Outside ESA Limit | 12       | 14 of 16 years (1995 - 2010) | 
| 1357308478  | Snake River Fall Chinook           | Years Within ESA Limit  | 91       | 10 of 11 years (2000 - 2010) | 
| 1357308478  | Snake River Fall Chinook           | Years Outside ESA Limit | 9        | 10 of 11 years (2000 - 2010) | 
| 1357308478  | Upper Columbia Spring Chinook      | Years Within ESA Limit  | 83       | 10 of 12 years (1999 - 2010) | 
| 1357308478  | Upper Columbia Spring Chinook      | Years Outside ESA Limit | 17       | 10 of 12 years (1999 - 2010) | 
| 1357308478  | Lower Columbia Fall Tule Chinook   | Years Within ESA Limit  | 83       | 10 of 12 years (1999 - 2010) | 
| 1357308478  | Lower Columbia Fall Tule Chinook   | Years Outside ESA Limit | 17       | 10 of 12 years (1999 - 2010) | 
| 1357308478  | Lower Columbia Fall Bright Chinook | Years Within ESA Limit  | 73       | 8 of 11 years (2000 - 2010)  | 
| 1357308478  | Lower Columbia Fall Bright Chinook | Years Outside ESA Limit | 27       | 8 of 11 years (2000 - 2010)  | 
```