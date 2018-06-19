# Medical Examiner - Burial Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-burial-locations-762b2) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/hc2f-evny) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hc2f-evny/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hc2f-evny/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | hc2f-evny |
| Name | Medical Examiner - Burial Locations |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2014-08-01T15:51:49Z |
| Publication Date | 2016-12-22T23:24:51Z |

## Description

The following page lists the final disposition sites of the indigents buried by the Cook County Medical Examiner?s Office. Homewood Memorial Gardens Cemetery provides Latitude and Longitude coordinates. Mount Olivet provides Grave, Lot, and Block locations.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | case             | Case             | text          | text          |
| Yes      | series tag     | name             | Name             | text          | text          |
| Yes      | numeric metric | age              | Age              | number        | number        |
| Yes      | series tag     | sex              | Sex              | text          | text          |
| Yes      | series tag     | race             | Race             | text          | text          |
| No       |                | date_of_death    | Date of Death    | calendar_date | calendar_date |
| Yes      | time           | burial_date      | Burial Date      | calendar_date | calendar_date |
| Yes      | series tag     | cemetery         | Cemetery         | text          | text          |
| No       |                | cemetery_address | Cemetery Address | text          | text          |
| Yes      | numeric metric | grave            | Grave            | number        | number        |
| Yes      | series tag     | lot              | Lot              | text          | number        |
| Yes      | series tag     | block            | Block            | text          | number        |
| No       |                | longitude        | Longitude        | number        | number        |
| No       |                | latitude         | Latitude         | number        | number        |
```

## Time Field

```ls
Value = burial_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_of_death,cemetery_address,longitude,latitude
```

## Data Commands

```ls
series e:hc2f-evny d:2016-11-10T00:00:00.000Z t:sex=U t:name=Unknown t:cemetery="Mount Olivet" t:lot=17 t:block=2 t:case="114 Jan 14" t:race=U m:grave=9

series e:hc2f-evny d:2016-11-10T00:00:00.000Z t:sex=M t:name=Unknown t:cemetery="Mount Olivet" t:lot=18 t:block=2 t:case=ME2015-04223 t:race=B m:grave=9

series e:hc2f-evny d:2016-11-10T00:00:00.000Z t:sex=F t:name=Unknown t:cemetery="Mount Olivet" t:lot=18 t:case=ME2015-04985 t:race=W m:grave=10
```

## Meta Commands

```ls
metric m:age p:integer l:Age t:dataTypeName=number

metric m:grave p:integer l:Grave t:dataTypeName=number

entity e:hc2f-evny l:"Medical Examiner - Burial Locations" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/hc2f-evny

property e:hc2f-evny t:meta.view v:id=hc2f-evny v:category=Healthcare v:attributionLink=http://www.cookcountyil.gov/medical-examiner/ v:averageRating=0 v:name="Medical Examiner - Burial Locations" v:attribution="Cook County Medical Examiner"

property e:hc2f-evny t:meta.view.owner v:id=bsrr-d69s v:screenName=amayorga v:displayName=amayorga

property e:hc2f-evny t:meta.view.tableauthor v:id=bsrr-d69s v:screenName=amayorga v:roleName=editor v:displayName=amayorga
```

## Top Records

```ls
| case         | name             | age | sex | race | date_of_death       | burial_date         | cemetery     | cemetery_address                   | grave | lot | block | longitude | latitude | 
| ============ | ================ | === | === | ==== | =================== | =================== | ============ | ================================== | ===== | === | ===== | ========= | ======== | 
| 114 Jan 14   | Unknown          |     | U   | U    | 2014-01-08T00:00:00 | 2016-11-10T00:00:00 | Mount Olivet | 2755 W 111th St, Chicago, IL 60655 | 9     | 17  | 2     |           |          | 
| ME2015-04223 | Unknown          |     | M   | B    | 2015-10-01T00:00:00 | 2016-11-10T00:00:00 | Mount Olivet | 2755 W 111th St, Chicago, IL 60655 | 9     | 18  | 2     |           |          | 
| ME2015-04985 | Unknown          |     | F   | W    | 2015-11-18T00:00:00 | 2016-11-10T00:00:00 | Mount Olivet | 2755 W 111th St, Chicago, IL 60655 | 10    | 18  |       |           |          | 
| ME2016-01223 | BABY BOY WELCH   | 0   | M   | W    | 2016-03-10T00:00:00 | 2016-11-10T00:00:00 | Mount Olivet | 2755 W 111th St, Chicago, IL 60655 | 4     | 21  | 9     |           |          | 
| ME2016-03538 | BABY GIRL PILEKA | 0   | F   | W    | 2016-07-21T00:00:00 | 2016-11-10T00:00:00 | Mount Olivet | 2755 W 111th St, Chicago, IL 60655 | 4     | 21  | 9     |           |          | 
| 442 MAY 14   | VRENI MENDOZA    | 71  | F   | W    | 2014-04-22T00:00:00 | 2016-11-10T00:00:00 | Mount Olivet | 2755 W 111th St, Chicago, IL 60655 | 4     | 18  | 4     |           |          | 
| 426 JUL 14   | MARC CARTER      | 61  | M   | B    | 2014-07-24T00:00:00 | 2016-11-10T00:00:00 | Mount Olivet | 2755 W 111th St, Chicago, IL 60655 | 4     | 18  | 4     |           |          | 
| 372 JUN 14   | VIVIAN GREER     | 77  | F   | B    | 2014-06-22T00:00:00 | 2016-11-10T00:00:00 | Mount Olivet | 2755 W 111th St, Chicago, IL 60655 | 4     | 18  | 4     |           |          | 
| 292 JUN 14   | SAEID EMAD       | 63  | M   | W    | 2014-06-14T00:00:00 | 2016-11-10T00:00:00 | Mount Olivet | 2755 W 111th St, Chicago, IL 60655 | 4     | 18  | 4     |           |          | 
| 181 JUN 14   | FRANTISKA SMRCKA | 58  | M   | W    | 2014-06-11T00:00:00 | 2016-11-10T00:00:00 | Mount Olivet | 2755 W 111th St, Chicago, IL 60655 | 4     | 18  | 4     |           |          | 
```