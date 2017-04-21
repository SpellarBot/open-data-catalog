# Medical Examiner Indigent Cremations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-indigent-cremations-b8572) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/f9wk-2wb9) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/f9wk-2wb9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/f9wk-2wb9/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | f9wk-2wb9 |
| Name | Medical Examiner Indigent Cremations |
| Attribution | Cook County Medical Examiner |
| Tags | cremation, indigent |
| Created | 2014-12-03T22:58:44Z |
| Publication Date | 2017-03-09T23:20:36Z |

## Description

The following page lists the unclaimed indigents cremated by the Cook County Medical Examiner?s Office.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | case           | Case           | text          | text          |
| Yes      | series tag     | name           | Name           | text          | text          |
| Yes      | numeric metric | age            | Age            | number        | number        |
| Yes      | series tag     | sex            | Sex            | text          | text          |
| Yes      | series tag     | race           | Race           | text          | text          |
| Yes      | time           | date_of_death  | Date of Death  | calendar_date | calendar_date |
| No       |                | cremation_date | Cremation Date | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_of_death
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = cremation_date
```

## Data Commands

```ls
series e:f9wk-2wb9 d:2016-12-29T00:00:00.000Z t:sex=MALE t:name="MITCHEL MCBRYDE" t:case=ST2017-00016 t:race=BLACK m:age=81

series e:f9wk-2wb9 d:2017-01-07T00:00:00.000Z t:sex=FEMALE t:name="YOLONZA HOGAN" t:case=ST2017-00015 t:race=BLACK m:age=59

series e:f9wk-2wb9 d:2017-01-20T00:00:00.000Z t:sex=MALE t:name="HOWARD GOLD" t:case=ME2017-00352 t:race=WHITE m:age=53
```

## Meta Commands

```ls
metric m:age p:integer l:Age t:dataTypeName=number

entity e:f9wk-2wb9 l:"Medical Examiner Indigent Cremations" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/f9wk-2wb9

property e:f9wk-2wb9 t:meta.view v:id=f9wk-2wb9 v:attributionLink=http://www.cookcountyil.gov/medical-examiner/ v:averageRating=0 v:name="Medical Examiner Indigent Cremations" v:attribution="Cook County Medical Examiner"

property e:f9wk-2wb9 t:meta.view.owner v:id=bsrr-d69s v:screenName=amayorga v:displayName=amayorga

property e:f9wk-2wb9 t:meta.view.tableauthor v:id=bsrr-d69s v:screenName=amayorga v:roleName=editor v:displayName=amayorga
```

## Top Records

```ls
| case         | name             | age | sex    | race  | date_of_death       | cremation_date      | 
| ============ | ================ | === | ====== | ===== | =================== | =================== | 
| ST2017-00016 | MITCHEL MCBRYDE  | 81  | MALE   | BLACK | 2016-12-29T00:00:00 | 2017-03-08T00:00:00 | 
| ST2017-00015 | YOLONZA HOGAN    | 59  | FEMALE | BLACK | 2017-01-07T00:00:00 | 2017-03-08T00:00:00 | 
| ME2017-00352 | HOWARD GOLD      | 53  | MALE   | WHITE | 2017-01-20T00:00:00 | 2017-03-08T00:00:00 | 
| ME2017-00305 | MARION DANIEL    | 89  | MALE   | WHITE | 2017-01-18T00:00:00 | 2017-03-08T00:00:00 | 
| ME2017-00293 | STANLEY MATELSKI |     | MALE   | WHITE | 2017-01-17T00:00:00 | 2017-03-08T00:00:00 | 
| ME2017-00365 | MARTIN CISNEROS  | 49  | MALE   | WHITE | 2017-01-21T00:00:00 | 2017-03-03T00:00:00 | 
| ST2017-00014 | DELORES BELLMORE | 89  | FEMALE | WHITE | 2017-01-11T00:00:00 | 2017-03-02T00:00:00 | 
| ST2017-00011 | JOHN SOTOS       | 57  | MALE   | WHITE | 2016-12-15T00:00:00 | 2017-03-02T00:00:00 | 
| ST2017-00018 | ROBERT SUNDQUIST | 86  | MALE   | WHITE | 2016-11-20T00:00:00 | 2017-03-01T00:00:00 | 
| ME2017-00346 | CONNIE WILLIAMS  | 41  | FEMALE | BLACK | 2017-01-20T00:00:00 | 2017-03-01T00:00:00 | 
```