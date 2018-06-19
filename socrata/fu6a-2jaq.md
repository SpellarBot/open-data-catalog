# Department of Public Safety Weekly Population Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-public-safety-weekly-population-reports-4ce59) |
| Metadata | [Link](https://data.hawaii.gov/api/views/fu6a-2jaq) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/fu6a-2jaq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/fu6a-2jaq/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | fu6a-2jaq |
| Name | Department of Public Safety Weekly Population Reports |
| Category | Public Safety |
| Created | 2013-11-21T00:38:35Z |
| Publication Date | 2013-11-21T01:24:34Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type     | Render Type   |
| ======== | ============== | ================== | ==================== | ============= | ============= |
| Yes      | time           | date               | Date                 | calendar_date | calendar_date |
| Yes      | series tag     | count              | Count                | text          | text          |
| Yes      | series tag     | facility           | Facility             | text          | text          |
| Yes      | series tag     | location           | Location             | text          | text          |
| Yes      | series tag     | count_type         | Count Type           | text          | text          |
| Yes      | numeric metric | total_count        | Total Count          | number        | number        |
| Yes      | numeric metric | total_count_male   | Total Count (Male)   | number        | number        |
| Yes      | numeric metric | total_count_female | Total Count (Female) | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fu6a-2jaq d:2012-07-02T00:00:00.000Z t:count_type="Assigned Count" t:facility=WCF t:count=Weekly t:location=Hawaii m:total_count_male=290 m:total_count_female=0 m:total_count=290

series e:fu6a-2jaq d:2012-07-02T00:00:00.000Z t:count_type="Assigned Count" t:facility=WCCC t:count=Weekly t:location=Hawaii m:total_count_male=0 m:total_count_female=330 m:total_count=330

series e:fu6a-2jaq d:2012-07-02T00:00:00.000Z t:count_type="Assigned Count" t:facility="Saguaro CC, AZ" t:count=Weekly t:location=Mainland m:total_count_male=0 m:total_count_female=0 m:total_count=0
```

## Meta Commands

```ls
metric m:total_count p:integer l:"Total Count" t:dataTypeName=number

metric m:total_count_male p:integer l:"Total Count (Male)" t:dataTypeName=number

metric m:total_count_female p:integer l:"Total Count (Female)" t:dataTypeName=number

entity e:fu6a-2jaq l:"Department of  Public Safety Weekly Population Reports" t:url=https://data.hawaii.gov/api/views/fu6a-2jaq

property e:fu6a-2jaq t:meta.view v:id=fu6a-2jaq v:category="Public Safety" v:averageRating=0 v:name="Department of  Public Safety Weekly Population Reports"

property e:fu6a-2jaq t:meta.view.owner v:id=trij-xrnq v:profileImageUrlMedium=/api/users/trij-xrnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/trij-xrnq/profile_images/LARGE v:screenName="Meredith Slota" v:profileImageUrlSmall=/api/users/trij-xrnq/profile_images/TINY v:lastNotificationSeenAt=1492637852 v:displayName="Meredith Slota"

property e:fu6a-2jaq t:meta.view.tableauthor v:id=trij-xrnq v:profileImageUrlMedium=/api/users/trij-xrnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/trij-xrnq/profile_images/LARGE v:screenName="Meredith Slota" v:profileImageUrlSmall=/api/users/trij-xrnq/profile_images/TINY v:lastNotificationSeenAt=1492637852 v:displayName="Meredith Slota"
```

## Top Records

```ls
| date                | count  | facility        | location | count_type     | total_count | total_count_male | total_count_female | 
| =================== | ====== | =============== | ======== | ============== | =========== | ================ | ================== | 
| 2012-07-02T00:00:00 | Weekly | WCF             | Hawaii   | Assigned Count | 290         | 290              | 0                  | 
| 2012-07-02T00:00:00 | Weekly | WCCC            | Hawaii   | Assigned Count | 330         | 0                | 330                | 
| 2012-07-02T00:00:00 | Weekly | Saguaro CC, AZ  | Mainland | Assigned Count | 0           | 0                | 0                  | 
| 2012-07-02T00:00:00 | Weekly | Red Rock CC, AZ | Mainland | Assigned Count | 0           | 0                | 0                  | 
| 2012-07-02T00:00:00 | Weekly | OCCC            | Hawaii   | Assigned Count | 1604        | 1398             | 206                | 
| 2012-07-02T00:00:00 | Weekly | MCCC            | Hawaii   | Assigned Count | 385         | 329              | 56                 | 
| 2012-07-02T00:00:00 | Weekly | KCCC            | Hawaii   | Assigned Count | 207         | 167              | 40                 | 
| 2012-07-02T00:00:00 | Weekly | HMSF            | Hawaii   | Assigned Count | 1034        | 1034             | 0                  | 
| 2012-07-02T00:00:00 | Weekly | HCCC            | Hawaii   | Assigned Count | 559         | 467              | 92                 | 
| 2012-07-02T00:00:00 | Weekly | Federal Det Ctr | Hawaii   | Assigned Count | 0           | 0                | 0                  | 
```