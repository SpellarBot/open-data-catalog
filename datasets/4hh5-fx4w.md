# Austin Recycles Games District Numbers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-recycles-games-district-numbers) |
| Metadata | [Link](https://data.austintexas.gov/api/views/4hh5-fx4w) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/4hh5-fx4w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/4hh5-fx4w/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 4hh5-fx4w |
| Name | Austin Recycles Games District Numbers |
| Attribution | City of Austin's - Austin Resource Recovery |
| Category | Government |
| Tags | austin recycles games, pounds of recyclables, district |
| Created | 2016-02-11T14:13:32Z |
| Publication Date | 2016-05-17T19:49:58Z |

## Description

The Austin Recycles Games will calculate pounds of recyclables collected per household in each district for the months of December 2015 through March 2016.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name               | Data Type | Render Type |
| ======== | ============== | ================ | ================== | ========= | =========== |
| No       | time           | :updated_at      | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | district         | DISTRICT           | text      | text        |
| Yes      | numeric metric | october_baseline | OCTOBER (Baseline) | number    | number      |
| Yes      | numeric metric | nov_30_to_dec_31 | NOV 30 to DEC 31   | number    | number      |
| Yes      | numeric metric | january          | JANUARY            | number    | number      |
| Yes      | numeric metric | february         | FEBRUARY           | number    | number      |
| Yes      | numeric metric | march            | MAR 1 to APR 1     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4hh5-fx4w d:2016-05-17T12:32:19.000Z t:district="District 1" m:october_baseline=44.17 m:march=42.43 m:nov_30_to_dec_31=44.22 m:february=37 m:january=43.25

series e:4hh5-fx4w d:2016-05-17T12:32:27.000Z t:district="District 2" m:october_baseline=43.79 m:march=41.04 m:nov_30_to_dec_31=59.83 m:february=48.81 m:january=45.12

series e:4hh5-fx4w d:2016-05-17T12:32:42.000Z t:district="District 3" m:october_baseline=46.94 m:march=46.47 m:nov_30_to_dec_31=55.23 m:february=42.62 m:january=54.77
```

## Meta Commands

```ls
metric m:october_baseline p:float l:"OCTOBER (Baseline)" t:dataTypeName=number

metric m:nov_30_to_dec_31 p:float l:"NOV 30 to DEC 31" t:dataTypeName=number

metric m:january p:float l:JANUARY t:dataTypeName=number

metric m:february p:float l:FEBRUARY t:dataTypeName=number

metric m:march p:float l:"MAR 1 to APR 1" t:dataTypeName=number

entity e:4hh5-fx4w l:"Austin Recycles Games District Numbers" t:attribution="City of Austin's - Austin Resource Recovery" t:url=https://data.austintexas.gov/api/views/4hh5-fx4w

property e:4hh5-fx4w t:meta.view v:id=4hh5-fx4w v:category=Government v:attributionLink=http://www.austintexas.gov/games v:averageRating=0 v:name="Austin Recycles Games District Numbers" v:attribution="City of Austin's - Austin Resource Recovery"

property e:4hh5-fx4w t:meta.view.license v:name="Public Domain"

property e:4hh5-fx4w t:meta.view.owner v:id=wna5-wuwp v:screenName=julmisse v:displayName=julmisse

property e:4hh5-fx4w t:meta.view.tableauthor v:id=wna5-wuwp v:screenName=julmisse v:roleName=editor v:displayName=julmisse
```

## Top Records

```ls
| :updated_at | district    | october_baseline   | nov_30_to_dec_31 | january | february | march | 
| =========== | =========== | ================== | ================ | ======= | ======== | ===== | 
| 1463488339  | District 1  | 44.17              | 44.22            | 43.25   | 37       | 42.43 | 
| 1463488347  | District 2  | 43.79              | 59.83            | 45.12   | 48.81    | 41.04 | 
| 1463488362  | District 3  | 46.94              | 55.23            | 54.77   | 42.62    | 46.47 | 
| 1463488370  | District 4  | 45.55              | 63.32            | 42.73   | 38.71    | 50.12 | 
| 1463488377  | District 5  | 40.229999999999997 | 57.75            | 46.88   | 45.24    | 44.75 | 
| 1463488609  | District 6  | 43.63              | 54.69            | 54.57   | 39.92    | 62.65 | 
| 1463488621  | District 7  | 46.34              | 60.53            | 47.19   | 41.77    | 51.51 | 
| 1463488629  | District 8  | 49.54              | 72.94            | 60.57   | 62.71    | 57.08 | 
| 1463488636  | District 9  | 55.9               | 43.91            | 45.81   | 40.27    | 53.53 | 
| 1463488639  | District 10 | 62.29              | 70.69            | 65.39   | 52.57    | 61.61 | 
```