# Active Uniform Staff By Rank And Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-uniform-staff-by-rank-and-gender-6dda6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6dn9-qgma) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6dn9-qgma/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6dn9-qgma/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6dn9-qgma |
| Name | Active Uniform Staff By Rank And Gender |
| Attribution | Department of Correction (DOC) |
| Category | City Government |
| Tags | department of correction, doc, rank, warden, deputy, male, female |
| Created | 2013-03-06T14:47:55Z |
| Publication Date | 2013-06-21T20:09:33Z |

## Description

This table represents the percentage of active Uniform Staff by Rank and Gender.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | rank        | Rank       | text      | text        |
| Yes      | numeric metric | male        | Male       | percent   | percent     |
| Yes      | numeric metric | female      | Female     | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6dn9-qgma d:2013-03-06T06:47:56.000Z t:rank="Correction Officer" m:female=55 m:male=45

series e:6dn9-qgma d:2013-03-06T06:47:56.000Z t:rank=Captain m:female=49 m:male=51

series e:6dn9-qgma d:2013-03-06T06:47:56.000Z t:rank="Assistant Deputy Warden" m:female=63 m:male=38
```

## Meta Commands

```ls
metric m:male p:integer l:Male t:dataTypeName=percent

metric m:female p:integer l:Female t:dataTypeName=percent

entity e:6dn9-qgma l:"Active Uniform Staff By Rank And Gender" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/6dn9-qgma

property e:6dn9-qgma t:meta.view v:id=6dn9-qgma v:category="City Government" v:attributionLink=http://www.nyc.gov/html/doc/html/about/032812DOC_at_a_Glance_single_page.pdf v:averageRating=0 v:name="Active Uniform Staff By Rank And Gender" v:attribution="Department of Correction (DOC)"

property e:6dn9-qgma t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6dn9-qgma t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | rank                     | male | female | 
| =========== | ======================== | ==== | ====== | 
| 1362552476  | Correction Officer       | 45   | 55     | 
| 1362552476  | Captain                  | 51   | 49     | 
| 1362552476  | Assistant Deputy Warden  | 38   | 63     | 
| 1362552476  | Deputy Warden            | 24   | 76     | 
| 1362552476  | Deputy Warden in Command | 33   | 67     | 
| 1362552476  | Warden                   | 29   | 71     | 
```