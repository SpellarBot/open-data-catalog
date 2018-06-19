# Average Salaries In Department Of Correction

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/average-salaries-in-department-of-correction-4257b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pf7i-ims3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pf7i-ims3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pf7i-ims3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pf7i-ims3 |
| Name | Average Salaries In Department Of Correction |
| Attribution | Department of Correction (DOC) |
| Category | City Government |
| Tags | department of correction, doc, salaries |
| Created | 2013-03-06T14:35:37Z |
| Publication Date | 2013-06-21T20:07:39Z |

## Description

This table represents the average salaries of uniformed and civilian staff

## Columns

```ls
| Included | Schema Type    | Field Name     | Name             | Data Type | Render Type |
| ======== | ============== | ============== | ================ | ========= | =========== |
| No       | time           | :updated_at    | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | rank           | Rank             | text      | text        |
| Yes      | numeric metric | base_salary    | Base Salary      | money     | money       |
| Yes      | numeric metric | loaded_fringes | Loaded + Fringes | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pf7i-ims3 d:2013-03-06T06:35:38.000Z t:rank="Correction Officer" m:base_salary=69862 m:loaded_fringes=137747

series e:pf7i-ims3 d:2013-03-06T06:35:38.000Z t:rank=Captain m:base_salary=90801 m:loaded_fringes=175238

series e:pf7i-ims3 d:2013-03-06T06:35:38.000Z t:rank="Assistant Deputy Warden" m:base_salary=110762 m:loaded_fringes=216784
```

## Meta Commands

```ls
metric m:base_salary p:double l:"Base Salary" t:dataTypeName=money

metric m:loaded_fringes p:double l:"Loaded + Fringes" t:dataTypeName=money

entity e:pf7i-ims3 l:"Average Salaries In Department Of Correction" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/pf7i-ims3

property e:pf7i-ims3 t:meta.view v:id=pf7i-ims3 v:category="City Government" v:attributionLink=http://www.nyc.gov/html/doc/html/about/032812DOC_at_a_Glance_single_page.pdf v:averageRating=0 v:name="Average Salaries In Department Of Correction" v:attribution="Department of Correction (DOC)"

property e:pf7i-ims3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pf7i-ims3 t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | rank                    | base_salary | loaded_fringes | 
| =========== | ======================= | =========== | ============== | 
| 1362551738  | Correction Officer      | 69862.00    | 137747.00      | 
| 1362551738  | Captain                 | 90801.00    | 175238.00      | 
| 1362551738  | Assistant Deputy Warden | 110762.00   | 216784.00      | 
| 1362551738  | Deputy Warden/ DWIC     | 134664.00   | 260906.00      | 
| 1362551738  | Warden                  | 171196.00   | 306864.00      | 
```