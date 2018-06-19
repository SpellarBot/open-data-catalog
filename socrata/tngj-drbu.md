# Target Community District

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/target-community-district-faca2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tngj-drbu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tngj-drbu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tngj-drbu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tngj-drbu |
| Name | Target Community District |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, law, contact, justice, programs, cd, community district |
| Created | 2013-02-12T17:42:56Z |
| Publication Date | 2013-06-21T20:07:02Z |

## Description

The Table representing "Target Community District Probation Demographic Data" as of 08/05/2011

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                            | Data Type | Render Type |
| ======== | ============== | ============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | borough_name                   | Borough Name                    | text      | text        |
| Yes      | series tag     | community_district             | Community District              | text      | text        |
| Yes      | numeric metric | total_probationers_ages_16_24  | Total Probationers Ages 16 - 24 | number    | number      |
| Yes      | numeric metric | male_probationers_ages_16_24   | Male Probationers Ages 16-24    | number    | number      |
| Yes      | numeric metric | female_probationers_ages_16_24 | Female Probationers Ages 16-24  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tngj-drbu d:2013-02-12T09:42:57.000Z t:borough_name=Brooklyn t:community_district="CD 3" m:male_probationers_ages_16_24=239 m:total_probationers_ages_16_24=289 m:female_probationers_ages_16_24=50

series e:tngj-drbu d:2013-02-12T09:42:57.000Z t:borough_name=Brooklyn t:community_district="CD 4" m:male_probationers_ages_16_24=119 m:total_probationers_ages_16_24=143 m:female_probationers_ages_16_24=24

series e:tngj-drbu d:2013-02-12T09:42:57.000Z t:borough_name=Brooklyn t:community_district="CD 5" m:male_probationers_ages_16_24=229 m:total_probationers_ages_16_24=263 m:female_probationers_ages_16_24=34
```

## Meta Commands

```ls
metric m:total_probationers_ages_16_24 p:integer l:"Total Probationers Ages 16 - 24" t:dataTypeName=number

metric m:male_probationers_ages_16_24 p:integer l:"Male Probationers Ages 16-24" t:dataTypeName=number

metric m:female_probationers_ages_16_24 p:integer l:"Female Probationers Ages 16-24" t:dataTypeName=number

entity e:tngj-drbu l:"Target Community District" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/tngj-drbu

property e:tngj-drbu t:meta.view v:id=tngj-drbu v:category="City Government" v:attributionLink=http://www.nyc.gov/html/prob/downloads/pdf/yajp_rfp_addendum_1.pdf v:averageRating=0 v:name="Target Community District" v:attribution="Department of Probation (DOP)"

property e:tngj-drbu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tngj-drbu t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | borough_name | community_district | total_probationers_ages_16_24 | male_probationers_ages_16_24 | female_probationers_ages_16_24 | 
| =========== | ============ | ================== | ============================= | ============================ | ============================== | 
| 1360662177  | Brooklyn     | CD 3               | 289                           | 239                          | 50                             | 
| 1360662177  | Brooklyn     | CD 4               | 143                           | 119                          | 24                             | 
| 1360662177  | Brooklyn     | CD 5               | 263                           | 229                          | 34                             | 
| 1360662177  | Brooklyn     | CD 8               | 131                           | 111                          | 20                             | 
| 1360662177  | Brooklyn     | CD 13              | 87                            | 66                           | 21                             | 
| 1360662177  | Brooklyn     | CD 16              | 198                           | 161                          | 37                             | 
| 1360662177  | Bronx        | CD 1               | 193                           | 161                          | 32                             | 
| 1360662177  | Bronx        | CD 2               | 113                           | 96                           | 17                             | 
| 1360662177  | Bronx        | CD 3               | 183                           | 155                          | 28                             | 
| 1360662177  | Bronx        | CD 4               | 236                           | 204                          | 32                             | 
```