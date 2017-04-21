# Find A Missouri Utility

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/find-a-missouri-utility-a32ff) |
| Metadata | [Link](https://data.mo.gov/api/views/yeiz-h2m2) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/yeiz-h2m2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/yeiz-h2m2/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | yeiz-h2m2 |
| Name | Find A Missouri Utility |
| Created | 2014-06-23T16:08:27Z |
| Publication Date | 2014-06-23T16:09:20Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | city        | CITY       | text      | text        |
| Yes      | series tag  | county      | COUNTY     | text      | text        |
| Yes      | series tag  | map         | MAP        | text      | text        |
| Yes      | series tag  | e_type      | E-Type     | text      | text        |
| Yes      | series tag  | electric    | ELECTRIC   | text      | text        |
| Yes      | series tag  | e_division  | E-Division | text      | text        |
| Yes      | series tag  | g_type      | G-Type     | text      | text        |
| Yes      | series tag  | gas         | GAS        | text      | text        |
| Yes      | series tag  | area        | Area       | text      | text        |
| Yes      | series tag  | g_division  | G-Division | text      | text        |
| Yes      | series tag  | g_district  | G-District | text      | text        |
| Yes      | series tag  | water       | WATER      | text      | text        |
| Yes      | series tag  | telephone   | TELEPHONE  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yeiz-h2m2 d:2014-06-23T09:08:30.000Z t:county=ADAIR t:electric="TRI-COUNTY ELECTRIC  COOPERATIVE ASSN." t:e_type=COOP t:map=F-1 t:telephone="AT&T MISSOURI" t:city=ADAIR m:row_number.yeiz-h2m2=1

series e:yeiz-h2m2 d:2014-06-23T09:08:30.000Z t:water=MUNICIPAL t:county=ADAIR t:electric="UNION ELECTRIC COMPANY" t:e_type=IOU t:map=F-2 t:telephone="MARK TWAIN" t:city=BRASHEAR m:row_number.yeiz-h2m2=2

series e:yeiz-h2m2 d:2014-06-23T09:08:30.000Z t:county=ADAIR t:electric="TRI-COUNTY ELECTRIC COOPERATIVE ASSN." t:e_type=COOP t:map=E-1 t:telephone="AT&T MISSOURI" t:city=CONNELSVILLE m:row_number.yeiz-h2m2=3
```

## Meta Commands

```ls
metric m:row_number.yeiz-h2m2 p:long l:"Row Number"

entity e:yeiz-h2m2 l:"Find A Missouri Utility" t:url=https://data.mo.gov/api/views/yeiz-h2m2

property e:yeiz-h2m2 t:meta.view v:id=yeiz-h2m2 v:averageRating=0 v:name="Find A Missouri Utility"

property e:yeiz-h2m2 t:meta.view.owner v:id=xfqs-bcyn v:screenName=whitwo v:displayName=whitwo

property e:yeiz-h2m2 t:meta.view.tableauthor v:id=xfqs-bcyn v:screenName=whitwo v:roleName=editor v:displayName=whitwo
```

## Top Records

```ls
| :updated_at | city           | county | map | e_type | electric                              | e_division | g_type | gas                      | area | g_division | g_district | water               | telephone     | 
| =========== | ============== | ====== | === | ====== | ===================================== | ========== | ====== | ======================== | ==== | ========== | ========== | =================== | ============= | 
| 1403514510  | ADAIR          | ADAIR  | F-1 | COOP   | TRI-COUNTY ELECTRIC COOPERATIVE ASSN. |            |        |                          |      |            |            |                     | AT&T MISSOURI | 
| 1403514510  | BRASHEAR       | ADAIR  | F-2 | IOU    | UNION ELECTRIC COMPANY                |            |        |                          |      |            |            | MUNICIPAL           | MARK TWAIN    | 
| 1403514510  | CONNELSVILLE   | ADAIR  | E-1 | COOP   | TRI-COUNTY ELECTRIC COOPERATIVE ASSN. |            |        |                          |      |            |            |                     | AT&T MISSOURI | 
| 1403514510  | GIBBS          | ADAIR  | F-2 | IOU    | UNION ELECTRIC COMPANY                |            |        |                          |      |            |            | ADAIR COUNTY PWSD 1 | AT&T MISSOURI | 
| 1403514510  | KIRKSVILLE     | ADAIR  | F-l | IOU    | UNION ELECTRIC COMPANY                |            | IOU    | ATMOS ENERGY CORPORATION | K    | NORTHEAST  | KIRKSVILLE | MUNICIPAL           | AT&T MISSOURI | 
| 1403514510  | MILLARD        | ADAIR  | F-2 | IOU    | UNION ELECTRIC COMPANY                |            |        |                          |      |            |            | ADAIR COUNTY PWSD 1 | AT&T MISSOURI | 
| 1403514510  | NOVINGER       | ADAIR  | E-l | IOU    | UNION ELECTRIC COMPANY                |            |        |                          |      |            |            | MUNICIPAL           | NORTHEAST MO  | 
| 1403514510  | SUBLETTE       | ADAIR  | F-1 | IOU    | UNION ELECTRIC COMPANY                |            |        |                          |      |            |            |                     | AT&T MISSOURI | 
| 1403514510  | WILLMATHSVILLE | ADAIR  | F-1 | COOP   | TRI-COUNTY ELECTRIC COOPERATIVE ASSN. |            |        |                          |      |            |            |                     | MARK TWAIN    | 
| 1403514510  | YARROW         | ADAIR  | E-2 | COOP   | TRI-COUNTY ELECTRIC COOPERATIVE ASSN. |            |        |                          |      |            |            |                     | AT&T MISSOURI | 
```